# YORUGATA Portfolio Site

チームポートフォリオ用のシンプルな静的サイトです。ビルド不要で、そのまま GitHub Pages に載せられます。

## ファイル構成

- `index.html` : ページ本体
- `styles.css` : デザイン
- `script.js` : フッター年表示の軽い補助
- `assets/achievements/` : 実績セクションで使う画像

## 変更しやすいポイント

- ヒーロー文言: `index.html`
- 実績カード: `index.html`
- メンバー情報: `index.html`
- 問い合わせ先: `index.html`
- 色味や余白: `styles.css`

## 実績の入れ方

`index.html` の `Achievements` セクションは、次の2段構成にしています。

- 代表事例を写真つきで見せる `Featured Project`
- 受賞歴や作品を並べる `Achievements` カード一覧

差し替えやすい項目は次の通りです。

- タイトル
- 概要文
- 作品名
- 担当範囲
- 成果
- 画像
- 外部リンク

## 公開方法

1. この内容を GitHub リポジトリに push
2. GitHub の `Settings` → `Pages`
3. `Deploy from a branch` を選択
4. ブランチを `main`、フォルダを `/ (root)` に設定

必要なら次に、実メンバー情報や実績内容に合わせて中身を埋めます。
