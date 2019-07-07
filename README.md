# なにこれ

mikutterでRaspberry Pi向けのAppImageをつくる環境をつくるやつ。Ansible Playbookだよ

* Dockerをインストールする
* [linuxdeploy-plugin-appimage](https://github.com/linuxdeploy/linuxdeploy-plugin-appimage) プラグイン入り [linuxdeploy](https://github.com/linuxdeploy/linuxdeploy) のarmhf版AppImageを生成する
* [AppImageKit-checkrt](https://github.com/darealshinji/AppImageKit-checkrt) のarmhf版exec.soを用意する

armhfバイナリとして出てくるが、実際には実行するRaspberry Piのモデルによってarmv6l(Zero/RPi1)かarmv7l(RPi2以降)のどちらかになる。両方で動くようにする方法はわからず。

## ひつようなもの

* Ansible環境
* Raspbian Buster (Dockerのところでハードコードしてるだけでそこを直せばStretchでも)

## LICENSE

MIT License.

