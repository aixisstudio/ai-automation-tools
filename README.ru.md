# Ai Automation Tools

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Автоматизация с ИИ — агенты и пайплайны

_Подробное содержимое (списки, ссылки, описания) ведётся на английском — разделы ниже помогут сориентироваться._

## 🔧 Platforms
| Tool | Note |
|---|---|
| [n8n](https://github.com/n8n-io/n8n) | OSS workflow automation + AI nodes — self-hostable |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Drag-drop LLM pipelines |
| [Dify](https://github.com/langgenius/dify) | Full LLM app platform (agents, RAG, workflows) |
| [Activepieces](https://github.com/activepieces/activepieces) | OSS Zapier alternative |
| [Zapier AI](https://zapier.com/) | No-code + AI actions |
| [Make](https://www.make.com/) | Visual scenarios + AI modules |

## 🤖 Agent frameworks
| Tool | Note |
|---|---|
| [CrewAI](https://github.com/crewAIInc/crewAI) | Multi-agent crews |
| [AutoGen](https://github.com/microsoft/autogen) | Agent conversations |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Stateful agent graphs |
| [smolagents](https://github.com/huggingface/smolagents) | HF minimal agents |

## 📄 Document pipelines
| Tool | Note |
|---|---|
| [Docling](https://github.com/docling-project/docling) | PDF/docs → structured data |
| [Unstructured](https://github.com/Unstructured-IO/unstructured) | Any doc → LLM-ready chunks |
| [Firecrawl](https://github.com/mendableai/firecrawl) | Web → clean markdown for LLMs |

## 🏗️ DIY stack
```
trigger (cron/webhook) → fetch data → LLM step(s) → validate → act (API/db/notify)
```
Start simple: one cron + one LLM call + one action. Agentic can come later.

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
