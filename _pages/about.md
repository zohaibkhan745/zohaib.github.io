---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Software Engineering student at [Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI)](https://www.giki.edu.pk/) with hands-on research experience in low-resource Natural Language Processing (NLP) and Large Language Model (LLM) fine-tuning. 

Supervised by **Dr. Khurram Jadoon** at the **GIKI AI Research Lab**, my recent work includes curating large-scale instruction datasets for low-resource languages, designing Parameter-Efficient Fine-Tuning (PEFT) pipelines, and co-authoring an **IEEE conference paper**.

I was ranked **13th nationally in Pakistan at ICPC Asia Regional 2025** and have strong quantitative and algorithmic fundamentals. I am proficient with **PyTorch**, **QLoRA/LoRA**, **Unsloth**, and empirical evaluation frameworks.

---

## 🔬 Research Experience

* **AI Research Assistant** | *AI Research Lab, GIKI* *(Supervised by Dr. Khurram Jadoon)* <span style="float:right;">*Jun 2026 – Jul 2026*</span>
  * **Low-Resource Pashto LLM Fine-Tuning**: Collected and curated large-scale Afghan Pashto text corpora (*Bakhtar*, *Khaama*, *RTA*, *Shamshad*, *Watan HD*, *Ariana*) using custom Python scrapers with bot evasion and deduplication, followed by instruction-formatting for Supervised Fine-Tuning (SFT).
  * **Qehwa LLM**: Fine-tuned Qehwa LLM (built on `Qwen2.5-7B`) on ~74,966 Afghan-dialect instruction pairs using **QLoRA**, **LoRA**, **Unsloth**, and **PyTorch**. Developed dialect-mixing mitigation strategies for efficient domain adaptation on limited GPU resources.
  * **IEEE Publication**: Co-authored and submitted an **IEEE conference paper** detailing the Pashto LLM fine-tuning methodology and experimental evaluation.

* **Personalized Math Tutoring via Fine-Tuned LLMs** *(Supervised Research Project under Dr. Khurram Jadoon)*
  * Fine-tuned a `Meta-Llama-3-8B-Instruct` adapter with QLoRA for personalized mathematics tutoring.
  * **Catastrophic Forgetting Mitigation**: Diagnosed mathematical regression in v1 as catastrophic forgetting caused by targeting MLP layers on a small dataset. Iterated fine-tuning recipe (v2) using attention-only LoRA targets, reduced rank, and fewer epochs to resolve forgetting.
  * **SymPy Evaluation Benchmark**: Designing a formal evaluation benchmark (20 problems with automated SymPy grading) for reproducible, supervisor-reviewed performance metrics.

* **Transformer Language Model from Scratch** | *PyTorch*
  * Implemented a decoder-only Transformer language model from scratch in PyTorch, including multi-head self-attention, positional embeddings, feed-forward networks, residual connections, and layer normalization.
  * Built complete training pipeline covering tokenization, batching, optimization, and autoregressive text generation to reproduce GPT-style architecture mechanics.

---

## 📝 Publications & Preprints

* **Pashto LLM: Fine-Tuning Methodology and Experimental Results for Low-Resource Dialect Adaptation**  
  *Zohaib Malik*, Dr. Khurram Jadoon, et al.  
  *Submitted to IEEE Conference (2026).*

---

## 🏆 Honors & Awards

* **ICPC Asia Regional (2025)**: Ranked **13th in Pakistan** in the nation's premier competitive programming contest — solved complex algorithmic problems under strict time constraints.
* **GIKI Merit Scholarship (2023–Present)**: Fully funded scholarship (**PKR 4M+**) awarded on entrance merit and maintained through academic excellence.
* **Dean’s Honor List (Fall 2024)**: Recognized for top-tier academic performance.
* **1st Place, Intra-Faculty Chess Competition (2025)**: Champion out of 200+ participants.

---

## 🛠️ Technical Skills

* **ML & Research**: PyTorch, QLoRA, LoRA, Unsloth, Scikit-Learn, Fine-Tuning & SFT Pipelines, Empirical Evaluation, Transformers, HuggingFace
* **Programming Languages**: Python, C/C++, JavaScript, SQL, HTML, CSS
* **Frameworks & Databases**: FastAPI, React, Node.js, Django, REST APIs, PostgreSQL, MongoDB, Docker
* **Core Concepts**: Data Structures & Algorithms, Machine Learning, Deep Learning, OOP, Software Requirement Engineering, CI/CD

---

## 💻 Engineering Experience & Selected Projects

* **The BookClub (GIKI Student Initiative)** | *Founder & Lead Software Engineer* <span style="float:right;">*Nov 2025 – Present*</span>
  * Architected and deployed a full-stack P2P textbook exchange platform serving **500+ GIKI students**, processing 200+ weekly transactions with zero downtime.
  * Built backend REST APIs with **FastAPI (Python)**, responsive frontend with **React + Vite**, containerized with Docker, and optimized PostgreSQL schema.

* **Flood Detection & Prediction System** *(Python, Scikit-Learn, Pandas)*
  * Trained Random Forest and Logistic Regression models on regional environmental data for flood-risk prediction; end-to-end ML pipeline with cross-validation.

* **AI Fit & Try — Virtual Try-On System** *(Python, PyTorch, OpenCV)*
  * Deep learning pipeline for virtual garment try-on using body segmentation and mask-based post-processing.

---

## 🎓 Education

* **Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI)** — *Topi, Pakistan*
  * **BS in Software Engineering** | **CGPA: 3.34 / 4.00** | *Sep 2023 – Jun 2027*
  * *Relevant Coursework*: Artificial Intelligence, Data Structures & Algorithms, Database Systems, Web Engineering, DevOps, Software Requirement Engineering, Computer Networks.
