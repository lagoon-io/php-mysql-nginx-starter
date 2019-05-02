# php-mysql-nginx-starter

[![Build Status](https://travis-ci.org/lagoon-io/php-mysql-nginx-starter.svg?branch=master)](https://travis-ci.org/lagoon-io/php-mysql-nginx-starter)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

PHP7、MySQL、Nginx 構成の Docker

## 前提条件

・Docker インストール済み  
・Docker-compose インストール済み

## スタック

・PHP7.2  
・MySQL5.7  
・phpMyAdmin  
・Nginx(最新版)

## 起動方法

```
# モジュール取得
$ git clone https://github.com/lagoon-io/php-mysql-nginx-starter.git

# コンテナ作成
$ cd php-mysql-nginx-starter
$ docker-compose up -d
```

## 停止方法

```
$ docker-compose stop
```



## Webサーバ
・ポート番号：8080

## PHPモジュール配置先
・パス： <プロジェクトルート>/www/html/

## DBログイン
・ポート番号：13306  
・ユーザー名：root  
・パスワード ：secret  

## phpMyAdminログイン
・ポート番号：8888  
・ユーザー名：DBログインと同じ  
・パスワード ：DBログインと同じ  
