# Shivanshu Agrawal

**Medical Imaging · Computational Pathology · Document AI · Healthcare AI**

*I spend most of my time trying to get models to notice things doctors don't have time to look for.*

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=1400&color=E07BA8&width=620&height=36&vCenter=true&lines=Segmenting+stroke+lesions+on+CTP+perfusion+maps;Predicting+gene+expression+from+H%26E+slides;Parsing+messy+healthcare+documents;Mapping+dialect+symptoms+to+SNOMED+CT">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=1400&color=6B4C9A&width=620&height=36&vCenter=true&lines=Segmenting+stroke+lesions+on+CTP+perfusion+maps;Predicting+gene+expression+from+H%26E+slides;Parsing+messy+healthcare+documents;Mapping+dialect+symptoms+to+SNOMED+CT">
  <img alt="Segmenting stroke lesions on CTP perfusion maps. Predicting gene expression from H&E slides. Parsing messy healthcare documents. Mapping dialect symptoms to SNOMED CT." src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=1400&color=6B4C9A&width=620&height=36&vCenter=true&lines=Segmenting+stroke+lesions+on+CTP+perfusion+maps;Predicting+gene+expression+from+H%26E+slides;Parsing+messy+healthcare+documents;Mapping+dialect+symptoms+to+SNOMED+CT">
</picture>

Final-year B.Tech, Biochemical Engineering & Biotechnology at **IIT Delhi** (2023–2027) · CGPA 8.44 · Department Rank 3 (top 5% of 70+)
[Portfolio](https://shivanshu-agrawal.github.io) · [LinkedIn](https://www.linkedin.com/in/shivanshu-agrawal-0b47711b6/) · [Email](mailto:shivanshu.iitd2027@gmail.com)

<img src="assets/divider.svg" width="100%" height="2" alt="">

### Now

- 🔬 Distilling spatial-transcriptomics models small enough to actually deploy (IIT Delhi, Prof. Ishaan Gupta)
- 🧠 StrokeSeg-xAI manuscript under review; oral presentation at NBRCOM, AIIMS Jodhpur
- 🌏 Research Intern @ UNSW Sydney: AI + thermal imaging for pressure-injury staging
- 🏥 Building Lakshan: an AI clinical scribe for Indian healthcare

<img src="assets/divider.svg" width="100%" height="2" alt="">

### Research & Engineering Work

Take a slow, expert-dependent process in healthcare and see if a model can do the first pass faster. Three tracks below; the numbers are the ones I'd defend in an interview.

#### A · Medical Imaging & Computational Pathology

<table>
<tr>
<td valign="top" width="50%">

**StrokeSeg-xAI**

Explainable ischemic stroke lesion segmentation on ISLES 2018 CTP maps, built for small, low-contrast lesions.

**Oral @ NBRCOM, AIIMS Jodhpur**, manuscript under review

![ISLES 2018](https://img.shields.io/badge/ISLES_2018-6B4C9A?style=flat-square) ![Generalized Dice + Focal Tversky](https://img.shields.io/badge/Generalized_Dice_%2B_Focal_Tversky-6B4C9A?style=flat-square) ![Grad-CAM](https://img.shields.io/badge/Grad--CAM-6B4C9A?style=flat-square) ![MC-Dropout](https://img.shields.io/badge/MC--Dropout-6B4C9A?style=flat-square)

<sub>Prof. Anup Singh · Code: [repo-link]</sub>

</td>
<td valign="top" width="50%">

**Lightweight H&E → Spatial Gene Expression**

Predicting spatial gene expression from H&E slides with models small enough to deploy (HEST-1k, HER2).

**0.463 vs 0.435** cell-wise PCC for TinyGPQ (~315k params) with DeepSpot-M distilled into it. Reproduced TinyH2GNet at 0.462 vs the paper's 0.463: a 38× smaller model loses only ~0.04 PCC. Now replicating HINGE (CVPR 2026) with the CellFM foundation model.

![HEST-1k](https://img.shields.io/badge/HEST--1k-6B4C9A?style=flat-square) ![TinyH2GNet](https://img.shields.io/badge/TinyH2GNet-6B4C9A?style=flat-square) ![TinyGPQ](https://img.shields.io/badge/TinyGPQ-6B4C9A?style=flat-square) ![DeepSpot-M](https://img.shields.io/badge/DeepSpot--M-6B4C9A?style=flat-square) ![HINGE](https://img.shields.io/badge/HINGE-6B4C9A?style=flat-square) ![CellFM](https://img.shields.io/badge/CellFM-6B4C9A?style=flat-square)

<sub>IIT Delhi, Prof. Ishaan Gupta · Code: [repo-link]</sub>

</td>
</tr>
<tr>
<td valign="top" colspan="2">

**Thermal-imaging AI for Pressure Injury** (UNSW Sydney)

PRISMA-ScR review across 77 screened records, with Mask R-CNN / CapsNet / ConvNeXt benchmarked for staging.

**92–95% staging accuracy, AUC up to 0.98**, and 3 systematic gaps in the literature

![PRISMA-ScR](https://img.shields.io/badge/PRISMA--ScR-6B4C9A?style=flat-square) ![Mask R-CNN](https://img.shields.io/badge/Mask_R--CNN-6B4C9A?style=flat-square) ![CapsNet](https://img.shields.io/badge/CapsNet-6B4C9A?style=flat-square) ![ConvNeXt](https://img.shields.io/badge/ConvNeXt-6B4C9A?style=flat-square)

<sub>Code: [repo-link]</sub>

</td>
</tr>
</table>

#### B · Document AI & Healthcare Systems

<table>
<tr>
<td valign="top" width="50%">

**Rasyn AI: Healthcare Document Layout** (Aug–Sep 2026)

Synthetic-data pipeline with pseudo-labels from PP-DocLayout / DocLayout-YOLO and a self-hosted Qwen2.5-VL. **DocGrammar**: declarative per-document schemas that derive reading-order ground truth, plus an XY-Cut difficulty controller. A geometry-aware layout metric. SFT of DocLayout-v3.

![PP-DocLayout](https://img.shields.io/badge/PP--DocLayout-6B4C9A?style=flat-square) ![DocLayout-YOLO](https://img.shields.io/badge/DocLayout--YOLO-6B4C9A?style=flat-square) ![Qwen2.5-VL](https://img.shields.io/badge/Qwen2.5--VL-6B4C9A?style=flat-square) ![DocLayout-v3](https://img.shields.io/badge/DocLayout--v3-6B4C9A?style=flat-square)

<sub>Proprietary, so described here and not linked</sub>

</td>
<td valign="top" width="50%">

**Lakshan**

AI clinical scribe with a context layer that maps dialect-level symptoms to **SNOMED CT** (multilingual embeddings, graph-based concept expansion, schema-constrained generation). ABDM/ABHA integration, **FHIR R4** bundles, and a doctor dashboard where one-click corrections feed back into the dialect lexicon.

![SNOMED CT](https://img.shields.io/badge/SNOMED_CT-6B4C9A?style=flat-square) ![FHIR R4](https://img.shields.io/badge/FHIR_R4-6B4C9A?style=flat-square) ![ABDM/ABHA](https://img.shields.io/badge/ABDM%2FABHA-6B4C9A?style=flat-square)

<sub>Private · in development</sub>

</td>
</tr>
</table>

#### C · LLMs, Agents & Applied ML

| Project | What it does | The number |
|---|---|---|
| **LLM Eval Framework**<br><sub>[repo-link]</sub> | Async RAG eval over 1.2K FiQA samples, G-Eval / LLM-as-a-judge rubrics, PyTest regression gates in GitHub Actions CI.<br>![G-Eval](https://img.shields.io/badge/G--Eval-6B4C9A?style=flat-square) ![PyTest](https://img.shields.io/badge/PyTest-6B4C9A?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-6B4C9A?style=flat-square) | **4.68** groundedness, **8%** hallucination rate |
| **NutriSense AI**<br><sub>[repo-link]</sub> | Async Telegram agent with Gemini 2.0 vision and semantic search over 13+ GB of food embeddings.<br>![Gemini 2.0](https://img.shields.io/badge/Gemini_2.0-6B4C9A?style=flat-square) ![Telegram](https://img.shields.io/badge/Telegram-6B4C9A?style=flat-square) | macro lookups in **under 2 s** |
| **Legal Clause Extractor**<br><sub>[repo-link]</sub> | LegalBERT extractive QA on CUAD (510 contracts, 41 categories).<br>![LegalBERT](https://img.shields.io/badge/LegalBERT-6B4C9A?style=flat-square) ![CUAD](https://img.shields.io/badge/CUAD-6B4C9A?style=flat-square) | **46.2%** Precision@80% Recall |
| **Credit Card Fraud Detection**<br><sub>[repo-link]</sub> | XGBoost on 284k records with 0.17% fraud, against an autoencoder (0.526) and Isolation Forest (0.263).<br>![XGBoost](https://img.shields.io/badge/XGBoost-6B4C9A?style=flat-square) ![Autoencoder](https://img.shields.io/badge/Autoencoder-6B4C9A?style=flat-square) ![Isolation Forest](https://img.shields.io/badge/Isolation_Forest-6B4C9A?style=flat-square) | **0.876** AUPRC |
| **Agri-Price Forecasting**<br><sub>[repo-link]</sub> | LSTM for cotton, groundnut and soybean, plus Random Forest hoarding-anomaly detection.<br>![LSTM](https://img.shields.io/badge/LSTM-6B4C9A?style=flat-square) ![Random Forest](https://img.shields.io/badge/Random_Forest-6B4C9A?style=flat-square) | nRMSE **0.19** |

<details>
<summary>Also: Antifungal Virtual Screening</summary>

<br>

AutoDock Vina docking of 1,300 phytochemicals + 11,000 FDA drugs, validated on DUD-E/BindingDB (Prof. Manoj B. Menon).

![AutoDock Vina](https://img.shields.io/badge/AutoDock_Vina-6B4C9A?style=flat-square) ![DUD-E](https://img.shields.io/badge/DUD--E-6B4C9A?style=flat-square) ![BindingDB](https://img.shields.io/badge/BindingDB-6B4C9A?style=flat-square)

<sub>Code: [repo-link]</sub>

</details>

<img src="assets/divider.svg" width="100%" height="2" alt="">

### Tech Stack

| | |
|---|---|
| **Core** | ![Python](https://img.shields.io/badge/Python-6B4C9A?style=flat-square) ![C++](https://img.shields.io/badge/C%2B%2B-6B4C9A?style=flat-square) ![SQL](https://img.shields.io/badge/SQL-6B4C9A?style=flat-square) ![Bash](https://img.shields.io/badge/Bash-6B4C9A?style=flat-square) ![Git](https://img.shields.io/badge/Git-6B4C9A?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-6B4C9A?style=flat-square) ![AWS](https://img.shields.io/badge/AWS-6B4C9A?style=flat-square) ![Linux](https://img.shields.io/badge/Linux-6B4C9A?style=flat-square) |
| **Deep Learning / CV** | ![PyTorch](https://img.shields.io/badge/PyTorch-6B4C9A?style=flat-square) ![scikit-learn](https://img.shields.io/badge/scikit--learn-6B4C9A?style=flat-square) ![XGBoost](https://img.shields.io/badge/XGBoost-6B4C9A?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-6B4C9A?style=flat-square) ![Vision Transformers](https://img.shields.io/badge/Vision_Transformers-6B4C9A?style=flat-square) ![EfficientNet](https://img.shields.io/badge/EfficientNet-6B4C9A?style=flat-square) ![Grad-CAM](https://img.shields.io/badge/Grad--CAM-6B4C9A?style=flat-square) ![Knowledge Distillation](https://img.shields.io/badge/Knowledge_Distillation-6B4C9A?style=flat-square) ![Uncertainty Estimation](https://img.shields.io/badge/Uncertainty_Estimation-6B4C9A?style=flat-square) |
| **LLMs & Agents** | ![LangChain](https://img.shields.io/badge/LangChain-6B4C9A?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-6B4C9A?style=flat-square) ![VLMs (Qwen2.5-VL, Gemini)](https://img.shields.io/badge/VLMs_(Qwen2.5--VL,_Gemini)-6B4C9A?style=flat-square) ![MCP / A2A](https://img.shields.io/badge/MCP_%2F_A2A-6B4C9A?style=flat-square) ![RAG eval](https://img.shields.io/badge/RAG_eval-6B4C9A?style=flat-square) |
| **Bio & Health** | ![scanpy](https://img.shields.io/badge/scanpy-6B4C9A?style=flat-square) ![squidpy](https://img.shields.io/badge/squidpy-6B4C9A?style=flat-square) ![Biopython](https://img.shields.io/badge/Biopython-6B4C9A?style=flat-square) ![AutoDock Vina](https://img.shields.io/badge/AutoDock_Vina-6B4C9A?style=flat-square) ![GROMACS](https://img.shields.io/badge/GROMACS-6B4C9A?style=flat-square) ![SNOMED CT](https://img.shields.io/badge/SNOMED_CT-6B4C9A?style=flat-square) ![FHIR R4](https://img.shields.io/badge/FHIR_R4-6B4C9A?style=flat-square) |

<img src="assets/divider.svg" width="100%" height="2" alt="">

### Recognition

Dept. Rank 3 · ₹2L Discover & Learn research grant (IRD) · KVPY SA (AIR 208) · NSEC State Topper, Rajasthan · Winner, Goldman Sachs Future of Finance · Winner, PharmInnovate (IIT BHU) · TA for BBL773 · Convenor, CAIC

<img src="assets/divider.svg" width="100%" height="2" alt="">

### Off the GPU

Photography and documentary filmmaking (podiums at Antaragni and inter-hostel events), and quizzing. Mostly the same habit as the research: look at something long enough that it starts to make sense.

<!-- GitHub stats: uncomment once the account has activity.
<p><img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=shivanshu9799&show_icons=true&hide_border=true&bg_color=0d1117&title_color=E07BA8&icon_color=6B4C9A&text_color=9da7b3"></p>
-->

<!-- Contribution snake: needs the Platane/snk workflow publishing to an `output` branch. Uncomment after the workflow has run once.
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shivanshu9799/shivanshu9799/output/github-contribution-grid-snake-dark.svg">
  <img alt="Contribution graph snake" src="https://raw.githubusercontent.com/shivanshu9799/shivanshu9799/output/github-contribution-grid-snake.svg">
</picture>
-->

<img src="assets/divider.svg" width="100%" height="2" alt="">

I want to talk to people building ML for diagnostics or computational biology, especially teams past "look, a good AUC" and into "does a clinician actually trust this?"

[![Email](https://img.shields.io/badge/Email-E07BA8?style=flat-square)](mailto:shivanshu.iitd2027@gmail.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-E07BA8?style=flat-square)](https://www.linkedin.com/in/shivanshu-agrawal-0b47711b6/) [![Portfolio](https://img.shields.io/badge/Portfolio-E07BA8?style=flat-square)](https://shivanshu-agrawal.github.io)
