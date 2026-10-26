# 校務ポータル(portal)

- 全アプリ共通のルールは `../CLAUDE.md`。必ず従うこと。
- 作業を始める前に [HANDOFF.md](HANDOFF.md) を読むこと(データの仕組み・なぜ `.js` なのか・未確認のこと)。
- 機能を変えたら README.md(先生向け)・CHANGELOG.md・HANDOFF.md を同時に更新する。画面のボタンを変えたら、`index.html` の `TOUR`(画面ガイド)も直す。
- データに項目を足したら `normalize()` にも足す(古いデータファイルを読めるように)。
- 実際のリンクのデータ(`links-data.js`。学校のサーバー名・フォルダの場所が入る)は、このフォルダに置かない・コミットしない。テストで置いたら必ず消す。
- appcopy のミラー先は `C:\Users\idolo\Documents\projects\appcopy\portal\`。
