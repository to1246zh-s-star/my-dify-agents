# my-dify-agents# 🤖 Super Personal Assistant - Dify Chatflow Agent

[![Dify](https://img.shields.io/badge/Dify-v0.6+-blue.svg)](https://dify.ai/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An advanced, all-in-one AI Personal Assistant built using **Dify Chatflow**. This intelligent agent seamlessly integrates large language models (LLMs), multi-modal generation (text-to-image/video), Model Context Protocol (MCP) cloud tool ecosystem, and enterprise-grade SQL database querying with rich BI data visualization capabilities.

---

## 🌟 Core Features

The agent utilizes a smart **Intent Classifier** as its core router, automatically identifying user requests and dispatching them to one of the five specialized modules:

1. **Daily General Assistant**: A customized lifestyle and workplace consultant driven by expert-level system prompts for general Q&A.
2. **Professional Copywriting Optimizer**: A dedicated text refiner and expander that follows strict conversion-oriented copywriting principles, automatically generating structured, high-conversion copy exceeding 500 words.
3. **Multi-modal Creator**: Powered by the **Volcengine Doubao Plugin**, enabling high-quality **Text-to-Image (T2I)** and **Text-to-Video (T2V)** generation directly from text prompts.
4. **MCP Toolbox (Gaode Maps & Life Assistant)**：Connected to the ModelScope MCP marketplace via SSE mode, interacting with the Gaode Maps Open Platform API to provide real-time route planning, nearby food recommendations, and news briefings.
5. **SQL Data Pipeline & Dashboard**: Integrated with the `rookie-text2data` plugin, allowing direct connection to relational databases for natural-language-to-SQL queries, and leveraging BI chart extensions to automatically generate **column, line, and pie charts**.

---

## 🛠️ Workflow Architecture

The full architecture of the Dify Chatflow orchestration is illustrated below:
