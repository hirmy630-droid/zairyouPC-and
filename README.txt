材料取り 計算 PWA 完成版

このZIPをGitHub Pagesの公開フォルダに、そのまま上書きアップロードしてください。

入っているもの:
- index.html
- manifest.webmanifest
- sw.js
- apple-touch-icon.png
- icon-180.png
- icon-192.png
- icon-maskable-192.png
- icon-512.png
- icon-maskable-512.png
- icon-1024.png

このZIPでは以下を整理済み:
- manifestを1本化（manifest.jsonは削除）
- service workerのキャッシュ対象を実在ファイルだけに統一
- iPhone用apple-touch-icon追加
- Android用maskableアイコン追加
- 新しいservice workerへ強制更新しやすい構成に変更

アップロード後:
1. GitHubに既存ファイルを上書き
2. 公開URLを開く
3. 1回だけ画面更新
4. 既存ホーム画面アイコンが古い場合は、ホーム画面から削除して再追加
