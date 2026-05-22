<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI音声入力 Chrome拡張機能" />
</p>

<h3 align="center">LinguaVox — あなたの言語で話す。21以上の言語で書く。</h3>

<p align="center">
  ショートカットキーを押しながら話す · 離す · 3秒以内にどのWebフィールドにもテキストが入力される<br>
  OpenAI Whisper · 21以上の出力言語 · 6つのAIモード · APIキー不要 · Slack、Gmail、Notion、Jira
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/ライセンス-MIT-blue.svg" alt="ライセンス" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/ウェブサイト-linguavox-brightgreen" alt="ウェブサイト" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20ウェブストア-無料インストール-blue?logo=googlechrome" alt="Chrome ウェブストア" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/ダッシュボード-開く-orange" alt="ダッシュボード" /></a>
  <img src="https://img.shields.io/badge/バージョン-2.8-green" alt="バージョン" />
</p>

---

## LinguaVoxとは？

LinguaVoxは、AI搭載の音声入力・翻訳Chrome拡張機能です。Ctrl+Spaceを押しながら話し、離すと、転写されたテキストが即座にアクティブなテキストフィールドに入力されます：チャットボックス、メールエディター、検索フィールド、CRMフォーム、コードエディターなど。OpenAI Whisperで95%以上の精度を実現し、GPT-4o-miniによるオプションのAI強化（文法修正、スタイル書き換え、翻訳）も提供します。

ほとんどの音声入力ツールとは異なり、LinguaVoxは自分のOpenAI APIキーを必要としません。無料ユーザーは共有キープールから1日100リクエストを取得でき、設定は不要です。パワーユーザーやチームは自分のキーを接続して無制限に使用できます。

## 使い方

**LinguaVox導入前：** 別アプリを開く → 録音 → コピー → ブラウザに切り替え → 貼り付け  
**LinguaVox導入後：**

```
1. 任意のフィールドをクリック（Slack、Gmail、Notion、Jira…）
2. Ctrl+Space  を押しながら  →  話す
3. 離す  →  ~3秒以内にテキストが入力される  ✓
```

コピー&ペースト不要。アプリ切り替え不要。あらゆるウェブサイトで動作。

## 対応プラットフォーム

| プラットフォーム | 状態 | 備考 |
|----------------|------|------|
| Slack（ブラウザ） | ✅ | ブラウザレベルのショートカットでSlackのキー入力キャプチャを回避 |
| Gmail | ✅ | 作成・返信フィールド |
| Notion | ✅ | すべての`contenteditable`ブロック |
| Jira | ✅ | タスクフィールド、コメント、説明 |
| Asana | ✅ | タスク・コメントフィールド |
| Salesforce | ✅ | CRM入力フィールド |
| 任意の`<input>` / `<textarea>` | ✅ | ユニバーサル — あらゆるウェブサイト |
| 任意の`contenteditable` | ✅ | React、Draft.js、Quill互換 |
| Google ドキュメント | ⚠️ | 制限あり — カスタムキャンバスエディター |

## 主な機能

- **APIキー不要** — 共有プールから1日100リクエスト無料、設定ゼロ
- **自分のキー（BYOK）** — OpenAIコストで無制限使用（典型的な月額$0.50未満）
- **組織アカウント** — 共有キープール、メンバー管理、使用状況分析
- **21以上の言語** — 文字起こしと翻訳を1ステップで
- **6つのAI強化モード** — 文法修正、ビジネススタイル、学術的、カジュアル、クリエイティブ、スマートポリッシュ
- **プライバシー優先** — 音声は保存されず、リアルタイムで処理・破棄
- **3秒以内** — 発話からテキスト挿入まで
- **95%以上の精度** — OpenAI Whisper large-v2

## AI強化モード

| モード | 機能 |
|-------|------|
| スマートポリッシュ | 文法を修正し、明瞭さを向上、意味を保持 |
| ビジネススタイル | プロフェッショナルなビジネスコミュニケーション向けに書き換え |
| 文法修正 | 文法とスペルのみ修正 |
| クリエイティブスタイル | 生き生きとした魅力的な文章 |
| カジュアルスタイル | フレンドリーで会話的なトーン |
| 学術スタイル | 正式な学術的言語 |

## 料金

| プラン | リクエスト | 設定 |
|--------|-----------|------|
| 無料 | 100/日 | Googleログインのみ |
| 自分のキー | 無制限 | OpenAI APIキー |
| 組織 | 無制限 | チーム共有キー + 分析 |

## よくある質問

### LinguaVoxはSlackで動作しますか？
はい。Slackはページレベルでキーボードイベントを傍受します。LinguaVoxは`chrome.commands.onCommand`を通じてブラウザレベルでショートカットを登録し、Slackの傍受を回避します。すべてのSlackメッセージフィールドで動作します。

### OpenAI APIキーは必要ですか？
必要ありません。無料ユーザーは共有プールから1日100リクエストを取得します。無制限使用のためにダッシュボードで自分のキーを追加できます。

### 音声は録音・保存されますか？
されません。音声はWhisperによってリアルタイムで処理され、すぐに破棄されます。音声データはどこにも保存されません。

## リンク

| | |
|--|--|
| 🌐 ウェブサイト | https://linguavox.uk |
| 📊 ダッシュボード | https://linguavox.uk/login |
| 🎤 音声翻訳 | https://linguavox.uk/voice-translation |
| ✨ AI音声強化 | https://linguavox.uk/ai-voice-enhancement |
| 🌍 非ネイティブスピーカー | https://linguavox.uk/for-non-native-speakers |
| 👤 著者について | https://linguavox.uk/about |
| 🔒 プライバシーポリシー | https://linguavox.uk/privacy/ |
| 💬 サポート | https://linguavox.uk/support/ |

## コミュニティ＆サポート

| | |
|--|--|
| 📺 YouTube | [デモ動画とチュートリアル](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox コミュニティチャンネル](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [linguavox.slack.com に参加](https://linguavox.slack.com) |

## デモ動画

| ユースケース | 視聴 |
|------------|------|
| Gmail — 音声でメールを作成 | [▶ 視聴](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — 音声メッセージ | [▶ 視聴](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — 音声ディクテーション | [▶ 視聴](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — 音声で投稿を書く | [▶ 視聴](https://youtube.com/watch?v=3WX9EmYNYjk) |
| ミーティングモード — リアルタイム字幕 | [▶ 視聴](https://youtube.com/watch?v=agcMJVPKlxE) |

## ライセンス

MIT — [LICENSE](LICENSE)を参照