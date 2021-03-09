# gypsyChamois
環境構築
```
git clone https://github.com/lil-shimon/gypsyChamois-back.git
cd gypsyChamois
docker-compose up -d
```
コンテナに入る
```
docker container exec -it gypsychamois_web_1 bash
```
サーバ立ち上げ

```
 python manage.py runserver 0.0.0.0:8000
```

DB
```
APIURL + /admin
```

開発ユーザー情報
```
username: admin
password: admin
```
