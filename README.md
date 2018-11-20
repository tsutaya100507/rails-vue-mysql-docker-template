# rails-vue-mysql-docker-template

## ディレクトリ構成
├ rails-vue-mysql-docker-template/
　├ app-api/
　│  └ Dockerfile
　├ app-front/
　│　└ Dockerfile
　└ docker-compose.yml

## 開発用コマンド
- 開発環境立ち上げ
```
docker-compose up
```
- 開発環境停止
```
docker-compose down
```
- gemの追加後
```
docker-compose run rails bundle install
```
- schemaファイルの追加・変更後(ridgepole)
