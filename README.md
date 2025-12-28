# 📊 Automated Daily AI Trend Analysis Workflow (n8n)

<img width="980" height="372" alt="TrendyAI workflow (n8n)" src="https://github.com/user-attachments/assets/c3815b48-eeb1-460b-8877-2a6415e9c444" />


This repository documents an **n8n-based automated workflow** that **automatically discovers trending topics in Artificial Intelligence**, generates AI-powered insights, and exports a **daily AI trend report as a PDF**.

The workflow continuously monitors recent developments in AI, enriches findings with real-time web data, and delivers clean, professional reports without manual effort.

---

## 🔥 What This Workflow Does

- Automatically **identifies top trending AI topics from the past 7 days**
- Highlights **key developments, breakthrough technologies, and major announcements**
- Detects **emerging AI trends**
- Enriches insights with **real-time web search**
- Generates **AI-written summaries and analysis**
- Produces **daily PDF AI trend reports**
- Runs **fully automated on a schedule**

---

## 🧠 Workflow Overview

The workflow runs on a daily schedule and follows this sequence:

1. **Trigger** – Executes automatically at a scheduled time  
2. **AI Agent** – Researches and analyzes AI trends from the past 7 days  
3. **Web Search (Tavily)** – Fetches current context, news, and signals  
4. **Markdown → HTML** – Converts AI output into HTML  
5. **HTML → PDF** – Exports the final AI trend report as a PDF  

---

## 🔁 Workflow Architecture

