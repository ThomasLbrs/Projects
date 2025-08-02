# 🧠 AI-Powered UX Projects

This page showcases four AI-based projects I developed to explore how machine learning can enhance UX analysis, visual search, and user behavior understanding. All projects are fully functional, containerized with Docker, and deployed online.

🌐 [See full portfolio site](https://thomaslebras5.wixsite.com/thomaslebras)  
🎯 [Jump directly to the portfolio section](https://thomaslebras5.wixsite.com/thomaslebras/portfolio)

---

## 🎨 [DeepUX](https://thomaslebras5.wixsite.com/thomaslebras/deepux)  
**Evaluate the user experience of a webpage in one click.**

A deep neural network predicts UX dimensions (e.g., aesthetics, trustworthiness) directly from a screenshot.  
Ideal for benchmarking and identifying design improvements before user testing.

- 🧩 Input: Screenshot of a webpage  
- 📈 Output: Scores across UX dimensions (e.g., Prototypicality, Trustworthiness, Aesthetics)  
- 🔍 Under the hood: Fine-tuned ResNet trained on annotated UX datasets  
- 🐳 Dockerized FastAPI backend  
- ☁️ Deployed with: Cloud Run (API) + Netlify (frontend)

---

## 👀 [AttentionAI](https://thomaslebras5.wixsite.com/thomaslebras/attentionai)  
**Predict where users will look — before they even do.**

Simulates eye-tracking with AI to generate heatmaps from any visual interface (ads, apps, websites).  
Based on real human eye-tracking data, trained with deep learning.

- 🖼️ Input: Any image (UI, ad, landing page)  
- 🔥 Output: Heatmap showing predicted visual attention  
- 🧠 Model: U-Net variant trained on large eye-tracking datasets  
- 🐳 Dockerized backend running inference  
- ☁️ Deployed with: Cloud Run + Vertex AI jobs

---

## 🔎 [SearchAI](https://thomaslebras5.wixsite.com/thomaslebras/copie-de-attentionai-1)  
**A semantic search engine for artwork discovery.**

Enables users to search through hundreds of museum pieces using natural language.  
Embeddings are computed for both queries and documents to retrieve the most semantically similar artworks.

- 🧑‍🎨 Dataset: 300+ public domain artworks from The MET API  
- 🧠 Embeddings: SentenceTransformer for both text and image descriptions  
- 🔍 Vector-based similarity search  
- 🐳 Dockerized FastAPI backend  
- ☁️ Deployed with: Cloud Run (API) + Netlify (frontend)

---

## 🖱️ [CursorAI](https://thomaslebras5.wixsite.com/thomaslebras/copie-de-attentionai)  
**Measure user engagement from their mouse movements.**

Predicts engagement level in under 15 seconds using only cursor behavior.  
Useful for early-stage UX evaluations or dynamic personalization.

- 🖱️ Input: Behavioral mouse data  
- 📈 Output: Binary classification: High vs. Low Engagement  
- 🧠 Model: Traditional ML algorithm trained on cursor trajectories  
- 🐳 Dockerized backend  
- ☁️ Deployed with: Cloud Run (API) + Netlify (frontend)

---

## 🧪 Want to try them?

Each project has a live demo on my website.  
Feel free to explore or reach out via [my portfolio](https://thomaslebras5.wixsite.com/thomaslebras).
