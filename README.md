## CSSインジェクションお試しリポジトリ
- injection_example.htmlをブラウザで開きます。
- ユーザーが入力したものが、その後入力フォームの下側に出力として出てくる簡単なサイトです。
- localStorageを擬似DBとして使用しています。
  - 他の開発中のアプリに影響があるかもしれないので、試した後にlocalStorageに保存されたデータは削除する事を推奨します。
- CSSインジェクションを体験する入力例を下記に記載します
  - Hello 私はハッカーだ。君のPCを乗っ取った。情報を流されたく無ければ。⚪︎⚪︎⚪︎⚪︎に100万円振り込め。<style>body {background-color: red;}</style>
- このリポジトリを使ってzennの記事も書いているので、そちらも参照してください！（いいねしてくれると嬉しいです！！）
  - https://zenn.dev/irsc/articles/abount-css-injection
