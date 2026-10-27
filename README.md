# Shivanshu Agrawal

<p align="left">
  <img src="https://img.shields.io/badge/Medical%20Imaging-CTP%20Perfusion%20Maps-6B4C9A?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Computational%20Pathology-H%26E%20Slides-E07BA8?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Document%20AI-Healthcare%20Docs-6B4C9A?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Healthcare%20AI-Clinical%20ML-E07BA8?style=flat-square&logoColor=white" />
</p>

I spend most of my time trying to get models to notice things doctors don't have time to look for.

<p align="left">
  <img
    src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&duration=3800&pause=1000&color=E07BA8&background=transparent&lines=Segmenting+stroke+lesions+on+CTP+perfusion+maps|Predicting+gene+expression+from+H%26E+slides|Parsing+messy+healthcare+documents|Mapping+dialect+symptoms+to+SNOMED+CT"
    alt="Typing SVG"
  />
</p>

## Now

- 🔬 Distilling spatial-transcriptomics models small enough to actually deploy (IIT Delhi, Prof. Ishaan Gupta)
- 🧠 StrokeSeg-xAI manuscript under review; oral presentation at NBRCOM, AIIMS Jodhpur
- 🌏 Research Intern @ UNSW Sydney: AI + thermal imaging for pressure-injury staging
- 🏥 Building Lakshan: an AI clinical scribe for Indian healthcare

<svg width="100%" height="2" viewBox="0 0 1200 2" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="1" x2="1200" y2="1" stroke="#6B4C9A" stroke-width="2" />
</svg>

## Research & Engineering Work

### Medical Imaging & Computational Pathology

| Project | Problem | Signal | Stack | Repo |
| --- | --- | --- | --- | --- |
| **StrokeSeg-xAI** | Explainable ischemic stroke lesion segmentation on ISLES 2018 CTP maps | Oral @ NBRCOM, AIIMS Jodhpur; manuscript under review | PyTorch, CUDA, Grad-CAM, MC-Dropout, Focal Tversky, Generalized Dice | [repo-link] |
| **Lightweight H&E → Spatial Gene Expression** | Reproducing and compressing gene-expression prediction from H&E slides | Cell-wise PCC 0.462 vs 0.463 paper; TinyGPQ (~315k params) reaches 0.463 vs 0.435 baseline | PyTorch, Vision Transformers, knowledge distillation, DeepSpot-M, CellFM | [repo-link] |
| **Thermal-imaging AI for Pressure Injury (UNSW Sydney)** | Systematic review and benchmark design for pressure-injury staging from thermal imaging | PRISMA-ScR review across 77 screened records; 92–95% staging accuracy, AUC up to 0.98 | Mask R-CNN, CapsNet, ConvNeXt, Python, review synthesis | [repo-link] |

### Document AI & Healthcare Systems

| Project | Problem | Signal | Stack | Repo |
| --- | --- | --- | --- | --- |
| **Rasyn AI: Healthcare Document Layout** | Synthetic-data pipeline for healthcare document understanding | Declarative DocGrammar + XY-Cut difficulty controller; geometry-aware layout metric; DocLayout-v3 SFT | Qwen2.5-VL, PP-DocLayout, DocLayout-YOLO, synthetic data, Python | Proprietary |
| **Lakshan** | AI clinical scribe for Indian healthcare | In development; maps dialect-level symptoms to SNOMED CT with schema-constrained generation | Python, embeddings, graph expansion, FHIR R4, ABDM/ABHA integration | Private: in development |

### LLMs, Agents & Applied ML

| Project | Problem | Signal | Stack | Repo |
| --- | --- | --- | --- | --- |
| **LLM Eval Framework** | RAG evaluation over noisy healthcare and finance question sets | 1.2K FiQA samples; groundedness 4.68; 8% hallucination rate | async RAG, G-Eval, PyTest, GitHub Actions | [repo-link] |
| **NutriSense AI** | Food understanding and semantic retrieval over large image-text corpora | Macro lookups in under 2 s | Gemini 2.0 vision, semantic search, Telegram agent | [repo-link] |
| **Legal Clause Extractor** | Extractive QA over contracts | 46.2% Precision@80% Recall on CUAD (510 contracts, 41 categories) | LegalBERT, extraction QA | [repo-link] |
| **Credit Card Fraud Detection** | Detecting rare fraud under severe class imbalance | XGBoost at 0.876 AUPRC on 284k records with 0.17% fraud | XGBoost, autoencoder, Isolation Forest | [repo-link] |
| **Agri-Price Forecasting** | Forecasting commodity prices and hoarding anomaly detection | LSTM nRMSE 0.19; Random Forest anomaly detection | LSTM, Random Forest, time-series modeling | [repo-link] |
| **Antifungal Virtual Screening** *(optional)* | Screening phytochemicals and FDA drugs against fungal targets | Docking of 1,300 phytochemicals + 11,000 FDA drugs; validated on DUD-E/BindingDB | AutoDock Vina, docking pipelines | [repo-link] |

<svg width="100%" height="2" viewBox="0 0 1200 2" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="1" x2="1200" y2="1" stroke="#E07BA8" stroke-width="2" />
</svg>

## Tech Stack

### Core
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=white" />
</p>

### Deep Learning / CV
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-4B8BBE?style=flat-square&logo=xgboost&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/ViT-Vision%20Transformers-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/EfficientNet-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/Grad--CAM-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/Uncertainty%20Estimation-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/Knowledge%20Distillation-6B4C9A?style=flat-square" />
</p>

### LLMs & Agents
<p align="left">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Qwen2.5--VL-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/Gemini-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/MCP-A2A-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/RAG%20Eval-6B4C9A?style=flat-square" />
</p>

### Bio & Health
<p align="left">
  <img src="https://img.shields.io/badge/scanpy-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/squidpy-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/Biopython-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/AutoDock%20Vina-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/GROMACS-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/SNOMED%20CT-6B4C9A?style=flat-square" />
  <img src="https://img.shields.io/badge/FHIR%20R4-6B4C9A?style=flat-square" />
</p>

## Recognition

| Signal |
| --- |
| Dept. Rank 3 · ₹2L Discover & Learn research grant (IRD) · KVPY SA (AIR 208) · NSEC State Topper, Rajasthan · Winner, Goldman Sachs Future of Finance · Winner, PharmInnovate (IIT BHU) · TA for BBL773 · Convenor, CAIC |

## Off the GPU

Photography and documentary filmmaking (Antaragni & inter-hostel podiums) and quizzing.

<svg width="100%" height="2" viewBox="0 0 1200 2" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="1" x2="1200" y2="1" stroke="#6B4C9A" stroke-width="2" />
</svg>

## About

Final-year B.Tech in Biochemical Engineering & Biotechnology, IIT Delhi (2023–2027). CGPA 8.44, Department Rank 3 (top 5% of 70+).

Current roles: Research Intern @ UNSW Sydney · AI Research Intern @ Rasyn AI (Aug–Sep 2026) · Founder @ Lakshan (early-stage healthcare AI startup)

Focus: Medical Imaging, Computational Pathology, Document AI, Healthcare AI

Portfolio: [shivanshu-agrawal.github.io](https://shivanshu-agrawal.github.io)  
Email: [shivanshu.iitd2027@gmail.com](mailto:shivanshu.iitd2027@gmail.com)  
LinkedIn: [link](#)

Take a slow, expert-dependent process in healthcare and see if a model can do the first pass faster.

I want to talk to people building ML for diagnostics or computational biology, especially teams past "look, a good AUC" and into "does a clinician actually trust this?"

<p align="left">
  <a href="mailto:shivanshu.iitd2027@gmail.com"><img src="https://img.shields.io/badge/Email-shivanshu.iitd2027@gmail.com-6B4C9A?style=flat-square&logo=mail.ru&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-link-E07BA8?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://shivanshu-agrawal.github.io"><img src="https://img.shields.io/badge/Portfolio-shivanshu--agrawal.github.io-6B4C9A?style=flat-square" /></a>
</p>

<!--
GitHub stats and the contribution snake are intentionally off by default.
Uncomment once the account has real activity:

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Shivanshu9799&show_icons=true&theme=dracula)
![GitHub streak](https://github-readme-streak-stats.herokuapp.com/?user=Shivanshu9799&theme=dracula)
![Profile views](https://komarev-counter.vercel.app/api/count?style=flat-square&color=6B4C9A&username=Shivanshu9799)
-->
