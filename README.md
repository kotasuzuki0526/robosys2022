# robosys2022

# plusコマンド
![test](https://github.com/kotasuzuki0526/robosys2022/actions/workflows/test.yml/badge.svg)

* 標準入力から読み込んだ数字を足し、結果を出力します.
## 使い方
* seq n と ./plusをパイプでつないで使用します.nは任意の整数です.
* コマンドの例
```
seq 15 | ./plus
```
このように入力すると1から15までの和の結果を出力します.
## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## 動作確認済み環境
* Ubuntu20.04

## ライセンス

* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます.
* このパッケージは，aaa由来のコード（© 2022 Hoge Fuge）を利用しています．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自>身の著作としたものです．
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Kota Suzuki
