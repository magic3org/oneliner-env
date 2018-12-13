# 1行で環境構築
サーバにrootログインし１行のコマンドを実行するだけでMagic3の動作環境構築できるスクリプトです。
Magic3のインストーラが起動できるところまでを一気に構築します。

Magic3運用に必要なソフトウェアがすべて1台のサーバに納まるようにパッケージ化されています。
環境構築は難しい、たいへん時間がかかるという問題を解決します。

## 対象OS
- CentOS 7

## ライセンス

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# 実行内容
ローカルにAnsibleをインストールし、Ansible GalaxyのPlaybookを基本に少しカスタマイズして環境構築しています。
次の特色があります。

- 最新のソフトウェア環境
- 日本語最適化

# 使い方
新規にOSをインストールしたサーバにrootでログインし、構築したい環境のスクリプトを実行します。
完了後は一旦サーバを再起動してください。

## LEMP環境構築
Linux(L),Nginx(N),MariaDB(M),PHP(P)のLEMP環境を作成します。
PHPはバージョン7.0以上です。

```
$ curl https://raw.githubusercontent.com/czbone/oneliner-env/master/script/build_lemp.sh | sh
```

# 検証環境
- Vagrant Box 「centos/7」
- さくらVPS 「CentOS7」
