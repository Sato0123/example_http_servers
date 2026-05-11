# example_http_servers

## cgi (Common Gateway Interface)

httpリクエストに対してスクリプトを実行し、標準出力としてそのまま返す方式。
クエリパラメータは環境変数に入れられるのでそれを読み込む。

### 動作確認

```
cd cgi
docker compose up -d
```

## ssi (Server Side Includes)

インクルードディレクティブと呼ばれる命令をHTMLに埋め込む。
テンプレートエンジンの祖先

### 動作確認

```
cd ssi
docker compose up -d
```

## template engine

テンプレートを用意し、そこにエンジンと呼ばれるスクリプトで動的にコンテンツを生成する。

### 動作確認

```
cd template_engine
docker compose up -d
```
