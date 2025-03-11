FROM mariadb:latest

# 初期化用のSQLとスクリプトをコンテナにコピー
COPY ./init.sh /docker-entrypoint-initdb.d/
COPY ./init.sql /docker-entrypoint-initdb.d/
