## json-server

```bash
npm install -g json-server
json-server --watch
```



## メソッド

### GET

`curl -X GET "http://localhost:3000/episodes" -v`

-x: メソッドの指定
-v: レスポンスとリクエストの詳細を見ることができる

### POST

`curl -X POST -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の団欒"}' "http://localhost:3000/episodes" -v`

-H: 送るデータがJson形式であることを示している

### PUT

`curl -X PUT -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の争乱"}' "http://localhost:3000/episodes/4" -v`

### DELETE

`curl -X DELETE "http://localhost:3000/episodes/4" -v`

### HEAD

`curl -X HEAD "http://localhost:3000/episodes" -v`

### OPTIONS

`curl -X OPTIONS "http://localhost:3000/episodes" -v`
