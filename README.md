# DockerComposeForPython
---
Dockerで分析環境を作成するための備忘録

## 操作方法
### 起動
    docker compose up -d --build

### 停止
    docker-compose stop

### 停止＆削除（コンテナ・ネットワーク）
    docker-compose down

### 停止＆削除（コンテナ・ネットワーク・イメージ）
    docker-compose down --rmi all

### 停止＆削除（コンテナ・ネットワーク・ボリューム）
    docker-compose down -v

