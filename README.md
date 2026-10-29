# 筋トレログ

自分専用の筋トレ記録アプリ（PWA）。記録の入力、BIG3・種目別の折れ線グラフ、履歴、CSVでのバックアップができます。
記録はiPhoneのSafariの中に保存され、外部には送られません。

## 入っているファイル

| ファイル | 役割 |
|---|---|
| index.html | アプリ本体（10月の記録19日分を初期データとして内蔵） |
| manifest.webmanifest | ホーム画面に置いたときの名前・アイコンの設定 |
| sw.js | 電波がない場所でも開けるようにする仕組み |
| icon-192.png / icon-512.png / apple-touch-icon.png | アイコン |

## GitHub Pagesで公開する手順

1. github.com で無料アカウントを作る
2. 右上の「＋」→「New repository」。名前は `kintore`、Public を選んで「Create repository」
3. 「uploading an existing file」をクリックし、上のファイルを全部ドラッグして「Commit changes」
4. リポジトリの「Settings」→ 左の「Pages」→ Branch を `main`・`/ (root)` にして「Save」
5. 1〜2分待つと `https://あなたのユーザー名.github.io/kintore/` で開けるようになる

## iPhoneに入れる

1. iPhoneのSafariで上のURLを開く
2. 共有ボタン →「ホーム画面に追加」
3. 以後はホーム画面のアイコンから開く

## 注意

- 記録はそのiPhoneのSafariの中だけにあります。ときどき「データ」タブから書き出してください
- 公開されるのはアプリのコードだけで、記録した重量や回数は公開されません
- アプリを直したときは、同じ手順でファイルを上書きアップロードすれば反映されます
