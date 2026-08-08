---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /resume/
---

{% include base_path %}

<div style="margin-bottom: 25px; background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 5px solid #2b6cb0;">
  <h3 style="margin-top: 0;">Download Formal Research Resume</h3>
  <p>You can view or download the complete PDF version of my Curriculum Vitae:</p>
  <a href="/files/Zohaib_Malik_CV.pdf" target="_blank" class="btn btn--primary" style="font-weight: bold; padding: 8px 18px; text-decoration: none;">Download Zohaib_Malik_CV.pdf</a>
</div>

Education
======
* **Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI)** — *Topi, Pakistan*
  * **BS in Software Engineering** | **CGPA: 3.34 / 4.00** | *Sep 2023 – Jun 2027*
  * **Relevant Coursework**: Artificial Intelligence, Data Structures & Algorithms, Database Systems, OOP, Web Engineering, DevOps, Software Requirement Engineering, Computer Networks.

Research Experience
======
* **AI Research Assistant** | *AI Research Lab, GIKI* *(Supervised by Dr. Khurram Jadoon)* | *Jun 2026 – Jul 2026*
  * **Dataset Scraper & Curations**: Collected and curated large-scale Afghan Pashto text corpora (*Bakhtar*, *Khaama*, *RTA*, *Shamshad*, *Watan HD*, *Ariana*), building robust Python scrapers with bot evasion and deduplication, followed by cleaning and instruction-formatting for Supervised Fine-Tuning (SFT).
  * **Qehwa LLM Fine-Tuning**: Fine-tuned Qehwa LLM (built on `Qwen2.5-7B`) on ~74,966 Afghan-dialect instruction pairs using **QLoRA**, **LoRA**, **Unsloth**, and **PyTorch**, including dialect-mixing mitigation strategies for efficient domain adaptation on limited GPU resources.
  * **Pipeline Design**: Designed complete data preparation pipeline: preprocessing, tokenization, quality filtering, and SFT dataset generation for low-resource languages.
  * **IEEE Publication**: Co-authored and submitted an IEEE conference paper describing the Pashto LLM fine-tuning methodology and experimental results.

* **Personalized Math Tutoring via Fine-Tuned LLMs** | *Supervised Research Project under Dr. Khurram Jadoon*
  * Fine-tuned a `Meta-Llama-3-8B-Instruct` adapter with QLoRA for personalized math tutoring.
  * Diagnosed mathematical regression in v1 as catastrophic forgetting caused by targeting MLP layers on a small dataset.
  * Iterated on the fine-tuning recipe (v2): attention-only LoRA targets, reduced rank, and fewer epochs, to mitigate the forgetting effect.
  * Designing a formal evaluation benchmark (20 problems, automated SymPy grading) to produce reproducible, supervisor-reviewed performance metrics.

* **Transformer Language Model from Scratch** | *PyTorch*
  * Implemented a decoder-only Transformer language model from scratch in PyTorch, including multi-head self-attention, positional embeddings, feed-forward networks, residual connections, and layer normalization.
  * Implemented complete training pipeline including tokenization, batching, optimization, and autoregressive text generation to reproduce GPT-style architecture mechanics.

Publications & Preprints
======
* **Pashto LLM: Fine-Tuning Methodology and Experimental Results for Low-Resource Dialect Adaptation**  
  *Zohaib Malik*, Dr. Khurram Jadoon, et al.  
  *Submitted to IEEE Conference (2026).*

Honors & Awards
======
* **ICPC Asia Regional (2025)**: Ranked **13th in Pakistan** in the nation's premier competitive programming contest — solved complex algorithmic problems under strict time constraints.
* **GIKI Merit Scholarship (2023–Present)**: Fully funded scholarship (**PKR 4M+**) awarded on entrance merit; maintained through academic excellence.
* **Dean’s Honor List (Fall 2024)**: Recognized for top-tier academic performance during the semester.
* **1st Place, Intra-Faculty Chess Competition (2025)**: Champion out of 200+ participants.

Technical Skills
======
* **ML / Research**: PyTorch, QLoRA, LoRA, Unsloth, Scikit-Learn, Fine-tuning & SFT pipelines, Empirical evaluation
* **Programming Languages**: Python, C/C++, JavaScript, SQL, HTML, CSS
* **Frameworks & Tools**: FastAPI, React, Node.js, Django, REST APIs, Git, GitHub, Docker, Linux, PostgreSQL, MongoDB, VS Code, Jira
* **Concepts**: Data Structures & Algorithms, OOP, Agile/Scrum, SDLC, Software Requirement Engineering, CI/CD (basics)

Engineering Experience & Projects
======
* **The BookClub (GIKI Student Initiative)** | *Founder & Lead Software Engineer* | *Nov 2025 – Present*
  * Built and deployed a full-stack P2P textbook exchange platform serving **500+ GIKI students**, processing **200+ weekly listing transactions** with zero downtime.
  * Architected backend REST APIs using **FastAPI (Python)**, built responsive frontend with **React + Vite**, containerized with Docker, and optimized PostgreSQL schema for high student load.

* **Flood Detection System** *(Python, Scikit-Learn, Pandas)*
  * Trained Random Forest and Logistic Regression models on regional environmental data for flood-risk prediction; end-to-end ML pipeline including preprocessing, feature engineering, and cross-validation.

* **AI Fit & Try — Virtual Try-On System** *(Python, PyTorch, OpenCV)*
  * Deep learning pipeline for virtual garment try-on using body segmentation and mask-based post-processing; preprocessing tuned for noisy real-world images.

Leadership & Extracurriculars
======
* **Nexus Society & AIFS Society (GIKI)**: Organized national-level tech events and contributed to AI-focused workshops and hackathons.
* **Project Topi**: Volunteered in community welfare and flood relief campaigns in Upper Dir.
* **Cricket & Chess**: District-level cricket player; 1st place in GIKI chess competition (200+ participants).
