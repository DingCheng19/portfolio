# Portfolio Site

GitHub Pages 用のシンプルなポートフォリオサイトです。

## ファイル構成

- `index.html` : 一覧ページ本体
- `style.css` : デザイン
- `projects.json` : プロジェクト一覧データ

## 使い方

1. `index.html` と `projects.json` の `YOUR_GITHUB_ID` を自分の GitHub ユーザー名に変更
2. `your-email@example.com` を自分のメールアドレスに変更
3. GitHub にアップロード
4. GitHub Pages を有効化

## 新しいプロジェクトを追加する方法

`projects.json` に以下の形式で1件追加します。

```json
{
  "title": "アプリ名",
  "description": "概要",
  "tech": ["Flutter", "Dart"],
  "highlights": ["ポイント1", "ポイント2"],
  "github": "https://github.com/YOUR_GITHUB_ID/repository_name",
  "demo": ""
}
```
