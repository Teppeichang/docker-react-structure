## 環境構築手順 / Instruction

イメージのビルド
```
docker-compose build
```

コンテナのビルド→create-react-appのインストール&create-react-app実行
```
docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app app"
```

コンテナ起動
```
docker-compose up
```

## 動作確認
http://localhost:3000  
初期画面(Reactのアイコンが回転しているページ)が表示されればOK!