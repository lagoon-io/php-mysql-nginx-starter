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
