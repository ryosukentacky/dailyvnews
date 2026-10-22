# GitHub Pages用・操作機能付きニュース再現版

`index.html` をGitHub Pagesの公開フォルダへ配置してください。ZIPの中身を同じ階層に置きます。

- `index.html`: Markdownに含まれた記事・解説を順番に表示。スライダー・解答開閉・グラフをブラウザ用に再実装。
- `original_chat.md`: **原文Markdown無変更**。
- `original_chat.html`: 提供されたHTMLを無変更で保存。
- `original_singlefile.html`: 提供されたSingleFile HTMLを無変更で保存。
- `learning_instructions.txt`: 学習形式指示の原本。

**制限**: ChatGPT固有のUIや実行機能はそのまま移植できません。Markdownから検出できたスライダー・確認問題・グラフのみ独立実装しました。本文のうちDIL専用レイアウトタグや動的表示構文は表示用に変換しています。全原文は `original_chat.md` に保持されています。既存のGitHubサイトの `index.html` は上書きしないでください。専用フォルダに配置してください。
