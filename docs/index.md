---
---
AI-powered automation — agents, pipelines, no-code flows

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

## 🔧 Real automation stacks

| Need | Tool |
|---|---|
| No-code flows | n8n (self-host), Zapier, Make |
| Agent automations | Flowise, LangFlow |
| Data pipelines | Airbyte + dbt + LLM steps |
| Email | Superhuman AI, Shortwave |
| Meetings | Otter, Fireflies, tl;dv |
| Scraping+AI | Browse AI, Apify actors |

## 💡 High-ROI automations

1. Inbox triage → draft replies → human approve
2. Meeting → summary → tasks to tracker
3. Form submission → enrichment → CRM
4. Support ticket → classify → route → draft answer

---
Maintained by [aixisstudio](https://github.com/aixisstudio).