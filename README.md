# 📊 AI Competitor Analysis from Customer Reviews

## 📌 Overview
Project ini bertujuan untuk menganalisis ulasan pelanggan dari kompetitor menggunakan AI untuk menghasilkan insight yang dapat digunakan dalam strategi bisnis.

This system processed 600+ reviews to identify customer sentiment and key product feedback trends.

## 🚨 Problem
- Review pelanggan tersebar di berbagai platform
- Analisis manual memakan waktu lama
- Sulit mengidentifikasi insight dari ratusan review

## 💡 Solution
Membangun workflow automation berbasis AI untuk:
- Scraping data review secara otomatis
- Melakukan sentiment analysis (positif, netral, negatif)
- Mengidentifikasi topik utama
- Menghasilkan insight siap pakai

⚙️ Tech Stack
n8n
Apify
AI Agent (LLM-based analysis)
Google Sheets
🔍 Key Features
Automated review scraping
Sentiment classification
Topic extraction
Insight generation
📊 Impact
Menganalisis ratusan review dalam hitungan menit
Membantu memahami kebutuhan pelanggan
Mendukung strategi bisnis berbasis data
⚠️ Limitations
Bergantung pada kualitas data
Potensi bias model AI
API usage cost
📄 Documentation

See full documentation in AI-Workflow_Analisis_Kompetitor.pdf

## 🧠 Workflow Architecture

```mermaid
flowchart TD
    A[Review Source] --> B[Data Scraping]
    B --> C[Data Cleaning]
    C --> D[AI Sentiment Analysis]
    D --> E[Topic Extraction]
    E --> F[Insight Generation]
    F --> G[Store to Google Sheets]
