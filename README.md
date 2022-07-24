# 雑メモ

- 全部止める
```
docker stop $(docker ps -q)
```

- touch と echo 一緒にできるやつ
```
cat > docker-compose.yml
```

- コンテナ立ち上げ
```
docker compose up -d --build
```

- コンテナ停止
```
docker compose down
```

- コンテナ確認
```
docker container ps
```

- コンテナ/イメージ 全削除
```
docker prune -a
```
