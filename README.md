# Impinj IoT Device Swagger UI Docker

## 概要

"Impinj IoT Device"のSwagger UIをDockerで簡単に構築するためのリポジトリです。プロジェクトの概要や使用方法について、以下に説明します。

## インストール

プロジェクトをクローンして、Dockerコンテナを構築します。

```bash
git clone https://github.com/your-username/impinj-iot-device-swagger-docker.git
cd impinj-iot-device-swagger-docker
```

## 使用方法

以下のコマンドでDockerコンテナを起動し、Swagger UIにアクセスできます。

```bash
docker-compose up
```

このコマンドを実行すると、Docker Composeが`docker-compose.yml`ファイルを読み込み、指定されたサービス（swagger-editor、swagger-ui、swagger-api）を起動します。各サービスはそれぞれのポートでアクセス可能です。

*   Swagger Editor: http://localhost:8001
*   Swagger UI: http://localhost:8002
*   Swagger API (Prism Mock Server): http://localhost:8003

コンテナを停止するには、以下のコマンドを使用します。

```bash
docker-compose down
```

## ライセンス

このプロジェクトはMITライセンスのもとで公開されています。詳細は[LICENSE](LICENSE)をご覧ください。
