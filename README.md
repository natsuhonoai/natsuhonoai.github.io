# なつほのAIホラー 公式ポータルサイト（公開＆AI自動管理パッケージ）

## 概要
「なつほのAIホラー」のYouTube、TikTok、X、ニコニコ動画を束ねる公式ポータルサイトです。
デザインは本格ホラー70% × コメディ30%の黄金比で設計されています。

## 特徴
1. **完全無料運用（サーバー代0円）：**
   GitHub Pages または Cloudflare Pages を利用することで、月額費用・保守管理コストが一切かかりません。
2. **Gemini Spark 自律管理対応：**
   `gemini_sync_daemon.py` および GitHub Actions ワークフローが同梱されており、GeminiがGoogleドライブ内の『全作品管理ダッシュボード』を読み込んで自動でWebサイトを同期・即時デプロイできます。

## デプロイ手順
1. 本フォルダの内容をGitHubのリポジトリにプッシュします。
2. Settings > Pages にて「GitHub Actions」を選択します。
3. 数秒後に公開URLが発行されます。
