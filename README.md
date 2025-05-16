# StudioQ Website

StudioQのウェブサイトリニューアルプロジェクトです。プロフェッショナルな写真・映像制作スタジオのウェブサイトです。

## 特徴

- モダンでレスポンシブなデザイン
- 写真・映像ギャラリー
- サービス紹介セクション
- ブログ機能
- お問い合わせフォーム

## 技術スタック

- HTML5
- CSS3
- JavaScript (ES6+)
- レスポンシブデザイン

## デプロイ方法

### GitHub Pages
このプロジェクトはGitHub Pagesを使用して自動的にデプロイされます。`main`ブランチにプッシュすると、GitHub Actionsによって`gh-pages`ブランチにデプロイされます。

### Vercel
Vercelでデプロイする場合は、リポジトリをインポートするだけで、`vercel.json`の設定に基づいて自動的にデプロイされます。

### Bolt.new
Bolt.newでデプロイする場合は、以下の手順に従ってください：

1. [bolt.new](https://bolt.new) にアクセスします
2. 「Import from GitHub」を選択
3. リポジトリURL `https://github.com/tedueda/bolt-studioq2.git` を入力
4. デプロイボタンをクリック

**または、ワンクリックでインポート：**

[![Import to Bolt](https://bolt.new/button)](https://bolt.new/import/github/tedueda/bolt-studioq2)

Bolt.newは`bolt.json`と`bolt.new.json`の設定に基づいて自動的にサイトをデプロイします。

## カスタマイズ方法

- `index.html` - メインページの内容
- `style.css` - スタイルシート
- `script.js` - インタラクティブな機能
- `images/` - 画像ファイル
- `movie/` - 動画ファイル
- `blog/` - ブログ記事

## ライセンス

MIT