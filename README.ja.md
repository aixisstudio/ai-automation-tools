# Ai Automation Tools

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

AI 自動化ツール

## ❀ プラットフォーム
| ツール | ノート |
|---|---|
|【n8n】(https://github.com/n8n-io/n8n) | OSS ワークフローの自動化 + AI ノード — セルフホスティング |
| 【フローズ】(https://github.com/FlowiseAI/Flowise) | ドラッグドロップLMパイプライン |
| [Dify](https://github.com/langgenius/dify) | フルLMアプリプラットフォーム(エージェント、RAG、ワークフロー) |
| 【アクティブピース】(https://github.com/activepieces/activepieces) | OSS Zapier 代替品 |
| 【Zapier AI】(https://zapier.com/) | ノーコード+AIアクション |
| 【メイク】(https://www.make.com/) | ビジュアルシナリオ+AIモジュール |

## ✔ エージェントフレームワーク
| ツール | ノート |
|---|---|
| 【クルーアイ】(https://github.com/crewAIInc/crewAI) | 複数エージェントクルー |
| 【AutoGen】(https://github.com/microsoft/autogen) | エージェントの会話 |
| 【ラングラフ】(https://github.com/langchain-ai/langgraph) | ステートフル エージェント グラフ |
| [試薬](https://github.com/huggingface/smolagents) | HF 最小限の剤 |

## ドキュメントパイプライン
| ツール | ノート |
|---|---|
| 【ドキュメント】(https://github.com/docling-project/docling) | PDF/docs → 構造データ |
| [非構成](https://github.com/Unstructured-IO/unstructured) | ドキュメント → LLM-ready チャンク |
| 【Firecrawl】(https://github.com/mendableai/firecrawl) | LLMのクリーンマークダウン |

## ️️ DIY スタック
```
trigger (cron/webhook) → fetch data → LLM step(s) → validate → act (API/db/notify)
```
簡単なスタート: 1 cron + 1 LLM コール + 1 つのアクション。 エージェントは後から来ることができます。

## ❀ リアルオートメーションスタック

| お問い合わせ | ツール |
|---|---|
| ノーコードフロー | n8n(セルフホスト)、Zapier、メイク |
| エージェントの自動化 | フローズ・ランフロー |
| データパイプライン | エアバイト + dbt + LLM ステップ |
| メール | 超人AI・短波 |
| 会議 | オッター・ホタル・タル・テレビ |
| Scraping+AI | AIを閲覧し、俳優を承認 |

## ✔ ROI の自動化

1. 受信トレイのトリアージ → ドラフトの返信 → 人間の承認
2. 会議 → 要約 → トラッカーへのタスク
3. フォーム送信 → 充実 → CRM
4. サポートチケット → 分類 → ルート → 回答草案

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
