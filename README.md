# tweets_on_html
サマーハッカソン時に作ったパーツ. htmlに取得したtweetを表示する
分担したときに気軽にモックファイルをサーバーに置けたら便利だったので。
## 使い方
してない人は`json-server`をインストール

`npm install -g json-server`

db.jsonを返すサーバーを立てる

`json-server --watch db.json`

`http://localhost:3000/db`
にアクセスすると JSON が丸ごと帰ってくるので、今回はこれをTwitterAPIのGet Tweet timelinesからjsonが返ってきたとみなして開発を進めることができた

