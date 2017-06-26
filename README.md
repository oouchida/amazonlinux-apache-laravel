amazonlinux-apache-laravel
====

Dockerを使い、Amazon Linux+Apache+laravelで環境を構築しています

## Description
本イメージは、Laravelでアプリケーションを作る土台となっています。

## Usage
git clone https://github.com/oouchida/amazonlinux-apache-laravel.git  
cd amazonlinux-apache-laravel  
docker build -t oouchida/amazonlinux-apache-laravel .  
docker container run -itd -p 80:80 oouchida/amazonlinux-apache-laravel

## Test
ブラウザでhttp://localhost にアクセスしてください。
