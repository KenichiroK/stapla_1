# stapla
```
[mac]$ git clone git@github.com:Ken1roKomatsu/stapla.git
[mac]$ cd stapla/
[mac]$ docker-compose up -d --build
(結構時間かかります)
[mac]$ docker-compose exec app ash

# app内
/work # composer install
(ここも時間かかります)
/work # cp .env.example .env
/work # php artisan key:generate

http://localhost:8881/

/work # php artisan migrate
/work # exit
```
