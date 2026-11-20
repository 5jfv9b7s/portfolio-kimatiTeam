#  Portfolio

Kimati Teamのポートフォリオサイト初稿です。HTML / CSS / JavaScriptだけで構成しているため、GitHub Pagesなどの静的ホスティングでそのまま公開できます。

## ローカルで確認する

`index.html`をブラウザで開いてください。

## 公開方法

GitHubリポジトリの **Settings → Pages** から、Build and deploymentのSourceに **Deploy from a branch**、Branchに `main` / `/ (root)` を指定します。
https://5jfv9b7s.github.io/portfolio-kimatiTeam/index.html

## メンバーページ

ホーム画面のMembersから、4人それぞれのプロフィールページへ移動できます。各ページには「プロフィール」「自己紹介」「趣味・興味」「目標・夢」「好きなもの」の雛形を用意しています。

### Takahashiの自己紹介

- `members/Takahashi.html`：プロフィール、興味、制作物、紹介文を編集します。
- `members/Takahashi.css`：このページ専用の配色とレイアウトを編集します。
- `assets/images/takahashi-icon.jpg`：プロフィールとファビコンに使用する画像です。

紹介文は、共有された人物紹介をもとに、趣味や制作活動を中心にまとめています。
以前の `members/member-01.html` からも、新しいページへ自動的に移動します。

## 次に更新する箇所

- 残りのメンバーページにある名前・年齢・出身・所属・紹介文の実情報への差し替え
- 残りのメンバーのプロフィール画像の追加
- 制作実績の画像、詳細ページ、リンクの追加
- `hello@kimati.team` の連絡先変更
