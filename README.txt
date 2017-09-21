
Dockerでlaravel環境構築(php-fpm,nginx,mysql,redis)

http://qiita.com/meidaimae/items/1b5902e2e520ece34b9a#2env%E3%82%92%E7%B7%A8%E9%9B%86%E3%81%97%E3%81%BE%E3%81%99

いまいちだった。



=== 利用しているイメージ
https://hub.docker.com/_/php/

https://hub.docker.com/_/nginx/










=== 開始 ===
$ docker-compose up -d



=== 終了 ===
$ docker-compose down --rmi all
Stopping laravel_web_1 ... done
Stopping laravel_app_1 ... done
Stopping laravel_redis_1 ... done
Stopping laravel_mysql_1 ... done
Removing laravel_web_1 ... done
Removing laravel_app_1 ... done
Removing laravel_redis_1 ... done
Removing laravel_mysql_1 ... done
Removing network laravel_default
Removing image redis:latest
Removing image mysql:latest
Removing image laravel_app
Removing image laravel_web


