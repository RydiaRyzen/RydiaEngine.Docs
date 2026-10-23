# Rydia Engine Website Template

GitHub Pages用の静的サイトテンプレートです。Visual StudioなどのエディターでHTML/CSS/JavaScriptを編集できます。

## ファイル構成

- `index.html` — トップページ
- `css/style.css` — デザイン、レスポンシブ対応
- `js/main.js` — モバイルナビゲーションとコピーライト年
- `docs/index.html` — ドキュメント案内
- `news/index.html` — 更新履歴のサンプル
- `404.html` — 404ページ

## GitHub Pagesへの配置

1. `rydiaryzen/RydiaEngine` リポジトリのルートに、これらのファイルとフォルダーを配置します。
2. GitHubの **Settings → Pages** を開きます。
3. Sourceを `Deploy from a branch`、Branchを `main`、Folderを `/(root)` に設定して保存します。
4. `https://rydiaryzen.github.io/RydiaEngine/` を確認します。

## 公開前に確認すること

- `index.html` の説明文と機能説明を実装状況に合わせて変更する。
- GitHub Releasesへのリンクが正しいことを確認する。
- スクリーンショットやロゴを追加する場合は `images/` フォルダーを作成し、HTMLの画像パスを設定する。
- `RydiaEngine` のリポジトリ名やユーザー名を変更した場合はGitHubリンクも更新する。

このテンプレートはHTML/CSS/JavaScriptのみで動作し、ビルド工程やサーバーサイド処理は必要ありません。
