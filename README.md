# robosys2022

# plusコマンド
![test](https://github.com/kotasuzuki0526/robosys2022/actions/workflows/test.yml/badge.svg)

* 標準入力から読み込んだ数字を足し、結果を出力します.
## 使い方
* `seq n` と `./plus`をパイプでつないで使用します. nは任意の自然数です.
* コマンドの例
```
$ seq 15 | ./plus
```
* 結果
```
$ 120
```
## インストール方法
* 以下を実行してください。
```
$ git clone https://github.com/kotasuzuki0526/robosys2022.git
```
## 必要なソフトウェア
* テスト済み:Python 3.7〜3.10

## 動作確認済み環境
* Ubuntu 20.04

## ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます.
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Kota Suzuki
