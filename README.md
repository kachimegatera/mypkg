# 課題2提出用
これまで授業で学んだことをgithub上で見せるため。

![test](https://github.com/kachimegatera/mypkg/actions/workflows/test.yml/badge.svg)

# ノード
## talker
整数を０からカウントする。
トピック名を決める。
## listener
talkerから発信された情報を受け取る。

# トピック
## countup
ノードをつなぐ流路のことで、メッセージの型は16ビット符号付整数でこれを0.5秒ずつ送信されるようになっている。

# 実行方法
* 1.ubuntuの端末を二つにする。
* 2.一つ目の端末に
```
ros2 run mypkg talker
```
を実行する。
* 3.2つ目の端末に
```
ros2 run mypkg listener
```
を実行する。
# テスト環境

* ros2 humble
* Ubuntu22.04

テストには上田隆一先生のコンテナを使っています。
# ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* 🄫2022 Takuma Kachi
