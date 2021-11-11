
## dockerにログインする
```ubuntu
docker login
　※UsernameとPasswordを聞かれるので入力
```

## dockerから任意のイメージをpullする（インストールするイメージ）
```ubuntu
docker pull <image>

```
## ホスト(PC等)の中にあるイメージのリストを確認
```ubuntu
docker images
```
## コンテナを作成
```ubuntu
docker run <image>
```

## コンテナを表示する(アクティブなもののみ)
```ubuntu
docker ps
```

## コンテナを全て表示する
```ubuntu
docker ps -a
```

## ubuntuのDocker imageをrunする（コンテナに入る）
```ubuntu
docker run -it ubuntu bash
```

## ubntuのコンテナを更新（コンテナに入っている状態(run)で）
```ubuntu
（例）
touch <file>
　※ファイルが作成される
```

## コンテナから抜ける
```ubuntu
exit
```

## コンテナを再度起動する
```ubuntu
docker restart <コンテナのIDか名前>
```

## コンテナに再度入る
```ubuntu
docker exec -it <コンテナのIDか名前> bash
```

## コンテナを新しいイメージとして保存する
```ubuntu
docker commit <コンテナのIDか名前> ubntu:updated
```





