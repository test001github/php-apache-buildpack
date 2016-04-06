# php-apache-buildpack

PHP + Apache HTTPD 環境のサンプル BuildPack for IBM Bluemix

## 使い方

- cf コマンドラインツールをインストール [Link](https://github.com/cloudfoundry/cli/releases)

- ドキュメントルートに **index.php** ファイルを用意（このファイルがないと動かない）

- 必要であれば index.php 以外の PHP ファイル等も用意

- cf push *appname* -b https://github.com/dotnsf/php-apache-buildpack でプッシュ

## スペック

- PHP 5.6.14

- Apache HTTPD 2.4.16

- php.ini 及び httpd.conf の内容は config 以下参照

