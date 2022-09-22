---
title: "zshのtimeコマンド"
date: 2022-07-02T23:26:08+09:00
draft: true
---

# timeコマンド

zshではtimeと打つと、時間を計測できる

```
$ time ...
```

# nginxのaccess.logからIPアドレス毎のリクエスト数を見る

ログの場所を確認
```
$ less /etc/nginx/nginx.conf
```
access_logの右に書いている箇所がaccess.logの場所にあたる。

以下のコマンドでIPアドレス毎のリクエスト数が分かる。[参考](https://noauto-nolife.com/post/nginx-log-check-by-awk/)

```
$ less access.log | grep posting/map | awk '{print $1}' | sort | uniq -c | sort -rn
```

