# CONTRIBUTING

p5jsウェブサイトの日本語訳プロジェクトに興味を持ってくださりありがとうございます！ここでは、このプロジェクトに貢献する様々な方法を紹介します。

## Organizationに参加する

翻訳プロジェクトはGitHub Organization [p5js-i18n-ja](https://github.com/p5js-i18n-ja)内で行われています。このOrganizationに参加したい場合、まずはDiscordサーバーに参加してください！

招待リンク: https://discord.gg/eAypr2BaMU

このDiscordサーバーではプロジェクトに関する議論、Organizationの運営などが行われています。サーバーへの参加後にOrganizationに招待してもらいましょう。

## Fork・PRについて

このプロジェクトでは[p5js-i18n-ja/p5.js-website](https://github.com/p5js-i18n-ja/p5.js-website)のリポジトリに翻訳の成果物が置かれています。翻訳の提案などがある場合はこのリポジトリをForkしてPRを出してください！具体的な作業手順については[GitHowTo.md](./GitHowTo.md)などを参考にしてください。Fork・PRの方法については、以下の記事なども参考になります:

- [リポジトリをフォークする - GitHub Docs](https://docs.github.com/ja/get-started/quickstart/fork-a-repo)
- [pull request の作成 - GitHub Docs](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

## 翻訳にあたってのスタイルガイド・ルール等

以下の文献を参考にしてください。

- [マイクロソフト スタイルガイド](https://www.microsoft.com/ja-jp/language/styleguides)
- [ひらがな、漢字の使い分け](https://webtan.impress.co.jp/e/2017/11/24/26279)

上記文献の内容を基本方針とした上で、さらに以下のルールに従ってください。

**単語最後の長音は記述する**

正誤例:

正 | 誤
--- | ---
サーバー | サーバ
ユーザー | ユーザ
コンピューター | コンピュータ

**「読み込み」か「ロード」か**

データの読み書きは「ロード・セーブ」が適切に感じられますが、メディア(画像や音声)など、そのままで意味を成して利用されるものは「読み込み・書き込み」の方が適切でしょう。しかしプログラム内でメディアなどを利用する場合はロードの方が適切かもしれません。

このように使い分けに迷うところではありますが、ここでは「読み込み・書き込み」で統一します。ゲームのセーブデータなど、よっぽど「ロード・セーブ」の方が適切だと感じられる場合はその限りではありません。
