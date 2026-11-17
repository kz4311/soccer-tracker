# Soccer Tracker

既存の `soccer-tracker(1).html` を、機能・デザインを変更せずにWeb公開するための最小構成です。

## 現状

- アプリ本体は単一HTMLファイルです。
- 外部ライブラリ、ビルド、サーバーは不要です。
- 入力内容はブラウザの `localStorage` に保存されます。
- 端末やブラウザをまたいだデータ共有は、まだ行いません。

## 公開構成

GitHubリポジトリに `index.html` を置き、Cloudflare Pagesなどの静的ホスティングに接続します。

```text
soccer-tracker/
├── index.html
└── README.md
```

GitHubアカウントと公開先サービスの接続が必要になった段階で、画面を確認しながら進めます。
