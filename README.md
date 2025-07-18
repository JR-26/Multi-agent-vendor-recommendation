# 🛒 AI-Powered Product Recommendation System

**Reimagining Retail with Multi-Agent AI and Real-Time Trend Insights**

This project is an AI-driven shopping assistant that delivers intelligent product recommendations, personalized summaries, and real-time trend analytics using cutting-edge large language models and Google Shopping data. The final result is rendered on a Django-based web interface for a seamless and interactive user experience.

---

## 🚀 Features

- **Natural Language Understanding**  
  Parses queries like _“Looking for earphones under 1000”_ to extract product type and budget.

- **Real-Time Product Search**  
  Fetches accurate product data from Google Shopping via SerpAPI.

- **Multi-Agent Intelligence**  
  Uses CrewAI agents powered by Groq's LLaMA 3.1-8B model:
  - 🧠 **Product Researcher**: Creates product summary tables.
  - 💡 **Product Recommendation Specialist**: Selects and justifies the best choice.
  - 📈 **Trend Analyst**: Analyzes popularity trends using Google Trends.

- **Visual Trend Insights**  
  Generates interest-over-time charts with Matplotlib and Seaborn.

- **Frontend Integration**  
  Renders complete output in a Django-based web UI (not just a Markdown file).

---

## 🛠️ Tech Stack

| Component                | Technology Used                      |
|--------------------------|--------------------------------------|
| Language                 | Python                               |
| Web Framework            | Django                               |
| Multi-Agent Framework    | [CrewAI](https://github.com/joaomdmoura/crewAI)         |
| LLM Provider             | Groq – LLaMA 3.1-8B                  |
| Product Data Source      | [SerpAPI](https://serpapi.com/)      |
| Trend Data Source        | [PyTrends](https://github.com/GeneralMills/pytrends)     |
| Data Visualization       | Matplotlib, Seaborn                  |
| Frontend Output Format   | Markdown + HTML Rendering in Django  |

---
