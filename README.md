# 📊 MarketMind AI

[🌐 Website](https://bhaskar2603.github.io/MarketMind_AI/) | [🤖 Backend Model](https://huggingface.co/spaces/Bhaskar2611/marketmind) | [💻 GitHub Repo](https://github.com/Bhaskar2603/MarketMind_AI)

**MarketMind AI** is an AI-powered market intelligence tool that converts **real-time Google search data** into actionable business insights. Whether you're a startup founder validating a new idea, an SEO expert researching keywords, or an investor analyzing trends—**MarketMind** acts as your co-pilot.

Built using **Gradio**, **Serpstack API**, and the **Qwen2.5-7B-Instruct** LLM, this tool provides deep insights into:
- Competitor analysis
- Keyword research
- Trend discovery
- Idea validation

---

## 🧠 Project Overview

> “Your AI-Powered Market Intelligence Co-Pilot.”

**MarketMind AI** combines real-time search intelligence with LLM-based summarization to transform unstructured web data into structured business advice.

---

## ⚙️ Tools & Tech Stack

| Component          | Tool / API                                   |
|-------------------|----------------------------------------------|
| Search API         | Serpstack                                    |
| Language Model     | Qwen2.5-7B-Instruct (Hugging Face)           |
| Frontend           | Gradio                                       |
| Deployment         | Hugging Face Spaces                          |
| Hosting            | GitHub Pages                                 |

---

## 📦 Project Architecture

```
User Input (Gradio UI)
       ↓
Agent Logic (agent.py)
       ↓
Serpstack API → Google Search Results
       ↓
Qwen2.5 LLM → Insight Generation
       ↓
Formatted Markdown Output
```

---

## 🚀 Features

### 1. 🏢 Competitor Analysis
- Input: Competitor Website (e.g., `zomato.com`)
- Output: SWOT analysis, pricing benchmarks, user sentiment

### 2. 🔍 Keyword Research
- Input: Topic (e.g., "vegan restaurants")
- Output: Trending keywords, CPC data, SEO suggestions

### 3. 📈 Trend Discovery
- Input: Industry or niche (e.g., "AI startups")
- Output: Viral content, trend spikes, opportunity areas

### 4. 💡 Idea Validation
- Input: Business idea (e.g., "Plant-based meal kit")
- Output: Market demand score, saturation level, go-to-market tips

---

## 🧩 UI Flow

```
User Selects Analysis Type
       ↓
Provide Query/Input
       ↓
Gradio App Calls Backend
       ↓
LLM Generates Markdown Response
       ↓
User Sees Business Insights
```

---

## 📌 Use Cases

| Use Case              | Who Benefits                  | Value Provided                               |
|-----------------------|-------------------------------|----------------------------------------------|
| Market Research       | Founders, Entrepreneurs        | Reduces guesswork before investing           |
| SEO Optimization      | Marketers, Bloggers            | Keyword and content gap analysis             |
| Competitive Strategy  | Product Managers               | Understand competitors and improve strategy  |
| Trend Monitoring      | Analysts, Investors            | Catch emerging trends early                  |

---


## 📊 Example Output

### 🧪 Idea Validation – "Plant-Based Meal Kit"
```
- Market Demand: 8/10
- Competitor Saturation: Medium (5–10 players)
- Pricing Benchmark: ₹800–1,200 per kit
- Suggestions: Focus on Tier-1 cities & subscription model
```

### 🔍 Keyword Research – "Vegan Restaurants"
```
1. vegan restaurants near me (CPC: ₹80)
2. best vegan delivery (CPC: ₹60)
3. vegan food Mumbai (CPC: ₹45)
```

### 💼 SWOT for Zomato
```
Strengths: Market leader in India, solid brand
Weaknesses: Thin margins, delivery charges
Opportunities: Cloud kitchens, Tier-2 cities
Threats: Growing competition from Swiggy
```

---

## 🌱 Future Enhancements

- 🧾 **PDF Export** – Download insights as structured reports  
- 🌐 **Multi-LLM Support** – Add Mistral, LLaMA 3 as options  
- 📊 **Historical Search Trends** – Show change over time  
- 👥 **Team Collaboration** – Shared dashboards  
- 🔗 **API Access** – For integration into other platforms  

---

## 👨‍💻 Author

**Jyothula Bhaskar**  
B.Tech in Computer Science & Engineering (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/bhaskar-jyothula-974bbb271/) | [Hugging Face](https://huggingface.co/Bhaskar2611) | [GitHub](https://github.com/Bhaskar2603) | [Kaggle](https://www.kaggle.com/bhaskarjyothula)

---

## 🙏 Acknowledgements

- Hugging Face Spaces and LLM community  
- Open-source model contributors (Qwen team)  
- Medium Digest for trend inspirations  
- Serpstack for real-time SERP data access

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full terms.

