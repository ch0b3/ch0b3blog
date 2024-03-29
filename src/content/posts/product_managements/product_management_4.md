---
title: "プロダクトマネジメントプロセス"
date: 2022-10-01T15:53:36+09:00
draft: true
---

# プロダクトマネジメントプロセス

## プロダクトイニシアティブ候補を洗い出す

- 戦略的意図(ビジネスレベルの戦略): 個人ユーザーからの収益を上げたい
  1. 個人ユーザーの新規獲得(指標: User数)
  2. 既存個人ユーザーからのリテンションを上げる(指標: LTV)
  3. 既存個人ユーザーから新たな収入源を作る(指標: ARPU)

1. 個人ユーザーの新規獲得について
会員登録ファネル分析
-> 登録して料金を払うところまでのCVRが低い
-> Qualarooでアンケート
-> 「興味のある講座がない」「スキルが身につくか分からない(信用性が低い)」

2. リテンション
データ分析->半年で40パーセントまで減少
「興味のある講座がない」

そもそもコンテンツ作れてる？
-> 1つしか作れていない
-> ユーザーがどんな講座を求めているか分からない

## -> プロダクトイニシアティブとオプション
- イニシアティブ1
  - サイトで興味のあるコンテンツを増やすことで新規ユーザー獲得とリテンション上げる
- オプション1
  - 簡単に作れるようにする
  - 関心講座を作れるような働きかけ

- イニシアティブ2
  - スキルが身についたかわかるようにする
- オプション2
  - 評価システムの導入
  - 証明書

## プロダクトのカタ

上記の探索はプロダクトのカタに従うとよい。
1. 方向性を理解する
  - ビジョン、戦略的意図、プロダクトイニシアティブ
2. 現状を把握する
  - 1.の目標を達成する上での現状
3. 次の目標を設定する
  - 1.の目標と2.の現状の直線上にあるプロットのうちの一つ目を設定する
4. ステップ選択と実行
  - 問題の探索、ソリューション探索

プロダクトのカタによって、プロダクトイニシアティブとオプションを探索する

## ※価値提案の中心ではないものに時間を費やさない

費用対効果の薄いものには実験や調査の時間をなるべく費やさない。
ECサイトでいえば、購入画面は他のサービスを真似しちゃってもいいよね？

## アイデアを消去法で消す

いいアイデアだけが残るように、調査で必要なかったアイデアを消して行く。

## 成功指標の算出

例えば、以下のような思考回路
- 現在1000万円の売上でCVRが40%
- CVRが30%上がったら
- 750万円売上増加する見込み(1000 * 100/40 * 30/100)

### さまざまな指標
- 海賊指標
- HEART指標

- `指標は複数もつのが良い`  
  - 一つだと簡単に操作できてしまう
  - 先行指標と遅延指標の組み合わせ
  - 先行指標: 計測に時間がかからない
    - アクティベーション(ユーザーがプロダクトを体験するステップ)、エンゲージメント
  - 遅延指標: 計測に時間がかかる
    - リテンション

オプションは先行指標重視する

# 問題の探索

マーケットリーの例

- イニシアティブ
  - ユーザーの関心の多い講座を増やす
- オプションの探索
  - 現状
    - 公開率の低さ
  - 目標
    - 公開率の改善
  - 次のステップ
    - 調査する
    - 公開率の妨げになっていることをユーザーにインタビュー
    - -> 講座をシステムに取り込むのに苦労している
    - -> スムーズに講座をシステムに取り込めるようにした方がいい？

解決したい課題に必要な情報の調査→生成的調査  
ソリューションがユーザーに使いやすい形になっているかの調査→検証的調査  
-> 生成的調査が先に来るべき  

## プロダクトのカタに戻って考える

- 最後のステップ
  - -> 講座をシステムに取り込むのに苦労している
  - -> スムーズに講座をシステムに取り込めるようにした方がいい？
- 目標
  - 公開率の改善
- 現状
  - 講座をシステムに取り込むのに苦労しているのが分かった
- 次の目標
  - なぜ講座をシステムに取り込むのに苦労しているのか知ること
- 次のステップ
  - `5人の講師に代わり、自分たちが実際に講座をシステムに取り込んでみる`
  - -> 講座をシステムに取り込むことよりも、コンテンツを作ることに時間がかかっている

# ソリューションの探索

- 最後のステップ
  - `5人の講師に代わり、自分たちが実際に講座をシステムに取り込んでみる`
  - -> 講座をシステムに取り込むことよりも、コンテンツを作ることに時間がかかっている
- 目標
  - 公開率の改善
- 現状
  - コンテンツを作ることに時間がかかっていることが分かった
- 次の目標
  - `コンテンツを作る時間を短縮すれば公開率の改善になるのか知ること`
- 次のステップ
  - 講師の代わりに実際にコンテンツ作りを手伝ってあげて、講座の公開数が上がるか実験する(コンシェルジュ手法)
  - -> 公開数増えたので、成功

## 実験の手法

MVPとは学習のための最小の労力、実験である
- [ ] MVPの実現の仕方について考える

- コンシェルジュ
  - 概要
    - ユーザーの代わりに手動で機能を再現することで効果があるかを測る
  - メリット
    - ユーザーと密にコミュニケーション取れる
  - デメリット
    - サンプル数に限界がある
- オズの魔法使い
  - 概要
    - モックページを作成し、バックエンドを手動で行う
- コンセプトテスト
  - 概要
    - ワイヤーフレームやデモ動画でコンセプトを紹介する

## ソリューションの選択

ソリューション候補
- フリーランスを雇って動画作成サービスを提供する
- ソフトウェアを作る
- 他社のソフトウェアを組み込む or 連携 or 案内する

動画編集ソフトを試してみる -> 40人の講師に使ってもらう実験
-> 効果あり

# ソリューションの構築と最適化

- カスタマージャーニーとプロトタイプの作成
- 北極星の作成
- ストーリーマッピング
  - 全員が作業を把握
  - 優先順位をつける

- 成功指標作成
  - 利用率: 講師の75%が利用する
  - 公開率: 講座の公開率を60%にする
  - 公開LT: 講座作成が3ヶ月から1ヶ月に短縮される

## 優先順位をつける

- 遅延コスト
  - 価値(重要度)と緊急度の2軸で考える
  - トレードオフの関係

### 完成の定義

- リリースではなく、目標に達成すること？
  - ストーリーはそれで良さそう
  - アウトカムを完成の定義に置く
