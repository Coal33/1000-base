# 千字文千進法相互変換ツール

こちらのツイートのソースコードです。
https://twitter.com/Engr_Coal33/status/1341639508656189443

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">千字文を使った千進数に相互変換できるやつをPythonで書いてみた <a href="https://t.co/OHtglK7uMV">https://t.co/OHtglK7uMV</a> <a href="https://t.co/GTMfcIzqTS">pic.twitter.com/GTMfcIzqTS</a></p>&mdash; Coal (@Engr_Coal33) <a href=https://twitter.com/Engr_Coal33/status/1341639508656189443?ref_src=twsrc%5Etfw">December 23, 2020</a></blockquote>

## 実行方法

ダウンロードして、Python で実行してください。

```
$ git clone https://github.com/Coal33/1000-base.git
$ cd 1000-base
$ python3 1000-base.py
```

10 進のアラビア数字を入力すると千字文千進数に、千字文千進数を入力すると 10 進のアラビア数字に変換されます。

実行例

```
$ python3 1000-base.py
5006
5006 => 宇宙
$ python3 1000-base.py
上皇
上皇 => 329080
$ python3 1000-base.py
36037
36037 => 雨露
$ python3 1000-base.py
令和二年
令和二年 => 296330415945
$ python3 1000-base.py
1002079
1002079 => 天地人
```
