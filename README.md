<h1 align="center">
  Raed Karkoub
</h1>

<p align="center">
  <strong>Data Systems · Backend · Product Builder</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/raed-karkoub">
    <img src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" width="48" />
  </a>
  <a href="mailto:rkarkoub03@gmail.com">
    <img src="https://img.icons8.com/?size=100&id=tnnUFgHrPmR0&format=png&color=000000" width="48" />
  </a>
</p>

<p align="center">
  I build practical systems that turn messy information into usable products.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Builder-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Systems-111827?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Data-Workflows-0F766E?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Product-Minded-7C3AED?style=for-the-badge" />
</p>

---

<p align="center">
  <a href="#about-me">About</a> ·
  <a href="#what-im-building">What I'm Building</a> ·
  <a href="#selected-work">Selected Work</a> ·
  <a href="#experience">Experience</a> ·
  <a href="#contact">Contact</a>
</p>

---

## About Me

I’m someone who likes finding solutions.

What excites me most about technology is how much you can build with just a computer: a better workflow, a cleaner system, a tool that saves people time, or a product that makes something frustrating feel simple. I’m especially drawn to messy problems at the start: scattered information, inefficient processes, and clunky experiences that need structure.

I studied Applied Data Science at Penn State because I was drawn to the idea of using statistical methods to build fast, predictive systems. Combined with my drive to innovate and build, that foundation pushed me toward creating systems that are practical, scalable, and actually useful.

---

## What I'm Building

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Products</strong><br/>
      Tools that solve real, specific problems.
    </td>
    <td width="33%" valign="top">
      <strong>Data Systems</strong><br/>
      Pipelines and workflows that make messy information usable.
    </td>
    <td width="33%" valign="top">
      <strong>Useful Software</strong><br/>
      Things that save time, reduce friction, and actually get used.
    </td>
  </tr>
</table>

---

## Selected Work

## Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 CampusCribs</h3>
      <strong>Student housing marketplace</strong><br/><br/>

      <strong>Problem</strong><br/>
      Student housing is fragmented across listings, roommate search, and communication platforms. Users are forced to switch between tools, lose context, and deal with slow or disconnected workflows.<br/><br/>

      <strong>Solution</strong><br/>
      Built a unified platform that combines listings, roommate matching, and direct messaging into a single system designed around how students actually search and decide.<br/><br/>

      <strong>Impact</strong><br/>
      Reduced friction across the full flow (discovery → matching → communication), creating a more continuous and usable housing experience.<br/><br/>

      <strong>Stack</strong><br/>
      FlutterFlow · Firebase · Python

      <br/><br/>
      <details>
        <summary><strong>Inside the system</strong></summary>
        <br/>
        • role-based architecture for students, listers, and property managers<br/>
        • compatibility-driven roommate matching logic<br/>
        • messaging system tightly integrated with listing interactions<br/>
        • structured backend to support scaling listings, users, and engagement<br/>
      </details>
    </td>

    <td width="50%" valign="top">
      <h3>📄 Financial Document Parser</h3>
      <strong>Hybrid PDF extraction pipeline</strong><br/><br/>

      <strong>Problem</strong><br/>
      Financial statements contain high-value data but are locked inside inconsistent, multi-page PDFs that break traditional parsing approaches.<br/><br/>

      <strong>Solution</strong><br/>
      Built a hybrid pipeline that uses LLMs to understand document structure and deterministic parsing logic to extract structured data reliably.<br/><br/>

      <strong>Impact</strong><br/>
      Converted messy, unstructured documents into analysis-ready datasets with high accuracy, enabling reliable downstream analytics.<br/><br/>

      <strong>Stack</strong><br/>
      Python · pdfplumber · LLMs

      <br/><br/>
      <details>
        <summary><strong>Inside the system</strong></summary>
        <br/>
        • LLM-based structure discovery to detect sections and layouts<br/>
        • state-based parsing to track account context and transitions<br/>
        • custom handlers for trades, transfers, and summary sections<br/>
        • achieved 99.2% row-level accuracy and 99.8% reconciliation accuracy<br/>
      </details>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3>🗽 NYC Price Intelligence</h3>
      <strong>Rental data pipeline + analytics</strong><br/><br/>

      <strong>Problem</strong><br/>
      Rental data is scattered across platforms, inconsistent in structure, and difficult to analyze in a unified way.<br/><br/>

      <strong>Solution</strong><br/>
      Built a scraping and normalization pipeline that collects listings across sources and transforms them into a clean, structured dataset.<br/><br/>

      <strong>Impact</strong><br/>
      Enabled cross-platform comparisons, pricing analysis, and trend discovery that wouldn’t be possible with isolated data sources.<br/><br/>

      <strong>Stack</strong><br/>
      Python · Crawl4AI · Playwright · Pandas · SQL

      <br/><br/>
      <details>
        <summary><strong>Inside the system</strong></summary>
        <br/>
        • dynamic scraping across JS-heavy listing platforms<br/>
        • persistent browser sessions to handle anti-bot friction<br/>
        • cross-source normalization for consistent schema<br/>
        • pipeline designed for analytics and modeling use cases<br/>
      </details>
    </td>

    <td width="50%" valign="top">
      <h3>🧵 Garment Retrieval Engine</h3>
      <strong>Semantic search system</strong><br/><br/>

      <strong>Problem</strong><br/>
      Keyword-based search fails when users want to find designs based on meaning, style, or similarity rather than exact metadata.<br/><br/>

      <strong>Solution</strong><br/>
      Built a semantic retrieval engine using embeddings and vector search to enable natural language queries.<br/><br/>

      <strong>Impact</strong><br/>
      Enabled fast, intuitive search across thousands of design files using meaning instead of exact matches.<br/><br/>

      <strong>Stack</strong><br/>
      Python · SentenceTransformers · FAISS · FastAPI

      <br/><br/>
      <details>
        <summary><strong>Inside the system</strong></summary>
        <br/>
        • processed and indexed 25K+ garment design files<br/>
        • dense vector embeddings for semantic similarity<br/>
        • FAISS-powered retrieval for low-latency queries<br/>
        • API-based architecture for real-time search workflows<br/>
      </details>
    </td>
  </tr>
</table>

---

## Experience

### Noema Consulting
**AI / Data Systems**

Built and improved backend tools, document intelligence workflows, and PII-safe ingestion systems for enterprise-facing use cases.

### Rice University
**Robotics / Machine Learning**

Worked on predictive modeling for mechanical systems using simulation, system behavior, and time-series features, reaching 90%+ accuracy.

---

## Contact

<p>
  <strong>LinkedIn:</strong>
  <a href="https://linkedin.com/in/raed-karkoub">linkedin.com/in/raed-karkoub</a>
  <br/>
  <strong>Email:</strong>
  <a href="mailto:rkarkoub03@gmail.com">rkarkoub03@gmail.com</a>
</p>
