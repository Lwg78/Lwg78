### Hi there, I'm Wen Gio 👋
**Bridging Retail Operations & Artificial Intelligence.**

I am a Retail Ops Professional transitioning into AI Engineering. I build practical systems that solve real-world problems—from automating stocktake variances to decoding genomic sequences.

---

### 🛠️ Technical Arsenal
* **Languages:** Python (Pandas, PyTorch, NumPy)
* **Engineering:** Docker, GitHub Actions (CI/CD), FastAPI, Streamlit
* **Focus:** Process Automation, Deep Learning, Data Engineering

---

## 📂 Portfolio Projects

### 🐻 Memory Bear: Cognitive Edge AI on Legacy Hardware
**[View Repository](https://github.com/lwg78/memory-bear-legacy-edge)**

> *Engineered a local, cognitive AI agent capable of running on constrained legacy hardware (2017 MacBook Air) by implementing biologically inspired memory optimization.*

**The Challenge:**
Running modern Large Language Models (LLMs) requires massive compute. Standard RAG (Retrieval Augmented Generation) often floods the limited context window of small models with irrelevant noise, leading to "amnesia" or hallucinations.

**The Solution:**
I built a **Cognitive Architecture** that mimics the human brain's memory consolidation process. Instead of a simple FIFO buffer, I implemented a **Dynamic Forgetting Curve** ($R = e^{-t/S}$) to filter information based on salience and rehearsal.

**Key Engineering Achievements:**
* **Edge Optimization:** Successfully deployed a quantized **Phi-3 Mini (3.8B)** model on a Dual-Core Intel i5 CPU with only 8GB RAM.
* **Cognitive RAG:** Integrated **Episodic Memory** (Vector DB) and **Semantic Memory** (Knowledge Graph) for human-like recall.
* **Algorithm Design:** Validated the **Ebbinghaus Decay** algorithm via EDA simulations, reducing context token load by ~60% while retaining critical long-term facts.
* **Dependency Resolution:** Solved critical ABI conflicts between modern AI libraries (`NumPy 2.x`, `PyTorch`) and legacy macOS environments.

**Tech Stack:** `Python`, `Llama.cpp`, `ChromaDB`, `NetworkX`, `Phi-3`, `Quantization`

### 🛒 Retail Operations & Supply Chain AI
*My core focus: Bringing engineering rigor to supermarket logistics.*

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[FreshGuard V2 (Retail Waste)](https://github.com/Lwg78/retail-waste-management-v2)** | **🚀 Flagship.** Production-grade forecasting engine reducing perishable waste. Features **Docker**, **CI/CD**, and **Streamlit**. *The engineered evolution of V1.* | Python, Docker, Pytest, Holt-Winters |
| **[Stocktake Variance Reporter](https://github.com/Lwg78/Stocktake-Variance-Reporter)** | **Automation Tool.** A full-stack utility designed to cut stocktake reporting time by 99%. Includes "Theft Detection" logic and a web UI. | FastAPI, Docker, Pandas |
| **[Enterprise Retail Solution](https://github.com/Lwg78/Enterprise-Solution-for-Supermarket-style-retail)** | **Advanced R&D.** A predictive analytics experiment utilizing **Armstrong Cycle Transformers** to forecast complex sales demand patterns. | Time-Series, PyTorch Transformers |
| **[Retail Waste System (V1)](https://github.com/Lwg78/retail-waste-management-system)** | **Prototype.** My initial menu-driven application for inventory tracking. Focuses on core CRUD operations and basic analytics. | Python, Matplotlib, Pandas |

### 🧠 AI Engineering & Search Systems
*Building efficient, modular systems for real-world constraints.*

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[Silver Retriever](https://github.com/Lwg78/Silver-Retriever)** | **Offline RAG System.** A modular search engine designed for legacy hardware (No GPUs). Features a **Plugin Architecture** ("The Brain") to detect user intent (Deadlines, Tasks) using TF-IDF instead of heavy LLMs. Includes **CI/CD** and **Smart Chunking**. | Python, Streamlit, Scikit-Learn, GitHub Actions |

### 🧬 Bio-Informatics & Deep Learning
*Applying AI to decode complex genomic sequences.*

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[Genomic Decoder V2](https://github.com/Lwg78/genomic-decoder-v2)** | **Advanced Pipeline.** Refined Deep Learning architecture for DNA sequencing. Focuses on modular code structure and improved inference performance over the original. | PyTorch, BioPython, CI/CD |
| **[Genomic Decoder (FlyOS)](https://github.com/Lwg78/genomic-decoder-fly)** | **Research Implementation.** An end-to-end pipeline that reads raw DNA sequences to predict gene expression. Features **O(1) lazy-loading** for massive datasets. | PyTorch, Transformers |

### 🎓 Early Projects
| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[O-Level Predictor](https://github.com/Lwg78/O-Level-Predictor)** | **First App.** My very first attempt to convert a Python calculation script into an interactive web app using Streamlit. | Python, Streamlit |

---

### 📫 Connect with me
* [LinkedIn](https://www.linkedin.com/in/wen-gio-lim-a8bb4327)
