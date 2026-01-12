# Otaku Tabi HP (オタク旅)

YouTuber「オタク旅」の公式ホームページプロジェクト。
未知の世界を楽しみながら前向きに学びに変える、夫婦旅チャンネルの世界観を表現したWebサイトです。

## 🚀 特徴

- **Premium Design**: 暖色（赤）と寒色（ティール）を基調としたモダンで洗練されたデザイン。
- **High Performance**: Vite + Vanilla JS + CSS3による軽量・高速な動作。
- **Responsive**: モバイルファーストなレスポンシブデザイン。
- **Animations**: スクロール連動のフェードインやパララックス効果。

## 🛠️ 技術スタック

- **Build Tool**: [Vite](https://vitejs.dev/)
- **Languages**: HTML5, CSS3, Vanilla JavaScript
- **Deployment**: Static Hosting (Netlify, Vercel, GitHub Pages etc.)

## 📦 セットアップ

プロジェクトを手元で動かすための手順です。

### 前提条件

- Node.js (v18以上推奨)
- npm

### インストール

```bash
# リポジトリのクローン
git clone https://github.com/37mo/otakutabi-hp.git
cd otakutabi-hp

# 依存関係のインストール
npm install
```

### 開発サーバーの起動

```bash
npm run dev
```

`http://localhost:5173` でプレビューできます。

### ビルド

本番環境用のファイルを生成します。

```bash
npm run build
```

`dist` フォルダに成果物が出力されます。

## 📁 ディレクトリ構成

```
src/
├── assets/         # 画像などの静的ファイル
│   └── images/     # YouTubeから取得した画像など
├── components/     # (将来的な拡張用)
├── styles/
│   └── main.css    # メインスタイルシート
├── index.html      # メインHTML
└── main.js         # エントリーポイント・インタラクション
```

## 📝 ライセンス

All Rights Reserved.
