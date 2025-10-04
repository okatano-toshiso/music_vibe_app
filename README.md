# 🎵 Music Vibe App

Music Vibe Appは、音楽を通じて気分を高めるためのWebアプリケーションです。  
LaravelとViteをベースに構築されており、モダンでスムーズなユーザー体験を提供します。

---

## 🚀 概要

このアプリは、ユーザーが音楽を検索・再生し、プレイリストを作成・共有できるプラットフォームです。  
Spotify APIなどの外部サービスと連携し、リアルタイムで音楽データを取得します。

---

## 🧩 主な機能

- 🎧 楽曲検索（アーティスト名・曲名・ジャンルなど）
- 💾 プレイリスト作成・保存
- 🔗 Spotifyなどの外部API連携
- 🌓 ダークモード対応UI
- 📱 レスポンシブデザイン（スマホ・タブレット対応）

---

## 🛠️ セットアップ手順

### 1. リポジトリのクローン
```bash
git clone https://github.com/yourusername/music_vibe_app.git
cd music_vibe_app
```

### 2. 依存関係のインストール
```bash
composer install
npm install
```

### 3. 環境設定
`.env.example` をコピーして `.env` を作成し、必要な環境変数を設定します。
```bash
cp .env.example .env
php artisan key:generate
```

### 4. データベースのマイグレーション
```bash
php artisan migrate
```

### 5. 開発サーバーの起動
```bash
php artisan serve
npm run dev
```

ブラウザで以下にアクセス：
```
http://localhost:8000
```

---

## ⚙️ 使用技術

| カテゴリ | 技術 |
|-----------|------|
| フレームワーク | [Laravel 10](https://laravel.com/) |
| フロントエンド | [Vite](https://vitejs.dev/), [Vue.js](https://vuejs.org/) |
| スタイリング | [Tailwind CSS](https://tailwindcss.com/) |
| データベース | MySQL / SQLite |
| API連携 | Spotify API, Last.fm API |
| テスト | PHPUnit |

---

## 📁 ディレクトリ構成（抜粋）

```
music_vibe_app/
├── app/                # アプリケーションロジック
├── resources/          # フロントエンドリソース（Blade, Vue, CSSなど）
├── routes/             # ルーティング設定
├── public/             # 公開ディレクトリ
├── database/           # マイグレーション・シーディング
├── vite.config.js      # Vite設定
└── .env.example        # 環境変数サンプル
```

---

## 🧑‍💻 開発者向けコマンド

| コマンド | 説明 |
|-----------|------|
| `php artisan serve` | Laravel開発サーバーを起動 |
| `npm run dev` | Vite開発サーバーを起動 |
| `npm run build` | 本番用ビルドを生成 |
| `php artisan migrate` | データベースマイグレーションを実行 |

---

## 🧪 テスト

```bash
php artisan test
```

---

## 📝 ライセンス

このプロジェクトは [MITライセンス](https://opensource.org/licenses/MIT) の下で公開されています。

---

## 📚 参考資料

- [GitHub公式Markdown記法ガイド](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Qiita: READMEの書き方まとめ](https://qiita.com/dfalcon0001/items/843b93d90f21b9e99d50)
- [cpp-learning.com: READMEの作り方](https://cpp-learning.com/readme/)
- [Reddit: GitHub README Templates](https://www.reddit.com/r/programming/comments/l0mgcy/github_readme_templates_creating_a_good_readme_is/?tl=ja)
