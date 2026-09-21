# みんあい学園｜Team-MinAI

GitHub Pagesでそのまま公開できる、静的な学習ゲームポータルです。

## 公開手順
1. GitHubで新しいPublic repositoryを作成
2. `index.html` をアップロード
3. Settings → Pages
4. Source を `Deploy from a branch`
5. Branch を `main` / `/ (root)` にして Save
6. 数分後に表示されるURLを開く

## ゲーム追加
`index.html` の `const games = [...]` に以下の形式で追加してください。

`{title:"ゲーム名", subject:"算数", icon:"➕", desc:"説明", url:"https://makeplay.ai/p/xxxxx"}`

MakePlayのURLは実際の公開URLをそのまま貼り付けてください。
