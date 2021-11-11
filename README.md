
## dockerにログインする
```bash
docker login
　※UsernameとPasswordを聞かれるので入力
```

## dockerから任意のイメージをpullする（インストールするイメージ）
```bash
docker pull <image>

```
## ホスト(PC等)の中にあるイメージのリストを確認
```bash
docker images
```
## コンテナを作成
```bash
docker run <image>
```

## コンテナを表示する(アクティブなもののみ)
```bash
docker ps
```

## コンテナを全て表示する
```bash
docker ps -a
```

## ubuntuのDocker imageをrunする（コンテナに入る）
```bash
docker run -it ubuntu bash
```

## ubntuのコンテナを更新（コンテナに入っている状態(run)で）
```bash
（例）
touch <file>
　※ファイルが作成される
```

## コンテナから抜ける
```bash
exit
```

## コンテナを再度起動する
```bash
docker restart <コンテナのIDか名前>
```

## コンテナに再度入る
```bash
docker exec -it <コンテナのIDか名前> bash
```

## コンテナを新しいイメージとして保存する
```bash
docker commit <コンテナのIDか名前> ubntu:updated（IMAGE名:TAG名）
```

## DockerhubにDocker imageをpushする
```bash
docker push <image>
 ※このイメージはリポジトリの名前になる
```




