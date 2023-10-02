## 音声ファイル要約AI

### デモ

![demo](https://github.com/oijofie/llm_summary_generator/blob/main/demo/llm_sum.gif)

### 概要

- 音声ファイルをAIでテキスト化し、要約する

### 機能

1. mp3ファイルをドラッグ&ドロップ
2. chatgptによりmp3ファイルから文字起こし&要約
3. 要約した結果が表示される

### ユースケース

- 音声ファイル(mp3)だけでなく、pdfやwordなどのテキストからの要約が可能。
- 社内文書の要約、社内業務Q&A作成、調査業務などに活用可能

### 技術

- インフラ：docker
- フロントエンド：vue, tailwind css
- バックエンド：python, fastapi, chatgpt api
