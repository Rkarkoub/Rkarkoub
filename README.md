<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     BANNER — replace with your image               -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
<!-- 📸 BANNER PLACEHOLDER — drop your custom banner image here -->
<!-- <img src="YOUR_BANNER_URL" width="100%" alt="banner" /> -->
<!-- Animated typing headline -->
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=E07B54&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Raed+%F0%9F%91%8B;Builder.+Thinker.+Data+Nerd.;I+turn+ideas+into+products+that+ship.;Always+learning%2C+always+building.)
<br/>
<!-- Social badges -->
<a href="https://linkedin.com/in/raed-karkoub">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:rkarkoub03@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<img src="https://komarev.com/ghpvc/?username=raedkarkoub&style=for-the-badge&color=E07B54&label=PROFILE+VIEWS" />
</div>
---
👋 About Me
I'm Raed — a developer who genuinely loves building things. Not just for the sake of shipping code, but because there's something deeply satisfying about taking a messy real-world problem and making it clean, useful, and fast. I studied Applied Data Science at Penn State, but most of what I care about lives at the intersection of data, products, and people.
I've worked on everything from robotics predictive modeling at Rice University to building AI-powered document pipelines at a fintech consulting firm. Right now I'm most excited about the products I'm building from scratch — student housing, real estate intelligence, and financial data tooling.
When I'm not writing code, I'm probably thinking about the next thing to build. That's just how I'm wired.
🔭 Currently building CampusCribs — a full student housing marketplace
🌱 Always learning: currently deep into LLM pipelines, system design, and product thinking
💡 I believe the best tech feels invisible — it just works
🌍 Arabic/Tunisian native, English fluent, based in Pennsylvania
---
🛠️ Tech I Work With
<!-- ══ Languages ══ -->
<p align="left">
  <img src="https://skillicons.dev/icons?i=python,js,ts,flutter,mysql,firebase&theme=light" />
</p>
<!-- ══ Data & ML ══ -->
<p align="left">
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow&theme=light" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/FAISS-4A90E2?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/SentenceTransformers-FF6F00?style=flat-square&logoColor=white"/>
</p>
<!-- ══ Infra & Tools ══ -->
<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,gcp,fastapi,git&theme=light" />
  <img src="https://img.shields.io/badge/LlamaIndex-6C3483?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-Pipelines-E07B54?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoftazure&logoColor=white"/>
</p>
---
🚀 Projects
> A mix of shipped products, research tools, and things I built because I had to scratch an itch.
---
🏠 CampusCribs — Student Housing Marketplace
<!-- 📸 BANNER PLACEHOLDER -->
<!-- <img src="YOUR_CAMPUSCRIBS_BANNER" width="100%" /> -->
> *The one-stop shop for students to find apartments, meet roommates, and actually communicate with property managers — all in one place.*
Student housing is broken. Listings are scattered, roommate finding is sketchy, and managers are impossible to reach. CampusCribs fixes that.
Built to support 10K+ listings with multi-role user flows for students, listers, and managers. The platform handles listings, search & filtering, real-time messaging, authentication, and compatibility scoring — all in one clean experience.
Stack: FlutterFlow · Firebase · Firestore · Python backend · Role-based security rules
![Status](https://img.shields.io/badge/Status-Live%20%26%20Growing-brightgreen?style=flat-square)
![Role](https://img.shields.io/badge/Role-Founding%20Engineer-E07B54?style=flat-square)
---
📄 Fidelity PDF → CSV Parser — Financial Statement Intelligence
<!-- 📸 BANNER PLACEHOLDER -->
<!-- <img src="YOUR_PARSER_BANNER" width="100%" /> -->
> *Brokerage statements are a nightmare to parse. This pipeline makes them clean, structured, and queryable.*
Built a hybrid LLM + pdfplumber document parsing pipeline that turns messy multi-page Fidelity investment statements into pristine, analysis-ready CSVs. The state-machine parser tracks account context, document sections, and transaction types across pages — achieving 99.2% row-level extraction accuracy and 99.8% reconciliation accuracy.
Key challenge: PDF text extraction is chaos — merged rows, split lines, continuation records. Solved all of it.
Stack: Python · pdfplumber · LLM structure discovery · State-machine parser · Automated validation
![Accuracy](https://img.shields.io/badge/Extraction%20Accuracy-99.2%25-brightgreen?style=flat-square)
![Reconciliation](https://img.shields.io/badge/Reconciliation-99.8%25-brightgreen?style=flat-square)
---
🗽 NYC Apartment Scraper & Price Intelligence
<!-- 📸 BANNER PLACEHOLDER -->
<!-- <img src="YOUR_SCRAPER_BANNER" width="100%" /> -->
> *Real estate data is gated behind expensive APIs. This scrapes it, structures it, and actually analyzes it.*
Built a multi-source scraper pulling listings from StreetEasy, Apartments.com, and Zillow into a unified dataset. Then does what the apps don't — actual price intelligence: trend analysis, neighborhood comparisons, price-per-sqft breakdowns, and anomaly detection on rental prices across NYC boroughs.
Stack: Python · BeautifulSoup / Playwright · Pandas · Matplotlib · SQL
![Sources](https://img.shields.io/badge/Sources-StreetEasy%20%7C%20Zillow%20%7C%20Apartments.com-4A90E2?style=flat-square)
---
🧵 Garment Pattern Semantic Retrieval Engine
<!-- 📸 BANNER PLACEHOLDER -->
<!-- <img src="YOUR_GARMENT_BANNER" width="100%" /> -->
> *Search 25,000+ garment designs by meaning, not just keywords.*
Built a semantic retrieval system for garment design files. Processed 25K+ YAML/JSON files, encoded them with SentenceTransformers, indexed with FAISS, and deployed a real-time natural-language search interface on Kubernetes with a chatbot UI on GCS.
Stack: Python · SentenceTransformers · FAISS · Kubernetes · GCS · FastAPI
![Scale](https://img.shields.io/badge/Dataset-25K%2B%20Designs-blueviolet?style=flat-square)
![Deployment](https://img.shields.io/badge/Deployed-Kubernetes-326CE5?style=flat-square)
---
🤖 Financial Fraud Detection — CGAN + Autoencoder Pipeline
> *Imbalanced fraud data? Synthesize your way out of it.*
Tackled class imbalance on 24K transactions by combining SMOTE + Conditional GANs to generate 18K realistic fraud samples. Built a deep autoencoder to reconstruct normal transactions and flag anomalies, integrated with LightGBM.
Achieved 94% accuracy · 0.94 ROC-AUC · 0.91 recall.
Stack: PyTorch · Scikit-learn · LightGBM · CGAN · SMOTE
![Accuracy](https://img.shields.io/badge/Accuracy-94%25-brightgreen?style=flat-square)
![ROC-AUC](https://img.shields.io/badge/ROC--AUC-0.94-brightgreen?style=flat-square)
---
🛢️ Used Car Dealership Database System
Designed a normalized MySQL schema and ER model for dealership inventory management. Tested with mock and edge-case data for robustness.
Stack: MySQL · ER Modeling · SQL
---
💼 Experience
Junior Data Scientist / AI Engineer · Noema Consulting · Jan 2025 – Present
> Partnered with banking and infrastructure clients. Built customer segmentation models (PCA + Agglomerative Clustering on 100K+ records, silhouette = 0.78). Designed document automation tools cutting prep time by 80%. Built PII protection frameworks, test suites, and FastAPI/Docker backend utilities.
Research Intern · Rice University · May – Aug 2024
> Predictive modeling for robotics maintenance using digital twin simulations. Tested Random Forest + Neural Network models achieving **90%+ accuracy** in orientation prediction.
---
📊 GitHub Stats
<div align="center">
<!-- 📸 BANNER PLACEHOLDER — optionally swap themes -->
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=raedkarkoub&show_icons=true&theme=buefy&hide_border=true&count_private=true&include_all_commits=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raedkarkoub&layout=compact&theme=buefy&hide_border=true&langs_count=8" />
</div>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=raedkarkoub&theme=buefy&hide_border=true" />
</div>
---
🏆 Trophies
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=raedkarkoub&theme=flat&no-frame=true&column=7&margin-w=10" />
</div>
---
🐍 Contribution Snake
<div align="center">
<!-- 
  To enable this: create .github/workflows/snake.yml in your repo
  See: https://github.com/Platane/snk
<!-- <img src="https://github.com/raedkarkoub/raedkarkoub/blob/output/github-contribution-grid-snake.svg" /> -->
↑ Set up the contribution snake workflow to activate this ↑
</div>
---
🎓 Education & Certs
🎓 B.S. Applied Data Science · Penn State University · May 2025
📜 Microsoft Certified: Azure Data Scientist Associate
---
<div align="center">
"Build things that matter. Learn from everything. Ship."
<br/>
<a href="https://linkedin.com/in/raed-karkoub">
  <img src="https://img.shields.io/badge/Let's%20Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:rkarkoub03@gmail.com">
  <img src="https://img.shields.io/badge/Say%20Hi-rkarkoub03%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
</div>
