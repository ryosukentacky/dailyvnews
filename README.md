# 読売新聞ニュース解説ノート

2026年10月14日・15日のChatGPTによるニュース解説を日付・カテゴリ別に整理したGitHub Pagesサイトです。

## 公開方法
1. このZIPを解凍します。
2. GitHubのリポジトリに **index.html、original_chat.md、imagesフォルダ** をアップロードします。
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) を選び保存します。
4. 数分後に公開URLへアクセスします。

## 収録内容
- 解説 19 件（2026年10月14日：10件、15日：9件）
- 日付・カテゴリ切替、本文検索
- 各解説の原文をそのまま表示・コピー可能
- チャット全文のMarkdown原本（画像への参照を含む）
- 元のスクリーンショット画像 18 枚

注意：元チャットに含まれるDILの動的UI・検索画像・引用コンポーネントは静的HTMLとして完全再現できないため、読みやすい表示に加え原文を保存しています。元の会話テキストは変更していません。


## GitHub Pages の Jekyll エラー対策

ルートにある `.nojekyll` を必ず `index.html` と同じ階層にアップロードしてください。これにより `original_chat.md` 内の `{{...}}` が Liquid テンプレートとして誤解析される問題を回避します。GitHub で `.nojekyll` が見えない場合、隠しファイル表示を有効にしてください。
