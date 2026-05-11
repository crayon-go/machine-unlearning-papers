# Machine Unlearning — Papers Catalog

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Papers](https://img.shields.io/badge/papers-2114-blue) ![Updated](https://img.shields.io/badge/updated-2026--05--10-brightgreen) [![Stars](https://img.shields.io/github/stars/crayon-go/machine-unlearning-papers?style=social)](https://github.com/crayon-go/machine-unlearning-papers/stargazers) ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=crayon-go.machine-unlearning-papers) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](https://github.com/crayon-go/machine-unlearning-papers/issues)

A continuously-updated reference catalog of **machine unlearning** research — the study of selectively removing the influence of specific training data, samples, classes, concepts, or knowledge from a trained model after the fact. The catalog spans algorithms (exact and approximate), evaluation benchmarks, attacks against unlearning, and applications across LLMs, diffusion models, graphs, federated learning, and recommender systems.

Unlike hand-curated lists, this catalog is **automatically assembled and refreshed** from primary academic indices (Semantic Scholar, OpenAlex, OpenReview, DBLP, Crossref, arXiv, Hugging Face Papers, GitHub Search). Each entry shows live citation counts and, where available, links to the official code repository — fields that are usually missing from existing machine-unlearning lists.

## Quick stats

- **2,114 papers** classified as machine-unlearning research. Spans **1990–2026**.
- **1,110 (52.5%)** have an official code repository link (GitHub / Hugging Face / GitLab).
- **1,399 (66.2%)** have a resolvable arXiv ID.
- Domain distribution: **LLM** 565 · **Diffusion** 308 · **Vision** 280 · **Graph** 71 · **Federated** 275 · **Recsys** 62 · **Other** 553
- Citation counts last refreshed: **2026-05-10** (KST).

## What's inside

Each year section below is a sortable table with six columns:

| Column | Notes |
|---|---|
| **Authors** | Up to three author names; longer lists abbreviated as `et al.` |
| **Title** | Linked to the canonical source (DOI > arXiv > OpenAlex > S2) |
| **Venue** | Normalized short label (e.g. `arXiv`, `NeurIPS`, `IEEE T-IFS`, `WWW`) |
| **Category** | Primary research domain — one of `LLM` / `Diffusion` / `Vision` / `Graph` / `Federated` / `Recsys` / `Other` |
| **Code** | First available repository link with priority `GitHub > HF > GitLab`; `—` if unknown |
| **Citations** | Live counts from Semantic Scholar; rows are sorted citations-desc within each year |

## Frameworks & tooling

- **[OpenUnlearning](https://github.com/locuslab/open-unlearning)** — Unified evaluation framework for LLM unlearning (TOFU, MUSE, WMDP).
- **[Machine Unlearning Comparator](https://github.com/gnueaj/Machine-Unlearning-Comparator)** — Visual analytics tool for comparing unlearning methods side-by-side.
- **[ERASURE](https://github.com/aiim-research/ERASURE)** — Modular framework for reproducible machine-unlearning experiments (CIKM '25).

## Recommended surveys

- **[A Survey of Machine Unlearning](https://arxiv.org/abs/2209.02299)** — Nguyen et al., ACM TIST 2025 — comprehensive taxonomy & datasets.
- **[Rethinking Machine Unlearning for Large Language Models](https://arxiv.org/abs/2402.08787)** — Liu et al., 2024 — LLM-specific challenges, evaluation, and threat models.
- **[Machine Unlearning: A Survey](https://arxiv.org/abs/2306.03558)** — Xu et al., ACM Computing Surveys 2023 — exact vs approximate unlearning.
- **[A Comprehensive Survey of Machine Unlearning Techniques for LLMs](https://arxiv.org/abs/2503.01854)** — Geng et al., 2025 — focused review of LLM unlearning methods.

## Key benchmarks

- **[TOFU](https://arxiv.org/abs/2401.06121)** — Fictitious-author QA benchmark for LLM unlearning. (Maini et al., COLM '24)
- **[MUSE](https://arxiv.org/abs/2407.06460)** — Six-way evaluation across forget quality, utility, privacy, scalability. (Shi et al., ICLR '25)
- **[WMDP](https://arxiv.org/abs/2403.03218)** — Hazardous-knowledge unlearning benchmark in bio/chem/cyber. (Li et al., ICML '24)
- **[UnlearnCanvas](https://arxiv.org/abs/2402.11846)** — Stylized image dataset for diffusion-model concept unlearning.

## How this catalog is built

1. **Discovery** — seed snowball over a hand-picked list of foundational papers, plus keyword search across academic APIs and recent-author tracking.
2. **Relevance filtering** — title-level whitelist/blacklist heuristics, then a Claude-based judge (with prompt caching) for ambiguous cases.
3. **Deduplication** — DOI / arXiv / fuzzy title match collapses preprint and venue versions of the same work.
4. **Metadata enrichment** — Semantic Scholar batch refresh, plus a fall-through to OpenReview, DBLP, Crossref, and arXiv for missing year/venue.
5. **Code-link discovery** — Hugging Face Papers (API + HTML), GitHub Search by arXiv ID and title, abstract-URL regex, and arXiv PDF body parsing.

Every paper carries a `source` provenance trail so any cell in the table can be traced back to the API that produced it.

## Contents

- [2026](#2026)
- [2025](#2025)
- [2024](#2024)
- [2023](#2023)
- [2022](#2022)
- [2021](#2021)
- [2020](#2020)
- [2019](#2019)
- [2018](#2018)
- [2017](#2017)
- [2016](#2016)
- [2015](#2015)
- [2014](#2014)
- [2012](#2012)
- [2011](#2011)
- [2010](#2010)
- [2009](#2009)
- [2008](#2008)
- [2007](#2007)
- [2004](#2004)
- [2003](#2003)
- [2000](#2000)
- [1997](#1997)
- [1990](#1990)
- [Undated](#undated)

## 2026

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Pengyang Shao et al. | [BalDRO: A Distributionally Robust Optimization based Framework for Large Language Model Unlearning](https://doi.org/10.1145/3774904.3792975) | WWW | LLM | [GitHub](https://github.com/nxZhai/BalDRO) | 8 |
| Naixin Zhai et al. | [Maximizing Local Entropy Where It Matters: Prefix-Aware Localized LLM Unlearning](https://doi.org/10.48550/arXiv.2601.03190) | arXiv | LLM | [GitHub](https://github.com/nxZhai/PALU) | 8 |
| Hyejun Jeong, Shiqing Ma, Amir Houmansadr | [A Survey on Federated Unlearning: Challenges and Opportunities](https://doi.org/10.1109/tbdata.2026.3668538) | IEEE TBD | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 6 |
| Ruinan Jin et al. | [Forgettable Federated Linear Learning With Certified Data Unlearning](https://doi.org/10.1109/tnnls.2026.3683398) | IEEE TNNLS | Federated | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 6 |
| Zhuo Huang et al. | [Is Gradient Ascent Really Necessary? Memorize to Forget for Machine Unlearning](https://doi.org/10.48550/arXiv.2602.06441) | arXiv | Other | [GitHub](https://github.com/crayon-go/machine-unlearning-papers) | 4 |
| Yiling Wang et al. | [SafeMo: Linguistically Grounded Unlearning for Trustworthy Text-to-Motion Generation](https://doi.org/10.48550/arXiv.2601.00590) | arXiv | Diffusion | [GitHub](https://github.com/AIGeeksGroup/SafeMo) | 4 |
| Jiahao Zhang et al. | [Unlearning Inversion Attacks for Graph Neural Networks](https://doi.org/10.1145/3773966.3777929) | WSDM | Graph | [GitHub](https://github.com/QwQ2000/WSDM26-Graph-Unlearning-Inversion) | 3 |
| Fengpeng Li et al. | [AEGIS: Adversarial Target-Guided Retention-Data-Free Robust Concept Erasure from Diffusion Models](https://doi.org/10.48550/arXiv.2602.06771) | arXiv | Diffusion | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 3 |
| McKinney, Lev et al. | [Gauss-Newton Unlearning for the LLM Era](https://doi.org/10.48550/arXiv.2602.10568) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 3 |
| Renyang Liu et al. | [SafeRedir: Prompt Embedding Redirection for Robust Unlearning in Image Generation Models](https://doi.org/10.48550/arXiv.2601.08623) | arXiv | Diffusion | [GitHub](https://github.com/ryliu68/SafeRedir) | 3 |
| Xunlei Chen et al. | [ALTER: Asymmetric LoRA for Token-Entropy-Guided Unlearning of LLMs](https://doi.org/10.1609/aaai.v40i42.40845) | AAAI | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Anmol Goel, Alan Ritter, Iryna Gurevych | [Auditing Language Model Unlearning via Information Decomposition](https://doi.org/10.48550/arXiv.2601.15111) | ACL | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Alireza Dehghanpour Farashah et al. | [Multilingual Amnesia: On the Transferability of Unlearning in Multilingual LLMs](https://doi.org/10.48550/arXiv.2601.05641) | ACL | LLM | [GitHub](https://github.com/alirezafarashah/multilingual_unlearning) | 2 |
| Zhenhua Xu et al. | [ForgetMark: Stealthy Fingerprint Embedding via Targeted Unlearning in Language Models](https://doi.org/10.48550/arXiv.2601.08189) | ICASSP | LLM | [GitHub](https://github.com/Xuzhenhua55/ForgetMark) | 2 |
| Yang Zhao, D. Niyato | [Exploring Federated Unlearning: Analysis, Comparison, and Insights](https://www.semanticscholar.org/paper/7f7d11a14ed0c66056d3655ee194f70cbe620c75) | IEEE Network | Federated | — | 2 |
| Yilei Wang et al. | [Cer-FeaUn: Certified Feature Unlearning in Vertical Federated Learning](https://doi.org/10.1109/TMC.2025.3594851) | IEEE TMC | Federated | [GitHub](https://github.com/lzbuuu/Cer-FeaUn) | 2 |
| Weiqi Wang et al. | [BlindU: Blind Machine Unlearning Without Revealing Erasing Data](https://doi.org/10.1109/TPAMI.2026.3654093) | IEEE TPAMI | Federated | [GitHub](https://github.com/wwq5-code/BlindU) | 2 |
| Junfeng Liao et al. | [Explainable LLM Unlearning Through Reasoning](https://arxiv.org/abs/2603.09980) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Iyad Ait Hou et al. | [Parameter-Efficient Token Embedding Editing for Clinical Class-Level Unlearning](https://arxiv.org/abs/2603.19302) | arXiv | LLM | — | 2 |
| Jiali Cheng et al. | [Toward Understanding Unlearning Difficulty: A Mechanistic Perspective and Circuit-Guided Difficulty Metric](https://doi.org/10.48550/arXiv.2601.09624) | arXiv | LLM | — | 2 |
| Jingpu Cheng et al. | [Machine Unlearning under Retain-Forget Entanglement](https://arxiv.org/abs/2603.26569) | arXiv | Vision | [GitHub](https://github.com/Jingpu-Cheng/unlearning-entanglement) | 2 |
| Saad Hossain et al. | [TamperBench: Systematically Stress-Testing LLM Safety Under Fine-Tuning and Tampering](https://doi.org/10.48550/arXiv.2602.06911) | arXiv | LLM | [HF](https://huggingface.co/datasets/b0sungk1m/tamperbench-quantization-qwen3-4b) | 2 |
| Zichong Wang, Tongliang Liu, Wenbin Zhang | [GUIC: Certified Graph Unlearning with Individual Fairness Guarantees](https://doi.org/10.1609/aaai.v40i42.40896) | AAAI | Graph | — | 1 |
| Junehyoung Kwon et al. | [Easy to Learn, Yet Hard to Forget: Towards Robust Unlearning Under Bias](https://doi.org/10.1609/aaai.v40i7.37499) | AAAI | Vision | — | 1 |
| Ayush K. Varshney, Vicenç Torra | [Realistic image-to-image machine unlearning via decoupling and knowledge retention](https://doi.org/10.1016/j.bdr.2026.100592) | Big Data Research | Diffusion | — | 1 |
| Myungjin Lee, Eunji Shin, Jiyoung Lee | [Erasing Your Voice Before It's Heard: Training-free Speaker Unlearning for Zero-shot Text-to-Speech](https://doi.org/10.48550/arXiv.2601.20481) | ICASSP | LLM | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 1 |
| Lulu Xue et al. | [UnlearnShield: Shielding Forgotten Privacy against Unlearning Inversion](https://doi.org/10.48550/arXiv.2601.20325) | ICASSP | Other | — | 1 |
| Xingli Fang, Jung-Eun Kim | [Learnability and Privacy Vulnerability are Entangled in a Few Critical Weights](https://arxiv.org/abs/2603.13186) | ICLR Poster | Vision | — | 1 |
| Zhiqiang Xie et al. | [Closed-Box Unlearning for Large Language Model-Enabled Internet of Everything](https://doi.org/10.1109/mnet.2026.3660124) | IEEE Network | LLM | — | 1 |
| Xuhan Zuo et al. | [Federated TrustChain: Blockchain-Enhanced LLM Training and Unlearning](https://doi.org/10.1109/tdsc.2026.3665277) | IEEE TDSC | Federated | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Yijing Lin et al. | [Quantifying and Certifying Unlearning for Large Language Models without Full Retraining](https://doi.org/10.1109/tmc.2026.3672778) | IEEE TMC | LLM | — | 1 |
| Zhenguo Ma et al. | [AdaFUN: Enhancing Federated Unlearning with Adaptive Local Step in Edge Computing](https://doi.org/10.1109/tsc.2026.3685363) | IEEE TSC | Federated | — | 1 |
| Weidong Zheng et al. | [Accurate and fast machine unlearning with hessian-guided overfitting approximation](https://doi.org/10.1016/j.neucom.2026.133369) | Neurocomputing | Other | — | 1 |
| Mohammad Partohaghighi et al. | [Statistical Roughness-Informed Machine Unlearning](https://doi.org/10.48550/arXiv.2602.09304) | arXiv | Other | — | 1 |
| Yuze Cai et al. | [Prototype-Guided Concept Erasure in Diffusion Models](https://arxiv.org/abs/2603.08271) | arXiv | Diffusion | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 1 |
| Chi Zhang et al. | [Closed-Form Concept Erasure via Double Projections](https://arxiv.org/abs/2604.10032) | arXiv | Diffusion | — | 1 |
| Kaiyuan Deng et al. | [Forget-It-All: Multi-Concept Machine Unlearning via Concept-Aware Neuron Masking](https://doi.org/10.48550/arXiv.2601.06163) | arXiv | Diffusion | [GitHub](https://github.com/kaiyuan02415/Forget-It-All) | 1 |
| Raj Sanjay Shah et al. | [The Unlearning Mirage: A Dynamic Framework for Evaluating LLM Unlearning](https://arxiv.org/abs/2603.11266) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Zeguan Xiao et al. | [Modeling LLM Unlearning as an Asymmetric Two-Task Learning Problem](https://arxiv.org/abs/2604.14808) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Xiaoyu Xu et al. | [From Domains to Instances: Dual-Granularity Data Synthesis for LLM Unlearning](https://doi.org/10.48550/arXiv.2601.04278) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Yangyang Guo et al. | [LLMs Can Unlearn Refusal with Only 1,000 Benign Samples](https://doi.org/10.48550/arXiv.2601.19231) | arXiv | LLM | [GitHub](https://github.com/guoyang9/refusal-unlearning) | 1 |
| Seyun Bae, Seokhan Lee, Eunho Yang | [CURaTE: Continual Unlearning in Real Time with Ensured Preservation of LLM Knowledge](https://arxiv.org/abs/2604.14644) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Wenxuan Li et al. | [From Anchors to Supervision: Memory-Graph Guided Corpus-Free Unlearning for Large Language Models](https://arxiv.org/abs/2604.13777) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Taoran Li, Varun Chandrasekaran, Zhiyuan Yu | [Layer-Targeted Multilingual Knowledge Erasure in Large Language Models](https://doi.org/10.48550/arXiv.2602.22562) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Pengfei Ding, Yan Wang, Guanfeng Liu | [Re-understanding Graph Unlearning through Memorization](https://doi.org/10.1145/3774904.3792383) | arXiv | Graph | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 1 |
| Renqiang Luo et al. | [FairGU: Fairness-aware Graph Unlearning in Social Networks](https://doi.org/10.1145/3774904.3793004) | arXiv | Graph | [GitHub](https://github.com/LuoRenqiang/FairGU) | 1 |
| Ravi Ranjan et al. | [RAZOR: Ratio-Aware Layer Editing for Targeted Unlearning in Vision Transformers and Diffusion Models](https://arxiv.org/abs/2603.14819) | arXiv | Diffusion | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 1 |
| Ravi Ranjan, Agoritsa Polyzou | [VLA-Forget: Vision-Language-Action Unlearning for Embodied Foundation Models](https://arxiv.org/abs/2604.03956) | arXiv | LLM | [GitHub](https://github.com/AriESQ/stars) | 1 |
| S. Laguna et al. | [Rethinking Machine Unlearning: Models Designed to Forget via Key Deletion](https://arxiv.org/abs/2603.15033) | arXiv | Other | [HF](https://huggingface.co/google/vit-base-patch16-224) | 1 |
| Saleh Zare Zade et al. | [Attention Smoothing Is All You Need For Unlearning](https://doi.org/10.48550/arXiv.2603.01285) | arXiv | LLM | [GitHub](https://github.com/Salehzz/ASU-unlearning) | 1 |
| Chenhao Zhang et al. | [Unlearning Evaluation through Subset Statistical Independence](https://doi.org/10.48550/arXiv.2603.00587) | arXiv | Other | [GitHub](https://github.com/ChildEden/SDE) | 1 |
| Xuanqi Zhang, Haoyang Shang, Xiaoxiao Li | [GSS: Gated Subspace Steering for Selective Memorization Mitigation in LLMs](https://doi.org/10.48550/arXiv.2602.08901) | arXiv | LLM | — | 1 |
| Weiqi Wang et al. | [EVE: Efficient Verification of Data Erasure through Customized Perturbation in Approximate Unlearning](https://doi.org/10.48550/arXiv.2602.03567) | arXiv | Other | — | 1 |
| Neil Rathi, Alec Radford | [Shaping capabilities with token-level data filtering](https://doi.org/10.48550/arXiv.2601.21571) | arXiv | LLM | [GitHub](https://github.com/neilrathi/token-filtering) | 1 |
| Hsiang Hsu et al. | [The Unseen Threat: Residual Knowledge in Machine Unlearning under Perturbed Samples](https://doi.org/10.48550/arXiv.2601.22359) | arXiv | Other | [GitHub](https://github.com/AdityaGolatkar/SelectiveForgetting) | 1 |
| Syed Naveed Mahmood et al. | [Representation-Aware Unlearning via Activation Signatures: From Suppression to Knowledge-Signature Erasure](https://doi.org/10.48550/arXiv.2601.10566) | arXiv | LLM | [GitHub](https://github.com/kitkiti/kitkiti) | 1 |
| Jonas Mirlach, S. Laguna, Julia E. Vogt | [Reference-Guided Machine Unlearning](https://arxiv.org/abs/2603.11210) | arXiv | Vision | [GitHub](https://github.com/jmirlach/ReGUn) | 1 |
| Guangwei Zhang et al. | [Copyright Detective: A Forensic System to Evidence LLMs Flickering Copyright Leakage Risks](https://doi.org/10.48550/arXiv.2602.05252) | arXiv | LLM | [GitHub](https://github.com/changhu73/Copyright-Detective) | 1 |
| Yi Sun et al. | [ActErase: A Training-Free Paradigm for Precise Concept Erasure via Activation Patching](https://doi.org/10.48550/arXiv.2601.00267) | arXiv | Diffusion | — | 1 |
| Ziyu Xie et al. | [A Survey on Federated Unlearning: Lifecycle, Taxonomy, and Insights](https://doi.org/10.36227/techrxiv.177004227.77961306/v1) |  | Federated | — | 0 |
| Ujjwal Pudasaini, Jun Huang, Zihao Ding | [Securing Smart Agriculture with Communication-Efficient Federated Unlearning](https://doi.org/10.36227/techrxiv.177223092.23251086/v1) |  | Federated | — | 0 |
| Anamika Paul Rupa, Anietie U Andy | [Probe-Geometry Alignment: Erasing the Cross-Sequence Memorization Signature Below Chance](https://arxiv.org/abs/2605.01699) |  | LLM | [GitHub](https://github.com/Rupawheatly/MLDU2) | 0 |
| J. Li, Yongqiang Chen, Ningning Ding | [CiPO: Counterfactual Unlearning for Large Reasoning Models through Iterative Preference Optimization](https://arxiv.org/abs/2604.15847) |  | LLM | — | 0 |
| Jiahang Tu et al. | [Mass Concept Erasure in Diffusion Models with Concept Hierarchy](https://doi.org/10.1609/aaai.v40i12.37920) | AAAI | Diffusion | — | 0 |
| Miaozeng Du et al. | [Forget What Has Seen: Selective Concept Unlearning in Segmentation Foundation Models](https://doi.org/10.1609/aaai.v40i25.39233) | AAAI | Vision | — | 0 |
| Haokun Chen et al. | [AUVIC: Adversarial Unlearning of Visual Concepts for Multi-modal Large Language Models](https://doi.org/10.1609/aaai.v40i36.40272) | AAAI | LLM | — | 0 |
| Weipeng Jiang et al. | [From Chaos to Clarity: A Knowledge Graph-Driven Audit Dataset Generation Framework for LLM Unlearning](https://doi.org/10.1609/aaai.v40i37.40397) | AAAI | LLM | — | 0 |
| Jingjing Zhou et al. | [STaR: Sensitive Trajectory Regulation for Unlearning in Large Reasoning Models](https://doi.org/10.1609/aaai.v40i41.40818) | AAAI | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yuming Ai et al. | [PAGE: A Unified Approach for Federated Graph Unlearning](https://doi.org/10.1609/aaai.v40i24.39038) | AAAI | Federated | [GitHub](https://github.com/striker2333/PAGE) | 0 |
| He Zhang et al. | [Imprint of the Forgotten: Stealthy Membership Inference in Unlearned Graph Neural Networks](https://doi.org/10.1609/aaai.v40i33.40047) | AAAI | Graph | — | 0 |
| Siyuan Wen et al. | [FedShard: Federated Unlearning with Efficiency Fairness and Performance Fairness](https://doi.org/10.1609/aaai.v40i32.39895) | AAAI | Federated | — | 0 |
| Xinyi Sheng et al. | [Retaliatory Attacks Against Federated Unlearning via Data Leakage](https://doi.org/10.1609/aaai.v40i30.39725) | AAAI | Federated | [GitHub](https://github.com/stcebra/Retaliatory-Attacks-Against-Federated-Unlearning) | 0 |
| Aobo Chen et al. | [Towards Unveiling Vulnerabilities of Large Reasoning Models in Machine Unlearning](https://arxiv.org/abs/2604.04255) | AAAI | LLM | — | 0 |
| Jérémie Dentan, Davide Buscaldi, Sonia Vanier | [Guess or Recall? Training CNNs to Classify and Localize Memorization in LLMs](https://doi.org/10.1609/aaai.v40i36.40304) | AAAI | LLM | [GitHub](https://github.com/orailix/cnn-4-llm-memo) | 0 |
| Yuyuan Li et al. | [FedAU2: Attribute Unlearning for User-Level Federated Recommender Systems with Adaptive and Robust Adversarial Training](https://doi.org/10.1609/aaai.v40i28.39500) | AAAI | Federated | — | 0 |
| Baogang Song et al. | [Injection, Attack and Erasure: Revocable Backdoor Attacks via Machine Unlearning](https://doi.org/10.1609/aaai.v40i30.39747) | AAAI | Vision | — | 0 |
| Man Hu et al. | [DUP: Detection-guided Unlearning for Backdoor Purification in Language Models](https://doi.org/10.1609/aaai.v40i37.40366) | AAAI | LLM | [GitHub](https://github.com/ManHu2025/DUP) | 0 |
| Tetsuya Hoya, Shunpei Morita | [Automatic Construction of Pattern Classifiers Capable of Continuous Class Incremental Learning and Unlearning](https://doi.org/10.1109/AAIML67890.2026.11498162) | AAIML | Other | — | 0 |
| Marton Szep et al. | [Unintended Memorization of Sensitive Information in Fine-Tuned Language Models](https://doi.org/10.48550/arXiv.2601.17480) | ACL | LLM | [GitHub](https://github.com/martonszep/llm-pii-leak) | 0 |
| Alyssa Shuang Sha, Bernardo Pereira Nunes, Armin Haller | [Selective Forgetting in Machine Learning and Beyond: A Survey](https://doi.org/10.1145/3796542) | ACM Computing Surveys | Other | — | 0 |
| Chen Yang et al. | [Detecting Training Data For Large Language Models: A Survey](https://doi.org/10.1145/3779430) | ACM Computing Surveys | LLM | — | 0 |
| Zhuo Cai et al. | [Misinformation Unlearning for Responsible Content Recommendation](https://doi.org/10.1145/3812649) | ACM Transactions on Information Systems | Recsys | [GitHub](https://github.com/iamZhuoCai/MisEraser) | 0 |
| Yi Gao et al. | [An Illusion of Unlearning? Assessing Machine Unlearning Through Internal Representations](https://arxiv.org/abs/2604.08271) | AISTATS Poster | Vision | — | 0 |
| Chika Onyagu et al. | [Securing the Edge: An AI-Driven Federated Unlearning Framework for Cybersecurity and IoT Forensics](https://doi.org/10.63363/aijfr.2026.v07i02.4891) | Advanced International Journal for Research | Federated | — | 0 |
| Ning Lin et al. | [Machine Unlearning and Continual Learning in Hybrid Resistive Memory Neuromorphic Systems](https://arxiv.org/abs/2601.10037) | Applied Sciences | Other | [GitHub](https://github.com/MrLinNing/RMAdaptiveMachine) | 0 |
| Khoa Tran, Simon S. Woo | [Efficient Unlearning through Maximizing Relearning Convergence Delay](https://arxiv.org/abs/2604.09391) | CVPR | Vision | — | 0 |
| Yuhang Wang et al. | [ICU-Bench:Benchmarking Continual Unlearning in Multimodal Large Language Models](https://arxiv.org/abs/2605.05938) | CVPR | LLM | — | 0 |
| Bin Cao et al. | [MOEA-SISA: Multiobjective Optimization to Improve Model Performance During Forgetting Data](https://doi.org/10.23919/cje.2024.00.052) | Chinese journal of electronics | Other | — | 0 |
| Zhenguo Ma et al. | [Enhancing federated unlearning using catastrophic forgetting in heterogeneous Industrial Internet of Things](https://doi.org/10.1016/j.comcom.2026.108497) | Computer Communications | Federated | — | 0 |
| Jiahao Fan et al. | [Fortified Concept Forgetting for text-to-image generative models by machine unlearning on CLIP](https://doi.org/10.1016/j.csi.2026.104142) | Computer Standards &amp; Interfaces | Diffusion | — | 0 |
| Jie Zhang, Chi-Ho Lin, Suan Lee | [Instruction Fine-Tuning Through the Lens of Verbatim Memorization](https://doi.org/10.3390/electronics15020377) | Electronics | LLM | [GitHub](https://github.com/muyuleiguang/instruction-ft-memorization) | 0 |
| Tazeem Ahmad et al. | [Balancing privacy and performance: An empirical study of machine unlearning in deep learning models](https://doi.org/10.1016/j.engappai.2025.113530) | Engineering applications of artificial intelligence | Other | — | 0 |
| Jie Fu et al. | [Revisiting Privacy Leakage in Machine Unlearning: Membership Inference Beyond the Forgotten Set](https://arxiv.org/abs/2605.01129) | Euro S&P' | Other | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Long Xue, Yixin Yao, Bin Song | [EAI-DMCU: Evolutionary algorithm-inspired diffusion model for concept unlearning](https://doi.org/10.1016/j.eswa.2026.132466) | Expert Systems with Applications | Diffusion | — | 0 |
| Jiaqi Chao et al. | [FedASU: Attention-guided sensitivity unlearning framework for multi-scenario federated graph unlearning](https://doi.org/10.1016/j.eswa.2026.132218) | Expert Systems with Applications | Federated | — | 0 |
| Wang Ye et al. | [Reconstruction attacks on forgotten data in federated unlearning](https://doi.org/10.1016/j.eswa.2026.131190) | Expert Systems with Applications | Federated | — | 0 |
| Cristian Cosentino et al. | [Machine Unlearning: A Perspective, Taxonomy, and Benchmark Evaluation](https://doi.org/10.3390/fi18030174) | Future Internet | Other | — | 0 |
| D.J. Ranade, Rajesh Jaiswal | [Right-to-be-Forgotten by Design in Adapter-Tuned Transformers](https://doi.org/10.1145/3777490.3777507) | HCAIep | LLM | — | 0 |
| Baisen Wang et al. | [Latent DPO for Concept Erasure in Text-To-Video Diffusion Models](https://doi.org/10.1109/icassp55912.2026.11463338) | ICASSP | Diffusion | — | 0 |
| Ruyun Wang, Fuqing Zhu, Xi Zhang | [Flash-Unlearn: On-the-Fly, Training-Free Large Language Models Unlearning Through Subspace Distribution Filtering](https://doi.org/10.1109/icassp55912.2026.11460558) | ICASSP | LLM | — | 0 |
| Weimin Lai et al. | [Federated Camouflaged Poisoning Attack in Federated Unlearning](https://doi.org/10.1109/icassp55912.2026.11463455) | ICASSP | Federated | [GitHub](https://github.com/laiweimin/FedCPA) | 0 |
| Boxu Xiao, Sijia Liu, Qing Ling | [Top-1 Compression Suffices for Federated Unlearning with the Help of Adaptive Error Feedback](https://doi.org/10.1109/icassp55912.2026.11462604) | ICASSP | Federated | — | 0 |
| Siyuan Wu et al. | [A Model-Heterogeneous Federated Unlearning Method via Negative Knowledge Distillation](https://doi.org/10.1109/icassp55912.2026.11462588) | ICASSP | Federated | — | 0 |
| Wenwei Zhao et al. | [Adversarial Update-Based Federated Unlearning for Poisoned Model Recovery](https://doi.org/10.1109/icassp55912.2026.11463407) | ICASSP | Federated | [GitHub](https://github.com/bddk520/DailyArXiv) | 0 |
| Jingwen Pu et al. | [CLEAN: Compliant Loops with Enhanced Adjustment for Training-Free Unlearning](https://doi.org/10.1109/icassp55912.2026.11463950) | ICASSP | LLM | — | 0 |
| Ruyun Wang, Fuqing Zhu, Xiaodan Zhang | [Breaking the Forgetting-Memorization Trade-Off: A Memory-Adaptive Optimizer for Effective Large Language Models Unlearning](https://doi.org/10.1109/icassp55912.2026.11462705) | ICASSP | LLM | — | 0 |
| Nikhil Saini, Rituraj Singh | [Learn to Unlearn in Large Language Models](https://doi.org/10.1109/icassp55912.2026.11464235) | ICASSP | LLM | — | 0 |
| Guofu Xie, Yu Zhou, Bingyan Liu | [FedSKU: Defending Backdoors in Federated Learning Through Selective Knowledge Unlearning](https://doi.org/10.1109/icassp55912.2026.11463673) | ICASSP | Federated | — | 0 |
| Nithya Leela, Ruthi Niyenthri, Dr. G. R. Karpagam | [Machine Unlearning Concepts, Algorithm, and Case Studies for Forgetting in Artificial Intelligence](https://doi.org/10.1109/ICISCoIS62701.2026.11448044) | ICISCoIS | Other | — | 0 |
| Ruthi Niyenthri S et al. | [Empirical Analysis of Loss Functions for Machine Unlearning Across Minority and Majority Classes](https://doi.org/10.1109/ICISCoIS62701.2026.11447967) | ICISCoIS | LLM | — | 0 |
| Yuhang Wang et al. | [Null Space Constrained Contrastive Visual Forgetting for MLLM Unlearning](https://arxiv.org/abs/2605.05909) | ICME | LLM | — | 0 |
| Zichun Ye et al. | [Unlearning Offline Stochastic Multi-Armed Bandits](https://arxiv.org/abs/2605.00638) | ICML poster | Other | — | 0 |
| S. Youn, Chulyun Kim | [MiniUn: A Machine Unlearning Method to Minimize Dependency on Original Training Data](https://doi.org/10.1109/ACCESS.2026.3653817) | IEEE Access | Other | — | 0 |
| A. Patel et al. | [Privacy-Preserving Multi-Class Skin Lesion Classification Using Single-Shot Machine Unlearning and Noise Maximization](https://doi.org/10.1109/ACCESS.2026.3669210) | IEEE Access | Vision | — | 0 |
| Shohei Yamamoto, Soh Yoshida, M. Muneyasu | [Feature Space-Preserving Machine Unlearning for Robust Image Classification With Noisy Labels](https://doi.org/10.1109/ACCESS.2026.3676403) | IEEE Access | Vision | [GitHub](https://github.com/meruemon/FSPMU) | 0 |
| Seyfullah Arslan, Fırat Aydemir | [ULTRA: A Standardized Certification Metric for Machine Unlearning](https://doi.org/10.1109/ACCESS.2026.3688958) | IEEE Access | Other | — | 0 |
| Q. Ngo et al. | [Machine Unlearning for Equalizer Classifiers in 6G Wireless Communication Systems](https://doi.org/10.1109/LCOMM.2026.3673226) | IEEE Communications Letters | Other | — | 0 |
| Yijing Lin et al. | [Proof of Unlearning for Semantic Knowledge Bases in Large Language Models-Enabled Semantic Communication](https://doi.org/10.1109/MCOM.001.2500479) | IEEE Communications Magazine | LLM | — | 0 |
| Yang Zhao et al. | [A Survey on Continuous Unlearning in Generative AI: Approaches and Tradeoffs](https://doi.org/10.1109/MIS.2025.3616192) | IEEE Intelligent Systems | Other | — | 0 |
| Wei Zheng et al. | [Label Leakage Attacks in Machine Unlearning: A Parameter and Inversion-Based Approach](https://arxiv.org/abs/2604.07386) | IEEE Open J. Comput. Soc | Vision | [GitHub](https://github.com/zhouchanggeng/DailyArXiv) | 0 |
| Claudio Savelli et al. | [UnSLU-BENCH+: Extended Machine Unlearning Benchmark for Spoken Language Understanding](https://doi.org/10.1109/TASLPRO.2026.3675768) | IEEE TASLP | Other | — | 0 |
| Laiqiao Qin et al. | [Machine Unlearning on Pre-trained Models by Residual Feature Alignment Using LoRA](https://doi.org/10.1109/tdsc.2026.3658545) | IEEE TDSC | Vision | — | 0 |
| Huanghuang Liang et al. | [Federated Unlearning via Representation Misdirection with Adaptive Anchor Generation](https://doi.org/10.1109/tdsc.2026.3689563) | IEEE TDSC | Federated | — | 0 |
| Zitong Li et al. | [SUGPT: Efficient Graph Unsummarization for the Right to Be Forgotten](https://doi.org/10.1109/TKDE.2026.3667723) | IEEE TKDE | Graph | — | 0 |
| Alessio Mora, Lorenzo Valerio, Paolo Bellavista | [Federated Unlearning via Distilled Data](https://doi.org/10.1109/tmc.2026.3666356) | IEEE TMC | Federated | [GitHub](https://github.com/alessiomora/unlearning_distilled_data) | 0 |
| Chenchen Tan et al. | [Logits-Level Balanced Machine Unlearning for LLM-Based Recommendation System](https://doi.org/10.1109/tnnls.2026.3660137) | IEEE TNNLS | Recsys | — | 0 |
| Zeyi Li et al. | [Silent-App-Aware Federated Machine Unlearning for Encrypted Network Traffic Classification](https://doi.org/10.1109/TNSE.2026.3672152) | IEEE TNSE | Federated | — | 0 |
| Yuta Goto et al. | [Feature Transformation for Learning with Selective Forgetting](https://doi.org/10.1587/transinf.2025edp7064) | IEICE Transactions on Information and Systems | Vision | — | 0 |
| Ayyadurai M, Nandha Kumar P | [Machine Unlearning for Reinforcement Learning Agents: Methods and Challenges](https://doi.org/10.1109/IITCEE67948.2026.11394122) | IITCEE | Other | — | 0 |
| Jiaqi Lang, Linjing Li, D. Zeng | [A Unified Knowledge Management Framework for Continual Learning and Machine Unlearning in Large Language Models](https://doi.org/10.3390/info17030238) | Inf | LLM | — | 0 |
| Haoke Han et al. | [Federated Illusion: Multi-Level Geometric Privacy Audit for Federated Graph Unlearning](https://doi.org/10.3390/info17050424) | Information | Federated | — | 0 |
| Yanxin Hu et al. | [FedRazor: Two-Stage Federated Unlearning via Representation Divergence and Gradient Conflict Trimming](https://doi.org/10.3390/info17020146) | Information | Federated | — | 0 |
| Jericka Guy, Chutima Boonthum-Denecke | [Forgetting by Design](https://doi.org/10.32473/flairs.39.1.141797) | International Florida Artificial Intelligence Research Society Conference | Other | — | 0 |
| Mohammad Partohaghighi et al. | [A survey on bias and fairness in machine unlearning](https://doi.org/10.1016/j.jiixd.2026.03.003) | Journal of Information and Intelligence | Other | — | 0 |
| A. Kurt et al. | [EVALUATING SISA-BASED MACHINE UNLEARNING ACROSS DIVERSE MODALITIES: TABULAR, VISUAL AND AUDITORY DATA](https://doi.org/10.56850/jnse.1829992) | Journal of Naval Sciences and Engineering | Other | — | 0 |
| Xinlei Yu, Zhen Wang, Miaomiao Wang | [A cost-efficient federated unlearning framework with rollback and compression optimization](https://doi.org/10.1016/j.knosys.2026.115699) | Knowledge-Based Systems | Federated | — | 0 |
| Tzu-Hsuan Yang, Cheng-Te Li | [ReCUR: Bipartite Graph Contrastive Unlearning with Influence Estimation for Privacy-Preserved Recommendation](https://doi.org/10.1007/s10994-025-06979-8) | Machine Learning | Recsys | — | 0 |
| Taehyeon Kim et al. | [Repulsive Guidance for Memorization Mitigation in Text-to-Music Diffusion Models](https://doi.org/10.3390/math14091512) | Mathematics | Diffusion | — | 0 |
| Xiaoran Bai et al. | [Dual-path consistency constrained concept erasure for text-to-image diffusion models](https://doi.org/10.1007/s00530-025-02168-8) | Multimedia Systems | Diffusion | — | 0 |
| Yaohua Liu, Wenjie Zhu | [Federated Unlearning via Synthetic Data Distillation](https://doi.org/10.1109/NNICE68970.2026.11465532) | NNICE | Federated | — | 0 |
| Xuran Li et al. | [PRUNE: A Patching Based Repair Framework for Certifiable and Privacy-Robust Unlearning of Neural Networks](https://doi.org/10.1016/j.neunet.2026.108897) | Neural Networks | Other | — | 0 |
| Hanxiao Wu et al. | [Adversarial discriminant attack on text-to-image diffusion models](https://doi.org/10.1016/j.neunet.2026.108716) | Neural Networks | Diffusion | — | 0 |
| Zheling Meng et al. | [Dark Miner: Towards combating residuals in concept erasure for text-to-image diffusion models](https://doi.org/10.1016/j.neucom.2026.133228) | Neurocomputing | Diffusion | — | 0 |
| Hui Chen et al. | [Entropy-driven sabotage: Informative unlearning attacks on diffusion model](https://doi.org/10.1016/j.neucom.2026.132644) | Neurocomputing | Diffusion | — | 0 |
| Qianfu Qiu et al. | [CDCU: A centroid drifting causal unlearning method for facial privacy protection](https://doi.org/10.1016/j.neucom.2026.133225) | Neurocomputing | Vision | — | 0 |
| Ningbo Liu et al. | [Balance forgetting and remembering: An extension of machine unlearning for policy updates in machine learning-based access control](https://doi.org/10.1016/j.neucom.2026.133388) | Neurocomputing | Other | [GitHub](https://github.com/ningboliucug/bfr-policy-update) | 0 |
| Asitha Kottahachchi Kankanamge Don et al. | [HQSU: Hybrid Quantum Selective Unlearning for Backdoor Mitigation in Federated Learning](https://doi.org/10.1109/QCNC69040.2026.00128) | QCNC | Federated | — | 0 |
| Don Roosan et al. | [Quantum Approximate Optimization for Targeted Weight Removal in Large Language Models](https://doi.org/10.1109/QCNC69040.2026.00178) | QCNC | LLM | — | 0 |
| Andreza M. C. Falcao, Filipe R. Cordeiro | [Does Machine Unlearning Preserve Clinical Safety? A Risk Analysis for Medical Image Classification](https://arxiv.org/abs/2604.23854) | SIBGRAPI | Vision | — | 0 |
| Doruk Benli et al. | [TUNE: A Task For Turkish Machine Unlearning For Data Privacy](https://doi.org/10.18653/v1/2026.sigturk-1.3) | SIGTURK | LLM | — | 0 |
| Jiali Wang et al. | [Feature-indistinguishable machine unlearning via negative-hot label encoding and class weight masking](https://doi.org/10.1038/s41598-026-40379-9) | Scientific Reports | Vision | — | 0 |
| Jiawei Wang et al. | [Peeling the Layers of Privacy-Utility Onion on Tabular Data](https://doi.org/10.1145/3805621.3807630) | Sixth European Workshop on Machine Learning and Systems | Other | — | 0 |
| Zifan Zhang et al. | [Network Digital Untwinning: Towards Backward Optimization of Digital Twins](https://arxiv.org/abs/2605.00169) | Struct Multidisc Optim | Other | — | 0 |
| Yun Xia | [P-Fed Rec: A Certifiable Unlearning Framework for Personalized Federated Recommendation](https://doi.org/10.24940/theijst/2025/v13/i12/st2512-004) | The International Journal of Science & Technoledge | Federated | — | 0 |
| Anamta Sayyed et al. | [CLUE: Bringing Machine Unlearning to Mobile Devices](https://doi.org/10.1109/WACV61042.2026.00366) | WACV | Vision | — | 0 |
| Mayank Kumar Kundalwal, Deepak Mishra, Asif Ekbal | [Federated Model Synchronization for Diagnostic Redefinition through a Novel Selective Parameter Unlearning](https://doi.org/10.1109/WACV61042.2026.00142) | WACV | Federated | — | 0 |
| Ce Liu et al. | [IPRU: Input-Perturbation-based Radio Frequency Fingerprinting Unlearning for LAWNs](https://arxiv.org/abs/2604.24022) | WCNC | Other | — | 0 |
| Sheetal Sehgal, Ankita Verma, Himani Bansal | [From Forgetting to Future: A Survey of Machine Unlearning Approaches](https://doi.org/10.1002/widm.70082) | WIREs Data Mining and Knowledge Discovery | Other | — | 0 |
| Chenhan Zhang et al. | [Forget Me, Not My Friends! Object Unlearning Based on Scene Graphs](https://doi.org/10.1145/3773966.3777964) | WSDM | Vision | — | 0 |
| Hakjun Moon, Simon S. Woo | [CelebCaption: A Benchmark Dataset for Identity-Sensitive Unlearning in Image Captioning](https://doi.org/10.1145/3773966.3779359) | WSDM | Vision | [GitHub](https://github.com/DASH-Lab/CelebCaption) | 0 |
| Peng Liu et al. | [Towards Practical LLM Unlearning: Efficient, Modular, and Retain-Free](https://doi.org/10.1145/3774904.3792324) | WWW | LLM | — | 0 |
| Jiajun Liu et al. | [Unlearning of Knowledge Graph Embedding via Preference Optimization](https://doi.org/10.1145/3774904.3792397) | WWW | Graph | [GitHub](https://github.com/ljj-007/GraphDPO) | 0 |
| H Wang et al. | [DIARY: Differentially Private Recovery with Adaptive Privacy Budgets in Federated Unlearning](https://doi.org/10.1145/3774904.3792423) | WWW | Federated | [GitHub](https://github.com/LaityLu/DIARY) | 0 |
| Zhigao Zheng et al. | [DeepUL: Deep Unlearning via Model Sparsity](https://doi.org/10.1145/3774904.3792441) | WWW | Other | — | 0 |
| Roy Rinberg et al. | [Easy Data Unlearning Bench](https://doi.org/10.48550/arXiv.2602.16400) | arXiv | Other | [HF](https://huggingface.co/datasets/easydub/EasyDUB-dataset) | 0 |
| Aviraj Newatia et al. | [Mitigating Privacy Risk via Forget Set-Free Unlearning](https://arxiv.org/abs/2604.10636) | arXiv | Other | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Martin Van Waerebeke et al. | [Variance-Reduced $(\varepsilon,δ)-$Unlearning using Forget Set Gradients](https://openalex.org/W7130237008) | arXiv | Other | — | 0 |
| Tuan Le, Wei Qian, Mengdi Huai | [Selective Forgetting for Large Reasoning Models](https://arxiv.org/abs/2604.03571) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xiaoyu Xu et al. | [FIT: Defying Catastrophic Forgetting in Continual LLM Unlearning](https://doi.org/10.48550/arXiv.2601.21682) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yisheng Zhong, Zhengbang Yang, Zhuangdi Zhu | [DUET: Distilled LLM Unlearning from an Efficiently Contextualized Teacher](https://doi.org/10.48550/arXiv.2601.21283) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Qiang Chen et al. | [LEGATO: Good Identity Unlearning Is Continuous](https://openalex.org/W7120272199) | arXiv | Diffusion | — | 0 |
| Pengyu Li et al. | [$\textbf{AGT$^{AO}$}$: Robust and Stabilized LLM Unlearning via Adversarial Gating Training with Adaptive Orthogonality](https://openalex.org/W7127541597) | arXiv | LLM | [GitHub](https://github.com/TiezMind/AGT-unlearning) | 0 |
| Borisiuk Anna et al. | [Anatomy of Unlearning: The Dual Impact of Fact Salience and Model Fine-Tuning](https://doi.org/10.48550/arXiv.2602.19612) | arXiv | LLM | [HF](https://huggingface.co/datasets/SwetieePawsss/DUET) | 0 |
| Zhengbang Yang et al. | [CATNIP: LLM Unlearning via Calibrated and Tokenized Negative Preference Alignment](https://doi.org/10.48550/arXiv.2602.02824) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Chahana Dahal, A. Balasubramaniam, Zuobin Xiong | [GONE: Structural Knowledge Unlearning via Neighborhood-Expanded Distribution Shaping](https://arxiv.org/abs/2603.12275) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Himanshu Mishra, Kanwal Mehreen | [QUAIL: Quantization Aware Unlearning for Mitigating Misinformation in LLMs](https://doi.org/10.48550/arXiv.2601.15538) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ningkang Peng et al. | [Don't Break the Boundary: Continual Unlearning for OOD Detection Based on Free Energy Repulsion](https://doi.org/10.48550/arXiv.2602.06331) | arXiv | Vision | — | 0 |
| Zezheng Wu et al. | [U-CAN: Utility-Aware Contrastive Attenuation for Efficient Unlearning in Generative Recommendation](https://doi.org/10.48550/arXiv.2602.23400) | arXiv | Recsys | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ramin Akbari, Milad Afshari, Vishnu Naresh Boddeti | [Obliviator Reveals the Cost of Nonlinear Guardedness in Concept Erasure](https://openalex.org/W7134859957) | arXiv | Other | [GitHub](https://github.com/afsharim/Obliviator) | 0 |
| 龚庆辉 | [Dynamic Eraser for Guided Concept Erasure in Diffusion Models](https://openalex.org/W7155244555) | arXiv | Diffusion | — | 0 |
| Chuancheng Shi et al. | [OrthoEraser: Coupled-Neuron Orthogonal Projection for Concept Erasure](https://arxiv.org/abs/2603.11493) | arXiv | Diffusion | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Jiang, Nanxiang et al. | [Z-Erase: Enabling Concept Erasure in Single-Stream Diffusion Transformers](https://arxiv.org/abs/2603.25074) | arXiv | Diffusion | [GitHub](https://github.com/nxjiang-jnx/Z-Erase) | 0 |
| Zhiqi Zhang et al. | [Differential Vector Erasure: Unified Training-Free Concept Erasure for Flow Matching Models](https://doi.org/10.48550/arXiv.2602.01089) | arXiv | Diffusion | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zhuan Shi et al. | [Neighbor-Aware Localized Concept Erasure in Text-to-Image Diffusion Models](https://arxiv.org/abs/2603.25994) | arXiv | Diffusion | [GitHub](https://github.com/alirezafarashah/NLCE) | 0 |
| Junyeong Ahn, Seojin Yoon, Sungyong Baik | [EGLOCE: Training-Free Energy-Guided Latent Optimization for Concept Erasure](https://arxiv.org/abs/2604.09405) | arXiv | Diffusion | — | 0 |
| Jun Li et al. | [Beyond Text Prompts: Precise Concept Erasure through Text-Image Collaboration](https://arxiv.org/abs/2604.15829) | arXiv | Diffusion | [GitHub](https://github.com/OpenAscent-L/TICoE) | 0 |
| Yi Sun et al. | [ActErase: A Training-Free Paradigm for Precise Concept Erasure via Activation Redirection](https://arxiv.org/abs/2601.00267) | arXiv | Diffusion | [GitHub](https://github.com/yilunzhao/s2-audit) | 0 |
| Zhaoxin Fan et al. | [EraseAnything++: Enabling Concept Erasure in Rectified Flow Transformers Leveraging Multi-Object Optimization](https://doi.org/10.48550/arXiv.2603.00978) | arXiv | Diffusion | [GitHub](https://github.com/CyL97/Awesome-Video-Generation-Post-Training) | 0 |
| Hoigi Seo et al. | [Erasing Thousands of Concepts: Towards Scalable and Practical Concept Erasure for Text-to-Image Diffusion Models](https://openalex.org/W7155246462) | arXiv | Diffusion | — | 0 |
| Yongwoo Kim et al. | [Consistency-Preserving Concept Erasure via Unsafe-Safe Pairing and Directional Fisher-weighted Adaptation](https://doi.org/10.48550/arXiv.2602.05339) | arXiv | Diffusion | — | 0 |
| Uichan Lee, Jeonghyeon Kim, Sangheum Hwang | [Localized Concept Erasure in Text-to-Image Diffusion Models via High-Level Representation Misdirection](https://openalex.org/W7131319545) | arXiv | Diffusion | — | 0 |
| Mansi et al. | [Selective Fine-Tuning for Targeted and Robust Concept Unlearning](https://doi.org/10.48550/arXiv.2602.07919) | arXiv | Diffusion | — | 0 |
| Kaiyuan Deng et al. | [Forget Many, Forget Right: Scalable and Precise Concept Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2601.06162) | arXiv | Diffusion | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zhangyun Tan et al. | [Can VLMs Truly Forget? Benchmarking Training-Free Visual Concept Unlearning](https://arxiv.org/abs/2604.03114) | arXiv | Vision | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yong Zou et al. | [REFORGE: Multi-modal Attacks Reveal Vulnerable Concept Unlearning in Image Generation Models](https://arxiv.org/abs/2603.16576) | arXiv | Diffusion | [GitHub](https://github.com/Imfatnoily/REFORGE) | 0 |
| Duc Hao Pham et al. | [A Concept is More Than a Word: Diversified Unlearning in Text-to-Image Diffusion Models](https://openalex.org/W7140001222) | arXiv | Diffusion | [GitHub](https://github.com/TruongDuy2607/Diversified_Unlearning) | 0 |
| Zeguan Xiao et al. | [Representation-Guided Parameter-Efficient LLM Unlearning](https://arxiv.org/abs/2604.17396) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Haoran Tang, Rajiv Khanna | [From Logits to Latents: Contrastive Representation Shaping for LLM Unlearning](https://doi.org/10.48550/arXiv.2601.22028) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| João Vitor Boer Abitante et al. | [Quantization-Robust LLM Unlearning via Low-Rank Adaptation](https://doi.org/10.48550/arXiv.2602.13151) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ziwen Liu et al. | [Randomized Antipodal Search Done Right for Data Pareto Improvement of LLM Unlearning](https://arxiv.org/abs/2604.16591) | arXiv | LLM | [HF](https://huggingface.co/BAAI/bge-base-en-v1.5) | 0 |
| Yisheng Zhong, Sijia Liu, Zhuangdi Zhu | [Harmonizing Multi-Objective LLM Unlearning via Unified Domain Representation and Bidirectional Logit Distillation](https://arxiv.org/abs/2604.15482) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ruihao Pan, Suhang Wang | [A Comprehensive Evaluation of LLM Unlearning Robustness under Multi-Turn Interaction](https://doi.org/10.48550/arXiv.2603.00823) | arXiv | LLM | — | 0 |
| Zhaokun Wang et al. | [CAP: Controllable Alignment Prompting for Unlearning in LLMs](https://arxiv.org/abs/2604.21251) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Esen Kurt, Haithem Afli | [Operationalising the Right to be Forgotten in LLMs: A Lightweight Sequential Unlearning Framework for Privacy-Aligned Deployment in Politically Sensitive Environments](https://arxiv.org/abs/2604.12459) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Tyler Lizzo, Larry Heck | [Unlearning in LLMs: Methods, Evaluation, and Open Challenges](https://doi.org/10.48550/arXiv.2601.13264) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ziheng Chen et al. | [CURE:Circuit-Aware Unlearning for LLM-based Recommendation](https://arxiv.org/abs/2604.04982) | arXiv | Recsys | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Bin Wang et al. | [Agentic Unlearning: When LLM Agent Meets Machine Unlearning](https://doi.org/10.48550/arXiv.2602.17692) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Dayong Ye et al. | [Secure Forgetting: A Framework for Privacy-Driven Unlearning in Large Language Model (LLM)-Based Agents](https://arxiv.org/abs/2604.00430) | arXiv | LLM | — | 0 |
| Vishnu Narayanan Anilkumar et al. | [Relationship-Aware Safety Unlearning for Multimodal LLMs](https://arxiv.org/abs/2603.14185) | arXiv | LLM | — | 0 |
| Yuze Wang et al. | [SAU: Sparsity-Aware Unlearning for LLMs via Gradient Masking and Importance Redistribution](https://arxiv.org/abs/2602.00577) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xinjie Zhou et al. | [Data-Free Privacy-Preserving for LLMs via Model Inversion and Selective Unlearning](https://doi.org/10.48550/arXiv.2601.15595) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Dinesh Srivasthav P et al. | [Shadow Unlearning: A Neuro-Semantic Approach to Fidelity-Preserving Faceless Forgetting in LLMs](https://doi.org/10.48550/arXiv.2601.04275) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xianya Fang et al. | [Beyond Superficial Unlearning: Sharpness-Aware Robust Erasure of Hallucinations in Multimodal LLMs](https://doi.org/10.48550/arXiv.2601.16527) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Eugenia Iofinova, Dan Alistarh | [Behemoth: Benchmarking Unlearning in LLMs Using Fully Synthetic Data](https://doi.org/10.48550/arXiv.2601.23153) | arXiv | LLM | [GitHub](https://github.com/IST-DASLab/behemoth) | 0 |
| Chengyi Cai et al. | [Per-parameter Task Arithmetic for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2601.22030) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ce Fang et al. | [KUDA: Knowledge Unlearning by Deviating Representation for Large Language Models](https://doi.org/10.48550/arXiv.2602.19275) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Efstratios Zaradoukas, Bardh Prenkaj, Gjergji Kasneci | [Reinforcement Unlearning via Group Relative Policy Optimization](https://doi.org/10.48550/arXiv.2601.20568) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Tien Dang et al. | [Beyond Forgetting: Machine Unlearning Elicits Controllable Side Behaviors and Capabilities](https://doi.org/10.48550/arXiv.2601.21702) | arXiv | LLM | [GitHub](https://github.com/meta-llama/llama3) | 0 |
| Chengyi Cai et al. | [Visual-Guided Key-Token Regularization for Multimodal Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2601.22020) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Mutsumi Sasaki et al. | [Exclusive Unlearning](https://arxiv.org/abs/2604.06154) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xingjian Zhao, Mohammad Mohammadi Amiri, Malik Magdon‐Ismail | [WIN-U: Woodbury-Informed Newton-Unlearning as a retain-free Machine Unlearning Framework](https://arxiv.org/abs/2604.13438) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Jagadeesh Rachapudi et al. | [RePAIR: Interactive Machine Unlearning through Prompt-Aware Model Repair](https://arxiv.org/abs/2604.12820) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xiaoyi Chen et al. | [PrivUn: Unveiling Latent Ripple Effects and Shallow Forgetting in Privacy Unlearning](https://arxiv.org/abs/2604.22076) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Seunghee Koh et al. | [Forget What Matters, Keep the Rest: Selective Unlearning of Informative Tokens](https://arxiv.org/abs/2604.17785) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Jiahao Zhang, Yilong Wang, Suhang Wang | [Attack by Unlearning: Unlearning-Induced Adversarial Attacks on Graph Neural Networks](https://arxiv.org/abs/2603.18570) | arXiv | Graph | — | 0 |
| Shreyansh Pathak, Jyotishman Das | [Graph Propagated Projection Unlearning: A Unified Framework for Vision and Audio Discriminative Models](https://arxiv.org/abs/2604.13127) | arXiv | Vision | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Zhaoyuan Cai, Xinglin Zhang | [Asynchronous Federated Unlearning with Invariance Calibration for Medical Imaging](https://arxiv.org/abs/2604.26809) | arXiv | Federated | — | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Jellyfish: Zero-Shot Federated Unlearning Scheme with Knowledge Disentanglement](https://arxiv.org/abs/2604.04030) | arXiv | Federated | [GitHub](https://github.com/xiao-jian-zi/Jellyfish) | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Forgetting to Witness: Efficient Federated Unlearning and Its Visible Evaluation](https://arxiv.org/abs/2604.04800) | arXiv | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Yuhua Xu et al. | [Client-Verifiable and Efficient Federated Unlearning in Low-Altitude Wireless Networks](https://arxiv.org/abs/2603.29688) | arXiv | Federated | — | 0 |
| Yue Li et al. | [FedCARE: Federated Unlearning with Conflict-Aware Projection and Relearning-Resistant Recovery](https://doi.org/10.48550/arXiv.2601.22589) | arXiv | Federated | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Radmehr Karimian et al. | [$f$-FUM: Federated Unlearning via min--max and $f$-divergence](https://doi.org/10.48550/arXiv.2602.06187) | arXiv | Federated | — | 0 |
| Hanwei Tan et al. | [Lethe:Adapter-Augmented Dual-Stream Update for Persistent Knowledge Erasure in Federated Unlearning](https://openalex.org/W7127203428) | arXiv | Federated | — | 0 |
| Minh-Duong Nguyen et al. | [Computation and Communication Efficient Federated Unlearning via On-server Gradient Conflict Mitigation and Expression](https://arxiv.org/abs/2603.13795) | arXiv | Federated | — | 0 |
| Zeyan Wang et al. | [FUPareto: Bridging the Forgetting-Utility Gap in Federated Unlearning via Pareto Augmented Optimization](https://openalex.org/W7127542582) | arXiv | Federated | — | 0 |
| Jer Shyuan Ng et al. | [Federated Unlearning in Edge Networks: A Survey of Fundamentals, Challenges, Practical Applications and Future Directions](https://doi.org/10.48550/arXiv.2601.09978) | arXiv | Federated | — | 0 |
| Yijun Quan, Wentai Wu, Giovanni Montana | [Exact Federated Continual Unlearning for Ridge Heads on Frozen Foundation Models](https://arxiv.org/abs/2603.12977) | arXiv | Federated | — | 0 |
| Mykola Vysotskyi et al. | [Critic-Guided Reinforcement Unlearning in Text-to-Image Diffusion](https://doi.org/10.48550/arXiv.2601.03213) | arXiv | Diffusion | — | 0 |
| K. Lee et al. | [Unlearning the Unpromptable: Prompt-free Instance Unlearning in Diffusion Models](https://arxiv.org/abs/2603.10445) | arXiv | Diffusion | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zeliang Zhang et al. | [Why Instruction-Based Unlearning Fails in Diffusion Models?](https://openalex.org/W7149874254) | arXiv | Diffusion | — | 0 |
| Ashutosh Ranjan et al. | [Forgetting is Competition: Rethinking Unlearning as Representation Interference in Diffusion Models](https://doi.org/10.48550/arXiv.2603.00975) | arXiv | Diffusion | — | 0 |
| Arian Komaei Koma et al. | [Erasure or Erosion? Evaluating Compositional Degradation in Unlearned Text-To-Image Diffusion Models](https://arxiv.org/abs/2604.04575) | arXiv | Diffusion | — | 0 |
| Manyi Li et al. | [The Illusion of Forgetting: Attack Unlearned Diffusion via Initial Latent Variable Optimization](https://doi.org/10.48550/arXiv.2602.00175) | arXiv | Diffusion | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 0 |
| Aljalila Aladawi, Mohammed Talha Alam, Fakhri Karray | [Projected Gradient Unlearning for Text-to-Image Diffusion Models: Defending Against Concept Revival Attacks](https://arxiv.org/abs/2604.21041) | arXiv | Diffusion | — | 0 |
| Ci Zhang et al. | [Roots Beneath the Cut: Uncovering the Risk of Concept Revival in Pruning-Based Unlearning for Diffusion Models](https://arxiv.org/abs/2603.06640) | arXiv | Diffusion | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Naoki MURATA et al. | [GUDA: Counterfactual Group-wise Training Data Attribution for Diffusion Models via Unlearning](https://doi.org/10.48550/arXiv.2601.22651) | arXiv | Diffusion | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Xinwen Cheng et al. | [Compensation-free Machine Unlearning in Text-to-Image Diffusion Models by Eliminating the Mutual Information](https://doi.org/10.48550/arXiv.2603.00992) | arXiv | Diffusion | [GitHub](https://github.com/OPTML-Group/AdvUnlearn) | 0 |
| Ignacy Kolton et al. | [ReLAPSe: Reinforcement-Learning-trained Adversarial Prompt Search for Erased concepts in unlearned diffusion models](https://doi.org/10.48550/arXiv.2602.00350) | arXiv | Diffusion | [GitHub](https://github.com/gmum/ReLaPSe) | 0 |
| Xiang, Qianlong et al. | [TINA: Text-Free Inversion Attack for Unlearned Text-to-Image Diffusion Models](https://arxiv.org/abs/2603.17828) | arXiv | Diffusion | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 0 |
| Zhiyong Ma et al. | [PECKER: A Precisely Efficient Critical Knowledge Erasure Recipe For Machine Unlearning in Diffusion Models](https://arxiv.org/abs/2604.05634) | arXiv | Diffusion | [GitHub](https://github.com/twenhui2-afk/daily-paper-reader) | 0 |
| Hyundo Choi et al. | [Unlearning for One-Step Generative Models via Unbalanced Optimal Transport](https://arxiv.org/abs/2603.16489) | arXiv | Diffusion | — | 0 |
| Zhanting Zhou et al. | [TRU: Targeted Reverse Update for Efficient Multimodal Recommendation Unlearning](https://arxiv.org/abs/2604.02183) | arXiv | Recsys | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Liang Qu et al. | [Federated Learning and Unlearning for Recommendation with Personalized Data Sharing](https://arxiv.org/abs/2603.11610) | arXiv | Federated | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Abdullah Khan, F. Sohel | [DurableUn: Quantization-Induced Recovery Attacks in Machine Unlearning](https://arxiv.org/abs/2605.02196) | arXiv | LLM | [GitHub](https://github.com/neurips26/DurableUnl) | 0 |
| Abdullah Khan, Hamid Laga, F. Sohel | [Metric Unreliability in Multimodal Machine Unlearning: A Systematic Analysis and Principled Unified Score](https://arxiv.org/abs/2605.02206) | arXiv | LLM | [GitHub](https://github.com/neurips26/UnifiedUnl) | 0 |
| Ruotong Ma et al. | [Graph Federated Unlearning for Privacy Preservation](https://arxiv.org/abs/2605.02297) | arXiv | Federated | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Jiawei Wu, Doudou Zhou | [Unlearning What Matters: Token-Level Attribution for Precise Language Model Unlearning](https://arxiv.org/abs/2605.00364) | arXiv | LLM | [GitHub](https://github.com/nlp-uoregon/trankit) | 0 |
| Zihao Ding, Beining Wu, Jun-Jie Huang | [EASE: Federated Multimodal Unlearning via Entanglement-Aware Anchor Closure](https://arxiv.org/abs/2605.00733) | arXiv | Federated | [GitHub](https://github.com/XCmiaow/knowledge-base) | 0 |
| Joseph Spracklen et al. | [LLM Ghostbusters: Surgical Hallucination Suppression via Adaptive Unlearning](https://arxiv.org/abs/2605.01047) | arXiv | LLM | [HF](https://huggingface.co/deepseek-ai/deepseek-coder-7b-instruct-v1.5) | 0 |
| Ishrak Hamim Mahi et al. | [Machine Unlearning for Class Removal through SISA-based Deep Neural Network Architectures](https://arxiv.org/abs/2604.27804) | arXiv | Vision | [GitHub](https://github.com/ZhikangNiu/arxiv_daily) | 0 |
| Ken Stewart | [Shape of Memory: a Geometric Analysis of Machine Unlearning in Second-Order Optimizers](https://arxiv.org/abs/2604.23046) | arXiv | Other | — | 0 |
| C. Schneider, Philipp Schoenegger, Ben Bariach | [Separable Expert Architecture: Toward Privacy-Preserving LLM Personalization via Composable Adapters and Deletable User Proxies](https://arxiv.org/abs/2604.21571) | arXiv | LLM | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Eun-Ju Park, Youjin Shin, Simon S. Woo | [Robust Continual Unlearning against Knowledge Erosion and Forgetting Reversal](https://arxiv.org/abs/2604.19108) | arXiv | Other | [GitHub](https://github.com/DASH-Lab/SAFER) | 0 |
| Arman Hatami, Romina Aalishah, I. Monosov | [Class Unlearning via Depth-Aware Removal of Forget-Specific Directions](https://arxiv.org/abs/2604.15166) | arXiv | Vision | [GitHub](https://github.com/Trustworthy-AI-Group/Adversarial_Examples_Papers) | 0 |
| Y. Rahulamathavan et al. | [Orthogonal Subspace Projection for Continual Machine Unlearning via SVD-Based LoRA](https://arxiv.org/abs/2604.12526) | arXiv | LLM | — | 0 |
| Eleni Triantafillou et al. | [Is your algorithm unlearning or untraining?](https://arxiv.org/abs/2604.07962) | arXiv | Other | [GitHub](https://github.com/frankmcsherry/blog) | 0 |
| Yunusa Haruna et al. | [Bias Redistribution in Visual Machine Unlearning: Does Forgetting One Group Harm Another?](https://arxiv.org/abs/2604.08111) | arXiv | Vision | — | 0 |
| Cai Selvas-Sala, Lei Kang, Lluis Gomez | [SALMUBench: A Benchmark for Sensitive Association-Level Multimodal Unlearning](https://arxiv.org/abs/2603.26316) | arXiv | Other | [GitHub](https://github.com/cvc-mmu/salmubench) | 0 |
| Hyundong Jin, Dongyoon Han, Eunwoo Kim | [Which Concepts to Forget and How to Refuse? Decomposing Concepts for Continual Unlearning in Large Vision-Language Models](https://arxiv.org/abs/2603.21484) | arXiv | LLM | — | 0 |
| Micha l Woźniak et al. | [Unlearning-based sliding window for continual learning under concept drift](https://arxiv.org/abs/2603.14484) | arXiv | Other | — | 0 |
| Kiseong Hong, Jungkyoo Shin, Eunwoo Kim | [Stake the Points: Structure-Faithful Instance Unlearning](https://arxiv.org/abs/2603.12915) | arXiv | Vision | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 0 |
| Thanapat Trachu et al. | [Targeted Speaker Poisoning Framework in Zero-Shot Text-to-Speech](https://arxiv.org/abs/2603.07551) | arXiv | LLM | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 0 |
| Nanhong Liu et al. | [A SISA-based Machine Unlearning Framework for Power Transformer Inter-Turn Short-Circuit Fault Localization](https://arxiv.org/abs/2603.06962) | arXiv | Other | — | 0 |
| Reo Fukunaga, Soh Yoshida, M. Muneyasu | [ACD-U: Asymmetric co-teaching with machine unlearning for robust learning with noisy labels](https://arxiv.org/abs/2603.07166) | arXiv | Vision | [GitHub](https://github.com/meruemon/ACD-U) | 0 |
| Carolin Heinzler, Kasra Malihi, Amartya Sanyal | [Less Noise, Same Certificate: Retain Sensitivity for Unlearning](https://arxiv.org/abs/2603.03172) | arXiv | Other | — | 0 |
| Ji-Wha Shin et al. | [ROKA: Robust Knowledge Unlearning against Adversaries](https://doi.org/10.48550/arXiv.2603.00436) | arXiv | LLM | — | 0 |
| Tiantong Wang et al. | [MPU: Towards Secure and Privacy-Preserving Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2602.23798) | arXiv | LLM | [GitHub](https://github.com/Tristan-SHU/MPU) | 0 |
| Yong-Sheng Chen et al. | [Unlearning Noise in PINNs: A Selective Pruning Framework for PDE Inverse Problems](https://doi.org/10.48550/arXiv.2602.19967) | arXiv | Other | [GitHub](https://github.com/chenyongssss/PPINN) | 0 |
| Haoyu Wang et al. | [MeGU: Machine-Guided Unlearning with Target Feature Disentanglement](https://doi.org/10.48550/arXiv.2602.17088) | arXiv | Vision | — | 0 |
| Martin Van Waerebeke et al. | [Variance-Reduced $(\varepsilon,\delta)-$Unlearning using Forget Set Gradients](https://arxiv.org/abs/2602.14938) | arXiv | Other | — | 0 |
| Jaewon Lee, Yongwoo Kim, Donghyun Kim | [Erase at the Core: Representation Unlearning for Machine Unlearning](https://doi.org/10.48550/arXiv.2602.05375) | arXiv | Vision | — | 0 |
| Ojasva Nema et al. | [Structural Disentanglement in Bilinear MLPs via Architectural Inductive Bias](https://doi.org/10.48550/arXiv.2602.05635) | arXiv | Other | — | 0 |
| Somnath Basu Roy Chowdhury et al. | [Inference-time Unlearning Using Conformal Prediction](https://doi.org/10.48550/arXiv.2602.03787) | arXiv | Other | — | 0 |
| Pengyu Li et al. | [AGTAO: Robust and Stabilized LLM Unlearning via Adversarial Gating Training with Adaptive Orthogonality](https://doi.org/10.48550/arXiv.2602.01703) | arXiv | LLM | [GitHub](https://github.com/TiezMind/AGT-unlearning) | 0 |
| Tian Zhang et al. | [Forget by Uncertainty: Orthogonal Entropy Unlearning for Quantized Neural Networks](https://doi.org/10.48550/arXiv.2602.00567) | arXiv | Vision | — | 0 |
| Kun Fang et al. | [Machine Unlearning in Low-Dimensional Feature Subspace](https://doi.org/10.48550/arXiv.2601.22456) | arXiv | Vision | [HF](https://huggingface.co/datasets/wmt/wmt19) | 0 |
| Antonio Almud'evar, Alfonso Ortega | [Representation Unlearning: Forgetting through Information Compression](https://doi.org/10.48550/arXiv.2601.21564) | arXiv | Other | [GitHub](https://github.com/antonioalmudevar/representation_unlearning) | 0 |
| Liheng Yu et al. | [FaLW: A Forgetting-aware Loss Reweighting for Long-tailed Unlearning](https://doi.org/10.48550/arXiv.2601.18650) | arXiv | Vision | — | 0 |
| A. Zhu et al. | [GRIP: Algorithm-Agnostic Machine Unlearning for Mixture-of-Experts via Geometric Router Constraints](https://doi.org/10.48550/arXiv.2601.16905) | arXiv | LLM | — | 0 |
| Jinduo Guo, Yinzhi Cao | [A Robust Certified Machine Unlearning Method Under Distribution Shift](https://doi.org/10.48550/arXiv.2601.06967) | arXiv | Other | — | 0 |
| Hengliang Wu et al. | [Certified Unlearning in Decentralized Federated Learning](https://doi.org/10.48550/arXiv.2601.06436) | arXiv | Federated | — | 0 |
| Nausherwan Malik, Z. Khalid, Muhammad Faryad | [Distribution-Guided and Constrained Quantum Machine Unlearning](https://doi.org/10.48550/arXiv.2601.04413) | arXiv | Other | — | 0 |
| Intae Jeon, Yujeong Kwon, Hyungjoon Koo | [UnPII: Unlearning Personally Identifiable Information with Quantifiable Exposure Risk](https://doi.org/10.48550/arXiv.2601.01786) | arXiv | LLM | [GitHub](https://github.com/ai-safety-unlearning/unpii) | 0 |
| Hongbin Lin et al. | [Controllable Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2601.00451) | arXiv | Vision | — | 0 |
| Sam Gunn | [How to sketch a learning algorithm](https://arxiv.org/abs/2604.07328) | arXiv | Other | [GitHub](https://github.com/SamSpo1/microgpt-sketch) | 0 |
| Amber Yijia Zheng, Yue Tai, Raymond A. Yeh | [Designing to Forget: Deep Semi-parametric Models for Unlearning](https://arxiv.org/abs/2603.22870) | arXiv | Other | [GitHub](https://github.com/amberyzheng/spm_unlearning) | 0 |
| Aloni Cohen et al. | [Protecting the Undeleted in Machine Unlearning](https://doi.org/10.48550/arXiv.2602.16697) | arXiv | Other | — | 0 |
| Hanna Benarroch, Jamal Atif, Olivier Capp'e | [Certified Per-Instance Unlearning Using Individual Sensitivity Bounds](https://doi.org/10.48550/arXiv.2602.15602) | arXiv | Other | — | 0 |
| Jacob L. Block et al. | [Temper-Then-Tilt: Principled Unlearning for Generative Models through Tempering and Classifier Guidance](https://doi.org/10.48550/arXiv.2602.10217) | arXiv | Other | — | 0 |
| Sangyeon Yoon et al. | [Rethinking Benign Relearning: Syntax as the Hidden Driver of Unlearning Failures](https://doi.org/10.48550/arXiv.2602.03379) | arXiv | LLM | [HF](https://huggingface.co/locuslab/tofu_ft_llama2-7b) | 0 |
| Pawel Batorski, Paul Swoboda | [EvoMU: Evolutionary Machine Unlearning](https://doi.org/10.48550/arXiv.2602.02139) | arXiv | Other | [GitHub](https://github.com/Batorskq/EvoMU) | 0 |
| Polina Dolgova, Sebastian U. Stich | [Sequential Subspace Noise Injection Prevents Accuracy Collapse in Certified Unlearning](https://doi.org/10.48550/arXiv.2601.05134) | arXiv | Vision | [GitHub](https://github.com/mlolab/blockwise-noisy-fine-tuning) | 0 |
| Kairan Zhao, Iurie Luca, Peter Triantafillou | [Benchmarking Unlearning for Vision Transformers](https://doi.org/10.48550/arXiv.2602.20114) | arXiv | Vision | — | 0 |
| Wei-Kai Chang, Rajiv Khanna | [Why Some Models Resist Unlearning: A Linear Stability Perspective](https://doi.org/10.48550/arXiv.2602.02986) | arXiv | Other | — | 0 |
| Y. Jang et al. | [Suppression or Deletion: A Restoration-Based Representation-Level Analysis of Machine Unlearning](https://doi.org/10.1145/3774904.3792896) | arXiv | Vision | [HF](https://huggingface.co/Yurim0507/suppression-or-deletion) | 0 |
| M'onica Ribero, Antonin Schrab, Arthur Gretton | [Regularized f-Divergence Kernel Tests](https://doi.org/10.48550/arXiv.2601.19755) | arXiv | Other | — | 0 |
| Jagadeesh Rachapudi et al. | [BID-LoRA: A Parameter-Efficient Framework for Continual Learning and Unlearning](https://arxiv.org/abs/2604.12686) | arXiv | LLM | [GitHub](https://github.com/shaokangW/LLM-wisdom) | 0 |
| Kai Zhao, Eleni Triantafillou, Peter Triantafillou | [You Don't Need All That Attention: Surgical Memorization Mitigation in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2603.00133) | arXiv | Diffusion | [GitHub](https://github.com/kairanzhao/GUARD) | 0 |
| Piotr W'ojcik et al. | [UnHype: CLIP-Guided Hypernetworks for Dynamic LoRA Unlearning](https://doi.org/10.48550/arXiv.2602.03410) | arXiv | Diffusion | [GitHub](https://github.com/gmum/UnHype) | 0 |
| Eric K. Easley, Sebastian Farquhar | [Latent Instruction Representation Alignment: defending against jailbreaks, backdoors and undesired knowledge in LLMs](https://arxiv.org/abs/2604.10403) | arXiv | LLM | — | 0 |
| P. Rybak et al. | [REBEL: Hidden Knowledge Recovery via Evolutionary-Based Evaluation Loop](https://doi.org/10.48550/arXiv.2602.06248) | arXiv | LLM | [GitHub](https://github.com/patryk-rybak/REBEL) | 0 |
| Yejin Kim et al. | [Knowledge Vector Weakening: Efficient Training-free Unlearning for Large Vision-Language Models](https://doi.org/10.48550/arXiv.2601.21794) | arXiv | LLM | — | 0 |
| Tyler Lizzo, Larry Heck | [Evaluating Cross-Lingual Unlearning in Multilingual Language Models](https://doi.org/10.48550/arXiv.2601.06675) | arXiv | LLM | — | 0 |
| Anna Mazhar, Sainyam Galhotra | [Towards Reliable Testing of Machine Unlearning](https://doi.org/10.1145/3803437.3805557) | arXiv | Other | — | 0 |
| Yan Huang et al. | [Subspace Control: Turning Constrained Model Steering into Controllable Spectral Optimization](https://arxiv.org/abs/2604.04231) | arXiv | LLM | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 0 |
| N. Sepahvand et al. | [Detoxifying LLMs via Representation Erasure-Based Preference Optimization](https://doi.org/10.48550/arXiv.2602.23391) | arXiv | LLM | — | 0 |
| Jialong Sun et al. | [Statistical MIA: Rethinking Membership Inference Attack for Reliable Unlearning Auditing](https://doi.org/10.48550/arXiv.2602.01150) | arXiv | Other | — | 0 |
| N. Konovalova, Andrey Kuznetsov, Aibek Alanov | [SHIFT: Steering Hidden Intermediates in Flow Transformers](https://arxiv.org/abs/2604.09213) | arXiv | Diffusion | [GitHub](https://github.com/ControlGenAI/SHIFT) | 0 |
| Lingyun Zhang et al. | [SafeCtrl: Region-Aware Safety Control for Text-to-Image Diffusion via Detect-Then-Suppress](https://arxiv.org/abs/2604.03941) | arXiv | Diffusion | — | 0 |
| Xian Yang et al. | [SafeRoPE: Risk-specific Head-wise Embedding Rotation for Safe Generation in Rectified Flow Transformers](https://arxiv.org/abs/2604.01826) | arXiv | Diffusion | [GitHub](https://github.com/deng12yx/SafeRoPE) | 0 |
| Yi-Yang Xie, Zheng Zhang, Ping Liu | [PROBE: Diagnosing Residual Concept Capacity in Erased Text-to-Video Diffusion Models](https://arxiv.org/abs/2603.21547) | arXiv | Diffusion | [GitHub](https://github.com/YiweiXie/PRObingBasedEvaluation) | 0 |
| Sathwik Karnik et al. | [Steering Away from Memorization: Reachability-Constrained Reinforcement Learning for Text-to-Image Diffusion](https://doi.org/10.48550/arXiv.2603.00140) | arXiv | Diffusion | — | 0 |
| Shingo Kodama et al. | [Understanding Empirical Unlearning with Combinatorial Interpretability](https://doi.org/10.48550/arXiv.2602.19215) | arXiv | Other | — | 0 |
| Tong Zhang, Ru Zhang, Jianyi Liu | [DICE: Disentangling Artist Style from Content via Contrastive Subspace Decomposition in Diffusion Models](https://doi.org/10.48550/arXiv.2602.08059) | arXiv | Diffusion | — | 0 |
| Natnael Mola et al. | [SPARE: Self-distillation for PARameter-Efficient Removal](https://arxiv.org/abs/2602.07058) | arXiv | Diffusion | [GitHub](https://github.com/AtharvaTaras/Dog-Breeds-Dataset) | 0 |
| Mengyu Sun et al. | [LURE: Latent Space Unblocking for Multi-Concept Reawakening in Diffusion Models](https://doi.org/10.48550/arXiv.2601.14330) | arXiv | Diffusion | — | 0 |
| Carolina R. Kelsch et al. | [FADE: Selective Forgetting via Sparse LoRA and Self-Distillation](https://doi.org/10.48550/arXiv.2602.07058) | arXiv | LLM | — | 0 |
| Pierre Lubitzsch, M. D. Rijke, Sebastian Schelter | [ERASE -- A Real-World Aligned Benchmark for Unlearning in Recommender Systems](https://arxiv.org/abs/2603.08341) | arXiv | Recsys | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Heng Xu et al. | [Forgetting Similar Samples: Can Machine Unlearning Do it Better?](https://doi.org/10.48550/arXiv.2601.06938) | arXiv | Other | [HF](https://huggingface.co/BAAI/bge-small-en) | 0 |
| Chenchen Tan et al. | [Less is More: Geometric Unlearning for LLMs with Minimal Data Disclosure](https://openalex.org/W7160457692) | arXiv | LLM | [GitHub](https://github.com/CCT-sys/GU) | 0 |
| Jingjing Zhou et al. | [Stable Multimodal Graph Unlearning via Feature-Dimension Aware Quantile Selection](https://arxiv.org/abs/2605.03303) | arXiv | Graph | — | 0 |
| Rohan Asthana, Belagiannis, Vasileios | [Detecting and Mitigating Memorization in Diffusion Models through Anisotropy of the Log-Probability](https://openalex.org/W7126123155) | arXiv | Diffusion | [GitHub](https://github.com/rohanasthana/memorization-anisotropy) | 0 |
| Yunzhuo Chen et al. | [Mitigating Memorization in Text-to-Image Diffusion via Region-Aware Prompt Augmentation and Multimodal Copy Detection](https://openalex.org/W7138824496) | arXiv | Diffusion | — | 0 |
| Yuto Nishida et al. | [Revisiting Non-Verbatim Memorization in Large Language Models: The Role of Entity Surface Forms](https://openalex.org/W7155654349) | arXiv | LLM | — | 0 |
| A. Feder Cooper et al. | [Estimating near-verbatim extraction risk in language models with decoding-constrained beam search](https://openalex.org/W7142557463) | arXiv | LLM | — | 0 |
| Kıvanç Kuzey Dikici et al. | [SERSEM: Selective Entropy-Weighted Scoring for Membership Inference in Code Language Models](https://openalex.org/W7149210024) | arXiv | LLM | — | 0 |
| Omer Sela | [No Memorization, No Detection: Output Distribution-Based Contamination Detection in Small Language Models](https://openalex.org/W7133571309) | arXiv | LLM | [GitHub](https://github.com/Sela-Omer/Contamination-Detection-Small-LM) | 0 |
| Chaoran Chen, Dayu Yuan, Peter Kairouz | [Behavioral Canaries: Auditing Private Retrieved Context Usage in RL Fine-Tuning](https://openalex.org/W7157505974) | arXiv | LLM | — | 0 |
| Junehyoung Kwon, JungMin Yun, YoungBin Kim | [Erase Persona, Forget Lore: Benchmarking Multimodal Copyright Unlearning in Large Vision Language Models](https://doi.org/10.63317/3zvek95uex2j) | arXiv | LLM | [HF](https://huggingface.co/datasets/herbwood27/CoVUBench) | 0 |
| Junhao Cai et al. | [Retain-Neutral Surrogates for Min-Max Unlearning](https://arxiv.org/abs/2605.05871) | arXiv | Other | — | 0 |
| Alexander Vedernikov | [Not Every Subject Should Stay: Machine Unlearning for Noisy Engagement Recognition](https://arxiv.org/abs/2605.04713) | arXiv | Vision | — | 0 |
| Junehyoung Kwon et al. | [Before Forgetting, Learn to Remember: Revisiting Foundational Learning Failures in LVLM Unlearning Benchmarks](https://arxiv.org/abs/2605.03759) | arXiv | LLM | [HF](https://huggingface.co/datasets/herbwood27/Remem) | 0 |
| Hsiang Hsu et al. | [A RE W E R EALLY U NLEARNING ? T HE P RESENCE OF R ESIDUAL K NOWLEDGE IN M ACHINE U NLEARNING](https://www.semanticscholar.org/paper/ea8f955b53d311b8539219fd64e7d38f7eaf6c10) | arXiv | Other | — | 0 |
| Quintin Pope et al. | [Automatically Finding and Validating Unexpected Side-Effects of Interventions on Language Models](https://arxiv.org/abs/2605.05090) | arXiv | LLM | — | 0 |

## 2025

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Thành Tâm Nguyên et al. | [A Survey of Machine Unlearning](https://doi.org/10.1145/3749987) | ACM TIST | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 385 |
| Sijia Liu et al. | [Rethinking machine unlearning for large language models](https://doi.org/10.1038/s42256-025-00985-0) | Nature Machine Intelligence | LLM | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 261 |
| Leyang Li et al. | [Set You Straight: Auto-Steering Denoising Trajectories to Sidestep Unwanted Concepts](https://doi.org/10.1145/3746027.3754546) | ACM MM | Diffusion | [GitHub](https://github.com/lileyang1210/ant) | 60 |
| Chongyu Fan et al. | [Towards LLM Unlearning Resilient to Relearning Attacks: A Sharpness-Aware Minimization Perspective and Beyond](https://doi.org/10.48550/arXiv.2502.05374) | ICML | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-Smooth) | 54 |
| Alberto Blanco-Justicia et al. | [Digital forgetting in large language models: a survey of unlearning methods](https://doi.org/10.1007/s10462-024-11078-6) | Artificial Intelligence Review | LLM | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 53 |
| Fazl Barez et al. | [Open Problems in Machine Unlearning for AI Safety](https://doi.org/10.48550/arXiv.2501.04952) | arXiv | LLM | — | 53 |
| Bartosz Cywi'nski, Kamil Deja | [SAeUron: Interpretable Concept Unlearning in Diffusion Models with Sparse Autoencoders](https://doi.org/10.48550/arXiv.2501.18052) | ICML | Diffusion | [GitHub](https://github.com/cywinski/SAeUron) | 52 |
| Wenjie Fu et al. | [Membership Inference Attacks against Generative Models with Probabilistic Fluctuation](https://www.semanticscholar.org/paper/78597483c2116b836caa75c466565e5cba0b96fc) | DIG-BUG Short | Other | — | 50 |
| Qizhou Wang et al. | [Rethinking LLM Unlearning Objectives: A Gradient Perspective and Go Beyond](https://doi.org/10.48550/arXiv.2502.19301) | ICLR | LLM | [GitHub](https://github.com/QizhouWang/G-effect) | 49 |
| Jamie Hayes et al. | [Measuring memorization in language models via probabilistic extraction](https://doi.org/10.18653/v1/2025.naacl-long.469) | NAACL | LLM | [GitHub](https://github.com/chawins/llm-sp) | 38 |
| Zora Che et al. | [Model Tampering Attacks Enable More Rigorous Evaluations of LLM Capabilities](https://doi.org/10.48550/arXiv.2502.05209) | TMLR | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 38 |
| Hongkang Li et al. | [When is Task Vector Provably Effective for Model Editing? A Generalization Analysis of Nonlinear Transformers](https://doi.org/10.48550/arXiv.2504.10957) | ICLR | LLM | — | 35 |
| Vineeth Dorna et al. | [OpenUnlearning: Accelerating LLM Unlearning via Unified Benchmarking of Methods and Metrics](https://doi.org/10.48550/arXiv.2506.12618) | arXiv | LLM | [GitHub](https://github.com/huggingface/accelerate) | 35 |
| Huu-Tien Dang et al. | [On Effects of Steering Latent Representation for Large Language Model Unlearning](https://doi.org/10.1609/aaai.v39i22.34544) | AAAI | LLM | [GitHub](https://github.com/RebelsNLU-jaist/llm-unlearning) | 33 |
| Martin Tutek et al. | [Measuring Chain of Thought Faithfulness by Unlearning Reasoning Steps](https://doi.org/10.18653/v1/2025.emnlp-main.504) | EMNLP | LLM | [HF](https://huggingface.co/spaces/richardyoung/abliteration-methods-dashboard) | 33 |
| Zijie Pan et al. | [Feature-Based Machine Unlearning for Vertical Federated Learning in IoT Networks](https://doi.org/10.1109/tmc.2025.3530529) | IEEE TMC | Federated | — | 32 |
| Yijiang River Dong et al. | [UNDIAL: Self-Distillation with Adjusted Logits for Robust Unlearning in Large Language Models](https://doi.org/10.18653/v1/2025.naacl-long.444) | NAACL | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 32 |
| Puning Yang et al. | [Exploring Criteria of Loss Reweighting to Enhance LLM Unlearning](https://doi.org/10.48550/arXiv.2505.11953) | ICML | LLM | [GitHub](https://github.com/tmlr-group/SatImp) | 30 |
| Yuyuan Li et al. | [Multi-Objective Unlearning in Recommender Systems via Preference Guided Pareto Exploration](https://doi.org/10.1109/tsc.2025.3593906) | IEEE TSC | Recsys | — | 29 |
| Anh-Vu Bui et al. | [Fantastic Targets for Concept Erasure in Diffusion Models and Where To Find Them](https://doi.org/10.48550/arXiv.2501.18950) | ICLR | Diffusion | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 27 |
| Xuandong Zhao et al. | [Improving LLM Safety Alignment with Dual-Objective Optimization](https://doi.org/10.48550/arXiv.2503.03710) | ICML | LLM | [GitHub](https://github.com/wicai24/door-alignment) | 27 |
| Jiahui Geng et al. | [A Comprehensive Survey of Machine Unlearning Techniques for Large Language Models](https://doi.org/10.48550/arXiv.2503.01854) | arXiv | LLM | [GitHub](https://github.com/jujingliuzy/Unlearning-LLM-papers) | 27 |
| Jiahao Huo et al. | [MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2502.11051) | ACL | LLM | [GitHub](https://github.com/Z1zs/MMUnlearner) | 26 |
| Anil Ramakrishna et al. | [LUME: LLM Unlearning with Multitask Evaluations](https://doi.org/10.48550/arXiv.2502.15097) | EMNLP | LLM | [GitHub](https://github.com/amazon-science/lume-llm-unlearning) | 25 |
| Mengshu Song et al. | [Trustworthy Intelligent Networks for Low-Altitude Economy](https://doi.org/10.1109/mcom.001.2400692) | IEEE Communications Magazine | Federated | — | 25 |
| Junkai Chen et al. | [SafeEraser: Enhancing Safety in Multimodal Large Language Models through Multimodal Machine Unlearning](https://doi.org/10.48550/arXiv.2502.12520) | ACL | LLM | — | 23 |
| XiaoYu Xu et al. | [Unlearning Isn't Deletion: Investigating Reversibility of Machine Unlearning in LLMs](https://doi.org/10.48550/arXiv.2505.16831) | arXiv | LLM | [GitHub](https://github.com/XiaoyuXU1/Representational_Analysis_Tools) | 23 |
| Meng Li, Haochen Sui | [Causal Recommendation via Machine Unlearning with a Few Unbiased Data](https://www.semanticscholar.org/paper/9d69eebef7cd41b4d6f480ab438268f848920215) | AAAI Workshop on Artificial Intelligence with Causal Techniques | Recsys | — | 22 |
| Yu Zhou et al. | [Decoupled Distillation to Erase: A General Unlearning Method for Any Class-centric Tasks](https://doi.org/10.1109/CVPR52734.2025.01895) | CVPR | Vision | — | 22 |
| Zhengyi Zhong et al. | [Unlearning through Knowledge Overwriting: Reversible Federated Unlearning via Selective Sparse Adapter](https://doi.org/10.1109/CVPR52734.2025.02855) | CVPR | Federated | [GitHub](https://github.com/Zhong-Zhengyi/FUSED-Code) | 22 |
| Naveen George et al. | [The Illusion of Unlearning: The Unstable Nature of Machine Unlearning in Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.01250) | CVPR | Diffusion | [GitHub](https://github.com/DIL-IITH/TIU) | 22 |
| K. Liu et al. | [Language Models May Verbatim Complete Text They Were Not Explicitly Trained On](https://doi.org/10.48550/arXiv.2503.17514) | ICML | LLM | [GitHub](https://github.com/karpathy/llm.c) | 22 |
| William F. Shen et al. | [LUNAR: LLM Unlearning via Neural Activation Redirection](https://doi.org/10.48550/arXiv.2502.07218) | arXiv | LLM | [GitHub](https://github.com/facebookresearch/LUNAR) | 22 |
| Ouxiang Li et al. | [SPEED: Scalable, Precise, and Efficient Concept Erasure for Diffusion Models](https://doi.org/10.48550/arXiv.2503.07392) | arXiv | Diffusion | [GitHub](https://github.com/Ouxiang-Li/SPEED) | 22 |
| Aobo Chen et al. | [A survey of security and privacy issues of machine unlearning](https://doi.org/10.1002/aaai.12209) | AI Magazine | Other | — | 21 |
| Yuyuan Li et al. | [Class-wise federated unlearning: Harnessing active forgetting with teacher–student memory generation](https://doi.org/10.1016/j.knosys.2025.113353) | Knowledge-Based Systems | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 21 |
| Aashiq Muhamed et al. | [SAEs Can Improve Unlearning: Dynamic Sparse Autoencoder Guardrails for Precision Unlearning in LLMs](https://doi.org/10.48550/arXiv.2504.08192) | arXiv | LLM | [GitHub](https://github.com/aashiqmuhamed/DynamicSAEGuardrails) | 20 |
| Zheyuan Liu et al. | [Modality-Aware Neuron Pruning for Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2502.15910) | ACL | LLM | [GitHub](https://github.com/franciscoliu/MANU) | 18 |
| Haoming Xu et al. | [ReLearn: Unlearning via Learning for Large Language Models](https://doi.org/10.48550/arXiv.2502.11190) | ACL | LLM | [GitHub](https://github.com/zjunlp/unlearn) | 18 |
| Byung Hyun Lee, Sungjin Lim, Se Young Chun | [Localized Concept Erasure for Text-to-Image Diffusion Models Using Training-Free Gated Low-Rank Adaptation](https://doi.org/10.1109/CVPR52734.2025.01733) | CVPR | Diffusion | [GitHub](https://github.com/Hyun1A/GLoCE) | 18 |
| Byung Hyun Lee et al. | [Concept Pinpoint Eraser for Text-to-image Diffusion Models via Residual Attention Gate](https://doi.org/10.48550/arXiv.2506.22806) | ICLR | Diffusion | [GitHub](https://github.com/Hyun1A/CPE) | 17 |
| Yasser H. Khalil et al. | [NoT: Federated Unlearning via Weight Negation](https://doi.org/10.1109/CVPR52734.2025.02399) | CVPR | Federated | [GitHub](https://github.com/mahdibeit/mahdibeit) | 16 |
| Zihao Wang et al. | [ACE: Anti-Editing Concept Erasure in Text-to-Image Models](https://doi.org/10.48550/arXiv.2501.01633) | CVPR | Diffusion | [GitHub](https://github.com/120l020904/ace) | 16 |
| He Zhang et al. | [Dynamic Graph Unlearning: A General and Efficient Post-Processing Method via Gradient Transformation](https://doi.org/10.1145/3696410.3714911) | WWW | Graph | — | 16 |
| K. Thakral et al. | [Fine-Grained Erasure in Text-To-Image Diffusion-Based Foundation Models](https://doi.org/10.1109/CVPR52734.2025.00852) | CVPR | Diffusion | — | 15 |
| Anastasia Koloskova et al. | [Certified Unlearning for Neural Networks](https://doi.org/10.48550/arXiv.2506.06985) | ICML | Other | [GitHub](https://github.com/stair-lab/certified-unlearning-neural-networks-icml-2025) | 15 |
| Mingyu Kim et al. | [Training-Free Safe Denoisers for Safe Use of Diffusion Models](https://doi.org/10.48550/arXiv.2502.08011) | arXiv | Diffusion | [GitHub](https://github.com/KJaebye/EmbodiedAI-Robotics-arXiv-Daily-Reporter) | 15 |
| Youyang Qu et al. | [The Frontier of Data Erasure: A Survey on Machine Unlearning for Large Language Models](https://doi.org/10.1109/mc.2024.3405397) | Computer | LLM | — | 14 |
| Gaurav Patel, Qiang Qiu | [Learning to Unlearn While Retaining: Combating Gradient Conflicts in Machine Unlearning](https://doi.org/10.1109/ICCV51701.2025.00401) | ICCV | Vision | — | 14 |
| Silas Alberti et al. | [Data Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2503.01034) | ICLR | Diffusion | [GitHub](https://github.com/claserken/SISS) | 14 |
| Changsheng Wang et al. | [Invariance Makes LLM Unlearning Resilient Even to Unanticipated Downstream Fine-Tuning](https://doi.org/10.48550/arXiv.2506.01339) | ICML | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 14 |
| Biao Yi et al. | [CTRAP: Embedding Collapse Trap to Safeguard Large Language Models from Harmful Fine-Tuning](https://doi.org/10.48550/arXiv.2505.16559) | arXiv | LLM | [HF](https://huggingface.co/datasets/openai/gsm8k) | 14 |
| Kevin Kuo et al. | [Exact Unlearning of Finetuning Data via Model Merging at Scale](https://doi.org/10.48550/arXiv.2504.04626) | arXiv | LLM | — | 14 |
| Christoforos N. Spartalis et al. | [LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty](https://doi.org/10.1109/CVPR52734.2025.00939) | CVPR | Vision | [GitHub](https://github.com/cspartalis/LoTUS) | 13 |
| Zhenyu Yu et al. | [ForgetMe: Benchmarking the selective forgetting capabilities of generative models](https://doi.org/10.1016/j.engappai.2025.112087) | Engineering Applications of Artificial Intelligence | Diffusion | [GitHub](https://github.com/YuZhenyuLindy/ForgetMe) | 13 |
| Shanshan Ye, Jie Lü, Guangquan Zhang | [Towards Safe Machine Unlearning: A Paradigm that Mitigates Performance Degradation](https://doi.org/10.1145/3696410.3714638) | WWW | Other | — | 13 |
| Jie Ren et al. | [A General Framework to Enhance Fine-tuning-based LLM Unlearning](https://doi.org/10.48550/arXiv.2502.17823) | ACL | LLM | [GitHub](https://github.com/renjie3/GRUN) | 12 |
| Denghui Zhang, Zhaozhuo Xu, Weijie Zhao | [LLMs and Copyright Risks: Benchmarks and Mitigation Approaches](https://doi.org/10.18653/v1/2025.naacl-tutorial.7) | ACL | LLM | — | 12 |
| Changsheng Wang et al. | [Reasoning Model Unlearning: Forgetting Traces, Not Just Answers, While Preserving Reasoning Skills](https://doi.org/10.48550/arXiv.2506.12963) | EMNLP | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-R2MU) | 12 |
| S. S et al. | [Machine Unlearning for Grid SearchCV](https://doi.org/10.1109/ICCTDC64446.2025.11158784) | ICCTDC | Other | — | 12 |
| Ruidong Chen et al. | [TRCE: Towards Reliable Malicious Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICCV51701.2025.01759) | ICCV | Diffusion | [GitHub](https://github.com/ddgoodgood/TRCE) | 12 |
| Yue Wang et al. | [GRU: Mitigating the Trade-off between Unlearning and Retention for Large Language Models](https://doi.org/10.48550/arXiv.2503.09117) | ICML | LLM | — | 12 |
| Zeng Wang et al. | [SALAD: Systematic Assessment of Machine Unlearning on LLM-Aided Hardware Design](https://doi.org/10.1109/MLCAD65511.2025.11189152) | Workshop on Machine Learning for CAD | LLM | [GitHub](https://github.com/DfX-NYUAD/SALAD) | 12 |
| Yiwei Chen et al. | [Unlearning Isn't Invisible: Detecting Unlearning Traces in LLMs from Model Outputs](https://doi.org/10.48550/arXiv.2506.14003) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-Trace) | 12 |
| Soumyadeep Pal et al. | [LLM Unlearning Reveals a Stronger-Than-Expected Coreset Effect in Current Benchmarks](https://doi.org/10.48550/arXiv.2504.10185) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/MU-Coreset) | 12 |
| Rongzhe Wei et al. | [Do LLMs Really Forget? Evaluating Unlearning with Knowledge Correlation and Confidence Awareness](https://doi.org/10.48550/arXiv.2506.05735) | arXiv | LLM | [GitHub](https://github.com/Graph-COM/Knowledge_Unlearning) | 12 |
| Daiheng Gao et al. | [Revoking Amnesia: RL-based Trajectory Optimization to Resurrect Erased Concepts in Diffusion Models](https://doi.org/10.48550/arXiv.2510.03302) | arXiv | Diffusion | [HF](https://huggingface.co/black-forest-labs/FLUX.1-dev) | 12 |
| Yongwoo Kim, Sungmin Cha, Donghyun Kim | [Are We Truly Forgetting? A Critical Re-examination of Machine Unlearning Evaluation Protocols](https://doi.org/10.1016/j.engappai.2026.113785) | Engineering applications of artificial intelligence | Vision | — | 11 |
| Jiali Cheng, Hadi Amiri | [Tool Unlearning for Tool-Augmented LLMs](https://doi.org/10.48550/arXiv.2502.01083) | ICML | LLM | — | 11 |
| Vaidehi Patil et al. | [Unlearning Sensitive Information in Multimodal LLMs: Benchmark and Attack-Defense Evaluation](https://doi.org/10.48550/arXiv.2505.01456) | TMLR | LLM | [GitHub](https://github.com/Vaidehi99/UnLOK-VQA) | 11 |
| Yiwei Chen et al. | [Safety Mirage: How Spurious Correlations Undermine VLM Safety Fine-tuning](https://doi.org/10.48550/arXiv.2503.11832) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 11 |
| K. Lu et al. | [When Are Concepts Erased From Diffusion Models?](https://doi.org/10.48550/arXiv.2505.17013) | arXiv | Diffusion | [GitHub](https://github.com/kevinlu4588/WhenAreConceptsErased) | 11 |
| Shristi Das Biswas, Arani Roy, Kaushik Roy | [CURE: Concept Unlearning via Orthogonal Representation Editing in Diffusion Models](https://doi.org/10.48550/arXiv.2505.12677) | arXiv | Diffusion | [GitHub](https://github.com/ShristiDasBiswas/CURE-Concept-Unlearning-via-Orthogonal-Representation-Editing-in-Diffusion-Models) | 11 |
| Sangamesh Kodge et al. | [SAP: Corrective Machine Unlearning with Scaled Activation Projection for Label Noise Robustness](https://doi.org/10.1609/aaai.v39i17.33972) | AAAI | Vision | [GitHub](https://github.com/sangamesh-kodge/LabelNoiseRobustness) | 10 |
| Zexi Li et al. | [Editing as Unlearning: Are Knowledge Editing Methods Strong Baselines for Large Language Model Unlearning?](https://doi.org/10.48550/arXiv.2505.19855) | AAAI | LLM | — | 10 |
| Haomin Zhuang et al. | [SEUF: Is Unlearning One Expert Enough for Mixture-of-Experts LLMs?](https://doi.org/10.18653/v1/2025.acl-long.424) | ACL | LLM | [GitHub](https://github.com/byungsoo-oh/ml-systems-papers) | 10 |
| Jaydeep Borkar et al. | [Privacy Ripple Effects from Adding or Removing Personal Information in Language Model Training](https://doi.org/10.48550/arXiv.2502.15680) | ACL | LLM | [GitHub](https://github.com/jaydeepborkar/Assisted-Memorization) | 10 |
| Anubhav Jain et al. | [Classifier-Free Guidance inside the Attraction Basin May Cause Memorization](https://doi.org/10.1109/cvpr52734.2025.01201) | CVPR | Diffusion | [GitHub](https://github.com/sony/creativeai) | 10 |
| Zheling Meng et al. | [Concept Corrector: Erase concepts on the fly for text-to-image diffusion models](https://doi.org/10.48550/arXiv.2502.16368) | Chinese Conference on Pattern Recognition and Computer Vision | Diffusion | [GitHub](https://github.com/RichardSunnyMeng/ConceptCorrector) | 10 |
| Taiming Lu, Philipp Koehn | [Learn and Unlearn: Addressing Misinformation in Multilingual LLMs](https://doi.org/10.18653/v1/2025.emnlp-main.516) | EMNLP | LLM | [GitHub](https://github.com/TaiMingLu/learn-unlearn) | 10 |
| Feiran Li et al. | [One Image is Worth a Thousand Words: A Usability Preservable Text-Image Collaborative Erasing Framework](https://doi.org/10.48550/arXiv.2505.11131) | ICML | Diffusion | [GitHub](https://github.com/ferry-li/co-erasing) | 10 |
| Ouyang Yang et al. | [Layer-Level Self-Exposure and Patch: Affirmative Token Mitigation for Jailbreak Attack Defense](https://doi.org/10.48550/arXiv.2501.02629) | NAACL | LLM | [GitHub](https://github.com/oyy2000/layeradvpatcher) | 10 |
| Boheng Li et al. | [Towards Resilient Safety-driven Unlearning for Diffusion Models against Downstream Fine-tuning](https://doi.org/10.48550/arXiv.2507.16302) | arXiv | Diffusion | [GitHub](https://github.com/AntigoneRandy/ResAlign) | 10 |
| Debdeep Sanyal, Murari Mandal | [Agents Are All You Need for LLM Unlearning](https://arxiv.org/abs/2502.00406) | COLM | LLM | [GitHub](https://github.com/respailab/agentic-llm-unlearning) | 9 |
| Feifei Li et al. | [Detect-and-Guide: Self-regulation of Diffusion Models for Safe Text-to-Image Generation via Guideline Token Optimization](https://doi.org/10.1109/CVPR52734.2025.01237) | CVPR | Diffusion | [GitHub](https://github.com/vpulab/ovam) | 9 |
| Yoav Gur-Arieh et al. | [Precise In-Parameter Concept Erasure in Large Language Models](https://doi.org/10.48550/arXiv.2505.22586) | EMNLP | LLM | [GitHub](https://github.com/yoavgur/PISCES) | 9 |
| Ibtihel Amara et al. | [Erasing More Than Intended? How Concept Erasure Degrades the Generation of Non-Target Concepts](https://doi.org/10.1109/iccv51701.2025.01524) | ICCV | Diffusion | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 9 |
| Gen Li et al. | [Sculpting Memory: Multi-Concept Forgetting in Diffusion Models via Dynamic Mask and Concept-Aware Optimization](https://doi.org/10.1109/ICCV51701.2025.01828) | ICCV | Diffusion | [GitHub](https://github.com/coulsonlee/Sculpting-Memory-ICCV-2025) | 9 |
| Yang Zhang et al. | [Minimalist Concept Erasure in Generative Models](https://doi.org/10.48550/arXiv.2507.13386) | ICML | Diffusion | [GitHub](https://github.com/YaNgZhAnG-V5/minimalist_concept_erasure) | 9 |
| Fan Li et al. | [TCGU: Data-Centric Graph Unlearning Based on Transferable Condensation](https://doi.org/10.1109/tkde.2025.3638465) | IEEE TKDE | Graph | [GitHub](https://github.com/Frostland12138/Awesome-Graph-Scaling) | 9 |
| Dayong Ye et al. | [Data Duplication: A Novel Multi-Purpose Attack Paradigm in Machine Unlearning](https://doi.org/10.48550/arXiv.2501.16663) | USENIX Security | Other | [GitHub](https://github.com/openai/gym) | 9 |
| Weiqi Wang et al. | [TAPE: Tailored Posterior Difference for Auditing of Machine Unlearning](https://doi.org/10.1145/3696410.3714875) | WWW | Other | [GitHub](https://github.com/wwq5-code/TAPE) | 9 |
| Kemou Li et al. | [LLM Unlearning with LLM Beliefs](https://doi.org/10.48550/arXiv.2510.19422) | arXiv | LLM | — | 9 |
| Bruce Lee et al. | [Distillation Robustifies Unlearning](https://doi.org/10.48550/arXiv.2506.06278) | arXiv | LLM | [GitHub](https://github.com/AddieFoote/distillation-robustify-unlearning) | 9 |
| Zhijie Deng et al. | [GUARD: Generation-time LLM Unlearning via Adaptive Restriction and Detection](https://doi.org/10.48550/arXiv.2505.13312) | arXiv | LLM | [HF](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) | 9 |
| K. Thakral et al. | [Continual Unlearning for Foundational Text-to-Image Models without Generalization Erosion](https://doi.org/10.48550/arXiv.2503.13769) | arXiv | Diffusion | [GitHub](https://github.com/GaParmar/clean-fid) | 9 |
| Yifan Li et al. | [Analyzing and Mitigating Object Hallucination: A Training Bias Perspective](https://doi.org/10.48550/arXiv.2508.04567) | AAAI | LLM | [GitHub](https://github.com/AoiDragon/POPEv2) | 8 |
| Zesheng Shi, Yucheng Zhou, Jing Li | [Safety Alignment via Constrained Knowledge Unlearning](https://doi.org/10.48550/arXiv.2505.18588) | ACL | LLM | [GitHub](https://github.com/ZeroNLP/Eraser) | 8 |
| Hadi Reisizadeh et al. | [BLUR: A Bi-Level Optimization Approach for LLM Unlearning](https://doi.org/10.48550/arXiv.2506.08164) | ACL | LLM | [GitHub](https://github.com/OptimAI-Lab/BLURLLMUnlearning) | 8 |
| Chen Chen et al. | [Enhancing Privacy-Utility Trade-offs to Mitigate Memorization in Diffusion Models](https://doi.org/10.1109/cvpr52734.2025.00766) | CVPR | Diffusion | [GitHub](https://github.com/wellzline/Trustworthy_T2I_DMs) | 8 |
| Sangyeon Yoon, Wonje Jeung, Albert No | [R-TOFU: Unlearning in Large Reasoning Models](https://doi.org/10.48550/arXiv.2505.15214) | EMNLP | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 8 |
| Xu Wang et al. | [Model Unlearning via Sparse Autoencoder Subspace Guided Projections](https://doi.org/10.48550/arXiv.2505.24428) | EMNLP | LLM | [GitHub](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) | 8 |
| Ali Ebrahimpour Boroojeny, Hari Sundaram, Varun Chandrasekaran | [Not All Wrong is Bad: Using Adversarial Examples for Unlearning](https://www.semanticscholar.org/paper/62fd8dbf030a5317c98d45f807ced1ceba1d892d) | ICML | Vision | — | 8 |
| Jian Chen et al. | [FedMUA: Exploring the Vulnerabilities of Federated Learning to Malicious Unlearning Attacks](https://doi.org/10.1109/tifs.2025.3531141) | IEEE T-IFS | Federated | [GitHub](https://github.com/ity207/FedMUA) | 8 |
| Shengming Zhang et al. | [LLM-Eraser: Optimizing Large Language Model Unlearning through Selective Pruning](https://doi.org/10.1145/3690624.3709312) | KDD | LLM | [GitHub](https://github.com/mmichaelzhang/LLM-Eraser) | 8 |
| Yongce Li, Chung-En Sun, Tsui-Wei Weng | [Effective Skill Unlearning through Intervention and Abstention](https://doi.org/10.48550/arXiv.2503.21730) | NAACL | LLM | [GitHub](https://github.com/trustworthy-ml-lab/effective_skill_unlearning) | 8 |
| Dahyun Jung et al. | [CoME: An Unlearning-based Approach to Conflict-free Model Editing](https://doi.org/10.48550/arXiv.2502.15826) | NAACL | LLM | [GitHub](https://github.com/ekgus9/COME) | 8 |
| Cheng-Long Wang et al. | [Towards Lifecycle Unlearning Commitment Management: Measuring Sample-level Unlearning Completeness](https://doi.org/10.48550/arXiv.2506.06112) | USENIX Security | Other | [GitHub](https://github.com/Happy2Git/Unlearning_Inference_IAM) | 8 |
| Zengyan Li, Qingqing Ye, Haibo Hu | [FUNU: Boosting Machine Unlearning Efficiency by Filtering Unnecessary Unlearning](https://doi.org/10.1145/3696410.3714711) | WWW | Other | — | 8 |
| Jie Ren et al. | [SoK: Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2506.09227) | arXiv | LLM | [HF](https://huggingface.co/spaces/raayraay/LLM-Fact-Forgetter) | 8 |
| Jie Ren et al. | [Keeping an Eye on LLM Unlearning: The Hidden Risk and Remedy](https://doi.org/10.48550/arXiv.2506.00359) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-Simple) | 8 |
| Shoaib Ahmed Siddiqui et al. | [From Dormant to Deleted: Tamper-Resistant Unlearning Through Weight-Space Regularization](https://doi.org/10.48550/arXiv.2505.22310) | arXiv | Vision | [HF](https://huggingface.co/girishgupta/deep-ignorance-unfiltered_unlearned_wt_dist) | 8 |
| Xiaoyu Ye et al. | [T2VUnlearning: A Concept Erasing Method for Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2505.17550) | arXiv | Diffusion | [GitHub](https://github.com/VDIGPKU/T2VUnlearning) | 8 |
| Aravind Krishnan, Siva Reddy, Marius Mosbach | [Not All Data Are Unlearned Equally](https://doi.org/10.48550/arXiv.2504.05058) | arXiv | LLM | [GitHub](https://github.com/McGill-NLP/unequal-unlearning) | 8 |
| Iraklis Premptis et al. | [AILS-NTUA at SemEval-2025 Task 4: Parameter-Efficient Unlearning for Large Language Models using Data Chunking](https://doi.org/10.48550/arXiv.2503.02443) | arXiv | LLM | [GitHub](https://github.com/iraklis07/llm-unlearning) | 8 |
| Bowen Fan et al. | [OpenGU: A Comprehensive Benchmark for Graph Unlearning](https://doi.org/10.48550/arXiv.2501.02728) | arXiv | Graph | [GitHub](https://github.com/bwfan-bit/OpenGU) | 8 |
| Yi-Yang Xie, Ping Liu, Zheng Zhang | [Erasing Concepts, Steering Generations: A Comprehensive Survey of Concept Suppression](https://doi.org/10.48550/arXiv.2505.19398) | arXiv | Diffusion | [GitHub](https://github.com/GantMan/nsfw) | 8 |
| C. Kim, Yanjun Qi | [A Comprehensive Survey on Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2502.14896) | arXiv | Diffusion | [GitHub](https://github.com/lihuining/Awesome-Concepts-Erasing) | 8 |
| Hwan Chang, Hwanhee Lee | [Which Retain Set Matters for LLM Unlearning? A Case Study on Entity Unlearning](https://doi.org/10.48550/arXiv.2502.11441) | ACL | LLM | — | 7 |
| Zhiqi Wang et al. | [Membership Inference Attacks as Privacy Tools: Reliability, Disparity and Ensemble](https://doi.org/10.1145/3719027.3744818) | CCS | Other | [GitHub](https://github.com/RPI-DSPlab/MIAE) | 7 |
| XiaoYu Xu et al. | [OBLIVIATE: Robust and Practical Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2505.04416) | EMNLP | LLM | [GitHub](https://github.com/XiaoyuXU1/OBLIVIATE_unlearning_LLM) | 7 |
| Naen Xu et al. | [VideoEraser: Concept Erasure in Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2508.15314) | EMNLP | Diffusion | [GitHub](https://github.com/bluedream02/VideoEraser) | 7 |
| Yujia Tong et al. | [Robust Machine Unlearning for Quantized Neural Networks via Adaptive Gradient Reweighting with Similar Labels](https://doi.org/10.1109/ICCV51701.2025.01916) | ICCV | Vision | — | 7 |
| U. Basaran et al. | [A Certified Unlearning Approach without Access to Source Data](https://doi.org/10.48550/arXiv.2506.06486) | ICML | Other | [GitHub](https://github.com/info-ucr/certified-unlearning-surr-data) | 7 |
| Shuai Zhao et al. | [FedWiper: Federated Unlearning via Universal Adapter](https://doi.org/10.1109/tifs.2025.3557671) | IEEE T-IFS | Federated | [GitHub](https://github.com/grey1989/FedWiper) | 7 |
| Ayush K. Varshney, Vicenç Torra | [Efficient federated unlearning under plausible deniability](https://doi.org/10.1007/s10994-024-06685-x) | Machine Learning | Federated | [GitHub](https://github.com/Ayush-Umu/Federated-Unlearning-under-Plausible-Deniability) | 7 |
| Bichen Wang et al. | [Balancing Forget Quality and Model Utility: A Reverse KL-Divergence Knowledge Distillation Approach for Better Unlearning in LLMs](https://doi.org/10.18653/v1/2025.naacl-long.60) | NAACL | LLM | — | 7 |
| Haokun Chen et al. | [Does Machine Unlearning Truly Remove Knowledge?](https://arxiv.org/abs/2505.23270) | NeurIPS Lock-LLM Workshop Poster | LLM | — | 7 |
| Ayush K. Varshney, Konstantinos Vandikas, Vicenç Torra | [Unlearning Clients, Features and Samples in Vertical Federated Learning](https://doi.org/10.56553/popets-2025-0048) | PoPETs | Federated | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 7 |
| Alexey Kravets, Vinay P. Namboodiri | [Zero-shot CLIP Class Forgetting via Text-image Space Adaptation](https://www.semanticscholar.org/paper/594a08af403e3b54a55ef4ad9577d1add2ad7430) | TMLR | Vision | [GitHub](https://github.com/akres001/Zero-shot-CLIP-Forgetting-via-Text-image-Space-Adaptation) | 7 |
| Wenbin Wang et al. | [Poisoning Attacks and Defenses to Federated Unlearning](https://doi.org/10.1145/3701716.3715494) | WWW | Federated | — | 7 |
| Zhili Feng et al. | [Existing Large Language Model Unlearning Evaluations Are Inconclusive](https://doi.org/10.48550/arXiv.2506.00688) | arXiv | LLM | — | 7 |
| Shengyuan Hu et al. | [BLUR: A Benchmark for LLM Unlearning Robust to Forget-Retain Overlap](https://doi.org/10.48550/arXiv.2506.15699) | arXiv | LLM | [HF](https://huggingface.co/datasets/forgelab/BLUR) | 7 |
| Stefan Schoepf et al. | [Redirection for Erasing Memory (REM): Towards a universal unlearning method for corrupted data](https://doi.org/10.48550/arXiv.2505.17730) | arXiv | Vision | [GitHub](https://github.com/google-deepmind/rem) | 7 |
| Anil Ramakrishna et al. | [SemEval-2025 Task 4: Unlearning sensitive content from Large Language Models](https://doi.org/10.48550/arXiv.2504.02883) | arXiv | LLM | — | 7 |
| Yuhui Wang et al. | [Reasoning or Retrieval? A Study of Answer Attribution on Large Reasoning Models](https://doi.org/10.48550/arXiv.2509.24156) | arXiv | LLM | [GitHub](https://github.com/ZJUWYH/FARL) | 7 |
| Zhihua Tian et al. | [Sparse Autoencoder as a Zero-Shot Classifier for Concept Erasing in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2503.09446) | arXiv | Diffusion | [GitHub](https://github.com/nansirun/interpret-then-deactivate) | 7 |
| Jiahang Tu et al. | [CE-SDWV: Effective and Efficient Concept Erasure for Text-to-Image Diffusion Models via a Semantic-Driven Word Vocabulary](https://doi.org/10.48550/arXiv.2501.15562) | arXiv | Diffusion | [GitHub](https://github.com/TtuHamg/CE-SDWV) | 7 |
| Yongliang Wu et al. | [Unlearning Concepts in Diffusion Model via Concept Domain Correction and Concept Preserving Gradient](https://doi.org/10.1609/aaai.v39i8.32917) | AAAI | Diffusion | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 6 |
| Haoran Li et al. | [Simulate and Eliminate: Revoke Backdoors for Generative Large Language Models](https://doi.org/10.1609/aaai.v39i1.32018) | AAAI | LLM | [GitHub](https://github.com/HKUST-KnowComp/SANDE) | 6 |
| Ruipeng Wang et al. | [ACE: Concept Editing in Diffusion Models without Performance Degradation](https://doi.org/10.1145/3746027.3755749) | ACM MM | Diffusion | [GitHub](https://github.com/keven-cyber/ACE-zero) | 6 |
| Xiang Li, Wenqi Wei, B. Thuraisingham | [MUBox: A Critical Evaluation Framework of Deep Machine Unlearning [Systematization of Knowledge Paper]](https://doi.org/10.1145/3734436.3734454) | ACM Symposium on Access Control Models and Technologies | Other | [GitHub](https://github.com/Jessegator/MUBox) | 6 |
| Renyang Liu et al. | [Rethinking Machine Unlearning in Image Generation Models](https://doi.org/10.1145/3719027.3744793) | CCS | Diffusion | [GitHub](https://github.com/ryliu68/IGMU) | 6 |
| Ivanna Daniela Cevallos et al. | [A Systematic Literature Review of Machine Unlearning Techniques in Neural Networks](https://doi.org/10.3390/computers14040150) | Computers | Other | — | 6 |
| Wenyu Wang et al. | [UIPE: Enhancing LLM Unlearning by Removing Knowledge Related to Forgetting Targets](https://doi.org/10.48550/arXiv.2503.04693) | EMNLP | LLM | — | 6 |
| Guangzhi Sun et al. | [Unlearning vs. Obfuscation: Are We Truly Removing Knowledge?](https://doi.org/10.48550/arXiv.2505.02884) | EMNLP | LLM | [GitHub](https://github.com/potsawee/unlearning-dfmcq) | 6 |
| Nakyeong Yang et al. | [FaithUn: Toward Faithful Forgetting in Language Models by Investigating the Interconnectedness of Knowledge](https://doi.org/10.48550/arXiv.2502.19207) | EMNLP | LLM | [GitHub](https://github.com/centerforaisafety/wmdp) | 6 |
| Busra Buyuktanir, Kazim Yildiz, G. Baydogmus | [A Systematic Mapping Study on Machine Unlearning in Federated Learning](https://doi.org/10.1109/ICHORA65333.2025.11017102) | ICHORA | Federated | — | 6 |
| N. Sepahvand et al. | [Selective Unlearning via Representation Erasure Using Domain Adversarial Training](https://www.semanticscholar.org/paper/c7c555a04edc245750ef816346e8ed7dc89fa321) | ICLR | LLM | — | 6 |
| Vincent Siu et al. | [RepIt: Steering Language Models with Concept-Specific Refusal Vectors](https://arxiv.org/abs/2509.13281) | ICLR Poster | LLM | [GitHub](https://github.com/wang-research-lab/RepIt) | 6 |
| Gaurav R. Ghosal, Pratyush Maini, Aditi Raghunathan | [Memorization Sinks: Isolating Memorization during LLM Training](https://doi.org/10.48550/arXiv.2507.09937) | ICML | LLM | [GitHub](http://github.com/grghosal/MemSinks) | 6 |
| Jianxin Zhang et al. | [Model Recovery in Federated Unlearning With Restricted Server Data Resources](https://doi.org/10.1109/jiot.2025.3540463) | IEEE IoT-J | Federated | — | 6 |
| Shahad Hardan et al. | [Forget-MI: Machine Unlearning for Forgetting Multimodal Information in Healthcare Settings](https://doi.org/10.48550/arXiv.2506.23145) | MICCAI | Other | [GitHub](https://github.com/BioMedIA-MBZUAI/Forget-MI) | 6 |
| Nima Naderloui et al. | [Rectifying Privacy and Efficacy Measurements in Machine Unlearning: A New Inference Attack Perspective](https://doi.org/10.48550/arXiv.2506.13009) | USENIX Security | Other | [GitHub](https://github.com/datasec-lab/Ruli) | 6 |
| Fan Liu, Hao Liu | [Subgraph Federated Unlearning](https://doi.org/10.1145/3696410.3714821) | WWW | Federated | [GitHub](https://github.com/usail-hkust/FedUnlearnSFU) | 6 |
| Lulu Xue et al. | [Towards Reliable Forgetting: A Survey on Machine Unlearning Verification](https://arxiv.org/abs/2506.15115) | arXiv | Other | — | 6 |
| Vinith M. Suriyakumar, Ayush Sekhari, Ashia Wilson | [UCD: Unlearning in LLMs via Contrastive Decoding](https://doi.org/10.48550/arXiv.2506.12097) | arXiv | LLM | — | 6 |
| Vaidehi Patil, Elias Stengel-Eskin, Mohit Bansal | [UPCORE: Utility-Preserving Coreset Selection for Balanced Unlearning](https://doi.org/10.48550/arXiv.2502.15082) | arXiv | LLM | [GitHub](https://github.com/vaidehi99/upcore) | 6 |
| Bill Marino, Meghdad Kurmanji, N. Lane | [Bridge the Gaps between Machine Unlearning and AI Regulation](https://doi.org/10.48550/arXiv.2502.12430) | arXiv | Other | — | 6 |
| Chenlong Zhang et al. | [RULE: Reinforcement UnLEarning Achieves Forget-Retain Pareto Optimality](https://doi.org/10.48550/arXiv.2506.07171) | arXiv | LLM | [GitHub](https://github.com/chenlong-clock/RULE-Unlearn) | 6 |
| Huiqiang Chen et al. | [Safe and Reliable Diffusion Models via Subspace Projection](https://doi.org/10.48550/arXiv.2503.16835) | arXiv | Diffusion | — | 6 |
| Alexander Xiong et al. | [The Landscape of Memorization in LLMs: Mechanisms, Measurement, and Mitigation](https://doi.org/10.48550/arXiv.2507.05578) | arXiv | LLM | — | 6 |
| Zibin Pan et al. | [Federated Unlearning with Gradient Descent and Conflict Mitigation](https://doi.org/10.1609/aaai.v39i19.34181) | AAAI | Federated | [GitHub](https://github.com/zibinpan/FedOSD) | 5 |
| Yash Sinha, Murari Mandal, Mohan Kankanhalli | [Multi-Modal Recommendation Unlearning for Legal, Licensing, and Modality Constraints](https://doi.org/10.1609/aaai.v39i12.33367) | AAAI | Recsys | [GitHub](https://github.com/MachineUnlearn/MMRecUN) | 5 |
| Yezi Liu, Yanning Shen | [Enabling Group Fairness in Machine Unlearning via Distribution Correction](https://doi.org/10.1145/3746252.3761299) | CIKM | Other | — | 5 |
| Shaswati Saha et al. | [Side Effects of Erasing Concepts from Diffusion Models](https://doi.org/10.48550/arXiv.2508.15124) | EMNLP | Diffusion | [GitHub](https://github.com/shaswati1/see) | 5 |
| Bang Trinh Tran To, Thai Le | [Harry Potter is Still Here! Probing Knowledge Leakage in Targeted Unlearned Large Language Models via Automated Adversarial Prompting](https://doi.org/10.48550/arXiv.2505.17160) | EMNLP | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 5 |
| Rui Shao et al. | [Law LLM unlearning via interfere prompt, review output and update parameter: new challenges, method and baseline](https://doi.org/10.1016/j.eswa.2025.128612) | Expert Systems with Applications | LLM | — | 5 |
| Martin Van Waerebeke et al. | [When to Forget? Complexity Trade-offs in Machine Unlearning](https://doi.org/10.48550/arXiv.2502.17323) | ICML | Other | — | 5 |
| An Huang, Zhipeng Cai, Zuobin Xiong | [A Survey of Machine Unlearning in Generative AI Models: Methods, Applications, Security, and Challenges](https://doi.org/10.1109/jiot.2025.3570989) | IEEE IoT-J | Other | — | 5 |
| Weiqi Wang et al. | [CRFU: Compressive Representation Forgetting Against Privacy Leakage on Machine Unlearning](https://doi.org/10.1109/tdsc.2025.3542092) | IEEE TDSC | Vision | [GitHub](https://github.com/wwq5-code/CRFU) | 5 |
| Changjun Zhou et al. | [Federated Unlearning With Fast Recovery](https://doi.org/10.1109/tmc.2025.3563265) | IEEE TMC | Federated | — | 5 |
| Muhammad Ameen et al. | [Speed up Federated Unlearning With Temporary Local Models](https://doi.org/10.1109/tsusc.2025.3549112) | IEEE Transactions on Sustainable Computing | Federated | — | 5 |
| Kongyang Chen et al. | [Fast yet versatile machine unlearning for deep neural networks](https://doi.org/10.1016/j.neunet.2025.107648) | Neural Networks | Other | — | 5 |
| Tamim Al Mahmud et al. | [DP2Unlearning: An efficient and guaranteed unlearning framework for LLMs](https://doi.org/10.1016/j.neunet.2025.107879) | Neural Networks | LLM | [GitHub](https://github.com/tamimalmahmud/LLM-Unlearning/tree) | 5 |
| Muhammed Shafi K. P. et al. | [How Secure is Forgetting? Linking Machine Unlearning to Machine Learning Attacks](https://doi.org/10.48550/arXiv.2503.20257) | Neurocomputing | Other | — | 5 |
| Dang Huu-Tien et al. | [Improving LLM Unlearning Robustness via Random Perturbations](https://arxiv.org/abs/2501.19202) | TMLR | LLM | [GitHub](https://github.com/RebelsNLU-jaist/llmu-robustness) | 5 |
| Xiaohua Feng et al. | [Plug and Play: Enabling Pluggable Attribute Unlearning in Recommender Systems](https://doi.org/10.1145/3696410.3714671) | WWW | Recsys | [GitHub](https://github.com/Anya-bond/Awesome-Privacy-RecSys) | 5 |
| Zhaoyang Chu et al. | [Scrub It Out! Erasing Sensitive Memorization in Code Language Models via Machine Unlearning](https://doi.org/10.1145/3744916.3764573) | arXiv | LLM | [GitHub](https://github.com/Zhaoyang-Chu/code-unlearning) | 5 |
| Yang Xiao et al. | [The Right to be Forgotten in Pruning: Unveil Machine Unlearning on Sparse Models](https://doi.org/10.48550/arXiv.2507.18725) | arXiv | Other | [GitHub](https://github.com/NKUShaw/SparseModels) | 5 |
| Zhehao Huang et al. | [A Unified Gradient-based Framework for Task-agnostic Continual Learning-Unlearning](https://doi.org/10.48550/arXiv.2505.15178) | arXiv | Other | — | 5 |
| Yezi Liu et al. | [Enabling Group Fairness in Graph Unlearning via Bi-level Debiasing](https://doi.org/10.48550/arXiv.2505.09702) | arXiv | Graph | [GitHub](https://github.com/brandeis-machine-learning/FairAdj) | 5 |
| Haolin Zou et al. | [Certified Data Removal Under High-dimensional Settings](https://doi.org/10.48550/arXiv.2505.07640) | arXiv | Other | — | 5 |
| Tianyang Xu et al. | [SUV: Scalable Large Language Model Copyright Compliance with Regularized Selective Unlearning](https://doi.org/10.48550/arXiv.2503.22948) | arXiv | LLM | [GitHub](https://github.com/xz-liu/SUV) | 5 |
| Estrid He et al. | [Deep Contrastive Unlearning for Language Models](https://doi.org/10.48550/arXiv.2503.14900) | arXiv | LLM | — | 5 |
| Matthew Khoriaty et al. | [Don't Forget It! Conditional Sparse Autoencoder Clamping Works for Unlearning](https://doi.org/10.48550/arXiv.2503.11127) | arXiv | LLM | [GitHub](https://github.com/AMindToThink/sae_jailbreak_unlearning) | 5 |
| Linian Wang, Leye Wang | [Forgetting Any Data at Any Time: A Theoretically Certified Unlearning Framework for Vertical Federated Learning](https://doi.org/10.48550/arXiv.2502.17081) | arXiv | Federated | [GitHub](https://github.com/wangln19/vertical-federated-unlearning) | 5 |
| Tomer Ashuach et al. | [CRISP: Persistent Concept Unlearning via Sparse Autoencoders](https://doi.org/10.48550/arXiv.2508.13650) | arXiv | LLM | [GitHub](https://github.com/tomerashuach/CRISP) | 5 |
| N. Singh et al. | [Unlearning That Lasts: Utility-Preserving, Robust, and Almost Irreversible Forgetting in LLMs](https://doi.org/10.48550/arXiv.2509.02820) | arXiv | LLM | [GitHub](https://github.com/nmndeep/JensUn-Unlearning) | 5 |
| Ziqian Zhong, Aditi Raghunathan | [Watch the Weights: Unsupervised monitoring and control of fine-tuned LLMs](https://doi.org/10.48550/arXiv.2508.00161) | arXiv | LLM | [GitHub](https://github.com/fjzzq2002/WeightWatch) | 5 |
| Zhaopan Xu et al. | [PEBench: A Fictitious Dataset to Benchmark Machine Unlearning for Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2503.12545) | arXiv | LLM | [HF](https://huggingface.co/datasets/xuzhaopan/PEBench) | 5 |
| Yixin Wan et al. | [Not Every Token Needs Forgetting: Selective Unlearning to Limit Change in Utility in Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2506.00876) | arXiv | LLM | — | 5 |
| Tong Chen et al. | [ParaPO: Aligning Language Models to Reduce Verbatim Reproduction of Pre-training Data](https://doi.org/10.48550/arXiv.2504.14452) | arXiv | LLM | [GitHub](https://github.com/chentong0/ParaPO) | 5 |
| J. H. Grebe et al. | [Erased but Not Forgotten: How Backdoors Compromise Concept Erasure](https://doi.org/10.48550/arXiv.2504.21072) | arXiv | Diffusion | [GitHub](https://github.com/jonasgrebe/erased-but-not-forgotten) | 5 |
| Skyler Hallinan et al. | [The Surprising Effectiveness of Membership Inference with Simple N-Gram Coverage](https://doi.org/10.48550/arXiv.2508.09603) | arXiv | LLM | [GitHub](https://github.com/shallinan1/NGramCoverageAttack) | 5 |
| Jiali Wang et al. | [Scrub-and-Learn: Category-Aware Weight Modification for Machine Unlearning](https://doi.org/10.3390/ai6060108) | AI | Vision | — | 4 |
| Uyen N. Le-Khac, Vinh Truong | [A survey on large language models unlearning: taxonomy, evaluations, and future directions](https://doi.org/10.1007/s10462-025-11376-7) | Artificial Intelligence Review | LLM | — | 4 |
| Sk Miraj et al. | [Towards Source-Free Machine Unlearning](https://doi.org/10.1109/CVPR52734.2025.00466) | CVPR | Vision | [GitHub](https://github.com/info-ucr/source-free-unlearning) | 4 |
| Zeliang Zhang et al. | [Targeted Forgetting of Image Subgroups in CLIP Models](https://doi.org/10.1109/CVPR52734.2025.00922) | CVPR | Vision | — | 4 |
| Tae-Young Lee et al. | [ESC: Erasing Space Concept for Knowledge Deletion](https://doi.org/10.1109/CVPR52734.2025.00472) | CVPR | Vision | [GitHub](https://github.com/KU-VGI/ESC) | 4 |
| Hwiyeong Lee et al. | [Does Localization Inform Unlearning? A Rigorous Examination of Local Parameter Attribution for Knowledge Unlearning in Language Models](https://doi.org/10.48550/arXiv.2505.16252) | EMNLP | LLM | — | 4 |
| Aly M. Kassem et al. | [Reviving Your MNEME: Predicting The Side Effects of LLM Unlearning and Fine-Tuning via Sparse Model Diffing](https://doi.org/10.48550/arXiv.2507.21084) | EMNLP | LLM | — | 4 |
| Xiaoyu Luo et al. | [Shared Path: Unraveling Memorization in Multilingual LLMs through Language Similarities](https://doi.org/10.18653/v1/2025.emnlp-main.978) | EMNLP | LLM | — | 4 |
| Khaoula ElBedoui, Walid Barhoumi, Jungwon Cho | [<scp>SoK</scp> : Federated Learning and Unlearning for Medical Image Analysis](https://doi.org/10.1111/exsy.70063) | Expert Systems | Federated | — | 4 |
| Qian Feng et al. | [FG-OrIU: Towards Better Forgetting via Feature-Gradient Orthogonality for Incremental Unlearning](https://doi.org/10.1109/ICCV51701.2025.00190) | ICCV | Vision | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 4 |
| Jiahui Geng, Qing Li | [SAUCE: Selective Concept Unlearning in Vision-Language Models with Sparse Autoencoders](https://doi.org/10.1109/ICCV51701.2025.00290) | ICCV | Vision | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Kristian Georgiev et al. | [Machine Unlearning via Simulated Oracle Matching](https://www.semanticscholar.org/paper/8cbc39de7bd9689615288c91b3cb8f162867da8a) | ICLR | Other | — | 4 |
| Dahuin Jung | [EntUn: Mitigating the forget-retain dilemma in unlearning via entropy](https://doi.org/10.1016/j.icte.2025.06.007) | ICT express | Vision | — | 4 |
| Weiqi Wang et al. | [Evaluation of Machine Unlearning Through Model Difference](https://doi.org/10.1109/tifs.2025.3571666) | IEEE T-IFS | Other | — | 4 |
| Yang Wang, Xue Li, Siguang Chen | [Malicious Clients and Contribution Co-Aware Federated Unlearning](https://doi.org/10.1109/tai.2025.3556092) | IEEE TAI | Federated | — | 4 |
| Na Li et al. | [Machine Unlearning: Taxonomy, Metrics, Applications, Challenges, and Prospects](https://doi.org/10.1109/tnnls.2025.3530988) | IEEE TNNLS | Other | [GitHub](https://github.com/Carol-gutianle/Awesome-llm-unlearning) | 4 |
| Jiali Cheng, Hadi Amiri | [Speech Unlearning](https://doi.org/10.48550/arXiv.2506.00848) | INTERSPEECH | Other | — | 4 |
| Alkis Koudounas et al. | ["Alexa, can you forget me?" Machine Unlearning Benchmark in Spoken Language Understanding](https://doi.org/10.21437/Interspeech.2025-2607) | INTERSPEECH | Other | — | 4 |
| Kun Wu, Hui Wang | [Verification of Incomplete Graph Unlearning through Adversarial Perturbations](https://doi.org/10.1145/3711896.3737179) | KDD | Graph | [GitHub](https://github.com/kunwu522/unlearning-verification-gnn) | 4 |
| Wei Wang et al. | [Label Inference Attacks against Federated Unlearning](https://doi.org/10.48550/arXiv.2508.06789) | Knowledge Science, Engineering and Management | Federated | — | 4 |
| Huanqian Wang et al. | [Model Surgery: Modulating LLM’s Behavior Via Simple Parameter Editing](https://doi.org/10.18653/v1/2025.naacl-long.321) | NAACL (Long Papers) | LLM | — | 4 |
| Yu-Qin Chen, Shi-Xin Zhang | [Superior resilience to poisoning and amenability to unlearning in quantum machine learning](https://doi.org/10.1038/s41467-026-70420-4) | Nature Communications | Other | — | 4 |
| Jiajie He, Yuechun Gu, Keke Chen | [RecPS: Privacy Risk Scoring for Recommender Systems](https://doi.org/10.1145/3705328.3748052) | RecSys | Recsys | [GitHub](https://github.com/KJaebye/EmbodiedAI-Robotics-arXiv-Daily-Reporter) | 4 |
| Yiling Tao et al. | [Unlearning for Federated Online Learning to Rank: A Reproducibility Study](https://doi.org/10.1145/3726302.3730336) | SIGIR | Federated | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 4 |
| Raman Dutt et al. | [MemControl: Mitigating Memorization in Diffusion Models via Automated Parameter Selection](https://doi.org/10.1109/wacv61041.2025.00441) | WACV | Diffusion | [GitHub](https://github.com/Raman1121/Diffusion_Memorization_HPO) | 4 |
| Wenhan Wu, Jiawei Jiang, Chuang Hu | [Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks](https://doi.org/10.1145/3696410.3714823) | WWW | Recsys | — | 4 |
| Wang, Yaxuan et al. | [DRAGON: Guard LLM Unlearning in Context via Negative Detection and Reasoning](https://doi.org/10.48550/arXiv.2511.05784) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Liu, Yezi et al. | [LUNE: Efficient LLM Unlearning via LoRA Fine-Tuning with Negative Examples](https://doi.org/10.48550/arXiv.2512.07375) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Shariqah Hossain, Lalana Kagal | [Investigating Model Editing for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2512.20794) | arXiv | LLM | [GitHub](https://github.com/bostonadam525/Training-LLMs---From-Scratch-to-Fine-Tuning) | 4 |
| Qingjie Zhang et al. | [Understanding the Dilemma of Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2509.24675) | arXiv | LLM | — | 4 |
| Yan Scholten et al. | [Model Collapse Is Not a Bug but a Feature in Machine Unlearning for LLMs](https://doi.org/10.48550/arXiv.2507.04219) | arXiv | LLM | [GitHub](https://github.com/partial-model-collapse-unlearning/pmc-unlearning) | 4 |
| Hao Xuan, Xingyu Li | [Verifying Robust Unlearning: Probing Residual Knowledge in Unlearned Models](https://doi.org/10.48550/arXiv.2504.14798) | arXiv | Other | — | 4 |
| Jiali Cheng, Hadi Amiri | [Understanding Machine Unlearning Through the Lens of Mode Connectivity](https://doi.org/10.48550/arXiv.2504.06407) | arXiv | Other | — | 4 |
| M. Russinovich, Ahmed Salem | [Obliviate: Efficient Unmemorization for Protecting Intellectual Property in Large Language Models](https://doi.org/10.48550/arXiv.2502.15010) | arXiv | LLM | [GitHub](https://github.com/microsoft/Obliviate-Unmemorization) | 4 |
| Aviv Shamsian et al. | [Go Beyond Your Means: Unlearning with Per-Sample Gradient Orthogonalization](https://doi.org/10.48550/arXiv.2503.02312) | arXiv | Other | — | 4 |
| Xunkai Li et al. | [Toward Scalable Graph Unlearning: A Node Influence Maximization based Approach](https://doi.org/10.48550/arXiv.2501.11823) | arXiv | Graph | — | 4 |
| G. Alon, Yehuda Dar | [How Does Overparameterization Affect Machine Unlearning of Deep Neural Networks?](https://doi.org/10.48550/arXiv.2503.08633) | arXiv | Other | — | 4 |
| Yash Sinha et al. | [Step-by-Step Reasoning Attack: Revealing 'Erased' Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2506.17279) | arXiv | LLM | — | 4 |
| Yejin Kim et al. | [Improving Fisher Information Estimation and Efficiency for LoRA-based LLM Unlearning](https://doi.org/10.48550/arXiv.2508.21300) | arXiv | LLM | [GitHub](https://github.com/kyj93790/VILA) | 4 |
| Igor Shilov et al. | [Beyond Data Filtering: Knowledge Localization for Capability Removal in LLMs](https://doi.org/10.48550/arXiv.2512.05648) | arXiv | LLM | [GitHub](https://github.com/safety-research/selective-gradient-masking) | 4 |
| Renyang Liu et al. | [Image Can Bring Your Memory Back: A Novel Multi-Modal Guided Attack against Image Generation Model Unlearning](https://doi.org/10.48550/arXiv.2507.07139) | arXiv | Diffusion | [GitHub](https://github.com/ryliu68/RECALL) | 4 |
| Woosung Choi et al. | [Large-Scale Training Data Attribution for Music Generative Models via Unlearning](https://doi.org/10.48550/arXiv.2506.18312) | arXiv | Diffusion | [GitHub](https://github.com/Stability-AI/stable-audio-tools) | 4 |
| Ping Liu, Chi Zhang | [Erased or Dormant? Rethinking Concept Erasure Through Reversibility](https://doi.org/10.48550/arXiv.2505.16174) | arXiv | Diffusion | [HF](https://huggingface.co/Lykon/DreamShaper) | 4 |
| Nicky Kriplani et al. | [SolidMark: Evaluating Image Memorization in Generative Models](https://doi.org/10.48550/arXiv.2503.00592) | arXiv | Diffusion | [GitHub](https://github.com/NickyDCFP/SolidMark) | 4 |
| Subhodip Panda, Shashwat Sourav, Prathosh AP | [Partially Blinded Unlearning: Class Unlearning for Deep Networks from Bayesian Perspective](https://doi.org/10.1609/aaai.v39i6.32682) | AAAI | Vision | — | 3 |
| Qiming Guo et al. | [Efficient Unlearning for Spatio-temporal Graph (Student Abstract)](https://doi.org/10.1609/aaai.v39i28.35259) | AAAI | Graph | [GitHub](https://github.com/wenlu-lab/STEPS) | 3 |
| Wei Qian et al. | [Towards Benchmarking Privacy Vulnerabilities in Selective Forgetting with Large Language Models](https://doi.org/10.48550/arXiv.2512.18035) | AAAI | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 3 |
| Lulu Xue et al. | [Dual-View Inference Attack: Machine Unlearning Amplifies Privacy Exposure](https://doi.org/10.48550/arXiv.2512.16126) | AAAI | Other | — | 3 |
| Michael-Andrei Panaitescu-Liess et al. | [Can Watermarking Large Language Models Prevent Copyrighted Text Generation and Hide Training Data?](https://doi.org/10.1609/aaai.v39i23.34684) | AAAI | LLM | — | 3 |
| Yicheng Lang et al. | [Beyond Single-Value Metrics: Evaluating and Enhancing LLM Unlearning with Cognitive Diagnosis](https://doi.org/10.48550/arXiv.2502.13996) | ACL | LLM | [GitHub](https://github.com/lyicheng619/UNCD) | 3 |
| Xuran Li et al. | [PRUNE: A Patching Based Repair Framework for Certifiable Unlearning of Neural Networks](https://doi.org/10.1109/CAC67268.2025.11486844) | ACM Cloud and Autonomic Computing Conference | Other | — | 3 |
| Ci Zhang et al. | [Towards Memory-Efficient and Sustainable Machine Unlearning on Edge using Zeroth-Order Optimizer](https://doi.org/10.1145/3716368.3735273) | ACM Great Lakes Symposium on VLSI | Other | — | 3 |
| Qiang Chen et al. | [Graph Unlearning Meets Influence-aware Negative Preference Optimization](https://doi.org/10.1145/3746027.3754941) | ACM MM | Graph | [GitHub](https://github.com/sh-qiangchen/INPO) | 3 |
| Huanyi Ye et al. | [Enhancing AI safety of machine unlearning for ensembled models](https://doi.org/10.1016/j.asoc.2025.113011) | Applied Soft Computing | Other | — | 3 |
| Wei Qian et al. | [Towards Unveiling Predictive Uncertainty Vulnerabilities in the Context of the Right to Be Forgotten](https://doi.org/10.1145/3746252.3760964) | CIKM | Other | — | 3 |
| Yang Yang et al. | [FedCSA: Enhancing Federated Unlearning Efficiency Through Adaptive Clustering Under Data Heterogeneity](https://doi.org/10.23919/cje.2024.00.050) | Chinese Journal of Electronics | Federated | — | 3 |
| Alberto Blanco-Justicia et al. | [Unlearning in Large Language Models: We Are Not There Yet](https://doi.org/10.1109/mc.2024.3468588) | Computer | LLM | — | 3 |
| Igor Kabashkin | [Federated Unlearning Framework for Digital Twin–Based Aviation Health Monitoring Under Sensor Drift and Data Corruption](https://doi.org/10.3390/electronics14152968) | Electronics | Federated | — | 3 |
| Sai Siddhartha Chary Aylapuram, V. Elluru, Shivang Agarwal | [Bias-Aware Machine Unlearning: Towards Fairer Vision Models via Controllable Forgetting](https://doi.org/10.1109/ICCVW69036.2025.00270) | ICCV | Vision | — | 3 |
| Kien Nguyen, Anh Tran, Cuong Pham | [SuMa: A Subspace Mapping Approach for Robust and Effective Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICCV51701.2025.01821) | ICCV | Diffusion | — | 3 |
| Miao Yu et al. | [UniErase: Towards Balanced and Precise Unlearning in Language Models](https://arxiv.org/abs/2505.15674) | ICLR Conference Withdrawn Submission | LLM | [GitHub](https://github.com/Ymm-cll/UniErase) | 3 |
| N. Sepahvand et al. | [Leveraging Per-Instance Privacy for Machine Unlearning](https://doi.org/10.48550/arXiv.2505.18786) | ICML | Other | — | 3 |
| Taesoo Kim et al. | [Do Not Mimic My Voice: Speaker Identity Unlearning for Zero-Shot Text-to-Speech](https://doi.org/10.48550/arXiv.2507.20140) | ICML | Other | [GitHub](https://github.com/mokcho/mokcho) | 3 |
| Nay Myat Min, Long Pham, Jun Sun | [Unified Neural Backdoor Removal With Only Few Clean Samples Through Unlearning and Relearning](https://doi.org/10.1109/tifs.2025.3586499) | IEEE T-IFS | Vision | [GitHub](https://github.com/NayMyatMin/ULRL) | 3 |
| Wenhan Wu et al. | [Mimir: Data-Free Federated Unlearning Through Client-Specific Prompt Generation for Personalized Models](https://doi.org/10.1109/tmc.2025.3570018) | IEEE TMC | Federated | — | 3 |
| Hongbo Zhao et al. | [Practical Continual Forgetting for Pre-Trained Vision Models](https://doi.org/10.1109/TPAMI.2026.3654115) | IEEE TPAMI | Vision | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 3 |
| Jaeung Lee et al. | [Unlearning Comparator: A Visual Analytics System for Comparative Evaluation of Machine Unlearning Methods](https://doi.org/10.1109/TVCG.2026.3658325) | IEEE TVCG | Other | [GitHub](https://github.com/gnueaj/Machine-Unlearning-Comparator) | 3 |
| Kunho Kim et al. | [GRAIL: Gradient-Based Adaptive Unlearning for Privacy and Copyright in LLMs](https://doi.org/10.1109/IJCNN64981.2025.11229073) | IJCNN | LLM | [GitHub](https://github.com/piso7/piso7) | 3 |
| Jiali Wang et al. | [Weight masking in image classification networks: class-specific machine unlearning](https://doi.org/10.1007/s10115-024-02312-2) | Knowledge and Information Systems | Vision | — | 3 |
| Aly M. Kassem et al. | [ALPACA AGAINST VICUNA: Using LLMs to Uncover Memorization of LLMs](https://doi.org/10.18653/v1/2025.naacl-long.421) | NAACL | LLM | [GitHub](https://github.com/Alymostafa/Instruction_based_attack) | 3 |
| Yutong Wu et al. | [THEMIS: Regulating Textual Inversion for Personalized Concept Censorship](https://doi.org/10.14722/ndss.2025.230450) | NDSS | Diffusion | [GitHub](https://github.com/WU-YU-TONG/Themis) | 3 |
| Zhaobo Lu et al. | [FeaUn: Feature unlearning in vertical federated learning for IIoT against feature inference attacks](https://doi.org/10.1016/j.neucom.2025.131110) | Neurocomputing | Federated | — | 3 |
| Duo Zhou et al. | [Geometric-Disentangelment Unlearning](https://doi.org/10.48550/arXiv.2511.17100) | arXiv | LLM | [GitHub](https://github.com/Lemutisme/Geometric-Unlearning) | 3 |
| T. Shaik et al. | [Quantum Machine Unlearning: Foundations, Mechanisms, and Taxonomy](https://doi.org/10.48550/arXiv.2511.00406) | arXiv | Other | — | 3 |
| Ioannis Mavrothalassitis et al. | [Ascent Fails to Forget](https://doi.org/10.48550/arXiv.2509.26427) | arXiv | Other | — | 3 |
| Chengcan Wu et al. | [Reliable Unlearning Harmful Information in LLMs with Metamorphosis Representation Projection](https://doi.org/10.48550/arXiv.2508.15449) | arXiv | LLM | [GitHub](https://github.com/ChengcanWu/MRP) | 3 |
| Xiaohua Feng et al. | [A Survey on Generative Model Unlearning: Fundamentals, Taxonomy, Evaluation, and Future Direction](https://doi.org/10.48550/arXiv.2507.19894) | arXiv | Other | [GitHub](https://github.com/caxLee/Generative-model-unlearning-survey) | 3 |
| Dimitri Staufer | [What Should LLMs Forget? Quantifying Personal Data in LLMs for Right-to-Be-Forgotten Requests](https://doi.org/10.48550/arXiv.2507.11128) | arXiv | LLM | [HF](https://huggingface.co/datasets/humarin/chatgpt-paraphrases) | 3 |
| Taha Entesari et al. | [Constrained Entropic Unlearning: A Primal-Dual Framework for Large Language Models](https://doi.org/10.48550/arXiv.2506.05314) | arXiv | LLM | [GitHub](https://github.com/locuslab/open-unlearning) | 3 |
| Yuxin Wen et al. | [Quantifying Cross-Modality Memorization in Vision-Language Models](https://doi.org/10.48550/arXiv.2506.05198) | arXiv | Other | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 3 |
| Jianheng Tang et al. | [ACU: Analytic Continual Unlearning for Efficient and Exact Forgetting with Privacy Preservation](https://doi.org/10.48550/arXiv.2505.12239) | arXiv | Other | — | 3 |
| Ali Ebrahimpour Boroojeny, Hari Sundaram, Varun Chandrasekaran | [AMUN: Adversarial Machine UNlearning](https://doi.org/10.48550/arXiv.2503.00917) | arXiv | Vision | [GitHub](https://github.com/Ali-E/AMUN) | 3 |
| Wonje Jeung et al. | [DUSK: Do Not Unlearn Shared Knowledge](https://doi.org/10.48550/arXiv.2505.15209) | arXiv | LLM | [GitHub](https://github.com/AI-ISL/DUSK) | 3 |
| Lulu Xue et al. | [Towards Reliable Forgetting: A Survey on Machine Unlearning Verification, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2506.15115) | arXiv | Other | — | 3 |
| Alessio Mora et al. | [Federated Unlearning Made Practical: Seamless Integration via Negated Pseudo-Gradients](https://doi.org/10.48550/arXiv.2504.05822) | arXiv | Federated | — | 3 |
| Sayanta Adhikari, Vishnuprasadh Kumaravelu, P. Srijith | [An Unlearning Framework for Continual Learning](https://doi.org/10.48550/arXiv.2509.17530) | arXiv | Other | [GitHub](https://github.com/visprasadh/uncle) | 3 |
| Yeonwoo Jang et al. | [Prompt Attacks Reveal Superficial Knowledge Removal in Unlearning Methods](https://doi.org/10.48550/arXiv.2506.10236) | arXiv | LLM | [GitHub](https://github.com/diogo-cruz/prompt_attacks_paper) | 3 |
| Haoming Xu et al. | [ZJUKLAB at SemEval-2025 Task 4: Unlearning via Model Merging](https://doi.org/10.48550/arXiv.2503.21088) | arXiv | LLM | [GitHub](https://github.com/zjunlp/unlearn) | 3 |
| Chenlu Ding et al. | [MLLMEraser: Achieving Test-Time Unlearning in Multimodal Large Language Models through Activation Steering](https://doi.org/10.48550/arXiv.2510.04217) | arXiv | LLM | — | 3 |
| Xiaohua Feng et al. | [Bridging the Gap Between Preference Alignment and Machine Unlearning](https://doi.org/10.48550/arXiv.2504.06659) | arXiv | LLM | [GitHub](https://github.com/muyiahhh/U2A) | 3 |
| Lexiang Xiong et al. | [Semantic Surgery: Zero-Shot Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2510.22851) | arXiv | Diffusion | [GitHub](https://github.com/Lexiang-Xiong/Semantic-Surgery) | 3 |
| Finn Carter | [ACE: Attentional Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2504.11850) | arXiv | Diffusion | — | 3 |
| Yuyang Xue et al. | [CRCE: Coreference-Retention Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2503.14232) | arXiv | Diffusion | [GitHub](https://github.com/vios-s/CRCE) | 3 |
| A. Richardson et al. | [Rethinking the Vulnerability of Concept Erasure and a New Method](https://arxiv.org/abs/2502.17537) | arXiv | Diffusion | [GitHub](https://github.com/notAI-tech/NudeNet) | 3 |
| Arman Zarei et al. | [Localizing Knowledge in Diffusion Transformers](https://doi.org/10.48550/arXiv.2505.18832) | arXiv | Diffusion | [GitHub](https://github.com/ArmanZarei/DiT-Knowledge-Localization) | 3 |
| Filip Sondej et al. | [Robust LLM Unlearning with MUDMAN: Meta-Unlearning with Disruption Masking And Normalization](https://doi.org/10.48550/arXiv.2506.12484) | arXiv | LLM | [GitHub](https://github.com/filyp/mudman) | 3 |
| Qipeng Song et al. | [Synthetic Forgetting without Access: A Few-shot Zero-glance Framework for Machine Unlearning](https://doi.org/10.48550/arXiv.2511.13116) | AAAI | Vision | — | 2 |
| Kunhao Li et al. | [Cross-Modal Unlearning via Influential Neuron Path Editing in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2511.06793) | AAAI | LLM | [GitHub](https://github.com/PreckLi/MIP-Editor) | 2 |
| Shuai Zhao et al. | [Unlearning Backdoor Attacks for LLMs with Weak-to-Strong Knowledge Distillation](https://doi.org/10.18653/v1/2025.findings-acl.255) | ACL | LLM | [GitHub](https://github.com/shuaizhao95/w2sdefense) | 2 |
| S. Vasilev et al. | [Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target Self-Distillation](https://doi.org/10.48550/arXiv.2505.06027) | ACL | LLM | [GitHub](https://github.com/eBay/unilogit-acl-2025) | 2 |
| Feihong Yu et al. | [LEGO: A Lightweight and Efficient Multiple-Attribute Unlearning Framework for Recommender Systems](https://doi.org/10.1145/3746027.3755604) | ACM MM | Recsys | [GitHub](https://github.com/mtuann/machine-unlearning-papers) | 2 |
| Tarun Ram Menta, Susmit Agrawal, Chirag Agarwal | [Analyzing Memorization in Large Language Models through the Lens of Model Attribution](https://doi.org/10.18653/v1/2025.naacl-long.535) | BuildingTrust | LLM | — | 2 |
| Ziheng Chen et al. | [FROG: Fair Removal on Graph](https://doi.org/10.1145/3746252.3761341) | CIKM | Graph | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 2 |
| Ziheng Chen et al. | [FUTURE: Flexible Unlearning for Tree Ensemble](https://doi.org/10.1145/3746252.3760948) | CIKM | Other | — | 2 |
| Yi-Xing Peng et al. | [Person De-reidentification: A Variation-guided Identity Shift Modeling](https://doi.org/10.1109/CVPR52734.2025.02731) | CVPR | Vision | [GitHub](https://github.com/yxsysu/Person-DeReID) | 2 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [ReVeil: Unconstrained Concealed Backdoor Attack on Deep Neural Networks using Machine Unlearning](https://doi.org/10.1109/DAC63849.2025.11133199) | Design Automation Conference | Vision | [GitHub](https://github.com/momalab/ReVeil) | 2 |
| Wonje Jeung, Sangyeon Yoon, Albert No | [SEPS: A Separability Measure for Robust Unlearning in LLMs](https://doi.org/10.48550/arXiv.2505.14832) | EMNLP | LLM | [GitHub](https://github.com/AI-ISL/SEPS) | 2 |
| Xianren Zhang et al. | [SUA: Stealthy Multimodal Large Language Model Unlearning Attack](https://doi.org/10.18653/v1/2025.emnlp-main.565) | EMNLP | LLM | — | 2 |
| Yuntao Wen et al. | [Lock on Target! Precision Unlearning via Directional Control](https://doi.org/10.18653/v1/2025.findings-emnlp.1021) | EMNLP | LLM | — | 2 |
| Fasih Haider et al. | [Do generative models learn rare generative factors?](https://doi.org/10.3389/frai.2025.1697139) | Frontiers in Artificial Intelligence | Diffusion | — | 2 |
| Weixiang Zhao et al. | [The gains do not make up for the losses: a comprehensive evaluation for safety alignment of large language models via machine unlearning](https://doi.org/10.1007/s11704-024-41099-x) | Frontiers of Computer Science | LLM | — | 2 |
| Naglaa E. Ghannam, Esraa A. Mahareek | [Privacy-Preserving Federated Unlearning with Ontology-Guided Relevance Modeling for Secure Distributed Systems](https://doi.org/10.3390/fi17080335) | Future Internet | Federated | — | 2 |
| Puwei Lian et al. | [Enhancing Membership Inference Attacks on Diffusion Models from a Frequency-Domain Perspective](https://arxiv.org/abs/2505.20955) | ICASSP | Diffusion | — | 2 |
| Nowfel Mashnoor et al. | [CircuitGuard: Mitigating LLM Memorization in RTL Code Generation Against IP Leakage](https://doi.org/10.1109/ICCD65941.2025.00117) | ICCD | LLM | [GitHub](https://github.com/mashnoor/circuitguard) | 2 |
| Chenxu Zhao et al. | [Membership Inference Attacks With False Discovery Rate Control](https://doi.org/10.1109/ICCV51701.2025.00121) | ICCV | Other | [GitHub](https://github.com/chenxuzhao-ai/MIAFdR) | 2 |
| Yaxin Xiao et al. | [Reminiscence Attack on Residuals: Exploiting Approximate Machine Unlearning for Privacy](https://doi.org/10.1109/ICCV51701.2025.00293) | ICCV | Other | — | 2 |
| Ozan Özdenizci, Elmar Rueckert, R. Legenstein | [Privacy-Aware Lifelong Learning](https://doi.org/10.48550/arXiv.2505.10941) | ICLR | Other | [GitHub](https://github.com/oozdenizci/PALL) | 2 |
| Hiroshi Takahashi et al. | [Positive-Unlabeled Diffusion Models for Preventing Sensitive Data Generation](https://doi.org/10.48550/arXiv.2503.03789) | ICLR | Diffusion | [GitHub](https://github.com/takahashihiroshi/pudm) | 2 |
| Fangwei Wang et al. | [FedBT: Effective and Robust Federated Unlearning via Bad Teacher Distillation for Secure Internet of Things](https://doi.org/10.1109/jiot.2025.3571432) | IEEE IoT-J | Federated | — | 2 |
| Wathsara Daluwatta et al. | [SSFU: Selective Semantic Feature Unlearning for Federated Learning in 6G Internet of Things Systems](https://doi.org/10.1109/jiot.2025.3625756) | IEEE IoT-J | Federated | — | 2 |
| Pu Wang, Xin Su, Zhuoran Zheng | [Instance-Wise Privacy Preservation for All-in-One Image Restoration](https://doi.org/10.1109/LSP.2025.3624077) | IEEE Signal Processing Letters | Vision | — | 2 |
| Yu Jiang et al. | [Certifying the Right to Be Forgotten: Primal–Dual Optimization for Sample and Label Unlearning in Vertical Federated Learning](https://doi.org/10.1109/tifs.2025.3636788) | IEEE T-IFS | Federated | — | 2 |
| Xiaohan Yuan et al. | [FedEditor: Efficient and Effective Federated Unlearning in Cooperative Intelligent Transportation Systems](https://doi.org/10.1109/tifs.2025.3583231) | IEEE T-IFS | Federated | — | 2 |
| Yixiang Pan et al. | [The Safety Illusion? Testing the Boundaries of Concept Removal in Diffusion Models](https://doi.org/10.1109/TIP.2025.3620665) | IEEE TIP | Diffusion | — | 2 |
| Yuanxiang Gong et al. | [Channel Knowledge Map Updating with Machine Unlearning](https://doi.org/10.1109/icccworkshops67136.2025.11148163) | IEEE/CIC International Conference on Communications in China (ICCC Workshops) | Other | — | 2 |
| Yuechun Gu, Jiajie He, Keke Chen | [Auditing Approximate Machine Unlearning for Differentially Private Models](https://doi.org/10.1109/ICDM65498.2025.00134) | Industrial Conference on Data Mining | Other | — | 2 |
| Naglaa E. Ghannam, Esraa A. Mahareek | [AGU: Adaptive gradient unlearning for efficient machine unlearning](https://doi.org/10.1016/j.iswa.2025.200592) | Intelligent Systems with Applications | Other | — | 2 |
| Kun Gao et al. | [Federated Unlearning With Reinforcement Learning: Adaptive Privacy Preservation for Clients](https://doi.org/10.1016/j.jisa.2025.104164) | Journal of Information Security and Applications | Federated | — | 2 |
| N. Xu et al. | [Learn to unlearn: meta-learning-based knowledge graph embedding unlearning](https://doi.org/10.1007/s10115-025-02407-4) | Knowledge and Information Systems | Graph | — | 2 |
| Deliang Jin et al. | [Machine Unlearning for Robust DNNs: Attribution-Guided Partitioning and Neuron Pruning in Noisy Environments](https://doi.org/10.3390/make7030095) | Machine Learning and Knowledge Extraction | Vision | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 2 |
| Zhongbin Huang et al. | [ConceptVoid: Precision Multi-Concept Erasure in Generative Video Diffusion](https://doi.org/10.3390/math13162652) | Mathematics | Diffusion | — | 2 |
| Xiaoyu Wu et al. | [Unlearned but Not Forgotten: Data Extraction after Exact Unlearning in LLM](https://arxiv.org/abs/2505.24379) | NeurIPS poster | LLM | [GitHub](https://github.com/Nicholas0228/unlearned_data_extraction_llm) | 2 |
| Lin Li et al. | [Enhancing partition distinction: A contrastive policy to recommendation unlearning](https://doi.org/10.1016/j.neunet.2025.107667) | Neural Networks | Recsys | [GitHub](https://github.com/linli0818/PDCRU) | 2 |
| Abdulla Alshabanah, Keshav Balasubramanian, Murali Annavaram | [Meta-Learn to Unlearn: Enhanced Exact Machine Unlearning in Recommendation Systems with Meta-Learning](https://doi.org/10.56553/popets-2025-0152) | PoPETs | Recsys | — | 2 |
| Guoxuan Chen, Lianghao Xia, Chao Huang | [Pre-training for Recommendation Unlearning](https://doi.org/10.1145/3726302.3730060) | SIGIR | Recsys | [GitHub](https://github.com/HKUDS/UnlearnRec) | 2 |
| Haruki Yonekura et al. | [MobText-SISA: Efficient Machine Unlearning for Mobility Logs with Spatio-Temporal and Natural-Language Data](https://doi.org/10.1145/3748636.3763226) | SIGSPATIAL/GIS | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 2 |
| Amrita Roy Chowdhury, Zhifeng Kong, Kamalika Chaudhuri | [On the Reliability of Membership Inference Attacks](https://doi.org/10.1109/SaTML64287.2025.00036) | SaTML | Other | — | 2 |
| Thomas De Min et al. | [Group-robust Machine Unlearning](https://doi.org/10.48550/arXiv.2503.09330) | TMLR | Other | [GitHub](https://github.com/tdemin16/group-robust_machine_unlearning) | 2 |
| Lang Li et al. | [Inverse correction-optimized vertical federated unlearning](https://doi.org/10.1007/s11227-025-07310-x) | The Journal of Supercomputing | Federated | — | 2 |
| Nguyen, Viet, Patel, Vishal M. | [CGCE: Classifier-Guided Concept Erasure in Generative Models](https://doi.org/10.48550/arXiv.2511.05865) | arXiv | Diffusion | — | 2 |
| Liu, Yezi et al. | [Recover-to-Forget: Gradient Reconstruction from LoRA for Efficient LLM Unlearning](https://doi.org/10.48550/arXiv.2512.07374) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| M. Maheri et al. | [ZK-APEX: Zero-Knowledge Approximate Personalized Unlearning with Executable Proofs](https://doi.org/10.48550/arXiv.2512.09953) | arXiv | Other | — | 2 |
| Ruichen Qiu et al. | [A Survey on Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2510.25117) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Zirui Pang et al. | [Label Smoothing Improves Gradient Ascent in LLM Unlearning](https://doi.org/10.48550/arXiv.2510.22376) | arXiv | LLM | — | 2 |
| Shiji Zhou et al. | [Efficient Utility-Preserving Machine Unlearning with Implicit Gradient Surgery](https://doi.org/10.48550/arXiv.2510.22124) | arXiv | Other | [GitHub](https://github.com/anseryuer/EUPMU-Efficient-Utility-Preserving-Machine-Unlearning) | 2 |
| Jiatong Yu et al. | [On the Impossibility of Retrain Equivalence in Machine Unlearning](https://doi.org/10.48550/arXiv.2510.16629) | arXiv | Other | [HF](https://huggingface.co/spaces/raayraay/LLM-Fact-Forgetter) | 2 |
| Aaradhya Pandey et al. | [Gaussian Certified Unlearning in High Dimensions: A Hypothesis Testing Approach](https://doi.org/10.48550/arXiv.2510.13094) | arXiv | Other | — | 2 |
| Kai Qin et al. | [Distribution Preference Optimization: A Fine-grained Perspective for LLM Unlearning](https://doi.org/10.48550/arXiv.2510.04773) | arXiv | LLM | — | 2 |
| H. Lee, Ruixuan Liu, Li Xiong | [Direct Token Optimization: A Self-contained Approach to Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2510.00125) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Xiang Li et al. | [LoReUn: Data Itself Implicitly Provides Cues to Improve Machine Unlearning](https://doi.org/10.48550/arXiv.2507.22499) | arXiv | Diffusion | [GitHub](https://github.com/OPTML-Group/Unlearn-Saliency) | 2 |
| Xuyang Zhong, Hao Luo, Chen Liu | [DualOptim: Enhancing Efficacy and Stability in Machine Unlearning with Dual Optimizers](https://doi.org/10.48550/arXiv.2504.15827) | arXiv | Other | — | 2 |
| Yegor Klochkov | [A mean teacher algorithm for unlearning of language models](https://doi.org/10.48550/arXiv.2504.13388) | arXiv | LLM | [GitHub](https://github.com/yklochkov-bytedance/mt-unlearn) | 2 |
| Yijun Quan, Zushu Li, Giovanni Montana | [Efficient Verified Machine Unlearning For Distillation](https://doi.org/10.48550/arXiv.2503.22539) | arXiv | Other | [GitHub](https://github.com/YijunQuan/VerifiedMU4Distill) | 2 |
| Zonghao Huang, N. Gong, Michael K. Reiter | [Instance-Level Data-Use Auditing of Visual ML Models](https://doi.org/10.48550/arXiv.2503.22413) | arXiv | Vision | [GitHub](https://github.com/tensorflow/privacy/tree) | 2 |
| Yingdan Shi, Ren Wang | [Redefining Machine Unlearning: A Conformal Prediction-Motivated Approach](https://doi.org/10.48550/arXiv.2501.19403) | arXiv | Other | [GitHub](https://github.com/TIML-Group/Conformal-Prediction-Unlearning) | 2 |
| Jaeheun Jung et al. | [OPC: One-Point-Contraction Unlearning Toward Deep Feature Forgetting](https://doi.org/10.48550/arXiv.2507.07754) | arXiv | Vision | [GitHub](https://github.com/pytorch/vision) | 2 |
| Marco Arazzi, Antonino Nocera, P. Vinod | [When Forgetting Triggers Backdoors: A Clean Unlearning Attack](https://doi.org/10.48550/arXiv.2506.12522) | arXiv | Vision | — | 2 |
| Sadiah Qureshi et al. | [Exploring Incremental Unlearning: Techniques, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2502.16708) | arXiv | Other | — | 2 |
| Hao Zheng et al. | [OFFSIDE: Benchmarking Unlearning Misinformation in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2510.22535) | arXiv | LLM | [GitHub](https://github.com/zh121800/OFFSIDE) | 2 |
| Chenchen Tan et al. | [Wisdom is Knowing What not to Say: Hallucination-Free LLMs Unlearning via Attention Shifting](https://doi.org/10.48550/arXiv.2510.17210) | arXiv | LLM | [GitHub](https://github.com/google-research/lm-extraction-benchmark) | 2 |
| Junbeom Kim et al. | [Scalable and Robust LLM Unlearning by Correcting Responses with Retrieved Exclusions](https://doi.org/10.48550/arXiv.2509.25973) | arXiv | LLM | [GitHub](https://github.com/the-jb/cure) | 2 |
| Hang Yan, Zheyuan Liu, Meng Jiang | [Dual-Space Smoothness for Robust and Balanced LLM Unlearning](https://doi.org/10.48550/arXiv.2509.23362) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Nakyeong Yang et al. | [Erase or Hide? Suppressing Spurious Unlearning Neurons for Robust Unlearning](https://doi.org/10.48550/arXiv.2509.22263) | arXiv | LLM | [GitHub](https://github.com/centerforaisafety/wmdp) | 2 |
| Xiaoyuan Zhu et al. | [LLM Unlearning Without an Expert Curated Dataset](https://doi.org/10.48550/arXiv.2508.06595) | arXiv | LLM | [GitHub](https://github.com/xyzhu123/Synthetic_Textbook) | 2 |
| Tatsuki Kawakami et al. | [PULSE: Practical Evaluation Scenarios for Large Multimodal Model Unlearning](https://doi.org/10.48550/arXiv.2507.01271) | arXiv | LLM | — | 2 |
| Huazheng Wang et al. | [Erasing Without Remembering: Implicit Knowledge Forgetting in Large Language Models](https://arxiv.org/abs/2502.19982) | arXiv | LLM | [GitHub](https://github.com/MaybeLizzy/PERMU) | 2 |
| Huazheng Wang et al. | [Erasing Without Remembering: Safeguarding Knowledge Forgetting in Large Language Models](https://doi.org/10.48550/arXiv.2502.19982) | arXiv | LLM | [GitHub](https://github.com/MaybeLizzy/PERMU) | 2 |
| Zhen Zeng et al. | [Towards Benign Memory Forgetting for Selective Multimodal Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2511.20196) | arXiv | LLM | — | 2 |
| Chongyu Fan et al. | [LLM Unlearning Under the Microscope: A Full-Stack View on Methods and Metrics](https://doi.org/10.48550/arXiv.2510.07626) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-FullStack) | 2 |
| Bingqi Shang et al. | [Forgetting to Forget: Attention Sink as A Gateway for Backdooring LLM Unlearning](https://doi.org/10.48550/arXiv.2510.17021) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-Backdoor) | 2 |
| Hengrui Jia et al. | [The Erasure Illusion: Stress-Testing the Generalization of LLM Forgetting Evaluation](https://doi.org/10.48550/arXiv.2512.19025) | arXiv | Other | — | 2 |
| Xun Yuan et al. | [Towards Irreversible Machine Unlearning for Diffusion Models](https://doi.org/10.48550/arXiv.2512.03564) | arXiv | Diffusion | [GitHub](https://github.com/OPTML-Group/UnlearnCanvas) | 2 |
| Justin Lee et al. | [Continual Unlearning for Text-to-Image Diffusion Models: A Regularization Perspective](https://doi.org/10.48550/arXiv.2511.07970) | arXiv | Diffusion | — | 2 |
| Abhiram Kusumba et al. | [EraseFlow: Learning Concept Erasure Policies via GFlowNet-Driven Alignment](https://doi.org/10.48550/arXiv.2511.00804) | arXiv | Diffusion | [GitHub](https://github.com/Abhiramkns/EraseFlow) | 2 |
| Byeonghu Na et al. | [Training-Free Safe Text Embedding Guidance for Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2510.24012) | arXiv | Diffusion | [GitHub](https://github.com/aailab-kaist/STG) | 2 |
| Jiaqi Liu, Lan Zhang, Xiaoyong Yuan | [DyME: Dynamic Multi-Concept Erasure in Diffusion Models with Bi-Level Orthogonal LoRA Adaptation](https://doi.org/10.48550/arXiv.2509.21433) | arXiv | Diffusion | — | 2 |
| Antoni Kowalczuk et al. | [Finding Dori: Memorization in Text-to-Image Diffusion Models Is Not Local](https://arxiv.org/abs/2507.16880) | arXiv | Diffusion | [GitHub](https://github.com/KJaebye/EmbodiedAI-Robotics-arXiv-Daily-Reporter) | 2 |
| Amr Abdalla et al. | [GIFT: Gradient-aware Immunization of diffusion models against malicious Fine-Tuning with safe concepts retention](https://doi.org/10.48550/arXiv.2507.13598) | arXiv | Diffusion | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 2 |
| Finn Carter | [TRACE: Trajectory-Constrained Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2505.23312) | arXiv | Diffusion | — | 2 |
| Die Chen et al. | [Comprehensive Evaluation and Analysis for NSFW Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2505.15450) | arXiv | Diffusion | [GitHub](https://github.com/ECNU-CILAB/ErasureBenchmark) | 2 |
| Dahye Kim, Deepti Ghadiyaram | [Concept Steerers: Leveraging K-Sparse Autoencoders for Test-Time Controllable Generations](https://arxiv.org/abs/2501.19066) | arXiv | Diffusion | [GitHub](https://github.com/kim-dahye/steerers) | 2 |
| Pierre Lubitzsch et al. | [Towards a Real-World Aligned Benchmark for Unlearning in Recommender Systems](https://doi.org/10.48550/arXiv.2508.17076) | arXiv | Recsys | [GitHub](https://github.com/pierre-lubitzsch/towards-unlearning-in-recsys) | 2 |
| Sheng-Yu Wang et al. | [Fast Data Attribution for Text-to-Image Models](https://doi.org/10.48550/arXiv.2511.10721) | arXiv | Diffusion | [GitHub](https://github.com/PeterWang512/FastGDA) | 2 |
| Jimmy Z. Di et al. | [Demystifying Foreground-Background Memorization in Diffusion Models](https://doi.org/10.48550/arXiv.2508.12148) | AAAI | Diffusion | [GitHub](https://github.com/Jimmy-di/localizing_memorization_in_diffusion_models) | 1 |
| Edoardo De Matteis et al. | [Human Motion Unlearning](https://doi.org/10.48550/arXiv.2503.18674) | AAAI | Other | [GitHub](https://github.com/Mamiglia/hmu) | 1 |
| Peihai Jiang et al. | [Backdoor Token Unlearning: Exposing and Defending Backdoors in Pretrained Language Models](https://doi.org/10.1609/aaai.v39i23.34605) | AAAI | LLM | — | 1 |
| Weilin Lin et al. | [Fusing Pruned and Backdoored Models: Optimal Transport-based Data-free Backdoor Mitigation](https://doi.org/10.1609/aaai.v39i25.34828) | AAAI | Vision | — | 1 |
| Jiaqi Li et al. | [Forget the Token and Pixel: Rethinking Gradient Ascent for Concept Unlearning in Multimodal Generative Models](https://doi.org/10.18653/v1/2025.findings-acl.630) | ACL | Diffusion | [GitHub](https://github.com/DiWHNJ/FTTP) | 1 |
| M.Z. Naser | [Auditing the Shadows: A Review of Methods to Detect Shared Training Data in Large Language Models](https://doi.org/10.1145/3774897) | ACM Computing Surveys | LLM | — | 1 |
| Yizhou Lin et al. | [ICE: Intercede Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1145/3746027.3754992) | ACM MM | Diffusion | — | 1 |
| Yang Li et al. | [Cross-User Federated Recommendation Unlearning](https://doi.org/10.1145/3749990) | ACM TIST | Recsys | — | 1 |
| Yi Li et al. | [Graph Unlearning System with Subgraph De-Isolation Measures](https://doi.org/10.1145/3750734) | ACM Transactions on Autonomous and Adaptive Systems | Graph | — | 1 |
| Changsheng Wang et al. | [LLM Unlearning on Noisy Forget Sets: A Study of Incomplete, Rewritten, and Watermarked Data](https://doi.org/10.1145/3733799.3762973) | AISec@CCS | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Ranjit Kumar et al. | [Machine Unlearning for Trustworthy AI: A Systematic Review of Techniques, Challenges, and Applications](https://doi.org/10.1007/s11831-025-10436-z) | Archives of Computational Methods in Engineering | Other | — | 1 |
| Urbana Jaman Orthee et al. | [Unlearning for Clinical Deployment: Scalable Data Erasure in Medical Image Classification Models](https://doi.org/10.1109/BECITHCON69222.2025.11504291) | BECITHCON | Vision | — | 1 |
| Gaoyang Liu et al. | [Prototype Surgery: Tailoring Neural Prototypes via Soft Labels for Efficient Machine Unlearning](https://doi.org/10.1145/3719027.3744827) | CCS | Vision | — | 1 |
| Samaneh Mohammadi et al. | [EFU: Enforcing Federated Unlearning via Functional Encryption](https://doi.org/10.1145/3746252.3761091) | CIKM | Federated | — | 1 |
| Yang Xiao et al. | [Efficient Knowledge Graph Unlearning with Zeroth-order Information](https://doi.org/10.1145/3746252.3761379) | CIKM | Graph | [GitHub](https://github.com/NKUShaw/ZOWFKGIF) | 1 |
| Andrea D'Angelo et al. | [ERASURE: A Modular and Extensible Framework for Machine Unlearning](https://doi.org/10.1145/3746252.3761627) | CIKM | Other | [GitHub](https://github.com/aiim-research/ERASURE) | 1 |
| Muhammad Shaheryar, Jong Taek Lee, Soon Ki Jung | [Black Hole-Driven Identity Absorbing in Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02658) | CVPR | Diffusion | — | 1 |
| Àlex Pujol Vidal et al. | [Machine Unlearning in Hyperbolic vs. Euclidean Multimodal Contrastive Learning: Adapting Alignment Calibration to MERU](https://doi.org/10.1109/CVPRW67362.2025.00152) | CVPR | Vision | [GitHub](https://github.com/alexpv01/HAC) | 1 |
| Yimin Wen et al. | [Unlearning Recently Learned Data to Preserve Historical Learning for Dynamic Data Stream Classification](https://doi.org/10.23919/cje.2024.00.219) | Chinese Journal of Electronics | Other | — | 1 |
| Si Qi Goh et al. | [FROC: A Unified Framework with Risk-Optimized Control for Machine Unlearning in LLMs](https://doi.org/10.1109/ICAIIC68212.2026.11454224) | Digital Signal Processing and Signal Processing Education Workshop | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Feng Li et al. | [Secure Dynamic Spectrum Access in Internet-of-Things Based on Machine Unlearning](https://doi.org/10.1109/ICAIIC64266.2025.10920793) | Digital Signal Processing and Signal Processing Education Workshop | Other | — | 1 |
| Xin Gao et al. | [Can Prompts Rewind Time for LLMs? Evaluating the Effectiveness of Prompted Knowledge Cutoffs](https://doi.org/10.48550/arXiv.2510.02340) | EMNLP | LLM | [GitHub](https://github.com/gxx27/time_unlearn) | 1 |
| Jingyu Zhang et al. | [Certified Mitigation of Worst-Case LLM Copyright Infringement](https://doi.org/10.48550/arXiv.2504.16046) | EMNLP | LLM | [GitHub](https://github.com/JHU-CLSP/BloomScrub) | 1 |
| Haokun Chen et al. | [Soft Token Attacks Cannot Reliably Audit Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2502.15836) | EMNLP | LLM | [GitHub](https://github.com/IntelLabs/LLMart/tree) | 1 |
| Myeongseob Ko et al. | [Retracing the Past: LLMs Emit Training Data When They Get Lost](https://doi.org/10.18653/v1/2025.emnlp-main.1789) | EMNLP | LLM | — | 1 |
| Fan Zhang et al. | [BMAIU: Backdoor Mitigation in Self-Supervised Learning Through Active Implantation and Unlearning](https://doi.org/10.3390/electronics14081587) | Electronics | Vision | — | 1 |
| Fudu Xing et al. | [A continuous verification mechanism for ensuring client data forgetfulness in Federated Unlearning](https://doi.org/10.1016/j.engappai.2025.112553) | Engineering Applications of Artificial Intelligence | Federated | — | 1 |
| Van-Tuan Tran, Hong-Hanh Nguyen-Le, Quoc-Viet Pham | [ToFU: Transforming How Federated Learning Systems Forget User Data](https://doi.org/10.48550/arXiv.2509.15861) | European Conference on Artificial Intelligence | Federated | — | 1 |
| Yue Zhang et al. | [RUCLIP: Robust concept unlearning in CLIP via semantic anchors](https://doi.org/10.1016/j.eswa.2025.130495) | Expert Systems with Applications | Vision | — | 1 |
| Aman Kumar et al. | [FLUID: Federated Learning with Unlearning and Instant Drift-Recovery](https://doi.org/10.1109/FLTA67013.2025.11336437) | FLTA | Federated | [GitHub](https://github.com/Encore7/fluid) | 1 |
| Toan Tran, Ruixuan Liu, Xiong Li | [Tokens for Learning, Tokens for Unlearning: Mitigating Membership Inference Attacks in Large Language Models via Dual-Purpose Training](https://doi.org/10.18653/v1/2025.findings-acl.1174) | Findings | LLM | — | 1 |
| Shunichi Watanabe | [Pseudo-Labeling for Enhanced User Privacy in Approximate Machine Unlearning](https://doi.org/10.1109/ICASSP49660.2025.10890795) | ICASSP | Vision | — | 1 |
| Francisco Messina et al. | [Mitigating data replication in text-to-audio generative diffusion models through anti-memorization guidance](https://doi.org/10.48550/arXiv.2509.14934) | ICASSP | Diffusion | [GitHub](https://github.com/polimi-ispl/anti-memorization-tta) | 1 |
| Parthaw Goswami, Md Khairul Islam, Ashfak Yeafi | [PrivEraserVerify: Efficient, Private, and Verifiable Federated Unlearning](https://doi.org/10.1109/iccit68739.2025.11491311) | ICCIT | Federated | — | 1 |
| Zheling Meng et al. | [D ARK M INER : D EFEND AGAINST UNSAFE GENERATION FOR TEXT - TO - IMAGE DIFFUSION MODELS](https://www.semanticscholar.org/paper/58c129c6af566e8a3f9a8467a3e79458e2fb71bc) | ICLR Conference Withdrawn Submission | Diffusion | — | 1 |
| M. Maheri et al. | [WARP: Weight Teleportation for Attack-Resilient Unlearning Protocols](https://arxiv.org/abs/2512.00272) | ICLR Poster | Vision | [GitHub](https://github.com/mammadmaheri7/WARP_Unlearning) | 1 |
| Lin Lu, Ayush Sekhari, Karthik Sridharan | [System-Aware Unlearning Algorithms: Use Lesser, Forget Faster](https://doi.org/10.48550/arXiv.2506.06073) | ICML | Other | — | 1 |
| D. K et al. | [Machine Unlearning In Recommendation Systems](https://doi.org/10.1109/ICTEST64710.2025.11042432) | ICTEST | Recsys | — | 1 |
| Hong Xi Tae, Chee Seng Chan | [A Survey of Challenges and Opportunities in Vertical Federated Unlearning](https://doi.org/10.1109/access.2025.3600884) | IEEE Access | Federated | [GitHub](https://github.com/bryanhx/Vertical-Federated-Unlearning-Benchmark) | 1 |
| Wenhan Wu et al. | [Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning](https://doi.org/10.1109/ICDE65448.2025.00200) | IEEE International Conference on Data Engineering | Recsys | [GitHub](https://github.com/Anya-bond/Awesome-Privacy-RecSys) | 1 |
| Thanh Linh Nguyen et al. | [Toward Verifiable Federated Unlearning: Framework, Challenges, and the Road Ahead](https://doi.org/10.1109/MIC.2026.3656638) | IEEE Internet Computing | Federated | — | 1 |
| Xuanpeng Li et al. | [An Efficient Two-Stage Machine Unlearning Framework for Poisoned Specific Emitter Identification](https://doi.org/10.1109/jiot.2025.3583362) | IEEE IoT-J | Other | — | 1 |
| Linshan Hou et al. | [FixGuard: Repairing Backdoored Models via Class-Wise Trigger Recovery and Unlearning](https://doi.org/10.1109/lsp.2025.3572409) | IEEE Signal Processing Letters | Vision | — | 1 |
| Jiale Zhang et al. | [SSLDefender: Backdoor Defense in Self-Supervised Learning via Distillation-Guided Unlearning](https://doi.org/10.1109/TIFS.2025.3640880) | IEEE T-IFS | Vision | — | 1 |
| Jiahao Wu et al. | [Machine Unlearning For Alleviating Negative Transfer In Partial-Set Source-Free Unsupervised Domain Adaptation](https://doi.org/10.1109/tai.2025.3638979) | IEEE TAI | Vision | — | 1 |
| Xiangshan Gao et al. | [A2E: Black-Box Anti-Adversarial Example Based Watermarking to Verify Federated Unlearning](https://doi.org/10.1109/tdsc.2025.3598987) | IEEE TDSC | Federated | — | 1 |
| Weiqi Wang et al. | [SMS: Self-Supervised Model Seeding for Verification of Machine Unlearning](https://doi.org/10.1109/TDSC.2025.3615615) | IEEE TDSC | Other | [GitHub](https://github.com/wwq5-code/SMS) | 1 |
| Yuepeng Hu et al. | [Periodic Recovery From Poisoning Attacks in Machine Learning](https://doi.org/10.1109/TDSC.2025.3560239) | IEEE TDSC | Other | [GitHub](https://github.com/hifi-hyp/PeriRecover) | 1 |
| Wenjun Zeng et al. | [FU-PA: Federated Unlearning via Parameters Adjustment](https://doi.org/10.1109/tetci.2025.3576117) | IEEE TETCI | Federated | — | 1 |
| Yujun Cheng et al. | [SeFUL: A Selective Federated Unlearning Framework for Client Data Heterogeneity in Intelligent Wireless Networks](https://doi.org/10.1109/tmc.2025.3637775) | IEEE TMC | Federated | — | 1 |
| Jian Chen et al. | [Unlearning Attacks for Regression Learning](https://doi.org/10.1109/TNNLS.2025.3553821) | IEEE TNNLS | Other | — | 1 |
| Yanghe Pan et al. | [The Right to Be Forgotten Versus the Need to Be Remembered: Efficient Personalized Federated Unlearning With Optimal Incentives](https://doi.org/10.1109/tnse.2025.3597640) | IEEE TNSE | Federated | — | 1 |
| Jiayi Wang et al. | [A Zero-Shot Federated Unlearning Framework With Stability Verification](https://doi.org/10.1109/tccn.2025.3594672) | IEEE Transactions on Cognitive Communications and Networking | Federated | [GitHub](https://github.com/kayeewww/fuzv) | 1 |
| Yan Qu et al. | [Fuzzified Federated Multi-Task Unlearning for Efficient and Privacy-Preserving Swarm Consumer Electronics Systems](https://doi.org/10.1109/tce.2025.3571956) | IEEE Transactions on Consumer Electronics | Federated | — | 1 |
| Jielong Yang et al. | [Machine Unlearning for Source-Free Unsupervised Partial-Domain Adaptation in Remote Sensing](https://doi.org/10.1109/tgrs.2025.3637240) | IEEE Transactions on Geoscience and Remote Sensing | Vision | — | 1 |
| Yuange Liu et al. | [EPFL: Toward Elastic Personalized Federated Learning With Seamless Client Joining and Quitting](https://doi.org/10.1109/TSMC.2025.3613624) | IEEE Transactions on Systems, Man, and Cybernetics: Systems | Federated | — | 1 |
| Issa Sugiura, Shingo Okamura, Naoto Yanai | [Removing Mislabeled Data from Trained Models via Machine Unlearning](https://doi.org/10.1587/transinf.2024dat0002) | IEICE Trans. Inf. Syst | Vision | [GitHub](https://github.com/speed1313/mislabel-unlearning) | 1 |
| Mohammad Partohaghighi et al. | [Roughness-Informed Machine Unlearning: A Call for Fractal and Fractional Calculi](https://doi.org/10.1016/j.ifacol.2026.01.003) | IFAC-PapersOnLine | Other | — | 1 |
| Zhihao Sui et al. | [Recalling The Forgotten Class Memberships: Unlearned Models Can Be Noisy Labelers to Leak Privacy](https://doi.org/10.48550/arXiv.2506.19486) | IJCAI | Other | [GitHub](https://github.com/rainmilk/mra4mu) | 1 |
| Shreya Pathak et al. | [Quantum-Inspired Audio Unlearning: Towards Privacy-Preserving Voice Biometrics](https://doi.org/10.1109/IJCB65343.2025.11411246) | IJCB | Other | [GitHub](https://github.com/rishi02102017/QPAudioEraser-IndiaAI-Impact-Summit-Demo) | 1 |
| Chetia Phukan et al. | [Towards Machine Unlearning for Paralinguistic Speech Processing](https://doi.org/10.48550/arXiv.2506.02230) | INTERSPEECH | Other | [HF](https://huggingface.co/facebook/wav2vec2-xls-r-300m) | 1 |
| Ning Pang et al. | [Perturb and restore: Efficient category revocation in federated unlearning](https://doi.org/10.1016/j.inffus.2025.103994) | Information Fusion | Federated | — | 1 |
| Saeed Iqbal et al. | [Core unlearning: A multi-modal gradient-efficient architecture for exact and approximate model rewriting](https://doi.org/10.1016/j.ipm.2025.104417) | Information Processing & Management | Other | — | 1 |
| Hussien AbdelRaouf, Mohamed I. Ibrahem | [Federated Unlearning: Techniques, Trends, and Future Directions](https://doi.org/10.1109/ICMI65310.2025.11141148) | International Conference on Multimodal Interaction | Federated | — | 1 |
| Nishat Mahdiya Khan et al. | [Zero Trust Networks and Federated Unlearning Based <scp>6G</scp> Edge Networks: Attack Scenario, Security Model and Future Directions](https://doi.org/10.1002/itl2.70056) | Internet Technology Letters | Federated | — | 1 |
| Yunjian Zhang et al. | [Subspace-constrained graph unlearning for forgetting high-risk compound-protein interactions](https://doi.org/10.1016/j.knosys.2025.115193) | Knowledge-Based Systems | Graph | — | 1 |
| Dan Parii, Thomas van Osch, Chang Sun | [Machine Unlearning of Personally Identifiable Information in Large Language Models](https://doi.org/10.18653/v1/2025.nllp-1.6) | Natural Legal Language Processing Workshop | LLM | — | 1 |
| Ju-Hsuan Weng et al. | [Multimodal Robustness Benchmark for Concept Erasure in Diffusion Models](https://www.semanticscholar.org/paper/1346d7ba4f5e6fd972c261efe99e81758daa55c5) | NeurIPS Workshop GenProCC | Diffusion | — | 1 |
| Ruotong Geng et al. | [Mitigating sensitive information leakage in LLMs4Code through machine unlearning](https://doi.org/10.1016/j.neunet.2026.108606) | Neural Networks | LLM | — | 1 |
| Liang Xie et al. | [A Truthful Incentive Scheme Based on Data Forgetting Game for Federated Unlearning](https://doi.org/10.1109/pcds65695.2025.00030) | PCDS | Federated | — | 1 |
| Lei Kang et al. | [Preserving privacy without compromising accuracy: Machine unlearning for handwritten text recognition](https://doi.org/10.1016/j.patcog.2025.112411) | Pattern Recognition | Vision | [GitHub](https://github.com/leitro/WIC-WriterIDConfusion-MachineUnlearning) | 1 |
| Jun-Jian Su et al. | [From Membership-Privacy Leakage to Quantum Machine Unlearning](https://doi.org/10.1103/PhysRevApplied.25.044056) | Phys. Rev. Applied | Other | [GitHub](https://github.com/Sujun124/QMU) | 1 |
| Haocheng Dou, Tao Lian, Xin Xin | [Measuring Interaction-Level Unlearning Difficulty for Collaborative Filtering](https://doi.org/10.1145/3705328.3748092) | RecSys | Recsys | [GitLab](https://gitlab.com/hcdou/cf-unlearn-difficulty) | 1 |
| Andreza M. C. Falcao, Filipe R. Cordeiro | [Data Augmentation Improves Machine Unlearning](https://doi.org/10.1109/SIBGRAPI67909.2025.11223373) | SIBGRAPI Conference on Graphics, Patterns and Images | Vision | — | 1 |
| Subhodip Panda et al. | [Unlearning in Diffusion models under Data Constraints: A Variational Inference Approach](https://arxiv.org/abs/2510.04058) | TMLR | Diffusion | [GitHub](https://github.com/Subhodip123/VDU) | 1 |
| G. Nahass et al. | [Targeted Unlearning Using Perturbed Sign Gradient Methods With Applications On Medical Images](https://doi.org/10.48550/arXiv.2505.21872) | TMLR | Vision | — | 1 |
| Yuhe Leng et al. | [FedSSU: flexible and efficient decentralized unlearning for federated learning](https://doi.org/10.1007/s11227-025-07478-2) | The Journal of Supercomputing | Federated | — | 1 |
| Kongyang Chen et al. | [Optimizing Federated Incremental Learning: Efficient Malicious Data Removal for Big Data Analytics](https://doi.org/10.26599/tst.2025.901002) | Tsinghua Science & Technology | Federated | — | 1 |
| Lu Wei, Yuta Nakashima, Noa García | [EMMA: Concept Erasure Benchmark with Comprehensive Semantic Metrics and Diverse Categories](https://doi.org/10.48550/arXiv.2512.17320) | arXiv | Diffusion | [GitHub](https://github.com/lobsterlulu/EMMA) | 1 |
| Biswas, Shristi Das, Roy, Arani, Roy, Kaushik | [Now You See It, Now You Don't - Instant Concept Erasure for Safe Text-to-Image and Video Generation](https://doi.org/10.48550/arXiv.2511.18684) | arXiv | Diffusion | — | 1 |
| Carla Crivoi, R. Ionescu | [Machine Unlearning in the Era of Quantum Machine Learning: An Empirical Study](https://doi.org/10.48550/arXiv.2512.19253) | arXiv | Other | [GitHub](https://github.com/CrivoiCarla/HQML) | 1 |
| Bokang Zhang et al. | [FedSGT: Exact Federated Unlearning via Sequential Group-based Training](https://doi.org/10.48550/arXiv.2511.23393) | arXiv | Federated | [GitHub](https://github.com/deucalionAlpha/FedSGT) | 1 |
| Antoine Boutet, Lucas Magnana | [Leverage Unlearning to Sanitize LLMs](https://doi.org/10.48550/arXiv.2510.21322) | arXiv | LLM | [HF](https://huggingface.co/dslim/bert-base-NER) | 1 |
| Kodai Kawamura et al. | [Approximate Domain Unlearning for Vision-Language Models](https://doi.org/10.48550/arXiv.2510.08132) | arXiv | Vision | [GitHub](https://github.com/kodaikawamura/domain-unlearning) | 1 |
| Wenhan Wu et al. | [Beyond Sharp Minima: Robust LLM Unlearning via Feedback-Guided Multi-Point Optimization](https://doi.org/10.48550/arXiv.2509.20230) | arXiv | LLM | — | 1 |
| Qitan Shi et al. | [ReTrack: Data Unlearning in Diffusion Models through Redirecting the Denoising Trajectory](https://doi.org/10.48550/arXiv.2509.13007) | arXiv | Diffusion | [GitHub](https://github.com/sqt24/ReTrack) | 1 |
| Betty Mayeku, Sandra Hummel, Parisa Memarmoshrefi | [Machine Unlearning for Responsible and Adaptive AI in Education](https://doi.org/10.48550/arXiv.2509.10590) | arXiv | Other | — | 1 |
| A. Balordi et al. | [Tackling Federated Unlearning as a Parameter Estimation Problem](https://doi.org/10.48550/arXiv.2508.19065) | arXiv | Federated | [GitHub](https://github.com/lorenzomanini/FedUnlearn-PE) | 1 |
| Nicolò Romandini et al. | [FedUP: Efficient Pruning-based Federated Unlearning for Model Poisoning Attacks](https://doi.org/10.48550/arXiv.2508.13853) | arXiv | Federated | — | 1 |
| Xindi Fan et al. | [IMU: Influence-guided Machine Unlearning](https://doi.org/10.48550/arXiv.2508.01620) | arXiv | Other | [GitHub](https://github.com/goodluckisallyouneed/IMU) | 1 |
| Josep Domingo-Ferrer, N. Jebreel, David S'anchez | [Efficient Unlearning with Privacy Guarantees](https://doi.org/10.48550/arXiv.2507.04771) | arXiv | Other | [GitHub](https://github.com/najeebjebreel/EUPG) | 1 |
| Soumya Roy et al. | [NOVO: Unlearning-Compliant Vision Transformers](https://doi.org/10.48550/arXiv.2507.03281) | arXiv | Vision | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 1 |
| Yian Wang, Ali Ebrahimpour Boroojeny, Hari Sundaram | [On the Necessity of Output Distribution Reweighting for Effective Class Unlearning](https://doi.org/10.48550/arXiv.2506.20893) | arXiv | Vision | — | 1 |
| Prabhav Sanga, Jaskaran Singh, A. K. Dubey | [Train Once, Forget Precisely: Anchored Optimization for Efficient Post-Hoc Unlearning](https://doi.org/10.48550/arXiv.2506.14515) | arXiv | Vision | — | 1 |
| Yuwen Tan, Boqing Gong | [Lifting Data-Tracing Machine Unlearning to Knowledge-Tracing for Foundation Models](https://doi.org/10.48550/arXiv.2506.11253) | arXiv | LLM | — | 1 |
| Liou Tang, James B. D. Joshi, Ashish Kundu | [Apollo: A Posteriori Label-Only Membership Inference Attack Towards Machine Unlearning](https://doi.org/10.48550/arXiv.2506.09923) | arXiv | Other | — | 1 |
| Jacob L. Block, Aryan Mokhtari, Sanjay Shakkottai | [Machine Unlearning under Overparameterization](https://doi.org/10.48550/arXiv.2505.22601) | arXiv | Other | [GitHub](https://github.com/jacob-block/overparameterized-unlearning) | 1 |
| Le Ma et al. | [Losing is for Cherishing: Data Valuation Based on Machine Unlearning and Shapley Value](https://doi.org/10.48550/arXiv.2505.16147) | arXiv | Other | — | 1 |
| Hanyu Duan et al. | [Ready2Unlearn: A Learning-Time Approach for Preparing Models with Future Unlearning Readiness](https://doi.org/10.48550/arXiv.2505.10845) | arXiv | Other | [HF](https://huggingface.co/meta-llama/Llama-3.2-1B) | 1 |
| Yaxian Hu, Bernhard Scholkopf, Amartya Sanyal | [Online Learning and Unlearning](https://doi.org/10.48550/arXiv.2505.08557) | arXiv | Other | — | 1 |
| Abha Jha et al. | [Backdoor Defense in Diffusion Models via Spatial Attention Unlearning](https://doi.org/10.48550/arXiv.2504.18563) | arXiv | Diffusion | — | 1 |
| Xiaohua Feng et al. | [A Neuro-inspired Interpretation of Unlearning in Large Language Models through Sample-level Unlearning Difficulty](https://doi.org/10.48550/arXiv.2504.06658) | arXiv | LLM | [GitHub](https://github.com/unitaryai/detoxify) | 1 |
| Mahabub Uz Zaman, Xiang Sun, Jingjing Yao | [Sky of Unlearning (SoUL): Rewiring Federated Machine Unlearning via Selective Pruning](https://doi.org/10.48550/arXiv.2504.01705) | arXiv | Federated | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 1 |
| H. Lee et al. | [Node-level Contrastive Unlearning on Graph Neural Networks](https://doi.org/10.48550/arXiv.2503.02959) | arXiv | Graph | — | 1 |
| Bo Yang | [CE-U: Cross Entropy Unlearning](https://doi.org/10.48550/arXiv.2503.01224) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Weipeng Jiang et al. | [Holistic Audit Dataset Generation for LLM Unlearning via Knowledge Graph Traversal and Redundancy Removal](https://doi.org/10.48550/arXiv.2502.18810) | arXiv | LLM | — | 1 |
| Huawei Lin et al. | [Online Gradient Boosting Decision Tree: In-Place Updates for Efficient Adding/Deleting Data](https://doi.org/10.48550/arXiv.2502.01634) | arXiv | Other | [GitHub](https://github.com/huawei-lin/InplaceOnlineGBDT) | 1 |
| Mingliang Hou et al. | [PrivacyCD: Hierarchical Unlearning for Protecting Student Privacy in Cognitive Diagnosis](https://doi.org/10.48550/arXiv.2511.03966) | arXiv | Other | — | 1 |
| Mingliang Hou et al. | [P-MIA: A Profiled-Based Membership Inference Attack on Cognitive Diagnosis Models](https://doi.org/10.48550/arXiv.2511.04716) | arXiv | Other | — | 1 |
| Tomoya Yamashita et al. | [Sparse-Autoencoder-Guided Internal Representation Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2509.15631) | arXiv | LLM | [GitHub](https://github.com/tatsu-lab/alpaca) | 1 |
| Ittai Rubinstein, Samuel B. Hopkins | [Rescaled Influence Functions: Accurate Data Attribution in High Dimension](https://doi.org/10.48550/arXiv.2506.06656) | arXiv | Other | [GitHub](https://github.com/AriESQ/stars) | 1 |
| Yisheng Zhong, Zhengbang Yang, Zhuangdi Zhu | [Hierarchical Federated Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2510.17895) | arXiv | Federated | — | 1 |
| Hang Chen et al. | [CLUE: Conflict-guided Localization for LLM Unlearning Framework](https://doi.org/10.48550/arXiv.2509.20977) | arXiv | LLM | [GitHub](https://github.com/Zodiark-ch/CLUE) | 1 |
| Tomoya Yamashita et al. | [Concept Unlearning in Large Language Models via Self-Constructed Knowledge Triplets](https://doi.org/10.48550/arXiv.2509.15621) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Jiaxing Miao et al. | [CUFG: Curriculum Unlearning Guided by the Forgetting Gradient](https://doi.org/10.48550/arXiv.2509.14633) | arXiv | Vision | [GitHub](https://github.com/JiaxingMiao606/CUFG) | 1 |
| Jinwei Hu et al. | [FALCON: Fine-grained Activation Manipulation by Contrastive Orthogonal Unalignment for Large Language Model](https://doi.org/10.48550/arXiv.2502.01472) | arXiv | LLM | [GitHub](https://github.com/CharlesJW222/FALCON) | 1 |
| Agnieszka Polowczyk et al. | [Memory Self-Regeneration: Uncovering Hidden Knowledge in Unlearned Models](https://doi.org/10.48550/arXiv.2510.03263) | arXiv | Diffusion | [GitHub](https://github.com/gmum/MemoRa) | 1 |
| Taozhao Chen et al. | [Feature-Selective Representation Misdirection for Machine Unlearning](https://doi.org/10.48550/arXiv.2512.16297) | arXiv | LLM | — | 1 |
| Hadi Reisizadeh et al. | [Leak@k: Unlearning Does Not Make LLMs Forget Under Probabilistic Decoding](https://doi.org/10.48550/arXiv.2511.04934) | arXiv | LLM | [HF](https://huggingface.co/Jiajunruan/NPO-Fix) | 1 |
| Kyomin Hwang et al. | [Uncovering the Potential Risks in Unlearning: Danger of English-only Unlearning in Multilingual LLMs](https://doi.org/10.48550/arXiv.2510.23949) | arXiv | LLM | — | 1 |
| Sungjun Cho et al. | [Reference-Specific Unlearning Metrics Can Hide the Truth: A Reality Check](https://doi.org/10.48550/arXiv.2510.12981) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Ameya Anjarlekar, S. Pombra | [LLM Unlearning using Gradient Ratio-Based Influence Estimation and Noise Injection](https://doi.org/10.48550/arXiv.2508.06467) | arXiv | LLM | [HF](https://huggingface.co/datasets/allenai/c4) | 1 |
| Dunyuan Xu et al. | [From Learning to Unlearning: Biomedical Security Protection in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2508.04192) | arXiv | LLM | — | 1 |
| Philipp Spohn et al. | [Align-then-Unlearn: Embedding Alignment for LLM Unlearning](https://doi.org/10.48550/arXiv.2506.13181) | arXiv | LLM | [GitHub](https://github.com/ExplainableML/align-then-unlearn) | 1 |
| Evelyn Ma et al. | [GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models](https://doi.org/10.48550/arXiv.2506.10946) | arXiv | LLM | — | 1 |
| Jan Bronec et al. | [Atyaephyra at SemEval-2025 Task 4: Low-Rank Negative Preference Optimization](https://arxiv.org/abs/2503.13690) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Arpit Garg et al. | [Stable Forgetting: Bounded Parameter-Efficient Unlearning in LLMs](https://doi.org/10.48550/arXiv.2509.24166) | arXiv | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 1 |
| Jan Bronec, Jindrich Helcl | [Atyaephyra at SemEval-2025 Task 4: Low-Rank NPO](https://doi.org/10.48550/arXiv.2503.13690) | arXiv | LLM | [GitHub](https://github.com/HhhannahhhCl/unlearningLLMs) | 1 |
| Hongji Li et al. | [Towards Reasoning-Preserving Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2512.17911) | arXiv | LLM | — | 1 |
| Timothy Qian et al. | [Layered Unlearning for Adversarial Relearning](https://doi.org/10.48550/arXiv.2505.09500) | arXiv | LLM | [GitHub](https://github.com/JasxnNg/6.7960-final) | 1 |
| Ana-Maria Creţu et al. | [Evaluating Concept Filtering Defenses against Child Sexual Abuse Material Generation by Text-to-Image Models](https://doi.org/10.48550/arXiv.2512.05707) | arXiv | Diffusion | [GitHub](https://github.com/spring-epfl/t2i-chi) | 1 |
| Mohammed Talha Alam et al. | [SPQR: A Standardized Benchmark for Modern Safety Alignment Methods in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2511.19558) | arXiv | Diffusion | [GitHub](https://github.com/talha-alam/spqr) | 1 |
| Ning Han et al. | [GrOCE:Graph-Guided Online Concept Erasure for Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2511.12968) | arXiv | Diffusion | [GitHub](https://github.com/MagicCat-AI/GrOCE) | 1 |
| Tong Zhang et al. | [Beyond Fixed Anchors: Precisely Erasing Concepts with Sibling Exclusive Counterparts](https://doi.org/10.48550/arXiv.2510.16342) | arXiv | Diffusion | — | 1 |
| Nanxiang Jiang et al. | [Erased, But Not Forgotten: Erased Rectified Flow Transformers Still Remain Unsafe Under Concept Attack](https://doi.org/10.48550/arXiv.2510.00635) | arXiv | Diffusion | [GitHub](https://github.com/nxjiang-jnx/ReFlux) | 1 |
| Enrico Cassano et al. | [SAEmnesia: Erasing Concepts in Diffusion Models with Supervised Sparse Autoencoders](https://arxiv.org/abs/2509.21379) | arXiv | Diffusion | — | 1 |
| Feng Han et al. | [VCE: Safe Autoregressive Image Generation via Visual Contrast Exploitation](https://doi.org/10.48550/arXiv.2509.16986) | arXiv | Diffusion | [GitHub](https://github.com/Maplebb/VCE) | 1 |
| Zixuan Fu et al. | [Robust Concept Erasure in Diffusion Models: A Theoretical Perspective on Security and Robustness](https://doi.org/10.48550/arXiv.2509.12024) | arXiv | Diffusion | — | 1 |
| Jinju Kim et al. | [No Encore: Unlearning as Opt-Out in Music Generation](https://doi.org/10.48550/arXiv.2509.06277) | arXiv | Other | [GitHub](https://github.com/mokcho/mokcho) | 1 |
| Eric C. Yeats et al. | [Automating Evaluation of Diffusion Model Unlearning with (Vision-) Language Model World Knowledge](https://doi.org/10.48550/arXiv.2507.07137) | arXiv | Diffusion | — | 1 |
| Haipeng Fan et al. | [EAR: Erasing Concepts from Unified Autoregressive Models](https://doi.org/10.48550/arXiv.2506.20151) | arXiv | Diffusion | [GitHub](https://github.com/immc-lab/ear) | 1 |
| Feng He et al. | [How Robust is Model Editing after Fine-Tuning? An Empirical Study on Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2506.18428) | arXiv | Diffusion | [HF](https://huggingface.co/datasets/lambdalabs) | 1 |
| Hongguang Zhu et al. | [SAGE: Exploring the Boundaries of Unsafe Concept Domain with Semantic-Augment Erasing](https://doi.org/10.48550/arXiv.2506.09363) | arXiv | Diffusion | [GitHub](https://github.com/KevinLight831/SAGE) | 1 |
| Simone Facchiano et al. | [Video Unlearning via Low-Rank Refusal Vector](https://doi.org/10.48550/arXiv.2506.07891) | arXiv | Diffusion | [GitHub](https://github.com/simonefacchiano/Video-Unlearning) | 1 |
| Siyi Chen et al. | [The Dual Power of Interpretable Token Embeddings: Jailbreaking Attacks and Defenses for Diffusion Model Unlearning](https://doi.org/10.48550/arXiv.2504.21307) | arXiv | Diffusion | [GitHub](https://github.com/YiweiXie/Awesome-Comprehensive-Concept-Suppression) | 1 |
| Die Chen et al. | [Comprehensive Assessment and Analysis for NSFW Content Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2502.12527) | arXiv | Diffusion | [GitHub](https://github.com/lzws/ErasureBenchmark) | 1 |
| Zhenyu Yu, Mohd. Yamani Idna Idris, Pei Wang | [Prompt-Driven and Training-Free Forgetting Approach and Dataset for Large Language Models](https://doi.org/10.48550/arXiv.2504.12574) | arXiv | LLM | — | 1 |
| Enrico Cassano et al. | [SAEmnesia: Erasing Concepts in Diffusion Models with Sparse Autoencoders](https://doi.org/10.48550/arXiv.2509.21379) | arXiv | Diffusion | — | 1 |
| Anudeep Das et al. | [Do Concept Replacement Techniques Really Erase Unacceptable Concepts?](https://doi.org/10.48550/arXiv.2506.08991) | arXiv | Diffusion | [GitHub](https://github.com/DataSmithLab/Moderator) | 1 |
| Zhengyu Fang et al. | [A Closer Look on Memorization in Tabular Diffusion Model: A Data-Centric Perspective](https://doi.org/10.48550/arXiv.2505.22322) | arXiv | Diffusion | — | 1 |
| Filip Sondej, Yushi Yang | [Collapse of Irrelevant Representations (CIR) Ensures Robust and Non-Disruptive LLM Unlearning](https://doi.org/10.48550/arXiv.2509.11816) | arXiv | LLM | [HF](https://huggingface.co/datasets/m-a-p) | 1 |
| Feng Han et al. | [DuMo: Dual Encoder Modulation Network for Precise Concept Erasure](https://doi.org/10.1609/aaai.v39i3.32343) | AAAI | Diffusion | [GitHub](https://github.com/Maplebb/DuMo) | 0 |
| Xiafeng Man, Zhipeng Wei, Jingjing Chen | [Copyright Infringement Detection in Text-to-Image Diffusion Models via Differential Privacy](https://doi.org/10.48550/arXiv.2509.23022) | AAAI | Diffusion | — | 0 |
| Xue Jiang et al. | [Large Language Model Unlearning for Source Code](https://doi.org/10.48550/arXiv.2506.17125) | AAAI | LLM | [GitHub](https://github.com/dinhngoctuyen4125/PROD_test) | 0 |
| Chao-Hui He et al. | [Forgetting by Pruning: Data Deletion in Join Cardinality Estimation](https://doi.org/10.48550/arXiv.2511.20293) | AAAI | Other | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Feng Guo et al. | [Beyond Superficial Forgetting: Thorough Unlearning through Knowledge Density Estimation and Block Re-insertion](https://doi.org/10.48550/arXiv.2511.11667) | AAAI | LLM | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Fuyao Zhang et al. | [Oblivionis: A Lightweight Learning and Unlearning Framework for Federated Large Language Models](https://doi.org/10.48550/arXiv.2508.08875) | AAAI | Federated | [GitHub](https://github.com/fyzhang1/Oblivionis) | 0 |
| Wenhan Wu et al. | [REMISVFU: Vertical Federated Unlearning via Representation Misdirection for Intermediate Output Feature](https://doi.org/10.48550/arXiv.2512.10348) | AAAI | Federated | — | 0 |
| Tianle Gu et al. | [From Evasion to Concealment: Stealthy Knowledge Unlearning for LLMs](https://doi.org/10.18653/v1/2025.findings-acl.535) | ACL | LLM | — | 0 |
| S. Vasilev et al. | [UvA-DARE (Digital Academic Repository) Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target Self-Distillation](https://www.semanticscholar.org/paper/97ba9e39c1d2969b354b0cd3fcdc39dc253bf576) | ACL | LLM | — | 0 |
| Fan Qi et al. | [FORGET ME: Federated Unlearning for Face Generation Models](https://doi.org/10.1145/3746027.3754935) | ACM MM | Federated | [GitHub](https://github.com/FanQi-AI/FFGU) | 0 |
| Rutger Hendrix et al. | [Pre-Forgettable Models: Prompt Learning as a Native Mechanism for Unlearning](https://doi.org/10.1145/3746027.3758171) | ACM MM | Vision | [GitHub](https://github.com/perceivelab/PreForgettableModels) | 0 |
| Muhammad Shaheryar, Jong Taek Lee, Soon Ki Jung | [Unlearn and Protect: Selective Identity Removal in Diffusion Models for Privacy Preservation](https://doi.org/10.1145/3672608.3707842) | ACM Symposium on Applied Computing | Diffusion | — | 0 |
| Christian Troiani et al. | [Federated Unlearning using Tree-based Sharding](https://doi.org/10.1145/3733799.3762971) | AISec@CCS | Federated | — | 0 |
| Virgile Dine, Teddy Furon, Charly Faure | [Improving Unlearning with Model Updates Probably Aligned with Gradients](https://doi.org/10.1145/3733799.3762975) | AISec@CCS | Vision | [GitHub](https://github.com/owl1996/UnlearningFocusVector) | 0 |
| Giuseppe Gallipoli, Luca Cagliero | [In-Context Unlearning for Text Summarization using Large Language Models](https://doi.org/10.1109/AICT67988.2025.11268691) | Advanced Industrial Conference on Telecommunications | LLM | — | 0 |
| Fengda Zhao et al. | [Rapid federated unlearning with tuning parameters based on fisher information matrix](https://doi.org/10.1007/s10489-025-06593-0) | Applied Intelligence | Federated | — | 0 |
| Jing Zhang et al. | [CAUA: A Realistic and Effective Attack on Machine Unlearning Under Limited Information](https://doi.org/10.1109/ACSAC67867.2025.00080) | Asia-Pacific Computer Systems Architecture Conference | Other | [GitHub](https://github.com/ballinyz/CAUA-A-Realistic-and-Effective-Attack-on-Machine-Unlearning-under-Limited-Information-artifact) | 0 |
| Lei Cen, Guohao Li, Li Yang | [A Scenario-Driven Efficient Federated Unlearning Method for Multi-Granularity Data Removal](https://doi.org/10.1109/BigDIA68682.2025.11383040) | BigDIA | Federated | — | 0 |
| Yiming Li et al. | [Merging Erasure and Retention for Balanced Graph Unlearning](https://doi.org/10.1109/cac67268.2025.11486964) | CAC | Graph | — | 0 |
| Ebuka Chinaechetam Nkoro et al. | [Towards a Privacy Preserving Framework for Mobility as a Service (MaaS)](https://doi.org/10.1109/CIEES66347.2025.11300101) | CIEES | Other | — | 0 |
| Preethi Gurumurthy, P. K. Srijith | [Pseudo-Inverse Prefix Tuning for Effective Unlearning in LLMs](https://doi.org/10.1145/3746252.3760939) | CIKM | LLM | — | 0 |
| Sangjun Chung, Simon S. Woo | [MU-OT: Effective and Unified Machine Unlearning with Optimal Transport for Feature Realignment](https://doi.org/10.1145/3746252.3760915) | CIKM | Vision | — | 0 |
| Nexhi Sula et al. | [Silver Linings in the Shadows: Harnessing Membership Fingerprinting for Machine Unlearning](https://doi.org/10.1109/CNS66487.2025.11195030) | CNS | Other | — | 0 |
| Jundong Chen et al. | [Learning to Unlearn for Bayesian Personalized Ranking via Influence Function](https://doi.org/10.23919/cje.2023.00.417) | Chinese Journal of Electronics | Recsys | — | 0 |
| Yifei Zou et al. | [Conditional Machine Unlearning: Balancing Privacy and Regulation](https://doi.org/10.23919/cje.2024.00.343) | Chinese journal of electronics | Other | — | 0 |
| Enting Guo, Chunhua Su, Peng Li | [Efficient unlearning for data security in deep learning systems](https://doi.org/10.1093/comjnl/bxaf031) | Computer/law journal | Other | — | 0 |
| Long Cai, Ke Gu, Jiaqi Lei | [Defending Federated Learning System from Poisoning Attacks via Efficient Unlearning](https://doi.org/10.32604/cmc.2025.061377) | Computers, Materials &amp; Continua | Federated | — | 0 |
| R. Karn et al. | [Unlearning in Decision Tree Classifiers and Microcontroller Implementations](https://doi.org/10.1109/CAI64502.2025.00114) | Conference on Algebraic Informatics | Other | — | 0 |
| Jin Huang et al. | [Prompt-Tuning for Recommendation Unlearning](https://doi.org/10.1109/CAI64502.2025.00152) | Conference on Algebraic Informatics | Recsys | — | 0 |
| Ashley Etheridge et al. | [Tackling Sequential Entanglement in Split Unlearning](https://doi.org/10.1109/MIPR67560.2025.00053) | Conference on Multimedia Information Processing and Retrieval | Federated | [GitHub](https://github.com/AshleyJoyE/Split-Unlearning) | 0 |
| Xiaocui Dang et al. | [A Novel Scheme for Recommendation Unlearning Verification (RUV) Using Non-Influential Trigger Data](https://doi.org/10.1109/CCNC54725.2025.10976014) | Consumer Communications and Networking Conference | Recsys | — | 0 |
| Vishal Balasubramanian, Amna Shifa, M. Asghar | [Machine Unlearning for ensuring Compliance and Governance in Vision AI](https://doi.org/10.1109/Cyber-RCI68134.2025.11384951) | Cyber-RCI | Vision | — | 0 |
| Xinyi Sun et al. | [Unlearning the Spurious Correlations for Improving Generalization of Language Models](https://doi.org/10.3724/2096-7004.di.2025.0180) | Data Intelligence | LLM | — | 0 |
| Hrishikesh Kulkarni, Nazli Goharian, O. Frieder | [GUIR at SemEval-2025 Task 4: Adaptive Weight Tuning with Gradual Negative Matching for LLM Unlearning](https://www.semanticscholar.org/paper/5c80117ab9edc3cc7a8140646081a7dcb4fa0ac9) | ECIR (3) | LLM | — | 0 |
| Advit Deepak et al. | [Identifying Unlearned Data in LLMs via Membership Inference Attacks](https://doi.org/10.18653/v1/2025.emnlp-main.551) | EMNLP | LLM | [GitHub](https://github.com/AdvitDeepak/fuma) | 0 |
| Yixin Wan et al. | [Not Every Token Needs Forgetting: Selective Unlearning Balancing Forgetting and Utility in Large Language Models](https://doi.org/10.18653/v1/2025.findings-emnlp.96) | EMNLP | LLM | — | 0 |
| Bang Trinh Tran To, Thái Hoàng Lê | [Harry Potter is Still Here! Probing Knowledge Leakage in Targeted Unlearned Large Language Models](https://doi.org/10.18653/v1/2025.findings-emnlp.778) | EMNLP | LLM | [GitHub](https://github.com/Rachel1809/LURK) | 0 |
| Anda Cheng, Wei Huang, Yinggui Wang | [A Fully Probabilistic Perspective on Large Language Model Unlearning: Evaluation and Optimization](https://doi.org/10.18653/v1/2025.emnlp-main.452) | EMNLP | LLM | — | 0 |
| Linxi Xie et al. | [Reveal and Release: Iterative LLM Unlearning with Self-generated Data](https://doi.org/10.48550/arXiv.2509.14624) | EMNLP | LLM | [GitHub](https://github.com/LafouCC/Reveal-and-Release) | 0 |
| Shiji Yang et al. | [Forget the Unneeded: Backdooring Large Language Models via Contrastive-enhanced Machine Unlearning](https://doi.org/10.18653/v1/2025.findings-emnlp.1338) | EMNLP | LLM | — | 0 |
| Alexander Krawczyk, Alex Gepperth | [Continual Unlearning through Memory Suppression](https://doi.org/10.14428/esann/2025.es2025-102) | ESANN proceesdings | Vision | [GitHub](https://github.com/Alexk1704/scclv2) | 0 |
| Andrea Ruggieri | [Using Membership Inference Attack as an evaluation metric for Privacy Preserving Machine Unlearning](https://openalex.org/W7124820729) | Electronic Theses and Dissertations Repository (University of Pisa) | Vision | — | 0 |
| H. N. Tran et al. | [FAST: A pioneering unlearning framework integrating fine-tuning, adverse training, and student–teacher methods](https://doi.org/10.1016/j.jestch.2025.101996) | Engineering Science and Technology, an International Journal | Other | — | 0 |
| Shao Shen et al. | [Machine Unlearning for Streaming Forgetting](https://doi.org/10.48550/arXiv.2507.15280) | European Conference on Artificial Intelligence | Other | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 0 |
| Sümeye Nur Karahan et al. | [Semantic Communication Unlearning: A Variational Information Bottleneck Approach for Backdoor Defense in Wireless Systems](https://doi.org/10.3390/fi18010017) | Future Internet | Other | — | 0 |
| Jinyung Hong et al. | [Enhancing Graph Unlearning with Semantic and Structural Counterfactual Distillation](https://doi.org/10.1109/GLOBECOM59602.2025.11432697) | Global Communications Conference | Graph | — | 0 |
| Shohei Yamamoto, Soh Yoshida, M. Muneyasu | [Robust Image Classification via Centroid-Aware Machine Unlearning of Noisy Annotations](https://doi.org/10.1109/GCCE65946.2025.11275131) | Global Conference on Consumer Electronics | Vision | — | 0 |
| M. Jonathan, Windy Gambetta | [A Comparative Study of Nabla Tau and SCAR Unlearning Algorithms for CNN-Based Facial Race Classification](https://doi.org/10.1109/ICAICTA67604.2025.11335106) | ICAICTA | Vision | — | 0 |
| Zhifei Luo et al. | [Signed Graph Unlearning](https://doi.org/10.48550/arXiv.2510.26092) | ICASSP | Graph | — | 0 |
| Nicolas Renout et al. | [Fast Unlearning Techniques for Neural Network Prediction and Classification Algorithms](https://doi.org/10.1109/ICC52391.2025.11161398) | ICC | Other | — | 0 |
| Urbana Jaman Orthee et al. | [Efficient Data Erasure in Deep Learning via Sparsity and Stability Mechanisms](https://doi.org/10.1109/ICCIT68739.2025.11491062) | ICCIT | Vision | — | 0 |
| K. Thakral et al. | [Genμ: The Generative Machine Unlearning Challenge](https://doi.org/10.1109/ICCVW69036.2025.00266) | ICCV | Diffusion | — | 0 |
| Hongyi Nie et al. | [E RASING C ONCEPT C OMBINATIONS FROM T EXT - TO - I MAGE D IFFUSION M ODEL](https://www.semanticscholar.org/paper/3bfe72f50d55b4050b9b2155c70ef3f1da781ca7) | ICCV | Diffusion | — | 0 |
| Yuhao Sun et al. | [Invisible Watermarks, Visible Gains: Steering Machine Unlearning with Bi-Level Watermarking Design](https://doi.org/10.1109/ICCV51701.2025.00233) | ICCV | Vision | — | 0 |
| Hyun Jun Yook et al. | [ZIUM: Zero-Shot Intent-Aware Adversarial Attack on Unlearned Models](https://doi.org/10.1109/ICCV51701.2025.00374) | ICCV | Diffusion | — | 0 |
| Alexey Kravets, Da Chen, Vinay P. Namboodiri | [Rethinking Few Shot CLIP Benchmarks: A Critical Analysis in the Inductive Setting](https://doi.org/10.1109/ICCV51701.2025.00185) | ICCV | Vision | [GitHub](https://github.com/akres001/Rethinking-Few-Shot-CLIP-Benchmarks-A-Critical-Analysis-in-the-Inductive-Setting) | 0 |
| Eunseo Koh et al. | [Translation of Text Embedding Via Delta Vector to Suppress Strongly Entangled Content in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICCV51701.2025.01425) | ICCV | Diffusion | — | 0 |
| Anant Gupta et al. | [Self-Erasing Neural Networks (SENNs): A Neurogenesis-Inspired Framework for GDPR-Compliant Machine Unlearning](https://doi.org/10.1109/ICDDS67737.2025.11344675) | ICDDS | Other | — | 0 |
| Xiaohua Feng et al. | [Controllable Unlearning for Image-to-Image Generative Models via ϵ-Constrained Optimization](https://doi.org/10.48550/arXiv.2408.01689) | ICLR | Diffusion | — | 0 |
| Yahya Alkhatib, Muhammad Jamal, Wee Peng Tay | [Conformal Unlearning: A New Paradigm for Unlearning in Conformal Predictors](https://arxiv.org/abs/2508.03245) | ICLR Conference Withdrawn Submission | Other | [GitHub](https://github.com/chenyaofo/pytorch-cifar-models) | 0 |
| Youssef Allouah, R. Guerraoui, Sanmi Koyejo | [Distributional Machine Unlearning via Selective Data Removal](https://arxiv.org/abs/2507.15112) | ICLR Poster | LLM | [GitHub](https://github.com/ysfalh/unlearning-distribution) | 0 |
| Keivan Rezaei et al. | [Revisiting the Past: Data Unlearning with Model State History](https://arxiv.org/abs/2506.20941) | ICLR Poster | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| Puwei Lian et al. | [Achieving Zero-Glance Unlearning with Data-Free Inversion and Selective Parameters Suppression](https://doi.org/10.1109/ICME59968.2025.11209383) | ICME | Vision | — | 0 |
| Haoxuan Ji et al. | [Towards Aligned Data Forgetting via Twin Machine Unlearning](https://doi.org/10.1109/ICME59968.2025.11208918) | ICME | Vision | [GitHub](https://github.com/abc321123444/TWIN-unlearning) | 0 |
| Yufan Liu et al. | [Corer: Concept Residue Erasing in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICME59968.2025.11210155) | ICME | Diffusion | — | 0 |
| Haodong Zhang, Liu Yang, Zihan Jiang | [RKU: Relevant Knowledge-aware Unlearning for Federated Continual Learning](https://doi.org/10.1109/ICME59968.2025.11210106) | ICME | Federated | [GitHub](https://github.com/zhanghad/RKU) | 0 |
| Ye He, Wei Jiang, Bin Wang | [SCFU: A Collaborative Federated Unlearning Algorithm with Weighted Penalty and Adaptive Rewards](https://doi.org/10.1109/icpads67057.2025.11323166) | ICPADS | Federated | — | 0 |
| Jinghan Xu et al. | [GAIA-UL: Surgical Unlearning of Visual Knowledge via Causally-Guided Orthogonalization](https://doi.org/10.1109/ICPADS67057.2025.11323156) | ICPADS | LLM | — | 0 |
| Siyun Guo, Leixiao Li, Jinze Du | [Joint-FU: Blockchain-Based Federated Feature Unlearning Method](https://doi.org/10.1109/ICPADS67057.2025.11322875) | ICPADS | Federated | — | 0 |
| Shrutika Gupta et al. | [Integrating k-Means++ with ARCANE: A Scalable Framework for Exact Cluster Unlearning](https://doi.org/10.1109/ICRCICN68210.2025.11364795) | ICRCICN | Other | — | 0 |
| Sheetal Sehgal, Himani Bansal, Ankita Verma | [Extending GraphEraser: Scalable and Secure Partition-Based Graph Unlearning on Large-Scale Network](https://doi.org/10.1109/ICTBIG68706.2025.11323936) | ICTBIG | Graph | — | 0 |
| Natalie Lang, Alon Helvits, Nir Shlezinger | [Memory-Efficient Distributed Unlearning](https://doi.org/10.1109/ACCESS.2026.3663428) | IEEE Access | Federated | [GitHub](https://github.com/alonhelvits/FedUL) | 0 |
| Win Kent Ong, Chee Seng Chan | [Maverick++: Collaboration-Free Unlearning for Medical Privacy Preservation in Healthcare Federated Systems](https://doi.org/10.1109/ACCESS.2025.3611992) | IEEE Access | Federated | [GitHub](https://github.com/OngWinKent/Maverick) | 0 |
| Hyun Kwon, Jang-Woon Baek | [A Targeted Machine Unlearning Method for Sensitive Data in Military Helicopter Models](https://doi.org/10.1109/ACCESS.2025.3631684) | IEEE Access | Vision | — | 0 |
| Qingyu Tan, Yan Li, Byeong‐Seok Shin | [LAFUL: Lesion-Aware Federated Unlearning via Channel-Wise Gradient Masking and Feature Distillation](https://doi.org/10.1109/bibm66473.2025.11357193) | IEEE International Conference on Bioinformatics and Biomedicine | Federated | — | 0 |
| Tejo Vardhan Kattamuri et al. | [Securing Federated Learning: Anomaly Detection and Mitigation via VAEs and Unlearning](https://doi.org/10.1109/CONECCT65861.2025.11306723) | IEEE International Conference on Electronics, Computing and Communication Technologies | Federated | — | 0 |
| Chenghao Shao et al. | [Feature Unlearning for EEG-Based Seizure Prediction](https://doi.org/10.1109/JIOT.2024.3514666) | IEEE IoT-J | Other | — | 0 |
| Maryam Shirmohammadi, Anik Islam, Hadis Karimipour | [An Intent-Based Networking Framework for Secure and Privacy-Compliant Machine Unlearning Using Meta-Learning and Redactable Blockchain](https://doi.org/10.1109/jiot.2025.3638966) | IEEE IoT-J | Other | — | 0 |
| Hai Anh Tran | [ULNet: Federated Unlearning for SDN Control-Plane Anomaly Detection](https://doi.org/10.1109/lnet.2025.3645209) | IEEE Networking Letters | Federated | — | 0 |
| Md Serajun Nabi, Dema Yuden, Mohammad Faizal Ahmad Fauzi | [Deepfake Detection Using ResNet50V2 with Machine Unlearning Integration](https://doi.org/10.1109/TENCON66050.2025.11375020) | IEEE Region 10 Conference | Vision | — | 0 |
| Chunyi Zhou et al. | [TruVRF: Toward Triple-Granularity Verification on Machine Unlearning](https://doi.org/10.1109/tifs.2025.3565991) | IEEE T-IFS | Other | — | 0 |
| Jiaquan Liang et al. | [Hypergraph Unlearning: A Size-Based Hyperedge Selection and Coverage Aggregation Approach](https://doi.org/10.1109/tifs.2025.3580218) | IEEE T-IFS | Graph | [GitHub](https://github.com/Alchemistqqqq/HyperGraph-Unlearning) | 0 |
| Chenxi Hu et al. | [Copyright Protection of General Information via Simulation Task Supervision](https://doi.org/10.1109/TIFS.2025.3638667) | IEEE T-IFS | LLM | — | 0 |
| Lei Zhou, Youwen Zhu | [Model Inversion Attack Against Federated Unlearning](https://doi.org/10.1109/TIFS.2026.3666295) | IEEE T-IFS | Federated | — | 0 |
| Sayedmoslem Shokrolahi, I.-M. Kim | [MaxDiv: Zero-Shot Machine Unlearning via Distributionally Divergent Erasing Samples](https://doi.org/10.1109/tai.2025.3627517) | IEEE TAI | Vision | — | 0 |
| Xinyi Sheng et al. | [FUBA: Backdoor Federated Learning via Federated Unlearning](https://doi.org/10.1109/tai.2025.3630110) | IEEE TAI | Federated | [GitHub](https://github.com/stcebra/FUBA) | 0 |
| Kun Gao et al. | [Hidden Threats in Federated Unlearning: Camouflaged Poisoning Attacks and Their Unlearning Consequences](https://doi.org/10.1109/tdsc.2025.3630811) | IEEE TDSC | Federated | — | 0 |
| Lefeng Zhang et al. | [Trojan Attack on Machine Unlearning: Security Risk of the Right to be Forgotten](https://doi.org/10.1109/TDSC.2025.3567848) | IEEE TDSC | Other | — | 0 |
| Zhigang Wang et al. | [FELEMN: Toward Efficient Feature-Level Machine Unlearning for Exact Privacy Protection](https://doi.org/10.1109/TKDE.2025.3613659) | IEEE TKDE | Other | — | 0 |
| Zhenwei Wang et al. | [Inverse Feature Consistency Federated Unlearning for Vision-Language Model](https://doi.org/10.1109/tmc.2025.3629294) | IEEE TMC | Federated | — | 0 |
| Juncheng Jia et al. | [Fed$n$nP: Federated Unlearning With Multiple Client Set Partitions](https://doi.org/10.1109/tmc.2025.3586441) | IEEE TMC | Federated | — | 0 |
| J. Jia et al. | [Fed<inline-formula><tex-math notation="LaTeX">$n$</tex-math><alternatives><mml:math><mml:mi>n</mml:mi></mml:math><inline-graphic xlink:href="jia-ieq1-3586441.gif"/></alternatives></inline-formula>P: Federated Unlearning With Multiple Client Set Partitions](https://doi.org/10.1109/TMC.2025.3586441) | IEEE TMC | Federated | — | 0 |
| Yue Cui, Man Hon Cheung | [The Price of Forgetting: Incentive Mechanism Design for Machine Unlearning](https://doi.org/10.1109/TMC.2025.3582904) | IEEE TMC | Other | — | 0 |
| Xiangyun Tang et al. | [LVFUS: Vertical Federated Unlearning for Intelligent Network Security via Adaptive Optimizer Switching](https://doi.org/10.1109/tnse.2025.3637602) | IEEE TNSE | Federated | — | 0 |
| Li Duan et al. | [FedHydra: towards Parameter-Efficient and Backdoor-Resistant Federated Unlearning in Human-Centric Metaverse Service](https://doi.org/10.1109/tsc.2025.3620758) | IEEE TSC | Federated | — | 0 |
| Jingyi Li et al. | [Efficient Federated Metric Learning and Machine Unlearning Based on Prototype Distillation](https://doi.org/10.1109/tsc.2025.3645435) | IEEE TSC | Federated | — | 0 |
| Yuhong Huang et al. | [FedUP: Federated Unlearning With Prototypes](https://doi.org/10.1109/tsusc.2025.3612138) | IEEE Transactions on Sustainable Computing | Federated | — | 0 |
| Yi Zhang et al. | [Hierarchical Dual-Strategy Unlearning for Biomedical and Healthcare Intelligence Using Imperfect and Privacy-Sensitive Medical Data](https://doi.org/10.48550/arXiv.2511.19498) | IEEE transactions on consumer electronics | LLM | — | 0 |
| Jiande Huang et al. | [MAFRO: Optimal-Granularity Fuzzy Decision Rule-Based Classification Architecture for Attribute Unlearning](https://doi.org/10.1109/TFUZZ.2025.3586297) | IEEE transactions on fuzzy systems | Other | — | 0 |
| Haitham Y. Adarbah, Kewei Sha, Afzel Noore | [Toward Design of a Scalable Federated Unlearning Framework for Trustworthy Edge Intelligence](https://doi.org/10.1145/3769102.3774631) | IFIP International Information Security Conference | Federated | — | 0 |
| Hongyi Lyu et al. | [Fine-Grained and Efficient Self-Unlearning with Layered Iteration](https://doi.org/10.24963/ijcai.2025/850) | IJCAI | Vision | [GitHub](https://github.com/Hongyi-Lyu-MQ/SULI) | 0 |
| Huiqiang Chen et al. | [Zero-Shot Machine Unlearning with Proxy Adversarial Data Generation](https://doi.org/10.48550/arXiv.2507.21738) | IJCAI | Vision | — | 0 |
| Zhihao Sui et al. | [COLUR: Confidence-Oriented Learning, Unlearning and Relearning with Noisy-Label Data for Model Restoration and Refinement](https://doi.org/10.48550/arXiv.2506.19496) | IJCAI | Other | — | 0 |
| Fnu Shivam et al. | [CURE: Centroid-guided Unsupervised Representation Erasure for Facial Recognition Systems](https://doi.org/10.1109/IJCB65343.2025.11410631) | IJCB | Vision | [GitHub](https://github.com/Shivam101s/CURE_FaceUnlearning) | 0 |
| Alessio Mora et al. | [Federated Unlearning in Healthcare: Why It Matters](https://doi.org/10.1109/ijcnn64981.2025.11228665) | IJCNN | Federated | [GitHub](https://github.com/alessiomora/medical) | 0 |
| Zhenkang Hu, Zhe Yang | [NPFGLU: Unlearning Links in Graph Neural Networks](https://doi.org/10.1109/IJCNN64981.2025.11228853) | IJCNN | Graph | — | 0 |
| Miaolin Xing et al. | [Towards Effective Edge Unlearning: Enhancing Graph Unlearning via Contrastive Learning with Adversarial Example](https://doi.org/10.1109/IJCNN64981.2025.11227397) | IJCNN | Graph | — | 0 |
| Changchun Yin, Liming Fang, Lu Zhou | [An Effective Approach to Class-Wise Unlearning in Pre-trained Encoders for Contrastive Learning](https://doi.org/10.1109/IJCNN64981.2025.11228327) | IJCNN | Vision | — | 0 |
| Boxu Xiao, Sijia Liu, Qing Ling | [Federated Unlearning with Oriented Saliency Compression](https://doi.org/10.1109/IJCNN64981.2025.11228643) | IJCNN | Federated | [GitHub](https://github.com/RadiumStar/FedUOSC) | 0 |
| Dong Liang et al. | [Backdoor Defense via Malicious Knowledge Capturing and Machine Unlearning with Out-of-Distribution Data](https://doi.org/10.1109/ijcnn64981.2025.11228380) | IJCNN | Vision | — | 0 |
| Zhe Liu | [Unlearning LLM-Based Speech Recognition Models](https://doi.org/10.21437/interspeech.2025-287) | INTERSPEECH | LLM | — | 0 |
| Haichao Zhang et al. | [Customized Retrieval-Augmented Generation with LLM for Debiasing Recommendation Unlearning](https://doi.org/10.1109/ICDM65498.2025.00183) | Industrial Conference on Data Mining | Recsys | [GitHub](https://github.com/zhanghaichao520/LLM_rec_unlearning) | 0 |
| Muhammad Usmani et al. | [Federated unlearning using diffusive noise injection](https://doi.org/10.1016/j.inffus.2025.103796) | Information Fusion | Federated | — | 0 |
| Maximilian Egger, Rawad Bitar, Rüdiger L. Urbanke | [Efficient Machine Unlearning by Model Splitting and Core Sample Selection](https://doi.org/10.1109/ITW62417.2025.11240389) | Information Theory Workshop | Other | — | 0 |
| Imran Ahsan, Hyunwook Yu, Mucheol Kim | [GNN Unlearning Reality Checklist (GURC): A Standard for Robust, Reproducible, and Privacy-Safe Evaluation](https://doi.org/10.1109/ictc66702.2025.11387905) | Information and Communication Technology Convergence | Graph | — | 0 |
| Thang Hiep Duc Tran, Thai Hoang Le | [WSS-CL: Weight Saliency Soft-Guided Contrastive Learning for Efficient Machine Unlearning Image Classification](https://doi.org/10.48550/arXiv.2508.04308) | International Conference on Computational Collective Intelligence | Vision | — | 0 |
| Anil Babu Bathula, Subba Rao Peram | [GAD-SISA: A Scalable Defense Against Label Flipping Attack](https://doi.org/10.1109/CICN67655.2025.11368228) | International Conference on Computational Intelligence and Communication Networks | Other | — | 0 |
| Yongpei Zhang et al. | [Rethinking Privacy Protection for Recommender System in a Collaborative Way](https://doi.org/10.1109/CSCWD64889.2025.11033239) | International Conference on Computer Supported Cooperative Work in Design | Recsys | — | 0 |
| A. Chahal et al. | [Efficient Machine Unlearning using Mislabel Unlearning](https://doi.org/10.1109/IC366947.2025.11290239) | International Conference on Contemporary Computing | Other | [GitHub](https://github.com/yatin-shrma/mislabel-unlearning) | 0 |
| Xuanming Hu et al. | [Privacy-Aware Machine Unlearning for Stable Association Rules in Retail Recommendations](https://doi.org/10.1109/iceei68459.2025.11330842) | International Conference on Electrical Engineering and Informatics | Recsys | — | 0 |
| Hongyu Lin et al. | [CEFU-QoS: A Cloud-Edge Federated Unlearning Framework for Rapid QoS Prediction via Collaborative Mechanisms](https://doi.org/10.1145/3787330.3787356) | International Conference on Industrial Technology | Federated | — | 0 |
| Mr. Veerasagar S S | [Vershachi Unlearning: A Framework for Machine Unlearning](https://doi.org/10.22214/ijraset.2025.67269) | International Journal for Research in Applied Science and Engineering Technology | Other | — | 0 |
| Deepika Rajwade et al. | [Machine Unlearning: A Comprehensive Framework for Efficient Data Removal in Deep Learning Systems](https://doi.org/10.38124/ijisrt/25oct892) | International Journal of Innovative Science and Research Technology | Other | — | 0 |
| Swarwel Dorle et al. | [Towards Forgettable AI](https://doi.org/10.65521/ijacect.v14i3s.1604) | International Journal on Advanced Computer Engineering and Communication Technology | Other | — | 0 |
| So Yeon Kim et al. | [Selective LLM Unlearning via SAE-Based Token Importance Score](https://doi.org/10.1109/ISNCC66965.2025.11250473) | International Symposium on Networks, Computers and Communications | LLM | — | 0 |
| Bingguang Lu et al. | [BadFU: Backdoor Federated Learning through Adversarial Machine Unlearning](https://doi.org/10.1109/RAID67961.2025.00020) | International Symposium on Recent Advances in Intrusion Detection | Federated | [GitHub](https://github.com/BingguangLu/BadFU) | 0 |
| Pengfei Wang et al. | [Eliminating Poor-Quality Data Impacts from Multiple Participants with Federated Unlearning](https://doi.org/10.1109/IWQoS65803.2025.11143467) | International Workshop on Quality of Service | Federated | — | 0 |
| Weiping Peng et al. | [Machine Unlearning Scheme for Recommendation System Based on Gradient Attribution](https://doi.org/10.54097/gqxpaf75) | Journal of Computer Science and Artificial Intelligence | Recsys | — | 0 |
| Rongxin Zhu | [Unlearning in Tabular-to-Hypergraph Learning via Selective Distillation](https://doi.org/10.63313/jcsft.9035) | Journal of Computer Science and Frontier Technologies | Graph | — | 0 |
| Min Chen et al. | [From Expansion to Retraction: Long-tailed Machine Unlearning via Boundary Manipulation](https://doi.org/10.1145/3711896.3736970) | KDD | Vision | — | 0 |
| T. S, D. K S | [Ghost Data: Representational Inertia and the Quest for Verifiable Forgetting in Modern Artificial Intelligence](https://doi.org/10.59176/kjcs.v5i1.2550) | KJCS | Other | — | 0 |
| Faqian Guan et al. | [Graph Unlearning: Efficient Node Removal in Graph Neural Networks](https://doi.org/10.48550/arXiv.2509.04785) | Knowledge-Based Systems | Graph | — | 0 |
| Paolo De los Santos et al. | [Misinformation Representation and Feature Shifts from Machine Unlearning in Large Language Models (LLMs)](https://doi.org/10.5109/7395735) | Kyushu University Institutional Repository (QIR) (Kyushu University) | LLM | — | 0 |
| Yuhang Wang et al. | [Robust MLLM Unlearning via Visual Knowledge Distillation](https://arxiv.org/abs/2512.11325) | Lecture Notes in Computer Science | LLM | — | 0 |
| L. Chai, Jay Gupta | [Exploring Machine Unlearning in Large Language Models](https://www.semanticscholar.org/paper/9cd443a6fd4b80b1d70002687dfc3d8fd0660b56) | Lecture Notes on Data Engineering and Communications Technologies | LLM | — | 0 |
| Hai Anh Tran, Abdelhamid Mellouk | [Domain-Aware Federated Unlearning With Adaptive Multi-Resolution Models for Resource-Constrained IoT Networks](https://doi.org/10.1109/mecom67453.2025.11439237) | MECOM | Federated | — | 0 |
| Andrea D’Angelo, Francesco Gullo, Giovanni Stilo | [The forget-set identification problem](https://doi.org/10.1007/s10994-025-06897-9) | Machine Learning | Other | — | 0 |
| Devulapally, Naresh Kumar et al. | [Latent Diffusion Unlearning: Protecting Against Unauthorized Personalization Through Trajectory Shifted Perturbations](https://doi.org/10.13016/m2gvnj-76zd) | Maryland Shared Open Access Repository (USMAI Consortium) | Diffusion | — | 0 |
| Neil Sharma | [Computationally Efficient Federated Unlearning](https://doi.org/10.1145/3721464.3777434) | Middleware Demos/Posters/Doctoral Symposium | Federated | — | 0 |
| Linlin Wang et al. | [Invisible watermarking framework for unlearned diffusion model in online service](https://doi.org/10.1016/j.neunet.2025.108477) | Neural Networks | Diffusion | — | 0 |
| Chengzhi Shangguan et al. | [Boundary-Anchored Functional Duplication Attacks on Machine Unlearning](https://doi.org/10.1109/PCDS65695.2025.00035) | PCDS | Other | — | 0 |
| Xiaoxuan Han et al. | [Probing unlearned diffusion models: A transferable adversarial attack perspective](https://doi.org/10.1016/j.patcog.2025.112916) | Pattern Recognition | Diffusion | [GitHub](https://github.com/SaFo-Lab/Awesome-T2I-safety-Papers) | 0 |
| Sagar S. Bhumkar, Nilesh Joshi, Manisha Bharati | [A Federated Unlearning Approach for Aerospace MRO Using Digital Twins](https://doi.org/10.1109/punecon67554.2025.11378514) | PuneCon | Federated | — | 0 |
| Andreza M. C. Falcao, Filipe R. Cordeiro | [Analise de Desaprendizado de Maquina em Modelos de Classificacao de Imagens Medicas](https://doi.org/10.5753/sbcas_estendido.2025.6966) | SBCAS | Vision | — | 0 |
| Qi-Ang Hu et al. | [ETCE: Efficient Two-Stage Concept Erasure for Text-to-Image Diffusion Models](https://doi.org/10.1145/3757374.3771453) | SIGGRAPH | Diffusion | — | 0 |
| Melih Catal | [Towards Privacy-Preserving Code Generation: Understanding and Mitigating Memorization in Code Large Language Models](https://doi.org/10.1145/3696630.3731473) | SIGSOFT FSE Companion | LLM | — | 0 |
| Liu Li et al. | [Fairness-aware Graph Unlearning with Knowledge Distillation](https://doi.org/10.1109/SWC65939.2025.00109) | SWC | Graph | — | 0 |
| Teng Wang et al. | [Differentially private federated unlearning mechanism based on update residuals](https://doi.org/10.1360/ssi-2025-0243) | Scientia Sinica Informationis | Federated | — | 0 |
| Yijing Lin et al. | [Efficient and trusted federated unlearning for multi-user semantic knowledge base](https://doi.org/10.1360/ssi-2024-0304) | Scientia Sinica Informationis | Federated | — | 0 |
| Yajie Wang et al. | [Federated Meta Unlearning Based on Model Decomposition and Weighted Aggregation](https://doi.org/10.1360/ssi-2025-0221) | Scientia Sinica Informationis | Federated | — | 0 |
| Angel Navia-Vázquez | [Unlearning in distributed budget support vector machine](https://doi.org/10.1007/s00500-025-10929-w) | Soft Computing - A Fusion of Foundations, Methodologies and Applications | Federated | — | 0 |
| A. Singh et al. | [Concept Siever : Towards Controllable Erasure of Concepts from Diffusion Models without Side-effect](https://www.semanticscholar.org/paper/84b9b21921728f4a00751d93b869fd013f6a0d6a) | TMLR | Diffusion | — | 0 |
| Byeong Guk Lee et al. | [Discriminator-Guided Unlearning: A Framework for Selective Forgetting in Conditional GANs](https://www.semanticscholar.org/paper/e317ca1219b1529d54631ebb3966fe6f37b2f255) | TRUST-AI@ECAI | Diffusion | — | 0 |
| Ze Chai et al. | [Proactive Federated Backdoor Unlearning via Two-Phase Optimization and State Replacement](https://doi.org/10.1109/trustcom66490.2025.00373) | TrustCom | Federated | — | 0 |
| Subhodip Panda et al. | [Concept Forgetting via Label Annealing](https://www.semanticscholar.org/paper/098eee0ab8d7df913ef66a0f8d7f2ef4f875241c) | UAI | Diffusion | [GitHub](https://github.com/Subhodip123/LAN) | 0 |
| Amartya Hatua, Trung T. Nguyen | [Machine Unlearning Across Scales: Evaluation of Optimization Methods on Language Models](https://doi.org/10.1109/UEMCON67449.2025.11267758) | Ubiquitous Computing, Electronics & Mobile Communication Conference | LLM | [GitHub](https://github.com/amartyahatua/LLM_Unlearning) | 0 |
| Thanh Tu Nguyen | [Towards Verifiable Federated Unlearning](https://openalex.org/W7117095252) | VUBIR (Vrije Universiteit Brussel) | Federated | — | 0 |
| D. T. Nguyen et al. | [SUGAR: A Sweeter Spot for Generative Unlearning of Many Identities](https://doi.org/10.1109/WACV61042.2026.00268) | WACV | Diffusion | [GitHub](https://github.com/judydnguyen/SUGAR-Generative-Unlearn) | 0 |
| Ju-Hsuan Weng et al. | [M-ErasureBench: A Comprehensive Multimodal Evaluation Benchmark for Concept Erasure in Diffusion Models](https://doi.org/10.1109/WACV61042.2026.00059) | WACV | Diffusion | — | 0 |
| Imran Ahsan et al. | [Forget and Explain: Transparent Verification of GNN Unlearning](https://doi.org/10.48550/arXiv.2512.07450) | WSDM | Graph | [GitHub](https://github.com/ImranAhsan23/F-E) | 0 |
| Kakul Srivastava, Himani Bansal | [Operative Study of Federated Unlearning among Various Datasets](https://doi.org/10.1109/worldsuas66815.2025.11198923) | WorldSUAS | Federated | — | 0 |
| Mushtaq, Erum et al. | [From Narrow Unlearning to Emergent Misalignment: Causes, Consequences, and Containment in LLMs](https://openalex.org/W7106206980) | arXiv | LLM | — | 0 |
| Zhao, Junpeng et al. | [Certified Signed Graph Unlearning](https://openalex.org/W7106207050) | arXiv | Graph | — | 0 |
| Xiaoqi Han et al. | [Consistency-Aware Editing for Entity-level Unlearning in Language Models](https://doi.org/10.48550/arXiv.2601.08840) | arXiv | LLM | [GitHub](https://github.com/tatsu-lab/alpaca) | 0 |
| Claudio Savelli et al. | [FAME: Fictional Actors for Multilingual Erasure](https://doi.org/10.48550/arXiv.2512.15235) | arXiv | LLM | [HF](https://huggingface.co/ClaudioSavelli/FAME_base_llama32-1b-instruct-qa) | 0 |
| Ashish Mishra et al. | [Erasing CLIP Memories: Non-Destructive, Data-Free Zero-Shot class Unlearning in CLIP Models](https://doi.org/10.48550/arXiv.2512.14137) | arXiv | Vision | — | 0 |
| Ashish Mishra et al. | [Selective, Controlled and Domain-Agnostic Unlearning in Pretrained CLIP: A Training- and Data-Free Approach](https://doi.org/10.48550/arXiv.2512.14113) | arXiv | Vision | — | 0 |
| M. Zakharov | [Face Identity Unlearning for Retrieval via Embedding Dispersion](https://doi.org/10.48550/arXiv.2512.13317) | arXiv | Vision | — | 0 |
| Guoshenghui Zhao, Huawei Lin, Weijie Zhao | [RapidUn: Influence-Driven Parameter Reweighting for Efficient Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2512.04457) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yuanbang Liang, Yang Li | [Grokked Models are Better Unlearners](https://doi.org/10.48550/arXiv.2512.03437) | arXiv | Other | — | 0 |
| MohammadParsa Dini, Human Jafari | [Adaptive-lambda Subtracted Importance Sampled Scores in Machine Unlearning for DDPMs and VAEs](https://arxiv.org/abs/2512.01054) | arXiv | Diffusion | — | 0 |
| Tien Dat Hoang | [Illuminating the Black Box: Real-Time Monitoring of Backdoor Unlearning in CNNs via Explainable AI](https://doi.org/10.48550/arXiv.2511.21291) | arXiv | Vision | — | 0 |
| Anjie Le et al. | [POUR: A Provably Optimal Method for Unlearning Representations via Neural Collapse](https://doi.org/10.48550/arXiv.2511.19339) | arXiv | Vision | — | 0 |
| Arpit Garg, Hemanth Saratchandran, Simon Lucey | [SineProject: Machine Unlearning for Stable Vision Language Alignment](https://doi.org/10.48550/arXiv.2511.18444) | arXiv | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 0 |
| Nirjhor Datta, Md. Golam Raibul Alam | [Erase to Retain: Low Rank Adaptation Guided Selective Unlearning in Medical Segmentation Networks](https://doi.org/10.48550/arXiv.2511.16574) | arXiv | Vision | — | 0 |
| Ahmet Umur Özsoy | [Selective Forgetting in Option Calibration: An Operator-Theoretic Gauss-Newton Framework](https://doi.org/10.48550/arXiv.2511.14980) | arXiv | Other | — | 0 |
| Shizhou Xu et al. | [Forgetting-MarI: LLM Unlearning via Marginal Information Regularization](https://doi.org/10.48550/arXiv.2511.11914) | arXiv | LLM | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Lisong He, Yi Yang, Xiangyu Chang | [Beyond Uniform Deletion: A Data Value-Weighted Framework for Certified Machine Unlearning](https://doi.org/10.48550/arXiv.2511.06794) | arXiv | Other | — | 0 |
| Junpeng Zhao et al. | [Learning to Fast Unrank in Collaborative Filtering Recommendation](https://doi.org/10.48550/arXiv.2511.06803) | arXiv | Recsys | [GitHub](https://github.com/Juniper42/L2UnRank) | 0 |
| Eun-su Cho et al. | [FiCABU: A Fisher-Based, Context-Adaptive Machine Unlearning Processor for Edge AI](https://doi.org/10.48550/arXiv.2511.05605) | arXiv | Other | [GitHub](https://github.com/chipsalliance/rocket-chip) | 0 |
| Minyi Peng et al. | [MPRU: Modular Projection-Redistribution Unlearning as Output Filter for Classification Pipelines](https://doi.org/10.48550/arXiv.2510.26230) | arXiv | Vision | [GitHub](https://github.com/dgunamardi/MPRU) | 0 |
| J. Lanyon et al. | [On the limitation of evaluating machine unlearning using only a single training seed](https://doi.org/10.48550/arXiv.2510.26714) | arXiv | Other | [GitHub](https://github.com/jtlan90/evaluating-machine-unlearning-using-only-a-single-training-seed) | 0 |
| Jinseong Park, Mijung Park | [Data Unlearning Beyond Uniform Forgetting via Diffusion Time and Frequency Selection](https://doi.org/10.48550/arXiv.2510.17917) | arXiv | Diffusion | [GitHub](https://github.com/christophschuhmann/improved-aesthetic-predictor) | 0 |
| Amel Abdelraheem et al. | [Backdoor Unlearning by Linear Task Decomposition](https://doi.org/10.48550/arXiv.2510.14845) | arXiv | Vision | — | 0 |
| Ziheng Huang et al. | [Federated Unlearning in the Wild: Rethinking Fairness and Data Discrepancy](https://doi.org/10.48550/arXiv.2510.07022) | arXiv | Federated | — | 0 |
| Karuna Bhaila et al. | [Cross-Modal Attention Guided Unlearning in Vision-Language Models](https://doi.org/10.48550/arXiv.2510.07567) | arXiv | LLM | — | 0 |
| Zhao Ren et al. | [Machine Unlearning in Speech Emotion Recognition via Forget Set Alone](https://doi.org/10.48550/arXiv.2510.04251) | arXiv | Other | — | 0 |
| Xiang Zhang et al. | [Rotation Control Unlearning: Quantifying and Controlling Continuous Unlearning for LLM with The Cognitive Rotation Space](https://doi.org/10.48550/arXiv.2509.25743) | arXiv | LLM | — | 0 |
| Jinghan Xu et al. | [Preserving Cross-Modal Stability for Visual Unlearning in Multimodal Scenarios](https://doi.org/10.48550/arXiv.2509.23895) | arXiv | Vision | — | 0 |
| Sadia Asif, Mohammad Mohammadi Amiri | [OFMU: Optimization-Driven Framework for Machine Unlearning](https://doi.org/10.48550/arXiv.2509.22483) | arXiv | LLM | [HF](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf) | 0 |
| Nicola Novello et al. | [A Unified Framework for Diffusion Model Unlearning with f-Divergence](https://doi.org/10.48550/arXiv.2509.21167) | arXiv | Diffusion | — | 0 |
| Ali Faraji, M. Papagelis | [TraceHiding: Scalable Machine Unlearning for Mobility Data](https://doi.org/10.48550/arXiv.2509.17241) | arXiv | Other | [GitHub](https://github.com/alifa98/TraceHiding) | 0 |
| A. K. Patra, Lingaraj Sahoo | [MRD-LiNet: A Novel Lightweight Hybrid CNN with Gradient-Guided Unlearning for Improved Drought Stress Identification](https://doi.org/10.48550/arXiv.2509.06367) | arXiv | Vision | [GitHub](https://github.com/tzutalin/labelImg) | 0 |
| Nan Wang et al. | [zkUnlearner: A Zero-Knowledge Framework for Verifiable Unlearning with Multi-Granularity and Forgery-Resistance](https://doi.org/10.48550/arXiv.2509.07290) | arXiv | Other | — | 0 |
| Rishabh Dixit, Yuan Hui, Rayan Saab | [The Measure of Deception: An Analysis of Data Forging in Machine Unlearning](https://doi.org/10.48550/arXiv.2509.05865) | arXiv | Other | — | 0 |
| Zhihao Liu et al. | [Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Guidance with Proxy Constraint](https://arxiv.org/abs/2508.20443) | arXiv | LLM | [GitHub](https://github.com/KJaebye/EmbodiedAI-Robotics-arXiv-Daily-Reporter) | 0 |
| Wenjie Bao et al. | [Module-Aware Parameter-Efficient Machine Unlearning on Transformers](https://doi.org/10.48550/arXiv.2508.17233) | arXiv | Vision | — | 0 |
| Aristeidis Sidiropoulos et al. | [Evaluating the Defense Potential of Machine Unlearning against Membership Inference Attacks](https://doi.org/10.48550/arXiv.2508.16150) | arXiv | Other | — | 0 |
| Liu Yang et al. | [Curriculum Approximate Unlearning for Session-based Recommendation](https://doi.org/10.48550/arXiv.2508.15263) | arXiv | Recsys | — | 0 |
| X. Abdullah | [Unlearning at Scale: Implementing the Right to be Forgotten in Large Language Models](https://doi.org/10.48550/arXiv.2508.12220) | arXiv | LLM | [GitHub](https://github.com/zepharaai/artifact) | 0 |
| Hang Yin et al. | [Graph Unlearning via Embedding Reconstruction - A Range-Null Space Decomposition Approach](https://doi.org/10.48550/arXiv.2508.02044) | arXiv | Graph | — | 0 |
| Kehao Miao et al. | [Towards Evaluation for Real-World LLM Unlearning](https://doi.org/10.48550/arXiv.2508.01324) | arXiv | LLM | — | 0 |
| Jiawei Liu et al. | [Efficient Machine Unlearning via Influence Approximation](https://doi.org/10.48550/arXiv.2507.23257) | arXiv | Other | [GitHub](https://github.com/Lolo1222/IAU) | 0 |
| Xin Wang, R. T. Rockafellar, X. Ban | [Machine Unlearning of Traffic State Estimation and Prediction](https://doi.org/10.48550/arXiv.2507.17984) | arXiv | Other | — | 0 |
| Patryk Jasiorski, Marek Klonowski, Michal Wo'zniak | [How to Protect Models against Adversarial Unlearning?](https://doi.org/10.48550/arXiv.2507.10886) | arXiv | Other | — | 0 |
| J. Khan | [Leveraging Distribution Matching to Make Approximate Machine Unlearning Faster](https://doi.org/10.48550/arXiv.2507.09786) | arXiv | Vision | [GitHub](https://github.com/algebraicdianuj/DC_Unlearning) | 0 |
| Jiahao Chen et al. | [LoRAShield: Data-Free Editing Alignment for Secure Personalized LoRA Sharing](https://doi.org/10.48550/arXiv.2507.07056) | arXiv | Diffusion | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 0 |
| Qing Gong, Xue Yang, Xiaohu Tang | [Orthogonal Soft Pruning for Efficient Class Unlearning](https://doi.org/10.48550/arXiv.2506.19891) | arXiv | Federated | — | 0 |
| Ruihan Wu, Konstantin Garov, Kamalika Chaudhuri | [Learning-Time Encoding Shapes Unlearning in LLMs](https://doi.org/10.48550/arXiv.2506.15076) | arXiv | LLM | [GitHub](https://github.com/wrh14/learning_time_shapes_unlearning) | 0 |
| Xiangman Li et al. | [PDLRecover: Privacy-preserving Decentralized Model Recovery with Machine Unlearning](https://doi.org/10.48550/arXiv.2506.15112) | arXiv | Federated | — | 0 |
| Ya-Nan Yuan et al. | [Unlearning-Enhanced Website Fingerprinting Attack: Against Backdoor Poisoning in Anonymous Networks](https://doi.org/10.48550/arXiv.2506.13563) | arXiv | Vision | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 0 |
| Aleksey Kudelya, Alexander Shirnin | [Lacuna Inc. at SemEval-2025 Task 4: LoRA-Enhanced Influence-Based Unlearning for LLMs](https://doi.org/10.48550/arXiv.2506.04044) | arXiv | LLM | — | 0 |
| Minsu Kim, Nakyeong Yang, Kyomin Jung | [Rethinking Post-Unlearning Behavior of Large Vision-Language Models](https://doi.org/10.48550/arXiv.2506.02541) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| SeungBum Ha, Saerom Park, Sung Whan Yoon | [Unlearning's Blind Spots: Over-Unlearning and Prototypical Relearning Attack](https://doi.org/10.48550/arXiv.2506.01318) | arXiv | Vision | [GitHub](https://github.com/Seung-B/Spotter-Unlearning) | 0 |
| Öykü Deniz Köse, Gonzalo Mateos, Yanning Shen | [Unlearning Algorithmic Biases over Graphs](https://doi.org/10.48550/arXiv.2505.14945) | arXiv | Graph | — | 0 |
| Brennon Brimhall et al. | [Mirror Mirror on the Wall, Have I Forgotten it All? A New Framework for Evaluating Machine Unlearning](https://doi.org/10.48550/arXiv.2505.08138) | arXiv | Other | — | 0 |
| Xinyang Lu et al. | [WaterDrum: Watermarking for Data-centric Unlearning Metric](https://doi.org/10.48550/arXiv.2505.05064) | arXiv | LLM | [GitHub](https://github.com/lululu008/WaterDrum) | 0 |
| Saber Malekmohammadi, H. Lee, Li Xiong | [Sharpness-Aware Parameter Selection for Machine Unlearning](https://doi.org/10.48550/arXiv.2504.06398) | arXiv | Other | — | 0 |
| Chenguang Xiao et al. | [Benchmarking Federated Machine Unlearning methods for Tabular Data](https://doi.org/10.48550/arXiv.2504.00921) | arXiv | Federated | — | 0 |
| Piyush Nagasubramaniam et al. | [Prompting Forgetting: Unlearning in GANs via Textual Guidance](https://doi.org/10.48550/arXiv.2504.01218) | arXiv | Diffusion | — | 0 |
| Tetsuya Hoya, Shunpei Morita | [Automatic Construction of Pattern Classifiers Capable of Continuous Incremental Learning and Unlearning Tasks Based on Compact-Sized Probabilistic Neural Network](https://doi.org/10.48550/arXiv.2501.00725) | arXiv | Other | — | 0 |
| Hithem Lamri, Michail Maniatakos | [Fully Decentralized Certified Unlearning](https://doi.org/10.48550/arXiv.2512.08443) | arXiv | Federated | — | 0 |
| Mostafa Mozafari et al. | [Subtract the Corruption: Training-Data-Free Corrective Machine Unlearning using Task Arithmetic](https://doi.org/10.48550/arXiv.2511.18660) | arXiv | Vision | [GitHub](https://github.com/mosix11/CUTS) | 0 |
| Siqiao Mu, Diego Klabjan | [Descend or Rewind? Stochastic Gradient Descent Unlearning](https://doi.org/10.48550/arXiv.2511.15983) | arXiv | Other | [GitHub](https://github.com/anonymous-1234567/r2d2) | 0 |
| Yinyi Luo et al. | [KnowledgeSmith: Uncovering Knowledge Updating in LLMs with Model Editing and Unlearning](https://doi.org/10.48550/arXiv.2510.02392) | arXiv | LLM | [GitHub](https://github.com/AIFrontierLab/KnowledgeSmith) | 0 |
| Wenhao Yang et al. | [Factor Decorrelation Enhanced Data Removal from Deep Predictive Models](https://doi.org/10.48550/arXiv.2509.23443) | arXiv | Other | [GitHub](https://github.com/WUT-IDEA/DecoRemoval) | 0 |
| Anna Mazhar, Sainyam Galhotra | [Causal Fuzzing for Verifying Machine Unlearning](https://doi.org/10.48550/arXiv.2509.16525) | arXiv | Other | — | 0 |
| Ashwath Vaithinathan Aravindan et al. | [Sealing The Backdoor: Unlearning Adversarial Text Triggers In Diffusion Models Using Knowledge Distillation](https://doi.org/10.48550/arXiv.2508.18235) | arXiv | Diffusion | [GitHub](https://github.com/Mystic-Slice/Sealing-The-Backdoor) | 0 |
| Ken Stewart | [Mo' Memory, Mo' Problems: Stream-Native Machine Unlearning](https://doi.org/10.48550/arXiv.2508.10193) | arXiv | Other | — | 0 |
| Xinbao Qiao et al. | [Soft Weighted Machine Unlearning](https://doi.org/10.48550/arXiv.2505.18783) | arXiv | Other | — | 0 |
| Yingdan Shi, Ren Wang | [MCU: Improving Machine Unlearning through Mode Connectivity](https://doi.org/10.48550/arXiv.2505.10859) | arXiv | Vision | [GitHub](https://github.com/TIML-Group/Mode-Connectivity-Unlearning) | 0 |
| Fengli Wu et al. | [MedForget: Hierarchy-Aware Multimodal Unlearning Testbed for Medical AI](https://doi.org/10.48550/arXiv.2512.09867) | arXiv | Other | — | 0 |
| Aadya Goel, Mayuri Sridhar | [Delete and Retain: Efficient Unlearning for Document Classification](https://doi.org/10.48550/arXiv.2512.13711) | arXiv | LLM | — | 0 |
| Pinak Mandal, G. Gottwald | [UNO: Unlearning via Orthogonalization in Generative models](https://doi.org/10.48550/arXiv.2506.04712) | arXiv | Diffusion | [GitHub](https://github.com/pinakm9/forget) | 0 |
| Yasser H. Khalil, Mehdi Setayesh, Hongliang Li | [CoUn: Empowering Machine Unlearning via Contrastive Learning](https://doi.org/10.48550/arXiv.2509.16391) | arXiv | Vision | [GitHub](https://github.com/sheltparkle/CoUn_Code) | 0 |
| Christoforos N. Spartalis et al. | [Unleashing Uncertainty: Efficient Machine Unlearning for Generative AI](https://doi.org/10.48550/arXiv.2508.20773) | arXiv | Diffusion | — | 0 |
| Jaeik Kim, Jaeyoung Do | [Exploring and Leveraging Class Vectors for Classifier Editing](https://doi.org/10.48550/arXiv.2510.11268) | arXiv | Vision | [GitHub](https://github.com/AIDASLab/Class-Vector) | 0 |
| Roy Rinberg et al. | [RippleBench: Capturing Ripple Effects Using Existing Knowledge Repositories](https://doi.org/10.48550/arXiv.2512.04144) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Aakash Sen Sharma et al. | [The Realignment Problem: When Right becomes Wrong in LLMs](https://doi.org/10.48550/arXiv.2511.02623) | arXiv | LLM | [GitHub](https://github.com/respailab/TRACE) | 0 |
| Aakriti Shah, Thai Le | [The Limits of Obliviate: Evaluating Unlearning in LLMs via Stimulus-Knowledge Entanglement-Behavior Framework](https://doi.org/10.48550/arXiv.2510.25732) | arXiv | LLM | — | 0 |
| Anu Agarwal, Mihir Pamnani, Dilek Hakkani-Tur | [SIMU: Selective Influence Machine Unlearning](https://doi.org/10.48550/arXiv.2510.07822) | arXiv | LLM | — | 0 |
| Yicheng Lang et al. | [Downgrade to Upgrade: Optimizer Simplification Enhances Robustness in LLM Unlearning](https://doi.org/10.48550/arXiv.2510.00761) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn_Optimizer) | 0 |
| Yujian Sun, Tian Li | [iShumei-Chinchunmei at SemEval-2025 Task 4: A balanced forgetting and retention multi-task framework using effective unlearning loss](https://doi.org/10.48550/arXiv.2507.16263) | arXiv | LLM | — | 0 |
| Arjun Dosajh, Mihika Sanghi | [Mr. Snuffleupagus at SemEval-2025 Task 4: Unlearning Factual Knowledge from LLMs Using Adaptive RMU](https://doi.org/10.48550/arXiv.2506.16548) | arXiv | LLM | — | 0 |
| Xiaotian Ye, Mengqi Zhang, Shu Wu | [LLM Unlearning Should Be Form-Independent](https://doi.org/10.48550/arXiv.2506.07795) | arXiv | LLM | [GitHub](https://github.com/Acruxos/ORT) | 0 |
| P. Prashant, Kaustubh Ponkshe, Babak Salimi | [A Lightweight Method to Disrupt Memorized Sequences in LLM](https://doi.org/10.48550/arXiv.2502.05159) | arXiv | LLM | [GitHub](https://github.com/parjanya20/verbatim-llm) | 0 |
| Zhihao Liu et al. | [Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Aware Unlearning with Proxy Constraint](https://doi.org/10.48550/arXiv.2508.20443) | arXiv | LLM | — | 0 |
| Yiwen Liang et al. | [When Forgetting Builds Reliability: LLM Unlearning for Reliable Hardware Code Generation](https://doi.org/10.48550/arXiv.2512.05341) | arXiv | LLM | — | 0 |
| Liran Cohen, Yaniv Nemcovesky, Avi Mendelson | [REMIND: Input Loss Landscapes Reveal Residual Memorization in Post-Unlearning LLMs](https://doi.org/10.48550/arXiv.2511.04228) | arXiv | LLM | — | 0 |
| Myeongseob Ko et al. | [Probing Knowledge Holes in Unlearned LLMs](https://doi.org/10.48550/arXiv.2511.00030) | arXiv | LLM | — | 0 |
| Yuefeng Peng et al. | [Forget to Know, Remember to Use: Context-Aware Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2510.17620) | arXiv | LLM | — | 0 |
| Praveen Bushipaka, Lucia C. Passaro, Tommaso Cucinotta | [Standard vs. Modular Sampling: Best Practices for Reliable LLM Unlearning](https://doi.org/10.48550/arXiv.2509.05316) | arXiv | LLM | [GitHub](https://github.com/praveensonu/MELU) | 0 |
| Saransh Agrawal, Kuan-Hao Huang | [SHA256 at SemEval-2025 Task 4: Selective Amnesia - Constrained Unlearning for Large Language Models via Knowledge Isolation](https://doi.org/10.48550/arXiv.2504.12996) | arXiv | LLM | [GitHub](https://github.com/LAB-FLAIR/Constrained-Unlearning-for-LLM) | 0 |
| Dinesh P. Srivasthav, B. Garlapati | [Cyber for AI at SemEval-2025 Task 4: Forgotten but Not Lost: The Balancing Act of Selective Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2503.04795) | arXiv | LLM | [HF](https://huggingface.co/datasets/allenai/dolma) | 0 |
| Changjun Zhou et al. | [Dual-Phase Federated Deep Unlearning via Weight-Aware Rollback and Reconstruction](https://doi.org/10.48550/arXiv.2512.13381) | arXiv | Federated | [GitHub](https://github.com/00taotao/DPUL) | 0 |
| Lorenzo Simone, Davide Bacciu, Shuangge Ma | [ContinualFlow: Learning and Unlearning with Neural Flow Matching](https://doi.org/10.48550/arXiv.2506.18747) | arXiv | Diffusion | — | 0 |
| Hao Chen, Yiwei Wang, Songze Li | [Bi-Erasing: A Bidirectional Framework for Concept Removal in Diffusion Models](https://doi.org/10.48550/arXiv.2512.13039) | arXiv | Diffusion | [GitHub](https://github.com/chenahong/Bi-Erasing) | 0 |
| Dawid Malarz et al. | [From Unlearning to UNBRANDING: A Benchmark for Trademark-Safe Text-to-Image Generation](https://doi.org/10.48550/arXiv.2512.13953) | arXiv | Diffusion | [GitHub](https://github.com/gmum/UNBRANDING) | 0 |
| D. Kothandaraman, Jaclyn Pytlarz | [Beyond Memorization: Selective Learning for Copyright-Safe Diffusion Model Training](https://arxiv.org/abs/2512.11194) | arXiv | Diffusion | — | 0 |
| Naveen George et al. | [Distill, Forget, Repeat: A Framework for Continual Unlearning in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2512.02657) | arXiv | Diffusion | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Jiwoo Shin et al. | [Prompt-Based Safety Guidance Is Ineffective for Unlearned Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2511.04834) | arXiv | Diffusion | [GitHub](https://github.com/naver-ai/DUO) | 0 |
| Qinghong Yin, Yu Tian, Yue Zhang | [Rethinking Robust Adversarial Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2510.27285) | arXiv | Diffusion | [GitHub](https://github.com/Qhong-522/S-GRACE) | 0 |
| Youngsik Hwang, Dong-Young Lim | [Controllable Machine Unlearning via Gradient Pivoting](https://doi.org/10.48550/arXiv.2510.19226) | arXiv | Other | — | 0 |
| Hongxu Chen et al. | [Zero-Residual Concept Erasure via Progressive Alignment in Text-to-Image Model](https://doi.org/10.48550/arXiv.2508.04472) | arXiv | Diffusion | — | 0 |
| Zixuan Fu et al. | [FADE: Adversarial Concept Erasure in Flow Models](https://doi.org/10.48550/arXiv.2507.12283) | arXiv | Diffusion | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| Shreyas Udaya, A. Lakshmi | [Few-Shot Concept Unlearning with Low Rank Adaptation](https://doi.org/10.48550/arXiv.2505.12395) | arXiv | Diffusion | — | 0 |
| D. Kothandaraman, Jaclyn Pytlarz | [Beyond Memorization: Gradient Projection Enables Selective Learning in Diffusion Models](https://doi.org/10.48550/arXiv.2512.11194) | arXiv | Diffusion | — | 0 |
| Xiaoliu Guan et al. | [Redistribute Ensemble Training for Mitigating Memorization in Diffusion Models](https://doi.org/10.48550/arXiv.2502.09434) | arXiv | Diffusion | [GitHub](https://github.com/liuxiao-guan/IET_AGC) | 0 |
| Bocheng Ju et al. | [DRAGD: A Federated Unlearning Data Reconstruction Attack Based on Gradient Differences](https://doi.org/10.48550/arXiv.2507.09602) | arXiv | Federated | — | 0 |
| K. Basha, Athira Nambiar | [Supervised Contrastive Machine Unlearning of Background Bias in Sonar Image Classification with Fine-Grained Explainable AI](https://doi.org/10.48550/arXiv.2512.01291) | arXiv | Vision | — | 0 |
| Yuyuan Li et al. | [Reproducibility Companion Paper: Making Users Indistinguishable: Attribute-wise Unlearning in Recommender Systems](https://doi.org/10.48550/arXiv.2503.23032) | arXiv | Recsys | [GitHub](https://github.com/oktton/Attribute-wise-Unlearning) | 0 |
| Ilya Lasy, Peter Knees, Stefan Woltran | [Understanding Verbatim Memorization in LLMs Through Circuit Discovery](https://doi.org/10.18653/v1/2025.l2m2-1.7) | arXiv | LLM | [GitHub](https://github.com/ilyalasy/memorization_circuits) | 0 |
| Iris Ma et al. | [Memorization: A Close Look at Books](https://doi.org/10.18653/v1/2025.l2m2-1.13) | arXiv | LLM | — | 0 |
| Anat Kleiman et al. | [When unlearning is free: leveraging low influence points to reduce computational costs](https://doi.org/10.48550/arXiv.2512.05254) | arXiv | Other | [GitHub](https://github.com/unlearning-challenge/starting-kit/blob) | 0 |
| Hithem Lamri et al. | [DRAUN: An Algorithm-Agnostic Data Reconstruction Attack on Federated Unlearning Systems](https://doi.org/10.48550/arXiv.2506.01777) | arXiv | Federated | — | 0 |
| Robert Dilworth | [Privacy Preservation through Practical Machine Unlearning](https://doi.org/10.48550/arXiv.2502.10635) | arXiv | Other | — | 0 |
| Yujia Tong et al. | [LetheViT: Selective Machine Unlearning for Vision Transformers via Attention-Guided Contrastive Learning](https://doi.org/10.48550/arXiv.2508.01569) | arXiv | Vision | — | 0 |
| Rishub Tamirisa et al. | [T OWARD R OBUST U NLEARNING FOR LLM S](https://www.semanticscholar.org/paper/29116311adf2f6af8b64e270894e9cf53b101623) | arXiv | LLM | — | 0 |
| Massimiliano Falzari, M. Sabatelli | [Fisher-Guided Selective Forgetting (FGSF) For Deep Reinforcement Learning](https://www.semanticscholar.org/paper/25cfe9ee1cb86b44612ba822b072b02813c80919) | arXiv | Other | — | 0 |
| Jingqi Xu et al. | [FPAN: Mitigating Replication in Diffusion Models through the Fine-Grained Probabilistic Addition of Noise to Token Embeddings](https://doi.org/10.48550/arXiv.2505.21848) | arXiv | Diffusion | — | 0 |

## 2024

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Pratyush Maini et al. | [TOFU: A Task of Fictitious Unlearning for LLMs](https://doi.org/10.48550/arXiv.2401.06121) | arXiv | LLM | [GitHub](https://github.com/locuslab/tofu) | 408 |
| Ruiqi Zhang et al. | [Negative Preference Optimization: From Catastrophic Collapse to Effective Unlearning](https://doi.org/10.48550/arXiv.2404.05868) | arXiv | LLM | [HF](https://huggingface.co/girishgupta/deep-ignorance-unfiltered_unlearned_npo) | 401 |
| Nathaniel Li et al. | [The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning](https://arxiv.org/abs/2403.03218) | ICML | LLM | [GitHub](https://github.com/centerforaisafety/wmdp) | 392 |
| Shilin Lu et al. | [MACE: Mass Concept Erasure in Diffusion Models](https://doi.org/10.1109/CVPR52733.2024.00615) | CVPR | Diffusion | [GitHub](https://github.com/Shilin-LU/MACE) | 270 |
| Andy Zou et al. | [Improving Alignment and Robustness with Circuit Breakers](https://doi.org/10.48550/arXiv.2406.04313) | NeurIPS | LLM | [HF](https://huggingface.co/GraySwanAI/Llama-3-8B-Instruct-RR) | 268 |
| Weijia Shi et al. | [MUSE: Machine Unlearning Six-Way Evaluation for Language Models](https://doi.org/10.48550/arXiv.2407.06460) | ICLR | LLM | [GitHub](https://github.com/swj0419/muse_bench) | 201 |
| Zayd Hammoudeh, Daniel Lowd | [Training data influence analysis and estimation: a survey](https://doi.org/10.1007/s10994-023-06495-7) | Machine Learning | Other | [GitHub](https://github.com/ZaydH/influence_analysis_papers) | 167 |
| Zheyuan Liu et al. | [Towards Safer Large Language Models through Machine Unlearning](https://doi.org/10.48550/arXiv.2402.10058) | ACL | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 148 |
| Yimeng Zhang et al. | [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2405.15234) | NeurIPS | Diffusion | [GitHub](https://github.com/optml-group/advunlearn) | 145 |
| Aengus Lynch et al. | [Eight Methods to Evaluate Robust Unlearning in LLMs](https://doi.org/10.48550/arXiv.2402.16835) | arXiv | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 140 |
| Nathaniel Li et al. | [LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet](https://doi.org/10.48550/arXiv.2408.15221) | arXiv | LLM | [HF](https://huggingface.co/ScaleAI/mhj-llama3-8b-rmu) | 138 |
| A. Sheshadri et al. | [Latent Adversarial Training Improves Robustness to Persistent Harmful Behaviors in LLMs](https://arxiv.org/abs/2407.15549) | TMLR | LLM | [GitHub](https://github.com/aengusl/latent-adversarial-training) | 130 |
| Rishub Tamirisa et al. | [Tamper-Resistant Safeguards for Open-Weight LLMs](https://doi.org/10.48550/arXiv.2408.00761) | ICLR | LLM | [HF](https://huggingface.co/lapisrocks/Llama-3-8B-Instruct-TAR-Bio-v2) | 124 |
| Chris Liu et al. | [Large Language Model Unlearning via Embedding-Corrupted Prompts](https://doi.org/10.48550/arXiv.2406.07933) | NeurIPS | LLM | [GitHub](https://github.com/chrisliu298/llm-unlearn-eco) | 114 |
| Jin Yao et al. | [Machine Unlearning of Pre-trained Large Language Models](https://doi.org/10.48550/arXiv.2402.15159) | ACL | LLM | [GitHub](https://github.com/yaojin17/unlearning_llm) | 111 |
| Jinghan Jia et al. | [SOUL: Unlocking the Power of Second-Order Optimization for LLM Unlearning](https://doi.org/10.48550/arXiv.2404.18239) | EMNLP | LLM | [GitHub](https://github.com/optml-group/soul) | 107 |
| Chao Gong et al. | [Reliable and Efficient Concept Erasure of Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2407.12383) | ECCV | Diffusion | [GitHub](https://github.com/charlesgong12/rece) | 101 |
| Avi Schwarzschild et al. | [Rethinking LLM Memorization through the Lens of Adversarial Compression](https://doi.org/10.48550/arXiv.2404.15146) | NeurIPS | LLM | [HF](https://huggingface.co/spaces/pratyushmaini/acr_viewer) | 101 |
| Jakub Lucki et al. | [An Adversarial Perspective on Machine Unlearning for AI Safety](https://doi.org/10.48550/arXiv.2409.18025) | TMLR | LLM | [GitHub](https://github.com/ethz-spylab/unlearning-vs-safety) | 101 |
| Chongyu Fan et al. | [Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning](https://doi.org/10.48550/arXiv.2410.07163) | arXiv | LLM | [GitHub](https://github.com/OPTML-Group/Unlearn-Simple) | 100 |
| Leo Schwinn et al. | [Soft Prompt Threats: Attacking Safety Alignment and Unlearning in Open-Source LLMs through the Embedding Space](https://doi.org/10.48550/arXiv.2402.09063) | NeurIPS | LLM | [GitHub](https://github.com/SchwinnL/LLM_Embedding_Attack) | 94 |
| Dawen Zhang et al. | [Right to be forgotten in the Era of large language models: implications, challenges, and solutions](https://doi.org/10.1007/s43681-024-00573-9) | AI and Ethics | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 91 |
| Pratiksha Thaker, Yash Maurya, Virginia Smith | [Guardrail Baselines for Unlearning in LLMs](https://doi.org/10.48550/arXiv.2403.03329) | arXiv | LLM | [GitHub](https://github.com/pratiksha/guardrail-baselines) | 91 |
| Jaehong Yoon et al. | [SAFREE: Training-Free and Adaptive Guard for Safe Text-to-Image And Video Generation](https://doi.org/10.48550/arXiv.2410.12761) | ICLR | Diffusion | [GitHub](https://github.com/jaehong31/SAFREE) | 83 |
| Jamie Hayes et al. | [Inexact Unlearning Needs More Careful Evaluations to Avoid a False Sense of Privacy](https://doi.org/10.1109/SaTML64287.2025.00034) | SaTML | Other | — | 79 |
| Jiabao Ji et al. | [Reversing the Forget-Retain Objectives: An Efficient LLM Unlearning Framework from Logit Difference](https://doi.org/10.48550/arXiv.2406.08607) | NeurIPS | LLM | [GitHub](https://github.com/UCSB-NLP-Chang/ULD) | 77 |
| Kairan Zhao et al. | [What makes unlearning hard and what to do about it](https://doi.org/10.48550/arXiv.2406.01257) | NeurIPS | Other | [GitHub](https://github.com/kairanzhao/RUM) | 73 |
| Daiheng Gao et al. | [EraseAnything: Enabling Concept Erasure in Rectified Flow Transformers](https://doi.org/10.48550/arXiv.2412.20413) | arXiv | Diffusion | [GitHub](https://github.com/tomguluson92/eraseanything) | 71 |
| Debeshee Das, Jie Zhang, F. Tramèr | [Blind Baselines Beat Membership Inference Attacks for Foundation Models](https://doi.org/10.1109/SPW67851.2025.00016) | SPW | LLM | [GitHub](https://github.com/ethz-spylab/Blind-MIA) | 69 |
| Zhuoran Jin et al. | [RWKU: Benchmarking Real-World Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2406.10890) | NeurIPS | LLM | [GitHub](https://github.com/jinzhuoran/rwku) | 68 |
| Nicolò Romandini et al. | [Federated Unlearning: A Survey on Methods, Design Guidelines, and Evaluation Metrics](https://doi.org/10.1109/tnnls.2024.3478334) | IEEE TNNLS | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 67 |
| Pengfei Wang et al. | [Server-Initiated Federated Unlearning to Eliminate Impacts of Low-Quality Data](https://doi.org/10.1109/tsc.2024.3355188) | IEEE TSC | Federated | — | 67 |
| Yaxuan Wang et al. | [LLM Unlearning via Loss Adjustment with Only Forget Data](https://doi.org/10.48550/arXiv.2410.11143) | ICLR | LLM | [GitHub](https://github.com/UCSC-REAL/FLAT) | 64 |
| Hongsheng Hu et al. | [Learn What You Want to Unlearn: Unlearning Inversion Attacks against Machine Unlearning](https://doi.org/10.1109/SP54263.2024.00248) | IEEE S&P | Other | [GitHub](https://github.com/pytorch/opacus/blob) | 63 |
| Yihua Zhang et al. | [UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models](https://doi.org/10.48550/arXiv.2402.11846) | arXiv | Diffusion | — | 62 |
| Xinfeng Li et al. | [SafeGen: Mitigating Sexually Explicit Content Generation in Text-to-Image Models](https://doi.org/10.1145/3658644.3670295) | CCS | Diffusion | [GitHub](https://github.com/letterligo/text-agnostic-governance) | 60 |
| Zhiwei Zhang et al. | [Catastrophic Failure of LLM Unlearning via Quantization](https://arxiv.org/abs/2410.16454) | ICLR | LLM | [GitHub](https://github.com/zzwjames/FailureLLMUnlearning) | 60 |
| Ziyao Liu et al. | [Threats, Attacks, and Defenses in Machine Unlearning: A Survey](https://doi.org/10.1109/OJCS.2025.3543483) | IEEE Open Journal of the Computer Society | Other | — | 59 |
| Aghyad Deeb, Fabien Roger | [Do Unlearning Methods Remove Information from Language Model Weights?](https://doi.org/10.48550/arXiv.2410.08827) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 59 |
| Guihong Li et al. | [Machine Unlearning for Image-to-Image Generative Models](https://doi.org/10.48550/arXiv.2402.00351) | ICLR | Vision | [GitHub](https://github.com/jpmorganchase/i2i-generator-unlearning) | 56 |
| Chongyu Fan et al. | [Challenging Forgets: Unveiling the Worst-Case Forget Sets in Machine Unlearning](https://doi.org/10.48550/arXiv.2403.07362) | ECCV | Vision | [GitHub](https://github.com/optml-group/unlearn-worstcase) | 55 |
| Chen Chen, Daochang Liu, Chang Xu | [Towards Memorization-Free Diffusion Models](https://doi.org/10.1109/CVPR52733.2024.00805) | CVPR | Diffusion | [GitHub](https://github.com/lifangting/CVPR2024-Diffusion-Model) | 54 |
| Ilia Shumailov et al. | [UnUnlearning: Unlearning is not sufficient for content regulation in advanced generative AI](https://doi.org/10.48550/arXiv.2407.00106) | arXiv | LLM | — | 54 |
| Weikai Lu et al. | [Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge](https://doi.org/10.48550/arXiv.2404.05880) | arXiv | LLM | [GitHub](https://github.com/ZeroNLP/Eraser) | 54 |
| C. Kim, Kyle Min, Yezhou Yang | [R.A.C.E.: Robust Adversarial Concept Erasure for Secure Text-to-Image Diffusion Model](https://doi.org/10.48550/arXiv.2405.16341) | ECCV | Diffusion | [GitHub](https://github.com/chkimmmmm/R.A.C.E) | 53 |
| Eoin Farrell, Yeu-Tong Lau, Arthur Conmy | [Applying sparse autoencoders to unlearn knowledge in language models](https://doi.org/10.48550/arXiv.2410.19278) | arXiv | LLM | [GitHub](https://github.com/efarrell1/train_sparse_autoencoder) | 53 |
| Jing Huang, Diyi Yang, Christopher Potts | [Demystifying Verbatim Memorization in Large Language Models](https://doi.org/10.48550/arXiv.2407.17817) | EMNLP | LLM | [GitHub](https://github.com/explanare/verbatim-memorization) | 52 |
| Samyak Jain et al. | [What Makes and Breaks Safety Fine-tuning? A Mechanistic Study](https://doi.org/10.48550/arXiv.2407.10264) | NeurIPS | LLM | [GitHub](https://github.com/fiveai/understanding_safety_finetuning) | 51 |
| Shengyuan Hu et al. | [Unlearning or Obfuscating? Jogging the Memory of Unlearned LLMs via Benign Relearning](https://arxiv.org/abs/2406.13356) | ICLR | LLM | [GitHub](https://github.com/s-huu/jog_llm_memory) | 50 |
| Zheyuan Liu et al. | [Machine Unlearning in Generative AI: A Survey](https://doi.org/10.48550/arXiv.2407.20516) | arXiv | Other | [GitHub](https://github.com/franciscoliu/GenAI-MU-Reading) | 50 |
| Weiqi Wang, Zhiyi Tian, Shui Yu | [Machine Unlearning: A Comprehensive Survey](https://doi.org/10.48550/arXiv.2405.07406) | arXiv | Other | [GitHub](https://github.com/pybrush/pybrush) | 50 |
| Jing Wu, Mehrtash Harandi | [Scissorhands: Scrub Data Influence via Connection Sensitivity in Networks](https://doi.org/10.48550/arXiv.2401.06187) | ECCV | Vision | [GitHub](https://github.com/JingWu321/Scissorhands) | 49 |
| Pratiksha Thaker et al. | [Position: LLM Unlearning Benchmarks are Weak Measures of Progress](https://doi.org/10.1109/SaTML64287.2025.00035) | SaTML | LLM | [HF](https://huggingface.co/datasets/forgelab/wmdp-swap) | 49 |
| Jing Wu et al. | [EraseDiff: Erasing Data Influence in Diffusion Models](https://doi.org/10.48550/arXiv.2401.05779) | arXiv | Diffusion | [GitHub](https://github.com/JingWu321/EraseDiff) | 49 |
| Xuhao Hu et al. | [VLSBench: Unveiling Visual Leakage in Multimodal Safety](https://doi.org/10.48550/arXiv.2411.19939) | arXiv | LLM | [GitHub](https://github.com/ai45lab/vlsbench) | 49 |
| Yong-Hyun Park et al. | [Direct Unlearning Optimization for Robust and Safe Text-to-Image Models](https://doi.org/10.48550/arXiv.2407.21035) | NeurIPS | Diffusion | [GitHub](https://github.com/naver-ai/DUO) | 48 |
| Xiangyu Qi et al. | [On Evaluating the Durability of Safeguards for Open-Weight LLMs](https://doi.org/10.48550/arXiv.2412.07097) | ICLR | LLM | [GitHub](https://github.com/princeton-polaris-lab/Evaluating-Durable-Safeguards) | 47 |
| Ruchika Chavhan, Da Li, Timothy M. Hospedales | [ConceptPrune: Concept Editing in Diffusion Models via Skilled Neuron Pruning](https://doi.org/10.48550/arXiv.2405.19237) | ICLR | Diffusion | [GitHub](https://github.com/liuxuannan/Awesome-Multimodal-Jailbreak) | 47 |
| Zhou Yang et al. | [Unveiling Memorization in Code Models](https://doi.org/10.1145/3597503.3639074) | International Conference on Software Engineering | LLM | [GitHub](https://github.com/saltudelft/ml4se) | 47 |
| Eleni Triantafillou et al. | [Are we making progress in unlearning? Findings from the first NeurIPS unlearning competition](https://doi.org/10.48550/arXiv.2406.09073) | arXiv | Other | [GitHub](https://github.com/google-deepmind/unlearning_evaluation) | 47 |
| Zihao Liu et al. | [Backdoor Attacks via Machine Unlearning](https://doi.org/10.1609/aaai.v38i13.29321) | AAAI | Other | [GitHub](https://github.com/diadai/Machine-Unlearning) | 46 |
| Zheyuan Liu et al. | [Protecting Privacy in Multimodal Large Language Models with MLLMU-Bench](https://doi.org/10.48550/arXiv.2410.22108) | NAACL | LLM | [GitHub](https://github.com/franciscoliu/MLLMU-Bench) | 45 |
| Eli Chien et al. | [Langevin Unlearning: A New Perspective of Noisy Gradient Descent for Machine Unlearning](https://doi.org/10.48550/arXiv.2401.10371) | NeurIPS | Other | [GitHub](https://github.com/Graph-COM/Langevin_unlearning) | 45 |
| Nikhil Kandpal et al. | [User Inference Attacks on Large Language Models](https://doi.org/10.18653/v1/2024.emnlp-main.1014) | EMNLP | LLM | [GitHub](https://github.com/chawins/llm-sp) | 44 |
| Ali Al-Kaswan, Maliheh Izadi, Arie van Deursen | [Traces of Memorisation in Large Language Models for Code](https://doi.org/10.1145/3597503.3639133) | International Conference on Software Engineering | LLM | [GitHub](https://github.com/aise-tudelft/llm4code-extraction) | 44 |
| Boyi Wei et al. | [Evaluating Copyright Takedown Methods for Language Models](https://doi.org/10.48550/arXiv.2406.18664) | NeurIPS | LLM | [HF](https://huggingface.co/spaces/boyiwei/CoTaEval_leaderboard) | 44 |
| Lingzhi Wang et al. | [Selective Forgetting: Advancing Machine Unlearning Techniques and Evaluation in Language Models](https://doi.org/10.48550/arXiv.2402.05813) | AAAI | LLM | [GitHub](https://github.com/google-research/lm-extraction-benchmark) | 43 |
| Jiaqi Li et al. | [Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2405.12523) | NeurIPS | LLM | — | 42 |
| Nicholas Pochinkov, Nandi Schoots | [Dissecting Language Models: Machine Unlearning via Selective Pruning](https://doi.org/10.48550/arXiv.2403.01267) | arXiv | LLM | [GitHub](https://github.com/nickypro/selective-pruning) | 42 |
| A. Cooper et al. | [Machine Unlearning Doesn't Do What You Think: Lessons for Generative AI Policy, Research, and Practice](https://doi.org/10.48550/arXiv.2412.06966) | arXiv | Other | — | 42 |
| George-Octavian Barbulescu, Peter Triantafillou | [To Each (Textual Sequence) Its Own: Improving Memorized-Data Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2405.03097) | ICML | LLM | [GitHub](https://github.com/GeorgeOctavian/selective_unlearning) | 41 |
| Yang Zhang et al. | [Recommendation Unlearning via Influence Function](https://doi.org/10.1145/3701763) | ACM Transactions on Recommender Systems | Recsys | [GitHub](https://github.com/baiyimeng/IFRU) | 40 |
| Xiaojian \ Yuan et al. | [A Closer Look at Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2410.08109) | ICLR | LLM | [GitHub](https://github.com/sail-sg/closer-look-LLM-unlearning) | 40 |
| Chongyang Gao et al. | [On Large Language Model Continual Unlearning](https://arxiv.org/abs/2407.10223) | ICLR | LLM | [GitHub](https://github.com/gcyzsl/o3-llm-unlearning) | 39 |
| Anh-Vu Bui et al. | [Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation](https://doi.org/10.48550/arXiv.2410.15618) | NeurIPS | Diffusion | [GitHub](https://github.com/tuananhbui89/Erasing-Adversarial-Preservation) | 39 |
| Xunkai Li et al. | [Towards Effective and General Graph Unlearning via Mutual Evolution](https://doi.org/10.1609/aaai.v38i12.29273) | AAAI | Graph | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 38 |
| Chaochao Chen et al. | [Post-Training Attribute Unlearning in Recommender Systems](https://doi.org/10.1145/3701987) | ACM Transactions on Information Systems | Recsys | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 38 |
| Zhehao Huang et al. | [Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://doi.org/10.48550/arXiv.2409.19732) | NeurIPS | Vision | [GitHub](https://github.com/K1nght/Unified-Unlearning-w-Remain-Geometry) | 38 |
| Kongyang Chen et al. | [Federated Unlearning for Human Activity Recognition](https://doi.org/10.48550/arXiv.2404.03659) | arXiv | Federated | — | 38 |
| Yujian Liu et al. | [Revisiting Who’s Harry Potter: Towards Targeted Unlearning from a Causal Intervention Perspective](https://doi.org/10.48550/arXiv.2407.16997) | EMNLP | LLM | [GitHub](https://github.com/ucsb-nlp-chang/causal_unlearn) | 36 |
| Ruizhe Chen et al. | [Learnable Privacy Neurons Localization in Language Models](https://doi.org/10.48550/arXiv.2405.10989) | ACL | LLM | — | 34 |
| Youming Tao et al. | [Communication Efficient and Provable Federated Unlearning](https://doi.org/10.14778/3641204.3641220) | VLDB Endowment | Federated | [GitHub](https://github.com/Happy2Git/FATS_supplement) | 34 |
| Jing Wu et al. | [Erasing Undesirable Influence in Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02632) | CVPR | Diffusion | [GitHub](https://github.com/hxxdtd/Awesome-Diffusion-Model-Unlearning) | 33 |
| Martin Pawelczyk et al. | [Machine Unlearning Fails to Remove Data Poisoning Attacks](https://doi.org/10.48550/arXiv.2406.17216) | ICLR | Other | [GitHub](https://github.com/MartinPawelczyk/OpenUnlearn) | 33 |
| Zheyuan Liu et al. | [Breaking the Trilemma of Privacy, Utility, and Efficiency via Controllable Machine Unlearning](https://doi.org/10.1145/3589334.3645669) | WWW | Other | [GitHub](https://github.com/mtuann/machine-unlearning-papers) | 33 |
| Siyuan Liang et al. | [Unlearning Backdoor Threats: Enhancing Backdoor Defense in Multimodal Contrastive Learning via Local Token Unlearning](https://doi.org/10.48550/arXiv.2403.16257) | arXiv | Vision | [GitHub](https://github.com/usnistgov/trojai-literature) | 32 |
| Binchi Zhang et al. | [Towards Certified Unlearning for Deep Neural Networks](https://doi.org/10.48550/arXiv.2408.00920) | ICML | Other | [GitHub](https://github.com/zhangbinchi/certified-deep-unlearning) | 31 |
| Karuna Bhaila, Minh-Hao Van, Xintao Wu | [Soft Prompting for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2406.12038) | NAACL | LLM | [GitHub](https://github.com/karuna-bhaila/llm_unlearning) | 31 |
| James Y. Huang et al. | [Offset Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2404.11045) | TMLR | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 31 |
| Dawen Zhang et al. | [To be forgotten or to be fair: unveiling fairness implications of machine unlearning methods](https://doi.org/10.1007/s43681-023-00398-y) | AI and Ethics | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 30 |
| Masane Fuchi, Tomohiro Takagi | [Erasing Concepts from Text-to-Image Diffusion Models with Few-shot Unlearning](https://doi.org/10.48550/arXiv.2405.07288) | BMVC | Diffusion | [GitHub](https://github.com/fmp453/few-shot-erasing) | 30 |
| Meghdad Kurmanji, Eleni Triantafillou, Peter Triantafillou | [Machine Unlearning in Learned Databases: An Experimental Analysis](https://doi.org/10.1145/3639304) | ACM on Management of Data | Other | [GitHub](https://github.com/TsinghuaDatabaseGroup/AIDB) | 29 |
| Hongbo Zhao et al. | [Continual Forgetting for Pre-Trained Vision Models](https://doi.org/10.1109/CVPR52733.2024.02705) | CVPR | Vision | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 29 |
| Youyang Qu et al. | [Learn to Unlearn: Insights Into Machine Unlearning](https://doi.org/10.1109/mc.2023.3333319) | Computer | Other | — | 29 |
| Hongcheng Gao et al. | [Meta-Unlearning on Diffusion Models: Preventing Relearning Unlearned Concepts](https://doi.org/10.1109/ICCV51701.2025.00206) | ICCV | Diffusion | [GitHub](https://github.com/sail-sg/Meta-Unlearning) | 29 |
| Somnath Basu Roy Chowdhury et al. | [Towards Scalable Exact Machine Unlearning Using Parameter-Efficient Fine-Tuning](https://doi.org/10.48550/arXiv.2406.16257) | ICLR | Other | [GitHub](https://github.com/brcsomnath/S3T) | 29 |
| Chongyu Fan et al. | [UnlearnCanvas: Stylized Image Dataset for Enhanced Machine Unlearning Evaluation in Diffusion Models](https://doi.org/10.52202/079017-3055) | NeurIPS | Diffusion | [GitHub](https://github.com/optml-group/unlearncanvas) | 29 |
| Ali Satvaty, Suzan Verberne, Fatih Turkmen | [Undesirable Memorization in Large Language Models: A Survey](https://doi.org/10.48550/arXiv.2410.02650) | arXiv | LLM | [GitHub](https://github.com/alistvt/undesirable-llm-memorization) | 29 |
| Anmol Reddy Mekala et al. | [Alternate Preference Optimization for Unlearning Factual Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2409.13474) | arXiv | LLM | [GitHub](https://github.com/molereddy/Alternate-Preference-Optimization) | 29 |
| Minh Pham et al. | [Robust Concept Erasure Using Task Vectors](https://doi.org/10.48550/arXiv.2404.03631) | arXiv | Diffusion | [GitHub](https://github.com/mnpham0417/prompt-agnostic-concept-erasure) | 29 |
| Yuke Hu et al. | [ERASER: Machine Unlearning in MLaaS via an Inference Serving-Aware Approach](https://doi.org/10.1145/3658644.3670398) | CCS | Other | [GitHub](https://github.com/gnipping/Awesome-ML-SP-Papers) | 28 |
| Chen Wu et al. | [Unlearning Backdoor Attacks in Federated Learning](https://doi.org/10.1109/CNS62487.2024.10735680) | CNS | Federated | — | 28 |
| Sungmin Cha et al. | [Towards Robust and Parameter-Efficient Knowledge Unlearning for LLMs](https://arxiv.org/abs/2408.06621) | ICLR | LLM | [GitHub](https://github.com/csm9493/efficient-llm-unlearning) | 28 |
| Andrei Muresanu et al. | [Fast Exact Unlearning for In-Context Learning Data for LLMs](https://arxiv.org/abs/2402.00751) | ICML | LLM | — | 28 |
| Hirokazu Kiyomaru et al. | [A Comprehensive Analysis of Memorization in Large Language Models](https://doi.org/10.18653/v1/2024.inlg-main.45) | International Conference on Natural Language Generation | LLM | [GitHub](https://github.com/speed1313/fast-near-duplicate-matching) | 28 |
| Zhiqi Bu et al. | [Unlearning as multi-task optimization: A normalized gradient difference approach with an adaptive learning rate](https://doi.org/10.48550/arXiv.2410.22086) | NAACL | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 28 |
| Martin Bertran et al. | [Reconstruction Attacks on Machine Unlearning: Simple Models are Vulnerable](https://doi.org/10.48550/arXiv.2405.20272) | NeurIPS | Other | — | 28 |
| Yijing Lin et al. | [Incentive and Dynamic Client Selection for Federated Unlearning](https://doi.org/10.1145/3589334.3645462) | WWW | Federated | — | 28 |
| Aditya Golatkar et al. | [CPR: Retrieval Augmented Generation for Copyright Protection](https://doi.org/10.1109/CVPR52733.2024.01176) | CVPR | Diffusion | — | 27 |
| Benjamin Biggs et al. | [Diffusion Soup: Model Merging for Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2406.08431) | ECCV | Diffusion | — | 27 |
| Niklas Stoehr et al. | [Localizing Paragraph Memorization in Language Models](https://doi.org/10.48550/arXiv.2403.19851) | arXiv | LLM | [GitHub](https://github.com/googleinterns/localizing-paragraph-memorization) | 27 |
| Hongbang Yuan et al. | [Towards Robust Knowledge Unlearning: An Adversarial Framework for Assessing and Improving Unlearning Robustness in Large Language Models](https://doi.org/10.48550/arXiv.2408.10682) | AAAI | LLM | [HF](https://huggingface.co/muse-bench/MUSE-news) | 26 |
| Trishna Chakraborty et al. | [Cross-Modal Safety Alignment: Is textual unlearning all you need?](https://doi.org/10.48550/arXiv.2406.02575) | EMNLP | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 26 |
| Bo Tian et al. | [To Forget or Not? Towards Practical Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2407.01920) | EMNLP | LLM | [GitHub](https://github.com/zjunlp/knowundo) | 26 |
| Tianqi Chen, Shujian Zhang, Mi Zhou | [Score Forgetting Distillation: A Swift, Data-Free Method for Machine Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2409.11219) | ICLR | Diffusion | [GitHub](https://github.com/tqch/score-forgetting-distillation) | 26 |
| Qizhou Wang et al. | [Towards Effective Evaluations and Comparisons for LLM Unlearning Methods](https://arxiv.org/abs/2406.09179) | ICLR | LLM | [GitHub](https://github.com/tmlr-group/Unlearning-with-Control) | 26 |
| ZhiYu Hu et al. | [Exact and Efficient Unlearning for Large Language Model-Based Recommendation](https://doi.org/10.1109/TKDE.2025.3594687) | IEEE TKDE | Recsys | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 26 |
| Hengzhu Liu et al. | [A Survey on Machine Unlearning: Techniques and New Emerged Privacy Risks](https://doi.org/10.48550/arXiv.2406.06186) | Journal of Information Security and Applications | Other | [GitHub](https://github.com/awatson246/forecast-unlearning) | 26 |
| Guangyao Dou et al. | [Avoiding Copyright Infringement via Large Language Model Unlearning](https://doi.org/10.18653/v1/2025.findings-naacl.288) | NAACL | LLM | [GitHub](https://github.com/guangyaodou/SSU_Unlearn) | 26 |
| Shashwat Goel et al. | [Corrective Machine Unlearning](https://doi.org/10.48550/arXiv.2402.14015) | TMLR | Other | [GitHub](https://github.com/drimpossible/corrective-unlearning-bench) | 26 |
| Jiahao Zhang | [Graph Unlearning with Efficient Partial Retraining](https://doi.org/10.1145/3589335.3651265) | WWW | Graph | — | 26 |
| Tianyun Yang, Juan Cao, Chang Xu | [Pruning for Robust Concept Erasing in Diffusion Models](https://doi.org/10.48550/arXiv.2405.16534) | arXiv | Diffusion | [GitHub](https://github.com/xiye7lai/Awesome-Generative-Image-Unlearning) | 26 |
| Mark He Huang, Lin Geng Foo, Jun Liu | [Learning to Unlearn for Robust Machine Unlearning](https://doi.org/10.48550/arXiv.2407.10494) | ECCV | Vision | — | 25 |
| Jacopo Bonato, Marco Cotogni, Luigi Sabetta | [Is Retain Set All You Need in Machine Unlearning? Restoring Performance of Unlearned Models with Out-Of-Distribution Images](https://doi.org/10.48550/arXiv.2404.12922) | ECCV | Vision | [GitHub](https://github.com/jbonato1/scar) | 25 |
| Harshay Shah, Andrew Ilyas, A. Ma̧dry | [Decomposing and Editing Predictions by Modeling Model Computation](https://doi.org/10.48550/arXiv.2404.11534) | ICML | Other | [GitHub](https://github.com/madrylab/modelcomponents) | 25 |
| Yushun Dong et al. | [IDEA: A Flexible Framework of Certified Unlearning for Graph Neural Networks](https://doi.org/10.1145/3637528.3671744) | KDD | Graph | [GitHub](https://github.com/yushundong/IDEA) | 25 |
| Rohit Gandikota et al. | [Erasing Conceptual Knowledge from Language Models](https://doi.org/10.48550/arXiv.2410.02760) | arXiv | LLM | [GitHub](https://github.com/rohitgandikota/erasing-llm) | 25 |
| Yuan Wang et al. | [Precise, Fast, and Low-cost Concept Erasure in Value Space: Orthogonal Complement Matters](https://doi.org/10.1109/CVPR52734.2025.02678) | CVPR | Diffusion | [GitHub](https://github.com/WYuan1001/AdaVD) | 24 |
| Hangyu Wang et al. | [Towards efficient and effective unlearning of large language models for recommendation](https://doi.org/10.1007/s11704-024-40044-2) | Frontiers of Computer Science | Recsys | [GitHub](https://github.com/CHIANGEL/Awesome-LLM-for-RecSys) | 24 |
| P. Guo et al. | [Mechanistic Unlearning: Robust Knowledge Unlearning and Editing via Mechanistic Localization](https://doi.org/10.48550/arXiv.2410.12949) | ICML | LLM | — | 24 |
| Hanlin Gu et al. | [Unlearning during Learning: An Efficient Federated Machine Unlearning Method](https://doi.org/10.48550/arXiv.2405.15474) | IJCAI | Federated | [GitHub](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) | 24 |
| Youyang Qu et al. | [The Frontier of Data Erasure: Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2403.15779) | arXiv | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 24 |
| Mengnan Zhao et al. | [Separable Multi-Concept Erasure from Diffusion Models](https://doi.org/10.48550/arXiv.2402.05947) | arXiv | Diffusion | [GitHub](https://github.com/xiye7lai/Awesome-Generative-Image-Unlearning) | 24 |
| Kongyang Chen et al. | [Machine Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2404.16841) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 24 |
| Thanh Trung Huynh et al. | [Certified Unlearning for Federated Recommendation](https://doi.org/10.1145/3706419) | ACM Transactions on Information Systems | Recsys | [GitHub](https://github.com/sohaib0075/CFRU-Federated-Recommendation-Unlearning) | 23 |
| Zichen Wang et al. | [Efficient Vertical Federated Unlearning via Fast Retraining](https://doi.org/10.1145/3657290) | ACM Transactions on Internet Technology | Federated | [GitHub](https://github.com/fizzasarfraz515/Efficient-Vertical-Federated-Unlearning-via-Fast-Retraining) | 23 |
| Yihuai Hong et al. | [Intrinsic Test of Unlearning Using Parametric Knowledge Traces](https://doi.org/10.18653/v1/2025.emnlp-main.985) | EMNLP | LLM | [GitHub](https://github.com/yihuaihong/conceptvectors) | 23 |
| Felix Koulischer et al. | [Dynamic Negative Guidance of Diffusion Models](https://doi.org/10.48550/arXiv.2410.14398) | ICLR | Diffusion | [GitHub](https://github.com/codylejang/attribute-contrastive-cfg) | 23 |
| Huiqiang Chen et al. | [Machine Unlearning via Null Space Calibration](https://doi.org/10.48550/arXiv.2404.13588) | IJCAI | Vision | [GitHub](https://github.com/HQC-ML/UNSC) | 23 |
| T. Huynh et al. | [Fast-FedUL: A Training-Free Federated Unlearning with Provable Skew Resilience](https://doi.org/10.48550/arXiv.2405.18040) | ECML/PKDD | Federated | [GitHub](https://github.com/thanhtrunghuynh93/fastFedUL) | 22 |
| XiaoHua Feng et al. | [Fine-grained Pluggable Gradient Ascent for Knowledge Unlearning in Language Models](https://doi.org/10.18653/v1/2024.emnlp-main.566) | EMNLP | LLM | — | 22 |
| Daniel Trippa et al. | [∇ τ: Gradient-based and Task-Agnostic machine Unlearning](https://doi.org/10.48550/arXiv.2403.14339) | arXiv | Other | — | 22 |
| Jai Doshi, Asa Cooper Stickland | [Does Unlearning Truly Unlearn? A Black Box Evaluation of LLM Unlearning Methods](https://doi.org/10.48550/arXiv.2411.12103) | arXiv | LLM | [GitHub](https://github.com/jaidoshi/knowledge-erasure) | 22 |
| Zhenhua Liu et al. | [Learning to Refuse: Towards Mitigating Privacy Risks in LLMs](https://doi.org/10.48550/arXiv.2407.10058) | COLING | LLM | [GitHub](https://github.com/zhliu0106/learning-to-refuse) | 21 |
| Jie Chen et al. | [Unveiling the Flaws: Exploring Imperfections in Synthetic Data and Mitigation Strategies for Large Language Models](https://doi.org/10.48550/arXiv.2406.12397) | EMNLP | LLM | [GitHub](https://github.com/pengr/LLM-Synthetic-Data) | 21 |
| Shao Shen et al. | [Label-Agnostic Forgetting: A Supervision-Free Unlearning in Deep Models](https://doi.org/10.48550/arXiv.2404.00506) | ICLR | Vision | [GitHub](https://github.com/shaofeishen768/laf) | 21 |
| Binchi Zhang et al. | [Verification of Machine Unlearning is Fragile](https://doi.org/10.48550/arXiv.2408.00929) | ICML | Other | [GitHub](https://github.com/zhangbinchi/unlearning-verification-is-fragile) | 21 |
| Ziyao Liu et al. | [Guaranteeing Data Privacy in Federated Unlearning With Dynamic User Participation](https://doi.org/10.1109/tdsc.2024.3476533) | IEEE TDSC | Federated | — | 21 |
| Shang Wang et al. | [When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?](https://doi.org/10.1109/TDSC.2025.3620832) | IEEE TDSC | LLM | [GitHub](https://github.com/infiniflow/ragflow) | 21 |
| Xuhan Zuo et al. | [Federated Learning With Blockchain-Enhanced Machine Unlearning: A Trustworthy Approach](https://doi.org/10.1109/TSC.2025.3553709) | IEEE TSC | Federated | — | 21 |
| Sheng-Yu Wang et al. | [Data Attribution for Text-to-Image Models by Unlearning Synthesized Images](https://doi.org/10.48550/arXiv.2406.09408) | NeurIPS | Diffusion | [GitHub](https://github.com/PeterWang512/AttributeByUnlearning) | 21 |
| Hanlin Gu et al. | [Ferrari: Federated Feature Unlearning via Optimizing Feature Sensitivity](https://doi.org/10.48550/arXiv.2405.17462) | NeurIPS | Federated | [GitHub](https://github.com/OngWinKent/Federated-Feature-Unlearning) | 21 |
| Alex Cloud et al. | [Gradient Routing: Masking Gradients to Localize Computation in Neural Networks](https://doi.org/10.48550/arXiv.2410.04332) | arXiv | Other | [GitHub](https://github.com/kxcloud/gradient-routing) | 21 |
| Alexey Dontsov et al. | [CLEAR: Character Unlearning in Textual and Visual Modalities](https://doi.org/10.18653/v1/2025.findings-acl.1058) | ACL | LLM | [GitHub](https://github.com/somvy/multimodal_unlearning) | 20 |
| Yu Jiang et al. | [Efficient Federated Unlearning with Adaptive Differential Privacy Preservation](https://doi.org/10.1109/BigData62323.2024.10825236) | BigData Congress [Services Society] | Federated | — | 20 |
| Yihuai Hong et al. | [Dissecting Fine-Tuning Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2410.06606) | EMNLP | LLM | [GitHub](https://github.com/yihuaihong/Dissecting-FT-Unlearning) | 20 |
| Chenlu Ding et al. | [Unified Parameter-Efficient Unlearning for LLMs](https://doi.org/10.48550/arXiv.2412.00383) | ICLR | LLM | [GitHub](https://github.com/oceanoceanna/LLMEraser) | 20 |
| Lei Gao et al. | [Ethos: Rectifying Language Models in Orthogonal Parameter Space](https://doi.org/10.48550/arXiv.2403.08994) | NAACL-HLT | LLM | [GitHub](https://github.com/leigao97/Ethos) | 20 |
| Jinghan Jia et al. | [WAGLE: Strategic Weight Attribution for Effective and Modular Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2410.17509) | NeurIPS | LLM | [GitHub](https://github.com/OPTML-Group/WAGLE) | 20 |
| Jiajun Tan et al. | [Unlink to Unlearn: Simplifying Edge Unlearning in GNNs](https://doi.org/10.48550/arXiv.2402.10695) | WWW | Graph | [GitHub](https://github.com/Sumsky21/Unlink-to-Unlearn) | 20 |
| S. Kadhe et al. | [Split, Unlearn, Merge: Leveraging Data Attributes for More Effective Unlearning in LLMs](https://doi.org/10.48550/arXiv.2406.11780) | arXiv | LLM | — | 20 |
| Bichen Wang et al. | [RKLD: Reverse KL-Divergence-based Knowledge Distillation for Unlearning Personal Information in Large Language Models](https://doi.org/10.48550/arXiv.2406.01983) | arXiv | LLM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 20 |
| Peiran Wang et al. | [Moderator: Moderating Text-to-Image Diffusion Models through Fine-grained Context-based Policies](https://doi.org/10.1145/3658644.3690327) | CCS | Diffusion | [GitHub](https://github.com/AISmithLab/Moderator) | 19 |
| Juwon Seo et al. | [Generative Unlearning for Any Identity](https://doi.org/10.1109/CVPR52733.2024.00874) | CVPR | Diffusion | [GitHub](https://github.com/KHU-AGI/GUIDE) | 19 |
| K. Srivatsan et al. | [STEREO: A Two-Stage Framework for Adversarially Robust Concept Erasing from Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02213) | CVPR | Diffusion | [GitHub](https://github.com/koushiksrivats/robust-concept-erasing) | 19 |
| Yan Scholten, Stephan Günnemann, Leo Schwinn | [A Probabilistic Perspective on Unlearning and Alignment for Large Language Models](https://doi.org/10.48550/arXiv.2410.03523) | ICLR | LLM | [GitHub](https://github.com/yascho/probabilistic-unlearning) | 19 |
| Lijie Hu et al. | [Editable Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2405.15476) | ICML | Vision | [GitHub](https://github.com/kaustpradalab/ECBM) | 19 |
| Yijing Lin et al. | [Scalable Federated Unlearning via Isolated and Coded Sharding](https://doi.org/10.48550/arXiv.2401.15957) | IJCAI | Federated | [GitHub](https://github.com/karpathy/nanoGPT) | 19 |
| Kang Gu et al. | [Second-Order Information Matters: Revisiting Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2403.10557) | arXiv | LLM | — | 19 |
| Tianyu Yang et al. | [CLIPErase: Efficient Unlearning of Visual-Textual Associations in CLIP](https://doi.org/10.48550/arXiv.2410.23330) | ACL | Vision | [GitHub](https://github.com/Tianyu-yang-anna/ClipErase-ACL) | 18 |
| Mengru Wang et al. | [Detoxifying Large Language Models via Knowledge Editing](https://doi.org/10.18653/v1/2024.acl-long.171) | ACL (1) | LLM | [GitHub](https://github.com/zjunlp/KnowledgeEditingPapers) | 18 |
| Chunxiao Li et al. | [An overview of machine unlearning](https://doi.org/10.1016/j.hcc.2024.100254) | High-Confidence Computing | Other | [GitHub](https://github.com/DlEnginner/bias_chest_xrays) | 18 |
| Yanli Yuan et al. | [Toward Efficient and Robust Federated Unlearning in IoT Networks](https://doi.org/10.1109/jiot.2024.3378329) | IEEE IoT-J | Federated | — | 18 |
| H. Lee et al. | [Contrastive Unlearning: A Contrastive Approach to Machine Unlearning](https://doi.org/10.48550/arXiv.2401.10458) | IJCAI | Vision | [GitHub](https://github.com/Hongkyu-Lee/Contrastive-Unlearning) | 18 |
| Myeongseob Ko et al. | [Boosting Alignment for Post-Unlearning Text-to-Image Generative Models](https://doi.org/10.48550/arXiv.2412.07808) | NeurIPS | Diffusion | [GitHub](https://github.com/reds-lab/Restricted_gradient_diversity_unlearning) | 18 |
| Zhexin Zhang et al. | [From Theft to Bomb-Making: The Ripple Effect of Unlearning in Defending Against Jailbreak Attacks](https://arxiv.org/abs/2407.02855) | arXiv | LLM | [GitHub](https://github.com/thu-coai/safeunlearning) | 18 |
| Zhiwei Zhang et al. | [Does your LLM truly unlearn? An embarrassingly simple approach to recover unlearned knowledge](https://doi.org/10.48550/arXiv.2410.16454) | arXiv | LLM | — | 18 |
| Tianle Gu et al. | [MEOW: MEMOry Supervised LLM Unlearning Via Inverted Facts](https://doi.org/10.48550/arXiv.2409.11844) | arXiv | LLM | [GitHub](https://github.com/Carol-gutianle/MEOW) | 18 |
| Md. Rafi Ur Rashid et al. | [Forget to Flourish: Leveraging Machine-Unlearning on Pretrained Language Models for Privacy Leakage](https://doi.org/10.48550/arXiv.2408.17354) | AAAI | LLM | [HF](https://huggingface.co/docs/hub/en) | 17 |
| Masaru Isonuma, Ivan Titov | [Unlearning Traces the Influential Training Data of Language Models](https://doi.org/10.18653/v1/2024.acl-long.343) | ACL | LLM | [GitHub](https://github.com/misonuma/untrac) | 17 |
| Omkar Dige et al. | [Can Machine Unlearning Reduce Social Bias in Language Models?](https://doi.org/10.18653/v1/2024.emnlp-industry.71) | EMNLP | LLM | [GitHub](https://github.com/VectorInstitute/bias-mitigation-unlearning) | 17 |
| Shangyu Xing et al. | [EFUF: Efficient Fine-Grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2402.09801) | EMNLP | LLM | [GitHub](https://github.com/starreeze/efuf) | 17 |
| Yingzi Ma et al. | [Benchmarking Vision Language Model Unlearning via Fictitious Facial Identity Dataset](https://doi.org/10.48550/arXiv.2411.03554) | ICLR | Vision | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 17 |
| Heng Xu et al. | [Update Selective Parameters: Federated Machine Unlearning Based on Model Explanation](https://doi.org/10.1109/tbdata.2024.3409947) | IEEE TBD | Federated | — | 17 |
| Alessandro Achille et al. | [AI model disgorgement: Methods and choices](https://doi.org/10.1073/pnas.2307304121) | National Academy of Sciences | Other | — | 17 |
| Jinqi Luo et al. | [PaCE: Parsimonious Concept Engineering for Large Language Models](https://doi.org/10.48550/arXiv.2406.04331) | NeurIPS | LLM | [GitHub](https://github.com/peterljq/Parsimonious-Concept-Engineering) | 17 |
| Yash Sinha, Murari Mandal, Mohan S. Kankanhalli | [UnStar: Unlearning with Self-Taught Anti-Sample Reasoning for LLMs](https://doi.org/10.48550/arXiv.2410.17050) | TMLR | LLM | — | 17 |
| Siqiao Mu, Diego Klabjan | [Rewind-to-Delete: Certified Machine Unlearning for Nonconvex Functions](https://doi.org/10.48550/arXiv.2409.09778) | arXiv | Other | [GitHub](https://github.com/siqiaomu/r2d) | 17 |
| Minseok Choi et al. | [SNAP: Unlearning Selective Knowledge in Large Language Models with Negative Instructions](https://doi.org/10.48550/arXiv.2406.12329) | arXiv | LLM | — | 17 |
| Tomer Ashuach, Martin Tutek, Yonatan Belinkov | [REVS: Unlearning Sensitive Information in Language Models via Rank Editing in the Vocabulary Space](https://doi.org/10.48550/arXiv.2406.09325) | ACL | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 16 |
| Yangsibo Huang et al. | [Unlearn and Burn: Adversarial Machine Unlearning Requests Destroy Model Accuracy](https://doi.org/10.48550/arXiv.2410.09591) | ICLR | Vision | [GitHub](https://github.com/daogaoliu/unlearning-under-adversary) | 16 |
| Anik Islam et al. | [A Federated Unlearning-Based Secure Management Scheme to Enable Automation in Smart Consumer Electronics Facilitated by Digital Twin](https://doi.org/10.1109/tce.2024.3396723) | IEEE Transactions on Consumer Electronics | Federated | — | 16 |
| Kun Gao et al. | [Defending against gradient inversion attacks in federated learning via statistical machine unlearning](https://doi.org/10.1016/j.knosys.2024.111983) | Knowledge-Based Systems | Federated | — | 16 |
| Zirui Huang, Yunlong Mao, Sheng Zhong | [UBA-Inf: Unlearning Activated Backdoor Attack with Influence-Driven Camouflage](https://www.semanticscholar.org/paper/3cbddd0096c05459f8589f0dd6ec2c49e3f8a00f) | USENIX Security | Other | [GitHub](https://github.com/Huangzirui1206/UBA-Inf) | 16 |
| Vinith M. Suriyakumar et al. | [Unstable Unlearning: The Hidden Risk of Concept Resurgence in Diffusion Models](https://doi.org/10.48550/arXiv.2410.08074) | arXiv | Diffusion | [GitHub](https://github.com/Giphy/celeb-detection-oss) | 16 |
| Wenhao Wang et al. | [Replication in Visual Diffusion Models: A Survey and Outlook](https://doi.org/10.48550/arXiv.2408.00001) | arXiv | Diffusion | [GitHub](https://github.com/wangwenhao0716/awesome-diffusion-replication) | 16 |
| Xinwei Wu et al. | [Mitigating Privacy Seesaw in Large Language Models: Augmented Privacy Neuron Editing via Activation Patching](https://doi.org/10.18653/v1/2024.findings-acl.315) | ACL | LLM | [GitHub](https://github.com/flamewei123/APNEAP-) | 15 |
| Lu Yi, Zhewei Wei | [Scalable and Certifiable Graph Unlearning: Overcoming the Approximation Error Barrier](https://arxiv.org/abs/2408.09212) | ICLR | Graph | [GitHub](https://github.com/luyi256/ScaleGUN) | 15 |
| Yu Wang et al. | [Large Scale Knowledge Washing](https://doi.org/10.48550/arXiv.2405.16720) | ICLR | LLM | [GitHub](https://github.com/wangyu-ustc/LargeScaleWashing) | 15 |
| Weijian Su et al. | [F2UL: Fairness-Aware Federated Unlearning for Data Trading](https://doi.org/10.1109/tmc.2024.3429228) | IEEE TMC | Federated | [GitHub](https://github.com/suweijian1996/F2UL) | 15 |
| Mengde Han et al. | [Vertical Federated Unlearning via Backdoor Certification](https://doi.org/10.1109/TSC.2025.3536312) | IEEE TSC | Federated | — | 15 |
| Alexey Kravets, Vinay P. Namboodiri | [Zero-Shot Class Unlearning in CLIP with Synthetic Samples](https://doi.org/10.1109/WACV61041.2025.00629) | WACV | Vision | [GitHub](https://github.com/akres001/Zero-Shot-Class-Unlearning-in-CLIP-with-Synthetic-Samples) | 15 |
| Shiji Zhou et al. | [On the Limitations and Prospects of Machine Unlearning for Generative AI](https://doi.org/10.48550/arXiv.2408.00376) | arXiv | Other | — | 15 |
| Li Shan et al. | [Lifelong Learning and Selective Forgetting via Contrastive Strategy](https://doi.org/10.48550/arXiv.2405.18663) | arXiv | Vision | [GitHub](https://github.com/XikunHuang/daily_paper) | 15 |
| Yi Xu | [Machine Unlearning for Traditional Models and Large Language Models: A Short Survey](https://doi.org/10.48550/arXiv.2404.01206) | arXiv | Other | — | 15 |
| Chongyang Gao et al. | [Practical Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2407.10223) | arXiv | LLM | — | 15 |
| Guanhua Ye et al. | [Heterogeneous decentralised machine unlearning with seed model distillation](https://doi.org/10.1049/cit2.12281) | CAAI Transactions on Intelligence Technology | Federated | — | 14 |
| Anudeep Das et al. | [Espresso: Robust Concept Filtering in Text-to-Image Models](https://doi.org/10.1145/3714393.3726502) | Conference on Data and Application Security and Privacy | Diffusion | [GitHub](https://github.com/ssg-research/concept-filtering) | 14 |
| Deepak Sridhar, Nuno Vasconcelos | [Prompt Sliders for Fine-Grained Control, Editing and Erasing of Concepts in Diffusion Models](https://doi.org/10.48550/arXiv.2409.16535) | ECCV Workshops | Diffusion | [GitHub](https://github.com/Cocozzj/Self-Correcting-LLM) | 14 |
| Jinxu Lin et al. | [Diffusion Attribution Score: Evaluating Training Data Influence in Diffusion Model](https://doi.org/10.48550/arXiv.2410.18639) | ICLR | Diffusion | [GitHub](https://github.com/Jinxu-Lin/DAS) | 14 |
| Zonglin Di et al. | [Adversarial Machine Unlearning](https://doi.org/10.48550/arXiv.2406.07687) | ICLR | Other | [GitHub](https://github.com/daogaoliu/unlearning-under-adversary) | 14 |
| Ziyao Liu et al. | [Privacy-Preserving Federated Unlearning With Certified Client Removal](https://doi.org/10.1109/TIFS.2025.3555868) | IEEE T-IFS | Federated | — | 14 |
| Weiqi Wang et al. | [FedU: Federated Unlearning via User-Side Influence Approximation Forgetting](https://doi.org/10.1109/tdsc.2024.3520614) | IEEE TDSC | Federated | — | 14 |
| Shao Shen et al. | [CaMU: Disentangling Causal Effects in Deep Model Unlearning](https://doi.org/10.48550/arXiv.2401.17504) | SDM | Other | [GitHub](https://github.com/ShaofeiShen768/CaMU) | 14 |
| Jianing Zhu et al. | [Decoupling the Class Label and the Target Concept in Machine Unlearning](https://doi.org/10.48550/arXiv.2406.08288) | arXiv | Vision | [GitHub](https://github.com/ZFancy/TARF) | 14 |
| Atakan Seyitoglu et al. | [Extracting Unlearned Information from LLMs with Activation Steering](https://doi.org/10.48550/arXiv.2411.02631) | arXiv | LLM | — | 14 |
| Tianwei Xiong et al. | [Editing Massive Concepts in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2403.13807) | arXiv | Diffusion | [GitHub](https://github.com/silentview/emcid) | 14 |
| Anh-Vu Bui et al. | [Removing Undesirable Concepts in Text-to-Image Generative Models with Learnable Prompts](https://doi.org/10.48550/arXiv.2403.12326) | arXiv | Diffusion | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 14 |
| Zhe-Rui Yang et al. | [Erase then Rectify: A Training-Free Parameter Editing Approach for Cost-Effective Graph Unlearning](https://doi.org/10.48550/arXiv.2409.16684) | AAAI | Graph | [GitHub](https://github.com/AllminerLab/ETR) | 13 |
| Weitao Ma et al. | [Unveiling Entity-Level Unlearning for Large Language Models: A Comprehensive Analysis](https://arxiv.org/abs/2406.15796) | COLING | LLM | — | 13 |
| Minseok Choi, Kyunghyun Min, Jaegul Choo | [Cross-Lingual Unlearning of Selective Knowledge in Multilingual Language Models](https://doi.org/10.48550/arXiv.2406.12354) | EMNLP | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 13 |
| Runtao Liu et al. | [AlignGuard: Scalable Safety Alignment for Text-to-Image Generation](https://doi.org/10.1109/ICCV51701.2025.01581) | ICCV | Diffusion | [GitHub](https://github.com/Visualignment/SafetyDPO) | 13 |
| Eliahu Horwitz, Jonathan Kahana, Yedid Hoshen | [Recovering the Pre-Fine-Tuning Weights of Generative Models](https://doi.org/10.48550/arXiv.2402.10208) | ICML | Diffusion | [GitHub](https://github.com/eliahuhorwitz/Spectral-DeTuning) | 13 |
| Xiaoyu Xia et al. | [Edge Unlearning is Not “on Edge”! an Adaptive Exact Unlearning System on Resource-Constrained Devices](https://doi.org/10.1109/SP61157.2025.00095) | IEEE S&P | Other | [GitHub](https://github.com/XLab-hub/CAUSE) | 13 |
| Stefan Schoepf, Jack Foster, A. Brintrup | [Potion: Towards Poison Unlearning](https://doi.org/10.48550/arXiv.2406.09173) | J. Data-centric Mach. Learn. Res | Vision | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 13 |
| Chao-Jun Chen et al. | [CURE4Rec: A Benchmark for Recommendation Unlearning with Deeper Influence](https://doi.org/10.48550/arXiv.2408.14393) | NeurIPS | Recsys | [GitHub](https://github.com/xiye7lai/CURE4Rec) | 13 |
| Youssef Allouah et al. | [The Utility and Complexity of In- and Out-of-Distribution Machine Unlearning](https://doi.org/10.48550/arXiv.2412.09119) | arXiv | Other | — | 13 |
| Kristian Georgiev et al. | [Attribute-to-Delete: Machine Unlearning via Datamodel Matching](https://doi.org/10.48550/arXiv.2410.23232) | arXiv | Other | [HF](https://huggingface.co/datasets/machine-unlearning-bench/data-unlearning-bench) | 13 |
| Dohyun Lee et al. | [Protecting Privacy Through Approximating Optimal Parameters for Sequence Unlearning in Language Models](https://doi.org/10.48550/arXiv.2406.14091) | ACL | LLM | [HF](https://huggingface.co/datasets/monology) | 12 |
| Yizhou Dang et al. | [Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences](https://doi.org/10.1145/3706633) | ACM Transactions on Information Systems | Recsys | [GitHub](https://github.com/KingGugu/GFEraser) | 12 |
| Reza Shirkavand et al. | [Efficient Fine-Tuning and Concept Suppression for Pruned Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.01735) | CVPR | Diffusion | [GitHub](https://github.com/rezashkv/unlearn-ft) | 12 |
| Houzhe Wang et al. | [Goldfish: An Efficient Federated Unlearning Framework](https://doi.org/10.1109/DSN58291.2024.00035) | Dependable Systems and Networks | Federated | [GitHub](https://github.com/xiao-jian-zi/MU-Goldfish-An-Efficient-Federated-Unlearning-Framework) | 12 |
| Abhinav Joshi et al. | [Towards Robust Evaluation of Unlearning in LLMs via Data Transformations](https://doi.org/10.18653/v1/2024.findings-emnlp.706) | EMNLP | LLM | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 12 |
| Shuyi Wang, Bing Liu, G. Zuccon | [How to Forget Clients in Federated Online Learning to Rank?](https://doi.org/10.48550/arXiv.2401.13410) | European Conference on Information Retrieval | Federated | [GitHub](https://github.com/ielab/2024-ECIR-foltr-unlearning) | 12 |
| Jing Wu, Mehrtash Harandi | [MUNBa: Machine Unlearning Via Nash Bargaining](https://doi.org/10.1109/ICCV51701.2025.00452) | ICCV | Vision | [GitHub](https://github.com/JingWu321/MUNBa) | 12 |
| Saemi Moon et al. | [Holistic Unlearning Benchmark: A Multi-Faceted Evaluation for Text-to-Image Diffusion Model Unlearning](https://doi.org/10.1109/ICCV51701.2025.01518) | ICCV | Diffusion | [GitHub](https://github.com/ml-postech/HUB) | 12 |
| Jiacheng Du, Zhibo Wang, Kui Ren | [Textual Unlearning Gives a False Sense of Unlearning](https://doi.org/10.48550/arXiv.2406.13348) | ICML | LLM | [GitHub](https://github.com/wanggroupAI/TextualUnlearning) | 12 |
| Chenxu Zhao et al. | [Rethinking Adversarial Robustness in the Context of the Right to be Forgotten](https://doi.org/10.31274/td-20251215-153) | ICML | Vision | — | 12 |
| Jack Foster et al. | [An Information Theoretic Approach to Machine Unlearning](https://arxiv.org/abs/2402.01401) | TMLR | Other | [GitHub](https://github.com/jwf40/Information-Theoretic-Unlearning) | 12 |
| Jiali Cheng, Hadi Amiri | [MU-Bench: A Multitask Multimodal Benchmark for Machine Unlearning](https://doi.org/10.48550/arXiv.2406.14796) | arXiv | Other | [GitHub](https://github.com/CLU-UML/MU-Bench) | 12 |
| Jiaqi Shao et al. | [Federated Unlearning: a Perspective of Stability and Fairness](https://doi.org/10.48550/arXiv.2402.01276) | arXiv | Federated | — | 12 |
| Keltin Grimes et al. | [Gone but Not Forgotten: Improved Benchmarks for Machine Unlearning](https://doi.org/10.48550/arXiv.2405.19211) | arXiv | Other | — | 12 |
| Stefan Schoepf, Jack Foster, A. Brintrup | [Parameter-tuning-free data entry error unlearning with adaptive selective synaptic dampening](https://doi.org/10.48550/arXiv.2402.10098) | arXiv | Vision | — | 12 |
| Anubhav Jain et al. | [TraSCE: Trajectory Steering for Concept Erasure](https://doi.org/10.48550/arXiv.2412.07658) | arXiv | Diffusion | [GitHub](https://github.com/anubhav1997/TraSCE) | 12 |
| Yufan Liu et al. | [RealEra: Semantic-level Concept Erasure via Neighbor-Concept Mining](https://doi.org/10.48550/arXiv.2410.09140) | arXiv | Diffusion | — | 12 |
| Dongjae Jeon et al. | [An Information Theoretic Evaluation Metric for Strong Unlearning](https://doi.org/10.1609/aaai.v40i26.39373) | AAAI | Other | [GitHub](https://github.com/pytorch/examples/tree) | 11 |
| Xinyi Sheng, Wei Bao, Liming Ge | [Robust Federated Unlearning](https://doi.org/10.1145/3627673.3679817) | CIKM | Federated | [GitHub](https://github.com/stcebra/Robust-Federated-Unlearning) | 11 |
| Dasol Choi et al. | [Towards Efficient Machine Unlearning with Data Augmentation: Guided Loss-Increasing (GLI) to Prevent the Catastrophic Model Utility Drop](https://doi.org/10.1109/CVPRW63382.2024.00014) | CVPR | Vision | [GitHub](https://github.com/Dasol-Choi/Guided_Loss_Increasing) | 11 |
| Chaohao Fu, Weijia Jia, Na Ruan | [Client-Free Federated Unlearning via Training Reconstruction with Anchor Subspace Calibration](https://doi.org/10.1109/icassp48485.2024.10447085) | ICASSP | Federated | — | 11 |
| Zibin Pan et al. | [Multi-Objective Large Language Model Unlearning](https://doi.org/10.1109/ICASSP49660.2025.10889776) | ICASSP | LLM | [GitHub](https://github.com/zibinpan/MOLLM) | 11 |
| Mansi Sakarvadia et al. | [Mitigating Memorization In Language Models](https://doi.org/10.48550/arXiv.2410.02159) | ICLR | LLM | [GitHub](https://github.com/msakarvadia/memorization) | 11 |
| Syed Irfan Ali Meerza, Amir Sadovnik, Jian Liu | [ConFUSE: Confusion-based Federated Unlearning with Salience Exploration](https://doi.org/10.1109/ISVLSI61997.2024.00083) | IEEE Computer Society Annual Symposium on VLSI | Federated | — | 11 |
| Zhengbao He et al. | [Towards Natural Machine Unlearning](https://doi.org/10.1109/TPAMI.2025.3597350) | IEEE TPAMI | Vision | [GitHub](https://github.com/ZhengbaoHe/NatMU) | 11 |
| Layan Jaman, Reem Alsharabi, Passent Elkafrawy | [Machine Unlearning: An Overview of the Paradigm Shift in the Evolution of AI](https://doi.org/10.1109/LT60077.2024.10469232) | L&T | Other | — | 11 |
| Ziang Chen et al. | [Certified Machine Unlearning via Noisy Stochastic Gradient Descent](https://doi.org/10.52202/079017-1228) | NeurIPS | Other | [GitHub](https://github.com/Graph-COM/SGD_unlearning) | 11 |
| Muhammad Ameen et al. | [Addressing unreliable local models in federated learning through unlearning](https://doi.org/10.1016/j.neunet.2024.106688) | Neural Networks | Federated | — | 11 |
| Yoon Wha Jung et al. | [Attack and Reset for Unlearning: Exploiting Adversarial Noise toward Machine Unlearning through Parameter Re-initialization](https://doi.org/10.48550/arXiv.2401.08998) | arXiv | Vision | — | 11 |
| Romit Chatterjee et al. | [A Unified Framework for Continual Learning and Machine Unlearning](https://doi.org/10.48550/arXiv.2408.11374) | arXiv | Other | [GitHub](https://github.com/respailab/CLMUL) | 11 |
| Bhavika Sachdeva et al. | [Machine Unlearning for Recommendation Systems: An Insight](https://doi.org/10.48550/arXiv.2401.10942) | arXiv | Recsys | — | 11 |
| Shen Lin et al. | [GDR-GMA: Machine Unlearning via Direction-Rectified and Magnitude-Adjusted Gradients](https://doi.org/10.1145/3664647.3680775) | ACM MM | Vision | — | 10 |
| Heng Xu et al. | [Don't Forget Too Much: Towards Machine Unlearning on Feature Level](https://doi.org/10.1109/tdsc.2024.3432169) | IEEE TDSC | Vision | — | 10 |
| Akash Dhasade et al. | [QuickDrop: Efficient Federated Unlearning via Synthetic Data Generation](https://doi.org/10.1145/3652892.3700764) | International Middleware Conference | Federated | [GitHub](https://github.com/fardeenfarhat/quickdrop-federated-unlearning) | 10 |
| Zhi-Hui Deng, Luyang Luo, Hao Chen | [Enable the Right to be Forgotten with Federated Client Unlearning in Medical Imaging](https://doi.org/10.48550/arXiv.2407.02356) | MICCAI | Federated | [GitHub](https://github.com/dzp2095/FCU) | 10 |
| Jiadong Pan et al. | [Leveraging Catastrophic Forgetting to Develop Safe Diffusion Models against Malicious Finetuning](https://doi.org/10.52202/079017-3658) | NeurIPS | Diffusion | — | 10 |
| Seonguk Seo, Dongwan Kim, Bohyung Han | [Revisiting Machine Unlearning with Dimensional Alignment](https://doi.org/10.1109/WACV61041.2025.00317) | WACV | Vision | — | 10 |
| Aakash Sen Sharma et al. | [Unlearning or Concealment? A Critical Analysis and Evaluation Metrics for Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2409.05668) | arXiv | Diffusion | [GitHub](https://github.com/respailab/unlearning-or-concealment) | 10 |
| Dasol Choi, Dongbin Na | [Distribution-Level Feature Distancing for Machine Unlearning: Towards a Better Trade-off Between Model Utility and Forgetting](https://doi.org/10.48550/arXiv.2409.14747) | AAAI | Vision | — | 9 |
| Minseok Choi et al. | [Opt-Out: Investigating Entity-Level Unlearning for Large Language Models via Optimal Transport](https://doi.org/10.18653/v1/2025.acl-long.1371) | ACL | LLM | [HF](https://huggingface.co/datasets/6rightjade/ELUDe) | 9 |
| Zhaohan Zhang, Ziquan Liu, Ioannis Patras | [Get Confused Cautiously: Textual Sequence Memorization Erasure with Selective Entropy Maximization](https://doi.org/10.48550/arXiv.2408.04983) | COLING | LLM | — | 9 |
| Vitali Petsiuk, K. Saenko | [Concept Arithmetics for Circumventing Concept Inhibition in Diffusion Models](https://doi.org/10.48550/arXiv.2404.13706) | ECCV | Diffusion | [GitHub](https://github.com/SarahRastegar/Best-Papers-Top-Venues) | 9 |
| Die Chen et al. | [Growth Inhibitors for Suppressing Inappropriate Image Concepts in Diffusion Models](https://arxiv.org/abs/2408.01014) | ICLR | Diffusion | [GitHub](https://github.com/notAI-tech/NudeNet) | 9 |
| Zhenguo Ma et al. | [Hier-FUN: Hierarchical Federated Learning and Unlearning in Heterogeneous Edge Computing](https://doi.org/10.1109/jiot.2024.3502666) | IEEE IoT-J | Federated | — | 9 |
| Yuyuan Li et al. | [A Survey on Recommendation Unlearning: Fundamentals, Taxonomy, Evaluation, and Open Questions](https://doi.org/10.1109/TKDE.2025.3638174) | IEEE TKDE | Recsys | — | 9 |
| Rui Ma et al. | [A Dataset and Benchmark for Copyright Infringement Unlearning from Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.12052) | Lecture Notes in Computer Science | Diffusion | [GitHub](https://github.com/datar001/Awesome-AD-on-T2IDM) | 9 |
| Wenhan Chang et al. | [Class Machine Unlearning for Complex Data via Concepts Inference and Data Poisoning](https://doi.org/10.48550/arXiv.2405.15662) | arXiv | Vision | [HF](https://huggingface.co/changwh5/Concepts_Poison_Unlearning_7B) | 9 |
| Yiwen Tu, Pingbang Hu, Jiaqi Ma | [Towards Reliable Empirical Machine Unlearning Evaluation: A Game-Theoretic View](https://doi.org/10.48550/arXiv.2404.11577) | arXiv | Other | — | 9 |
| Quang H. Nguyen, Hoang Phan, Khoa D. Doan | [Unveiling Concept Attribution in Diffusion Models](https://doi.org/10.48550/arXiv.2412.02542) | arXiv | Diffusion | [GitHub](https://github.com/mail-research/CAD-attribution4diffusion) | 9 |
| Shaojie Shi et al. | [ULMR: Unlearning Large Language Models via Negative Response and Model Parameter Average](https://doi.org/10.18653/v1/2024.emnlp-industry.57) | EMNLP | LLM | — | 8 |
| Xavier F. Cadet et al. | [Deep Unlearn: Benchmarking Machine Unlearning for Image Classification](https://doi.org/10.1109/EuroSP63326.2025.00058) | European Symposium on Security and Privacy | Vision | [GitHub](https://github.com/xcadet/deepunlearn) | 8 |
| Lun Wang, Om Thakkar, Rajiv Mathews | [Unintended Memorization in Large ASR Models, and How to Mitigate It](https://doi.org/10.1109/icassp48485.2024.10446083) | ICASSP | Other | — | 8 |
| Xinwen Cheng et al. | [Remaining-data-free Machine Unlearning by Suppressing Sample Contribution](https://arxiv.org/abs/2402.15109) | ICLR Poster | Other | [GitHub](https://github.com/poppopbean0903/MU-Mis) | 8 |
| Zikui Cai, Yaoteng Tan, M. S. Asif | [Targeted Unlearning with Single Layer Unlearning Gradient](https://arxiv.org/abs/2407.11867) | ICML | Diffusion | [GitHub](https://github.com/CSIPlab/slug) | 8 |
| Chao-Jun Chen et al. | [One for All: A Universal Generator for Concept Unlearnability via Multi-Modal Alignment](https://www.semanticscholar.org/paper/3c260518c36c9e74d63b10f70330a97a707bbcc9) | ICML | Diffusion | — | 8 |
| Zhiqiang Xie et al. | [Adaptive Clipping and Distillation Enabled Federated Unlearning](https://doi.org/10.1109/ICWS62655.2024.00094) | ICWS | Federated | — | 8 |
| Wathsara Daluwatta et al. | [DT-FU: Digital Twin-Driven Federated Unlearning for Resilient Vehicular Networks in the 6G Era](https://doi.org/10.1109/mcom.001.2400229) | IEEE Communications Magazine | Federated | — | 8 |
| Atef H. Bondok et al. | [Securing One-Class Federated Learning Classifiers Against Trojan Attacks in Smart Grid](https://doi.org/10.1109/jiot.2024.3481213) | IEEE IoT-J | Federated | — | 8 |
| Chenhan Zhang et al. | [Forgetting and Remembering Are Both You Need: Balanced Graph Structure Unlearning](https://doi.org/10.1109/tifs.2024.3422799) | IEEE T-IFS | Graph | — | 8 |
| Heng Xu et al. | [Really Unlearned? Verifying Machine Unlearning via Influential Sample Pairs](https://doi.org/10.1109/TDSC.2025.3620308) | IEEE TDSC | Other | — | 8 |
| Tyler Lizzo, Larry Heck | [UNLEARN Efficient Removal of Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2408.04140) | NAACL | LLM | — | 8 |
| Jack Foster, Stefan Schoepf, A. Brintrup | [Loss-Free Machine Unlearning](https://doi.org/10.48550/arXiv.2402.19308) | Tiny Papers @ ICLR | Vision | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 8 |
| Jiahao Xu, Zikai Zhang, Rui Hu | [Identify Backdoored Model in Federated Learning via Individual Unlearning](https://doi.org/10.1109/WACV61041.2025.00773) | WACV | Federated | [GitHub](https://github.com/JiiahaoXU/MASA) | 8 |
| Reza Nasirigerdeh et al. | [Machine Unlearning for Medical Imaging](https://doi.org/10.48550/arXiv.2407.07539) | arXiv | Vision | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 8 |
| Chenhao Zhang et al. | [GENIU: A Restricted Data Access Unlearning for Imbalanced Data](https://doi.org/10.48550/arXiv.2406.07885) | arXiv | Vision | — | 8 |
| Zonglin Di et al. | [Label Smoothing Improves Machine Unlearning](https://doi.org/10.48550/arXiv.2406.07698) | arXiv | Vision | — | 8 |
| Ling Han et al. | [Towards Independence Criterion in Machine Unlearning of Features and Labels](https://doi.org/10.48550/arXiv.2403.08124) | arXiv | Other | — | 8 |
| Yijing Lin et al. | [Blockchain-enabled Trustworthy Federated Unlearning](https://doi.org/10.48550/arXiv.2401.15917) | arXiv | Federated | [GitHub](https://github.com/xuperchain/xuperchain) | 8 |
| Michael Fore et al. | [Unlearning Climate Misinformation in Large Language Models](https://doi.org/10.48550/arXiv.2405.19563) | CLIMATENLP | LLM | [GitHub](https://github.com/mikeFore4/climateQA) | 7 |
| Lingyun Zhang et al. | [Concept Replacer: Replacing Sensitive Concepts in Diffusion Models via Precision Localization](https://doi.org/10.1109/CVPR52734.2025.00765) | CVPR | Diffusion | [GitHub](https://github.com/zhang-lingyun/ConceptReplacer) | 7 |
| Zulfiqar Ali et al. | [Evaluating Machine Unlearning: Applications, Approaches, and Accuracy](https://doi.org/10.1002/eng2.13081) | Engineering Reports | Other | — | 7 |
| Robert Geirhos et al. | [Towards flexible perception with visual memory](https://doi.org/10.48550/arXiv.2408.08172) | ICML | Vision | [GitHub](https://github.com/google-deepmind/visual-memory) | 7 |
| Weiqi Wang et al. | [SCU: An Efficient Machine Unlearning Scheme for Deep Learning Enabled Semantic Communications](https://doi.org/10.1109/tifs.2024.3516576) | IEEE T-IFS | Other | [GitHub](https://github.com/wwq5-code/SCU) | 7 |
| Xiao Liu et al. | [BlockFUL: Enabling Unlearning in Blockchained Federated Learning](https://doi.org/10.1109/TIFS.2025.3583109) | IEEE T-IFS | Federated | — | 7 |
| Chenghao Shao et al. | [Machine Unlearning for Seizure Prediction](https://doi.org/10.1109/tcds.2024.3395663) | IEEE Transactions on Cognitive and Developmental Systems | Other | — | 7 |
| Wathsara Daluwatta et al. | [UaaS-SFL: Unlearning as a Service for Safeguarding Federated Learning](https://doi.org/10.1109/tnsm.2024.3520109) | IEEE Transactions on Network and Service Management | Federated | — | 7 |
| Miao Xu | [Machine Unlearning: Challenges in Data Quality and Access](https://doi.org/10.24963/ijcai.2024/987) | IJCAI | Other | — | 7 |
| Haoyu Tang et al. | [Learn while Unlearn: An Iterative Unlearning Framework for Generative Language Models](https://doi.org/10.1109/ICDM65498.2025.00082) | Industrial Conference on Data Mining | LLM | [GitHub](https://github.com/himalalps/ICU) | 7 |
| Yu Jiang, Chee Wei Tan, Kwok‐Yan Lam | [FedUHB: Accelerating Federated Unlearning via Polyak Heavy Ball Method](https://doi.org/10.1109/itw61385.2024.10807033) | Information Theory Workshop | Federated | — | 7 |
| Reihaneh Torkzadehmahani et al. | [Improved Localized Machine Unlearning Through the Lens of Memorization](https://doi.org/10.48550/arXiv.2412.02432) | TMLR | Vision | [GitHub](https://github.com/reihaneh-torkzadehmahani/DEL-Unlearning) | 7 |
| Cheng-Long Wang et al. | [Towards Lifecycle Unlearning Commitment Management: Measuring Sample-level Approximate Unlearning Completeness](https://arxiv.org/abs/2403.12830) | arXiv | Other | — | 7 |
| Yegor Klochkov, Yang Liu | [Revisiting inverse Hessian vector products for calculating influence functions](https://doi.org/10.48550/arXiv.2409.17357) | arXiv | Other | — | 7 |
| Hongxiang Zhang, Yifeng He, Hao Chen | [SteerDiff: Steering towards Safe Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2410.02710) | arXiv | Diffusion | — | 7 |
| X. You et al. | [RRL: Recommendation Reverse Learning](https://doi.org/10.1609/aaai.v38i8.28782) | AAAI | Recsys | — | 6 |
| Shota Takashiro et al. | [Answer When Needed, Forget When Not: Language Models Pretend to Forget via In-Context Knowledge Unlearning](https://doi.org/10.48550/arXiv.2410.00382) | ACL | LLM | — | 6 |
| M. Rusanovsky et al. | [Memories of Forgotten Concepts](https://doi.org/10.1109/CVPR52734.2025.00282) | CVPR | Diffusion | [GitHub](https://github.com/matanr/Memories_of_Forgotten_Concepts) | 6 |
| Leon Wichert, Sandipan Sikdar | [Rethinking Evaluation Methods for Machine Unlearning](https://doi.org/10.18653/v1/2024.findings-emnlp.271) | EMNLP | LLM | [GitHub](https://github.com/Kartoffelpuffa/Rethinking-MU-Evaluation) | 6 |
| Zhiwei Zuo et al. | [ECIL-MU: Embedding Based Class Incremental Learning and Machine Unlearning](https://doi.org/10.1109/icassp48485.2024.10446273) | ICASSP | Vision | — | 6 |
| Arinbjörn Kolbeinsson et al. | [Composable Interventions for Language Models](https://doi.org/10.48550/arXiv.2407.06483) | ICLR | LLM | [GitHub](https://github.com/hartvigsen-group/composable-interventions) | 6 |
| Yijing Lin et al. | [Decentralized Unlearning for Trustworthy AI-Generated Content (AIGC) Services](https://doi.org/10.1109/mnet.2024.3439411) | IEEE Network | Federated | — | 6 |
| Zhiwei Zuo et al. | [Machine Unlearning Through Fine-Grained Model Parameters Perturbation](https://doi.org/10.1109/TKDE.2025.3528551) | IEEE TKDE | Other | — | 6 |
| Zuobin Xiong, Wei Li, Zhipeng Cai | [Appro-Fun: Approximate Machine Unlearning in Federated Setting](https://doi.org/10.1109/ICCCN61486.2024.10637564) | International Conference on Computer Communications and Networks | Federated | — | 6 |
| Àlex Pujol Vidal et al. | [Verifying Machine Unlearning with Explainable AI](https://doi.org/10.48550/arXiv.2411.13332) | International Conference on Pattern Recognition | Vision | — | 6 |
| Andrea Schioppa, E. Hoogeboom, J. Heek | [Model Integrity when Unlearning with T2I Diffusion Models](https://doi.org/10.48550/arXiv.2411.02068) | arXiv | Diffusion | — | 6 |
| Vikram S Chundawat et al. | [ConDa: Fast Federated Unlearning with Contribution Dampening](https://doi.org/10.48550/arXiv.2410.04144) | arXiv | Federated | [GitHub](https://github.com/if-loops/if-loops) | 6 |
| Binhao Ma et al. | [Releasing Malevolence from Benevolence: The Menace of Benign Data on Machine Unlearning](https://doi.org/10.48550/arXiv.2407.05112) | arXiv | Other | — | 6 |
| David Zagardo | [A More Practical Approach to Machine Unlearning](https://doi.org/10.48550/arXiv.2406.09391) | arXiv | LLM | — | 6 |
| A. Sha, B. Nunes, Armin Haller | ["Forgetting" in Machine Learning and Beyond: A Survey](https://doi.org/10.48550/arXiv.2405.20620) | arXiv | Other | — | 6 |
| Subhodip Panda, Shashwat Sourav, Prathosh A.P. | [Partially Blinded Unlearning: Class Unlearning for Deep Networks a Bayesian Perspective](https://doi.org/10.48550/arXiv.2403.16246) | arXiv | Vision | — | 6 |
| Eleni Triantaﬁllou, P. Kairouz | [Evaluation for the NeurIPS Machine Unlearning Competition](https://www.semanticscholar.org/paper/f71ea29a845839efbcb735b3c89b71fbc1887a02) | arXiv | Other | [GitHub](https://github.com/tinee29/ETH-Deep-Learning) | 6 |
| Cheng-Long Wang et al. | [Has Approximate Machine Unlearning been evaluated properly? From Auditing to Side Effects](https://doi.org/10.48550/arXiv.2403.12830) | arXiv | Other | — | 6 |
| Alessio Mora et al. | [FedQUIT: On-Device Federated Unlearning via a Quasi-Competent Virtual Teacher](https://doi.org/10.48550/arXiv.2408.07587) | arXiv | Federated | [GitHub](https://github.com/alessiomora/FedQUIT) | 6 |
| Anh-Vu Bui et al. | [Hiding and Recovering Knowledge in Text-to-Image Diffusion Models via Learnable Prompts](https://arxiv.org/abs/2403.12326) | arXiv | Diffusion | [GitHub](https://github.com/tuananhbui89/Erasing-Adversarial-Preservation) | 6 |
| Kairan Zhao, Peter Triantafillou | [Scalability of memorization-based machine unlearning](https://doi.org/10.48550/arXiv.2410.16516) | arXiv | Other | [GitHub](https://github.com/kairanzhao/RUM) | 6 |
| Alessio Mora, Luca Dominici, Paolo Bellavista | [FedUNRAN: On-device Federated Unlearning via Random Labels](https://doi.org/10.1109/bigdata62323.2024.10825563) | BigData Congress [Services Society] | Federated | [GitHub](https://github.com/alessiomora/FedUNRAN) | 5 |
| Jie Ren et al. | [Six-CD: Benchmarking Concept Removals for Text-to-image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02679) | CVPR | Diffusion | [GitHub](https://github.com/deep-floyd/if) | 5 |
| Guofeng Li et al. | [Federated Unlearning in the Internet of Vehicles](https://doi.org/10.1109/DSN-S60304.2024.00034) | DSN-S | Federated | — | 5 |
| Chaoyi Wang, Zuobin Ying, Zijie Pan | [Machine unlearning in brain-inspired neural network paradigms](https://doi.org/10.3389/fnbot.2024.1361577) | Frontiers in Neurorobotics | Vision | — | 5 |
| Wei-gang Zhu et al. | [Federated Unlearning with Multiple Client Partitions](https://doi.org/10.1109/ICC51166.2024.10622238) | ICC | Federated | — | 5 |
| Javier Abad et al. | [Copyright-Protected Language Generation via Adaptive Model Fusion](https://doi.org/10.48550/arXiv.2412.06619) | ICLR | LLM | [GitHub](https://github.com/jaabmar/cp_fuse) | 5 |
| Hyoseo Kim, Dongyoon Han, Junsuk Choe | [NegMerge: Sign-Consensual Weight Merging for Machine Unlearning](https://arxiv.org/abs/2410.05583) | ICML | Vision | [GitHub](https://github.com/naver-ai/negmerge) | 5 |
| Lei Kang et al. | [Machine Unlearning for Document Classification](https://doi.org/10.48550/arXiv.2404.19031) | IEEE International Conference on Document Analysis and Recognition | Vision | [GitHub](https://github.com/leitro/MachineUnlearning-DocClassification) | 5 |
| Kongyang Chen et al. | [Private Data Protection With Machine Unlearning for Next-Generation Networks](https://doi.org/10.1109/ojcoms.2024.3518503) | IEEE Open Journal of the Communications Society | Other | — | 5 |
| Xiaoyu Zhang et al. | [DuplexGuard: Safeguarding Deletion Right in Machine Unlearning via Duplex Watermarking](https://doi.org/10.1109/tdsc.2024.3456811) | IEEE TDSC | Other | — | 5 |
| Samuele Poppi et al. | [Unlearning Vision Transformers Without Retaining Data via Low-Rank Decompositions](https://doi.org/10.1007/978-3-031-78122-3_10) | International Conference on Pattern Recognition | Vision | — | 5 |
| Yan Pang et al. | [Towards Understanding Unsafe Video Generation](https://doi.org/10.48550/arXiv.2407.12581) | NDSS | Diffusion | [GitHub](https://github.com/py85252876/uvd) | 5 |
| Igor Shilov, Matthieu Meeus, Yves-Alexandre de Montjoye | [The mosaic memory of large language models](https://doi.org/10.1038/s41467-026-68603-0) | Nature Communications | LLM | [GitHub](https://github.com/imperial-aisp/mosaic_memory) | 5 |
| Yuyao Zhong | [Federated unlearning for medical image analysis](https://doi.org/10.1117/12.3030004) | Other Conferences | Federated | — | 5 |
| Sebastian Schelter, Stefan Grafberger, Maarten de Rijke | [Snarcase - Regain Control over Your Predictions with Low-Latency Machine Unlearning](https://doi.org/10.14778/3685800.3685853) | VLDB Endowment | Recsys | — | 5 |
| Minseok Choi et al. | [Breaking Chains: Unraveling the Links in Multi-Hop Knowledge Unlearning](https://doi.org/10.48550/arXiv.2410.13274) | arXiv | LLM | — | 5 |
| Javier Abad et al. | [Strong Copyright Protection for Language Models via Adaptive Model Fusion](https://doi.org/10.48550/arXiv.2407.20105) | arXiv | LLM | [GitHub](https://github.com/pypa/virtualenv/issues) | 5 |
| Nhung Bui et al. | [On Newton's Method to Unlearn Neural Networks](https://doi.org/10.48550/arXiv.2406.14507) | arXiv | Other | [HF](https://huggingface.co/meta-llama/Llama-2-7b-hf) | 5 |
| N. Sepahvand et al. | [Data Selection for Transfer Unlearning](https://doi.org/10.48550/arXiv.2405.10425) | arXiv | Other | — | 5 |
| T. Surve, Romila Pradhan | [Example-based Explanations for Random Forests using Machine Unlearning](https://doi.org/10.48550/arXiv.2402.05007) | arXiv | Other | — | 5 |
| Rongzhe Wei et al. | [Underestimated Privacy Risks for Minority Populations in Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2412.08559) | arXiv | LLM | — | 5 |
| Jiangweizhi Peng et al. | [Safeguarding Text-to-Image Generation via Inference-Time Prompt-Noise Optimization](https://doi.org/10.48550/arXiv.2412.03876) | arXiv | Diffusion | — | 5 |
| Jinho Chang, Hyungjin Chung, Jong Chul Ye | [Contrastive CFG: Improving CFG in Diffusion Models by Contrasting Positive and Negative Concepts](https://doi.org/10.48550/arXiv.2411.17077) | arXiv | Diffusion | [GitHub](https://github.com/jinhojsk515/ContrastiveCFG) | 5 |
| Yi Li et al. | [Community-Centric Graph Unlearning](https://doi.org/10.48550/arXiv.2408.09705) | AAAI | Graph | [GitHub](https://github.com/liiiyi/CCGU) | 4 |
| Chenhao Zhang et al. | [Toward Efficient Data-Free Unlearning](https://doi.org/10.48550/arXiv.2412.13790) | AAAI | Vision | [GitHub](https://github.com/ChildEden/ISPF) | 4 |
| Zhenhong Zhou et al. | [Quantifying and Analyzing Entity-Level Memorization in Large Language Models](https://doi.org/10.1609/aaai.v38i17.29948) | AAAI | LLM | — | 4 |
| F. Mueller et al. | [LLMs and Memorization: On Quality and Specificity of Copyright Compliance](https://doi.org/10.1609/aies.v7i1.31697) | AAAI/ACM Conference on AI Ethics and Society | LLM | [GitHub](https://github.com/felixbmuller/llms-memorization-copyright) | 4 |
| Yongjing Hao et al. | [A General Strategy Graph Collaborative Filtering for Recommendation Unlearning](https://doi.org/10.1145/3627673.3679637) | CIKM | Recsys | [GitHub](https://github.com/YongjingHao/GSGCF-RU) | 4 |
| V. Perifanis et al. | [SFTC: Machine Unlearning via Selective Fine-tuning and Targeted Confusion](https://doi.org/10.1145/3655693.3655697) | European Interdisciplinary Cybersecurity Conference | Vision | [GitHub](https://github.com/vperifan/SFTC-Unlearn) | 4 |
| Yue Cui, Man Hon Cheung | [The Price of Forgetting: Data Redemption Mechanism Design for Machine Unlearning](https://doi.org/10.1109/ICC51166.2024.10622287) | ICC | Other | — | 4 |
| Stanley Wei et al. | [Provable unlearning in topic modeling and downstream tasks](https://doi.org/10.48550/arXiv.2411.12600) | ICLR | Other | — | 4 |
| Youngsik Yoon et al. | [Few-shot Unlearning](https://doi.org/10.1109/SP54263.2024.00249) | IEEE S&P | Other | [GitHub](https://github.com/ml-postech/Few-shot-Unlearning) | 4 |
| Wenhan Chang et al. | [Zero-shot Class Unlearning via Layer-wise Relevance Analysis and Neuronal Path Perturbation](https://doi.org/10.48550/arXiv.2410.23693) | IEEE TDSC | Vision | — | 4 |
| Amartya Hatua et al. | [Machine Unlearning using Forgetting Neural Networks](https://doi.org/10.48550/arXiv.2410.22374) | International Conference on Agents and Artificial Intelligence | Vision | — | 4 |
| Wenqin Li et al. | [Enhancing Privacy Protection for Online Learning Resource Recommendation with Machine Unlearning](https://doi.org/10.1109/cscwd61410.2024.10580315) | International Conference on Computer Supported Cooperative Work in Design | Recsys | — | 4 |
| Ruikai Yang et al. | [MUSO: achieving exact machine unlearning in over-parameterized regimes](https://doi.org/10.1007/s10994-025-06806-0) | Machine-mediated learning | Other | [GitHub](https://github.com/Yruikk/MUSO) | 4 |
| Kongyang Chen, Zixin Wang, Bing Mi | [Private Data Protection with Machine Unlearning in Contrastive Learning Networks](https://doi.org/10.3390/math12244001) | Mathematics | Vision | — | 4 |
| Zhongcheng Wei et al. | [CIU-L: A class-incremental learning and machine unlearning passive sensing system for human identification](https://doi.org/10.1016/j.pmcj.2024.101947) | Pervasive and Mobile Computing | Other | — | 4 |
| Tong Chen et al. | [CopyBench: Measuring Literal and Non-Literal Reproduction of Copyright-Protected Text in Language Model Generation](https://doi.org/10.18653/v1/2024.emnlp-main.844) | Red Teaming GenAI Workshop @ NeurIPS'24 Poster | LLM | [GitHub](https://github.com/chentong0/copy-bench) | 4 |
| Thomas De Min et al. | [Unlearning Personal Data from a Single Image](https://arxiv.org/abs/2407.12069) | TMLR | Vision | [GitHub](https://github.com/tdemin16/one-shui) | 4 |
| Aviraj Newatia, Michael Cooper, R. Krishnan | [Unlearning Tabular Data Without a “Forget Set”](https://www.semanticscholar.org/paper/9b4a5a920a7b784ab9fb295236feda970a1d9286) | TRL @ NeurIPS Poster | Other | — | 4 |
| Kerem Zaman, Leshem Choshen, Shashank Srivastava | [Fuse to Forget: Bias Reduction and Selective Memorization through Model Fusion](https://doi.org/10.18653/v1/2024.emnlp-main.1045) | arXiv | LLM | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 4 |
| Jose Miguel Lara Rangel et al. | [Learning to Forget using Hypernetworks](https://doi.org/10.48550/arXiv.2412.00761) | arXiv | Other | [GitHub](https://github.com/if-loops/if-loops) | 4 |
| Eric Zhang, Leshem Choshen, Jacob Andreas | [Unforgettable Generalization in Language Models](https://doi.org/10.48550/arXiv.2409.02228) | arXiv | LLM | — | 4 |
| Shiqi Liu, Yihua Tan | [Unlearning Concepts from Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2407.14209) | arXiv | Diffusion | — | 4 |
| Ziheng Chen et al. | [Debiasing Machine Unlearning with Counterfactual Examples](https://doi.org/10.48550/arXiv.2404.15760) | arXiv | Other | — | 4 |
| Changchang Sun et al. | [Forget Vectors at Play: Universal Input Perturbations Driving Machine Unlearning in Image Classification](https://doi.org/10.48550/arXiv.2412.16780) | arXiv | Vision | [GitHub](https://github.com/Changchangsun/Forget-Vector) | 4 |
| Teodora Baluta et al. | [Unlearning in- vs. out-of-distribution data in LLMs under gradient-based method](https://doi.org/10.48550/arXiv.2411.04388) | arXiv | LLM | — | 4 |
| Kuanrong Liu et al. | [Efficient Backdoor Defense in Multimodal Contrastive Learning: A Token-Level Unlearning Method for Mitigating Threats](https://doi.org/10.48550/arXiv.2409.19526) | arXiv | Vision | — | 4 |
| A. Veldanda et al. | [LLM Surgery: Efficient Knowledge Unlearning and Editing in Large Language Models](https://doi.org/10.48550/arXiv.2409.13054) | arXiv | LLM | [GitHub](https://github.com/akshajkumarv/llm_surgery_code) | 4 |
| Dong Han, Salaheldin Mohamed, Yong Li | [ShieldDiff: Suppressing Sexual Content Generation from Diffusion Models through Reinforcement Learning](https://doi.org/10.48550/arXiv.2410.05309) | arXiv | Diffusion | [GitHub](https://github.com/Yuchen413/text2image) | 4 |
| Zheling Meng et al. | [Dark Miner: Defend against undesired generation for text-to-image diffusion models](https://doi.org/10.48550/arXiv.2409.17682) | arXiv | Diffusion | — | 4 |
| Xiao Liu et al. | [Decentralized Federated Unlearning on Blockchain](https://doi.org/10.48550/arXiv.2402.16294) | arXiv | Federated | — | 4 |
| Romit Chatterjee et al. | [A Unified Framework for Continual Learning and Unlearning](https://arxiv.org/abs/2408.11374) | arXiv | Other | [GitHub](https://github.com/respailab/CLMUL) | 4 |
| Xiaoze Liu et al. | [SHIELD: Evaluation and Defense Strategies for Copyright Compliance in LLM Text Generation](https://doi.org/10.18653/v1/2024.emnlp-main.98) | arXiv | LLM | — | 4 |
| Lefeng Zhang et al. | [The Price of Unlearning: Identifying Unlearning Risk in Edge Computing](https://doi.org/10.1145/3662184) | ACM Trans. Multim. Comput. Commun. Appl | Other | — | 3 |
| Zirui Ling, Chaoyu Zhang, Zijie Pan | [Multi-step and Iterative Backdoor Injection in Federated Machine Unlearning](https://doi.org/10.1109/CSRSWTC64338.2024.10811514) | CSRSWTC | Federated | — | 3 |
| Jingwen Ye et al. | [Distilled Datamodel with Reverse Gradient Matching](https://doi.org/10.1109/CVPR52733.2024.01136) | CVPR | Vision | [GitHub](https://github.com/islam15-8789/Distilled_Datamodel_with_Reverse_Gradient_Matching_Reproduction) | 3 |
| Kealan Dunnett et al. | [Unlearning Backdoor Attacks Through Gradient-Based Model Pruning](https://doi.org/10.1109/dsn-w60302.2024.00021) | DSN-W | Vision | [GitHub](https://github.com/WhoDunnett/Grad-Prune/tree) | 3 |
| Guitao Chen et al. | [WPN: An Unlearning Method Based on N-pair Contrastive Learning in Language Models](https://doi.org/10.48550/arXiv.2408.09459) | European Conference on Artificial Intelligence | LLM | [GitHub](https://github.com/baojunshan/nlp-fluency) | 3 |
| Yixiong Wang et al. | [Learning to Unlearn in Federated Learning](https://doi.org/10.1109/FLTA63145.2024.10840121) | FLTA | Federated | — | 3 |
| Qi Guo et al. | [Forgetting Through Transforming: Enabling Federated Unlearning via Class-Aware Representation Transformation](https://doi.org/10.1109/ICCV51701.2025.00145) | ICCV | Federated | [GitHub](https://github.com/Mahanth-Maha/Unlearn) | 3 |
| Wanzhu Jiang et al. | [Moderating the Generalization of Score-Based Generative Model](https://doi.org/10.1109/ICCV51701.2025.00041) | ICCV | Diffusion | [GitHub](https://github.com/yunfengdiao/Moderated-Score-based-Generative-Model) | 3 |
| Hanlin Gu et al. | [Towards Privacy-Guaranteed Label Unlearning in Vertical Federated Learning: Few-Shot Forgetting without Disclosure](https://arxiv.org/abs/2410.10922) | ICLR Poster | Federated | [GitHub](https://github.com/bryanhx/Towards-Privacy-Guaranteed-Label-Unlearning-in-Vertical-Federated-Learning) | 3 |
| Varshita Kolipaka et al. | [A Cognac Shot To Forget Bad Memories: Corrective Unlearning for Graph Neural Networks](https://arxiv.org/abs/2412.00789) | ICML | Graph | [GitHub](https://github.com/cognac-gnn-unlearning/corrective-unlearning-for-gnns) | 3 |
| Emircan Gündogdu, Altay Unal, Gozde Unal | [A Study Regarding Machine Unlearning on Facial Attribute Data](https://doi.org/10.1109/FG59268.2024.10581972) | IEEE International Conference on Automatic Face & Gesture Recognition | Vision | [GitHub](https://github.com/ituvisionlab/face-attribute-unlearning) | 3 |
| Yi Tang et al. | [Unlearning from Weakly Supervised Learning](https://doi.org/10.24963/ijcai.2024/553) | IJCAI | Vision | — | 3 |
| Pengfei Ding et al. | [Adaptive Graph Unlearning](https://doi.org/10.24963/ijcai.2024/308) | IJCAI | Graph | [GitHub](https://github.com/Aliezzz/AGU) | 3 |
| Yuyang Xue et al. | [Erase to Enhance: Data-Efficient Machine Unlearning in MRI Reconstruction](https://doi.org/10.48550/arXiv.2405.15517) | International Conference on Medical Imaging with Deep Learning | Vision | [GitHub](https://github.com/yuyangxueed/reconunlearning) | 3 |
| Chen Gong et al. | [TrajDeleter: Enabling Trajectory Forgetting in Offline Reinforcement Learning Agents](https://doi.org/10.48550/arXiv.2404.12530) | NDSS | Other | [GitHub](https://github.com/2019ChenGong/TrajDeleter) | 3 |
| Li Cui, Pengfei Wang, Yuqi Han | [Edge Caching with Federated Unlearning in Cluster-Centric Small Cell Networks](https://doi.org/10.1109/ngdn61651.2024.10744106) | NGDN | Federated | — | 3 |
| Yusuke Kuwana et al. | [Black-Box Forgetting](https://doi.org/10.48550/arXiv.2411.00409) | NeurIPS | Vision | [GitHub](https://github.com/yusukekwn/Black-Box-Forgetting) | 3 |
| Jiayi Wu et al. | [Cross-model Control: Improving Multiple Large Language Models in One-time Training](https://doi.org/10.48550/arXiv.2410.17599) | NeurIPS | LLM | [GitHub](https://github.com/wujwyi/cmc) | 3 |
| Peiran Dong et al. | [Towards Safe Concept Transfer of Multi-Modal Diffusion via Causal Representation Editing](https://doi.org/10.52202/079017-0404) | NeurIPS | Diffusion | — | 3 |
| Yiwen Tu, Pingbang Hu, Jiaqi W. Ma | [A Reliable Cryptographic Framework for Empirical Machine Unlearning Evaluation](https://arxiv.org/abs/2404.11577) | NeurIPS poster | Other | — | 3 |
| P. Guo et al. | [Robust Knowledge Unlearning via Mechanistic Localizations](https://www.semanticscholar.org/paper/359d4db8585317f0f1eafc873220e2b9d0c62c34) | NextGenAISafety Poster | LLM | — | 3 |
| Meng Ding et al. | [Understanding Fine-tuning in Approximate Unlearning: A Theoretical Perspective](https://arxiv.org/abs/2410.03833) | TMLR | Other | — | 3 |
| Tao Wu et al. | [GraphMU: Repairing Robustness of Graph Neural Networks via Machine Unlearning](https://doi.org/10.48550/arXiv.2406.13499) | arXiv | Graph | — | 3 |
| Wei Qian et al. | [Exploring Fairness in Educational Data Mining in the Context of the Right to be Forgotten](https://doi.org/10.48550/arXiv.2405.16798) | arXiv | Other | — | 3 |
| Ling Han et al. | [Unlearning Information Bottleneck: Machine Unlearning of Systematic Patterns and Biases](https://doi.org/10.48550/arXiv.2405.14020) | arXiv | Other | [GitHub](https://github.com/brianhan-coder/research) | 3 |
| Xinbao Qiao et al. | [Efficient Online Unlearning via Hessian-Free Recollection of Individual Data Statistics](https://doi.org/10.48550/arXiv.2404.01712) | arXiv | Other | — | 3 |
| Tingxu Han et al. | [Continuous Concepts Removal in Text-to-image Diffusion Models](https://doi.org/10.48550/arXiv.2412.00580) | arXiv | Diffusion | [GitHub](https://github.com/wssun/CCRT) | 3 |
| Varshita Kolipaka et al. | [A Cognac shot to forget bad memories: Corrective Unlearning in GNNs](https://doi.org/10.48550/arXiv.2412.00789) | arXiv | Graph | [GitHub](https://github.com/viciousAegis/CorrectiveUnlearningForGNNs) | 3 |
| Trishna Chakraborty et al. | [Can Textual Unlearning Solve Cross-Modality Safety Alignment?](https://doi.org/10.18653/v1/2024.findings-emnlp.574) | EMNLP | LLM | — | 2 |
| Shurong Wang et al. | [DynFrs: An Efficient Framework for Machine Unlearning in Random Forest](https://doi.org/10.48550/arXiv.2410.01588) | ICLR | Other | [GitHub](https://github.com/shurongwang/DynFrs) | 2 |
| Xiao Liu et al. | [Parallel Unlearning in Inherited Model Networks](https://doi.org/10.1109/TIFS.2025.3627869) | IEEE T-IFS | Other | [GitHub](https://github.com/MJLee00/Parallel-Unlearning-in-Inherited-Model-Networks) | 2 |
| Sangyoon Lee, Dae-Hyun Choi | [Learning and Unlearning to Operate Profitable Secure Electric Vehicle Charging](https://doi.org/10.1109/TII.2024.3396524) | IEEE T-II | Other | — | 2 |
| Heng Xu et al. | [Toward Efficient Target-Level Machine Unlearning Based on Essential Graph](https://doi.org/10.1109/tnnls.2024.3514607) | IEEE TNNLS | Vision | — | 2 |
| Jingrui Hou, Axel Finke, Georgina Cosma | [Neural Machine Unranking](https://doi.org/10.48550/arXiv.2408.05330) | IEEE TNNLS | LLM | — | 2 |
| A. Seetha et al. | [DiEvD-SF: Disruptive Event Detection Using Continual Machine Learning With Selective Forgetting](https://doi.org/10.1109/TCSS.2024.3364544) | IEEE Transactions on Computational Social Systems | Other | — | 2 |
| Andrea D'Angelo et al. | [How to Make Reproducible Research in Machine Unlearning with ERASURE](https://doi.org/10.24963/ijcai.2024/1255) | IJCAI | Other | [GitHub](https://github.com/aiim-research/ERASURE) | 2 |
| Wenhan Wu et al. | [Zero-shot Federated Unlearning via Transforming from Data-Dependent to Personalized Model-Centric](https://doi.org/10.24963/ijcai.2024/733) | IJCAI | Federated | — | 2 |
| Lang Li et al. | [Pseudo unlearning via sample swapping with hash](https://doi.org/10.1016/j.ins.2024.120135) | Information Sciences | Other | — | 2 |
| Liou Tang, James Joshi | [Towards Privacy-Preserving and Secure Machine Unlearning: Taxonomy, Challenges and Research Directions](https://doi.org/10.1109/TPS-ISA62245.2024.00040) | International Conference on Trust, Privacy and Security in Intelligent Systems and Applications | Other | — | 2 |
| Shanshan Chen et al. | [A Continuous Verification Mechanism for Clients in Federated Unlearning to Defend the Right to be Forgotten](https://doi.org/10.1109/ispa63168.2024.00115) | International Symposium on Image and Signal Processing and Analysis | Federated | [GitHub](https://github.com/paper-liu/BAFV-master) | 2 |
| C. Murti, Chiranjib Bhattacharyya | [DisCEdit: Model Editing by Identifying Discriminative Components](https://doi.org/10.52202/079017-1498) | NeurIPS | Vision | [GitHub](https://github.com/chaimurti/DisCEdit) | 2 |
| Zhuo Ma et al. | [Mitigate noisy data for smart IoT via GAN based machine unlearning](https://doi.org/10.1007/s11432-022-3671-9) | Science China Information Sciences | Other | — | 2 |
| Keivan Rezaei et al. | [RESTOR: Knowledge Recovery in Machine Unlearning](https://arxiv.org/abs/2411.00204) | TMLR | LLM | [GitHub](https://github.com/k1rezaei/restor) | 2 |
| Shivank Garg, Manyana Tiwari | [Unmasking the Veil: An Investigation into Concept Ablation for Privacy and Copyright Protection in Images](https://doi.org/10.48550/arXiv.2406.12592) | TMLR | Diffusion | [GitHub](https://github.com/taited/clip-score) | 2 |
| Yinghua Hua, Hui Xia, Shuo Xu | [Federated Unlearning for Samples Based on Adaptive Gradient Ascent of Angles](https://doi.org/10.1109/TrustCom63139.2024.00125) | TrustCom | Federated | — | 2 |
| A. Cooper et al. | [Machine Unlearning Doesn't Do What You Think: Lessons for Generative AI Policy and Research](https://arxiv.org/abs/2412.06966) | arXiv | Other | — | 2 |
| Chenghao Li et al. | [LoyalDiffusion: A Diffusion Model Guarding Against Data Replication](https://doi.org/10.48550/arXiv.2412.01118) | arXiv | Diffusion | — | 2 |
| Yuncong Yang et al. | [From Machine Learning to Machine Unlearning: Complying with GDPR's Right to be Forgotten while Maintaining Business Value of Predictive Models](https://doi.org/10.48550/arXiv.2411.17126) | arXiv | Other | — | 2 |
| Heng Xu, Tianqing Zhu, Wanlei Zhou | [Evaluating of Machine Unlearning: Robustness Verification Without Prior Modifications](https://doi.org/10.48550/arXiv.2410.10120) | arXiv | Other | — | 2 |
| Zhangjie Xia, ChiHua Wang, Guang Cheng | [Data Deletion for Linear Regression with Noisy SGD](https://doi.org/10.48550/arXiv.2410.09311) | arXiv | Other | — | 2 |
| Evan Rose et al. | [UTrace: Poisoning Forensics for Private Collaborative Learning](https://doi.org/10.48550/arXiv.2409.15126) | arXiv | Other | — | 2 |
| Xinchi Qiu et al. | [How Data Inter-connectivity Shapes LLMs Unlearning: A Structural Unlearning Perspective](https://arxiv.org/abs/2406.16810) | arXiv | LLM | [HF](https://huggingface.co/datasets/xinchiqiu/PISTOL) | 2 |
| Heng Xu et al. | [Towards Efficient Target-Level Machine Unlearning Based on Essential Graph](https://doi.org/10.48550/arXiv.2406.10954) | arXiv | Vision | [GitHub](https://github.com/IMoonKeyBoy/Towards-Efficient-Target-Level-Machine-Unlearning-Based-on-Essential-Graph) | 2 |
| Jie Xu et al. | [LMEraser: Large Model Unlearning through Adaptive Prompt Tuning](https://doi.org/10.48550/arXiv.2404.11056) | arXiv | LLM | [GitHub](https://github.com/lmeraser/lmeraser) | 2 |
| Rohan Sharma et al. | [Discriminative Adversarial Unlearning](https://doi.org/10.48550/arXiv.2402.06864) | arXiv | Vision | — | 2 |
| Yuxuan Wu, Bonaventure F. P. Dossou, Dianbo Liu | [CodeUnlearn: Amortized Zero-Shot Machine Unlearning in Language Models Using Discrete Concept](https://doi.org/10.48550/arXiv.2410.10866) | arXiv | LLM | — | 2 |
| Lu Yi, Zhewei Wei | [Scalable and Certifiable Graph Unlearning via Lazy Local Propagation](https://doi.org/10.48550/arXiv.2408.09212) | arXiv | Graph | — | 2 |
| Zihao Zhao et al. | [Pseudo-Probability Unlearning: Towards Efficient and Privacy-Preserving Machine Unlearning](https://doi.org/10.48550/arXiv.2411.02622) | arXiv | Other | — | 2 |
| Matthew Wicker et al. | [Certificates of Differential Privacy and Unlearning for Gradient-Based Training](https://doi.org/10.48550/arXiv.2406.13433) | arXiv | Other | [GitHub](https://github.com/Mihneaghitu/ModelGuidanceViaRobustFeatureAttribution) | 2 |
| Xiao Liu et al. | [Fishers Harvest Parallel Unlearning in Inherited Model Networks](https://doi.org/10.48550/arXiv.2408.08493) | arXiv | Other | — | 2 |
| Bingchen Liu, Yuanyuan Fang | [Federated Knowledge Graph Unlearning via Diffusion Model](https://doi.org/10.48550/arXiv.2403.08554) | arXiv | Federated | — | 2 |
| Xiaoyu Wu, Jiaru Zhang, Steven Wu | [Revealing the Unseen: Guiding Personalized Diffusion Models to Expose Training Data](https://doi.org/10.48550/arXiv.2410.03039) | arXiv | Diffusion | — | 2 |
| Kahou Tam et al. | [Towards Federated Domain Unlearning: Verification Methodologies and Challenges](https://doi.org/10.48550/arXiv.2406.03078) | arXiv | Federated | — | 2 |
| Mingchen Li et al. | [Unlearning Virus Knowledge Toward Safe and Responsible Mutation Effect Predictions](https://doi.org/10.1101/2024.10.02.616274) | bioRxiv | LLM | — | 2 |
| Peng Deng et al. | [Cooperation Among Multiple Medical Institutions on Retinal Disease Identification Based on Federated Learning and Unlearning](https://doi.org/10.1109/ACCTCS61748.2024.00100) | ACCTCS | Federated | — | 1 |
| Jiadong Pan et al. | [SafeCFG: Controlling Harmful Features with Dynamic Safe Guidance for Safe Generation](https://doi.org/10.1145/3746027.3754717) | ACM MM | Diffusion | [GitHub](https://github.com/matrix0721/SafeCFG) | 1 |
| Amartya Hatua, Trung T. Nguyen, Andrew H. Sung | [Machine Unlearning using a Multi-GAN based Model](https://doi.org/10.48550/arXiv.2407.18467) | AIP Conference Proceedings | Vision | — | 1 |
| Kai Cui, Yong Liao | [A Highly Efficient and Lightweight Graph Unlearning Method with Balanced Graph Partitioning and Adaptive Aggregation](https://doi.org/10.1109/CISCE62493.2024.10653362) | CISCE | Graph | — | 1 |
| Abraham Chan et al. | [Hierarchical Unlearning Framework for Multi-Class Classiﬁcation](https://www.semanticscholar.org/paper/1b1518a62d3834feb77648d2f0435035a0507f8f) | FITML Poster | Vision | — | 1 |
| Eray Guven, Günes Karabulut-Kurt | [Machine Unlearning for Uplink Interference Cancellation](https://doi.org/10.1109/GLOBECOM52923.2024.10901616) | Global Communications Conference | Other | [GitHub](https://github.com/riguwen/MULforIC) | 1 |
| Zhihao Zhu, Yi Yang, Defu Lian | [TDDBench: A Benchmark for Training data detection](https://doi.org/10.48550/arXiv.2411.03363) | ICLR | Other | [GitHub](https://github.com/zzh9568/TDDBench) | 1 |
| Aditi Seetha et al. | [<i>DiEvD-SF</i>: Disruptive Event Detection Using Continual Machine Learning With Selective Forgetting](https://doi.org/10.1109/tcss.2024.3364544) | IEEE Transactions on Computational Social Systems | Other | — | 1 |
| Jingrui Hou, Axel Finke, Georgina Cosma | [Neural Corrective Machine Unranking](https://doi.org/10.48550/arXiv.2411.08562) | Information Sciences | Other | [GitHub](https://github.com/JingruiHou/CorrectiveUnranking) | 1 |
| Yong Zhang et al. | [A Novel Model-Knowledge Transfer Approach for Effective Machine Unlearning and Performance Preservation](https://doi.org/10.1145/3714334.3714371) | International Conference on Artificial Intelligence, Systems and Network Security | Other | — | 1 |
| Indira Gandhi Delhi, S. Reddy, Rishika Anand | [Comparison of Model Adaptation Techniques with Machine Unlearning](https://doi.org/10.1109/ICCCNT61001.2024.10723921) | International Conference on Computing Communication and Networking Technologies | Other | — | 1 |
| Muhammad Ameen, Pengfei Wang | [Lightweight Federated Unlearning for IoT Sensing Systems](https://doi.org/10.1109/MSN63567.2024.00028) | International Conference on Mobile Ad-hoc and Sensor Networks | Federated | — | 1 |
| Taro Togo et al. | [Analysis of Continual Learning Techniques for Image Generative Models with Learned Class Information Management](https://doi.org/10.3390/s24103087) | Italian National Conference on Sensors | Diffusion | — | 1 |
| V. C. Gogineni, E. Nadimi | [Efficient Knowledge Deletion from Trained Models through Layer-wise Partial Machine Unlearning](https://doi.org/10.48550/arXiv.2403.07611) | JMLR | Other | — | 1 |
| G. Brahmani et al. | [Emerging Challenges and Future Directions in Federated Unlearning](https://doi.org/10.48001/jocsvl.2024.127-14) | Journal of Computer Systems, Virtualization and Languages | Federated | — | 1 |
| Abhinav Bhatelé et al. | [Be like a Goldfish, Don't Memorize! Mitigating Memorization in Generative LLMs](https://doi.org/10.52202/079017-0757) | NeurIPS | LLM | — | 1 |
| Lei Zhou et al. | [Streamlined Federated Unlearning: Unite as One to Be Highly Efficient](https://doi.org/10.48550/arXiv.2412.00126) | arXiv | Federated | — | 1 |
| Hammad Rizwan et al. | [Instance-Level Difficulty: A Missing Perspective in Machine Unlearning](https://arxiv.org/abs/2410.03043) | arXiv | Other | — | 1 |
| Xin Su, Zhuoran Zheng | [Accurate Forgetting for All-in-One Image Restoration Model](https://doi.org/10.48550/arXiv.2409.00685) | arXiv | Vision | [GitHub](https://github.com/Harbinzzy/All-in-One-Image-Restoration-Survey) | 1 |
| Ahan Chatterjee et al. | [Remembering Everything Makes You Vulnerable: A Limelight on Machine Unlearning for Personalized Healthcare Sector](https://doi.org/10.48550/arXiv.2407.04589) | arXiv | Other | — | 1 |
| Nexhi Sula et al. | [Silver Linings in the Shadows: Harnessing Membership Inference for Machine Unlearning](https://doi.org/10.48550/arXiv.2407.00866) | arXiv | Other | — | 1 |
| Zhixin Pan et al. | [Privacy-Preserving Debiasing using Data Augmentation and Machine Unlearning](https://doi.org/10.48550/arXiv.2404.13194) | arXiv | Other | — | 1 |
| Ikhyun Cho, Changyeon Park, J. Hockenmaier | [ViT-MUL: A Baseline Study on Recent Machine Unlearning Methods Applied to Vision Transformers](https://doi.org/10.48550/arXiv.2403.09681) | arXiv | Vision | [GitHub](https://github.com/ihcho2/ViTMUL) | 1 |
| J. Khan | [Dataset Condensation Driven Machine Unlearning](https://doi.org/10.48550/arXiv.2402.00195) | arXiv | Other | [GitHub](https://github.com/algebraicdianuj/DC_U) | 1 |
| Carl E.J. Brodzinski | [Survey of Security and Data Attacks on Machine Unlearning In Financial and E-Commerce](https://doi.org/10.48550/arXiv.2410.00055) | arXiv | Other | — | 1 |
| R. Smirnov | [Classifier-free guidance in LLMs Safety](https://doi.org/10.48550/arXiv.2412.06846) | arXiv | LLM | — | 1 |
| Xinrui Yu et al. | [Federated Unlearning Model Recovery in Data with Skewed Label Distributions](https://doi.org/10.48550/arXiv.2412.13466) | arXiv | Federated | — | 1 |
| Felix Hsieh et al. | [Mitigating Backdoor Attacks using Activation-Guided Model Editing](https://doi.org/10.48550/arXiv.2407.07662) | ACCV Workshops | Vision | — | 0 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Training-free Class For-getting](https://www.semanticscholar.org/paper/0499ce47dee94383309fe2e5ddb4197dbc1bbefd) | Accepted by TMLR | Vision | — | 0 |
| Laman Aliyeva et al. | [Deep Unlearning of Breast Cancer Histopathological Images for Enhanced Responsibility in Classification](https://doi.org/10.1109/AICT61888.2024.10740413) | Advanced Industrial Conference on Telecommunications | Vision | — | 0 |
| Huanyi Ye et al. | [Malicious Unlearning in Ensemble Models](https://doi.org/10.1109/PST62714.2024.10788066) | Conference on Privacy, Security and Trust | Other | — | 0 |
| Sofiane Azogagh et al. | [Oblivious Exact (Un)Learning of Extremely Randomized Trees](https://www.semanticscholar.org/paper/471f49452591e17a356dc32bc865fb3c2275f6df) | EDCC | Other | — | 0 |
| Zheling Meng et al. | [Dark Miner: Defend against undesirable generation for text-to-image diffusion models](https://arxiv.org/abs/2409.17682) | ICLR Conference Withdrawn Submission | Diffusion | [GitHub](https://github.com/ultralytics/ultralytics) | 0 |
| Zihao Zhao et al. | [AdaProb: Efficient Machine Unlearning via Adaptive Probability](https://arxiv.org/abs/2411.02622) | ICLR Workshop DATA-FM | Vision | [GitHub](https://github.com/zzhao71/AdaProb) | 0 |
| R. Karn, J. Knechtel, Ozgur Sinanoglu | [Selective Forgetting in Task-Progressive Learning Through Machine Unlearning](https://doi.org/10.1109/ICMLC63072.2024.10935063) | ICML | Other | — | 0 |
| Ching-Chun Chang et al. | [Hypnopaedia-Aware Machine Unlearning via Psychometrics of Artificial Mental Imagery](https://doi.org/10.1109/ACCESS.2025.3576800) | IEEE Access | Vision | — | 0 |
| Jianfang Wang, Menghao Liang, G. Chai | [Recommendation Unlearning with Dynamic Sampling and Interest Boundary Perception](https://doi.org/10.1109/HPCC64274.2024.00183) | IEEE International Conference on High Performance Computing and Communications | Recsys | — | 0 |
| Wen-Hung Liao, Yang-Jing Lin | [Investigation of Feature Distribution and Network Weight Updates in the Machine Unlearning Process](https://doi.org/10.1109/ISM63611.2024.00022) | IEEE International Symposium on Multimedia | Vision | — | 0 |
| Hengzhu Liu et al. | [Game-Theoretic Machine Unlearning: Mitigating Extra Privacy Leakage](https://doi.org/10.1109/TIFS.2025.3623364) | IEEE T-IFS | Other | — | 0 |
| Luka Borec, Philipp Sadler, David Schlangen | [The Unreasonable Ineffectiveness of Nucleus Sampling on Mitigating Text Memorization](https://doi.org/10.18653/v1/2024.inlg-main.30) | INLG | LLM | — | 0 |
| Wenxiao Zhang | [A Comprehensive Investigation of Federated Unlearning: Challenges, Methods and Future Prospects in Privacy-Sensitive Applications](https://doi.org/10.5220/0013528500004619) | International Conference on Data Analysis and Machine Learning | Federated | — | 0 |
| Y. Qu et al. | [Continuous Verification of Catastrophic Recalling in Machine Unlearning via Adversarial Testing](https://doi.org/10.1109/DSC63484.2024.00056) | International Conference on Data Science in Cyberspace | Other | — | 0 |
| I. Pratama, Windy Gambetta | [Implementation of Exact Machine Unlearning Algorithm in Credit Scoring Cases](https://doi.org/10.1109/ICoDSE63307.2024.10829911) | International Conference on Data and Software Engineering | Other | — | 0 |
| Jeremy Syaloom Okey Nathanael Simbolon, Windy Gambetta | [On Performance Comparison between Strong Machine Unlearning Algorithms for Logistic Regression Credit Assessment Models](https://doi.org/10.1109/ICoDSE63307.2024.10829916) | International Conference on Data and Software Engineering | Other | — | 0 |
| Lingyue Ge | [Erasing memories: implementing client unlearning in medical image analysis](https://doi.org/10.1117/12.3035404) | International Conference on Image Processing and Artificial Intelligence | Federated | — | 0 |
| U. G et al. | [Securing Personal Identity in Facial Recognition: The Shift to Machine Unlearning](https://doi.org/10.1109/ICSES63445.2024.10763384) | International Conference on Signals and Electronic Systems | Vision | — | 0 |
| Florian Stadtmann, Adil Rasheed | [Federated Learning and Unlearning as Enablers of Wind Turbine Digital Twins](https://doi.org/10.1088/1742-6596/2767/5/052031) | Journal of Physics: Conference Series | Federated | — | 0 |
| Xiwen Wei, Guihong Li, R. Marculescu | [Fairness Implications of Machine Unlearning: Bias Risks in Removing NSFW Content from Text-to-Image Models](https://www.semanticscholar.org/paper/5ad0199e38cd61df8c81b55d46366006dcb3e40c) | RegML | Diffusion | — | 0 |
| Xinghui Yue et al. | [Research on Machine Unlearning Verification Based on Predictive Cross-Entropy](https://doi.org/10.1109/SWC62898.2024.00139) | SWC | Other | — | 0 |
| K. Salas-Jimenez et al. | [GIL-IIMAS UNAM at SemEval-2025 Task 4: LA-Min(E): LLM Unlearning Approaches Under Function Minimizing Evaluation Constraints](https://www.semanticscholar.org/paper/86222121bff9302a2f7d0ef7a3b17acd792b258f) | SemEval | LLM | — | 0 |
| Claudio Savelli et al. | [MALTO at SemEval-2025 Task 4: Dual Teachers for Unlearning Sensitive Content in LLMs](https://www.semanticscholar.org/paper/463cef51494fbc82ea38b9594c53d18778b043c6) | SemEval@NAACL | LLM | — | 0 |
| Yihan Wang et al. | [MUC: Machine Unlearning for Contrastive Learning with Black-box Evaluation](https://arxiv.org/abs/2406.03603) | TMLR | Vision | [GitHub](https://github.com/EhanW/Alignment-Calibration) | 0 |
| M. Suliman et al. | [Towards a Re-evaluation of Data Forging Attacks in Practice](https://doi.org/10.48550/arXiv.2411.05658) | USENIX Security | Other | — | 0 |
| Chenhan Zhang et al. | [Targeted Therapy in Data Removal: Object Unlearning Based on Scene Graphs](https://doi.org/10.48550/arXiv.2412.00067) | arXiv | Vision | [GitHub](https://github.com/democode-CC/Object-Unlearning-Based-on-Scene-Graphs) | 0 |
| Junjie Chen et al. | [Machine Unlearning in Forgettability Sequence](https://doi.org/10.48550/arXiv.2410.06446) | arXiv | Other | — | 0 |
| Zixin Wang, Kongyang Chen | [Machine Unlearning in Contrastive Learning](https://doi.org/10.48550/arXiv.2405.07317) | arXiv | Other | — | 0 |
| Tao Huang et al. | [Machine Unlearning with Minimal Gradient Dependence for High Unlearning Ratios](https://doi.org/10.48550/arXiv.2406.16986) | arXiv | Other | — | 0 |
| Haoxuan Ji et al. | [Towards Aligned Data Removal via Twin Machine Unlearning](https://doi.org/10.48550/arXiv.2408.11433) | arXiv | Vision | — | 0 |
| Adam Shostack | [: R EMOVING H ARRY P OTTER FROM AN LLM IS HARDER THAN REPORTED](https://www.semanticscholar.org/paper/f1723094e3db36bac5125fbe8b86d31e32bba3dd) | arXiv | LLM | — | 0 |
| Shivank Garg, Manyana Tiwari | [Attention Shift: Steering AI Away from Unsafe Content](https://doi.org/10.48550/arXiv.2410.04447) | arXiv | Diffusion | [GitHub](https://github.com/harrywang/finetune-sd) | 0 |
| He Zhang et al. | [Gradient Transformation: Towards Efficient and Model-Agnostic Unlearning for Dynamic Graph Neural Networks](https://doi.org/10.48550/arXiv.2405.14407) | arXiv | Graph | — | 0 |
| Zheng Dai, David K Gifford | [Ablation Based Counterfactuals](https://doi.org/10.48550/arXiv.2406.07908) | arXiv | Diffusion | [GitHub](https://github.com/JBlitzar/constructive-counterfactuals) | 0 |
| Ruixuan Liu et al. | [ExpShield: Safeguarding Web Text from Unauthorized Crawling and LLM Exploitation](https://doi.org/10.48550/arXiv.2412.21123) | arXiv | LLM | [GitHub](https://github.com/Emory-AIMS/ExpShield-demo) | 0 |
| Huaxi Huang et al. | [Enhancing User-Centric Privacy Protection: An Interactive Framework through Diffusion Models and Machine Unlearning](https://doi.org/10.48550/arXiv.2409.03326) | arXiv | Diffusion | — | 0 |

## 2023

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Nicholas Carlini et al. | [Extracting Training Data from Diffusion Models](https://doi.org/10.48550/arXiv.2301.13188) | USENIX Security | Diffusion | [HF](https://huggingface.co/datasets/malena-fj/MSc-Thesis-professionset) | 910 |
| Milad Nasr et al. | [Scalable Extraction of Training Data from (Production) Language Models](https://doi.org/10.48550/arXiv.2311.17035) | arXiv | LLM | [GitHub](https://github.com/ZJU-LLMs/Foundations-of-LLMs) | 539 |
| Rohit Gandikota et al. | [Erasing Concepts from Diffusion Models](https://doi.org/10.1109/ICCV51070.2023.00230) | ICCV | Diffusion | [GitHub](https://github.com/rohitgandikota/erasing) | 536 |
| Patrick Schramowski et al. | [Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://doi.org/10.1109/cvpr52729.2023.02157) | CVPR | Diffusion | [GitHub](https://github.com/ml-research/safe-latent-diffusion) | 529 |
| Weijia Shi et al. | [Detecting Pretraining Data from Large Language Models](https://doi.org/10.48550/arXiv.2310.16789) | ICLR | LLM | [GitHub](https://github.com/swj0419/detect-pretrain-code) | 366 |
| Rohit Gandikota et al. | [Unified Concept Editing in Diffusion Models](https://doi.org/10.1109/WACV57701.2024.00503) | WACV | Diffusion | [GitHub](https://github.com/rohitgandikota/unified-concept-editing) | 366 |
| Ronen Eldan, M. Russinovich | [Who's Harry Potter? Approximate Unlearning in LLMs](https://arxiv.org/abs/2310.02238) | arXiv | LLM | [HF](https://huggingface.co/datasets/PhillipGuo/WHP_Generic_Predictions) | 363 |
| Chongyu Fan et al. | [SalUn: Empowering Machine Unlearning via Gradient-based Weight Saliency in Both Image Classification and Generation](https://doi.org/10.48550/arXiv.2310.12508) | ICLR | Vision | [GitHub](https://github.com/optml-group/unlearn-saliency) | 351 |
| Nupur Kumari et al. | [Ablating Concepts in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICCV51070.2023.02074) | ICCV | Diffusion | [GitHub](https://github.com/nupurkmr9/concept-ablation) | 327 |
| Eric J. Zhang et al. | [Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPRW63382.2024.00182) | CVPR | Diffusion | [GitHub](https://github.com/SHI-Labs/Forget-Me-Not) | 313 |
| Yuanshun Yao, Xiaojun Xu, Yang Liu | [Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2310.10683) | NeurIPS | LLM | [GitHub](https://github.com/kevinyaobytedance/llm_unlearn) | 283 |
| Meghdad Kurmanji, P. Triantafillou, Eleni Triantafillou | [Towards Unbounded Machine Unlearning](https://doi.org/10.48550/arXiv.2302.09880) | NeurIPS | Vision | [GitHub](https://github.com/meghdadk/SCRUB) | 280 |
| Jiaao Chen, Diyi Yang | [Unlearn What You Want to Forget: Efficient Unlearning for LLMs](https://doi.org/10.48550/arXiv.2310.20150) | EMNLP | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 241 |
| Jinghan Jia et al. | [Model Sparsity Can Simplify Machine Unlearning](https://doi.org/10.52202/075280-2246) | NeurIPS | Other | [GitHub](https://github.com/optml-group/unlearn-sparse) | 240 |
| Gowthami Somepalli et al. | [Understanding and Mitigating Copying in Diffusion Models](https://doi.org/10.48550/arXiv.2305.20086) | NeurIPS | Diffusion | [GitHub](https://github.com/somepago/dcr) | 227 |
| Martin Pawelczyk, Seth Neel, Himabindu Lakkaraju | [In-Context Unlearning: Language Models as Few Shot Unlearners](https://doi.org/10.48550/arXiv.2310.07579) | ICML | LLM | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 218 |
| Jack Foster, Stefan Schoepf, A. Brintrup | [Fast Machine Unlearning Without Retraining Through Selective Synaptic Dampening](https://doi.org/10.48550/arXiv.2308.07707) | AAAI | Vision | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 209 |
| Yu-Lin Tsai et al. | [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://doi.org/10.48550/arXiv.2310.10012) | ICLR | Diffusion | [GitHub](https://github.com/chiayi-hsu/Ring-A-Bell) | 207 |
| Yimeng Zhang et al. | [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://doi.org/10.48550/arXiv.2310.11868) | ECCV | Diffusion | [GitHub](https://github.com/optml-group/diffusion-mu-attack) | 205 |
| Alvin Heng, Harold Soh | [Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models](https://doi.org/10.48550/arXiv.2305.10120) | NeurIPS | Diffusion | [GitHub](https://github.com/clear-nus/selective-amnesia) | 187 |
| Qiusi Zhan et al. | [Removing RLHF Protections in GPT-4 via Fine-Tuning](https://doi.org/10.48550/arXiv.2311.05553) | NAACL | LLM | [GitHub](https://github.com/vktrbr/hack-gpt-35) | 169 |
| Vaidehi Patil, Peter Hase, Mohit Bansal | [Can Sensitive Information Be Deleted From LLMs? Objectives for Defending Against Extraction Attacks](https://doi.org/10.48550/arXiv.2309.17410) | ICLR | LLM | [GitHub](https://github.com/vaidehi99/infodeletionattacks) | 167 |
| Jinghan Zhang et al. | [Composing Parameter-Efficient Modules with Arithmetic Operations](https://doi.org/10.48550/arXiv.2306.14870) | NeurIPS | LLM | [GitHub](https://github.com/sjtu-lit/pem_composition) | 164 |
| Min Chen et al. | [Boundary Unlearning: Rapid Forgetting of Deep Networks via Shifting the Decision Boundary](https://doi.org/10.1109/CVPR52729.2023.00750) | CVPR | Vision | [GitHub](https://github.com/OngWinKent/MachineUnlearning) | 162 |
| Zhi-Yi Chin et al. | [Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts](https://doi.org/10.48550/arXiv.2309.06135) | ICML | Diffusion | [HF](https://huggingface.co/datasets/zhiyichin/p4d) | 155 |
| Wei Yuan et al. | [Federated Unlearning for On-Device Recommendation](https://doi.org/10.1145/3539597.3570463) | WSDM | Federated | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 152 |
| Mengyao Lyu et al. | [One-dimensional Adapter to Rule Them All: Concepts, Diffusion Models and Erasing Applications](https://doi.org/10.1109/CVPR52733.2024.00722) | CVPR | Diffusion | [GitHub](https://github.com/Con6924/SPM) | 145 |
| Jie Xu et al. | [Machine Unlearning: Solutions and Challenges](https://doi.org/10.1109/TETCI.2024.3379240) | IEEE TETCI | Other | [GitHub](https://github.com/pybrush/pybrush) | 128 |
| Ziyao Liu et al. | [A Survey on Federated Unlearning: Challenges, Methods, and Future Directions](https://doi.org/10.1145/3679014) | ACM Computing Surveys | Federated | — | 126 |
| Nikhil Vyas, S. Kakade, B. Barak | [On Provable Copyright Protection for Generative Models](https://arxiv.org/abs/2302.10870) | ICML | Other | [GitHub](https://github.com/chawins/llm-sp) | 121 |
| Chi-Pin Huang et al. | [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://doi.org/10.48550/arXiv.2311.17717) | ECCV | Diffusion | [GitHub](https://github.com/jasper0314-huang/Receler) | 115 |
| Lefeng Zhang et al. | [FedRecovery: Differentially Private Machine Unlearning for Federated Learning Frameworks](https://doi.org/10.1109/tifs.2023.3297905) | IEEE T-IFS | Federated | — | 115 |
| Daphne Ippolito et al. | [Preventing Generation of Verbatim Memorization in Language Models Gives a False Sense of Privacy](https://doi.org/10.18653/v1/2023.inlg-main.3) | International Conference on Natural Language Generation | LLM | [HF](https://huggingface.co/spaces/mithril-security/starcoder_memorization_checker) | 109 |
| Jooyoung Lee et al. | [Do Language Models Plagiarize?](https://doi.org/10.1145/3543507.3583199) | WWW | LLM | [GitHub](https://github.com/baixianghuang/survey-authorship) | 109 |
| Lingzhi Wang et al. | [KGA: A General Machine Unlearning Framework Based on Knowledge Gap Alignment](https://doi.org/10.48550/arXiv.2305.06535) | ACL | LLM | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 107 |
| Zhenyi Wang et al. | [A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning](https://doi.org/10.1109/TPAMI.2024.3498346) | IEEE TPAMI | Other | [GitHub](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) | 102 |
| Ruizhe Chen et al. | [Fast Model Debias with Machine Unlearning](https://doi.org/10.48550/arXiv.2310.12560) | NeurIPS | Vision | [GitHub](https://github.com/diadai/Machine-Unlearning) | 102 |
| Jiancan Wu et al. | [GIF: A General Graph Unlearning Strategy via Influence Function](https://doi.org/10.1145/3543507.3583521) | WWW | Graph | [GitHub](https://github.com/SJTU-DMTai/awesome-ml-data-quality-papers) | 97 |
| Xinwei Wu et al. | [DEPN: Detecting and Editing Privacy Neurons in Pretrained Language Models](https://doi.org/10.48550/arXiv.2310.20138) | EMNLP | LLM | [GitHub](https://github.com/ZJU-LLMs/Foundations-of-LLMs) | 92 |
| Xiangrong Zhu, Guangyao Li, Wei Hu | [Heterogeneous Federated Knowledge Graph Embedding Learning and Unlearning](https://doi.org/10.1145/3543507.3583305) | WWW | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 91 |
| Haibo Zhang et al. | [A Review on Machine Unlearning](https://doi.org/10.1007/s42979-023-01767-4) | SN Computer Science | Other | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 88 |
| Minh Pham, Kelly O. Marshall, C. Hegde | [Circumventing Concept Erasure Methods For Text-to-Image Generative Models](https://doi.org/10.48550/arXiv.2308.01508) | ICLR | Diffusion | [GitHub](https://github.com/nyu-dice-lab/circumventing-concept-erasure) | 82 |
| Pratyush Maini et al. | [Can Neural Network Memorization Be Localized?](https://doi.org/10.48550/arXiv.2307.09542) | ICML | Vision | [GitHub](https://github.com/pratyushmaini/localizing-memorization) | 82 |
| Sungmin Cha et al. | [Learning to Unlearn: Instance-wise Unlearning for Pre-trained Classifiers](https://doi.org/10.48550/arXiv.2301.11578) | AAAI | Vision | [GitHub](https://github.com/csm9493/L2UL) | 79 |
| Chaochao Chen et al. | [UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition](https://doi.org/10.52202/075280-0553) | NeurIPS | Recsys | — | 79 |
| Hang Li et al. | [Self-Discovering Interpretable Diffusion Latent Directions for Responsible Text-to-Image Generation](https://doi.org/10.1109/CVPR52733.2024.01141) | CVPR | Diffusion | [GitHub](https://github.com/hangligit/InterpretDiffusion) | 77 |
| Tianshi Che et al. | [Fast Federated Machine Unlearning with Nonlinear Functional Theory](https://www.semanticscholar.org/paper/bcd2c4ef6b1e985e0783e886b2576abe3c7983f9) | ICML | Federated | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 77 |
| Ningxin Su, Baochun Li | [Asynchronous Federated Unlearning](https://doi.org/10.1109/INFOCOM53939.2023.10229075) | IEEE Conference on Computer Communications | Federated | — | 74 |
| Kent K. Chang et al. | [Speak, Memory: An Archaeology of Books Known to ChatGPT/GPT-4](https://doi.org/10.18653/v1/2023.emnlp-main.453) | EMNLP | LLM | [GitHub](https://github.com/bamman-group/gpt4-books) | 69 |
| T. Shaik et al. | [Exploring the Landscape of Machine Unlearning: A Comprehensive Survey and Taxonomy](https://doi.org/10.1109/TNNLS.2024.3486109) | IEEE TNNLS | Other | — | 67 |
| Shen Lin et al. | [ERM-KTP: Knowledge-Level Machine Unlearning via Knowledge Transfer](https://doi.org/10.1109/CVPR52729.2023.01929) | CVPR | Vision | [GitHub](https://github.com/RUIYUN-ML/ERM-KTP) | 58 |
| Aly M. Kassem, Omar Mahmoud, Sherif Saad | [Preserving Privacy Through Dememorization: An Unlearning Technique For Mitigating Memorization Risks In Language Models](https://doi.org/10.18653/v1/2023.emnlp-main.265) | EMNLP | LLM | [GitHub](https://github.com/Alymostafa/DeMemorization) | 58 |
| Kun Wu et al. | [Certified Edge Unlearning for Graph Neural Networks](https://doi.org/10.1145/3580305.3599271) | KDD | Graph | [GitHub](https://github.com/kunwu522/certified_edge_unlearning) | 57 |
| Eli Chien, Chao Pan, O. Milenkovic | [Efficient Model Updates for Approximate Unlearning of Graph-Structured Data](https://www.semanticscholar.org/paper/5e04e20d9c550fc1cef1f1f86b30aadf0492fbac) | ICLR | Graph | [GitHub](https://github.com/thupchnsky/sgc_unlearn) | 55 |
| Jiali Cheng et al. | [GNNDelete: A General Strategy for Unlearning in Graph Neural Networks](https://doi.org/10.48550/arXiv.2302.13406) | ICLR | Graph | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 54 |
| Hui Xia et al. | [FedME<sup>2</sup>: Memory Evaluation &amp; Erase Promoting Federated Unlearning in DTMN](https://doi.org/10.1109/jsac.2023.3310049) | IEEE Journal on Selected Areas in Communications | Federated | — | 53 |
| Yu Guo et al. | [Verifying in the Dark: Verifiable Machine Unlearning by Using Invisible Backdoor Triggers](https://doi.org/10.1109/tifs.2023.3328269) | IEEE T-IFS | Other | [GitHub](https://github.com/techyangj/VD) | 52 |
| Heng Xu et al. | [Machine Unlearning: A Survey](https://doi.org/10.1145/3603620) | ACM Computing Surveys | Other | — | 51 |
| Adrian de Wynter et al. | [An evaluation on large language model outputs: Discourse and memorization](https://doi.org/10.1016/j.nlp.2023.100024) | Natural Language Processing Journal | LLM | [GitHub](https://github.com/aiverify-foundation/LLM-Evals-Catalogue) | 47 |
| Hui Xia et al. | [FedME2: Memory Evaluation & Erase Promoting Federated Unlearning in DTMN](https://doi.org/10.1109/JSAC.2023.3310049) | IEEE Journal on Selected Areas in Communications | Federated | — | 46 |
| Hongsheng Hu et al. | [A Duty to Forget, a Right to be Assured? Exposing Vulnerabilities in Machine Unlearning Services](https://doi.org/10.48550/arXiv.2309.08230) | NDSS | Other | — | 45 |
| Yuyuan Li et al. | [Selective and collaborative influence function for efficient recommendation unlearning](https://doi.org/10.1016/j.eswa.2023.121025) | Expert Systems with Applications | Recsys | — | 44 |
| Yian Zhao et al. | [Federated Unlearning With Momentum Degradation](https://doi.org/10.1109/jiot.2023.3321594) | IEEE IoT-J | Federated | — | 44 |
| Lukas Struppek et al. | [Exploiting Cultural Biases via Homoglyphs in Text-to-Image Synthesis](https://doi.org/10.1613/jair.1.15388) | Journal of Artificial Intelligence Research | Diffusion | [GitHub](https://github.com/LukasStruppek/Exploiting-Cultural-Biases-via-Homoglyphs) | 44 |
| Cheng-Long Wang, Mengdi Huai, Di Wang | [Inductive Graph Unlearning](https://doi.org/10.48550/arXiv.2304.03093) | USENIX Security | Graph | [GitHub](https://github.com/Happy2Git/GUIDE) | 44 |
| Nianwen Si et al. | [Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges](https://doi.org/10.48550/arXiv.2311.15766) | arXiv | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 44 |
| Wang Fei, Baochun Li, Bo Li | [Federated Unlearning and Its Privacy Threats](https://doi.org/10.1109/mnet.004.2300056) | IEEE Network | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 43 |
| Chao Pan, Eli Chien, Olgica Milenković | [Unlearning Graph Classifiers with Limited Data Resources](https://doi.org/10.1145/3543507.3583547) | WWW | Graph | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 43 |
| V. Smith et al. | [Identifying and Mitigating Privacy Risks Stemming from Language Models: A Survey](https://doi.org/10.48550/arXiv.2310.01424) | arXiv | LLM | [GitHub](https://github.com/chawins/llm-sp) | 42 |
| Tuan Hoang et al. | [Learn to Unlearn for Deep Neural Networks: Minimizing Unlearning Interference with Gradient Projection](https://doi.org/10.1109/WACV57701.2024.00475) | WACV | Vision | [GitHub](https://github.com/hnanhtuan/projected_gradient_unlearning) | 41 |
| Jinghan Jia et al. | [Model Sparsification Can Simplify Machine Unlearning](https://doi.org/10.48550/arXiv.2304.04934) | arXiv | Other | — | 41 |
| Zhengyue Zhao et al. | [Unlearnable Examples for Diffusion Models: Protect Data from Unauthorized Exploitation](https://doi.org/10.48550/arXiv.2306.01902) | arXiv | Diffusion | [GitHub](https://github.com/tanjascats/GenAI-IP-protection) | 40 |
| Yoichi Ishibashi, H. Shimodaira | [Knowledge Sanitization of Large Language Models](https://doi.org/10.48550/arXiv.2309.11852) | arXiv | LLM | [GitHub](https://github.com/zjunlp/KnowledgeEditingPapers) | 39 |
| Sanghyun Kim et al. | [Towards Safe Self-Distillation of Internet-Scale Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2307.05977) | arXiv | Diffusion | [GitHub](https://github.com/nannullna/safe-diffusion) | 39 |
| Weiqi Wang et al. | [BFU: Bayesian Federated Unlearning with Parameter Self-Sharing](https://doi.org/10.1145/3579856.3590327) | CCS | Federated | [GitHub](https://github.com/wwq5-code/BFU-Code) | 37 |
| Xintong Guo et al. | [FAST: Adopting Federated Unlearning to Eliminating Malicious Terminals at Server Side](https://doi.org/10.1109/tnse.2023.3343117) | IEEE TNSE | Federated | — | 37 |
| Wei Qian et al. | [Towards Understanding and Enhancing Robustness of Deep Learning Models against Malicious Unlearning Attacks](https://doi.org/10.1145/3580305.3599526) | KDD | Other | — | 37 |
| Guang-Ming Li et al. | [Subspace based Federated Unlearning](https://doi.org/10.48550/arXiv.2302.12448) | TMLR | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 37 |
| Junxu Liu et al. | [MUter: Machine Unlearning on Adversarially Trained Models](https://doi.org/10.1109/ICCV51070.2023.00451) | ICCV | Vision | [GitHub](https://github.com/JunxuLiu/MUter) | 36 |
| Zuobin Xiong et al. | [Exact-Fun: An Exact and Efficient Federated Unlearning Approach](https://doi.org/10.1109/ICDM58522.2023.00188) | Industrial Conference on Data Mining | Federated | — | 36 |
| Korbinian Koch, Marcus Soll | [No Matter How You Slice It: Machine Unlearning with SISA Comes at the Expense of Minority Classes](https://doi.org/10.1109/SaTML54575.2023.00047) | SaTML | Other | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 36 |
| Yuyuan Li et al. | [Making Users Indistinguishable: Attribute-wise Unlearning in Recommender Systems](https://doi.org/10.1145/3581783.3612418) | ACM MM | Recsys | [GitHub](https://github.com/ZhangYizhao/RecAU) | 35 |
| Antonia Karamolegkou et al. | [Copyright Violations and Large Language Models](https://doi.org/10.18653/v1/2023.emnlp-main.458) | EMNLP | LLM | [GitHub](https://github.com/coastalcph/CopyrightLLMs) | 35 |
| Jiaqi Liu et al. | [Certified Minimax Unlearning with Generalization Rates and Deletion Capacity](https://doi.org/10.48550/arXiv.2312.10336) | NeurIPS | Other | [GitHub](https://github.com/M1LKzzz/Sensitive-Data-Collection-and-Analysis-Mechanism-with-Local-Differential-Privacy-Preservation) | 35 |
| M. Li, Xander Davies, Max Nadeau | [Circuit Breaking: Removing Model Behaviors with Targeted Ablation](https://doi.org/10.48550/arXiv.2309.05973) | arXiv | LLM | [GitHub](https://github.com/xanderdavies/circuit-breaking) | 35 |
| Pengfei Wang et al. | [Mitigating Poor Data Quality Impact with Federated Unlearning for Human-Centric Metaverse](https://doi.org/10.1109/jsac.2023.3345388) | IEEE Journal on Selected Areas in Communications | Federated | — | 34 |
| Dasol Choi, Dongbin Na | [Towards Machine Unlearning Benchmarks: Forgetting the Personal Identities in Facial Recognition Systems](https://doi.org/10.48550/arXiv.2311.02240) | arXiv | Vision | [GitHub](https://github.com/ndb796/machineunlearning) | 34 |
| Seunghoo Hong, Juhun Lee, Simon S. Woo | [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2312.12807) | AAAI | Diffusion | — | 33 |
| Yonatan Dukler et al. | [SAFE: Machine Unlearning With Shard Graphs](https://doi.org/10.1109/ICCV51070.2023.01569) | ICCV | Vision | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 32 |
| Zixuan Ni et al. | [Degeneration-Tuning: Using Scrambled Grid shield Unwanted Concepts from Stable Diffusion](https://doi.org/10.1145/3581783.3611867) | ACM MM | Diffusion | [GitHub](https://github.com/openai/dalle-2-preview/blob) | 31 |
| T. Shaik et al. | [FRAMU: Attention-Based Machine Unlearning Using Federated Reinforcement Learning](https://doi.org/10.1109/TKDE.2024.3382726) | IEEE TKDE | Federated | — | 31 |
| Alexander X. Oesterling et al. | [Fair Machine Unlearning: Data Removal while Mitigating Disparities](https://doi.org/10.48550/arXiv.2307.14754) | AISTATS | Other | [GitHub](https://github.com/AI4LIFE-GROUP/fair-unlearning) | 30 |
| Ting-Yun Chang, Jesse Thomason, Robin Jia | [Do Localization Methods Actually Localize Memorized Data in LLMs? A Tale of Two Benchmarks](https://doi.org/10.48550/arXiv.2311.09060) | NAACL | LLM | [GitHub](https://github.com/safr-ai-lab/survey-llm) | 30 |
| Tianlin Liu, S. Soatto | [Tangent Model Composition for Ensembling and Continual Fine-tuning](https://doi.org/10.1109/ICCV51070.2023.01712) | ICCV | Vision | [GitHub](https://github.com/tianyu139/tangent-model-composition) | 29 |
| Mengdi Huai et al. | [Static and Sequential Malicious Attacks in the Context of Selective Forgetting](https://doi.org/10.52202/075280-3276) | NeurIPS | Other | — | 29 |
| Weiqi Wang et al. | [Machine Unlearning via Representation Forgetting With Parameter Self-Sharing](https://doi.org/10.1109/tifs.2023.3331239) | IEEE T-IFS | Vision | [GitHub](https://github.com/wwq5-code/RFU-SS) | 28 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [Get Rid of Your Trail: Remotely Erasing Backdoors in Federated Learning](https://doi.org/10.1109/TAI.2024.3465441) | IEEE TAI | Federated | [GitHub](https://github.com/momalab/federated_backdoor_unlearning) | 28 |
| Weilin Cong, Mehrdad Mahdavi | [Efficiently Forgetting What You Have Learned in Graph Representation Learning via Projection](https://doi.org/10.48550/arXiv.2302.08990) | AISTATS | Graph | [GitHub](https://github.com/MinChen00/Graph-Unlearning) | 27 |
| Junfeng Guo et al. | [PolicyCleanse: Backdoor Detection and Mitigation for Competitive Reinforcement Learning](https://doi.org/10.1109/iccv51070.2023.00433) | ICCV | Other | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 27 |
| Jiachen Zhao et al. | [Learning and Forgetting Unsafe Examples in Large Language Models](https://doi.org/10.48550/arXiv.2312.12736) | ICML | LLM | [GitHub](https://github.com/andotalao24/learn-forget-unsafe-llm) | 27 |
| Haocheng Xia et al. | [Equitable Data Valuation Meets the Right to Be Forgotten in Model Markets](https://doi.org/10.14778/3611479.3611531) | VLDB Endowment | Other | [GitHub](https://github.com/ZJU-DIVER/ValuationMeetsRTBF) | 27 |
| Weilin Cong, Mehrdad Mahrdavi | [GraphEditor : An Efficient Graph Representation Learning and Unlearning Approach](https://www.semanticscholar.org/paper/6d00fbb3c7aad35066efc09971fbb38c420741be) | arXiv | Graph | — | 26 |
| Rui Jin et al. | [Forgettable Federated Linear Learning with Certified Data Removal](https://doi.org/10.48550/arXiv.2306.02216) | arXiv | Federated | [GitHub](https://github.com/Nanboy-Ronan/2F2L-Federated-Unlearning) | 25 |
| Zheng Dai, D. Gifford | [Training Data Attribution for Diffusion Models](https://doi.org/10.48550/arXiv.2306.02174) | arXiv | Diffusion | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 25 |
| Ningning Ding et al. | [Incentive Mechanism Design for Federated Learning and Unlearning](https://doi.org/10.1145/3565287.3610269) | ACM Interational Symposium on Mobile Ad Hoc Networking and Computing | Federated | — | 23 |
| Zhaomin Wu et al. | [DeltaBoost: Gradient Boosting Decision Trees with Efficient Machine Unlearning](https://doi.org/10.1145/3589313) | ACM on Management of Data | Other | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 23 |
| Saemi Moon, Seunghyuk Cho, Dongwoo Kim | [Feature Unlearning for Pre-trained GANs and VAEs](https://doi.org/10.1609/aaai.v38i19.30138) | AAAI | Diffusion | [GitHub](https://github.com/NVlabs/stylegan) | 22 |
| Marco Cotogni et al. | [DUCK: Distance-based Unlearning via Centroid Kinematics](https://doi.org/10.48550/arXiv.2312.02052) | arXiv | Vision | [GitHub](https://github.com/ocram17/duck) | 22 |
| Xin Zhou et al. | [Making Harmful Behaviors Unlearnable for Large Language Models](https://doi.org/10.48550/arXiv.2311.02105) | ACL | LLM | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 21 |
| Juexiao Zhou et al. | [A unified method to revoke the private data of patients in intelligent healthcare with audit to forget](https://doi.org/10.1038/s41467-023-41703-x) | Nature Communications | Vision | [GitHub](https://github.com/Krimmyjack/Fine-tuning-of-medical-privacy) | 21 |
| Sebastian Schelter, Mozhdeh Ariannezhad, Maarten de Rijke | [Forget Me Now: Fast and Exact Unlearning in Neighborhood-based Recommendation](https://doi.org/10.1145/3539618.3591989) | SIGIR | Recsys | — | 21 |
| Jiaxi Yang, Yang Zhao, Lixu Wang | [A Survey of Federated Unlearning: A Taxonomy, Challenges and Future Directions](https://doi.org/10.48550/arXiv.2310.19218) | arXiv | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 21 |
| T. Shaik et al. | [Exploring the Landscape of Machine Unlearning: A Survey and Taxonomy](https://www.semanticscholar.org/paper/3360d8d78e04579f5778b988506a0439115ceece) | arXiv | Other | — | 21 |
| Jaydeep Borkar | [What can we learn from Data Leakage and Unlearning for Law?](https://doi.org/10.48550/arXiv.2307.10476) | arXiv | LLM | — | 21 |
| Hyunjun Kim, Sangyong Lee, Simon S. Woo | [Layer Attack Unlearning: Fast and Accurate Machine Unlearning via Layer Level Attack and Knowledge Distillation](https://doi.org/10.48550/arXiv.2312.16823) | AAAI | Vision | — | 20 |
| Siva Sai et al. | [Machine Un-learning: An Overview of Techniques, Applications, and Future Directions](https://doi.org/10.1007/s12559-023-10219-3) | Cognitive Computation | Other | — | 20 |
| Jiali Cheng, Hadi Amiri | [MultiDelete for Multimodal Machine Unlearning](https://doi.org/10.1007/978-3-031-72940-9_10) | ECCV | Vision | [GitHub](https://github.com/CLU-UML/MultiDelete) | 20 |
| Zhili Liu et al. | [Implicit Concept Removal of Diffusion Models](https://doi.org/10.1007/978-3-031-72664-4_26) | ECCV | Diffusion | [HF](https://huggingface.co/datasets/zhili-liu/implicit-concept-dataset) | 20 |
| Yash Sinha, Murari Mandal, Mohan Kankanhalli | [Distill to Delete: Unlearning in Graph Networks With Knowledge Distillation](https://doi.org/10.1109/TNNLS.2025.3607995) | IEEE TNNLS | Graph | [GitHub](https://github.com/MachineUnlearn/D2DGN) | 20 |
| Yiyang Huang, C. Canonne | [Tight Bounds for Machine Unlearning via Differential Privacy](https://doi.org/10.48550/arXiv.2309.00886) | Journal of Privacy and Confidentiality | Other | [GitHub](https://github.com/XiangmanLI/Harmful-Information-Unlearning) | 20 |
| Akash Dhasade et al. | [QuickDrop: Efficient Federated Unlearning by Integrated Dataset Distillation](https://doi.org/10.48550/arXiv.2311.15603) | arXiv | Federated | [GitHub](https://github.com/sacs-epfl/quickdrop) | 20 |
| Hongyu Qiu et al. | [FedCIO: Efficient Exact Federated Unlearning with Clustering, Isolation, and One-shot Aggregation](https://doi.org/10.1109/BigData59044.2023.10386788) | BigData Congress [Services Society] | Federated | — | 19 |
| Huawei Lin et al. | [Machine Unlearning in Gradient Boosting Decision Trees](https://doi.org/10.1145/3580305.3599420) | KDD | Other | [GitHub](https://github.com/huawei-lin/GBDT_unlearning) | 19 |
| Zhili Liu et al. | [Geom-Erasing: Geometry-Driven Removal of Implicit Concept in Diffusion Models](https://doi.org/10.48550/arXiv.2310.05873) | arXiv | Diffusion | — | 19 |
| Myung Gyo Oh et al. | [Membership Inference Attacks With Token-Level Deduplication on Korean Language Models](https://doi.org/10.1109/access.2023.3239668) | IEEE Access | LLM | — | 18 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Gradient-free Class Forgetting](https://arxiv.org/abs/2312.00761) | TMLR | Vision | [GitHub](https://github.com/sangamesh-kodge/class_forgetting) | 18 |
| Seohui Bae et al. | [Gradient Surgery for One-shot Unlearning on Generative Model](https://doi.org/10.48550/arXiv.2307.04550) | arXiv | Other | — | 18 |
| Mimee Xu et al. | [Netflix and Forget: Efficient and Exact Machine Unlearning from Bi-linear Recommendations](https://doi.org/10.48550/arXiv.2302.06676) | arXiv | Recsys | — | 18 |
| Saemi Moon, Seunghyuk Cho, Dongwoo Kim | [Feature Unlearning for Generative Models via Implicit Feedback](https://doi.org/10.48550/arXiv.2303.05699) | arXiv | Diffusion | — | 18 |
| Ningning Ding, Ermin Wei, Randall Berry | [Strategic Data Revocation in Federated Unlearning](https://doi.org/10.1109/INFOCOM52122.2024.10621201) | IEEE Conference on Computer Communications | Federated | — | 17 |
| Hui Sun et al. | [Generative Adversarial Networks Unlearning](https://doi.org/10.1109/TDSC.2025.3564992) | IEEE TDSC | Other | — | 16 |
| Bang Wu et al. | [GraphGuard: Detecting and Counteracting Training Data Misuse in Graph Neural Networks](https://doi.org/10.48550/arXiv.2312.07861) | NDSS | Graph | [GitHub](https://github.com/awslabs/g) | 16 |
| Shotaro Ishihara | [Training Data Extraction From Pre-trained Language Models: A Survey](https://doi.org/10.18653/v1/2023.trustnlp-1.23) | arXiv | LLM | [GitHub](https://github.com/Peng99999/Data-Augmentation-Papers) | 16 |
| Yongjing Zhang et al. | [Machine Unlearning by Reversing the Continual Learning](https://doi.org/10.3390/app13169341) | Applied Sciences | Vision | — | 15 |
| Zihao Deng et al. | [Vertical Federated Unlearning on the Logistic Regression Model](https://doi.org/10.3390/electronics12143182) | Electronics | Federated | [GitHub](https://github.com/bryanhx/Vertical-Federated-Unlearning-Benchmark) | 15 |
| Tian-Yu Liu, Aditya Golatkar, S. Soatto | [Tangent Transformers for Composition, Privacy and Removal](https://doi.org/10.48550/arXiv.2307.08122) | ICLR | Vision | [GitHub](https://github.com/tianyu139/tangent-model-composition) | 15 |
| Rui Zhu et al. | [Selective Amnesia: On Efficient, High-Fidelity and Blind Suppression of Backdoor Effects in Trojaned Machine Learning Models](https://doi.org/10.1109/sp46215.2023.10351028) | IEEE S&P | Vision | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 15 |
| Xin Xin et al. | [On the Effectiveness of Unlearning in Session-Based Recommendation](https://doi.org/10.1145/3616855.3635823) | WSDM | Recsys | [GitHub](https://github.com/shirryliu/SRU-code) | 15 |
| Aditya Golatkar et al. | [Training Data Protection with Compositional Diffusion Models](https://doi.org/10.48550/arXiv.2308.01937) | arXiv | Diffusion | [GitHub](https://github.com/Zoky-2020/Security_and_Privacy_in_AIGC) | 15 |
| Yuyuan Li et al. | [Federated Unlearning via Active Forgetting](https://doi.org/10.48550/arXiv.2307.03363) | arXiv | Federated | — | 15 |
| Kongyang Chen et al. | [Privacy preserving machine unlearning for smart cities](https://doi.org/10.1007/s12243-023-00960-z) | Annals of Telecommunications | Other | — | 14 |
| Zonghao Ying, Bin Wu | [DLP: towards active defense against backdoor attacks with decoupled learning process](https://doi.org/10.1186/s42400-023-00141-4) | Cybersecurity | Vision | — | 14 |
| Satyapriya Krishna, Jiaqi W. Ma, Himabindu Lakkaraju | [Towards Bridging the Gaps between the Right to Explanation and the Right to be Forgotten](https://doi.org/10.48550/arXiv.2302.04288) | ICML | Other | — | 14 |
| Matthew Jagielski et al. | [How to Combine Membership-Inference Attacks on Multiple Updated Machine Learning Models](https://doi.org/10.56553/popets-2023-0078) | PoPETs | Other | [GitHub](https://github.com/stanleykywu/model-updates) | 14 |
| Vedant Shah et al. | [Unlearning via Sparse Representations](https://doi.org/10.48550/arXiv.2311.15268) | TMLR | Vision | [GitHub](https://github.com/facebookresearch/fvcore) | 14 |
| Piyush Tiwary et al. | [Adapt then Unlearn: Exploiting Parameter Space Semantics for Unlearning in Generative Adversarial Networks](https://doi.org/10.48550/arXiv.2309.14054) | TMLR | Diffusion | [GitHub](https://github.com/atriguha/Adapt_Unlearn) | 14 |
| S. Kadhe et al. | [FairSISA: Ensemble Post-Processing to Improve Fairness of Unlearning in LLMs](https://doi.org/10.48550/arXiv.2312.07420) | arXiv | LLM | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 14 |
| Mustafa Ozdayi et al. | [Controlling the Extraction of Memorized Data from Large Language Models via Prompt-Tuning](https://doi.org/10.18653/v1/2023.acl-short.129) | arXiv | LLM | — | 14 |
| Dayong Ye et al. | [Reinforcement Unlearning](https://doi.org/10.48550/arXiv.2312.15910) | NDSS | Other | [GitHub](https://github.com/cp-lab-uts/Reinforcement-Unlearning) | 13 |
| J. Hartley. et al. | [Neural networks memorise personal information from one sample](https://doi.org/10.1038/s41598-023-48034-3) | Scientific Reports | Other | — | 13 |
| Badih Ghazi et al. | [Ticketed Learning-Unlearning Schemes](https://doi.org/10.48550/arXiv.2306.15744) | Annual Conference Computational Learning Theory | Other | — | 11 |
| Jia Shi et al. | [DeepClean: Machine Unlearning on the Cheap by Resetting Privacy Sensitive Weights using the Fisher Diagonal](https://doi.org/10.48550/arXiv.2311.10448) | ECCV Workshops | Vision | — | 11 |
| Anwar Said et al. | [A Survey of Graph Unlearning](https://doi.org/10.48550/arXiv.2310.02164) | arXiv | Graph | — | 11 |
| Samuele Poppi et al. | [Removing NSFW Concepts from Vision-and-Language Models for Text-to-Image Retrieval and Generation](https://doi.org/10.48550/arXiv.2311.16254) | ECCV | Diffusion | [GitHub](https://github.com/aimagelab/safe-clip) | 10 |
| Samuele Poppi et al. | [Multiclass Unlearning for Image Classification via Weight Filtering](https://doi.org/10.1109/MIS.2024.3412742) | IEEE Intelligent Systems | Vision | — | 10 |
| Xulong Zhang et al. | [Machine Unlearning Methodology Based on Stochastic Teacher Network](https://doi.org/10.1007/978-3-031-46677-9_18) | International Conference on Advanced Data Mining and Applications | Other | — | 10 |
| Yufang Liu et al. | [Unlearning with Fisher Masking](https://doi.org/10.48550/arXiv.2310.05331) | arXiv | Vision | — | 10 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Training-free Approach to Controlled Forgetting](https://doi.org/10.48550/arXiv.2312.00761) | arXiv | Vision | — | 10 |
| Ningning Ding et al. | [Incentivized Federated Learning and Unlearning](https://doi.org/10.1109/TMC.2025.3557857) | IEEE TMC | Federated | — | 9 |
| Wangkun Xu, Fei Teng | [Task-Aware Machine Unlearning and Its Application in Load Forecasting](https://doi.org/10.1109/TPWRS.2024.3376828) | IEEE Transactions on Power Systems | Other | [GitHub](https://github.com/xuwkk/task_aware_machine_unlearning) | 9 |
| Zhifeng Kong, Kamalika Chaudhuri | [Data Redaction from Conditional Generative Models](https://doi.org/10.1109/SaTML59370.2024.00035) | SaTML | Diffusion | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 9 |
| Zhifeng Kong, Amrita Roy Chowdhury, Kamalika Chaudhuri | [Can Membership Inferencing be Refuted?](https://doi.org/10.48550/arXiv.2303.03648) | arXiv | Other | [GitHub](https://github.com/erykml/medium) | 9 |
| Quintina Campbell, J. Herington, Andrew D. White | [Censoring chemical data to mitigate dual use risk](https://doi.org/10.48550/arXiv.2304.10510) | arXiv | Other | [GitHub](https://github.com/ur-whitelab/chem-dual-use) | 9 |
| Yanna Jiang et al. | [Split Unlearning](https://doi.org/10.1145/3719027.3744787) | CCS | Other | — | 8 |
| Sangyong Lee, Simon S. Woo | [UNDO: Effective and Accurate Unlearning Method for Deep Neural Networks](https://doi.org/10.1145/3583780.3615235) | CIKM | Vision | [GitHub](https://github.com/DASH-Lab/ML_privacy_research) | 8 |
| Kaiyue Zhang et al. | [Conditional Matching GAN Guided Reconstruction Attack in Machine Unlearning](https://doi.org/10.1109/GLOBECOM54140.2023.10437231) | Global Communications Conference | Other | — | 8 |
| Marvin Li et al. | [MoPe: Model Perturbation based Privacy Attacks on Language Models](https://doi.org/10.18653/v1/2023.emnlp-main.842) | arXiv | LLM | — | 8 |
| Peixin Zhang et al. | [Exploiting Machine Unlearning for Backdoor Attacks in Deep Learning System](https://arxiv.org/abs/2310.10659) | arXiv | Vision | [GitHub](https://github.com/seartifacts/bau) | 8 |
| Rui-Zhen Xu et al. | [A Revocation Key-based Approach Towards Efficient Federated Unlearning](https://doi.org/10.1109/AsiaJCIS60284.2023.00014) | Asia Joint Conference on Information Security | Federated | — | 7 |
| Guihong Li et al. | [Fast-NTK: Parameter-Efficient Unlearning for Large-Scale Models](https://doi.org/10.1109/CVPRW63382.2024.00027) | CVPR | Vision | [GitHub](https://github.com/ksasi/ModelEditingPapers) | 7 |
| Deming Zhou et al. | [Fast and Accurate SNN Model Strengthening for Industrial Applications](https://doi.org/10.3390/electronics12183845) | Electronics | Other | — | 7 |
| Enayat Ullah, R. Arora | [From Adaptive Query Release to Machine Unlearning](https://doi.org/10.48550/arXiv.2307.11228) | ICML | Other | [GitHub](https://github.com/XiangmanLI/Harmful-Information-Unlearning) | 7 |
| Yang Zhao et al. | [Exploring Federated Unlearning: Review, Comparison, and Insights](https://doi.org/10.1109/MNET.2025.3571462) | IEEE Network | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 7 |
| Mohammadhadi Shateri et al. | [Preserving Privacy in GANs Against Membership Inference Attack](https://doi.org/10.1109/tifs.2023.3342654) | IEEE T-IFS | Other | [GitHub](https://github.com/tensorflow/privacy) | 7 |
| Jens Leysen | [Exploring Unlearning Methods to Ensure the Privacy, Security, and Usability of Recommender Systems](https://doi.org/10.1145/3604915.3608862) | RecSys | Recsys | — | 7 |
| Jiahao Liu et al. | [Recommendation Unlearning via Matrix Correction](https://doi.org/10.48550/arXiv.2307.15960) | arXiv | Recsys | — | 7 |
| Tzu-Hsuan Yang, Cheng-Te Li | [When Contrastive Learning Meets Graph Unlearning: Graph Contrastive Unlearning for Link Prediction](https://doi.org/10.1109/BigData59044.2023.10386624) | BigData Congress [Services Society] | Graph | — | 6 |
| Shuijing Zhang et al. | [Closed-form Machine Unlearning for Matrix Factorization](https://doi.org/10.1145/3583780.3614811) | CIKM | Recsys | — | 6 |
| Javier Martínez Llamas, D. Preuveneers, W. Joosen | [Effective Machine Learning-based Access Control Administration through Unlearning](https://doi.org/10.1109/EuroSPW59978.2023.00011) | Euro S&P | Other | — | 6 |
| Dominik Hintersdorf et al. | [Defending Our Privacy With Backdoors](https://doi.org/10.48550/arXiv.2310.08320) | European Conference on Artificial Intelligence | Vision | [GitHub](https://github.com/D0miH/Defending-Our-Privacy-With-Backdoors) | 6 |
| Zhe Liu, Ozlem Kalinli | [Forgetting Private Textual Sequences in Language Models Via Leave-One-Out Ensemble](https://doi.org/10.1109/ICASSP48485.2024.10446299) | ICASSP | LLM | — | 6 |
| Jie Song et al. | [ModelGiF: Gradient Fields for Model Functional Distance](https://doi.org/10.1109/ICCV51070.2023.00563) | ICCV | Vision | [GitHub](https://github.com/zju-vipa/modelgif) | 6 |
| Zhen Wang et al. | [FedCSA: Boosting the Convergence Speed of Federated Unlearning under Data Heterogeneity](https://doi.org/10.1109/ISPA-BDCloud-SocialCom-SustainCom59178.2023.00083) | IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom) | Federated | [GitHub](https://github.com/ZhenWang9/FedCSA) | 6 |
| Subhodip Panda, AP Prathosh | [FAST: Feature Aware Similarity Thresholding for Weak Unlearning in Black-Box Generative Models](https://doi.org/10.1109/TAI.2024.3499939) | IEEE TAI | Diffusion | [GitHub](https://github.com/Subhodip123/weak-unlearning-gan) | 6 |
| Zhou Zhai et al. | [Global Model Selection via Solution Paths for Robust Support Vector Machine](https://doi.org/10.1109/tpami.2023.3346765) | IEEE TPAMI | Other | [GitHub](https://github.com/zhouzhai/SPRSVM) | 6 |
| Ali Abbasi et al. | [CovarNav: Machine Unlearning via Model Inversion and Covariance Navigation](https://doi.org/10.48550/arXiv.2311.12999) | arXiv | Vision | — | 6 |
| Jian Zhang et al. | [SecureCut: Federated Gradient Boosting Decision Trees with Efficient Machine Unlearning](https://doi.org/10.48550/arXiv.2311.13174) | arXiv | Federated | — | 6 |
| Junde Li, Swaroop Ghosh | [Random Relabeling for Efficient Machine Unlearning](https://doi.org/10.48550/arXiv.2305.12320) | arXiv | Other | — | 6 |
| Zhe Liu, Xuedong Zhang, Fuchun Peng | [Mitigating Unintended Memorization in Language Models Via Alternating Teaching](https://doi.org/10.1109/icassp49357.2023.10096557) | ICASSP | LLM | [GitHub](https://github.com/alistvt/undesirable-llm-memorization) | 5 |
| Yuxiang Zeng et al. | [Toward Highly-Efficient and Accurate Services QoS Prediction via Machine Unlearning](https://doi.org/10.1109/access.2023.3291410) | IEEE Access | Recsys | — | 5 |
| Khaoula ElBedoui | [ECG Classifiction Based on Federated Unlearning](https://doi.org/10.1109/isncc58260.2023.10323758) | International Symposium on Networks, Computers and Communications | Federated | — | 5 |
| Peixin Zhang et al. | [Backdoor Attack through Machine Unlearning](https://doi.org/10.48550/arXiv.2310.10659) | arXiv | Other | [GitHub](https://github.com/seartifacts/bau) | 5 |
| Yashaswini Viswanath et al. | [Machine unlearning for generative AI](https://doi.org/10.69554/kzrs2422) | Journal of AI, robotics & workplace automation | Other | [GitHub](https://github.com/ExplainableML/align-then-unlearn) | 4 |
| Shaokui Wei et al. | [Shared Adversarial Unlearning: Backdoor Mitigation by Unlearning Shared Adversarial Examples](https://doi.org/10.52202/075280-1126) | NeurIPS | Vision | — | 4 |
| Rana Salal Ali et al. | [Unintended Memorization and Timing Attacks in Named Entity Recognition Models](https://doi.org/10.56553/popets-2023-0056) | PoPETs | LLM | — | 4 |
| Guanhua Ye et al. | [Heterogeneous Decentralized Machine Unlearning with Seed Model Distillation](https://doi.org/10.48550/arXiv.2308.13269) | arXiv | Federated | — | 4 |
| Leijie Wu et al. | [On Knowledge Editing in Federated Learning: Perspectives, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2306.01431) | arXiv | Federated | — | 4 |
| Tomoya Yamashita, Masanori Yamada, Takashi Shibata | [One-Shot Machine Unlearning with Mnemonic Code](https://doi.org/10.48550/arXiv.2306.05670) | Asian Conference on Machine Learning | Vision | [GitHub](https://github.com/tomyamkum/OneShotMU-with-MNCode) | 3 |
| Manal A. Alshehri, Xiangliang Zhang | [Forgetting User Preference in Recommendation Systems with Label-Flipping](https://doi.org/10.1109/BigData59044.2023.10386603) | BigData Congress [Services Society] | Recsys | — | 3 |
| Qun Song, Rui Tan, Jianping Wang | [Towards Efficient Personalized Driver Behavior Modeling with Machine Unlearning](https://doi.org/10.1145/3576914.3587489) | CPS-IoT Week Workshops | Other | — | 3 |
| Roie Reshef et al. | [Verification of Neural Networks Local Differential Classification Privacy](https://doi.org/10.48550/arXiv.2310.20299) | International Conference on Verification, Model Checking and Abstract Interpretation | Other | [GitHub](https://github.com/Robgy/Verification-of-Neural-Networks-Privacy) | 3 |
| Nora Belrose et al. | [LEACE: Perfect linear concept erasure in closed form](https://doi.org/10.52202/075280-2884) | NeurIPS | LLM | [GitHub](https://github.com/EleutherAI/tagged-pile) | 3 |
| Xulong Zhang et al. | [Machine Unlearning Methodology base on Stochastic Teacher Network](https://doi.org/10.48550/arXiv.2308.14322) | arXiv | Other | [HF](https://huggingface.co/spaces/llam/Papers) | 3 |
| Seunghee Koh et al. | [Disposable Transfer Learning for Selective Source Task Unlearning](https://doi.org/10.1109/ICCV51070.2023.01079) | ICCV | Vision | — | 2 |
| Shubhi Asthana et al. | [IDMU: Impact Driven Machine Unlearning](https://doi.org/10.1109/BigData59044.2023.10386841) | BigData Congress [Services Society] | Other | — | 1 |
| Lijun Chen et al. | [Incremental and Decremental Optimal Margin Distribution Learning](https://doi.org/10.24963/ijcai.2023/392) | IJCAI | Other | — | 1 |
| Long-Kai Huang et al. | [Retaining Beneficial Information from Detrimental Data for Neural Network Repair](https://doi.org/10.52202/075280-2084) | NeurIPS | Vision | — | 1 |
| Yuxiang Zeng et al. | [QoSEraser: A Data Erasable Framework for Web Service QoS Prediction](https://doi.org/10.1109/SSE60056.2023.00022) | SSE | Recsys | [GitHub](https://github.com/ZengYuXiang7/QoSEraser) | 1 |
| Mehrdad Sheikhjaberi, Dima Alhadidi | [Reducing Model Memorization to Mitigate Membership Inference Attacks](https://doi.org/10.1109/trustcom60117.2023.00033) | TrustCom | Other | [GitHub](https://github.com/Mehrdadsj/Reducing-Model-Memorization-to-Mitigate-Membership-Inference-Attacks) | 1 |
| Dmitrii Usynin, Moritz Knolle, G. Kaissis | [SoK: Memorisation in machine learning](https://doi.org/10.48550/arXiv.2311.03075) | arXiv | Other | — | 1 |
| Aditya Golatkar | [Unlearning and Privacy in Deep Neural Networks](https://www.semanticscholar.org/paper/51ff9fcf855568ec0c9e9a9265d12bec3e56375e) |  | Other | — | 0 |
| Thai-Hung Nguyen et al. | [An Empirical Study of Federated Unlearning: Efficiency and Effectiveness](https://www.semanticscholar.org/paper/6d6612fa08179826513c2f18998db2662c5d1945) | ACML | Federated | — | 0 |
| Hsuan-Cheng Lin, Shih-Hsuan Yang | [Using Shadow Models to Protect Private Data on Machine Unlearning](https://doi.org/10.1109/ICCE-Taiwan58799.2023.10226994) | ICCE-Taiwan | Other | — | 0 |
| Yuxin Wen et al. | [Canary in a Coalmine: Better Membership Inference with Ensembled Adversarial Queries](https://www.semanticscholar.org/paper/049e016d5241eb2eab9c7e015394aa7dc8bf2b40) | ICLR | Other | — | 0 |
| Fahao Chen, Peng Li, Shui Yu | [Efficient Giant Graph Unlearning via Push-Pull Tuning](https://doi.org/10.1109/ISPA-BDCloud-SocialCom-SustainCom59178.2023.00151) | IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom) | Graph | — | 0 |
| Adithyan M Nair et al. | [Selective Unlearning in Face Recognition: Forgetting Faces without Compromising Accuracy](https://doi.org/10.1109/ICIMIA60377.2023.10426386) | International Conference on Innovative Mechanisms for Industry Applications | Vision | — | 0 |
| Amr AbdelFatah Ahmed et al. | [Robust Concept Erasure via Kernelized Rate-Distortion Maximization](https://doi.org/10.52202/075280-1875) | NeurIPS | Diffusion | [GitHub](https://github.com/brcsomnath/KRaM) | 0 |
| Anwar Said et al. | [G RAPH U NLEARNING : A R EVIEW](https://www.semanticscholar.org/paper/a1862a376102751cef5bce3d3a4e3bca01706d16) | NeurIPS | Graph | — | 0 |
| Zekun Wang et al. | [DUTir at SemEval-2025 Task 4: Optimized Fine-Tuning of Linear Layers for Balanced Knowledge Forgetting and Retention](https://www.semanticscholar.org/paper/2dc8175896e29ff1814bd8e3f987790d31815430) | SemEval | LLM | — | 0 |
| Youyang Qu et al. | [Learn to Unlearn: A Survey on Machine Unlearning](https://doi.org/10.48550/arXiv.2305.07512) | arXiv | Other | [GitHub](https://github.com/thuwuyinjun/DeltaGrad) | 0 |
| Yegor Klochkov et al. | [Deep Concept Removal](https://doi.org/10.48550/arXiv.2310.05755) | arXiv | Vision | [GitHub](https://github.com/Tianxiaomo/pytorch-YOLOv4) | 0 |

## 2022

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Katherine Lee et al. | [Deduplicating Training Data Makes Language Models Better](https://doi.org/10.18653/v1/2022.acl-long.577) | ACL | LLM | [HF](https://huggingface.co/Markr-AI/COKAL-DPO-13b-v2) | 844 |
| Joel Jang et al. | [Knowledge Unlearning for Mitigating Privacy Risks in Language Models](https://doi.org/10.48550/arXiv.2210.01504) | ACL | LLM | [GitHub](https://github.com/joeljang/knowledge-unlearning) | 433 |
| Vikram S Chundawat et al. | [Can Bad Teaching Induce Forgetting? Unlearning in Deep Networks using an Incompetent Teacher](https://doi.org/10.48550/arXiv.2205.08096) | AAAI | Vision | — | 248 |
| Yi Liu et al. | [The Right to be Forgotten in Federated Learning: An Efficient Realization with Rapid Retraining](https://doi.org/10.1109/INFOCOM48880.2022.9796721) | IEEE Conference on Computer Communications | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 235 |
| Junxiao Wang et al. | [Federated Unlearning via Class-Discriminative Pruning](https://doi.org/10.1145/3485447.3512222) | WWW | Federated | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 217 |
| Borja Balle, Giovanni Cherubin, Jamie Hayes | [Reconstructing Training Data with Informed Adversaries](https://doi.org/10.1109/sp46214.2022.9833677) | IEEE S&P | Vision | [GitHub](https://github.com/kbarbora/database-reconstruction) | 215 |
| Yiwen Jiang et al. | [Machine unlearning survey](https://doi.org/10.1117/12.2660330) | MCTE | Other | [GitHub](https://github.com/jessecu2024/unlearningsurvey) | 213 |
| Min Chen et al. | [Graph Unlearning](https://doi.org/10.1145/3548606.3559352) | CCS | Graph | [GitHub](https://github.com/MinChen00/Graph-Unlearning) | 212 |
| Vikram S Chundawat et al. | [Zero-Shot Machine Unlearning](https://doi.org/10.1109/TIFS.2023.3265506) | IEEE T-IFS | Vision | [GitHub](https://github.com/ayu987/zero-shot-unlearning) | 202 |
| Anisa Halimi et al. | [Federated Unlearning: How to Efficiently Erase a Client in FL?](https://doi.org/10.48550/arXiv.2207.05521) | arXiv | Federated | [GitHub](https://github.com/IBM/federated-unlearning) | 201 |
| Haonan Yan et al. | [ARCANE: An Efficient Architecture for Exact Machine Unlearning](https://doi.org/10.24963/ijcai.2022/556) | IJCAI | Other | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 176 |
| Thomas Baumhauer, Pascal Schöttle, Matthias Zeppelzauer | [Machine unlearning: linear filtration for logit-based classifiers](https://doi.org/10.1007/s10994-022-06178-9) | Machine Learning | Other | [GitHub](https://github.com/th-b/linear_filtration) | 166 |
| Chen Wu, Sencun Zhu, P. Mitra | [Federated Unlearning with Knowledge Distillation](https://arxiv.org/abs/2201.09441) | arXiv | Federated | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 160 |
| Juhan Bae et al. | [If Influence Functions are the Answer, Then What is the Question?](https://doi.org/10.48550/arXiv.2209.05364) | NeurIPS | Other | [GitHub](https://github.com/ZaydH/influence_analysis_papers) | 157 |
| Nicholas Carlini et al. | [The Privacy Onion Effect: Memorization is Relative](https://doi.org/10.48550/arXiv.2206.10469) | NeurIPS | Other | [GitHub](https://github.com/RhincodonE/Privacy-Onion-effect) | 154 |
| Chong Chen et al. | [Recommendation Unlearning](https://doi.org/10.1145/3485447.3511997) | WWW | Recsys | [GitHub](https://github.com/chenchongthu/Recommendation-Unlearning) | 146 |
| Matthew Jagielski et al. | [Measuring Forgetting of Memorized Training Examples](https://doi.org/10.48550/arXiv.2207.00099) | ICLR | Other | [GitHub](https://github.com/safr-ai-lab/survey-llm) | 142 |
| B. Liu, Qian Liu, P. Stone | [Continual Learning and Private Unlearning](https://doi.org/10.48550/arXiv.2203.12817) | CoLLAs | Other | [GitHub](https://github.com/cranial-xix/continual-learning-private-unlearning) | 131 |
| Ronak Mehta et al. | [Deep Unlearning via Randomized Conditionally Independent Hessians](https://doi.org/10.1109/cvpr52688.2022.01017) | CVPR | Vision | [GitHub](https://github.com/vsingh-group/LCODEC-deep-unlearning) | 121 |
| Leijie Wu et al. | [Federated Unlearning: Guarantee the Right of Clients to Forget](https://doi.org/10.1109/mnet.001.2200198) | IEEE Network | Federated | — | 116 |
| Yang Liu et al. | [Backdoor Defense with Machine Unlearning](https://doi.org/10.1109/infocom48880.2022.9796974) | IEEE INFOCOM - IEEE Conference on Computer Communications | Vision | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 113 |
| Ga Wu, Masoud Hashemi, Christopher Srinivasa | [PUMA: Performance Unchanged Model Augmentation for Training Data Removal](https://doi.org/10.1609/aaai.v36i8.20846) | AAAI | Other | — | 96 |
| Neil G. Marchant, Benjamin I. P. Rubinstein, Scott Alfeld | [Hard to Forget: Poisoning Attacks on Certified Machine Unlearning](https://doi.org/10.1609/aaai.v36i7.20736) | AAAI | Other | [GitHub](https://github.com/ngmarchant/attack-unlearning) | 95 |
| Shashwat Goel et al. | [Towards Adversarial Evaluations for Inexact Machine Unlearning](https://arxiv.org/abs/2201.06640) | arXiv | Other | [GitHub](https://github.com/shash42/Evaluating-Inexact-Unlearning) | 94 |
| Xiangshan Gao et al. | [VeriFi: Towards Verifiable Federated Unlearning](https://doi.org/10.1109/TDSC.2024.3382321) | IEEE TDSC | Federated | — | 79 |
| Rishav Chourasia, Neil Shah, R. Shokri | [Forget Unlearning: Towards True Data-Deletion in Machine Learning](https://doi.org/10.48550/arXiv.2210.08911) | ICML | Other | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 73 |
| Fatemehsadat Mireshghallah et al. | [Quantifying Privacy Risks of Masked Language Models Using Membership Inference Attacks](https://doi.org/10.18653/v1/2022.emnlp-main.570) | EMNLP | LLM | — | 72 |
| Yuyuan Li et al. | [Making Recommender Systems Forget: Learning and Unlearning for Erasable Recommendation](https://doi.org/10.48550/arXiv.2203.11491) | Knowledge-Based Systems | Recsys | — | 72 |
| Jimmy Z. Di et al. | [Hidden Poison: Machine Unlearning Enables Camouflaged Poisoning Attacks](https://doi.org/10.48550/arXiv.2212.10717) | NeurIPS | Vision | [GitHub](https://github.com/Jimmy-di/camouflage-poisoning) | 67 |
| Junyaup Kim, Simon S. Woo | [Efficient Two-stage Model Retraining for Machine Unlearning](https://doi.org/10.1109/cvprw56347.2022.00482) | CVPR | Vision | [GitHub](https://github.com/DASH-Lab/ML_privacy_research) | 58 |
| Eli Chien, Chao Pan, O. Milenkovic | [Certified Graph Unlearning](https://doi.org/10.48550/arXiv.2206.09140) | arXiv | Graph | [GitHub](https://github.com/mims-harvard/GNNDelete) | 57 |
| Jingwen Ye et al. | [Learning with Recoverable Forgetting](https://doi.org/10.48550/arXiv.2207.08224) | ECCV | Vision | [GitHub](https://github.com/JngwenYe/LIRF) | 53 |
| Zijie Zhang et al. | [Prompt Certified Machine Unlearning with Randomized Gradient Smoothing and Quantization](https://doi.org/10.52202/068431-0977) | NeurIPS | Other | — | 52 |
| David Sommer et al. | [Athena: Probabilistic Verification of Machine Unlearning](https://doi.org/10.56553/popets-2022-0072) | PoPETs | Other | [GitHub](https://github.com/inspire-group/unlearning-verification) | 52 |
| Alexander Becker, T. Liebig | [Evaluating Machine Unlearning via Epistemic Uncertainty](https://doi.org/10.48550/arXiv.2208.10836) | arXiv | Other | [GitHub](https://github.com/ROYALBEFF/evaluating_machine_unlearning_via_epistemic_uncertainty) | 52 |
| A. Tarun et al. | [Deep Regression Unlearning](https://doi.org/10.48550/arXiv.2210.08196) | ICML | Other | [GitHub](https://github.com/ayu987/deep-regression-unlearning) | 51 |
| Vinith M. Suriyakumar, Ashia C. Wilson | [Algorithms that Approximate Data Removal: New Results and Limitations](https://doi.org/10.48550/arXiv.2209.12269) | NeurIPS | Other | [GitHub](https://github.com/VMS-6511/online-data-deletion) | 50 |
| Quoc Phong Nguyen et al. | [Markov Chain Monte Carlo-Based Machine Unlearning](https://doi.org/10.1145/3488932.3517406) | CCS | Other | [GitHub](https://github.com/egstatsml/arxivsearch) | 46 |
| Vinayshekhar Bannihatti Kumar, Rashmi Gangadharaiah, Dan Roth | [Privacy Adhering Machine Un-learning in NLP](https://doi.org/10.48550/arXiv.2212.09573) | International Joint Conference on Natural Language Processing | LLM | [GitHub](https://github.com/awslabs/privacy-adhering-machine-unlearning-nlp) | 46 |
| Chao Pan et al. | [Machine Unlearning of Federated Clusters](https://doi.org/10.48550/arXiv.2210.16424) | ICLR | Federated | [GitHub](https://github.com/thupchnsky/mufc) | 43 |
| Thorsten Eisenhofer et al. | [Verifiable and Provably Secure Machine Unlearning](https://doi.org/10.1109/SaTML64287.2025.00033) | SaTML | Other | [GitHub](https://github.com/cleverhans-lab/verifiable-unlearning) | 43 |
| Zayd Hammoudeh, Daniel Lowd | [Identifying a Training-Set Attack's Target Using Renormalized Influence Estimation](https://doi.org/10.1145/3548606.3559335) | CCS | Other | [GitHub](https://github.com/ZaydH/target_identification) | 42 |
| Hongsheng Hu et al. | [Membership Inference via Backdooring](https://doi.org/10.24963/ijcai.2022/532) | IJCAI | Other | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 41 |
| Ryutaro Tanno et al. | [Repairing Neural Networks by Leaving the Right Past Behind](https://doi.org/10.48550/arXiv.2207.04806) | NeurIPS | Other | [GitHub](https://github.com/tejasr20/CS772-project) | 40 |
| Shaopeng Fu, Fengxiang He, Dacheng Tao | [Knowledge Removal in Sampling-based Bayesian Inference](https://doi.org/10.48550/arXiv.2203.12964) | ICLR | Other | [GitHub](https://github.com/fshp971/mcmc-unlearning) | 37 |
| Peng-Fei Zhang et al. | [Machine Unlearning for Image Retrieval](https://doi.org/10.1145/3503161.3548378) | ACM MM | Vision | [GitHub](https://github.com/sduzpf/Machine-Unlearning-for-Image-Retrieval-A-Generative-Scrubbing-Approach) | 32 |
| Zhaobo Lu et al. | [Label‐only membership inference attacks on machine unlearning without dependence of posteriors](https://doi.org/10.1002/int.23000) | International Journal of Intelligent Systems | Other | — | 30 |
| Yann Fraboni et al. | [SIFU: Sequential Informed Federated Unlearning for Efficient and Provable Client Unlearning in Federated Optimization](https://arxiv.org/abs/2211.11656) | AISTATS | Federated | — | 29 |
| Ji Gao et al. | [Deletion inference, reconstruction, and compliance in machine (un)learning](https://doi.org/10.56553/popets-2022-0079) | PoPETs | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 29 |
| Tao Guo et al. | [Efficient Attribute Unlearning: Towards Selective Removal of Input Attributes from Feature Representations](https://arxiv.org/abs/2202.13295) | ACM Trans. Inf. Syst | Vision | — | 27 |
| Jiasi Weng et al. | [Proof of Unlearning: Definitions and Instantiation](https://doi.org/10.1109/TIFS.2024.3358993) | IEEE T-IFS | Other | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 27 |
| Honorius Gâlmeanu, Răzvan Andonie | [Weighted Incremental–Decremental Support Vector Machines for concept drift with shifting window](https://doi.org/10.1016/j.neunet.2022.05.018) | Neural Networks | Other | — | 25 |
| Haiyan Chen et al. | [Incremental learning for transductive support vector machine](https://doi.org/10.1016/j.patcog.2022.108982) | Pattern Recognition | Other | — | 25 |
| Youngsik Yoon et al. | [Few-Shot Unlearning by Model Inversion](https://doi.org/10.48550/arXiv.2205.15567) | arXiv | Vision | — | 25 |
| Jiamin Fan et al. | [Fast Model Update for IoT Traffic Anomaly Detection With Machine Unlearning](https://doi.org/10.1109/jiot.2022.3214840) | IEEE IoT-J | Other | — | 21 |
| Yann Fraboni et al. | [Sequential Informed Federated Unlearning: Efficient and Provable Client Unlearning in Federated Optimization](https://doi.org/10.48550/arXiv.2211.11656) | arXiv | Federated | — | 21 |
| Salvatore Mercuri et al. | [An Introduction to Machine Unlearning](https://doi.org/10.48550/arXiv.2209.00939) | arXiv | Other | [GitHub](https://github.com/susiesyli/Machine-Unlearning-Papers) | 20 |
| Shashwat Goel, Ameya Prabhu, P. Kumaraguru | [Evaluating Inexact Unlearning Requires Revisiting Forgetting](https://www.semanticscholar.org/paper/d98484eac2c42e54585a3b09c7ed85c920548120) | arXiv | Other | — | 20 |
| Zhifeng Kong, Kamalika Chaudhuri | [Data Redaction from Pre-trained GANs](https://doi.org/10.1109/SaTML54575.2023.00048) | SaTML | Diffusion | [GitHub](https://github.com/sbaresearch/GenAI-IP-protection) | 19 |
| Jinu Gong, Osvaldo Simeone, Joonhyuk Kang | [Compressed Particle-Based Federated Bayesian Learning and Unlearning](https://doi.org/10.1109/lcomm.2022.3223655) | IEEE Communications Letters | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 18 |
| Ananth Mahadevan, Michael Mathioudakis | [Certifiable Unlearning Pipelines for Logistic Regression: An Experimental Study](https://doi.org/10.3390/make4030028) | Machine Learning and Knowledge Extraction | Other | — | 18 |
| Weijun Qian et al. | [Patient Similarity Learning with Selective Forgetting](https://doi.org/10.1109/bibm55620.2022.9995016) | BIBM | Other | — | 12 |
| Zihao Cao et al. | [Machine Unlearning Method Based On Projection Residual](https://doi.org/10.1109/dsaa54385.2022.10032413) | DSAA | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 12 |
| Sihao Yu et al. | [LegoNet: A Fast and Exact Unlearning Architecture](https://doi.org/10.48550/arXiv.2210.16023) | arXiv | Vision | — | 11 |
| Wenyan Liu et al. | [Forgetting Fast in Recommender Systems](https://doi.org/10.48550/arXiv.2208.06875) | arXiv | Recsys | [GitHub](https://github.com/chenchongthu/ENMF) | 11 |
| Zhifeng Kong, Scott Alfeld | [Approximate Data Deletion in Generative Models](https://doi.org/10.48550/arXiv.2206.14439) | European Conference on Artificial Intelligence | Other | [GitHub](https://github.com/aaron-xichen/pytorch-playground) | 8 |
| Zhengming Zhang et al. | [Poison Neural Network-Based mmWave Beam Selection and Detoxification With Machine Unlearning](https://doi.org/10.1109/tcomm.2022.3232794) | IEEE Transactions on Communications | Other | — | 8 |
| Ben Wang, Sebastian Schelter | [Efficiently Maintaining Next Basket Recommendations under Additions and Deletions of Baskets and Items](https://arxiv.org/abs/2201.13313) | arXiv | Recsys | [GitHub](https://github.com/0xeeff/amnesiac_recsys) | 8 |
| Vikas Raunak, Arul Menezes | [Finding Memo: Extractive Memorization in Constrained Sequence Generation Tasks](https://doi.org/10.18653/v1/2022.findings-emnlp.378) | EMNLP | LLM | [GitHub](https://github.com/vyraun/Finding-Memo) | 7 |
| Zhou Zhai, Heng Huang, Bin Gu | [Kernel Path for Semisupervised Support Vector Machine](https://doi.org/10.1109/tnnls.2022.3183825) | IEEE TNNLS | Other | — | 7 |
| Xianjia Meng et al. | [Active forgetting via influence estimation for neural networks](https://doi.org/10.1002/int.22981) | International Journal of Intelligent Systems | Other | — | 7 |
| Zhifeng Kong, Amrita Roy Chowdhury, Kamalika Chaudhuri | [Forgeability and Membership Inference Attacks](https://doi.org/10.1145/3560830.3563731) | AISec@CCS | Other | — | 6 |
| Zhiwen Zhou et al. | [Dynamically Selected Mixup Machine Unlearning](https://doi.org/10.1109/TrustCom56396.2022.00077) | TrustCom | Other | — | 6 |
| Ambrish Rawat et al. | [Challenges and Pitfalls of Bayesian Unlearning](https://doi.org/10.48550/arXiv.2207.03227) | arXiv | Other | — | 6 |
| Wenrao Pang, Gang Wu | [Fast algorithms for incremental and decremental semi-supervised discriminant analysis](https://doi.org/10.1016/j.patcog.2022.108888) | Pattern Recognition | Other | — | 5 |
| Chao Pan, Eli Chien, O. Milenkovic | [Unlearning Nonlinear Graph Classifiers in the Limited Training Data Regime](https://doi.org/10.48550/arXiv.2211.03216) | arXiv | Graph | [GitHub](https://github.com/thupchnsky/sgc_unlearn) | 5 |
| Shauli Ravfogel et al. | [Adversarial Concept Erasure in Kernel Space](https://doi.org/10.18653/v1/2022.emnlp-main.405) | EMNLP | LLM | — | 4 |
| Ruolin Su, Xiao Liu, S. Tsaftaris | [Why patient data cannot be easily forgotten?](https://doi.org/10.48550/arXiv.2206.14541) | MICCAI | Vision | — | 4 |
| Joshua Stock et al. | [Property Unlearning: A Defense Strategy Against Property Inference Attacks](https://doi.org/10.48550/arXiv.2205.08821) | arXiv | Other | — | 4 |
| Pravendra Singh, Pratik Mazumder, Mohammed Asad Karim | [Attaining Class-level Forgetting in Pretrained Model using Few Samples](https://doi.org/10.48550/arXiv.2210.10670) | ECCV | Vision | — | 3 |
| Alexander Becker, T. Liebig | [Certified Data Removal in Sum-Product Networks](https://doi.org/10.1109/ICKG55886.2022.00010) | ICKG | Other | [GitHub](https://github.com/ROYALBEFF/UnlearnSPN) | 3 |
| Diyang Li, Bin Gu | [Chunk Dynamic Updating for Group Lasso with ODEs](https://doi.org/10.1609/aaai.v36i7.20704) | AAAI | Other | — | 2 |
| Shimon Malnick, S. Avidan, Ohad Fried | [Taming Normalizing Flows](https://doi.org/10.1109/WACV57701.2024.00458) | WACV | Other | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 2 |
| Zhifeng Kong, Kamalika Chaudhuri | [Forgetting Data from Pre-trained GANs](https://doi.org/10.48550/arXiv.2206.14389) | arXiv | Diffusion | — | 2 |
| J. Gong et al. | [Forget-SVGD: Particle-Based Bayesian Federated Unlearning](https://doi.org/10.1109/dslw53931.2022.9820602) | DSLW | Federated | — | 1 |
| Narsimha Chilkuri, C. Eliasmith | [Debugging using Orthogonal Gradient Descent](https://doi.org/10.48550/arXiv.2206.08489) | arXiv | Vision | — | 1 |
| Tao Guo et al. | [Vertical Machine Unlearning: Selectively Removing Sensitive Information From Latent Feature Space](https://www.semanticscholar.org/paper/2956ec6b50a930cf59d78728f589dfaa8eed2399) | arXiv | Other | — | 1 |
| J. Hartley, S. Tsaftaris | [Unintended memorisation of unique features in neural networks](https://doi.org/10.48550/arXiv.2205.10079) | arXiv | Other | [GitHub](https://github.com/jasminium/feature-memorisation) | 1 |

## 2021

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Nicholas Carlini et al. | [Membership Inference Attacks From First Principles](https://doi.org/10.1109/sp46214.2022.9833649) | IEEE S&P | Other | [GitHub](https://github.com/orientino/lira-pytorch) | 1052 |
| Hongsheng Hu et al. | [Membership Inference Attacks on Machine Learning: A Survey](https://doi.org/10.1145/3523273) | ACM Computing Surveys | Other | [GitHub](https://github.com/HongshengHu/membership-inference-machine-learning-literature) | 663 |
| Damai Dai et al. | [Knowledge Neurons in Pretrained Transformers](https://doi.org/10.18653/v1/2022.acl-long.581) | ACL | LLM | [GitHub](https://github.com/ZJU-LLMs/Foundations-of-LLMs) | 651 |
| Ayush Sekhari et al. | [Remember What You Want to Forget: Algorithms for Machine Unlearning](https://arxiv.org/abs/2103.03279) | NeurIPS | Other | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 444 |
| Min Chen et al. | [When Machine Unlearning Jeopardizes Privacy](https://doi.org/10.1145/3460120.3484756) | CCS | Other | [GitHub](https://github.com/MinChen00/UnlearningLeaks) | 314 |
| Anvith Thudi et al. | [Unrolling SGD: Understanding Factors Influencing Machine Unlearning](https://doi.org/10.1109/EuroSP53844.2022.00027) | European Symposium on Security and Privacy | Other | [GitHub](https://github.com/OngWinKent/MachineUnlearning) | 312 |
| A. Tarun et al. | [Fast Yet Effective Machine Unlearning](https://doi.org/10.1109/TNNLS.2023.3266233) | IEEE TNNLS | Vision | [GitHub](https://github.com/vikram2000b/Fast-Machine-Unlearning) | 301 |
| Alexander Warnecke et al. | [Machine Unlearning of Features and Labels](https://doi.org/10.14722/ndss.2023.23087) | NDSS | Other | [GitHub](https://github.com/alewarne/MachineUnlearning) | 300 |
| Gaoyang Liu et al. | [FedEraser: Enabling Efficient Client-Level Data Removal from Federated Learning Models](https://doi.org/10.1109/IWQOS52092.2021.9521274) | International Workshop on Quality of Service | Federated | — | 256 |
| Varun Gupta et al. | [Adaptive Machine Unlearning](https://arxiv.org/abs/2106.04378) | NeurIPS | Other | [GitHub](https://github.com/Simoni2412/Machine-Unlearning) | 236 |
| Anvith Thudi et al. | [On the Necessity of Auditable Algorithmic Definitions for Machine Unlearning](https://arxiv.org/abs/2110.11891) | USENIX Security | Other | [GitHub](https://github.com/cleverhans-lab/Forging) | 222 |
| Enayat Ullah et al. | [Machine Unlearning via Algorithmic Stability](https://arxiv.org/abs/2102.13179) | Annual Conference Computational Learning Theory | Other | — | 153 |
| Bo Hui et al. | [Practical Blind Membership Inference Attack via Differential Comparisons](https://doi.org/10.14722/ndss.2021.24293) | NDSS | Other | [GitHub](https://github.com/hyhmia/BlindMI) | 140 |
| Sebastian Schelter, Stefan Grafberger, Ted Dunning | [HedgeCut: Maintaining Randomised Trees for Low-Latency Machine Unlearning](https://doi.org/10.1145/3448016.3457239) | SIGMOD Conference | Other | [GitHub](https://github.com/schelterlabs/hedgecut) | 122 |
| Takashi Shibata et al. | [Learning with Selective Forgetting](https://doi.org/10.24963/ijcai.2021/137) | IJCAI | Vision | [GitHub](https://github.com/nttcslab/Learning-with-Selective-Forgetting) | 79 |
| Shawn Shan et al. | [Poison Forensics: Traceback of Data Poisoning Attacks in Neural Networks](https://arxiv.org/abs/2110.06904) | USENIX Security | Other | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 64 |
| Ananth Mahadevan, M. Mathioudakis | [Certifiable Machine Unlearning for Linear Models](https://arxiv.org/abs/2106.15093) | arXiv | Other | [GitHub](https://github.com/testc2/unlearning-experiments) | 57 |
| Sumit Mukherjee et al. | [privGAN: Protecting GANs from membership inference attacks at low cost to utility](https://doi.org/10.2478/popets-2021-0041) | PoPETs | Other | [GitHub](https://github.com/microsoft/privGAN) | 53 |
| Alexandra Peste, Dan Alistarh, Christoph H. Lampert | [SSSE: Efficiently Erasing Samples from Trained Machine Learning Models](https://arxiv.org/abs/2107.03860) | arXiv | Other | — | 40 |
| Yingzhe He et al. | [DeepObliviate: A Powerful Charm for Erasing Data Residual Memory in Deep Neural Networks](https://arxiv.org/abs/2105.06209) | arXiv | Other | — | 34 |
| M. E. Khan, S. Swaroop | [Knowledge-Adaptation Priors](https://arxiv.org/abs/2106.08769) | NeurIPS | Other | [GitHub](https://github.com/team-approx-bayes/kpriors) | 29 |
| Honorius Gâlmeanu, Răzvan Andonie | [Concept Drift Adaptation with Incremental–Decremental SVM](https://doi.org/10.3390/app11209644) | Applied Sciences | Other | — | 18 |
| Daniel Felps et al. | [Class Clown: Data Redaction in Machine Unlearning at Enterprise Scale](https://doi.org/10.5220/0010419600070014) | International Conference on Operations Research and Enterprise Systems | Vision | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 18 |
| Jinu Gong, Osvaldo Simeone, Joonhyuk Kang | [Bayesian Variational Federated Learning and Unlearning in Decentralized Networks](https://doi.org/10.1109/spawc51858.2021.9593225) | International Workshop on Signal Processing Advances in Wireless Communications | Federated | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 16 |
| Yangsibo Huang, Xiaoxiao Li, Kai Li | [EMA: Auditing Data Removal from Trained Models](https://doi.org/10.1007/978-3-030-87240-3_76) | MICCAI | Vision | [GitHub](https://github.com/Hazelsuko07/EMA) | 16 |
| Derui Zhu et al. | [DeepMemory: Model-based Memorization Analysis of Deep Neural Language Models](https://doi.org/10.1109/ase51524.2021.9678871) | ASE | LLM | — | 12 |
| Shaopeng Fu et al. | [Bayesian Inference Forgetting](https://arxiv.org/abs/2101.06417) | arXiv | Other | [GitHub](https://github.com/fshp971/BIF) | 12 |
| Kongyang Chen, Yiwen Wang, Yao Huang | [Lightweight machine unlearning in neural network](https://arxiv.org/abs/2111.05528) | arXiv | Other | — | 11 |
| Kongyang Chen, Yao Huang, Yiwen Wang | [Machine unlearning via GAN](https://arxiv.org/abs/2111.11869) | arXiv | Vision | — | 10 |
| Aman Tahiliani et al. | [Machine Unlearning: Its Need and Implementation Strategies](https://doi.org/10.1145/3474124.3474158) | International Conference on Contemporary Computing | Other | — | 9 |
| Sharu Theresa Jose, O. Simeone | [A Unified PAC-Bayesian Framework for Machine Unlearning via Information Risk Minimization](https://doi.org/10.1109/mlsp52302.2021.9596170) | International Workshop on Machine Learning for Signal Processing | Other | — | 9 |
| Lei Hu, Guoxing Yi, Huang Chao | [A sparse algorithm for adaptive pruning least square support vector regression machine based on global representative point ranking](https://doi.org/10.23919/jsee.2021.000014) | Journal of Systems Engineering and Electronics | Other | — | 9 |
| Zachary Izzo et al. | [Approximate Data Deletion from Machine Learning Models](https://openalex.org/W3158390351) | AISTATS | Other | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 8 |
| Adit Goyal, Vikas Hassija, V. Albuquerque | [Revisiting Machine Learning Training Process for Enhanced Data Privacy](https://doi.org/10.1145/3474124.3474208) | International Conference on Contemporary Computing | Vision | — | 3 |
| Nishchal Parne et al. | [An Investigation on Learning, Polluting, and Unlearning the Spam Emails for Lifelong Learning](https://arxiv.org/abs/2111.14609) | arXiv | Other | — | 3 |
| Geunseop Lee | [Fast and more accurate incremental-decremental principal component analysis algorithm for online learning of face recognition](https://doi.org/10.1117/1.jei.30.4.043012) | Journal of Electronic Imaging | Other | — | 2 |
| Tobias Dam, Maximilian Henzl, L. Klausner | [Delete My Account: Impact of Data Deletion on Machine Learning Classifiers](https://doi.org/10.1109/ICSSA53632.2021.00010) | International Conference on Software Security and Assurance | Other | — | 1 |
| Nishchal Parne et al. | [Machine Unlearning: Learning, Polluting, and Unlearning for Spam Email](https://www.semanticscholar.org/paper/d7cc0015257bba726fbad0dad210932ebb773ec6) | arXiv | Other | — | 1 |
| S. Simeone, Sharu Theresa Jose, Osvaldo Simeone | [University of Birmingham A unified PAC-Bayesian framework for machine unlearning via information risk minimization](https://www.semanticscholar.org/paper/7fd1c6fbb87c523c775d712dbb340c955b19714c) | MLSP | Other | — | 0 |

## 2020

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Laura Graves, Vineel Nagisetty, Vijay Ganesh | [Amnesiac Machine Learning](https://doi.org/10.1609/aaai.v35i13.17371) | AAAI | Vision | [GitHub](https://github.com/lmgraves/AmnesiacML) | 417 |
| Seth Neel, Aaron Roth, Saeed Sharifi-Malvajerdi | [Descent-to-Delete: Gradient-Based Methods for Machine Unlearning](https://arxiv.org/abs/2007.02923) | ALT | Other | [GitHub](https://github.com/safr-ai-lab/survey-llm) | 380 |
| Zachary Izzo et al. | [Approximate Data Deletion from Machine Learning Models: Algorithms and Evaluations](https://arxiv.org/abs/2002.10077) | AISTATS | Other | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 357 |
| Yinjun Wu, Edgar Dobriban, S. Davidson | [DeltaGrad: Rapid retraining of machine learning models](https://arxiv.org/abs/2006.14755) | ICML | Other | [GitHub](https://github.com/wuyinjun-1993/DeltaGrad) | 263 |
| Aditya Golatkar, A. Achille, Stefano Soatto | [Forgetting Outside the Box: Scrubbing Deep Networks of Information Accessible from Input-Output Observations](https://doi.org/10.1007/978-3-030-58526-6_23) | ECCV | Vision | — | 245 |
| Jonathan Brophy, Daniel Lowd | [Machine Unlearning for Random Forests](https://doi.org/10.48550/arxiv.2009.05567) | ICML | Other | [GitHub](https://github.com/jjbrophy47/dare_rf) | 222 |
| Aditya Golatkar et al. | [Mixed-Privacy Forgetting in Deep Networks](https://doi.org/10.1109/CVPR46437.2021.00085) | CVPR | Vision | [GitHub](https://github.com/52CV/CVPR-2021-Papers) | 220 |
| Quoc Phong Nguyen, Bryan Kian Hsiang Low, Patrick Jaillet | [Variational Bayesian Unlearning](https://arxiv.org/abs/2010.12883) | NeurIPS | Other | [GitHub](https://github.com/Mahanth-Maha/Unlearn) | 177 |
| Gavin Brown et al. | [When is memorization of irrelevant training data necessary for high-accuracy learning?](https://doi.org/10.1145/3406325.3451131) | Symposium on the Theory of Computing | Other | [GitHub](https://github.com/gavinrbrown1/training-data-memorization) | 126 |
| Yang Liu et al. | [Learn to Forget: Machine Unlearning via Neuron Masking](https://doi.org/10.1109/TDSC.2022.3194884) | IEEE TDSC | Vision | [GitHub](https://github.com/hendrycks/error-detection/tree) | 89 |
| D. Sommer et al. | [Towards Probabilistic Verification of Machine Unlearning](https://arxiv.org/abs/2003.04247) | arXiv | Other | [GitHub](https://github.com/TouchSky-Lab/Awesome-Memorization-Elimination) | 83 |
| Gaoyang Liu et al. | [Federated Unlearning](https://arxiv.org/abs/2012.13891) | arXiv | Federated | — | 79 |
| Rasha Kashef | [A boosted SVM classifier trained by incremental learning and decremental unlearning approach](https://doi.org/10.1016/j.eswa.2020.114154) | Expert Systems with Applications | Other | — | 72 |
| Nasser Aldaghri, Hessam Mahdavifar, Ahmad Beirami | [Coded Machine Unlearning](https://doi.org/10.1109/ACCESS.2021.3090019) | IEEE Access | Other | — | 48 |
| Yinjun Wu, V. Tannen, S. Davidson | [PrIU: A Provenance-Based Approach for Incrementally Updating Regression Models](https://doi.org/10.1145/3318464.3380571) | SIGMOD Conference | Other | — | 44 |
| Sebastian Schelter | ["Amnesia" - Machine Learning Models That Can Forget User Data Very Fast](https://www.semanticscholar.org/paper/4e99e7af4b9f08b0a89577cd8ea92a37d4744e1e) | Conference on Innovative Data Systems Research | Other | — | 29 |
| Xiao Liu, S. Tsaftaris | [Have you forgotten? A method to assess if machine learning models have forgotten data](https://doi.org/10.1007/978-3-030-59710-8_10) | MICCAI | Vision | — | 29 |
| Yuantong Li, ChiHua Wang, Guang Cheng | [Online Forgetting Process for Linear Regression Models](https://arxiv.org/abs/2012.01668) | AISTATS | Other | — | 28 |
| Alexandre Reeberg de Mello, Marcelo Ricardo Stemmer, Alessandro L. Koerich | [Incremental and decremental fuzzy bounded twin support vector machine](https://doi.org/10.1016/j.ins.2020.03.038) | Information Sciences | Other | [GitHub](https://github.com/kritchie/LIBiFBTSVM) | 27 |
| Tomohiro Hayase, S. Yasutomi, Takashi Katoh | [Selective Forgetting of Deep Networks at a Finer Level than Samples](https://arxiv.org/abs/2012.11849) | arXiv | Vision | — | 17 |
| Jonathan Brophy | [Exit Through the Training Data: A Look into Instance-Attribution Explanations and Efﬁcient Data Deletion in Machine Learning](https://www.semanticscholar.org/paper/86407c30ec00d742ae44f125e9833ba23323eb87) |  | Other | — | 8 |
| Jonathan Brophy, Daniel Lowd | [DART: Data Addition and Removal Trees](https://www.semanticscholar.org/paper/bae70f16348001cf164469701c2a493e682a6648) | arXiv | Other | — | 6 |
| S. Deepanjali, S. Dhivya, S. Catherine | [Efficient Machine Unlearning Using General Adversarial Network](https://doi.org/10.1007/978-981-15-5329-5_45) | Lecture Notes in Networks and Systems | Other | — | 3 |
| Da Yu et al. | [Membership Inference with Privately Augmented Data Endorses the Benign while Suppresses the Adversary](https://arxiv.org/abs/2007.10567) | arXiv | Other | [GitHub](https://github.com/dayu11/MI_with_DA) | 1 |

## 2019

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Bolun Wang et al. | [Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks](https://doi.org/10.1109/SP.2019.00031) | IEEE S&P | Vision | [GitHub](https://github.com/bolunwang/backdoor) | 1801 |
| Lucas Bourtoule et al. | [Machine Unlearning](https://doi.org/10.1109/SP40001.2021.00019) | IEEE S&P | Other | [GitHub](https://github.com/cleverhans-lab/machine-unlearning) | 1391 |
| Aditya Golatkar, A. Achille, Stefano Soatto | [Eternal Sunshine of the Spotless Net: Selective Forgetting in Deep Networks](https://doi.org/10.1109/cvpr42600.2020.00932) | CVPR | Vision | [GitHub](https://github.com/AdityaGolatkar/SelectiveForgetting) | 776 |
| Antonio A. Ginart et al. | [Making AI Forget You: Data Deletion in Machine Learning](https://arxiv.org/abs/1907.05012) | NeurIPS | Other | [GitHub](https://github.com/tginart/deletion-efficient-kmeans) | 673 |
| Chuan Guo et al. | [Certified Data Removal from Machine Learning Models](https://arxiv.org/abs/1911.03030) | ICML | Other | [GitHub](https://github.com/facebookresearch/certified-removal) | 634 |
| Stacey Truex et al. | [Demystifying Membership Inference Attacks in Machine Learning as a Service](https://doi.org/10.1109/TSC.2019.2897554) | IEEE TSC | Other | [GitHub](https://github.com/git-disl/membership_vulnerability) | 323 |
| Congzheng Song, Vitaly Shmatikov | [Auditing Data Provenance in Text-Generation Models](https://doi.org/10.1145/3292500.3330885) | KDD | LLM | [GitHub](https://github.com/csong27/auditing-text-generation) | 287 |
| Pang Wei Koh et al. | [On the Accuracy of Influence Functions for Measuring Group Effects](https://arxiv.org/abs/1905.13289) | NeurIPS | Other | [GitHub](https://github.com/kohpangwei/group-influence-release) | 237 |
| Yuantao Chen et al. | [A novel online incremental and decremental learning algorithm based on variable support vector machine](https://doi.org/10.1007/s10586-018-1772-4) | Cluster Computing | Other | — | 169 |
| Sebastian Schelter | [“Amnesia” – Towards Machine Learning Models That Can Forget User Data Very Fast](https://www.semanticscholar.org/paper/2e8528d78d6f273c72ad8e60b6d7de5c29dc2aef) | CIDR | Other | — | 29 |
| S. Shintre, Kevin A. Roundy, Jasjeet Dhaliwal | [Making Machine Learning Forget](https://doi.org/10.1007/978-3-030-21752-5_6) | Annual Privacy Forum | Other | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 19 |
| Shuyang Yu et al. | [Tackle Balancing Constraint for Incremental Semi-Supervised Support Vector Learning](https://doi.org/10.1145/3292500.3330962) | KDD | Other | — | 11 |
| Wei‐Han Lee et al. | [Exact Incremental and Decremental Learning for LS-SVM](https://doi.org/10.1109/icip.2019.8803291) | International Conference on Information Photonics | Other | — | 4 |
| Jeevan Sirkunan, Nasir Shaikh-Husin, Muhammad Nadzir Marsono | [Interleaved Incremental/Decremental Support Vector Machine for Embedded System](https://doi.org/10.1109/iscas.2019.8702745) | International Symposium on Circuits and Systems | Other | — | 0 |

## 2018

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Nicholas Carlini et al. | [The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks](https://arxiv.org/abs/1802.08232) | USENIX Security | LLM | [GitHub](https://github.com/OpenMined/private-ai-resources) | 1386 |
| Nicholas Carlini et al. | [The Secret Sharer: Measuring Unintended Neural Network Memorization & Extracting Secrets](https://www.semanticscholar.org/paper/f9313ada269360c9faa74385d966122e5a20e69a) | arXiv | LLM | — | 199 |
| Mariya Toneva et al. | [An Empirical Study of Example Forgetting during Deep Neural Network Learning](https://doi.org/10.48550/arxiv.1812.05159) | arXiv | Vision | [GitHub](https://github.com/mtoneva/example_forgetting) | 114 |
| Yinzhi Cao et al. | [Efficient Repair of Polluted Machine Learning Systems via Causal Unlearning](https://doi.org/10.1145/3196494.3196517) | CCS | Other | — | 53 |
| Seira Hidano et al. | [Model Inversion Attacks for Online Prediction Systems: Without Knowledge of Non-Sensitive Attributes](https://doi.org/10.1587/TRANSINF.2017ICP0013) | IEICE Trans. Inf. Syst | Other | — | 21 |
| S. Shintre, Jasjeet Dhaliwal | [Verifying that the influence of a user data point has been removed from a machine learning classifier](https://www.semanticscholar.org/paper/eae00a0a476038906bfedb23cb1cafbf0a728434) | Lecture Notes in Computer Science | Other | — | 7 |
| Zhe Liu et al. | [Online Incremental and Decremental SVDD Learning Based on CP](https://doi.org/10.12783/dtcse/cmsms2018/25235) | DEStech Transactions on Computer Science and Engineering | Other | — | 0 |

## 2017

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| B. Hitaj, G. Ateniese, F. Pérez-Cruz | [Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://doi.org/10.1145/3133956.3134012) | CCS | Federated | [GitHub](https://github.com/Jaskiee/GAN-Attack-against-Federated-Deep-Learning) | 1581 |
| Congzheng Song, Thomas Ristenpart, Vitaly Shmatikov | [Machine Learning Models that Remember Too Much](https://doi.org/10.1145/3133956.3134077) | CCS | Other | [GitHub](https://github.com/csong27/ml-model-remember) | 582 |
| Jamie Hayes et al. | [LOGAN: Membership Inference Attacks Against Generative Models](https://doi.org/10.2478/popets-2019-0008) | PoPETs | Other | [GitHub](https://github.com/manjunath5496/Machine-Learning-Privacy-Papers) | 582 |
| Apostolos Pyrgelis, C. Troncoso, Emiliano De Cristofaro | [Knock Knock, Who's There? Membership Inference on Aggregate Location Data](https://doi.org/10.14722/NDSS.2018.23183) | NDSS | Other | — | 293 |
| Bo Jin, Zhongliang Jing, Haitao Zhao | [Incremental and Decremental Extreme Learning Machine Based on Generalized Inverse](https://doi.org/10.1109/access.2017.2758645) | IEEE Access | Other | — | 16 |
| Yinzhi Cao | [Machine Unlearning: Repairing Learning Models in Adversarial Environments](https://doi.org/10.1201/9781315154374-7) | Big Data Analytics in Cybersecurity | Other | — | 1 |

## 2016

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| R. Shokri et al. | [Membership Inference Attacks Against Machine Learning Models](https://doi.org/10.1109/SP.2017.41) | IEEE S&P | Other | [GitHub](https://github.com/13o-bbr-bbq/machine_learning_security) | 5137 |
| Lei Zhu et al. | [Incremental and Decremental Max-Flow for Online Semi-Supervised Learning](https://doi.org/10.1109/tkde.2016.2550042) | IEEE TKDE | Other | — | 19 |
| Honorius Gâlmeanu, Lucian Mircea Sasu, Răzvan Andonie | [Incremental and Decremental SVM for Regression](https://doi.org/10.15837/ijccc.2016.6.2744) | International Journal of Computers Communications & Control | Other | — | 9 |

## 2015

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Yinzhi Cao, Junfeng Yang | [Towards Making Systems Forget with Machine Unlearning](https://doi.org/10.1109/SP.2015.35) | IEEE S&P | Other | [GitHub](https://github.com/TouchSky-Lab/Awesome-Memorization-Elimination) | 1035 |

## 2014

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Cheng-Hao Tsai, Chieh-Yen Lin, Chih-Jen Lin | [Incremental and decremental training for linear classification](https://doi.org/10.1145/2623330.2623661) | KDD | Other | — | 91 |
| Bin Gu, Guansheng Zheng, Jiandong Wang | [Analysis for Incremental and Decremental Standard Support Vector Machine](https://doi.org/10.3724/sp.j.1001.2013.04327) | Journal of Software | Other | — | 3 |
| Junfei Li, Baolei Zhang | [Online learning algorithm of direct support vector machine for regression based on Cholesky factorization](https://doi.org/10.1109/infoseee.2014.6946145) | International Conference on Information Science, Electronics and Electrical Engineering | Other | — | 2 |

## 2012

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Runpeng Gao, Ye San | [Improved adaptive pruning algorithm for least squares support vector regression](https://doi.org/10.1109/jsee.2012.00055) | Journal of Systems Engineering and Electronics | Other | — | 6 |
| Mu-Song Chen, Tze-Yee Ho, Deng-Yuan Huang | [Online transductive support vector machines for classification](https://doi.org/10.1109/isic.2012.6449755) | International Conference on Information Security and Intelligent Control | Other | — | 5 |
| Qing Li et al. | [Decremental learning based on sample-weighted Support Vector Regression](https://doi.org/10.1109/ccdc.2012.6244212) | Chinese Control and Decision Conference | Other | — | 1 |

## 2011

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| P-K. Wong, H-C Wong, Chi‐Man Vong | [Online time-sequence incremental and decremental least squares support vector machines for engine air-ratio prediction](https://doi.org/10.1177/1468087411420280) | International Journal of Engine Research | Other | — | 19 |
| Zhang Xian, Wang Hong-Li | [Selective forgetting extreme learning machine and its application to time series prediction](https://doi.org/10.7498/aps.60.080504) | Acta Physica Sinica | Other | — | 12 |
| Yi Zhu | [Robust Sparse Least Squares Support Vector Regression Machine Based on Decremental Learning](https://openalex.org/W2378959817) | Tance yu kongzhi xuebao | Other | — | 3 |
| Wei Zhang et al. | [Decremental multi-output least square SVR learning](https://doi.org/10.1109/csae.2011.5953299) | International Conference on Computer Science and Application Engineering | Other | — | 1 |

## 2010

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Shaoning Pang et al. | [Incremental and decremental LDA learning with applications](https://doi.org/10.1109/ijcnn.2010.5596727) | IJCNN | Other | — | 6 |
| Linda Corucci, Marco Cococcioni, Fabio Nardelli | [Building a time variant cost-oriented classifier using an ensemble of SVMs on a real case application](https://doi.org/10.1109/icsmc.2010.5642237) | IEEE International Conference on Systems, Man and Cybernetics | Other | — | 3 |
| Hao Zhi | [Robust Least Squares Support Vector Machine Regression Based on Hypothesis-Testing and Outlier-Elimination](https://openalex.org/W2368118765) |  | Other | — | 1 |

## 2009

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Masayuki Karasuyama, I. Takeuchi | [Multiple Incremental Decremental Learning of Support Vector Machines](https://doi.org/10.1109/TNN.2010.2048039) | IEEE Transactions on Neural Networks | Other | [GitHub](https://github.com/Mahanth-Maha/Unlearn) | 176 |
| Khaled Boukharouba, Laurent Bako, Stéphane Lecoeuche | [Incremental and Decremental Multi-category Classification by Support Vector Machines](https://doi.org/10.1109/icmla.2009.114) | ICML | Other | — | 16 |
| Zhuang Wang, Slobodan Vučetić | [Twin Vector Machines for Online Learning on a Budget](https://doi.org/10.1137/1.9781611972795.78) | SDM | Other | — | 15 |
| Zhuang Wang, Slobodan Vučetić | [Fast Online Training of Ramp Loss Support Vector Machines](https://doi.org/10.1109/icdm.2009.53) | Ninth IEEE International Conference on Data Mining | Other | — | 11 |
| Honorius Gâlmeanu, Răzvan Andonie | [A Multi-class Incremental and Decremental SVM Approach Using Adaptive Directed Acyclic Graphs](https://doi.org/10.1109/icais.2009.27) | International Conference on Adaptive and Intelligent Systems | Other | — | 6 |
| Xiangrong Zhang, Yifan Zhang, Licheng Jiao | [SAR target recognition based on improved sparse LSSVM](https://doi.org/10.1117/12.832466) | SPIE, the International Society for Optical Engineering/ SPIE | Other | — | 1 |

## 2008

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Honorius Gâlmeanu, Răzvan Andonie | [Incremental / decremental SVM for function approximation](https://doi.org/10.1109/optim.2008.4602473) | International Conference on Optimization of Electrical and Electronic Equipment | Other | — | 10 |
| Bogdan Raducanu, Jordi Vitrià | [FACE RECOGNITION BY ARTIFICIAL VISION SYSTEMS: A COGNITIVE PERSPECTIVE](https://doi.org/10.1142/s0218001408006545) | International Journal of Pattern Recognition and Artificial Intelligence | Other | — | 2 |

## 2007

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| E. Romero, Ignacio Barrio, L. B. Muñoz | [Incremental and Decremental Learning for Linear Support Vector Machines](https://doi.org/10.1007/978-3-540-74690-4_22) | ICANN | Other | — | 33 |
| H. Duan et al. | [Decremental Learning Algorithms for Nonlinear Langrangian and Least Squares Support Vector Machines](https://openalex.org/W114966885) | ICIC (2) | Other | — | 12 |
| Shouda Jiang, Lianlei Lin, Chao Sun | [A Fast Training Algorithm for Least Squares SVM](https://doi.org/10.1109/iih-msp.2007.18) | Intelligent Information Hiding and Multimedia Signal Processing | Other | — | 1 |
| A. Naskar et al. | [JU-CSE-NLP’25 at SemEval-2025 Task 4: Learning to Unlearn LLMs](https://www.semanticscholar.org/paper/1746a36f7b5419ba0ac9c4363e1ce8828861c935) | International Workshop on Semantic Evaluations - SemEval '07 | LLM | — | 0 |

## 2004

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Christopher Diehl, Gert Cauwenberghs | [Svm incremental learning, adaptation and optimization](https://doi.org/10.1109/ijcnn.2003.1223991) | IJCNN | Other | [GitHub](https://github.com/diehl/Incremental-SVM-Learning-in-MATLAB) | 280 |
| Hyunsoo Kim, Haesun Park | [Incremental and Decremental Least Squares Support Vector Machine and Its Application to Drug Design](https://openalex.org/W2143675528) | CSB | Other | — | 8 |
| Haesun Park, Hyunsoo Kim | [Machine learning and bioinformatics](https://openalex.org/W2266724186) | ACM on Conference on Information and Knowledge Management | Other | [GitHub](https://github.com/dataprofessor/dataprofessor) | 6 |

## 2003

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Amund Tveit, Magnus Lie Hetland, Håavard Engum | [Incremental and Decremental Proximal Support Vector Classification using Decay Coefficients](https://doi.org/10.1007/978-3-540-45228-7_42) | International Conference on Data Warehousing and Knowledge Discovery | Other | — | 27 |

## 2000

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| G. Cauwenberghs, T. Poggio | [Incremental and Decremental Support Vector Machine Learning](https://openalex.org/W2108807072) | NeurIPS | Other | [GitHub](https://github.com/mrgloom/Large-Scale-Linear-Classification) | 1418 |
| D.R. Wilson, Tony Martinez | [An Integrated Instance‐Based Learning Algorithm](https://doi.org/10.1111/0824-7935.00103) | Computational Intelligence | Other | — | 87 |
| G. Monari, G. Dreyfus | [Withdrawing an example from the training set: An analytic estimation of its effect on a non-linear parameterised model](https://doi.org/10.1016/S0925-2312(00)00325-8) | Neurocomputing | Other | — | 47 |

## 1997

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| D.R. Wilson | [Advances in instance-based learning algorithms](https://openalex.org/W2138525317) |  | Other | — | 22 |

## 1990

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| J. Leo van Hemmen et al. | [Increasing the efficiency of a neural network through unlearning](https://doi.org/10.1016/0378-4371(90)90345-s) | Physica A Statistical Mechanics and its Applications | Other | — | 39 |

## Undated

| Authors | Title | Venue | Category | Code | Citations |
|---|---|---|---|---|---:|
| Yang Chen, Zheyan Luo, Zhiwen Tang | [YNU at SemEval-2025 Task 4: Synthetic Token Alternative Training for LLM Unlearning](https://www.semanticscholar.org/paper/ca7a477a4665e5eba24a021e24bb1e767bf55279) |  | LLM | — | 2 |
| Varshita Kolipaka et al. | [S ANITY C HECKS FOR E VALUATING G RAPH U NLEARNING](https://www.semanticscholar.org/paper/190d81153f41f84e45061d67d10e2df386f307c7) |  | Graph | — | 0 |
| Chi-Ming Kuan, Yifei Chen | [NEKO at SemEval-2025 Task 4: A Gradient Ascent Based Machine Unlearning Strategy](https://www.semanticscholar.org/paper/bef5c81b6acd580305ea7846d63d70a991ef3a1e) |  | LLM | — | 0 |
| Hoorieh Sabzevari et al. | [NLPART at SemEval-2025 Task 4: Forgetting is harder than Learning](https://www.semanticscholar.org/paper/035f0c64d8fdd3ad544eb23dc669bd5949e64e5b) |  | LLM | — | 0 |
| A. Balordi | [A Principled Framework for Parameter Estimation in Federated Unlearning](https://www.semanticscholar.org/paper/6f8f992638559787c91d2ea89433c0bbcbe99822) |  | Federated | — | 0 |
| Olivier Capp´e | [Methods and Algorithms for Approximate Machine Unlearning](https://www.semanticscholar.org/paper/7834ed0c597a2cfa83ac602ffe9c36f56cdd03ae) |  | Other | — | 0 |
| Hongyin Shi et al. | [Machine Unlearning Challenge](https://www.semanticscholar.org/paper/7e233b84f51a0356668273d42f6498ab191c4313) |  | Other | [GitHub](https://github.com/unlearning-challenge/starting-kit) | 0 |
| A. Pesudo, Pce | [ESC: Erasing Space Concept for Knowledge Deletion Supplementary Material](https://www.semanticscholar.org/paper/b5c5d40a3055ae8ed233ffbe781ec386fc8e1844) |  | LLM | — | 0 |
| Adam Ge, Aadya Goel | [Unlearning Mechanisms in Graph Models and Document Classification](https://www.semanticscholar.org/paper/b2f8df0d12d0575335e0b9201b907a0192f93e4a) |  | Other | — | 0 |
