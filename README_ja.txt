最速降下曲線ゲーム（週間・全期間ランキング対応／本番API設定済み）

このZIPには次のファイルが入っています。
- index.html: 日本語版
- index_en.html: 英語版

両ファイルの SCORE_API_URL には指定されたGoogle Apps Scriptの /exec URLを設定済みです。
PREVIEW_MODE = false なので、表示するランキングはサンプルではなく実際のデータです。
また、5問終了後にスコアを登録すると本番のGoogleスプレッドシートへ書き込まれます。

注意：Google Apps Script側は既存コードと差し替え済みのことを前提にしています。
WebアプリのURLが本番にデプロイされている必要があります。
GitHubにアップロードする前に、別環境でランキング読み込み・スコア登録を確かめてください。
元のHTMLとApps Scriptは必ずバックアップしてください。

バージョン表示：v0.2 beta（HTMLの画面表示とブラウザーのタイトルを統一）
