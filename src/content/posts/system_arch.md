---
title: "状態遷移のルールをわかりやすくする"
date: 2022-07-31T15:40:08+09:00
draft: true
---

以下の状態があるとする

```state.rb
module State
  REVIEWING = '審査中'
  APPROVED = '承認済み'
  DISAPPROVED = '承認NG'
  DOING = '実施中'
  FINISHED = '完了'
end
```

1. ある状態から遷移できる状態をマッピングする
2. 遷移元の状態と遷移後の状態を渡して、遷移可能なケースかどうかを1.のマッピングから判定する

```state_transition.rb
class StateTransition
  ALLOWED = {
    State::REVIEWING => [State::APPROVED, State::DISAPPROVED],
    State::APPROVED => [State::DOING, State::FINISHED],
    State::DOING => [State::FINISHED],
    ...
    中略
    ...
  }.freeze

  def can_transit(from:, to:)
    allowed_states = ALLOWED[:from]
    allowed_states.include?(to)
  end
end
```