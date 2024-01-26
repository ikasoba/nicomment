# nicomment

デスクトップ上にニコニコのコメントっぽく文字が流れるやつです。

- Windowsのみ対応

# ダウンロード

ここから好きなバージョンをダウンロードしてください。

https://github.com/ikasoba/nicomment/releases

# 設定

実行ファイルと同じディレクトリの`port.txt`に好きなポート番号を書くとそのポート番号で起動します。

# 使い方

`nicomment.exe`が本体で、`nicomment_client.exe`が動作確認用のクライアントです。

実行時にポート番号がダイアログで表示されるのでOKを押してください。

nicommentが動いてるポート(デフォルトでは`3214`)にTCPで接続し、文字列のバイト数(32bit符号付き整数)とその文字列を送信するとその文字列が画面上に表示されます。

また、文字コードはsjisのみ対応しています。

# クライアント一覧

- peertube用クライアント

  https://github.com/ikasoba/nicomment-peertube-livechat
