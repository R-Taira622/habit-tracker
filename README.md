# 習慣化記録トラッカー

🗓️ **習慣化を支援するシンプルなカレンダーアプリ（PWA対応）**  
GitHub Pagesで公開中 👉 [こちらからアクセス](https://r-taira622.github.io/habit-tracker/)

※ChatGPTでサクッと作りました。

## 🔧 機能概要

- 📆 カレンダー形式で開発記録（開発した日：緑、しなかった日：赤）
- 📝 各日付に1行メモを記録
- 📲 PWA対応：スマホホーム画面に追加してアプリ感覚で使える
- 💾 データはローカル保存（ブラウザに保持）
- 📱 ダークテーマ・スマホ最適化済み
- 🎨 テーマ切り替え（シンプル / ダーク / パステル）対応（※任意機能）

## 📁 ファイル構成
habit-tracker/

├── index.html

├── manifest.json

├── service-worker.js

└── icons/

　├── icon-192.png
 
　└── icon-512.png


## 🚀 公開方法（GitHub Pages）

1. このリポジトリを `main` ブランチで公開
2. `Settings > Pages > Deploy from a branch` を `/ (root)` に設定
3. 数分でページが生成され、URLが発行されます

## 📱 スマホでの使い方（PWA）

1. Chromeで公開URLを開く
2. メニュー「︙」→「ホーム画面に追加」
3. アプリのように起動・使用可能！

## 🧠 開発メモ

- 使用言語：HTML / CSS / JavaScript（フレームワーク不使用）
- オフライン対応：Service Worker によるキャッシュ

## 🧑‍💻 作者

[R-Taira622](https://github.com/R-Taira622)

