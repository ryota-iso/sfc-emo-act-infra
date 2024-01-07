# SFC 感情と行動のコンピューティング Docker Compose

「感情と行動のコンピューティング」の最終課題用リポジトリです。
DBをローカルで動かすためのdocker-compose.ymlを記載します。

個別に起動したり、DBの変更が頻繁に行われる可能性があるため、個別のdocker-compose,ymlを用意しています。

## 利用方法
起動したいDBのディレクトリに移動して下記コマンドを実行

### コンテナの起動
```zsh
docker-compose up -d
```

### コンテナの停止
```zsh
docker-compose stop
```
### コンテナの削除
```zsh
docker-compose down
```
