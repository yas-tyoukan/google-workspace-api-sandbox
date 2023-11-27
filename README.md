# google-workspace-api-sandbox
Google Workspace API の動作確認をするコード

# 動作確認
## 事前準備
credentials.jsonまたはtoken.jsonを配置する。
GoogleのOAuth2.0クライアントID(デスクトップクライアント)のcredentialsをcredentials.jsonとして保存する。
token.jsonがなければcredentials.jsonの情報からOAuth認証でtoken.jsonが作られる。

## 実行コマンド
```
npm i && node .
```