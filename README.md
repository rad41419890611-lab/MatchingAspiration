# Matching Aspiration

吸引カテーテル参照ツール（脳血管内治療補助用）

## 概要

脳血管内治療において使用する吸引カテーテルの選択をサポートするWebアプリケーションです。  
PWA（Progressive Web App）対応のため、ホーム画面に追加してネイティブアプリのように利用できます。

## ファイル構成

```
├── index.html                    # エントリーポイント（リダイレクト用）
├── MatchingAspiration.html       # メインアプリケーション
├── site.webmanifest              # PWAマニフェスト
├── apple-touch-icon.png          # iOS ホーム画面アイコン (180×180)
├── apple-touch-icon-152x152.png  # iPad ホーム画面アイコン (152×152)
├── apple-touch-icon-167x167.png  # iPad Pro ホーム画面アイコン (167×167)
├── android-chrome-192x192.png    # Android ホーム画面アイコン (192×192)
├── android-chrome-512x512.png    # Android スプラッシュ用アイコン (512×512)
├── favicon.ico                   # ブラウザタブアイコン
├── favicon-16x16.png             # ファビコン 16px
├── favicon-32x32.png             # ファビコン 32px
├── 404.html                      # 404エラーページ
├── _headers                      # Netlify / Cloudflare Pages ヘッダー設定
├── _redirects                    # Netlify リダイレクト設定
├── netlify.toml                  # Netlify 設定ファイル
└── package.json                  # パッケージ情報
```

## デプロイ

GitHub リポジトリと連携し、以下のサービスへ自動デプロイしています。

- **Netlify**
- **Cloudflare Pages**

`main` ブランチへのプッシュで自動的にデプロイが実行されます。

## PWA（ホーム画面追加）

iOS Safari・Android Chrome から「ホーム画面に追加」することで、  
アプリとして起動できます。アイコンには本ツール専用の画像が設定されています。

## 更新履歴

| バージョン | 内容 |
|---|---|
| fixed | ホーム画面アイコンを専用デザインに変更（全サイズ更新） |

