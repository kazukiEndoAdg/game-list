FROM node:20

WORKDIR /app

# Install NodeJS and npm
RUN apt-get update && apt-get install -y tini

# コンテナを永続的に稼働させるためのコマンド
ENTRYPOINT ["/usr/bin/tini", "--"]

CMD ["sleep", "infinity"]