# Ai Automation Tools

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Автоматизация с ИИ — агенты и пайплайны

##Платформы
| Инструмент | Примечание
|---|---|
| [n8n] (https://github.com/n8n-io/n8n) | Автоматизация рабочего процесса OSS + узлы AI — самоуправляемые |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Drag-drop LLM трубопроводы |
| [Dify] (https://github.com/langgenius/dify) | Полная платформа приложений LLM (агенты, RAG, рабочие процессы) |
https://github.com/activepieces/activepieces - альтернатива OSS Zapier
| [Zapier AI] (https://zapier.com/) | Без кода + действия ИИ |
| [Make](https://www.make.com/) | Визуальные сценарии + модули ИИ |

##  framework фреймворки агентов
| Инструмент | Примечание
|---|---|
[CrewAI] (https://github.com/crewAIInc/crewAI) | Многоагентные экипажи
[AutoGen] (https://github.com/microsoft/autogen) | Разговоры агентов |
[LangGraph] (https://github.com/langchain-ai/langgraph) | Графики состояния агента |
[smolagents] (https://github.com/huggingface/smolagents) | HF минимальные агенты

## Документные трубопроводы
| Инструмент | Примечание
|---|---|
| [Docling] (https://github.com/docling-project/docling) | PDF/docs → структурированные данные |
[Неструктурированный] (https://github.com/Unstructured-IO/unstructured) Любой документ → LLM-готовые куски
[Firecrawl] (https://github.com/mendableai/firecrawl) | Web → чистая разметка для LLM

##  ️ DIY стек
```
trigger (cron/webhook) → fetch data → LLM step(s) → validate → act (API/db/notify)
```
Начните с простого: один крон + один вызов LLM + одно действие. Агент может прийти позже.

###Настоящая автоматизация

Потребность в инструменте
|---|---|
| No-code flows | n8n (self-host), Zapier, Make |
Автоматизация агентов Flowise, LangFlow
| Трубопроводы данных | Шаги Airbyte + dbt + LLM
Оригинальное название: Superhuman AI, Shortwave
Выдра, светлячки, tl;dv |
Скриншоты из игры Scraping+AI, Browse AI, Apify

## - Автоматизация с высокой рентабельностью инвестиций

1.Сортировка почтовых ящиков → проект ответов → одобрение человека
2. Встреча → резюме → задачи по отслеживанию
3.Подача формы → обогащение → CRM
4. билет поддержки → классифицировать → маршрут

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
