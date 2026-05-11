# example_http_servers

## アーキテクチャ一覧

## nc

netcatコマンドを使った簡易サーバ。
listenなどの基本を確認できる。

### cgi (Common Gateway Interface)

httpリクエストに対してスクリプトを実行し、標準出力としてそのまま返す方式。
クエリパラメータは環境変数に入れられるのでそれを読み込む。

### ssi (Server Side Includes)

インクルードディレクティブと呼ばれる命令をHTMLに埋め込む。
テンプレートエンジンの祖先

### template engine

テンプレートを用意し、そこにエンジンと呼ばれるスクリプトで動的にコンテンツを生成する。

### 動作確認

#### 起動

対象アーキテクチャのディレクトリに移動

```
docker compose up -d
```

#### 出力確認

```
curl -i localhost:80
```

#### 停止

```
docker compose down
```
