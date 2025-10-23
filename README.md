# 自分AI 簡易版 Lv.1

**静岡マーケサロン配布用 | 書籍「自分AIの作り方」実践テンプレート**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![関連プロジェクト](https://img.shields.io/badge/関連-書籍プロジェクト-blue)](https://github.com/myucakhr/book-publishing-project)

---

## 📚 このプロジェクトについて

このリポジトリは、**書籍「自分AIの作り方」（仮）のLv.1簡易版**として実装されたテンプレート集です。

- **関連プロジェクト**: [book-publishing-project](https://github.com/myucakhr/book-publishing-project)
- **書籍の位置づけ**: 第1章「自分AI Lv.1簡易版」の実装例
- **対象読者**: マーケター、経営者、個人事業主

---

## 🎯 自分AIとは？

**あなた専用のAIアシスタント**です。

あなたの価値観、話し方、経験を学習して、メール返信、タスク整理、コンテンツ作成など、**あなたらしいサポート**をしてくれます。

---

## 🚀 クイックスタート

### 1. このリポジトリをクローン

```bash
git clone https://github.com/myucakhr/jibun-ai-lv1-simple.git
cd jibun-ai-lv1-simple
```

### 2. Google Driveにアップロード

フォルダ全体をGoogle Driveにアップロードします。

### 3. Gemini Gemsに設定

1. [Gemini](https://gemini.google.com)を開く
2. 「Gems」→「新規Gem作成」
3. 以下のファイルをGoogle Driveから追加：
   - `00_自分AI_システムプロンプト.md`
   - `knowledge/My_Values.md`
   - `knowledge/My_CommunicationStyle.md`
   - `knowledge/My_Episodes.md`
   - `modes/`配下の5ファイル
4. Gem名を「自分AI」に設定
5. 保存

### 4. 自分の情報を記入

`knowledge/`フォルダの3ファイルに、自分の情報を記入します。

---

## 📁 ファイル構成

```
jibun-ai-lv1-simple/
├── 00_自分AI_システムプロンプト.md  ← AIへの指示（ルーター）
├── knowledge/                        ← データベース層
│   ├── My_Values.md                 ← あなたの価値観
│   ├── My_CommunicationStyle.md     ← あなたの話し方
│   └── My_Episodes.md               ← あなたの経験
├── modes/                            ← 実行層（5つの専門Mode）
│   ├── mode1_update.md              ← 日々の記録
│   ├── mode2_maintenance.md         ← 週次メンテナンス
│   ├── mode3_task_management.md     ← タスク整理
│   ├── mode4_email.md               ← メール作成
│   └── mode5_content_generation.md  ← コンテンツ生成
└── README.md                         ← 使い方ガイド
```

---

## 💡 5つのMode

| Mode | 用途 | 使用頻度 |
|------|------|---------|
| **Mode1: Update** | 日々の記録・更新 | 毎日 |
| **Mode2: Maintenance** | メンテナンス | 週次 |
| **Mode3: Task** | タスク整理 | 毎日 |
| **Mode4: Email** | メール作成・返信 | 随時 |
| **Mode5: Content** | コンテンツ生成 | 随時 |

---

## 📚 関連プロジェクト

### 書籍「自分AIの作り方」

- **リポジトリ**: [book-publishing-project](https://github.com/myucakhr/book-publishing-project)
- **Issue**: [#1 - 【書籍PJ】Lv.1簡易版の実装](https://github.com/myucakhr/book-publishing-project/issues/1)

### レベル構成

| レベル | 内容 | リポジトリ |
|--------|------|-----------|
| **Lv.1** | 簡易版（本リポジトリ） | [jibun-ai-lv1-simple](https://github.com/myucakhr/jibun-ai-lv1-simple) |
| Lv.2 | カレンダー・Gmail API連携 | 開発予定 |
| Lv.3 | GitHub・Slack連携 | 開発予定 |

---

## 🛠️ 技術スタック

- **AIツール**: Gemini Gems（推奨）、ChatGPT、Claude
- **ストレージ**: Google Drive
- **言語**: Markdown
- **バージョン管理**: Git/GitHub

---

## 📝 使用例

### 例1：日々の記録（Mode1）

```
あなた：「今日はA社との打ち合わせで、相手の本音を引き出せた」

自分AI：「My_Episodes.mdに追加する内容を整理しました...」
```

### 例2：タスク整理（Mode3）

```
あなた：「今日のタスクを整理して
       ・提案書作成
       ・メール返信」

自分AI：「優先順位を付けました：
        1. 提案書作成（2時間）
        2. メール返信（30分）
        Googleカレンダーへの追加方法：...」
```

---

## 🤝 コントリビューション

このプロジェクトは書籍プロジェクトの一部ですが、改善提案や機能追加のPRを歓迎します。

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

---

## 📄 ライセンス

MIT License - 詳細は [LICENSE](LICENSE) ファイルを参照

---

## 👤 作成者

**宮内章宏（SmartFlow）**

- GitHub: [@myucakhr](https://github.com/myucakhr)
- 関連: [書籍プロジェクト](https://github.com/myucakhr/book-publishing-project)

---

## 🙏 謝辞

- 静岡マーケサロンの皆様
- YELLOWコミュニティの勉強会参加者の皆様

---

**自分AIを育てて、あなたらしい働き方を実現しましょう！**
