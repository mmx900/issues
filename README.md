# 빠띠 이슈즈

![logo](public/favicons/android-icon-144x144.png)
https://issues.asia/

## 환경설정
`.env` 설정
```
DATABASE_USERNAME=postgres
DATABASE_PASSWORD=tmp_password
REDIS_HOST=localhost
REDIS_PORT=6379
```

```
$ rbenv install 2.7.2
$ bundle install
$ docker compose up
$ rails db:setup
$ rails s
```
