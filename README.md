# scraping-server

## docker 立ち上げ

```sh
# 初回 or dockerfile に更新がある場合
docker-compose up -d --build

# 2回目以降
docker-compose up -d
```

## コンテナ内に入る

```sh
docker-compose exec python3 bash
```
