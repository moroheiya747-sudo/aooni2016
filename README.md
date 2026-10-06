# 青鬼

青鬼を **Render** にデプロイする方法です。

## Renderでデプロイ

このゲームは静的サイトとして動かします。

### 1. RenderでStatic Siteを作成

Renderで **New → Static Site** を選択し、GitHubなどのリポジトリを接続します。

### 2. 設定

以下のように設定します。

* **Environment:** Static Site
* **Build Command:** なし
* **Publish Directory:** `www`

### 3. デプロイ

設定を保存して **Deploy Static Site** を押せば完了です。

デプロイ後に発行されたURLへアクセスすると、青鬼をプレイできます 🎮
