# [Apache Cassandra](https://cassandra.apache.org/) を Cluster 起動 する docker-compose.yml

## 準備
1. [docker, docker-compose をインストール](https://docs.docker.com/install/#supported-platforms)

## 設定
デフォルト値から変更する場合は、 `.env.example` を `.env` にコピーし編集

```
cp .env.example .env
vi .env
```

### `cassandra_ip_port`
cassandraの `9042` 番portを forward する IP:PORT

デフォルト値: `127.0.0.1:9042-9044`

## 起動
```
docker-compose up -d
```
