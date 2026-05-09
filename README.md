# Machine Unlearning — Papers Catalog

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Papers](https://img.shields.io/badge/papers-2827-blue) ![Updated](https://img.shields.io/badge/updated-2026--05--06-brightgreen) [![Stars](https://img.shields.io/github/stars/crayon-go/machine-unlearning-papers?style=social)](https://github.com/crayon-go/machine-unlearning-papers/stargazers) ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=crayon-go.machine-unlearning-papers) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](https://github.com/crayon-go/machine-unlearning-papers/issues)

A continuously-updated reference catalog of **machine unlearning** research — the study of selectively removing the influence of specific training data, samples, classes, concepts, or knowledge from a trained model after the fact. The catalog spans algorithms (exact and approximate), evaluation benchmarks, attacks against unlearning, and applications across LLMs, diffusion models, graphs, federated learning, and recommender systems.

Unlike hand-curated lists, this catalog is **automatically assembled and refreshed** from primary academic indices (Semantic Scholar, OpenAlex, OpenReview, DBLP, Crossref, arXiv, Hugging Face Papers, GitHub Search). Each entry shows live citation counts and, where available, links to the official code repository — fields that are usually missing from existing machine-unlearning lists.

## Quick stats

- **2,827 papers** classified as machine-unlearning research. Spans **1942–2026**.
- **1,093 (38.7%)** have an official code repository link (GitHub / Hugging Face / GitLab).
- **1,253 (44.3%)** have a resolvable arXiv ID.
- Citation counts last refreshed: **2026-05-06** (KST).

## What's inside

Each year section below is a sortable table with five columns:

| Column | Notes |
|---|---|
| **Authors** | Up to three author names; longer lists abbreviated as `et al.` |
| **Title** | Linked to the canonical source (DOI > arXiv > OpenAlex > S2) |
| **Venue** | Normalized short label (e.g. `arXiv`, `NeurIPS`, `IEEE T-IFS`, `WWW`) |
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
- [2013](#2013)
- [2012](#2012)
- [2011](#2011)
- [2010](#2010)
- [2009](#2009)
- [2008](#2008)
- [2007](#2007)
- [2006](#2006)
- [2005](#2005)
- [2004](#2004)
- [2003](#2003)
- [2002](#2002)
- [2001](#2001)
- [2000](#2000)
- [1999](#1999)
- [1998](#1998)
- [1997](#1997)
- [1996](#1996)
- [1994](#1994)
- [1993](#1993)
- [1992](#1992)
- [1991](#1991)
- [1990](#1990)
- [1989](#1989)
- [1988](#1988)
- [1987](#1987)
- [1985](#1985)
- [1984](#1984)
- [1983](#1983)
- [1982](#1982)
- [1981](#1981)
- [1980](#1980)
- [1976](#1976)
- [1975](#1975)
- [1974](#1974)
- [1973](#1973)
- [1972](#1972)
- [1971](#1971)
- [1970](#1970)
- [1969](#1969)
- [1966](#1966)
- [1965](#1965)
- [1964](#1964)
- [1961](#1961)
- [1952](#1952)
- [1945](#1945)
- [1944](#1944)
- [1942](#1942)
- [Undated](#undated)

## 2026

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Naixin Zhai et al. | [Maximizing Local Entropy Where It Matters: Prefix-Aware Localized LLM Unlearning](https://doi.org/10.48550/arXiv.2601.03190) | arXiv | [GitHub](https://github.com/nxZhai/PALU) | 8 |
| Zhuo Huang et al. | [Is Gradient Ascent Really Necessary? Memorize to Forget for Machine Unlearning](https://doi.org/10.48550/arXiv.2602.06441) | arXiv | [GitHub](https://github.com/crayon-go/machine-unlearning-papers) | 4 |
| Qian Feng et al. | [FG-OrIU: Towards Better Forgetting via Feature-Gradient Orthogonality for Incremental Unlearning](https://doi.org/10.48550/arXiv.2601.13578) | arXiv | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 4 |
| Yiling Wang et al. | [SafeMo: Linguistically Grounded Unlearning for Trustworthy Text-to-Motion Generation](https://doi.org/10.48550/arXiv.2601.00590) | arXiv | [GitHub](https://github.com/AIGeeksGroup/SafeMo) | 4 |
| Fengpeng Li et al. | [AEGIS: Adversarial Target-Guided Retention-Data-Free Robust Concept Erasure from Diffusion Models](https://doi.org/10.48550/arXiv.2602.06771) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 3 |
| McKinney, Lev et al. | [Gauss-Newton Unlearning for the LLM Era](https://doi.org/10.48550/arXiv.2602.10568) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 3 |
| Renyang Liu et al. | [SafeRedir: Prompt Embedding Redirection for Robust Unlearning in Image Generation Models](https://doi.org/10.48550/arXiv.2601.08623) | arXiv | [GitHub](https://github.com/ryliu68/SafeRedir) | 3 |
| Anmol Goel, Alan Ritter, Iryna Gurevych | [Auditing Language Model Unlearning via Information Decomposition](https://doi.org/10.48550/arXiv.2601.15111) | ACL | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Alireza Dehghanpour Farashah et al. | [Multilingual Amnesia: On the Transferability of Unlearning in Multilingual LLMs](https://doi.org/10.48550/arXiv.2601.05641) | ACL | [GitHub](https://github.com/alirezafarashah/multilingual_unlearning) | 2 |
| Zhenhua Xu et al. | [ForgetMark: Stealthy Fingerprint Embedding via Targeted Unlearning in Language Models](https://doi.org/10.48550/arXiv.2601.08189) | ICASSP | [GitHub](https://github.com/Xuzhenhua55/ForgetMark) | 2 |
| Thanh Tu Nguyen et al. | [Toward Verifiable Federated Unlearning: Framework, Challenges, and the Road Ahead](https://doi.org/10.1109/mic.2026.3656638) | IEEE Internet Computing | — | 2 |
| Yang Zhao, D. Niyato | [Exploring Federated Unlearning: Analysis, Comparison, and Insights](https://www.semanticscholar.org/paper/7f7d11a14ed0c66056d3655ee194f70cbe620c75) | IEEE Network | — | 2 |
| Yilei Wang et al. | [Cer-FeaUn: Certified Feature Unlearning in Vertical Federated Learning](https://doi.org/10.1109/TMC.2025.3594851) | IEEE TMC | [GitHub](https://github.com/lzbuuu/Cer-FeaUn) | 2 |
| Weiqi Wang et al. | [BlindU: Blind Machine Unlearning Without Revealing Erasing Data](https://doi.org/10.1109/TPAMI.2026.3654093) | IEEE TPAMI | [GitHub](https://github.com/wwq5-code/BlindU) | 2 |
| Junfeng Liao et al. | [Explainable LLM Unlearning Through Reasoning](https://arxiv.org/abs/2603.09980) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Iyad Ait Hou et al. | [Parameter-Efficient Token Embedding Editing for Clinical Class-Level Unlearning](https://arxiv.org/abs/2603.19302) | arXiv | — | 2 |
| Jiali Cheng et al. | [Toward Understanding Unlearning Difficulty: A Mechanistic Perspective and Circuit-Guided Difficulty Metric](https://doi.org/10.48550/arXiv.2601.09624) | arXiv | — | 2 |
| Jingpu Cheng et al. | [Machine Unlearning under Retain-Forget Entanglement](https://arxiv.org/abs/2603.26569) | arXiv | [GitHub](https://github.com/Jingpu-Cheng/unlearning-entanglement) | 2 |
| Xunlei Chen et al. | [ALTER: Asymmetric LoRA for Token-Entropy-Guided Unlearning of LLMs](https://doi.org/10.1609/aaai.v40i42.40845) | AAAI | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Lulu Xue et al. | [Dual-View Inference Attack: Machine Unlearning Amplifies Privacy Exposure](https://doi.org/10.1609/aaai.v40i14.38134) | AAAI | — | 1 |
| Ayush K. Varshney, Vicenç Torra | [Realistic image-to-image machine unlearning via decoupling and knowledge retention](https://doi.org/10.1016/j.bdr.2026.100592) | Big Data Research | — | 1 |
| Cristian Cosentino et al. | [Machine Unlearning: A Perspective, Taxonomy, and Benchmark Evaluation](https://doi.org/10.3390/fi18030174) | Future Internet | — | 1 |
| Myungjin Lee, Eunji Shin, Jiyoung Lee | [Erasing Your Voice Before It's Heard: Training-free Speaker Unlearning for Zero-shot Text-to-Speech](https://doi.org/10.48550/arXiv.2601.20481) | ICASSP | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 1 |
| Hyejun Jeong, Shiqing Ma, Amir Houmansadr | [A Survey on Federated Unlearning: Challenges and Opportunities](https://doi.org/10.1109/tbdata.2026.3668538) | IEEE TBD | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 1 |
| Laiqiao Qin et al. | [Machine Unlearning on Pre-trained Models by Residual Feature Alignment Using LoRA](https://doi.org/10.1109/tdsc.2026.3658545) | IEEE TDSC | — | 1 |
| Xuhan Zuo et al. | [Federated TrustChain: Blockchain-Enhanced LLM Training and Unlearning](https://doi.org/10.1109/tdsc.2026.3665277) | IEEE TDSC | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Weidong Zheng et al. | [Accurate and fast machine unlearning with hessian-guided overfitting approximation](https://doi.org/10.1016/j.neucom.2026.133369) | Neurocomputing | — | 1 |
| Mohammad Partohaghighi et al. | [Statistical Roughness-Informed Machine Unlearning](https://doi.org/10.48550/arXiv.2602.09304) | arXiv | — | 1 |
| Yuze Cai et al. | [Prototype-Guided Concept Erasure in Diffusion Models](https://arxiv.org/abs/2603.08271) | arXiv | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 1 |
| Chi Zhang et al. | [Closed-Form Concept Erasure via Double Projections](https://arxiv.org/abs/2604.10032) | arXiv | — | 1 |
| Kaiyuan Deng et al. | [Forget-It-All: Multi-Concept Machine Unlearning via Concept-Aware Neuron Masking](https://doi.org/10.48550/arXiv.2601.06163) | arXiv | [GitHub](https://github.com/kaiyuan02415/Forget-It-All) | 1 |
| Raj Sanjay Shah et al. | [The Unlearning Mirage: A Dynamic Framework for Evaluating LLM Unlearning](https://arxiv.org/abs/2603.11266) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Zeguan Xiao et al. | [Modeling LLM Unlearning as an Asymmetric Two-Task Learning Problem](https://arxiv.org/abs/2604.14808) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Xiaoyu Xu et al. | [From Domains to Instances: Dual-Granularity Data Synthesis for LLM Unlearning](https://doi.org/10.48550/arXiv.2601.04278) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Yangyang Guo et al. | [LLMs Can Unlearn Refusal with Only 1,000 Benign Samples](https://doi.org/10.48550/arXiv.2601.19231) | arXiv | [GitHub](https://github.com/guoyang9/refusal-unlearning) | 1 |
| Wenxuan Li et al. | [From Anchors to Supervision: Memory-Graph Guided Corpus-Free Unlearning for Large Language Models](https://arxiv.org/abs/2604.13777) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Taoran Li, Varun Chandrasekaran, Zhiyuan Yu | [Layer-Targeted Multilingual Knowledge Erasure in Large Language Models](https://doi.org/10.48550/arXiv.2602.22562) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Renqiang Luo et al. | [FairGU: Fairness-aware Graph Unlearning in Social Networks](https://doi.org/10.1145/3774904.3793004) | arXiv | [GitHub](https://github.com/LuoRenqiang/FairGU) | 1 |
| Parthaw Goswami, Md Khairul Islam, Ashfak Yeafi | [PrivEraserVerify: Efficient, Private, and Verifiable Federated Unlearning](https://arxiv.org/abs/2604.12348) | arXiv | — | 1 |
| Ravi Ranjan et al. | [RAZOR: Ratio-Aware Layer Editing for Targeted Unlearning in Vision Transformers and Diffusion Models](https://arxiv.org/abs/2603.14819) | arXiv | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 1 |
| Ravi Ranjan, Agoritsa Polyzou | [VLA-Forget: Vision-Language-Action Unlearning for Embodied Foundation Models](https://arxiv.org/abs/2604.03956) | arXiv | [GitHub](https://github.com/AriESQ/stars) | 1 |
| S. Laguna et al. | [Rethinking Machine Unlearning: Models Designed to Forget via Key Deletion](https://arxiv.org/abs/2603.15033) | arXiv | [HF](https://huggingface.co/google/vit-base-patch16-224) | 1 |
| Saleh Zare Zade et al. | [Attention Smoothing Is All You Need For Unlearning](https://doi.org/10.48550/arXiv.2603.01285) | arXiv | [GitHub](https://github.com/Salehzz/ASU-unlearning) | 1 |
| Weiqi Wang et al. | [EVE: Efficient Verification of Data Erasure through Customized Perturbation in Approximate Unlearning](https://doi.org/10.48550/arXiv.2602.03567) | arXiv | — | 1 |
| Hsiang Hsu et al. | [The Unseen Threat: Residual Knowledge in Machine Unlearning under Perturbed Samples](https://doi.org/10.48550/arXiv.2601.22359) | arXiv | [GitHub](https://github.com/AdityaGolatkar/SelectiveForgetting) | 1 |
| Syed Naveed Mahmood et al. | [Representation-Aware Unlearning via Activation Signatures: From Suppression to Knowledge-Signature Erasure](https://doi.org/10.48550/arXiv.2601.10566) | arXiv | [GitHub](https://github.com/kitkiti/kitkiti) | 1 |
| Jonas Mirlach, S. Laguna, Julia E. Vogt | [Reference-Guided Machine Unlearning](https://arxiv.org/abs/2603.11210) | arXiv | [GitHub](https://github.com/jmirlach/ReGUn) | 1 |
| Yi Sun et al. | [ActErase: A Training-Free Paradigm for Precise Concept Erasure via Activation Patching](https://doi.org/10.48550/arXiv.2601.00267) | arXiv | — | 1 |
| Ziyu Xie et al. | [A Survey on Federated Unlearning: Lifecycle, Taxonomy, and Insights](https://doi.org/10.36227/techrxiv.177004227.77961306/v1) |  | — | 0 |
| Ujjwal Pudasaini, Jun Huang, Zihao Ding | [Securing Smart Agriculture with Communication-Efficient Federated Unlearning](https://doi.org/10.36227/techrxiv.177223092.23251086/v1) |  | — | 0 |
| Abbas Yazdinejad, Ann Fitz-Gerald | [Does ‘federated unlearning’ in AI improve data privacy, or create a new cybersecurity risk?](https://doi.org/10.64628/aam.h9kyquhyf) |  | — | 0 |
| Anamika Paul Rupa, Anietie U Andy | [Probe-Geometry Alignment: Erasing the Cross-Sequence Memorization Signature Below Chance](https://arxiv.org/abs/2605.01699) |  | [GitHub](https://github.com/Rupawheatly/MLDU2) | 0 |
| J. Li, Yongqiang Chen, Ningning Ding | [CiPO: Counterfactual Unlearning for Large Reasoning Models through Iterative Preference Optimization](https://arxiv.org/abs/2604.15847) |  | — | 0 |
| Jiahang Tu et al. | [Mass Concept Erasure in Diffusion Models with Concept Hierarchy](https://doi.org/10.1609/aaai.v40i12.37920) | AAAI | — | 0 |
| Miaozeng Du et al. | [Forget What Has Seen: Selective Concept Unlearning in Segmentation Foundation Models](https://doi.org/10.1609/aaai.v40i25.39233) | AAAI | — | 0 |
| Haokun Chen et al. | [AUVIC: Adversarial Unlearning of Visual Concepts for Multi-modal Large Language Models](https://doi.org/10.1609/aaai.v40i36.40272) | AAAI | — | 0 |
| Weipeng Jiang et al. | [From Chaos to Clarity: A Knowledge Graph-Driven Audit Dataset Generation Framework for LLM Unlearning](https://doi.org/10.1609/aaai.v40i37.40397) | AAAI | — | 0 |
| Jingjing Zhou et al. | [STaR: Sensitive Trajectory Regulation for Unlearning in Large Reasoning Models](https://doi.org/10.1609/aaai.v40i41.40818) | AAAI | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yuming Ai et al. | [PAGE: A Unified Approach for Federated Graph Unlearning](https://doi.org/10.1609/aaai.v40i24.39038) | AAAI | [GitHub](https://github.com/striker2333/PAGE) | 0 |
| Zichong Wang, Tongliang Liu, Wenbin Zhang | [GUIC: Certified Graph Unlearning with Individual Fairness Guarantees](https://doi.org/10.1609/aaai.v40i42.40896) | AAAI | — | 0 |
| He Zhang et al. | [Imprint of the Forgotten: Stealthy Membership Inference in Unlearned Graph Neural Networks](https://doi.org/10.1609/aaai.v40i33.40047) | AAAI | — | 0 |
| Siyuan Wen et al. | [FedShard: Federated Unlearning with Efficiency Fairness and Performance Fairness](https://doi.org/10.1609/aaai.v40i32.39895) | AAAI | — | 0 |
| Xinyi Sheng et al. | [Retaliatory Attacks Against Federated Unlearning via Data Leakage](https://doi.org/10.1609/aaai.v40i30.39725) | AAAI | [GitHub](https://github.com/stcebra/Retaliatory-Attacks-Against-Federated-Unlearning) | 0 |
| Wenhan Wu et al. | [REMISVFU: Vertical Federated Unlearning via Representation Misdirection for Intermediate Output Feature](https://doi.org/10.1609/aaai.v40i32.39911) | AAAI | — | 0 |
| Aobo Chen et al. | [Towards Unveiling Vulnerabilities of Large Reasoning Models in Machine Unlearning](https://arxiv.org/abs/2604.04255) | AAAI | — | 0 |
| Junehyoung Kwon et al. | [Easy to Learn, Yet Hard to Forget: Towards Robust Unlearning Under Bias](https://doi.org/10.1609/aaai.v40i7.37499) | AAAI | — | 0 |
| Wei Qian et al. | [Towards Benchmarking Privacy Vulnerabilities in Selective Forgetting with Large Language Models](https://doi.org/10.1609/aaai.v40i44.41120) | AAAI | — | 0 |
| Fuyao Zhang et al. | [Oblivionis: A Lightweight Learning and Unlearning Framework for Federated Large Language Models](https://doi.org/10.1609/aaai.v40i33.40045) | AAAI | — | 0 |
| Zexi Li et al. | [Editing as Unlearning: Are Knowledge Editing Methods Strong Baselines for Large Language Model Unlearning?](https://doi.org/10.1609/aaai.v40i44.41097) | AAAI | — | 0 |
| Xue Jiang et al. | [Large Language Model Unlearning for Source Code](https://doi.org/10.1609/aaai.v40i37.40398) | AAAI | [GitHub](https://github.com/dinhngoctuyen4125/PROD_meomeo) | 0 |
| Xiangyu Zhou et al. | [Not All Tokens Are Meant to Be Forgotten](https://doi.org/10.1609/aaai.v40i44.41156) | AAAI | [GitHub](https://github.com/xzhou98/Unlearning-TPO) | 0 |
| Alyssa Shuang Sha, Bernardo Pereira Nunes, Armin Haller | [Selective Forgetting in Machine Learning and Beyond: A Survey](https://doi.org/10.1145/3796542) | ACM Computing Surveys | — | 0 |
| Zhuo Cai et al. | [Misinformation Unlearning for Responsible Content Recommendation](https://doi.org/10.1145/3812649) | ACM Transactions on Information Systems | [GitHub](https://github.com/iamZhuoCai/MisEraser) | 0 |
| Yi Gao et al. | [An Illusion of Unlearning? Assessing Machine Unlearning Through Internal Representations](https://arxiv.org/abs/2604.08271) | AISTATS Poster | — | 0 |
| Chika Onyagu et al. | [Securing the Edge: An AI-Driven Federated Unlearning Framework for Cybersecurity and IoT Forensics](https://doi.org/10.63363/aijfr.2026.v07i02.4891) | Advanced International Journal for Research | — | 0 |
| Yanjiang Li | [Unlearning bias in text diffusion models based on decoupled adapter](https://doi.org/10.54254/2977-3903/2026.31209) | Advances in Engineering Innovation | — | 0 |
| Ning Lin et al. | [Machine Unlearning and Continual Learning in Hybrid Resistive Memory Neuromorphic Systems](https://arxiv.org/abs/2601.10037) | Applied Sciences | [GitHub](https://github.com/MrLinNing/RMAdaptiveMachine) | 0 |
| Khoa Tran, Simon S. Woo | [Efficient Unlearning through Maximizing Relearning Convergence Delay](https://arxiv.org/abs/2604.09391) | CVPR | — | 0 |
| Bin Cao et al. | [MOEA-SISA: Multiobjective Optimization to Improve Model Performance During Forgetting Data](https://doi.org/10.23919/cje.2024.00.052) | Chinese journal of electronics | — | 0 |
| Zhenguo Ma et al. | [Enhancing federated unlearning using catastrophic forgetting in heterogeneous Industrial Internet of Things](https://doi.org/10.1016/j.comcom.2026.108497) | Computer Communications | — | 0 |
| Hui Huang et al. | [ASG-FU: An adaptive and secure grouping framework for federated unlearning](https://doi.org/10.1016/j.csi.2026.104159) | Computer Standards & Interfaces | [GitHub](https://github.com/Fed-UN/ASG-FU) | 0 |
| Jiahao Fan et al. | [Fortified Concept Forgetting for text-to-image generative models by machine unlearning on CLIP](https://doi.org/10.1016/j.csi.2026.104142) | Computer Standards &amp; Interfaces | — | 0 |
| Alireza dehghanpour farashah et al. | [Multilingual Amnesia: On the Transferability of Unlearning in Multilingual LLMs](https://doi.org/10.18653/v1/2026.eacl-long.260) | EACL | [GitHub](https://github.com/alirezafarashah/multilingual_unlearning) | 0 |
| Tazeem Ahmad et al. | [Balancing privacy and performance: An empirical study of machine unlearning in deep learning models](https://doi.org/10.1016/j.engappai.2025.113530) | Engineering applications of artificial intelligence | — | 0 |
| Jie Fu et al. | [Revisiting Privacy Leakage in Machine Unlearning: Membership Inference Beyond the Forgotten Set](https://arxiv.org/abs/2605.01129) | Euro S&P' | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Long Xue, Yixin Yao, Bin Song | [EAI-DMCU: Evolutionary algorithm-inspired diffusion model for concept unlearning](https://doi.org/10.1016/j.eswa.2026.132466) | Expert Systems with Applications | — | 0 |
| Jiaqi Chao et al. | [FedASU: Attention-guided sensitivity unlearning framework for multi-scenario federated graph unlearning](https://doi.org/10.1016/j.eswa.2026.132218) | Expert Systems with Applications | — | 0 |
| Wang Ye et al. | [Reconstruction attacks on forgotten data in federated unlearning](https://doi.org/10.1016/j.eswa.2026.131190) | Expert Systems with Applications | — | 0 |
| D.J. Ranade, Rajesh Jaiswal | [Right-to-be-Forgotten by Design in Adapter-Tuned Transformers](https://doi.org/10.1145/3777490.3777507) | HCAIep | — | 0 |
| Baisen Wang et al. | [Latent DPO for Concept Erasure in Text-To-Video Diffusion Models](https://doi.org/10.1109/icassp55912.2026.11463338) | ICASSP | — | 0 |
| Ruyun Wang, Fuqing Zhu, Xi Zhang | [Flash-Unlearn: On-the-Fly, Training-Free Large Language Models Unlearning Through Subspace Distribution Filtering](https://doi.org/10.1109/icassp55912.2026.11460558) | ICASSP | — | 0 |
| Weimin Lai et al. | [Federated Camouflaged Poisoning Attack in Federated Unlearning](https://doi.org/10.1109/icassp55912.2026.11463455) | ICASSP | [GitHub](https://github.com/laiweimin/FedCPA) | 0 |
| Boxu Xiao, Sijia Liu, Qing Ling | [Top-1 Compression Suffices for Federated Unlearning with the Help of Adaptive Error Feedback](https://doi.org/10.1109/icassp55912.2026.11462604) | ICASSP | — | 0 |
| Siyuan Wu et al. | [A Model-Heterogeneous Federated Unlearning Method via Negative Knowledge Distillation](https://doi.org/10.1109/icassp55912.2026.11462588) | ICASSP | — | 0 |
| Wenwei Zhao et al. | [Adversarial Update-Based Federated Unlearning for Poisoned Model Recovery](https://doi.org/10.1109/icassp55912.2026.11463407) | ICASSP | [GitHub](https://github.com/bddk520/DailyArXiv) | 0 |
| Jingwen Pu et al. | [CLEAN: Compliant Loops with Enhanced Adjustment for Training-Free Unlearning](https://doi.org/10.1109/icassp55912.2026.11463950) | ICASSP | — | 0 |
| Ruyun Wang, Fuqing Zhu, Xiaodan Zhang | [Breaking the Forgetting-Memorization Trade-Off: A Memory-Adaptive Optimizer for Effective Large Language Models Unlearning](https://doi.org/10.1109/icassp55912.2026.11462705) | ICASSP | — | 0 |
| Ruyun Wang, Fuqing Zhu, Xiaodan Zhang | [Why Delete? Just Make it Natural. Maximum Entropy Distribution Distillation for Large Language Models Unlearning](https://doi.org/10.1109/icassp55912.2026.11463279) | ICASSP | — | 0 |
| Nithya Leela, Ruthi Niyenthri, Dr. G. R. Karpagam | [Machine Unlearning Concepts, Algorithm, and Case Studies for Forgetting in Artificial Intelligence](https://doi.org/10.1109/ICISCoIS62701.2026.11448044) | ICISCoIS | — | 0 |
| Ruthi Niyenthri S et al. | [Empirical Analysis of Loss Functions for Machine Unlearning Across Minority and Majority Classes](https://doi.org/10.1109/ICISCoIS62701.2026.11447967) | ICISCoIS | — | 0 |
| Zichun Ye et al. | [Unlearning Offline Stochastic Multi-Armed Bandits](https://arxiv.org/abs/2605.00638) | ICML poster | — | 0 |
| S. Youn, Chulyun Kim | [MiniUn: A Machine Unlearning Method to Minimize Dependency on Original Training Data](https://doi.org/10.1109/ACCESS.2026.3653817) | IEEE Access | — | 0 |
| A. Patel et al. | [Privacy-Preserving Multi-Class Skin Lesion Classification Using Single-Shot Machine Unlearning and Noise Maximization](https://doi.org/10.1109/ACCESS.2026.3669210) | IEEE Access | — | 0 |
| Shohei Yamamoto, Soh Yoshida, M. Muneyasu | [Feature Space-Preserving Machine Unlearning for Robust Image Classification With Noisy Labels](https://doi.org/10.1109/ACCESS.2026.3676403) | IEEE Access | [GitHub](https://github.com/meruemon/FSPMU) | 0 |
| Q. Ngo et al. | [Machine Unlearning for Equalizer Classifiers in 6G Wireless Communication Systems](https://doi.org/10.1109/LCOMM.2026.3673226) | IEEE Communications Letters | — | 0 |
| Yang Zhao et al. | [A Survey on Continuous Unlearning in Generative AI: Approaches and Tradeoffs](https://doi.org/10.1109/MIS.2025.3616192) | IEEE Intelligent Systems | — | 0 |
| Zhiqiang Xie et al. | [Closed-Box Unlearning for Large Language Model-Enabled Internet of Everything](https://doi.org/10.1109/mnet.2026.3660124) | IEEE Network | — | 0 |
| Wei Zheng et al. | [Label Leakage Attacks in Machine Unlearning: A Parameter and Inversion-Based Approach](https://arxiv.org/abs/2604.07386) | IEEE Open J. Comput. Soc | [GitHub](https://github.com/zhouchanggeng/DailyArXiv) | 0 |
| Lei Zhou, Youwen Zhu, Rongke Liu | [Model Inversion Attack Against Federated Unlearning](https://doi.org/10.1109/tifs.2026.3666295) | IEEE T-IFS | — | 0 |
| Claudio Savelli et al. | [UnSLU-BENCH+: Extended Machine Unlearning Benchmark for Spoken Language Understanding](https://doi.org/10.1109/TASLPRO.2026.3675768) | IEEE TASLP | — | 0 |
| Huanghuang Liang et al. | [Federated Unlearning via Representation Misdirection with Adaptive Anchor Generation](https://doi.org/10.1109/tdsc.2026.3689563) | IEEE TDSC | — | 0 |
| Zitong Li et al. | [SUGPT: Efficient Graph Unsummarization for the Right to Be Forgotten](https://doi.org/10.1109/TKDE.2026.3667723) | IEEE TKDE | — | 0 |
| Alessio Mora, Lorenzo Valerio, Paolo Bellavista | [Federated Unlearning via Distilled Data](https://doi.org/10.1109/tmc.2026.3666356) | IEEE TMC | [GitHub](https://github.com/alessiomora/unlearning_distilled_data) | 0 |
| Ruinan Jin et al. | [Forgettable Federated Linear Learning With Certified Data Unlearning](https://doi.org/10.1109/tnnls.2026.3683398) | IEEE TNNLS | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| Chenchen Tan et al. | [Logits-Level Balanced Machine Unlearning for LLM-Based Recommendation System](https://doi.org/10.1109/tnnls.2026.3660137) | IEEE TNNLS | — | 0 |
| Zeyi Li et al. | [Silent-App-Aware Federated Machine Unlearning for Encrypted Network Traffic Classification](https://doi.org/10.1109/TNSE.2026.3672152) | IEEE TNSE | — | 0 |
| Zhenguo Ma et al. | [AdaFUN: Enhancing Federated Unlearning with Adaptive Local Step in Edge Computing](https://doi.org/10.1109/tsc.2026.3685363) | IEEE TSC | — | 0 |
| Yuta Goto et al. | [Feature Transformation for Learning with Selective Forgetting](https://doi.org/10.1587/transinf.2025edp7064) | IEICE Transactions on Information and Systems | — | 0 |
| Ayyadurai M, Nandha Kumar P | [Machine Unlearning for Reinforcement Learning Agents: Methods and Challenges](https://doi.org/10.1109/IITCEE67948.2026.11394122) | IITCEE | — | 0 |
| Jiaqi Lang, Linjing Li, D. Zeng | [A Unified Knowledge Management Framework for Continual Learning and Machine Unlearning in Large Language Models](https://doi.org/10.3390/info17030238) | Inf | — | 0 |
| Haoke Han et al. | [Federated Illusion: Multi-Level Geometric Privacy Audit for Federated Graph Unlearning](https://doi.org/10.3390/info17050424) | Information | — | 0 |
| Yanxin Hu et al. | [FedRazor: Two-Stage Federated Unlearning via Representation Divergence and Gradient Conflict Trimming](https://doi.org/10.3390/info17020146) | Information | — | 0 |
| Saeed Iqbal et al. | [Causal continual unlearning with disentangled anomaly representations for private industrial vision](https://doi.org/10.1016/j.ipm.2026.104731) | Information Processing & Management | — | 0 |
| Mohammad Partohaghighi et al. | [A survey on bias and fairness in machine unlearning](https://doi.org/10.1016/j.jiixd.2026.03.003) | Journal of Information and Intelligence | — | 0 |
| A. Kurt et al. | [EVALUATING SISA-BASED MACHINE UNLEARNING ACROSS DIVERSE MODALITIES: TABULAR, VISUAL AND AUDITORY DATA](https://doi.org/10.56850/jnse.1829992) | Journal of Naval Sciences and Engineering | — | 0 |
| Xinlei Yu, Zhen Wang, Miaomiao Wang | [A cost-efficient federated unlearning framework with rollback and compression optimization](https://doi.org/10.1016/j.knosys.2026.115699) | Knowledge-Based Systems | — | 0 |
| Faqian Guan et al. | [Graph unlearning: Efficient node removal in graph neural networks](https://doi.org/10.1016/j.knosys.2026.116024) | Knowledge-Based Systems | — | 0 |
| Tzu-Hsuan Yang, Cheng-Te Li | [ReCUR: Bipartite Graph Contrastive Unlearning with Influence Estimation for Privacy-Preserved Recommendation](https://doi.org/10.1007/s10994-025-06979-8) | Machine Learning | — | 0 |
| Xiaoran Bai et al. | [Dual-path consistency constrained concept erasure for text-to-image diffusion models](https://doi.org/10.1007/s00530-025-02168-8) | Multimedia Systems | — | 0 |
| Yaohua Liu, Wenjie Zhu | [Federated Unlearning via Synthetic Data Distillation](https://doi.org/10.1109/NNICE68970.2026.11465532) | NNICE | — | 0 |
| Yaohua Liu, Wenjie Zhu | [Federated Unlearning via Synthetic Data Distillation](https://doi.org/10.1109/nnice68970.2026.11465532) | NNICE | — | 0 |
| Xiaoyu Xu et al. | [Rethinking LLM Unlearning: From Safety Constraints to Functional Utility](https://doi.org/10.13140/rg.2.2.12714.99526) | Nat Mach Intell | — | 0 |
| Xuran Li et al. | [PRUNE: A Patching Based Repair Framework for Certifiable and Privacy-Robust Unlearning of Neural Networks](https://doi.org/10.1016/j.neunet.2026.108897) | Neural Networks | — | 0 |
| Hanxiao Wu et al. | [Adversarial discriminant attack on text-to-image diffusion models](https://doi.org/10.1016/j.neunet.2026.108716) | Neural Networks | — | 0 |
| Zheling Meng et al. | [Dark Miner: Towards combating residuals in concept erasure for text-to-image diffusion models](https://doi.org/10.1016/j.neucom.2026.133228) | Neurocomputing | — | 0 |
| Hui Chen et al. | [Entropy-driven sabotage: Informative unlearning attacks on diffusion model](https://doi.org/10.1016/j.neucom.2026.132644) | Neurocomputing | — | 0 |
| Qianfu Qiu et al. | [CDCU: A centroid drifting causal unlearning method for facial privacy protection](https://doi.org/10.1016/j.neucom.2026.133225) | Neurocomputing | — | 0 |
| Ningbo Liu et al. | [Balance forgetting and remembering: An extension of machine unlearning for policy updates in machine learning-based access control](https://doi.org/10.1016/j.neucom.2026.133388) | Neurocomputing | [GitHub](https://github.com/ningboliucug/bfr-policy-update) | 0 |
| Jingtai Li et al. | [UPGP:Backdoor defense via unlearning perturbation and orthogonality-constraint gradient projection](https://doi.org/10.1016/j.patcog.2026.113211) | Pattern Recognition | — | 0 |
| Jun-Jian Su et al. | [Quantum machine unlearning](https://www.semanticscholar.org/paper/50e944abf8b120893ae218370b7708de3a09defe) | Phys. Rev. Applied | [GitHub](https://github.com/Sujun124/QMU) | 0 |
| XIAO Chuqiao et al. | [An applied study of privacy preservation on government affairs based on federated unlearning](https://openalex.org/W7126894699) | SHILAP Revista de lepidopterología | — | 0 |
| Andreza M. C. Falcao, Filipe R. Cordeiro | [Does Machine Unlearning Preserve Clinical Safety? A Risk Analysis for Medical Image Classification](https://arxiv.org/abs/2604.23854) | SIBGRAPI | — | 0 |
| Doruk Benli et al. | [TUNE: A Task For Turkish Machine Unlearning For Data Privacy](https://doi.org/10.18653/v1/2026.sigturk-1.3) | SIGTURK | — | 0 |
| Jiali Wang et al. | [Feature-indistinguishable machine unlearning via negative-hot label encoding and class weight masking](https://doi.org/10.1038/s41598-026-40379-9) | Scientific Reports | — | 0 |
| Zifan Zhang et al. | [Network Digital Untwinning: Towards Backward Optimization of Digital Twins](https://arxiv.org/abs/2605.00169) | Struct Multidisc Optim | — | 0 |
| Yun Xia | [P-Fed Rec: A Certifiable Unlearning Framework for Personalized Federated Recommendation](https://doi.org/10.24940/theijst/2025/v13/i12/st2512-004) | The International Journal of Science & Technoledge | — | 0 |
| Anamta Sayyed et al. | [CLUE: Bringing Machine Unlearning to Mobile Devices](https://www.semanticscholar.org/paper/6f91e9300b8d0b7a4a2d4c1c297b367abcdc6b04) | WACV | — | 0 |
| Mayank Kumar Kundalwal, Deepak Mishra, Asif Ekbal | [Federated Model Synchronization for Diagnostic Redefinition through a Novel Selective Parameter Unlearning](https://www.semanticscholar.org/paper/07b46b66f7ed0452566be439c8a4824e2e4e4e9f) | WACV | — | 0 |
| Ce Liu et al. | [IPRU: Input-Perturbation-based Radio Frequency Fingerprinting Unlearning for LAWNs](https://arxiv.org/abs/2604.24022) | WCNC | — | 0 |
| Sheetal Sehgal, Ankita Verma, Himani Bansal | [From Forgetting to Future: A Survey of Machine Unlearning Approaches](https://doi.org/10.1002/widm.70082) | WIREs Data Mining and Knowledge Discovery | — | 0 |
| Jiahao Zhang et al. | [Unlearning Inversion Attacks for Graph Neural Networks](https://doi.org/10.1145/3773966.3777929) | WSDM | [GitHub](https://github.com/QwQ2000/WSDM26-Graph-Unlearning-Inversion) | 0 |
| Chenhan Zhang et al. | [Forget Me, Not My Friends! Object Unlearning Based on Scene Graphs](https://doi.org/10.1145/3773966.3777964) | WSDM | — | 0 |
| Peng Liu et al. | [Towards Practical LLM Unlearning: Efficient, Modular, and Retain-Free](https://doi.org/10.1145/3774904.3792324) | WWW | — | 0 |
| Pengyang Shao et al. | [BalDRO: A Distributionally Robust Optimization based Framework for Large Language Model Unlearning](https://doi.org/10.1145/3774904.3792975) | WWW | [GitHub](https://github.com/nxZhai/BalDRO) | 0 |
| Jiajun Liu et al. | [Unlearning of Knowledge Graph Embedding via Preference Optimization](https://doi.org/10.1145/3774904.3792397) | WWW | [GitHub](https://github.com/ljj-007/GraphDPO) | 0 |
| H Wang et al. | [DIARY: Differentially Private Recovery with Adaptive Privacy Budgets in Federated Unlearning](https://doi.org/10.1145/3774904.3792423) | WWW | [GitHub](https://github.com/LaityLu/DIARY) | 0 |
| Zhigao Zheng et al. | [DeepUL: Deep Unlearning via Model Sparsity](https://doi.org/10.1145/3774904.3792441) | WWW | — | 0 |
| Roy Rinberg et al. | [Easy Data Unlearning Bench](https://doi.org/10.48550/arXiv.2602.16400) | arXiv | [HF](https://huggingface.co/datasets/easydub/EasyDUB-dataset) | 0 |
| Aviraj Newatia et al. | [Mitigating Privacy Risk via Forget Set-Free Unlearning](https://arxiv.org/abs/2604.10636) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Martin Van Waerebeke et al. | [Variance-Reduced $(\varepsilon,δ)-$Unlearning using Forget Set Gradients](https://openalex.org/W7130237008) | arXiv | — | 0 |
| Tuan Le, Wei Qian, Mengdi Huai | [Selective Forgetting for Large Reasoning Models](https://arxiv.org/abs/2604.03571) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yingjie Gu et al. | [FSFM: A Biologically-Inspired Framework for Selective Forgetting of Agent Memory](https://openalex.org/W7155654911) | arXiv | — | 0 |
| Xiaoyu Xu et al. | [FIT: Defying Catastrophic Forgetting in Continual LLM Unlearning](https://doi.org/10.48550/arXiv.2601.21682) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yisheng Zhong, Zhengbang Yang, Zhuangdi Zhu | [DUET: Distilled LLM Unlearning from an Efficiently Contextualized Teacher](https://doi.org/10.48550/arXiv.2601.21283) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Qiang Chen et al. | [LEGATO: Good Identity Unlearning Is Continuous](https://openalex.org/W7120272199) | arXiv | — | 0 |
| Pengyu Li et al. | [$\textbf{AGT$^{AO}$}$: Robust and Stabilized LLM Unlearning via Adversarial Gating Training with Adaptive Orthogonality](https://openalex.org/W7127541597) | arXiv | [GitHub](https://github.com/TiezMind/AGT-unlearning) | 0 |
| Borisiuk Anna et al. | [Anatomy of Unlearning: The Dual Impact of Fact Salience and Model Fine-Tuning](https://doi.org/10.48550/arXiv.2602.19612) | arXiv | [HF](https://huggingface.co/datasets/SwetieePawsss/DUET) | 0 |
| Zhengbang Yang et al. | [CATNIP: LLM Unlearning via Calibrated and Tokenized Negative Preference Alignment](https://doi.org/10.48550/arXiv.2602.02824) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Chahana Dahal, A. Balasubramaniam, Zuobin Xiong | [GONE: Structural Knowledge Unlearning via Neighborhood-Expanded Distribution Shaping](https://arxiv.org/abs/2603.12275) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Himanshu Mishra, Kanwal Mehreen | [QUAIL: Quantization Aware Unlearning for Mitigating Misinformation in LLMs](https://doi.org/10.48550/arXiv.2601.15538) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ningkang Peng et al. | [Don't Break the Boundary: Continual Unlearning for OOD Detection Based on Free Energy Repulsion](https://doi.org/10.48550/arXiv.2602.06331) | arXiv | — | 0 |
| Zezheng Wu et al. | [U-CAN: Utility-Aware Contrastive Attenuation for Efficient Unlearning in Generative Recommendation](https://doi.org/10.48550/arXiv.2602.23400) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| 龚庆辉 | [Dynamic Eraser for Guided Concept Erasure in Diffusion Models](https://openalex.org/W7155244555) | arXiv | — | 0 |
| Chuancheng Shi et al. | [OrthoEraser: Coupled-Neuron Orthogonal Projection for Concept Erasure](https://arxiv.org/abs/2603.11493) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Jiang, Nanxiang et al. | [Z-Erase: Enabling Concept Erasure in Single-Stream Diffusion Transformers](https://arxiv.org/abs/2603.25074) | arXiv | [GitHub](https://github.com/nxjiang-jnx/Z-Erase) | 0 |
| Zhiqi Zhang et al. | [Differential Vector Erasure: Unified Training-Free Concept Erasure for Flow Matching Models](https://doi.org/10.48550/arXiv.2602.01089) | arXiv | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zhuan Shi et al. | [Neighbor-Aware Localized Concept Erasure in Text-to-Image Diffusion Models](https://arxiv.org/abs/2603.25994) | arXiv | [GitHub](https://github.com/alirezafarashah/NLCE) | 0 |
| Junyeong Ahn, Seojin Yoon, Sungyong Baik | [EGLOCE: Training-Free Energy-Guided Latent Optimization for Concept Erasure](https://arxiv.org/abs/2604.09405) | arXiv | — | 0 |
| Jun Li et al. | [Beyond Text Prompts: Precise Concept Erasure through Text-Image Collaboration](https://arxiv.org/abs/2604.15829) | arXiv | [GitHub](https://github.com/OpenAscent-L/TICoE) | 0 |
| Yi Sun et al. | [ActErase: A Training-Free Paradigm for Precise Concept Erasure via Activation Redirection](https://arxiv.org/abs/2601.00267) | arXiv | [GitHub](https://github.com/yilunzhao/s2-audit) | 0 |
| Zhaoxin Fan et al. | [EraseAnything++: Enabling Concept Erasure in Rectified Flow Transformers Leveraging Multi-Object Optimization](https://doi.org/10.48550/arXiv.2603.00978) | arXiv | [GitHub](https://github.com/CyL97/Awesome-Video-Generation-Post-Training) | 0 |
| Hoigi Seo et al. | [Erasing Thousands of Concepts: Towards Scalable and Practical Concept Erasure for Text-to-Image Diffusion Models](https://openalex.org/W7155246462) | arXiv | — | 0 |
| Yongwoo Kim et al. | [Consistency-Preserving Concept Erasure via Unsafe-Safe Pairing and Directional Fisher-weighted Adaptation](https://doi.org/10.48550/arXiv.2602.05339) | arXiv | — | 0 |
| Uichan Lee, Jeonghyeon Kim, Sangheum Hwang | [Localized Concept Erasure in Text-to-Image Diffusion Models via High-Level Representation Misdirection](https://openalex.org/W7131319545) | arXiv | — | 0 |
| Mansi et al. | [Selective Fine-Tuning for Targeted and Robust Concept Unlearning](https://doi.org/10.48550/arXiv.2602.07919) | arXiv | — | 0 |
| Kaiyuan Deng et al. | [Forget Many, Forget Right: Scalable and Precise Concept Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2601.06162) | arXiv | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zhangyun Tan et al. | [Can VLMs Truly Forget? Benchmarking Training-Free Visual Concept Unlearning](https://arxiv.org/abs/2604.03114) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yong Zou et al. | [REFORGE: Multi-modal Attacks Reveal Vulnerable Concept Unlearning in Image Generation Models](https://arxiv.org/abs/2603.16576) | arXiv | [GitHub](https://github.com/Imfatnoily/REFORGE) | 0 |
| Duc Hao Pham et al. | [A Concept is More Than a Word: Diversified Unlearning in Text-to-Image Diffusion Models](https://openalex.org/W7140001222) | arXiv | [GitHub](https://github.com/TruongDuy2607/Diversified_Unlearning) | 0 |
| Zeguan Xiao et al. | [Representation-Guided Parameter-Efficient LLM Unlearning](https://arxiv.org/abs/2604.17396) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Haoran Tang, Rajiv Khanna | [From Logits to Latents: Contrastive Representation Shaping for LLM Unlearning](https://doi.org/10.48550/arXiv.2601.22028) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| João Vitor Boer Abitante et al. | [Quantization-Robust LLM Unlearning via Low-Rank Adaptation](https://doi.org/10.48550/arXiv.2602.13151) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ziwen Liu et al. | [Randomized Antipodal Search Done Right for Data Pareto Improvement of LLM Unlearning](https://arxiv.org/abs/2604.16591) | arXiv | [HF](https://huggingface.co/BAAI/bge-base-en-v1.5) | 0 |
| Yisheng Zhong, Sijia Liu, Zhuangdi Zhu | [Harmonizing Multi-Objective LLM Unlearning via Unified Domain Representation and Bidirectional Logit Distillation](https://arxiv.org/abs/2604.15482) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Tianlong Yu et al. | [UNSEEN: A Cross-Stack LLM Unlearning Defense against AR-LLM Social Engineering Attacks](https://openalex.org/W7158422502) | arXiv | — | 0 |
| Ruihao Pan, Suhang Wang | [A Comprehensive Evaluation of LLM Unlearning Robustness under Multi-Turn Interaction](https://doi.org/10.48550/arXiv.2603.00823) | arXiv | — | 0 |
| Zhaokun Wang et al. | [CAP: Controllable Alignment Prompting for Unlearning in LLMs](https://arxiv.org/abs/2604.21251) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Esen Kurt, Haithem Afli | [Operationalising the Right to be Forgotten in LLMs: A Lightweight Sequential Unlearning Framework for Privacy-Aligned Deployment in Politically Sensitive Environments](https://arxiv.org/abs/2604.12459) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Tyler Lizzo, Larry Heck | [Unlearning in LLMs: Methods, Evaluation, and Open Challenges](https://doi.org/10.48550/arXiv.2601.13264) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ziheng Chen et al. | [CURE:Circuit-Aware Unlearning for LLM-based Recommendation](https://arxiv.org/abs/2604.04982) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Bin Wang et al. | [Agentic Unlearning: When LLM Agent Meets Machine Unlearning](https://doi.org/10.48550/arXiv.2602.17692) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Dayong Ye et al. | [Secure Forgetting: A Framework for Privacy-Driven Unlearning in Large Language Model (LLM)-Based Agents](https://arxiv.org/abs/2604.00430) | arXiv | — | 0 |
| Vishnu Narayanan Anilkumar et al. | [Relationship-Aware Safety Unlearning for Multimodal LLMs](https://arxiv.org/abs/2603.14185) | arXiv | — | 0 |
| Yuze Wang et al. | [SAU: Sparsity-Aware Unlearning for LLMs via Gradient Masking and Importance Redistribution](https://arxiv.org/abs/2602.00577) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xinjie Zhou et al. | [Data-Free Privacy-Preserving for LLMs via Model Inversion and Selective Unlearning](https://doi.org/10.48550/arXiv.2601.15595) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Dinesh Srivasthav P et al. | [Shadow Unlearning: A Neuro-Semantic Approach to Fidelity-Preserving Faceless Forgetting in LLMs](https://doi.org/10.48550/arXiv.2601.04275) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Seyun Bae, Seokhan Lee, Eunho Yang | [CURaTE: Continual Unlearning in Real Time with Ensured Preservation of LLM Knowledge](https://arxiv.org/abs/2604.14644) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xianya Fang et al. | [Beyond Superficial Unlearning: Sharpness-Aware Robust Erasure of Hallucinations in Multimodal LLMs](https://doi.org/10.48550/arXiv.2601.16527) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Eugenia Iofinova, Dan Alistarh | [Behemoth: Benchmarking Unlearning in LLMs Using Fully Synthetic Data](https://doi.org/10.48550/arXiv.2601.23153) | arXiv | [GitHub](https://github.com/IST-DASLab/behemoth) | 0 |
| Chengyi Cai et al. | [Per-parameter Task Arithmetic for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2601.22030) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Ce Fang et al. | [KUDA: Knowledge Unlearning by Deviating Representation for Large Language Models](https://doi.org/10.48550/arXiv.2602.19275) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Efstratios Zaradoukas, Bardh Prenkaj, Gjergji Kasneci | [Reinforcement Unlearning via Group Relative Policy Optimization](https://doi.org/10.48550/arXiv.2601.20568) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Tien Dang et al. | [Beyond Forgetting: Machine Unlearning Elicits Controllable Side Behaviors and Capabilities](https://doi.org/10.48550/arXiv.2601.21702) | arXiv | [GitHub](https://github.com/meta-llama/llama3) | 0 |
| Chengyi Cai et al. | [Visual-Guided Key-Token Regularization for Multimodal Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2601.22020) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Jiajia Song, Zhihan Guo, Jionghao Lin | [Simulating Novice Students Using Machine Unlearning and Relearning in Large Language Models](https://arxiv.org/abs/2603.26142) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Mutsumi Sasaki et al. | [Exclusive Unlearning](https://arxiv.org/abs/2604.06154) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xingjian Zhao, Mohammad Mohammadi Amiri, Malik Magdon‐Ismail | [WIN-U: Woodbury-Informed Newton-Unlearning as a retain-free Machine Unlearning Framework](https://arxiv.org/abs/2604.13438) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Jagadeesh Rachapudi et al. | [RePAIR: Interactive Machine Unlearning through Prompt-Aware Model Repair](https://arxiv.org/abs/2604.12820) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Xiaoyi Chen et al. | [PrivUn: Unveiling Latent Ripple Effects and Shallow Forgetting in Privacy Unlearning](https://arxiv.org/abs/2604.22076) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Seunghee Koh et al. | [Forget What Matters, Keep the Rest: Selective Unlearning of Informative Tokens](https://arxiv.org/abs/2604.17785) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Pengfei Ding, Yan Wang, Guanfeng Liu | [Re-understanding Graph Unlearning through Memorization](https://doi.org/10.1145/3774904.3792383) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Jiahao Zhang, Yilong Wang, Suhang Wang | [Attack by Unlearning: Unlearning-Induced Adversarial Attacks on Graph Neural Networks](https://arxiv.org/abs/2603.18570) | arXiv | — | 0 |
| Shreyansh Pathak, Jyotishman Das | [Graph Propagated Projection Unlearning: A Unified Framework for Vision and Audio Discriminative Models](https://arxiv.org/abs/2604.13127) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Zhaoyuan Cai, Xinglin Zhang | [Asynchronous Federated Unlearning with Invariance Calibration for Medical Imaging](https://arxiv.org/abs/2604.26809) | arXiv | — | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Jellyfish: Zero-Shot Federated Unlearning Scheme with Knowledge Disentanglement](https://arxiv.org/abs/2604.04030) | arXiv | [GitHub](https://github.com/xiao-jian-zi/Jellyfish) | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Forgetting to Witness: Efficient Federated Unlearning and Its Visible Evaluation](https://arxiv.org/abs/2604.04800) | arXiv | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Yuhua Xu et al. | [Client-Verifiable and Efficient Federated Unlearning in Low-Altitude Wireless Networks](https://arxiv.org/abs/2603.29688) | arXiv | — | 0 |
| Yue Li et al. | [FedCARE: Federated Unlearning with Conflict-Aware Projection and Relearning-Resistant Recovery](https://doi.org/10.48550/arXiv.2601.22589) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Radmehr Karimian et al. | [$f$-FUM: Federated Unlearning via min--max and $f$-divergence](https://doi.org/10.48550/arXiv.2602.06187) | arXiv | — | 0 |
| Hanwei Tan et al. | [Lethe:Adapter-Augmented Dual-Stream Update for Persistent Knowledge Erasure in Federated Unlearning](https://openalex.org/W7127203428) | arXiv | — | 0 |
| Minh-Duong Nguyen et al. | [Computation and Communication Efficient Federated Unlearning via On-server Gradient Conflict Mitigation and Expression](https://arxiv.org/abs/2603.13795) | arXiv | — | 0 |
| Zeyan Wang et al. | [FUPareto: Bridging the Forgetting-Utility Gap in Federated Unlearning via Pareto Augmented Optimization](https://openalex.org/W7127542582) | arXiv | — | 0 |
| Jer Shyuan Ng et al. | [Federated Unlearning in Edge Networks: A Survey of Fundamentals, Challenges, Practical Applications and Future Directions](https://doi.org/10.48550/arXiv.2601.09978) | arXiv | — | 0 |
| Yijun Quan, Wentai Wu, Giovanni Montana | [Exact Federated Continual Unlearning for Ridge Heads on Frozen Foundation Models](https://arxiv.org/abs/2603.12977) | arXiv | — | 0 |
| Mykola Vysotskyi et al. | [Critic-Guided Reinforcement Unlearning in Text-to-Image Diffusion](https://doi.org/10.48550/arXiv.2601.03213) | arXiv | — | 0 |
| K. Lee et al. | [Unlearning the Unpromptable: Prompt-free Instance Unlearning in Diffusion Models](https://arxiv.org/abs/2603.10445) | arXiv | [GitHub](https://github.com/WangWenhao0716/Awesome-Diffusion-Replication) | 0 |
| Zeliang Zhang et al. | [Why Instruction-Based Unlearning Fails in Diffusion Models?](https://openalex.org/W7149874254) | arXiv | — | 0 |
| Ashutosh Ranjan et al. | [Forgetting is Competition: Rethinking Unlearning as Representation Interference in Diffusion Models](https://doi.org/10.48550/arXiv.2603.00975) | arXiv | — | 0 |
| Arian Komaei Koma et al. | [Erasure or Erosion? Evaluating Compositional Degradation in Unlearned Text-To-Image Diffusion Models](https://arxiv.org/abs/2604.04575) | arXiv | — | 0 |
| Manyi Li et al. | [The Illusion of Forgetting: Attack Unlearned Diffusion via Initial Latent Variable Optimization](https://doi.org/10.48550/arXiv.2602.00175) | arXiv | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 0 |
| Aljalila Aladawi, Mohammed Talha Alam, Fakhri Karray | [Projected Gradient Unlearning for Text-to-Image Diffusion Models: Defending Against Concept Revival Attacks](https://arxiv.org/abs/2604.21041) | arXiv | — | 0 |
| Ci Zhang et al. | [Roots Beneath the Cut: Uncovering the Risk of Concept Revival in Pruning-Based Unlearning for Diffusion Models](https://arxiv.org/abs/2603.06640) | arXiv | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Naoki MURATA et al. | [GUDA: Counterfactual Group-wise Training Data Attribution for Diffusion Models via Unlearning](https://doi.org/10.48550/arXiv.2601.22651) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Xinwen Cheng et al. | [Compensation-free Machine Unlearning in Text-to-Image Diffusion Models by Eliminating the Mutual Information](https://doi.org/10.48550/arXiv.2603.00992) | arXiv | [GitHub](https://github.com/OPTML-Group/AdvUnlearn) | 0 |
| Ignacy Kolton et al. | [ReLAPSe: Reinforcement-Learning-trained Adversarial Prompt Search for Erased concepts in unlearned diffusion models](https://doi.org/10.48550/arXiv.2602.00350) | arXiv | [GitHub](https://github.com/gmum/ReLaPSe) | 0 |
| Xiang, Qianlong et al. | [TINA: Text-Free Inversion Attack for Unlearned Text-to-Image Diffusion Models](https://arxiv.org/abs/2603.17828) | arXiv | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 0 |
| Zhiyong Ma et al. | [PECKER: A Precisely Efficient Critical Knowledge Erasure Recipe For Machine Unlearning in Diffusion Models](https://arxiv.org/abs/2604.05634) | arXiv | [GitHub](https://github.com/twenhui2-afk/daily-paper-reader) | 0 |
| Hyundo Choi et al. | [Unlearning for One-Step Generative Models via Unbalanced Optimal Transport](https://arxiv.org/abs/2603.16489) | arXiv | — | 0 |
| Zhanting Zhou et al. | [TRU: Targeted Reverse Update for Efficient Multimodal Recommendation Unlearning](https://arxiv.org/abs/2604.02183) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Liang Qu et al. | [Federated Learning and Unlearning for Recommendation with Personalized Data Sharing](https://arxiv.org/abs/2603.11610) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Abdullah Khan, F. Sohel | [DurableUn: Quantization-Induced Recovery Attacks in Machine Unlearning](https://arxiv.org/abs/2605.02196) | arXiv | [GitHub](https://github.com/neurips26/DurableUnl) | 0 |
| Abdullah Khan, Hamid Laga, F. Sohel | [Metric Unreliability in Multimodal Machine Unlearning: A Systematic Analysis and Principled Unified Score](https://arxiv.org/abs/2605.02206) | arXiv | [GitHub](https://github.com/neurips26/UnifiedUnl) | 0 |
| Ruotong Ma et al. | [Graph Federated Unlearning for Privacy Preservation](https://arxiv.org/abs/2605.02297) | arXiv | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Jiawei Wu, Doudou Zhou | [Unlearning What Matters: Token-Level Attribution for Precise Language Model Unlearning](https://arxiv.org/abs/2605.00364) | arXiv | [GitHub](https://github.com/nlp-uoregon/trankit) | 0 |
| Zihao Ding, Beining Wu, Jun-Jie Huang | [EASE: Federated Multimodal Unlearning via Entanglement-Aware Anchor Closure](https://arxiv.org/abs/2605.00733) | arXiv | [GitHub](https://github.com/XCmiaow/knowledge-base) | 0 |
| Joseph Spracklen et al. | [LLM Ghostbusters: Surgical Hallucination Suppression via Adaptive Unlearning](https://arxiv.org/abs/2605.01047) | arXiv | [HF](https://huggingface.co/deepseek-ai/deepseek-coder-7b-instruct-v1.5) | 0 |
| Ishrak Hamim Mahi et al. | [Machine Unlearning for Class Removal through SISA-based Deep Neural Network Architectures](https://arxiv.org/abs/2604.27804) | arXiv | [GitHub](https://github.com/ZhikangNiu/arxiv_daily) | 0 |
| Ken Stewart | [Shape of Memory: a Geometric Analysis of Machine Unlearning in Second-Order Optimizers](https://arxiv.org/abs/2604.23046) | arXiv | — | 0 |
| C. Schneider, Philipp Schoenegger, Ben Bariach | [Separable Expert Architecture: Toward Privacy-Preserving LLM Personalization via Composable Adapters and Deletable User Proxies](https://arxiv.org/abs/2604.21571) | arXiv | [GitHub](https://github.com/mitchelllisle/data-privacy-papers) | 0 |
| Eun-Ju Park, Youjin Shin, Simon S. Woo | [Robust Continual Unlearning against Knowledge Erosion and Forgetting Reversal](https://arxiv.org/abs/2604.19108) | arXiv | [GitHub](https://github.com/DASH-Lab/SAFER) | 0 |
| Arman Hatami, Romina Aalishah, I. Monosov | [Class Unlearning via Depth-Aware Removal of Forget-Specific Directions](https://arxiv.org/abs/2604.15166) | arXiv | [GitHub](https://github.com/Trustworthy-AI-Group/Adversarial_Examples_Papers) | 0 |
| Y. Rahulamathavan et al. | [Orthogonal Subspace Projection for Continual Machine Unlearning via SVD-Based LoRA](https://arxiv.org/abs/2604.12526) | arXiv | — | 0 |
| Eleni Triantafillou et al. | [Is your algorithm unlearning or untraining?](https://arxiv.org/abs/2604.07962) | arXiv | [GitHub](https://github.com/frankmcsherry/blog) | 0 |
| Yunusa Haruna et al. | [Bias Redistribution in Visual Machine Unlearning: Does Forgetting One Group Harm Another?](https://arxiv.org/abs/2604.08111) | arXiv | — | 0 |
| Cai Selvas-Sala, Lei Kang, Lluis Gomez | [SALMUBench: A Benchmark for Sensitive Association-Level Multimodal Unlearning](https://arxiv.org/abs/2603.26316) | arXiv | [GitHub](https://github.com/cvc-mmu/salmubench) | 0 |
| Hyundong Jin, Dongyoon Han, Eunwoo Kim | [Which Concepts to Forget and How to Refuse? Decomposing Concepts for Continual Unlearning in Large Vision-Language Models](https://arxiv.org/abs/2603.21484) | arXiv | — | 0 |
| Micha l Woźniak et al. | [Unlearning-based sliding window for continual learning under concept drift](https://arxiv.org/abs/2603.14484) | arXiv | — | 0 |
| Kiseong Hong, Jungkyoo Shin, Eunwoo Kim | [Stake the Points: Structure-Faithful Instance Unlearning](https://arxiv.org/abs/2603.12915) | arXiv | [GitHub](https://github.com/Paper2Chinese/CVPR-2026-reading-papers-with-code) | 0 |
| Thanapat Trachu et al. | [Targeted Speaker Poisoning Framework in Zero-Shot Text-to-Speech](https://arxiv.org/abs/2603.07551) | arXiv | [GitHub](https://github.com/liutaocode/TTS-arxiv-daily) | 0 |
| Nanhong Liu et al. | [A SISA-based Machine Unlearning Framework for Power Transformer Inter-Turn Short-Circuit Fault Localization](https://arxiv.org/abs/2603.06962) | arXiv | — | 0 |
| Reo Fukunaga, Soh Yoshida, M. Muneyasu | [ACD-U: Asymmetric co-teaching with machine unlearning for robust learning with noisy labels](https://arxiv.org/abs/2603.07166) | arXiv | [GitHub](https://github.com/meruemon/ACD-U) | 0 |
| Carolin Heinzler, Kasra Malihi, Amartya Sanyal | [Less Noise, Same Certificate: Retain Sensitivity for Unlearning](https://arxiv.org/abs/2603.03172) | arXiv | — | 0 |
| Chenhao Zhang et al. | [Unlearning Evaluation through Subset Statistical Independence](https://doi.org/10.48550/arXiv.2603.00587) | arXiv | [GitHub](https://github.com/ChildEden/SDE) | 0 |
| Ji-Wha Shin et al. | [ROKA: Robust Knowledge Unlearning against Adversaries](https://doi.org/10.48550/arXiv.2603.00436) | arXiv | — | 0 |
| Tiantong Wang et al. | [MPU: Towards Secure and Privacy-Preserving Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2602.23798) | arXiv | [GitHub](https://github.com/Tristan-SHU/MPU) | 0 |
| Yong-Sheng Chen et al. | [Unlearning Noise in PINNs: A Selective Pruning Framework for PDE Inverse Problems](https://doi.org/10.48550/arXiv.2602.19967) | arXiv | [GitHub](https://github.com/chenyongssss/PPINN) | 0 |
| Haoyu Wang et al. | [MeGU: Machine-Guided Unlearning with Target Feature Disentanglement](https://doi.org/10.48550/arXiv.2602.17088) | arXiv | — | 0 |
| Martin Van Waerebeke et al. | [Variance-Reduced $(\varepsilon,\delta)-$Unlearning using Forget Set Gradients](https://arxiv.org/abs/2602.14938) | arXiv | — | 0 |
| Qinqi Lin et al. | [Governing AI Forgetting: Auditing for Machine Unlearning Compliance](https://doi.org/10.48550/arXiv.2602.14553) | arXiv | — | 0 |
| Jaewon Lee, Yongwoo Kim, Donghyun Kim | [Erase at the Core: Representation Unlearning for Machine Unlearning](https://doi.org/10.48550/arXiv.2602.05375) | arXiv | — | 0 |
| Ojasva Nema et al. | [Structural Disentanglement in Bilinear MLPs via Architectural Inductive Bias](https://doi.org/10.48550/arXiv.2602.05635) | arXiv | — | 0 |
| Somnath Basu Roy Chowdhury et al. | [Inference-time Unlearning Using Conformal Prediction](https://doi.org/10.48550/arXiv.2602.03787) | arXiv | — | 0 |
| Pengyu Li et al. | [AGTAO: Robust and Stabilized LLM Unlearning via Adversarial Gating Training with Adaptive Orthogonality](https://doi.org/10.48550/arXiv.2602.01703) | arXiv | [GitHub](https://github.com/TiezMind/AGT-unlearning) | 0 |
| Tian Zhang et al. | [Forget by Uncertainty: Orthogonal Entropy Unlearning for Quantized Neural Networks](https://doi.org/10.48550/arXiv.2602.00567) | arXiv | — | 0 |
| Kun Fang et al. | [Machine Unlearning in Low-Dimensional Feature Subspace](https://doi.org/10.48550/arXiv.2601.22456) | arXiv | [HF](https://huggingface.co/datasets/wmt/wmt19) | 0 |
| Antonio Almud'evar, Alfonso Ortega | [Representation Unlearning: Forgetting through Information Compression](https://doi.org/10.48550/arXiv.2601.21564) | arXiv | [GitHub](https://github.com/antonioalmudevar/representation_unlearning) | 0 |
| Liheng Yu et al. | [FaLW: A Forgetting-aware Loss Reweighting for Long-tailed Unlearning](https://doi.org/10.48550/arXiv.2601.18650) | arXiv | — | 0 |
| A. Zhu et al. | [GRIP: Algorithm-Agnostic Machine Unlearning for Mixture-of-Experts via Geometric Router Constraints](https://doi.org/10.48550/arXiv.2601.16905) | arXiv | — | 0 |
| Jinduo Guo, Yinzhi Cao | [A Robust Certified Machine Unlearning Method Under Distribution Shift](https://doi.org/10.48550/arXiv.2601.06967) | arXiv | — | 0 |
| Hengliang Wu et al. | [Certified Unlearning in Decentralized Federated Learning](https://doi.org/10.48550/arXiv.2601.06436) | arXiv | — | 0 |
| Nausherwan Malik, Z. Khalid, Muhammad Faryad | [Distribution-Guided and Constrained Quantum Machine Unlearning](https://doi.org/10.48550/arXiv.2601.04413) | arXiv | — | 0 |
| Intae Jeon, Yujeong Kwon, Hyungjoon Koo | [UnPII: Unlearning Personally Identifiable Information with Quantifiable Exposure Risk](https://doi.org/10.48550/arXiv.2601.01786) | arXiv | [GitHub](https://github.com/ai-safety-unlearning/unpii) | 0 |
| Hongbin Lin et al. | [Controllable Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2601.00451) | arXiv | — | 0 |
| Sam Gunn | [How to sketch a learning algorithm](https://arxiv.org/abs/2604.07328) | arXiv | [GitHub](https://github.com/SamSpo1/microgpt-sketch) | 0 |
| Amber Yijia Zheng, Yue Tai, Raymond A. Yeh | [Designing to Forget: Deep Semi-parametric Models for Unlearning](https://arxiv.org/abs/2603.22870) | arXiv | [GitHub](https://github.com/amberyzheng/spm_unlearning) | 0 |
| Aloni Cohen et al. | [Protecting the Undeleted in Machine Unlearning](https://doi.org/10.48550/arXiv.2602.16697) | arXiv | — | 0 |
| Hanna Benarroch, Jamal Atif, Olivier Capp'e | [Certified Per-Instance Unlearning Using Individual Sensitivity Bounds](https://doi.org/10.48550/arXiv.2602.15602) | arXiv | — | 0 |
| Jacob L. Block et al. | [Temper-Then-Tilt: Principled Unlearning for Generative Models through Tempering and Classifier Guidance](https://doi.org/10.48550/arXiv.2602.10217) | arXiv | — | 0 |
| Sangyeon Yoon et al. | [Rethinking Benign Relearning: Syntax as the Hidden Driver of Unlearning Failures](https://doi.org/10.48550/arXiv.2602.03379) | arXiv | [HF](https://huggingface.co/locuslab/tofu_ft_llama2-7b) | 0 |
| Pawel Batorski, Paul Swoboda | [EvoMU: Evolutionary Machine Unlearning](https://doi.org/10.48550/arXiv.2602.02139) | arXiv | [GitHub](https://github.com/Batorskq/EvoMU) | 0 |
| Polina Dolgova, Sebastian U. Stich | [Sequential Subspace Noise Injection Prevents Accuracy Collapse in Certified Unlearning](https://doi.org/10.48550/arXiv.2601.05134) | arXiv | [GitHub](https://github.com/mlolab/blockwise-noisy-fine-tuning) | 0 |
| Hsiang Hsu et al. | [A RE W E R EALLY U NLEARNING ? T HE P RESENCE OF R ESIDUAL K NOWLEDGE IN M ACHINE U NLEARNING](https://arxiv.org/abs/2601.22359) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Kairan Zhao, Iurie Luca, Peter Triantafillou | [Benchmarking Unlearning for Vision Transformers](https://doi.org/10.48550/arXiv.2602.20114) | arXiv | — | 0 |
| Wei-Kai Chang, Rajiv Khanna | [Why Some Models Resist Unlearning: A Linear Stability Perspective](https://doi.org/10.48550/arXiv.2602.02986) | arXiv | — | 0 |
| Y. Jang et al. | [Suppression or Deletion: A Restoration-Based Representation-Level Analysis of Machine Unlearning](https://doi.org/10.1145/3774904.3792896) | arXiv | [HF](https://huggingface.co/Yurim0507/suppression-or-deletion) | 0 |
| Zixu Li et al. | [ConeSep: Cone-based Robust Noise-Unlearning Compositional Network for Composed Image Retrieval](https://arxiv.org/abs/2604.20358) | arXiv | [GitHub](https://github.com/Lee-zixu/ConeSep) | 0 |
| M'onica Ribero, Antonin Schrab, Arthur Gretton | [Regularized f-Divergence Kernel Tests](https://doi.org/10.48550/arXiv.2601.19755) | arXiv | — | 0 |
| Jagadeesh Rachapudi et al. | [BID-LoRA: A Parameter-Efficient Framework for Continual Learning and Unlearning](https://arxiv.org/abs/2604.12686) | arXiv | [GitHub](https://github.com/shaokangW/LLM-wisdom) | 0 |
| Piotr W'ojcik et al. | [UnHype: CLIP-Guided Hypernetworks for Dynamic LoRA Unlearning](https://doi.org/10.48550/arXiv.2602.03410) | arXiv | [GitHub](https://github.com/gmum/UnHype) | 0 |
| Eric K. Easley, Sebastian Farquhar | [Latent Instruction Representation Alignment: defending against jailbreaks, backdoors and undesired knowledge in LLMs](https://arxiv.org/abs/2604.10403) | arXiv | — | 0 |
| P. Rybak et al. | [REBEL: Hidden Knowledge Recovery via Evolutionary-Based Evaluation Loop](https://doi.org/10.48550/arXiv.2602.06248) | arXiv | [GitHub](https://github.com/patryk-rybak/REBEL) | 0 |
| Yejin Kim et al. | [Knowledge Vector Weakening: Efficient Training-free Unlearning for Large Vision-Language Models](https://doi.org/10.48550/arXiv.2601.21794) | arXiv | — | 0 |
| Tyler Lizzo, Larry Heck | [Evaluating Cross-Lingual Unlearning in Multilingual Language Models](https://doi.org/10.48550/arXiv.2601.06675) | arXiv | — | 0 |
| Yuze Wang et al. | [Sparsity-Aware Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2602.00577) | arXiv | — | 0 |
| Anna Mazhar, Sainyam Galhotra | [Towards Reliable Testing of Machine Unlearning](https://doi.org/10.1145/3803437.3805557) | arXiv | — | 0 |
| Jialong Sun et al. | [Statistical MIA: Rethinking Membership Inference Attack for Reliable Unlearning Auditing](https://doi.org/10.48550/arXiv.2602.01150) | arXiv | — | 0 |
| Ning Lin et al. | [Resistive Memory based Efficient Machine Unlearning and Continual Learning](https://doi.org/10.48550/arXiv.2601.10037) | arXiv | — | 0 |
| N. Konovalova, Andrey Kuznetsov, Aibek Alanov | [SHIFT: Steering Hidden Intermediates in Flow Transformers](https://arxiv.org/abs/2604.09213) | arXiv | [GitHub](https://github.com/ControlGenAI/SHIFT) | 0 |
| Xian Yang et al. | [SafeRoPE: Risk-specific Head-wise Embedding Rotation for Safe Generation in Rectified Flow Transformers](https://arxiv.org/abs/2604.01826) | arXiv | [GitHub](https://github.com/deng12yx/SafeRoPE) | 0 |
| Yi-Yang Xie, Zheng Zhang, Ping Liu | [PROBE: Diagnosing Residual Concept Capacity in Erased Text-to-Video Diffusion Models](https://arxiv.org/abs/2603.21547) | arXiv | [GitHub](https://github.com/YiweiXie/PRObingBasedEvaluation) | 0 |
| Shingo Kodama et al. | [Understanding Empirical Unlearning with Combinatorial Interpretability](https://doi.org/10.48550/arXiv.2602.19215) | arXiv | — | 0 |
| Tong Zhang, Ru Zhang, Jianyi Liu | [DICE: Disentangling Artist Style from Content via Contrastive Subspace Decomposition in Diffusion Models](https://doi.org/10.48550/arXiv.2602.08059) | arXiv | — | 0 |
| Natnael Mola et al. | [SPARE: Self-distillation for PARameter-Efficient Removal](https://arxiv.org/abs/2602.07058) | arXiv | [GitHub](https://github.com/AtharvaTaras/Dog-Breeds-Dataset) | 0 |
| Mengyu Sun et al. | [LURE: Latent Space Unblocking for Multi-Concept Reawakening in Diffusion Models](https://doi.org/10.48550/arXiv.2601.14330) | arXiv | — | 0 |
| Carolina R. Kelsch et al. | [FADE: Selective Forgetting via Sparse LoRA and Self-Distillation](https://doi.org/10.48550/arXiv.2602.07058) | arXiv | — | 0 |
| Pierre Lubitzsch, M. D. Rijke, Sebastian Schelter | [ERASE -- A Real-World Aligned Benchmark for Unlearning in Recommender Systems](https://arxiv.org/abs/2603.08341) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Heng Xu et al. | [Forgetting Similar Samples: Can Machine Unlearning Do it Better?](https://doi.org/10.48550/arXiv.2601.06938) | arXiv | [HF](https://huggingface.co/BAAI/bge-small-en) | 0 |
| Roy Rinberg et al. | [Easy Data Unlearning Bench](https://openalex.org/W7130617389) | arXiv | [GitHub](https://github.com/easydub/EasyDUB-code) | 0 |
| Aviraj Newatia et al. | [Mitigating Privacy Risk via Forget Set-Free Unlearning](https://openalex.org/W7154539444) | arXiv | [GitHub](https://github.com/projectavi/reload-unlearning) | 0 |
| Tuan Le, Wei Qian, Mengdi Huai | [Selective Forgetting for Large Reasoning Models](https://openalex.org/W7152331662) | arXiv | — | 0 |
| Xiaoyu Xu et al. | [FIT: Defying Catastrophic Forgetting in Continual LLM Unlearning](https://openalex.org/W7126281756) | arXiv | [GitHub](https://github.com/XiaoyuXU1/FIT) | 0 |
| Yisheng Zhong, Zhengbang Yang, Zhuangdi Zhu | [DUET: Distilled LLM Unlearning from an Efficiently Contextualized Teacher](https://openalex.org/W7126281531) | arXiv | — | 0 |
| Mohammad Partohaghighi et al. | [Statistical Roughness-Informed Machine Unlearning](https://openalex.org/W7128648791) | arXiv | — | 0 |
| Borisiuk Anna et al. | [Anatomy of Unlearning: The Dual Impact of Fact Salience and Model Fine-Tuning](https://openalex.org/W7131475538) | arXiv | [GitHub](https://github.com/Anya-wUw/DUET) | 0 |
| Zhengbang Yang et al. | [CATNIP: LLM Unlearning via Calibrated and Tokenized Negative Preference Alignment](https://openalex.org/W7127739571) | arXiv | — | 0 |
| Chahana Dahal, A. Balasubramaniam, Zuobin Xiong | [GONE: Structural Knowledge Unlearning via Neighborhood-Expanded Distribution Shaping](https://openalex.org/W7138824740) | arXiv | — | 0 |
| Himanshu Mishra, Kanwal Mehreen | [QUAIL: Quantization Aware Unlearning for Mitigating Misinformation in LLMs](https://openalex.org/W7125566883) | arXiv | — | 0 |
| Zhuo Huang et al. | [Is Gradient Ascent Really Necessary? Memorize to Forget for Machine Unlearning](https://openalex.org/W7128408257) | arXiv | [GitHub](https://github.com/crayon-go/machine-unlearning-papers) | 0 |
| Ningkang Peng et al. | [Don't Break the Boundary: Continual Unlearning for OOD Detection Based on Free Energy Repulsion](https://openalex.org/W7128408729) | arXiv | — | 0 |
| Zezheng Wu et al. | [U-CAN: Utility-Aware Contrastive Attenuation for Efficient Unlearning in Generative Recommendation](https://openalex.org/W7133267654) | arXiv | — | 0 |
| Yuze Cai et al. | [Prototype-Guided Concept Erasure in Diffusion Models](https://openalex.org/W7134860807) | arXiv | [GitHub](https://github.com/Cocteau-23/Prototype-Guided-Concept-Erasure) | 0 |
| Jiahang Tu et al. | [Mass Concept Erasure in Diffusion Models with Concept Hierarchy](https://openalex.org/W7119557765) | arXiv | — | 0 |
| Chi Zhang et al. | [Closed-Form Concept Erasure via Double Projections](https://openalex.org/W7154540164) | arXiv | — | 0 |
| Chuancheng Shi et al. | [OrthoEraser: Coupled-Neuron Orthogonal Projection for Concept Erasure](https://openalex.org/W7135428732) | arXiv | — | 0 |
| Jiang, Nanxiang et al. | [Z-Erase: Enabling Concept Erasure in Single-Stream Diffusion Transformers](https://openalex.org/W7142557640) | arXiv | — | 0 |
| Zhiqi Zhang et al. | [Differential Vector Erasure: Unified Training-Free Concept Erasure for Flow Matching Models](https://openalex.org/W7127540966) | arXiv | — | 0 |
| Zhuan Shi et al. | [Neighbor-Aware Localized Concept Erasure in Text-to-Image Diffusion Models](https://openalex.org/W7144391460) | arXiv | [GitHub](https://github.com/alirezafarashah/NLCE) | 0 |
| Junyeong Ahn, Seojin Yoon, Sungyong Baik | [EGLOCE: Training-Free Energy-Guided Latent Optimization for Concept Erasure](https://openalex.org/W7154427278) | arXiv | — | 0 |
| Jian Weng et al. | [M-ErasureBench: A Comprehensive Multimodal Evaluation Benchmark for Concept Erasure in Diffusion Models](https://doi.org/10.1109/wacv61042.2026.00059) | arXiv | — | 0 |
| Jun Li et al. | [Beyond Text Prompts: Precise Concept Erasure through Text-Image Collaboration](https://openalex.org/W7155246965) | arXiv | [GitHub](https://github.com/OpenAscent-L/TICoE) | 0 |
| Yi Sun et al. | [ActErase: A Training-Free Paradigm for Precise Concept Erasure via Activation Patching](https://openalex.org/W7119234231) | arXiv | — | 0 |
| Zhaoxin Fan et al. | [EraseAnything++: Enabling Concept Erasure in Rectified Flow Transformers Leveraging Multi-Object Optimization](https://openalex.org/W7133365320) | arXiv | — | 0 |
| Yongwoo Kim et al. | [Consistency-Preserving Concept Erasure via Unsafe-Safe Pairing and Directional Fisher-weighted Adaptation](https://openalex.org/W7128096000) | arXiv | — | 0 |
| Fengpeng Li et al. | [AEGIS: Adversarial Target-Guided Retention-Data-Free Robust Concept Erasure from Diffusion Models](https://openalex.org/W7128409028) | arXiv | [GitHub](https://github.com/Feng-peng-Li/AEGIS) | 0 |
| Mansi et al. | [Selective Fine-Tuning for Targeted and Robust Concept Unlearning](https://openalex.org/W7128555226) | arXiv | — | 0 |
| Kaiyuan Deng et al. | [Forget Many, Forget Right: Scalable and Precise Concept Unlearning in Diffusion Models](https://openalex.org/W7124118418) | arXiv | — | 0 |
| Zhangyun Tan et al. | [Can VLMs Truly Forget? Benchmarking Training-Free Visual Concept Unlearning](https://openalex.org/W7151672898) | arXiv | — | 0 |
| Yong Zou et al. | [REFORGE: Multi-modal Attacks Reveal Vulnerable Concept Unlearning in Image Generation Models](https://openalex.org/W7139148237) | arXiv | [GitHub](https://github.com/Imfatnoily/REFORGE) | 0 |
| Kaiyuan Deng et al. | [Forget-It-All: Multi-Concept Machine Unlearning via Concept-Aware Neuron Masking](https://openalex.org/W7124117424) | arXiv | [GitHub](https://github.com/kaiyuan02415/Forget-It-All) | 0 |
| Junfeng Liao et al. | [Explainable LLM Unlearning Through Reasoning](https://openalex.org/W7135156775) | arXiv | [GitHub](https://github.com/crayon-go/machine-unlearning-papers) | 0 |
| Zeguan Xiao et al. | [Representation-Guided Parameter-Efficient LLM Unlearning](https://openalex.org/W7155246687) | arXiv | [GitHub](https://github.com/Jacksooooff/reglu-open) | 0 |
| Raj Sanjay Shah et al. | [The Unlearning Mirage: A Dynamic Framework for Evaluating LLM Unlearning](https://openalex.org/W7135428587) | arXiv | — | 0 |
| Haoran Tang, Rajiv Khanna | [From Logits to Latents: Contrastive Representation Shaping for LLM Unlearning](https://openalex.org/W7126281433) | arXiv | — | 0 |
| Zeguan Xiao et al. | [Modeling LLM Unlearning as an Asymmetric Two-Task Learning Problem](https://openalex.org/W7154865541) | arXiv | [GitHub](https://github.com/shaokangW/LLM-wisdom) | 0 |
| João Vitor Boer Abitante et al. | [Quantization-Robust LLM Unlearning via Low-Rank Adaptation](https://openalex.org/W7129180976) | arXiv | [GitHub](https://github.com/JoaoVitorBoer/Quantization-Robust-LoRA-Unlearning) | 0 |
| Xiaoyu Xu et al. | [From Domains to Instances: Dual-Granularity Data Synthesis for LLM Unlearning](https://openalex.org/W7120272108) | arXiv | [GitHub](https://github.com/XiaoyuXU1/Biforget) | 0 |
| Ziwen Liu et al. | [Randomized Antipodal Search Done Right for Data Pareto Improvement of LLM Unlearning](https://openalex.org/W7155245215) | arXiv | — | 0 |
| Yisheng Zhong, Sijia Liu, Zhuangdi Zhu | [Harmonizing Multi-Objective LLM Unlearning via Unified Domain Representation and Bidirectional Logit Distillation](https://openalex.org/W7155245269) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Hadi Reisizadeh et al. | [BLUR: A Bi-Level Optimization Approach for LLM Unlearning](https://doi.org/10.18653/v1/2026.eacl-long.331) | arXiv | [GitHub](https://github.com/OptimAI-Lab/BLURLLMUnlearning) | 0 |
| Ruihao Pan, Suhang Wang | [A Comprehensive Evaluation of LLM Unlearning Robustness under Multi-Turn Interaction](https://openalex.org/W7133365277) | arXiv | — | 0 |
| Naixin Zhai et al. | [Maximizing Local Entropy Where It Matters: Prefix-Aware Localized LLM Unlearning](https://openalex.org/W7119233483) | arXiv | [GitHub](https://github.com/nxZhai/PALU) | 0 |
| McKinney, Lev et al. | [Gauss-Newton Unlearning for the LLM Era](https://openalex.org/W7128745817) | arXiv | [GitHub](https://github.com/crayon-go/machine-unlearning-papers) | 0 |
| Chenchen Tan et al. | [Less is More: Geometric Unlearning for LLMs with Minimal Data Disclosure](https://openalex.org/W7160457692) | arXiv | [GitHub](https://github.com/CCT-sys/GU) | 0 |
| Zhaokun Wang et al. | [CAP: Controllable Alignment Prompting for Unlearning in LLMs](https://openalex.org/W7155653947) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Esen Kurt, Haithem Afli | [Operationalising the Right to be Forgotten in LLMs: A Lightweight Sequential Unlearning Framework for Privacy-Aligned Deployment in Politically Sensitive Environments](https://openalex.org/W7154655266) | arXiv | — | 0 |
| Xunlei Chen et al. | [ALTER: Asymmetric LoRA for Token-Entropy-Guided Unlearning of LLMs](https://openalex.org/W7133365542) | arXiv | — | 0 |
| Tyler Lizzo, Larry Heck | [Unlearning in LLMs: Methods, Evaluation, and Open Challenges](https://openalex.org/W7125352447) | arXiv | — | 0 |
| Ziheng Chen et al. | [CURE:Circuit-Aware Unlearning for LLM-based Recommendation](https://openalex.org/W7152933875) | arXiv | — | 0 |
| Bin Wang et al. | [Agentic Unlearning: When LLM Agent Meets Machine Unlearning](https://openalex.org/W7131191319) | arXiv | — | 0 |
| Yangyang Guo et al. | [LLMs Can Unlearn Refusal with Only 1,000 Benign Samples](https://openalex.org/W7126001464) | arXiv | [GitHub](https://github.com/guoyang9/refusal-unlearning) | 0 |
| Dayong Ye et al. | [Secure Forgetting: A Framework for Privacy-Driven Unlearning in Large Language Model (LLM)-Based Agents](https://openalex.org/W7149209636) | arXiv | — | 0 |
| Si Qi Goh et al. | [FROC: A Unified Framework with Risk-Optimized Control for Machine Unlearning in LLMs](https://doi.org/10.1109/icaiic68212.2026.11454224) | arXiv | — | 0 |
| Vishnu Narayanan Anilkumar et al. | [Relationship-Aware Safety Unlearning for Multimodal LLMs](https://openalex.org/W7139146858) | arXiv | — | 0 |
| Yuze Wang et al. | [SAU: Sparsity-Aware Unlearning for LLMs via Gradient Masking and Importance Redistribution](https://openalex.org/W7127541260) | arXiv | — | 0 |
| Xinjie Zhou et al. | [Data-Free Privacy-Preserving for LLMs via Model Inversion and Selective Unlearning](https://openalex.org/W7125566882) | arXiv | — | 0 |
| Dinesh Srivasthav P et al. | [Shadow Unlearning: A Neuro-Semantic Approach to Fidelity-Preserving Faceless Forgetting in LLMs](https://openalex.org/W7120272359) | arXiv | — | 0 |
| Seyun Bae, Seokhan Lee, Eunho Yang | [CURaTE: Continual Unlearning in Real Time with Ensured Preservation of LLM Knowledge](https://openalex.org/W7154865273) | arXiv | — | 0 |
| Joseph Spracklen et al. | [LLM Ghostbusters: Surgical Hallucination Suppression via Adaptive Unlearning](https://openalex.org/W7160457743) | arXiv | — | 0 |
| Xianya Fang et al. | [Beyond Superficial Unlearning: Sharpness-Aware Robust Erasure of Hallucinations in Multimodal LLMs](https://openalex.org/W7125759759) | arXiv | — | 0 |
| Alireza dehghanpour farashah et al. | [Multilingual Amnesia: On the Transferability of Unlearning in Multilingual LLMs](https://openalex.org/W7123371394) | arXiv | [GitHub](https://github.com/alirezafarashah/multilingual_unlearning) | 0 |
| Eugenia Iofinova, Dan Alistarh | [Behemoth: Benchmarking Unlearning in LLMs Using Fully Synthetic Data](https://openalex.org/W7127202974) | arXiv | [GitHub](https://github.com/IST-DASLab/behemoth) | 0 |
| Pengyang Shao et al. | [BalDRO: A Distributionally Robust Optimization based Framework for Large Language Model Unlearning](https://openalex.org/W7124358576) | arXiv | — | 0 |
| Chengyi Cai et al. | [Per-parameter Task Arithmetic for Unlearning in Large Language Models](https://openalex.org/W7126281625) | arXiv | — | 0 |
| Ce Fang et al. | [KUDA: Knowledge Unlearning by Deviating Representation for Large Language Models](https://openalex.org/W7131319924) | arXiv | — | 0 |
| Efstratios Zaradoukas, Bardh Prenkaj, Gjergji Kasneci | [Reinforcement Unlearning via Group Relative Policy Optimization](https://openalex.org/W7126123351) | arXiv | [GitHub](https://github.com/strzar/purge) | 0 |
| Tien Dang et al. | [Beyond Forgetting: Machine Unlearning Elicits Controllable Side Behaviors and Capabilities](https://openalex.org/W7126281564) | arXiv | — | 0 |
| Jingjing Zhou et al. | [STaR: Sensitive Trajectory Regulation for Unlearning in Large Reasoning Models](https://openalex.org/W7124358332) | arXiv | — | 0 |
| Wenxuan Li et al. | [From Anchors to Supervision: Memory-Graph Guided Corpus-Free Unlearning for Large Language Models](https://openalex.org/W7154790022) | arXiv | [GitHub](https://github.com/shaokangW/LLM-wisdom) | 0 |
| Chengyi Cai et al. | [Visual-Guided Key-Token Regularization for Multimodal Large Language Model Unlearning](https://openalex.org/W7126281284) | arXiv | — | 0 |
| Jiajia Song, Zhihan Guo, Jionghao Lin | [Simulating Novice Students Using Machine Unlearning and Relearning in Large Language Models](https://openalex.org/W7148176027) | arXiv | — | 0 |
| Mutsumi Sasaki et al. | [Exclusive Unlearning](https://openalex.org/W7152934100) | arXiv | — | 0 |
| Xingjian Zhao, Mohammad Mohammadi Amiri, Malik Magdon‐Ismail | [WIN-U: Woodbury-Informed Newton-Unlearning as a retain-free Machine Unlearning Framework](https://openalex.org/W7154789827) | arXiv | — | 0 |
| Taoran Li, Varun Chandrasekaran, Zhiyuan Yu | [Layer-Targeted Multilingual Knowledge Erasure in Large Language Models](https://openalex.org/W7131910508) | arXiv | — | 0 |
| Jagadeesh Rachapudi et al. | [RePAIR: Interactive Machine Unlearning through Prompt-Aware Model Repair](https://openalex.org/W7154655914) | arXiv | [GitHub](https://github.com/shaokangW/LLM-wisdom) | 0 |
| Xiaoyi Chen et al. | [PrivUn: Unveiling Latent Ripple Effects and Shallow Forgetting in Privacy Unlearning](https://openalex.org/W7157506111) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Zhifei Luo et al. | [Signed Graph Unlearning](https://doi.org/10.1109/icassp55912.2026.11465012) | arXiv | — | 0 |
| Pengfei Ding, Yan Wang, Guanfeng Liu | [Re-understanding Graph Unlearning through Memorization](https://openalex.org/W7125459617) | arXiv | — | 0 |
| Renqiang Luo et al. | [FairGU: Fairness-aware Graph Unlearning in Social Networks](https://openalex.org/W7124357960) | arXiv | [GitHub](https://github.com/LuoRenqiang/FairGU) | 0 |
| Jiahao Zhang, Yilong Wang, Suhang Wang | [Attack by Unlearning: Unlearning-Induced Adversarial Attacks on Graph Neural Networks](https://openalex.org/W7140001031) | arXiv | — | 0 |
| Ruotong Ma et al. | [Graph Federated Unlearning for Privacy Preservation](https://openalex.org/W7160457536) | arXiv | — | 0 |
| Shreyansh Pathak, Jyotishman Das | [Graph Propagated Projection Unlearning: A Unified Framework for Vision and Audio Discriminative Models](https://openalex.org/W7154789976) | arXiv | — | 0 |
| Parthaw Goswami, Md Khairul Islam, Ashfak Yeafi | [PrivEraserVerify: Efficient, Private, and Verifiable Federated Unlearning](https://openalex.org/W7154655698) | arXiv | — | 0 |
| Zhaoyuan Cai, Xinglin Zhang | [Asynchronous Federated Unlearning with Invariance Calibration for Medical Imaging](https://openalex.org/W7159733910) | arXiv | — | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Jellyfish: Zero-Shot Federated Unlearning Scheme with Knowledge Disentanglement](https://openalex.org/W7152330923) | arXiv | [GitHub](https://github.com/xiao-jian-zi/Jellyfish) | 0 |
| Houzhe Wang, Xiaojie Zhu, Chi Chen | [Forgetting to Witness: Efficient Federated Unlearning and Its Visible Evaluation](https://openalex.org/W7152330399) | arXiv | [GitHub](https://github.com/xiao-jian-zi/Forgetting-to-Witness) | 0 |
| Yuhua Xu et al. | [Client-Verifiable and Efficient Federated Unlearning in Low-Altitude Wireless Networks](https://openalex.org/W7148176558) | arXiv | — | 0 |
| Yue Li et al. | [FedCARE: Federated Unlearning with Conflict-Aware Projection and Relearning-Resistant Recovery](https://openalex.org/W7127203047) | arXiv | — | 0 |
| Radmehr Karimian et al. | [$f$-FUM: Federated Unlearning via min--max and $f$-divergence](https://openalex.org/W7128408790) | arXiv | — | 0 |
| Minh-Duong Nguyen et al. | [Computation and Communication Efficient Federated Unlearning via On-server Gradient Conflict Mitigation and Expression](https://openalex.org/W7139146923) | arXiv | — | 0 |
| Wenwei Zhao et al. | [Adversarial Update-Based Federated Unlearning for Poisoned Model Recovery](https://openalex.org/W7160458511) | arXiv | — | 0 |
| Jer Shyuan Ng et al. | [Federated Unlearning in Edge Networks: A Survey of Fundamentals, Challenges, Practical Applications and Future Directions](https://openalex.org/W7124513638) | arXiv | — | 0 |
| Zihao Ding, Beining Wu, Jun Huang | [EASE: Federated Multimodal Unlearning via Entanglement-Aware Anchor Closure](https://openalex.org/W7160360615) | arXiv | — | 0 |
| Mykola Vysotskyi et al. | [Critic-Guided Reinforcement Unlearning in Text-to-Image Diffusion](https://openalex.org/W7119234376) | arXiv | — | 0 |
| K. Lee et al. | [Unlearning the Unpromptable: Prompt-free Instance Unlearning in Diffusion Models](https://openalex.org/W7135428884) | arXiv | — | 0 |
| Ashutosh Ranjan et al. | [Forgetting is Competition: Rethinking Unlearning as Representation Interference in Diffusion Models](https://openalex.org/W7133364018) | arXiv | — | 0 |
| Arian Komaei Koma et al. | [Erasure or Erosion? Evaluating Compositional Degradation in Unlearned Text-To-Image Diffusion Models](https://openalex.org/W7152331207) | arXiv | — | 0 |
| Manyi Li et al. | [The Illusion of Forgetting: Attack Unlearned Diffusion via Initial Latent Variable Optimization](https://openalex.org/W7127541489) | arXiv | — | 0 |
| Ravi Ranjan et al. | [RAZOR: Ratio-Aware Layer Editing for Targeted Unlearning in Vision Transformers and Diffusion Models](https://openalex.org/W7139145009) | arXiv | — | 0 |
| Aljalila Aladawi, Mohammed Talha Alam, Fakhri Karray | [Projected Gradient Unlearning for Text-to-Image Diffusion Models: Defending Against Concept Revival Attacks](https://openalex.org/W7155653878) | arXiv | — | 0 |
| Ci Zhang et al. | [Roots Beneath the Cut: Uncovering the Risk of Concept Revival in Pruning-Based Unlearning for Diffusion Models](https://openalex.org/W7134860773) | arXiv | — | 0 |
| Naoki MURATA et al. | [GUDA: Counterfactual Group-wise Training Data Attribution for Diffusion Models via Unlearning](https://openalex.org/W7127203299) | arXiv | — | 0 |
| Xinwen Cheng et al. | [Compensation-free Machine Unlearning in Text-to-Image Diffusion Models by Eliminating the Mutual Information](https://openalex.org/W7133365497) | arXiv | — | 0 |
| Ignacy Kolton et al. | [ReLAPSe: Reinforcement-Learning-trained Adversarial Prompt Search for Erased concepts in unlearned diffusion models](https://openalex.org/W7127541233) | arXiv | [GitHub](https://github.com/gmum/ReLaPSe) | 0 |
| Xiang, Qianlong et al. | [TINA: Text-Free Inversion Attack for Unlearned Text-to-Image Diffusion Models](https://openalex.org/W7139148366) | arXiv | [GitHub](https://github.com/iLearn-Lab/CVPR26-TINA) | 0 |
| Zhiyong Ma et al. | [PECKER: A Precisely Efficient Critical Knowledge Erasure Recipe For Machine Unlearning in Diffusion Models](https://openalex.org/W7152933393) | arXiv | — | 0 |
| Hyundo Choi et al. | [Unlearning for One-Step Generative Models via Unbalanced Optimal Transport](https://openalex.org/W7139146611) | arXiv | — | 0 |
| Zhanting Zhou et al. | [TRU: Targeted Reverse Update for Efficient Multimodal Recommendation Unlearning](https://openalex.org/W7149873605) | arXiv | — | 0 |
| Liang Qu et al. | [Federated Learning and Unlearning for Recommendation with Personalized Data Sharing](https://openalex.org/W7135428477) | arXiv | — | 0 |

## 2025

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Sijia Liu et al. | [Rethinking machine unlearning for large language models](https://doi.org/10.1038/s42256-025-00985-0) | Nature Machine Intelligence | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 59 |
| Chongyu Fan et al. | [Towards LLM Unlearning Resilient to Relearning Attacks: A Sharpness-Aware Minimization Perspective and Beyond](https://doi.org/10.48550/arXiv.2502.05374) | ICML | [GitHub](https://github.com/OPTML-Group/Unlearn-Smooth) | 53 |
| Fazl Barez et al. | [Open Problems in Machine Unlearning for AI Safety](https://doi.org/10.48550/arXiv.2501.04952) | arXiv | — | 53 |
| Thành Tâm Nguyên et al. | [A Survey of Machine Unlearning](https://doi.org/10.1145/3749987) | ACM TIST | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 52 |
| Bartosz Cywi'nski, Kamil Deja | [SAeUron: Interpretable Concept Unlearning in Diffusion Models with Sparse Autoencoders](https://doi.org/10.48550/arXiv.2501.18052) | ICML | [GitHub](https://github.com/cywinski/SAeUron) | 51 |
| Qizhou Wang et al. | [Rethinking LLM Unlearning Objectives: A Gradient Perspective and Go Beyond](https://doi.org/10.48550/arXiv.2502.19301) | ICLR | [GitHub](https://github.com/QizhouWang/G-effect) | 49 |
| Vineeth Dorna et al. | [OpenUnlearning: Accelerating LLM Unlearning via Unified Benchmarking of Methods and Metrics](https://doi.org/10.48550/arXiv.2506.12618) | arXiv | [GitHub](https://github.com/huggingface/accelerate) | 34 |
| Martin Tutek et al. | [Measuring Chain of Thought Faithfulness by Unlearning Reasoning Steps](https://doi.org/10.18653/v1/2025.emnlp-main.504) | EMNLP | [HF](https://huggingface.co/spaces/richardyoung/abliteration-methods-dashboard) | 32 |
| Puning Yang et al. | [Exploring Criteria of Loss Reweighting to Enhance LLM Unlearning](https://doi.org/10.48550/arXiv.2505.11953) | ICML | [GitHub](https://github.com/tmlr-group/SatImp) | 30 |
| Jiahui Geng et al. | [A Comprehensive Survey of Machine Unlearning Techniques for Large Language Models](https://doi.org/10.48550/arXiv.2503.01854) | arXiv | [GitHub](https://github.com/jujingliuzy/Unlearning-LLM-papers) | 27 |
| Anh-Vu Bui et al. | [Fantastic Targets for Concept Erasure in Diffusion Models and Where To Find Them](https://doi.org/10.48550/arXiv.2501.18950) | ICLR | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 26 |
| Anil Ramakrishna et al. | [LUME: LLM Unlearning with Multitask Evaluations](https://doi.org/10.48550/arXiv.2502.15097) | EMNLP | [GitHub](https://github.com/amazon-science/lume-llm-unlearning) | 25 |
| Jiahao Huo et al. | [MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2502.11051) | ACL | [GitHub](https://github.com/Z1zs/MMUnlearner) | 24 |
| Ziyao Liu et al. | [Threats, Attacks, and Defenses in Machine Unlearning: A Survey](https://doi.org/10.1109/ojcs.2025.3543483) | IEEE Open Journal of the Computer Society | — | 24 |
| Zijie Pan et al. | [Feature-Based Machine Unlearning for Vertical Federated Learning in IoT Networks](https://doi.org/10.1109/tmc.2025.3530529) | IEEE TMC | — | 24 |
| Junkai Chen et al. | [SafeEraser: Enhancing Safety in Multimodal Large Language Models through Multimodal Machine Unlearning](https://doi.org/10.48550/arXiv.2502.12520) | ACL | — | 23 |
| XiaoYu Xu et al. | [Unlearning Isn't Deletion: Investigating Reversibility of Machine Unlearning in LLMs](https://doi.org/10.48550/arXiv.2505.16831) | arXiv | [GitHub](https://github.com/XiaoyuXU1/Representational_Analysis_Tools) | 23 |
| Meng Li, Haochen Sui | [Causal Recommendation via Machine Unlearning with a Few Unbiased Data](https://www.semanticscholar.org/paper/9d69eebef7cd41b4d6f480ab438268f848920215) | AAAI Workshop on Artificial Intelligence with Causal Techniques | — | 22 |
| Zhengyi Zhong et al. | [Unlearning through Knowledge Overwriting: Reversible Federated Unlearning via Selective Sparse Adapter](https://doi.org/10.1109/CVPR52734.2025.02855) | CVPR | [GitHub](https://github.com/Zhong-Zhengyi/FUSED-Code) | 22 |
| William F. Shen et al. | [LUNAR: LLM Unlearning via Neural Activation Redirection](https://doi.org/10.48550/arXiv.2502.07218) | arXiv | [GitHub](https://github.com/facebookresearch/LUNAR) | 22 |
| Ouxiang Li et al. | [SPEED: Scalable, Precise, and Efficient Concept Erasure for Diffusion Models](https://doi.org/10.48550/arXiv.2503.07392) | arXiv | [GitHub](https://github.com/Ouxiang-Li/SPEED) | 22 |
| Yu Zhou et al. | [Decoupled Distillation to Erase: A General Unlearning Method for Any Class-centric Tasks](https://doi.org/10.1109/CVPR52734.2025.01895) | CVPR | — | 21 |
| Naveen George et al. | [The Illusion of Unlearning: The Unstable Nature of Machine Unlearning in Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.01250) | CVPR | [GitHub](https://github.com/DIL-IITH/TIU) | 21 |
| Na Li et al. | [Machine Unlearning: Taxonomy, Metrics, Applications, Challenges, and Prospects](https://doi.org/10.1109/tnnls.2025.3530988) | IEEE TNNLS | [GitHub](https://github.com/Carol-gutianle/Awesome-llm-unlearning) | 21 |
| Aashiq Muhamed et al. | [SAEs Can Improve Unlearning: Dynamic Sparse Autoencoder Guardrails for Precision Unlearning in LLMs](https://doi.org/10.48550/arXiv.2504.08192) | arXiv | [GitHub](https://github.com/aashiqmuhamed/DynamicSAEGuardrails) | 19 |
| Alberto Blanco-Justicia et al. | [Digital forgetting in large language models: a survey of unlearning methods](https://doi.org/10.1007/s10462-024-11078-6) | Artificial Intelligence Review | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 18 |
| Byung Hyun Lee, Sungjin Lim, Se Young Chun | [Localized Concept Erasure for Text-to-Image Diffusion Models Using Training-Free Gated Low-Rank Adaptation](https://doi.org/10.1109/CVPR52734.2025.01733) | CVPR | [GitHub](https://github.com/Hyun1A/GLoCE) | 18 |
| Haoming Xu et al. | [ReLearn: Unlearning via Learning for Large Language Models](https://doi.org/10.48550/arXiv.2502.11190) | ACL | [GitHub](https://github.com/zjunlp/unlearn) | 17 |
| Byung Hyun Lee et al. | [Concept Pinpoint Eraser for Text-to-image Diffusion Models via Residual Attention Gate](https://doi.org/10.48550/arXiv.2506.22806) | ICLR | [GitHub](https://github.com/Hyun1A/CPE) | 17 |
| Yasser H. Khalil et al. | [NoT: Federated Unlearning via Weight Negation](https://doi.org/10.1109/CVPR52734.2025.02399) | CVPR | [GitHub](https://github.com/mahdibeit/mahdibeit) | 16 |
| Zihao Wang et al. | [ACE: Anti-Editing Concept Erasure in Text-to-Image Models](https://doi.org/10.48550/arXiv.2501.01633) | CVPR | [GitHub](https://github.com/120l020904/ace) | 16 |
| Youyang Qu et al. | [The Frontier of Data Erasure: A Survey on Machine Unlearning for Large Language Models](https://doi.org/10.1109/mc.2024.3405397) | Computer | — | 16 |
| Zheyuan Liu et al. | [Modality-Aware Neuron Pruning for Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2502.15910) | ACL | [GitHub](https://github.com/franciscoliu/MANU) | 15 |
| K. Thakral et al. | [Fine-Grained Erasure in Text-To-Image Diffusion-Based Foundation Models](https://doi.org/10.1109/CVPR52734.2025.00852) | CVPR | — | 15 |
| Anastasia Koloskova et al. | [Certified Unlearning for Neural Networks](https://doi.org/10.48550/arXiv.2506.06985) | ICML | [GitHub](https://github.com/stair-lab/certified-unlearning-neural-networks-icml-2025) | 15 |
| Mengshu Song et al. | [Trustworthy Intelligent Networks for Low-Altitude Economy](https://doi.org/10.1109/mcom.001.2400692) | IEEE Communications Magazine | — | 15 |
| Xuhan Zuo et al. | [Federated Learning With Blockchain-Enhanced Machine Unlearning: A Trustworthy Approach](https://doi.org/10.1109/tsc.2025.3553709) | IEEE TSC | — | 15 |
| Silas Alberti et al. | [Data Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2503.01034) | ICLR | [GitHub](https://github.com/claserken/SISS) | 14 |
| Changsheng Wang et al. | [Invariance Makes LLM Unlearning Resilient Even to Unanticipated Downstream Fine-Tuning](https://doi.org/10.48550/arXiv.2506.01339) | ICML | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 14 |
| Kevin Kuo et al. | [Exact Unlearning of Finetuning Data via Model Merging at Scale](https://doi.org/10.48550/arXiv.2504.04626) | arXiv | — | 14 |
| Gaurav Patel, Qiang Qiu | [Learning to Unlearn while Retaining: Combating Gradient Conflicts in Machine Unlearning](https://doi.org/10.48550/arXiv.2503.06339) | arXiv | — | 13 |
| Zibin Pan et al. | [Federated Unlearning with Gradient Descent and Conflict Mitigation](https://doi.org/10.1609/aaai.v39i19.34181) | AAAI | [GitHub](https://github.com/zibinpan/FedOSD) | 12 |
| Jie Ren et al. | [A General Framework to Enhance Fine-tuning-based LLM Unlearning](https://doi.org/10.48550/arXiv.2502.17823) | ACL | [GitHub](https://github.com/renjie3/GRUN) | 12 |
| Christoforos N. Spartalis et al. | [LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty](https://doi.org/10.1109/CVPR52734.2025.00939) | CVPR | [GitHub](https://github.com/cspartalis/LoTUS) | 12 |
| Changsheng Wang et al. | [Reasoning Model Unlearning: Forgetting Traces, Not Just Answers, While Preserving Reasoning Skills](https://doi.org/10.48550/arXiv.2506.12963) | EMNLP | [GitHub](https://github.com/OPTML-Group/Unlearn-R2MU) | 12 |
| Yue Wang et al. | [GRU: Mitigating the Trade-off between Unlearning and Retention for Large Language Models](https://doi.org/10.48550/arXiv.2503.09117) | ICML | — | 12 |
| Hengzhu Liu et al. | [A survey on machine unlearning: Techniques and new emerged privacy risks](https://doi.org/10.1016/j.jisa.2025.104010) | Journal of Information Security and Applications | [GitHub](https://github.com/awatson246/forecast-unlearning) | 12 |
| Zeng Wang et al. | [SALAD: Systematic Assessment of Machine Unlearning on LLM-Aided Hardware Design](https://doi.org/10.1109/MLCAD65511.2025.11189152) | Workshop on Machine Learning for CAD | [GitHub](https://github.com/DfX-NYUAD/SALAD) | 12 |
| Soumyadeep Pal et al. | [LLM Unlearning Reveals a Stronger-Than-Expected Coreset Effect in Current Benchmarks](https://doi.org/10.48550/arXiv.2504.10185) | arXiv | [GitHub](https://github.com/OPTML-Group/MU-Coreset) | 12 |
| Daiheng Gao et al. | [Revoking Amnesia: RL-based Trajectory Optimization to Resurrect Erased Concepts in Diffusion Models](https://doi.org/10.48550/arXiv.2510.03302) | arXiv | [HF](https://huggingface.co/black-forest-labs/FLUX.1-dev) | 12 |
| Yongwoo Kim, Sungmin Cha, Donghyun Kim | [Are We Truly Forgetting? A Critical Re-examination of Machine Unlearning Evaluation Protocols](https://doi.org/10.1016/j.engappai.2026.113785) | Engineering applications of artificial intelligence | — | 11 |
| Jiali Cheng, Hadi Amiri | [Tool Unlearning for Tool-Augmented LLMs](https://doi.org/10.48550/arXiv.2502.01083) | ICML | — | 11 |
| Vaidehi Patil et al. | [Unlearning Sensitive Information in Multimodal LLMs: Benchmark and Attack-Defense Evaluation](https://doi.org/10.48550/arXiv.2505.01456) | TMLR | [GitHub](https://github.com/Vaidehi99/UnLOK-VQA) | 11 |
| Yiwei Chen et al. | [Unlearning Isn't Invisible: Detecting Unlearning Traces in LLMs from Model Outputs](https://doi.org/10.48550/arXiv.2506.14003) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-Trace) | 11 |
| Yiwei Chen et al. | [Safety Mirage: How Spurious Correlations Undermine VLM Safety Fine-tuning](https://doi.org/10.48550/arXiv.2503.11832) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 11 |
| Rongzhe Wei et al. | [Do LLMs Really Forget? Evaluating Unlearning with Knowledge Correlation and Confidence Awareness](https://doi.org/10.48550/arXiv.2506.05735) | arXiv | [GitHub](https://github.com/Graph-COM/Knowledge_Unlearning) | 11 |
| Zexi Li et al. | [Editing as Unlearning: Are Knowledge Editing Methods Strong Baselines for Large Language Model Unlearning?](https://doi.org/10.48550/arXiv.2505.19855) | AAAI | — | 10 |
| Zheling Meng et al. | [Concept Corrector: Erase concepts on the fly for text-to-image diffusion models](https://doi.org/10.48550/arXiv.2502.16368) | Chinese Conference on Pattern Recognition and Computer Vision | [GitHub](https://github.com/RichardSunnyMeng/ConceptCorrector) | 10 |
| S. S et al. | [Machine Unlearning for Grid SearchCV](https://doi.org/10.1109/ICCTDC64446.2025.11158784) | ICCTDC | — | 10 |
| Feiran Li et al. | [One Image is Worth a Thousand Words: A Usability Preservable Text-Image Collaborative Erasing Framework](https://doi.org/10.48550/arXiv.2505.11131) | ICML | [GitHub](https://github.com/ferry-li/co-erasing) | 10 |
| Boheng Li et al. | [Towards Resilient Safety-driven Unlearning for Diffusion Models against Downstream Fine-tuning](https://doi.org/10.48550/arXiv.2507.16302) | arXiv | [GitHub](https://github.com/AntigoneRandy/ResAlign) | 10 |
| K. Lu et al. | [When Are Concepts Erased From Diffusion Models?](https://doi.org/10.48550/arXiv.2505.17013) | arXiv | [GitHub](https://github.com/kevinlu4588/WhenAreConceptsErased) | 10 |
| Shristi Das Biswas, Arani Roy, Kaushik Roy | [CURE: Concept Unlearning via Orthogonal Representation Editing in Diffusion Models](https://doi.org/10.48550/arXiv.2505.12677) | arXiv | [GitHub](https://github.com/ShristiDasBiswas/CURE-Concept-Unlearning-via-Orthogonal-Representation-Editing-in-Diffusion-Models) | 10 |
| Debdeep Sanyal, Murari Mandal | [Agents Are All You Need for LLM Unlearning](https://arxiv.org/abs/2502.00406) | COLM | [GitHub](https://github.com/respailab/agentic-llm-unlearning) | 9 |
| Senthil Pandi S et al. | [Machine Unlearning for Grid SearchCV](https://doi.org/10.1109/icctdc64446.2025.11158784) | ICCTDC | — | 9 |
| Yang Zhang et al. | [Minimalist Concept Erasure in Generative Models](https://doi.org/10.48550/arXiv.2507.13386) | ICML | [GitHub](https://github.com/YaNgZhAnG-V5/minimalist_concept_erasure) | 9 |
| Yuyuan Li et al. | [Class-wise federated unlearning: Harnessing active forgetting with teacher–student memory generation](https://doi.org/10.1016/j.knosys.2025.113353) | Knowledge-Based Systems | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 9 |
| Zhengyi Zhong et al. | [Unlearning through Knowledge Overwriting: Reversible Federated Unlearning via Selective Sparse Adapter](https://doi.org/10.1109/cvpr52734.2025.02855) | OpenReview.net/Archive | — | 9 |
| Thorsten Eisenhofer et al. | [Verifiable and Provably Secure Machine Unlearning](https://doi.org/10.1109/satml64287.2025.00033) | SaTML | [GitHub](https://github.com/cleverhans-lab/verifiable-unlearning) | 9 |
| Dayong Ye et al. | [Data Duplication: A Novel Multi-Purpose Attack Paradigm in Machine Unlearning](https://doi.org/10.48550/arXiv.2501.16663) | USENIX Security | [GitHub](https://github.com/openai/gym) | 9 |
| Kemou Li et al. | [LLM Unlearning with LLM Beliefs](https://doi.org/10.48550/arXiv.2510.19422) | arXiv | — | 9 |
| Bruce Lee et al. | [Distillation Robustifies Unlearning](https://doi.org/10.48550/arXiv.2506.06278) | arXiv | [GitHub](https://github.com/AddieFoote/distillation-robustify-unlearning) | 9 |
| Gen Li et al. | [Sculpting Memory: Multi-Concept Forgetting in Diffusion Models via Dynamic Mask and Concept-Aware Optimization](https://doi.org/10.48550/arXiv.2504.09039) | arXiv | — | 9 |
| Zhijie Deng et al. | [GUARD: Generation-time LLM Unlearning via Adaptive Restriction and Detection](https://doi.org/10.48550/arXiv.2505.13312) | arXiv | [HF](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) | 9 |
| K. Thakral et al. | [Continual Unlearning for Foundational Text-to-Image Models without Generalization Erosion](https://doi.org/10.48550/arXiv.2503.13769) | arXiv | [GitHub](https://github.com/GaParmar/clean-fid) | 9 |
| Zesheng Shi, Yucheng Zhou, Jing Li | [Safety Alignment via Constrained Knowledge Unlearning](https://doi.org/10.48550/arXiv.2505.18588) | ACL | [GitHub](https://github.com/ZeroNLP/Eraser) | 8 |
| Hadi Reisizadeh et al. | [BLUR: A Bi-Level Optimization Approach for LLM Unlearning](https://doi.org/10.48550/arXiv.2506.08164) | ACL | [GitHub](https://github.com/OptimAI-Lab/BLURLLMUnlearning) | 8 |
| Yoav Gur-Arieh et al. | [Precise In-Parameter Concept Erasure in Large Language Models](https://doi.org/10.48550/arXiv.2505.22586) | EMNLP | [GitHub](https://github.com/yoavgur/PISCES) | 8 |
| Sangyeon Yoon, Wonje Jeung, Albert No | [R-TOFU: Unlearning in Large Reasoning Models](https://doi.org/10.48550/arXiv.2505.15214) | EMNLP | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 8 |
| Xu Wang et al. | [Model Unlearning via Sparse Autoencoder Subspace Guided Projections](https://doi.org/10.48550/arXiv.2505.24428) | EMNLP | [GitHub](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) | 8 |
| Ali Ebrahimpour Boroojeny, Hari Sundaram, Varun Chandrasekaran | [Not All Wrong is Bad: Using Adversarial Examples for Unlearning](https://www.semanticscholar.org/paper/62fd8dbf030a5317c98d45f807ced1ceba1d892d) | ICML | — | 8 |
| Mengde Han et al. | [Vertical Federated Unlearning via Backdoor Certification](https://doi.org/10.1109/tsc.2025.3536312) | IEEE TSC | — | 8 |
| Dahyun Jung et al. | [CoME: An Unlearning-based Approach to Conflict-free Model Editing](https://doi.org/10.48550/arXiv.2502.15826) | NAACL | [GitHub](https://github.com/ekgus9/COME) | 8 |
| Cheng-Long Wang et al. | [Towards Lifecycle Unlearning Commitment Management: Measuring Sample-level Unlearning Completeness](https://doi.org/10.48550/arXiv.2506.06112) | USENIX Security | [GitHub](https://github.com/Happy2Git/Unlearning_Inference_IAM) | 8 |
| Jie Ren et al. | [SoK: Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2506.09227) | arXiv | [HF](https://huggingface.co/spaces/raayraay/LLM-Fact-Forgetter) | 8 |
| Jie Ren et al. | [Keeping an Eye on LLM Unlearning: The Hidden Risk and Remedy](https://doi.org/10.48550/arXiv.2506.00359) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-Simple) | 8 |
| Shoaib Ahmed Siddiqui et al. | [From Dormant to Deleted: Tamper-Resistant Unlearning Through Weight-Space Regularization](https://doi.org/10.48550/arXiv.2505.22310) | arXiv | [HF](https://huggingface.co/girishgupta/deep-ignorance-unfiltered_unlearned_wt_dist) | 8 |
| Xiaoyu Ye et al. | [T2VUnlearning: A Concept Erasing Method for Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2505.17550) | arXiv | [GitHub](https://github.com/VDIGPKU/T2VUnlearning) | 8 |
| Aravind Krishnan, Siva Reddy, Marius Mosbach | [Not All Data Are Unlearned Equally](https://doi.org/10.48550/arXiv.2504.05058) | arXiv | [GitHub](https://github.com/McGill-NLP/unequal-unlearning) | 8 |
| Iraklis Premptis et al. | [AILS-NTUA at SemEval-2025 Task 4: Parameter-Efficient Unlearning for Large Language Models using Data Chunking](https://doi.org/10.48550/arXiv.2503.02443) | arXiv | [GitHub](https://github.com/iraklis07/llm-unlearning) | 8 |
| Bowen Fan et al. | [OpenGU: A Comprehensive Benchmark for Graph Unlearning](https://doi.org/10.48550/arXiv.2501.02728) | arXiv | [GitHub](https://github.com/bwfan-bit/OpenGU) | 8 |
| Yi-Yang Xie, Ping Liu, Zheng Zhang | [Erasing Concepts, Steering Generations: A Comprehensive Survey of Concept Suppression](https://doi.org/10.48550/arXiv.2505.19398) | arXiv | [GitHub](https://github.com/GantMan/nsfw) | 8 |
| C. Kim, Yanjun Qi | [A Comprehensive Survey on Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2502.14896) | arXiv | [GitHub](https://github.com/lihuining/Awesome-Concepts-Erasing) | 8 |
| Yifan Li et al. | [Analyzing and Mitigating Object Hallucination: A Training Bias Perspective](https://doi.org/10.48550/arXiv.2508.04567) | AAAI | [GitHub](https://github.com/AoiDragon/POPEv2) | 7 |
| Hwan Chang, Hwanhee Lee | [Which Retain Set Matters for LLM Unlearning? A Case Study on Entity Unlearning](https://doi.org/10.48550/arXiv.2502.11441) | ACL | — | 7 |
| XiaoYu Xu et al. | [OBLIVIATE: Robust and Practical Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2505.04416) | EMNLP | [GitHub](https://github.com/XiaoyuXU1/OBLIVIATE_unlearning_LLM) | 7 |
| U. Basaran et al. | [A Certified Unlearning Approach without Access to Source Data](https://doi.org/10.48550/arXiv.2506.06486) | ICML | [GitHub](https://github.com/info-ucr/certified-unlearning-surr-data) | 7 |
| Yongce Li, Chung-En Sun, Tsui-Wei Weng | [Effective Skill Unlearning through Intervention and Abstention](https://doi.org/10.48550/arXiv.2503.21730) | NAACL | [GitHub](https://github.com/trustworthy-ml-lab/effective_skill_unlearning) | 7 |
| Haokun Chen et al. | [Does Machine Unlearning Truly Remove Knowledge?](https://arxiv.org/abs/2505.23270) | NeurIPS Lock-LLM Workshop Poster | — | 7 |
| Alexey Kravets, Vinay P. Namboodiri | [Zero-shot CLIP Class Forgetting via Text-image Space Adaptation](https://www.semanticscholar.org/paper/594a08af403e3b54a55ef4ad9577d1add2ad7430) | TMLR | [GitHub](https://github.com/akres001/Zero-shot-CLIP-Forgetting-via-Text-image-Space-Adaptation) | 7 |
| Zhili Feng et al. | [Existing Large Language Model Unlearning Evaluations Are Inconclusive](https://doi.org/10.48550/arXiv.2506.00688) | arXiv | — | 7 |
| Shengyuan Hu et al. | [BLUR: A Benchmark for LLM Unlearning Robust to Forget-Retain Overlap](https://doi.org/10.48550/arXiv.2506.15699) | arXiv | [HF](https://huggingface.co/datasets/forgelab/BLUR) | 7 |
| Yujia Tong et al. | [Robust Machine Unlearning for Quantized Neural Networks via Adaptive Gradient Reweighting with Similar Labels](https://doi.org/10.48550/arXiv.2503.13917) | arXiv | — | 7 |
| Stefan Schoepf et al. | [Redirection for Erasing Memory (REM): Towards a universal unlearning method for corrupted data](https://doi.org/10.48550/arXiv.2505.17730) | arXiv | [GitHub](https://github.com/google-deepmind/rem) | 7 |
| Anil Ramakrishna et al. | [SemEval-2025 Task 4: Unlearning sensitive content from Large Language Models](https://doi.org/10.48550/arXiv.2504.02883) | arXiv | — | 7 |
| Zhihua Tian et al. | [Sparse Autoencoder as a Zero-Shot Classifier for Concept Erasing in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2503.09446) | arXiv | [GitHub](https://github.com/nansirun/interpret-then-deactivate) | 7 |
| Jiahang Tu et al. | [CE-SDWV: Effective and Efficient Concept Erasure for Text-to-Image Diffusion Models via a Semantic-Driven Word Vocabulary](https://doi.org/10.48550/arXiv.2501.15562) | arXiv | [GitHub](https://github.com/TtuHamg/CE-SDWV) | 7 |
| Yongliang Wu et al. | [Unlearning Concepts in Diffusion Model via Concept Domain Correction and Concept Preserving Gradient](https://doi.org/10.1609/aaai.v39i8.32917) | AAAI | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 6 |
| Aobo Chen et al. | [A survey of security and privacy issues of machine unlearning](https://doi.org/10.1002/aaai.12209) | AI Magazine | — | 6 |
| Renyang Liu et al. | [Rethinking Machine Unlearning in Image Generation Models](https://doi.org/10.1145/3719027.3744793) | CCS | [GitHub](https://github.com/ryliu68/IGMU) | 6 |
| Wenyu Wang et al. | [UIPE: Enhancing LLM Unlearning by Removing Knowledge Related to Forgetting Targets](https://doi.org/10.48550/arXiv.2503.04693) | EMNLP | — | 6 |
| Guangzhi Sun et al. | [Unlearning vs. Obfuscation: Are We Truly Removing Knowledge?](https://doi.org/10.48550/arXiv.2505.02884) | EMNLP | [GitHub](https://github.com/potsawee/unlearning-dfmcq) | 6 |
| Nakyeong Yang et al. | [FaithUn: Toward Faithful Forgetting in Language Models by Investigating the Interconnectedness of Knowledge](https://doi.org/10.48550/arXiv.2502.19207) | EMNLP | [GitHub](https://github.com/centerforaisafety/wmdp) | 6 |
| Naen Xu et al. | [VideoEraser: Concept Erasure in Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2508.15314) | EMNLP | [GitHub](https://github.com/bluedream02/VideoEraser) | 6 |
| Zhenyu Yu et al. | [ForgetMe: Benchmarking the selective forgetting capabilities of generative models](https://doi.org/10.1016/j.engappai.2025.112087) | Engineering Applications of Artificial Intelligence | [GitHub](https://github.com/YuZhenyuLindy/ForgetMe) | 6 |
| N. Sepahvand et al. | [Selective Unlearning via Representation Erasure Using Domain Adversarial Training](https://www.semanticscholar.org/paper/c7c555a04edc245750ef816346e8ed7dc89fa321) | ICLR | — | 6 |
| Gaurav R. Ghosal, Pratyush Maini, Aditi Raghunathan | [Memorization Sinks: Isolating Memorization during LLM Training](https://doi.org/10.48550/arXiv.2507.09937) | ICML | [GitHub](http://github.com/grghosal/MemSinks) | 6 |
| Angelica Vanessa Audrey Nasution, Suteki Suteki, Anggita Doramia Lumbanraja | [Addressing Deepfake Pornography and the Right to be Forgotten in Indonesia: Legal Challenges in the Era of AI-Driven Sexual Abuse](https://doi.org/10.1007/s11196-025-10265-0) | International Journal for the Semiotics of Law - Revue internationale de Sémiotique juridique | — | 6 |
| He Zhang et al. | [Dynamic Graph Unlearning: A General and Efficient Post-Processing Method via Gradient Transformation](https://doi.org/10.1145/3696410.3714911) | WWW | — | 6 |
| Xiaohua Feng et al. | [Plug and Play: Enabling Pluggable Attribute Unlearning in Recommender Systems](https://doi.org/10.1145/3696410.3714671) | WWW | [GitHub](https://github.com/Anya-bond/Awesome-Privacy-RecSys) | 6 |
| Lulu Xue et al. | [Towards Reliable Forgetting: A Survey on Machine Unlearning Verification](https://arxiv.org/abs/2506.15115) | arXiv | — | 6 |
| Vinith M. Suriyakumar, Ayush Sekhari, Ashia Wilson | [UCD: Unlearning in LLMs via Contrastive Decoding](https://doi.org/10.48550/arXiv.2506.12097) | arXiv | — | 6 |
| Vaidehi Patil, Elias Stengel-Eskin, Mohit Bansal | [UPCORE: Utility-Preserving Coreset Selection for Balanced Unlearning](https://doi.org/10.48550/arXiv.2502.15082) | arXiv | [GitHub](https://github.com/vaidehi99/upcore) | 6 |
| Bill Marino, Meghdad Kurmanji, N. Lane | [Bridge the Gaps between Machine Unlearning and AI Regulation](https://doi.org/10.48550/arXiv.2502.12430) | arXiv | — | 6 |
| Chenlong Zhang et al. | [RULE: Reinforcement UnLEarning Achieves Forget-Retain Pareto Optimality](https://doi.org/10.48550/arXiv.2506.07171) | arXiv | [GitHub](https://github.com/chenlong-clock/RULE-Unlearn) | 6 |
| Huiqiang Chen et al. | [Safe and Reliable Diffusion Models via Subspace Projection](https://doi.org/10.48550/arXiv.2503.16835) | arXiv | — | 6 |
| Reza Akbarian Bafghi et al. | [Fine Tuning without Catastrophic Forgetting via Selective Low Rank Adaptation](https://doi.org/10.48550/arXiv.2501.15377) | arXiv | — | 6 |
| Lingzhi Wang et al. | [Selective Forgetting: Advancing Machine Unlearning Techniques and Evaluation in Language Models](https://doi.org/10.1609/aaai.v39i1.32068) | AAAI | — | 5 |
| Md Rafi Ur Rashid et al. | [Forget to Flourish: Leveraging Machine-Unlearning on Pretrained Language Models for Privacy Leakage](https://doi.org/10.1609/aaai.v39i19.34218) | AAAI | — | 5 |
| Xiang Li, Wenqi Wei, B. Thuraisingham | [MUBox: A Critical Evaluation Framework of Deep Machine Unlearning [Systematization of Knowledge Paper]](https://doi.org/10.1145/3734436.3734454) | ACM Symposium on Access Control Models and Technologies | [GitHub](https://github.com/Jessegator/MUBox) | 5 |
| Ivanna Daniela Cevallos et al. | [A Systematic Literature Review of Machine Unlearning Techniques in Neural Networks](https://doi.org/10.3390/computers14040150) | Computers | — | 5 |
| Shaswati Saha et al. | [Side Effects of Erasing Concepts from Diffusion Models](https://doi.org/10.48550/arXiv.2508.15124) | EMNLP | [GitHub](https://github.com/shaswati1/see) | 5 |
| Bang Trinh Tran To, Thai Le | [Harry Potter is Still Here! Probing Knowledge Leakage in Targeted Unlearned Large Language Models via Automated Adversarial Prompting](https://doi.org/10.48550/arXiv.2505.17160) | EMNLP | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 5 |
| Busra Buyuktanir, Kazim Yildiz, G. Baydogmus | [A Systematic Mapping Study on Machine Unlearning in Federated Learning](https://doi.org/10.1109/ICHORA65333.2025.11017102) | ICHORA | — | 5 |
| Martin Van Waerebeke et al. | [When to Forget? Complexity Trade-offs in Machine Unlearning](https://doi.org/10.48550/arXiv.2502.17323) | ICML | — | 5 |
| Ziyao Liu et al. | [Privacy-Preserving Federated Unlearning With Certified Client Removal](https://doi.org/10.1109/tifs.2025.3555868) | IEEE T-IFS | — | 5 |
| Xiao Liu et al. | [BlockFUL: Enabling Unlearning in Blockchained Federated Learning](https://doi.org/10.1109/tifs.2025.3583109) | IEEE T-IFS | — | 5 |
| Zhiwei Zuo et al. | [Machine Unlearning Through Fine-Grained Model Parameters Perturbation](https://doi.org/10.1109/tkde.2025.3528551) | IEEE TKDE | — | 5 |
| Yuyuan Li et al. | [Multi-Objective Unlearning in Recommender Systems via Preference Guided Pareto Exploration](https://doi.org/10.1109/tsc.2025.3593906) | IEEE TSC | — | 5 |
| Muhammed Shafi K. P. et al. | [How Secure is Forgetting? Linking Machine Unlearning to Machine Learning Attacks](https://doi.org/10.48550/arXiv.2503.20257) | Neurocomputing | — | 5 |
| Ayush K. Varshney, Konstantinos Vandikas, Vicenç Torra | [Unlearning Clients, Features and Samples in Vertical Federated Learning](https://doi.org/10.56553/popets-2025-0048) | PoPETs | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 5 |
| Dang Huu-Tien et al. | [Improving LLM Unlearning Robustness via Random Perturbations](https://arxiv.org/abs/2501.19202) | TMLR | [GitHub](https://github.com/RebelsNLU-jaist/llmu-robustness) | 5 |
| Shanshan Ye, Jie Lü, Guangquan Zhang | [Towards Safe Machine Unlearning: A Paradigm that Mitigates Performance Degradation](https://doi.org/10.1145/3696410.3714638) | WWW | — | 5 |
| Yezi Liu et al. | [Enabling Group Fairness in Graph Unlearning via Bi-level Debiasing](https://doi.org/10.48550/arXiv.2505.09702) | arXiv | [GitHub](https://github.com/brandeis-machine-learning/FairAdj) | 5 |
| Haolin Zou et al. | [Certified Data Removal Under High-dimensional Settings](https://doi.org/10.48550/arXiv.2505.07640) | arXiv | — | 5 |
| Tianyang Xu et al. | [SUV: Scalable Large Language Model Copyright Compliance with Regularized Selective Unlearning](https://doi.org/10.48550/arXiv.2503.22948) | arXiv | [GitHub](https://github.com/xz-liu/SUV) | 5 |
| Matthew Khoriaty et al. | [Don't Forget It! Conditional Sparse Autoencoder Clamping Works for Unlearning](https://doi.org/10.48550/arXiv.2503.11127) | arXiv | [GitHub](https://github.com/AMindToThink/sae_jailbreak_unlearning) | 5 |
| Linian Wang, Leye Wang | [Forgetting Any Data at Any Time: A Theoretically Certified Unlearning Framework for Vertical Federated Learning](https://doi.org/10.48550/arXiv.2502.17081) | arXiv | [GitHub](https://github.com/wangln19/vertical-federated-unlearning) | 5 |
| Tomer Ashuach et al. | [CRISP: Persistent Concept Unlearning via Sparse Autoencoders](https://doi.org/10.48550/arXiv.2508.13650) | arXiv | [GitHub](https://github.com/tomerashuach/CRISP) | 5 |
| N. Singh et al. | [Unlearning That Lasts: Utility-Preserving, Robust, and Almost Irreversible Forgetting in LLMs](https://doi.org/10.48550/arXiv.2509.02820) | arXiv | [GitHub](https://github.com/nmndeep/JensUn-Unlearning) | 5 |
| Yixin Wan et al. | [Not Every Token Needs Forgetting: Selective Unlearning to Limit Change in Utility in Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2506.00876) | arXiv | — | 5 |
| J. H. Grebe et al. | [Erased but Not Forgotten: How Backdoors Compromise Concept Erasure](https://doi.org/10.48550/arXiv.2504.21072) | arXiv | [GitHub](https://github.com/jonasgrebe/erased-but-not-forgotten) | 5 |
| Xiangyu Zhou et al. | [Not All Tokens Are Meant to Be Forgotten](https://doi.org/10.48550/arXiv.2506.03142) | AAAI | [GitHub](https://github.com/xzhou98/Unlearning-TPO) | 4 |
| Hongbang Yuan et al. | [Towards Robust Knowledge Unlearning: An Adversarial Framework for Assessing and Improving Unlearning Robustness in Large Language Models](https://doi.org/10.1609/aaai.v39i24.34769) | AAAI | — | 4 |
| Leyang Li et al. | [Set You Straight: Auto-Steering Denoising Trajectories to Sidestep Unwanted Concepts](https://doi.org/10.1145/3746027.3754546) | ACM MM | [GitHub](https://github.com/lileyang1210/ant) | 4 |
| Jiali Wang et al. | [Scrub-and-Learn: Category-Aware Weight Modification for Machine Unlearning](https://doi.org/10.3390/ai6060108) | AI | — | 4 |
| Sk Miraj et al. | [Towards Source-Free Machine Unlearning](https://doi.org/10.1109/CVPR52734.2025.00466) | CVPR | [GitHub](https://github.com/info-ucr/source-free-unlearning) | 4 |
| Zeliang Zhang et al. | [Targeted Forgetting of Image Subgroups in CLIP Models](https://doi.org/10.1109/CVPR52734.2025.00922) | CVPR | — | 4 |
| Tae-Young Lee et al. | [ESC: Erasing Space Concept for Knowledge Deletion](https://doi.org/10.1109/CVPR52734.2025.00472) | CVPR | [GitHub](https://github.com/KU-VGI/ESC) | 4 |
| Lang Li et al. | [Finetune and Label Reversal: Privacy-preserving unlearning strategies for GAN models in cloud computing](https://doi.org/10.1016/j.csi.2025.103976) | Comput. Stand. Interfaces | — | 4 |
| Hwiyeong Lee et al. | [Does Localization Inform Unlearning? A Rigorous Examination of Local Parameter Attribution for Knowledge Unlearning in Language Models](https://doi.org/10.48550/arXiv.2505.16252) | EMNLP | — | 4 |
| Aly M. Kassem et al. | [Reviving Your MNEME: Predicting The Side Effects of LLM Unlearning and Fine-Tuning via Sparse Model Diffing](https://doi.org/10.48550/arXiv.2507.21084) | EMNLP | — | 4 |
| Kristian Georgiev et al. | [Machine Unlearning via Simulated Oracle Matching](https://www.semanticscholar.org/paper/8cbc39de7bd9689615288c91b3cb8f162867da8a) | ICLR | — | 4 |
| Shuai Zhao et al. | [FedWiper: Federated Unlearning via Universal Adapter](https://doi.org/10.1109/tifs.2025.3557671) | IEEE T-IFS | [GitHub](https://github.com/grey1989/FedWiper) | 4 |
| Zijie Pan et al. | [Robust Watermarking for Federated Diffusion Models with Unlearning-Enhanced Redundancy](https://doi.org/10.1109/tdsc.2025.3576791) | IEEE TDSC | — | 4 |
| Zhiyu Hu et al. | [Exact and Efficient Unlearning for Large Language Model-Based Recommendation](https://doi.org/10.1109/tkde.2025.3594687) | IEEE TKDE | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 4 |
| Zhengbao He et al. | [Towards Natural Machine Unlearning](https://doi.org/10.1109/tpami.2025.3597350) | IEEE TPAMI | [GitHub](https://github.com/ZhengbaoHe/NatMU) | 4 |
| Jiali Cheng, Hadi Amiri | [Speech Unlearning](https://doi.org/10.48550/arXiv.2506.00848) | INTERSPEECH | — | 4 |
| Alkis Koudounas et al. | ["Alexa, can you forget me?" Machine Unlearning Benchmark in Spoken Language Understanding](https://doi.org/10.21437/Interspeech.2025-2607) | INTERSPEECH | — | 4 |
| Shahad Hardan et al. | [Forget-MI: Machine Unlearning for Forgetting Multimodal Information in Healthcare Settings](https://doi.org/10.48550/arXiv.2506.23145) | MICCAI | [GitHub](https://github.com/BioMedIA-MBZUAI/Forget-MI) | 4 |
| Ayush K. Varshney, Vicenç Torra | [Efficient federated unlearning under plausible deniability](https://doi.org/10.1007/s10994-024-06685-x) | Machine Learning | [GitHub](https://github.com/Ayush-Umu/Federated-Unlearning-under-Plausible-Deniability) | 4 |
| Yu-Qin Chen, Shi-Xin Zhang | [Superior resilience to poisoning and amenability to unlearning in quantum machine learning](https://doi.org/10.1038/s41467-026-70420-4) | Nature Communications | — | 4 |
| Nima Naderloui et al. | [Rectifying Privacy and Efficacy Measurements in Machine Unlearning: A New Inference Attack Perspective](https://doi.org/10.48550/arXiv.2506.13009) | USENIX Security | [GitHub](https://github.com/datasec-lab/Ruli) | 4 |
| Wenhan Wu, Jiawei Jiang, Chuang Hu | [Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks](https://doi.org/10.1145/3696410.3714823) | WWW | — | 4 |
| Wang, Yaxuan et al. | [DRAGON: Guard LLM Unlearning in Context via Negative Detection and Reasoning](https://doi.org/10.48550/arXiv.2511.05784) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Liu, Yezi et al. | [LUNE: Efficient LLM Unlearning via LoRA Fine-Tuning with Negative Examples](https://doi.org/10.48550/arXiv.2512.07375) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Shariqah Hossain, Lalana Kagal | [Investigating Model Editing for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2512.20794) | arXiv | [GitHub](https://github.com/bostonadam525/Training-LLMs---From-Scratch-to-Fine-Tuning) | 4 |
| Qingjie Zhang et al. | [Understanding the Dilemma of Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2509.24675) | arXiv | — | 4 |
| Zhaoyang Chu et al. | [Scrub It Out! Erasing Sensitive Memorization in Code Language Models via Machine Unlearning](https://doi.org/10.1145/3744916.3764573) | arXiv | [GitHub](https://github.com/Zhaoyang-Chu/code-unlearning) | 4 |
| Yan Scholten et al. | [Model Collapse Is Not a Bug but a Feature in Machine Unlearning for LLMs](https://doi.org/10.48550/arXiv.2507.04219) | arXiv | [GitHub](https://github.com/partial-model-collapse-unlearning/pmc-unlearning) | 4 |
| Zhehao Huang et al. | [A Unified Gradient-based Framework for Task-agnostic Continual Learning-Unlearning](https://doi.org/10.48550/arXiv.2505.15178) | arXiv | — | 4 |
| Hao Xuan, Xingyu Li | [Verifying Robust Unlearning: Probing Residual Knowledge in Unlearned Models](https://doi.org/10.48550/arXiv.2504.14798) | arXiv | — | 4 |
| Jiali Cheng, Hadi Amiri | [Understanding Machine Unlearning Through the Lens of Mode Connectivity](https://doi.org/10.48550/arXiv.2504.06407) | arXiv | — | 4 |
| Estrid He et al. | [Deep Contrastive Unlearning for Language Models](https://doi.org/10.48550/arXiv.2503.14900) | arXiv | — | 4 |
| M. Russinovich, Ahmed Salem | [Obliviate: Efficient Unmemorization for Protecting Intellectual Property in Large Language Models](https://doi.org/10.48550/arXiv.2502.15010) | arXiv | [GitHub](https://github.com/microsoft/Obliviate-Unmemorization) | 4 |
| Xunkai Li et al. | [Toward Scalable Graph Unlearning: A Node Influence Maximization based Approach](https://doi.org/10.48550/arXiv.2501.11823) | arXiv | — | 4 |
| G. Alon, Yehuda Dar | [How Does Overparameterization Affect Machine Unlearning of Deep Neural Networks?](https://doi.org/10.48550/arXiv.2503.08633) | arXiv | — | 4 |
| Yash Sinha et al. | [Step-by-Step Reasoning Attack: Revealing 'Erased' Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2506.17279) | arXiv | — | 4 |
| Zhaopan Xu et al. | [PEBench: A Fictitious Dataset to Benchmark Machine Unlearning for Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2503.12545) | arXiv | [HF](https://huggingface.co/datasets/xuzhaopan/PEBench) | 4 |
| Yejin Kim et al. | [Improving Fisher Information Estimation and Efficiency for LoRA-based LLM Unlearning](https://doi.org/10.48550/arXiv.2508.21300) | arXiv | [GitHub](https://github.com/kyj93790/VILA) | 4 |
| Woosung Choi et al. | [Large-Scale Training Data Attribution for Music Generative Models via Unlearning](https://doi.org/10.48550/arXiv.2506.18312) | arXiv | [GitHub](https://github.com/Stability-AI/stable-audio-tools) | 4 |
| Ping Liu, Chi Zhang | [Erased or Dormant? Rethinking Concept Erasure Through Reversibility](https://doi.org/10.48550/arXiv.2505.16174) | arXiv | [HF](https://huggingface.co/Lykon/DreamShaper) | 4 |
| Kartik Thakral et al. | [Fine-Grained Erasure in Text-To-Image Diffusion-Based Foundation Models](https://doi.org/10.1109/cvpr52734.2025.00852) | arXiv | — | 4 |
| Subhodip Panda, Shashwat Sourav, Prathosh AP | [Partially Blinded Unlearning: Class Unlearning for Deep Networks from Bayesian Perspective](https://doi.org/10.1609/aaai.v39i6.32682) | AAAI | — | 3 |
| Yash Sinha, Murari Mandal, Mohan Kankanhalli | [Multi-Modal Recommendation Unlearning for Legal, Licensing, and Modality Constraints](https://doi.org/10.1609/aaai.v39i12.33367) | AAAI | [GitHub](https://github.com/MachineUnlearn/MMRecUN) | 3 |
| Wei Qian et al. | [Towards Benchmarking Privacy Vulnerabilities in Selective Forgetting with Large Language Models](https://doi.org/10.48550/arXiv.2512.18035) | AAAI | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 3 |
| Lulu Xue et al. | [Dual-View Inference Attack: Machine Unlearning Amplifies Privacy Exposure](https://doi.org/10.48550/arXiv.2512.16126) | AAAI | — | 3 |
| Zhe-Rui Yang et al. | [Erase Then Rectify: A Training-Free Parameter Editing Approach for Cost-Effective Graph Unlearning](https://doi.org/10.1609/aaai.v39i12.33423) | AAAI | [GitHub](https://github.com/AllminerLab/ETR) | 3 |
| Zheyuan Liu et al. | [Disentangling Biased Knowledge from Reasoning in Large Language Models via Machine Unlearning](https://doi.org/10.18653/v1/2025.acl-long.305) | ACL | — | 3 |
| Yicheng Lang et al. | [Beyond Single-Value Metrics: Evaluating and Enhancing LLM Unlearning with Cognitive Diagnosis](https://doi.org/10.48550/arXiv.2502.13996) | ACL | [GitHub](https://github.com/lyicheng619/UNCD) | 3 |
| Ci Zhang et al. | [Towards Memory-Efficient and Sustainable Machine Unlearning on Edge using Zeroth-Order Optimizer](https://doi.org/10.1145/3716368.3735273) | ACM Great Lakes Symposium on VLSI | — | 3 |
| Wei Qian et al. | [Towards Unveiling Predictive Uncertainty Vulnerabilities in the Context of the Right to Be Forgotten](https://doi.org/10.1145/3746252.3760964) | CIKM | — | 3 |
| Nexhi Sula et al. | [Silver Linings in the Shadows: Harnessing Membership Fingerprinting for Machine Unlearning](https://doi.org/10.1109/cns66487.2025.11195030) | CNS | — | 3 |
| Yang Xiao, Ruimeng Ye, Bo Hui | [Knowledge Graph Unlearning with Schema](https://www.semanticscholar.org/paper/bcbb74501566508503d80420e3925ba8c6b6a9c2) | COLING | — | 3 |
| Naveen George et al. | [The Illusion of Unlearning: The Unstable Nature of Machine Unlearning in Text-to-Image Diffusion Models](https://doi.org/10.1109/cvpr52734.2025.01250) | CVPR | [GitHub](https://github.com/DIL-IITH/TIU) | 3 |
| Alberto Blanco-Justicia et al. | [Unlearning in Large Language Models: We Are Not There Yet](https://doi.org/10.1109/mc.2024.3468588) | Computer | — | 3 |
| Dianqing Liu et al. | [Mitigating Biases in Language Models via Bias Unlearning](https://doi.org/10.48550/arXiv.2509.25673) | EMNLP | [GitHub](https://github.com/a101269/BiasUnlearn) | 3 |
| Khaoula ElBedoui, Walid Barhoumi, Jungwon Cho | [<scp>SoK</scp> : Federated Learning and Unlearning for Medical Image Analysis](https://doi.org/10.1111/exsy.70063) | Expert Systems | — | 3 |
| Rui Shao et al. | [Law LLM unlearning via interfere prompt, review output and update parameter: new challenges, method and baseline](https://doi.org/10.1016/j.eswa.2025.128612) | Expert Systems with Applications | — | 3 |
| Tyler Lizzo, Larry Heck | [UNLEARN Efficient Removal of Knowledge in Large Language Models](https://doi.org/10.18653/v1/2025.findings-naacl.405) | Findings | — | 3 |
| Sai Siddhartha Chary Aylapuram, V. Elluru, Shivang Agarwal | [Bias-Aware Machine Unlearning: Towards Fairer Vision Models via Controllable Forgetting](https://doi.org/10.1109/ICCVW69036.2025.00270) | ICCV | — | 3 |
| Büşra Büyüktanır, Kazım Yıldız, Gozde Karatas Baydoğmus | [A Systematic Mapping Study on Machine Unlearning in Federated Learning](https://doi.org/10.1109/ichora65333.2025.11017102) | ICHORA | — | 3 |
| Miao Yu et al. | [UniErase: Towards Balanced and Precise Unlearning in Language Models](https://arxiv.org/abs/2505.15674) | ICLR Conference Withdrawn Submission | [GitHub](https://github.com/Ymm-cll/UniErase) | 3 |
| N. Sepahvand et al. | [Leveraging Per-Instance Privacy for Machine Unlearning](https://doi.org/10.48550/arXiv.2505.18786) | ICML | — | 3 |
| Taesoo Kim et al. | [Do Not Mimic My Voice: Speaker Identity Unlearning for Zero-Shot Text-to-Speech](https://doi.org/10.48550/arXiv.2507.20140) | ICML | [GitHub](https://github.com/mokcho/mokcho) | 3 |
| Dahuin Jung | [EntUn: Mitigating the forget-retain dilemma in unlearning via entropy](https://doi.org/10.1016/j.icte.2025.06.007) | ICT express | — | 3 |
| Yang Zhao et al. | [Exploring Federated Unlearning: Review, Comparison, and Insights](https://doi.org/10.1109/mnet.2025.3571462) | IEEE Network | — | 3 |
| Yu Jiang et al. | [Certifying the Right to Be Forgotten: Primal–Dual Optimization for Sample and Label Unlearning in Vertical Federated Learning](https://doi.org/10.1109/tifs.2025.3636788) | IEEE T-IFS | — | 3 |
| Jian Chen et al. | [FedMUA: Exploring the Vulnerabilities of Federated Learning to Malicious Unlearning Attacks](https://doi.org/10.1109/tifs.2025.3531141) | IEEE T-IFS | [GitHub](https://github.com/ity207/FedMUA) | 3 |
| Changjun Zhou et al. | [Federated Unlearning With Fast Recovery](https://doi.org/10.1109/tmc.2025.3563265) | IEEE TMC | — | 3 |
| Ningning Ding et al. | [Incentivized Federated Learning and Unlearning](https://doi.org/10.1109/tmc.2025.3557857) | IEEE TMC | — | 3 |
| Yash Sinha, Murari Mandal, Mohan Kankanhalli | [Distill to Delete: Unlearning in Graph Networks With Knowledge Distillation](https://doi.org/10.1109/tnnls.2025.3607995) | IEEE TNNLS | [GitHub](https://github.com/MachineUnlearn/D2DGN) | 3 |
| Hongbo Zhao et al. | [Practical Continual Forgetting for Pre-Trained Vision Models](https://doi.org/10.1109/TPAMI.2026.3654115) | IEEE TPAMI | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 3 |
| Jaeung Lee et al. | [Unlearning Comparator: A Visual Analytics System for Comparative Evaluation of Machine Unlearning Methods](https://doi.org/10.1109/TVCG.2026.3658325) | IEEE TVCG | [GitHub](https://github.com/gnueaj/Machine-Unlearning-Comparator) | 3 |
| Pengfei Ding et al. | [Adaptive Graph Unlearning](https://doi.org/10.48550/arXiv.2505.12614) | IJCAI | [GitHub](https://github.com/Aliezzz/AGU) | 3 |
| Kunho Kim et al. | [GRAIL: Gradient-Based Adaptive Unlearning for Privacy and Copyright in LLMs](https://doi.org/10.1109/IJCNN64981.2025.11229073) | IJCNN | [GitHub](https://github.com/piso7/piso7) | 3 |
| T. Surve, Romila Pradhan | [Explaining Fairness Violations using Machine Unlearning](https://doi.org/10.48786/edbt.2025.50) | International Conference on Extending Database Technology | [GitHub](https://github.com/responsible-data-science-lab/fume) | 3 |
| Kun Wu, Hui Wang | [Verification of Incomplete Graph Unlearning through Adversarial Perturbations](https://doi.org/10.1145/3711896.3737179) | KDD | [GitHub](https://github.com/kunwu522/unlearning-verification-gnn) | 3 |
| Wei Wang et al. | [Label Inference Attacks against Federated Unlearning](https://doi.org/10.48550/arXiv.2508.06789) | Knowledge Science, Engineering and Management | — | 3 |
| Yijiang River Dong et al. | [UNDIAL: Self-Distillation with Adjusted Logits for Robust Unlearning in Large Language Models](https://doi.org/10.18653/v1/2025.naacl-long.444) | NAACL | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 3 |
| Kongyang Chen et al. | [Fast yet versatile machine unlearning for deep neural networks](https://doi.org/10.1016/j.neunet.2025.107648) | Neural Networks | — | 3 |
| Zhaobo Lu et al. | [FeaUn: Feature unlearning in vertical federated learning for IIoT against feature inference attacks](https://doi.org/10.1016/j.neucom.2025.131110) | Neurocomputing | — | 3 |
| Amrita Roy Chowdhury, Zhifeng Kong, Kamalika Chaudhuri | [On the Reliability of Membership Inference Attacks](https://doi.org/10.1109/SaTML64287.2025.00036) | SaTML | — | 3 |
| Pratiksha Thaker et al. | [Position: LLM Unlearning Benchmarks are Weak Measures of Progress](https://doi.org/10.1109/satml64287.2025.00035) | SaTML | — | 3 |
| Weiqi Wang et al. | [TAPE: Tailored Posterior Difference for Auditing of Machine Unlearning](https://doi.org/10.1145/3696410.3714875) | WWW | [GitHub](https://github.com/wwq5-code/TAPE) | 3 |
| T. Shaik et al. | [Quantum Machine Unlearning: Foundations, Mechanisms, and Taxonomy](https://doi.org/10.48550/arXiv.2511.00406) | arXiv | — | 3 |
| Ioannis Mavrothalassitis et al. | [Ascent Fails to Forget](https://doi.org/10.48550/arXiv.2509.26427) | arXiv | — | 3 |
| Chengcan Wu et al. | [Reliable Unlearning Harmful Information in LLMs with Metamorphosis Representation Projection](https://doi.org/10.48550/arXiv.2508.15449) | arXiv | [GitHub](https://github.com/ChengcanWu/MRP) | 3 |
| Xiaohua Feng et al. | [A Survey on Generative Model Unlearning: Fundamentals, Taxonomy, Evaluation, and Future Direction](https://doi.org/10.48550/arXiv.2507.19894) | arXiv | [GitHub](https://github.com/caxLee/Generative-model-unlearning-survey) | 3 |
| Yang Xiao et al. | [The Right to be Forgotten in Pruning: Unveil Machine Unlearning on Sparse Models](https://doi.org/10.48550/arXiv.2507.18725) | arXiv | [GitHub](https://github.com/NKUShaw/SparseModels) | 3 |
| Dimitri Staufer | [What Should LLMs Forget? Quantifying Personal Data in LLMs for Right-to-Be-Forgotten Requests](https://doi.org/10.48550/arXiv.2507.11128) | arXiv | [HF](https://huggingface.co/datasets/humarin/chatgpt-paraphrases) | 3 |
| Taha Entesari et al. | [Constrained Entropic Unlearning: A Primal-Dual Framework for Large Language Models](https://doi.org/10.48550/arXiv.2506.05314) | arXiv | [GitHub](https://github.com/locuslab/open-unlearning) | 3 |
| Jianheng Tang et al. | [ACU: Analytic Continual Unlearning for Efficient and Exact Forgetting with Privacy Preservation](https://doi.org/10.48550/arXiv.2505.12239) | arXiv | — | 3 |
| Ali Ebrahimpour Boroojeny, Hari Sundaram, Varun Chandrasekaran | [AMUN: Adversarial Machine UNlearning](https://doi.org/10.48550/arXiv.2503.00917) | arXiv | [GitHub](https://github.com/Ali-E/AMUN) | 3 |
| Wonje Jeung et al. | [DUSK: Do Not Unlearn Shared Knowledge](https://doi.org/10.48550/arXiv.2505.15209) | arXiv | [GitHub](https://github.com/AI-ISL/DUSK) | 3 |
| Aviv Shamsian et al. | [Go Beyond Your Means: Unlearning with Per-Sample Gradient Orthogonalization](https://doi.org/10.48550/arXiv.2503.02312) | arXiv | — | 3 |
| Lulu Xue et al. | [Towards Reliable Forgetting: A Survey on Machine Unlearning Verification, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2506.15115) | arXiv | — | 3 |
| Sayanta Adhikari, Vishnuprasadh Kumaravelu, P. Srijith | [An Unlearning Framework for Continual Learning](https://doi.org/10.48550/arXiv.2509.17530) | arXiv | [GitHub](https://github.com/visprasadh/uncle) | 3 |
| Ali Taheri et al. | [Forgetting: A New Mechanism Towards Better Large Language Model Fine-tuning](https://doi.org/10.48550/arXiv.2508.04329) | arXiv | [GitHub](https://github.com/AliTaheri2002/Forgetting-A-New-Mechanism-Towards-Better-Large-Language-Model-Fine-tuning) | 3 |
| Yeonwoo Jang et al. | [Prompt Attacks Reveal Superficial Knowledge Removal in Unlearning Methods](https://doi.org/10.48550/arXiv.2506.10236) | arXiv | [GitHub](https://github.com/diogo-cruz/prompt_attacks_paper) | 3 |
| Haoming Xu et al. | [ZJUKLAB at SemEval-2025 Task 4: Unlearning via Model Merging](https://doi.org/10.48550/arXiv.2503.21088) | arXiv | [GitHub](https://github.com/zjunlp/unlearn) | 3 |
| Chenlu Ding et al. | [MLLMEraser: Achieving Test-Time Unlearning in Multimodal Large Language Models through Activation Steering](https://doi.org/10.48550/arXiv.2510.04217) | arXiv | — | 3 |
| Xiaohua Feng et al. | [Bridging the Gap Between Preference Alignment and Machine Unlearning](https://doi.org/10.48550/arXiv.2504.06659) | arXiv | [GitHub](https://github.com/muyiahhh/U2A) | 3 |
| Igor Shilov et al. | [Beyond Data Filtering: Knowledge Localization for Capability Removal in LLMs](https://doi.org/10.48550/arXiv.2512.05648) | arXiv | [GitHub](https://github.com/safety-research/selective-gradient-masking) | 3 |
| Lexiang Xiong et al. | [Semantic Surgery: Zero-Shot Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2510.22851) | arXiv | [GitHub](https://github.com/Lexiang-Xiong/Semantic-Surgery) | 3 |
| Renyang Liu et al. | [Image Can Bring Your Memory Back: A Novel Multi-Modal Guided Attack against Image Generation Model Unlearning](https://doi.org/10.48550/arXiv.2507.07139) | arXiv | [GitHub](https://github.com/ryliu68/RECALL) | 3 |
| Finn Carter | [ACE: Attentional Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2504.11850) | arXiv | — | 3 |
| Yuyang Xue et al. | [CRCE: Coreference-Retention Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2503.14232) | arXiv | [GitHub](https://github.com/vios-s/CRCE) | 3 |
| A. Richardson et al. | [Rethinking the Vulnerability of Concept Erasure and a New Method](https://arxiv.org/abs/2502.17537) | arXiv | [GitHub](https://github.com/notAI-tech/NudeNet) | 3 |
| Arman Zarei et al. | [Localizing Knowledge in Diffusion Transformers](https://doi.org/10.48550/arXiv.2505.18832) | arXiv | [GitHub](https://github.com/ArmanZarei/DiT-Knowledge-Localization) | 3 |
| Seonguk Seo, Dong-Wan Kim, Bohyung Han | [Revisiting Machine Unlearning with Dimensional Alignment](https://doi.org/10.1109/wacv61041.2025.00317) | arXiv | — | 3 |
| Yuan Wang et al. | [Precise, Fast, and Low-cost Concept Erasure in Value Space: Orthogonal Complement Matters](https://doi.org/10.1109/cvpr52734.2025.02678) | arXiv | [GitHub](https://github.com/WYuan1001/AdaVD) | 3 |
| Jiahao Xu, Zikai Zhang, Rui Hu | [Identify Backdoored Model in Federated Learning via Individual Unlearning](https://doi.org/10.1109/wacv61041.2025.00773) | arXiv | [GitHub](https://github.com/JiiahaoXU/MASA) | 3 |
| Sangamesh Kodge et al. | [SAP: Corrective Machine Unlearning with Scaled Activation Projection for Label Noise Robustness](https://doi.org/10.1609/aaai.v39i17.33972) | AAAI | [GitHub](https://github.com/sangamesh-kodge/LabelNoiseRobustness) | 2 |
| Kunhao Li et al. | [Cross-Modal Unlearning via Influential Neuron Path Editing in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2511.06793) | AAAI | [GitHub](https://github.com/PreckLi/MIP-Editor) | 2 |
| Shuai Zhao et al. | [Unlearning Backdoor Attacks for LLMs with Weak-to-Strong Knowledge Distillation](https://doi.org/10.18653/v1/2025.findings-acl.255) | ACL | [GitHub](https://github.com/shuaizhao95/w2sdefense) | 2 |
| S. Vasilev et al. | [Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target Self-Distillation](https://doi.org/10.48550/arXiv.2505.06027) | ACL | [GitHub](https://github.com/eBay/unilogit-acl-2025) | 2 |
| Ignacio Marco-Pérez et al. | [The Many Faces of Data Deletion: On the Significance and Implications of Deleting Data](https://doi.org/10.1145/3779299) | ACM Computing Surveys | — | 2 |
| Feihong Yu et al. | [LEGO: A Lightweight and Efficient Multiple-Attribute Unlearning Framework for Recommender Systems](https://doi.org/10.1145/3746027.3755604) | ACM MM | [GitHub](https://github.com/mtuann/machine-unlearning-papers) | 2 |
| Uyen N. Le-Khac, Vinh Truong | [A survey on large language models unlearning: taxonomy, evaluations, and future directions](https://doi.org/10.1007/s10462-025-11376-7) | Artificial Intelligence Review | — | 2 |
| Ziheng Chen et al. | [FUTURE: Flexible Unlearning for Tree Ensemble](https://doi.org/10.1145/3746252.3760948) | CIKM | — | 2 |
| Yi-Xing Peng et al. | [Person De-reidentification: A Variation-guided Identity Shift Modeling](https://doi.org/10.1109/CVPR52734.2025.02731) | CVPR | [GitHub](https://github.com/yxsysu/Person-DeReID) | 2 |
| Yasser H. Khalil et al. | [NoT: Federated Unlearning via Weight Negation](https://doi.org/10.1109/cvpr52734.2025.02399) | CVPR | — | 2 |
| Yang Yang et al. | [FedCSA: Enhancing Federated Unlearning Efficiency Through Adaptive Clustering Under Data Heterogeneity](https://doi.org/10.23919/cje.2024.00.050) | Chinese Journal of Electronics | — | 2 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [ReVeil: Unconstrained Concealed Backdoor Attack on Deep Neural Networks using Machine Unlearning](https://doi.org/10.1109/dac63849.2025.11133199) | DAC | — | 2 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [ReVeil: Unconstrained Concealed Backdoor Attack on Deep Neural Networks using Machine Unlearning](https://doi.org/10.1109/DAC63849.2025.11133199) | Design Automation Conference | [GitHub](https://github.com/momalab/ReVeil) | 2 |
| Wonje Jeung, Sangyeon Yoon, Albert No | [SEPS: A Separability Measure for Robust Unlearning in LLMs](https://doi.org/10.48550/arXiv.2505.14832) | EMNLP | [GitHub](https://github.com/AI-ISL/SEPS) | 2 |
| Xianren Zhang et al. | [SUA: Stealthy Multimodal Large Language Model Unlearning Attack](https://doi.org/10.18653/v1/2025.emnlp-main.565) | EMNLP | — | 2 |
| Yuntao Wen et al. | [Lock on Target! Precision Unlearning via Directional Control](https://doi.org/10.18653/v1/2025.findings-emnlp.1021) | EMNLP | — | 2 |
| Igor Kabashkin | [Federated Unlearning Framework for Digital Twin–Based Aviation Health Monitoring Under Sensor Drift and Data Corruption](https://doi.org/10.3390/electronics14152968) | Electronics | — | 2 |
| Xavier F. Cadet et al. | [Deep Unlearn: Benchmarking Machine Unlearning for Image Classification](https://doi.org/10.1109/eurosp63326.2025.00058) | EuroS&amp;P | [GitHub](https://github.com/xcadet/deepunlearn) | 2 |
| Yue Zhang et al. | [RUCLIP: Robust concept unlearning in CLIP via semantic anchors](https://doi.org/10.1016/j.eswa.2025.130495) | Expert Systems with Applications | — | 2 |
| Shun‐ichi Watanabe | [Pseudo-Labeling for Enhanced User Privacy in Approximate Machine Unlearning](https://doi.org/10.1109/icassp49660.2025.10890795) | ICASSP | — | 2 |
| Ozan Özdenizci, Elmar Rueckert, R. Legenstein | [Privacy-Aware Lifelong Learning](https://doi.org/10.48550/arXiv.2505.10941) | ICLR | [GitHub](https://github.com/oozdenizci/PALL) | 2 |
| Thanh Linh Nguyen et al. | [Toward Verifiable Federated Unlearning: Framework, Challenges, and the Road Ahead](https://doi.org/10.1109/MIC.2026.3656638) | IEEE Internet Computing | — | 2 |
| Jianxin Zhang et al. | [Model Recovery in Federated Unlearning With Restricted Server Data Resources](https://doi.org/10.1109/jiot.2025.3540463) | IEEE IoT-J | — | 2 |
| Pu Wang, Xin Su, Zhuoran Zheng | [Instance-Wise Privacy Preservation for All-in-One Image Restoration](https://doi.org/10.1109/LSP.2025.3624077) | IEEE Signal Processing Letters | — | 2 |
| Weiqi Wang et al. | [Evaluation of Machine Unlearning Through Model Difference](https://doi.org/10.1109/tifs.2025.3571666) | IEEE T-IFS | — | 2 |
| Yang Wang, Xue Li, Siguang Chen | [Malicious Clients and Contribution Co-Aware Federated Unlearning](https://doi.org/10.1109/tai.2025.3556092) | IEEE TAI | — | 2 |
| Weiqi Wang et al. | [CRFU: Compressive Representation Forgetting Against Privacy Leakage on Machine Unlearning](https://doi.org/10.1109/tdsc.2025.3542092) | IEEE TDSC | [GitHub](https://github.com/wwq5-code/CRFU) | 2 |
| Yixiang Pan et al. | [The Safety Illusion? Testing the Boundaries of Concept Removal in Diffusion Models](https://doi.org/10.1109/TIP.2025.3620665) | IEEE TIP | — | 2 |
| Fan Li et al. | [TCGU: Data-Centric Graph Unlearning Based on Transferable Condensation](https://doi.org/10.1109/tkde.2025.3638465) | IEEE TKDE | [GitHub](https://github.com/Frostland12138/Awesome-Graph-Scaling) | 2 |
| Jiaxing Miao et al. | [Graph Memory Learning: Imitating Lifelong Remembering and Forgetting of Brain Networks](https://doi.org/10.1109/tpami.2025.3599898) | IEEE TPAMI | — | 2 |
| Muhammad Ameen et al. | [Speed up Federated Unlearning With Temporary Local Models](https://doi.org/10.1109/tsusc.2025.3549112) | IEEE Transactions on Sustainable Computing | — | 2 |
| Andrea D’Angelo et al. | [How to Make Reproducible Research in Machine Unlearning with ERASURE](https://doi.org/10.24963/ijcai.2025/1255) | IJCAI | [GitHub](https://github.com/aiim-research/ERASURE) | 2 |
| Yuechun Gu, Jiajie He, Keke Chen | [Auditing Approximate Machine Unlearning for Differentially Private Models](https://doi.org/10.1109/ICDM65498.2025.00134) | Industrial Conference on Data Mining | — | 2 |
| Naglaa E. Ghannam, Esraa A. Mahareek | [AGU: Adaptive gradient unlearning for efficient machine unlearning](https://doi.org/10.1016/j.iswa.2025.200592) | Intelligent Systems with Applications | — | 2 |
| Shengming Zhang et al. | [LLM-Eraser: Optimizing Large Language Model Unlearning through Selective Pruning](https://doi.org/10.1145/3690624.3709312) | KDD | [GitHub](https://github.com/mmichaelzhang/LLM-Eraser) | 2 |
| Xiaoyu Wu et al. | [Unlearned but Not Forgotten: Data Extraction after Exact Unlearning in LLM](https://arxiv.org/abs/2505.24379) | NeurIPS poster | [GitHub](https://github.com/Nicholas0228/unlearned_data_extraction_llm) | 2 |
| Tamim Al Mahmud et al. | [DP2Unlearning: An efficient and guaranteed unlearning framework for LLMs](https://doi.org/10.1016/j.neunet.2025.107879) | Neural Networks | [GitHub](https://github.com/tamimalmahmud/LLM-Unlearning/tree) | 2 |
| Cheng Cheng, Kopo M. Ramokapane | [``Erasing the Echo'': The Usability of Data Deletion in Smart Personal Assistants](https://doi.org/10.56553/popets-2025-0120) | PoPETs | — | 2 |
| Thomas De Min et al. | [Group-robust Machine Unlearning](https://doi.org/10.48550/arXiv.2503.09330) | TMLR | [GitHub](https://github.com/tdemin16/group-robust_machine_unlearning) | 2 |
| Tianwei Ni et al. | [Offline Learning and Forgetting for Reasoning with Large Language Models](https://arxiv.org/abs/2504.11364) | TMLR | [GitHub](https://github.com/danelpeng/Awesome-Continual-Leaning-with-PTMs) | 2 |
| Qiyuan Wang et al. | [Unlearning Incentivizes Learning under Privacy Risk](https://doi.org/10.1145/3696410.3714740) | WWW | — | 2 |
| Nguyen, Viet, Patel, Vishal M. | [CGCE: Classifier-Guided Concept Erasure in Generative Models](https://doi.org/10.48550/arXiv.2511.05865) | arXiv | — | 2 |
| Liu, Yezi et al. | [Recover-to-Forget: Gradient Reconstruction from LoRA for Efficient LLM Unlearning](https://doi.org/10.48550/arXiv.2512.07374) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| M. Maheri et al. | [ZK-APEX: Zero-Knowledge Approximate Personalized Unlearning with Executable Proofs](https://doi.org/10.48550/arXiv.2512.09953) | arXiv | — | 2 |
| Rasam Dorri, Rami Zwick | [Memory Power Asymmetry in Human-AI Relationships: Preserving Mutual Forgetting in the Digital Age](https://doi.org/10.48550/arXiv.2512.06616) | arXiv | — | 2 |
| Duo Zhou et al. | [Geometric-Disentangelment Unlearning](https://doi.org/10.48550/arXiv.2511.17100) | arXiv | [GitHub](https://github.com/Lemutisme/Geometric-Unlearning) | 2 |
| Ruichen Qiu et al. | [A Survey on Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2510.25117) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Zirui Pang et al. | [Label Smoothing Improves Gradient Ascent in LLM Unlearning](https://doi.org/10.48550/arXiv.2510.22376) | arXiv | — | 2 |
| Shiji Zhou et al. | [Efficient Utility-Preserving Machine Unlearning with Implicit Gradient Surgery](https://doi.org/10.48550/arXiv.2510.22124) | arXiv | [GitHub](https://github.com/anseryuer/EUPMU-Efficient-Utility-Preserving-Machine-Unlearning) | 2 |
| Jiatong Yu et al. | [On the Impossibility of Retrain Equivalence in Machine Unlearning](https://doi.org/10.48550/arXiv.2510.16629) | arXiv | [HF](https://huggingface.co/spaces/raayraay/LLM-Fact-Forgetter) | 2 |
| Aaradhya Pandey et al. | [Gaussian Certified Unlearning in High Dimensions: A Hypothesis Testing Approach](https://doi.org/10.48550/arXiv.2510.13094) | arXiv | — | 2 |
| Kai Qin et al. | [Distribution Preference Optimization: A Fine-grained Perspective for LLM Unlearning](https://doi.org/10.48550/arXiv.2510.04773) | arXiv | — | 2 |
| H. Lee, Ruixuan Liu, Li Xiong | [Direct Token Optimization: A Self-contained Approach to Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2510.00125) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Xiang Li et al. | [LoReUn: Data Itself Implicitly Provides Cues to Improve Machine Unlearning](https://doi.org/10.48550/arXiv.2507.22499) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-Saliency) | 2 |
| Yaxin Xiao et al. | [Reminiscence Attack on Residuals: Exploiting Approximate Machine Unlearning for Privacy](https://doi.org/10.48550/arXiv.2507.20573) | arXiv | — | 2 |
| Xuyang Zhong, Hao Luo, Chen Liu | [DualOptim: Enhancing Efficacy and Stability in Machine Unlearning with Dual Optimizers](https://doi.org/10.48550/arXiv.2504.15827) | arXiv | — | 2 |
| Yegor Klochkov | [A mean teacher algorithm for unlearning of language models](https://doi.org/10.48550/arXiv.2504.13388) | arXiv | [GitHub](https://github.com/yklochkov-bytedance/mt-unlearn) | 2 |
| Yijun Quan, Zushu Li, Giovanni Montana | [Efficient Verified Machine Unlearning For Distillation](https://doi.org/10.48550/arXiv.2503.22539) | arXiv | [GitHub](https://github.com/YijunQuan/VerifiedMU4Distill) | 2 |
| Zonghao Huang, N. Gong, Michael K. Reiter | [Instance-Level Data-Use Auditing of Visual ML Models](https://doi.org/10.48550/arXiv.2503.22413) | arXiv | [GitHub](https://github.com/tensorflow/privacy/tree) | 2 |
| Yingdan Shi, Ren Wang | [Redefining Machine Unlearning: A Conformal Prediction-Motivated Approach](https://doi.org/10.48550/arXiv.2501.19403) | arXiv | [GitHub](https://github.com/TIML-Group/Conformal-Prediction-Unlearning) | 2 |
| Jaeheun Jung et al. | [OPC: One-Point-Contraction Unlearning Toward Deep Feature Forgetting](https://doi.org/10.48550/arXiv.2507.07754) | arXiv | [GitHub](https://github.com/pytorch/vision) | 2 |
| Marco Arazzi, Antonino Nocera, P. Vinod | [When Forgetting Triggers Backdoors: A Clean Unlearning Attack](https://doi.org/10.48550/arXiv.2506.12522) | arXiv | — | 2 |
| Alessio Mora et al. | [Federated Unlearning Made Practical: Seamless Integration via Negated Pseudo-Gradients](https://doi.org/10.48550/arXiv.2504.05822) | arXiv | — | 2 |
| Sadiah Qureshi et al. | [Exploring Incremental Unlearning: Techniques, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2502.16708) | arXiv | — | 2 |
| Hao Zheng et al. | [OFFSIDE: Benchmarking Unlearning Misinformation in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2510.22535) | arXiv | [GitHub](https://github.com/zh121800/OFFSIDE) | 2 |
| Chenchen Tan et al. | [Wisdom is Knowing What not to Say: Hallucination-Free LLMs Unlearning via Attention Shifting](https://doi.org/10.48550/arXiv.2510.17210) | arXiv | [GitHub](https://github.com/google-research/lm-extraction-benchmark) | 2 |
| Junbeom Kim et al. | [Scalable and Robust LLM Unlearning by Correcting Responses with Retrieved Exclusions](https://doi.org/10.48550/arXiv.2509.25973) | arXiv | [GitHub](https://github.com/the-jb/cure) | 2 |
| Hang Yan, Zheyuan Liu, Meng Jiang | [Dual-Space Smoothness for Robust and Balanced LLM Unlearning](https://doi.org/10.48550/arXiv.2509.23362) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 2 |
| Nakyeong Yang et al. | [Erase or Hide? Suppressing Spurious Unlearning Neurons for Robust Unlearning](https://doi.org/10.48550/arXiv.2509.22263) | arXiv | [GitHub](https://github.com/centerforaisafety/wmdp) | 2 |
| Xiaoyuan Zhu et al. | [LLM Unlearning Without an Expert Curated Dataset](https://doi.org/10.48550/arXiv.2508.06595) | arXiv | [GitHub](https://github.com/xyzhu123/Synthetic_Textbook) | 2 |
| Huazheng Wang et al. | [Erasing Without Remembering: Implicit Knowledge Forgetting in Large Language Models](https://arxiv.org/abs/2502.19982) | arXiv | [GitHub](https://github.com/MaybeLizzy/PERMU) | 2 |
| Huazheng Wang et al. | [Erasing Without Remembering: Safeguarding Knowledge Forgetting in Large Language Models](https://doi.org/10.48550/arXiv.2502.19982) | arXiv | [GitHub](https://github.com/MaybeLizzy/PERMU) | 2 |
| Zhen Zeng et al. | [Towards Benign Memory Forgetting for Selective Multimodal Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2511.20196) | arXiv | — | 2 |
| Chongyu Fan et al. | [LLM Unlearning Under the Microscope: A Full-Stack View on Methods and Metrics](https://doi.org/10.48550/arXiv.2510.07626) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-FullStack) | 2 |
| Bingqi Shang et al. | [Forgetting to Forget: Attention Sink as A Gateway for Backdooring LLM Unlearning](https://doi.org/10.48550/arXiv.2510.17021) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-Backdoor) | 2 |
| Tianwei Ni et al. | [Teaching Large Language Models to Reason through Learning and Forgetting](https://doi.org/10.48550/arXiv.2504.11364) | arXiv | — | 2 |
| Hengrui Jia et al. | [The Erasure Illusion: Stress-Testing the Generalization of LLM Forgetting Evaluation](https://doi.org/10.48550/arXiv.2512.19025) | arXiv | — | 2 |
| Xun Yuan et al. | [Towards Irreversible Machine Unlearning for Diffusion Models](https://doi.org/10.48550/arXiv.2512.03564) | arXiv | [GitHub](https://github.com/OPTML-Group/UnlearnCanvas) | 2 |
| Justin Lee et al. | [Continual Unlearning for Text-to-Image Diffusion Models: A Regularization Perspective](https://doi.org/10.48550/arXiv.2511.07970) | arXiv | — | 2 |
| Jiaqi Liu, Lan Zhang, Xiaoyong Yuan | [DyME: Dynamic Multi-Concept Erasure in Diffusion Models with Bi-Level Orthogonal LoRA Adaptation](https://doi.org/10.48550/arXiv.2509.21433) | arXiv | — | 2 |
| Finn Carter | [TRACE: Trajectory-Constrained Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2505.23312) | arXiv | — | 2 |
| Die Chen et al. | [Comprehensive Evaluation and Analysis for NSFW Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2505.15450) | arXiv | [GitHub](https://github.com/ECNU-CILAB/ErasureBenchmark) | 2 |
| Pierre Lubitzsch et al. | [Towards a Real-World Aligned Benchmark for Unlearning in Recommender Systems](https://doi.org/10.48550/arXiv.2508.17076) | arXiv | [GitHub](https://github.com/pierre-lubitzsch/towards-unlearning-in-recsys) | 2 |
| Jiahao Huo et al. | [MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://doi.org/10.18653/v1/2025.findings-acl.375) | arXiv | [GitHub](https://github.com/Z1zs/MMUnlearner) | 2 |
| Zihao Wang et al. | [ACE: Anti-Editing Concept Erasure in Text-to-Image Models](https://doi.org/10.1109/cvpr52734.2025.02189) | arXiv | [GitHub](https://github.com/120L020904/ACE) | 2 |
| Karuna Bhaila, Minh-Hao Van, Xintao Wu | [Soft Prompting for Unlearning in Large Language Models](https://doi.org/10.18653/v1/2025.naacl-long.204) | arXiv | [GitHub](https://github.com/karuna-bhaila/llm_unlearning) | 2 |
| Dasol Choi, Dongbin Na | [Distribution-Level Feature Distancing for Machine Unlearning: Towards a Better Trade-off Between Model Utility and Forgetting](https://doi.org/10.1609/aaai.v39i3.32256) | AAAI | — | 1 |
| Qipeng Song et al. | [Synthetic Forgetting without Access: A Few-shot Zero-glance Framework for Machine Unlearning](https://doi.org/10.48550/arXiv.2511.13116) | AAAI | — | 1 |
| Edoardo De Matteis et al. | [Human Motion Unlearning](https://doi.org/10.48550/arXiv.2503.18674) | AAAI | [GitHub](https://github.com/Mamiglia/hmu) | 1 |
| Yi Li et al. | [Community-Centric Graph Unlearning](https://doi.org/10.1609/aaai.v39i17.34041) | AAAI | [GitHub](https://github.com/liiiyi/CCGU) | 1 |
| J. Bach et al. | [Unlearning with Partial Label Learning](https://doi.org/10.1145/3733155.3733201) | ACM International Conference on PErvasive Technologies Related to Assistive Environments | — | 1 |
| Yizhou Lin et al. | [ICE: Intercede Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1145/3746027.3754992) | ACM MM | — | 1 |
| Qiang Chen et al. | [Graph Unlearning Meets Influence-aware Negative Preference Optimization](https://doi.org/10.1145/3746027.3754941) | ACM MM | [GitHub](https://github.com/sh-qiangchen/INPO) | 1 |
| Emma Reyner-Fuentes, Esther Rituerto-González, Carmen Peláez-Moreno | [Machine Unlearning for Speaker-Agnostic Detection of Gender-Based Violence Condition in Speech](https://doi.org/10.3390/app152212270) | Applied Sciences | [GitHub](https://github.com/emmareyner/AdversarialTraining) | 1 |
| Huanyi Ye et al. | [Enhancing AI safety of machine unlearning for ensembled models](https://doi.org/10.1016/j.asoc.2025.113011) | Applied Soft Computing | — | 1 |
| Ranjit Kumar et al. | [Machine Unlearning for Trustworthy AI: A Systematic Review of Techniques, Challenges, and Applications](https://doi.org/10.1007/s11831-025-10436-z) | Archives of Computational Methods in Engineering | — | 1 |
| Gaoyang Liu et al. | [Prototype Surgery: Tailoring Neural Prototypes via Soft Labels for Efficient Machine Unlearning](https://doi.org/10.1145/3719027.3744827) | CCS | — | 1 |
| Yezi Liu, Yanning Shen | [Enabling Group Fairness in Machine Unlearning via Distribution Correction](https://doi.org/10.1145/3746252.3761299) | CIKM | — | 1 |
| Yang Xiao et al. | [Efficient Knowledge Graph Unlearning with Zeroth-order Information](https://doi.org/10.1145/3746252.3761379) | CIKM | [GitHub](https://github.com/NKUShaw/ZOWFKGIF) | 1 |
| Muhammad Shaheryar, Jong Taek Lee, Soon Ki Jung | [Black Hole-Driven Identity Absorbing in Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02658) | CVPR | — | 1 |
| Àlex Pujol Vidal et al. | [Machine Unlearning in Hyperbolic vs. Euclidean Multimodal Contrastive Learning: Adapting Alignment Calibration to MERU](https://doi.org/10.1109/CVPRW67362.2025.00152) | CVPR | [GitHub](https://github.com/alexpv01/HAC) | 1 |
| Christoforos N. Spartalis et al. | [LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty](https://doi.org/10.1109/cvpr52734.2025.00939) | CVPR | [GitHub](https://github.com/cspartalis/LoTUS) | 1 |
| Yimin Wen et al. | [Unlearning Recently Learned Data to Preserve Historical Learning for Dynamic Data Stream Classification](https://doi.org/10.23919/cje.2024.00.219) | Chinese Journal of Electronics | — | 1 |
| Si Qi Goh et al. | [FROC: A Unified Framework with Risk-Optimized Control for Machine Unlearning in LLMs](https://doi.org/10.1109/ICAIIC68212.2026.11454224) | Digital Signal Processing and Signal Processing Education Workshop | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Feng Li et al. | [Secure Dynamic Spectrum Access in Internet-of-Things Based on Machine Unlearning](https://doi.org/10.1109/ICAIIC64266.2025.10920793) | Digital Signal Processing and Signal Processing Education Workshop | — | 1 |
| Hannah Wooten | ["Set It and Forget It" Hydroponic Lettuce](https://doi.org/10.32473/edis-hs1488-2025) | EDIS | — | 1 |
| Xin Gao et al. | [Can Prompts Rewind Time for LLMs? Evaluating the Effectiveness of Prompted Knowledge Cutoffs](https://doi.org/10.48550/arXiv.2510.02340) | EMNLP | [GitHub](https://github.com/gxx27/time_unlearn) | 1 |
| Chunyang Jiang et al. | [Graceful Forgetting in Generative Language Models](https://doi.org/10.18653/v1/2025.emnlp-main.666) | EMNLP | [GitHub](https://github.com/rubickkcibur/LWF) | 1 |
| Haokun Chen et al. | [Soft Token Attacks Cannot Reliably Audit Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2502.15836) | EMNLP | [GitHub](https://github.com/IntelLabs/LLMart/tree) | 1 |
| Van-Tuan Tran, Hong-Hanh Nguyen-Le, Quoc-Viet Pham | [ToFU: Transforming How Federated Learning Systems Forget User Data](https://doi.org/10.48550/arXiv.2509.15861) | European Conference on Artificial Intelligence | — | 1 |
| Marwan Adnan Darwish, Evangelia Anna Markatou, Georgios Smaragdakis | [Provable Co-Owned Data Deletion with Zero-Residuals and Verifiability in Multi-Cloud Environment](https://doi.org/10.1145/3722041.3723104) | European Workshop on System Security | — | 1 |
| Aman Kumar et al. | [FLUID: Federated Learning with Unlearning and Instant Drift-Recovery](https://doi.org/10.1109/FLTA67013.2025.11336437) | FLTA | [GitHub](https://github.com/Encore7/fluid) | 1 |
| Aman Kumar et al. | [FLUID: Federated Learning with Unlearning and Instant Drift-Recovery](https://doi.org/10.1109/flta67013.2025.11336437) | FLTA | [GitHub](https://github.com/Encore7/fluid) | 1 |
| Jie Ren et al. | [A General Framework to Enhance Fine-tuning-based LLM Unlearning](https://doi.org/10.18653/v1/2025.findings-acl.949) | Findings | [GitHub](https://github.com/renjie3/GRUN) | 1 |
| Weixiang Zhao et al. | [The gains do not make up for the losses: a comprehensive evaluation for safety alignment of large language models via machine unlearning](https://doi.org/10.1007/s11704-024-41099-x) | Frontiers of Computer Science | — | 1 |
| Naglaa E. Ghannam, Esraa A. Mahareek | [Privacy-Preserving Federated Unlearning with Ontology-Guided Relevance Modeling for Secure Distributed Systems](https://doi.org/10.3390/fi17080335) | Future Internet | — | 1 |
| Loveth A Ebong, Gertrude Fischer | [Cloud Security Using Crypto-Shredding For Secure Data Deletion: A Reduction In Cyber Security Risks](https://doi.org/10.4314/gjpas.v31i4.6) | Global Journal of Pure and Applied Science | — | 1 |
| Shunichi Watanabe | [Pseudo-Labeling for Enhanced User Privacy in Approximate Machine Unlearning](https://doi.org/10.1109/ICASSP49660.2025.10890795) | ICASSP | — | 1 |
| Ibtihel Amara et al. | [Erasing More Than Intended? How Concept Erasure Degrades the Generation of Non-Target Concepts](https://doi.org/10.1109/iccv51701.2025.01524) | ICCV | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| M. Maheri et al. | [WARP: Weight Teleportation for Attack-Resilient Unlearning Protocols](https://arxiv.org/abs/2512.00272) | ICLR Poster | [GitHub](https://github.com/mammadmaheri7/WARP_Unlearning) | 1 |
| Lin Lu, Ayush Sekhari, Karthik Sridharan | [System-Aware Unlearning Algorithms: Use Lesser, Forget Faster](https://doi.org/10.48550/arXiv.2506.06073) | ICML | — | 1 |
| Hong Xi Tae, Chee Seng Chan | [A Survey of Challenges and Opportunities in Vertical Federated Unlearning](https://doi.org/10.1109/access.2025.3600884) | IEEE Access | [GitHub](https://github.com/bryanhx/Vertical-Federated-Unlearning-Benchmark) | 1 |
| Wenhan Wu et al. | [Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning](https://doi.org/10.1109/ICDE65448.2025.00200) | IEEE International Conference on Data Engineering | [GitHub](https://github.com/Anya-bond/Awesome-Privacy-RecSys) | 1 |
| An Huang, Zhipeng Cai, Zuobin Xiong | [A Survey of Machine Unlearning in Generative AI Models: Methods, Applications, Security, and Challenges](https://doi.org/10.1109/jiot.2025.3570989) | IEEE IoT-J | — | 1 |
| Xuanpeng Li et al. | [An Efficient Two-Stage Machine Unlearning Framework for Poisoned Specific Emitter Identification](https://doi.org/10.1109/jiot.2025.3583362) | IEEE IoT-J | — | 1 |
| Fangwei Wang et al. | [FedBT: Effective and Robust Federated Unlearning via Bad Teacher Distillation for Secure Internet of Things](https://doi.org/10.1109/jiot.2025.3571432) | IEEE IoT-J | — | 1 |
| Wathsara Daluwatta et al. | [SSFU: Selective Semantic Feature Unlearning for Federated Learning in 6G Internet of Things Systems](https://doi.org/10.1109/jiot.2025.3625756) | IEEE IoT-J | — | 1 |
| Chunyi Zhou et al. | [TruVRF: Toward Triple-Granularity Verification on Machine Unlearning](https://doi.org/10.1109/tifs.2025.3565991) | IEEE T-IFS | — | 1 |
| Xiaohan Yuan et al. | [FedEditor: Efficient and Effective Federated Unlearning in Cooperative Intelligent Transportation Systems](https://doi.org/10.1109/tifs.2025.3583231) | IEEE T-IFS | — | 1 |
| Jiale Zhang et al. | [SSLDefender: Backdoor Defense in Self-Supervised Learning via Distillation-Guided Unlearning](https://doi.org/10.1109/TIFS.2025.3640880) | IEEE T-IFS | — | 1 |
| Hengzhu Liu et al. | [Game-Theoretic Machine Unlearning: Mitigating Extra Privacy Leakage](https://doi.org/10.1109/tifs.2025.3623364) | IEEE T-IFS | — | 1 |
| Xiao Liu et al. | [Parallel Unlearning in Inherited Model Networks](https://doi.org/10.1109/tifs.2025.3627869) | IEEE T-IFS | [GitHub](https://github.com/MJLee00/Parallel-Unlearning-in-Inherited-Model-Networks) | 1 |
| Weiqi Wang et al. | [SMS: Self-Supervised Model Seeding for Verification of Machine Unlearning](https://doi.org/10.1109/TDSC.2025.3615615) | IEEE TDSC | [GitHub](https://github.com/wwq5-code/SMS) | 1 |
| Yuepeng Hu et al. | [Periodic Recovery From Poisoning Attacks in Machine Learning](https://doi.org/10.1109/TDSC.2025.3560239) | IEEE TDSC | [GitHub](https://github.com/hifi-hyp/PeriRecover) | 1 |
| Shang Wang et al. | [When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?](https://doi.org/10.1109/tdsc.2025.3620832) | IEEE TDSC | — | 1 |
| Yuyuan Li et al. | [A Survey on Recommendation Unlearning: Fundamentals, Taxonomy, Evaluation, and Open Questions](https://doi.org/10.1109/tkde.2025.3638174) | IEEE TKDE | — | 1 |
| Wenhan Wu et al. | [Mimir: Data-Free Federated Unlearning Through Client-Specific Prompt Generation for Personalized Models](https://doi.org/10.1109/tmc.2025.3570018) | IEEE TMC | — | 1 |
| Jian Chen et al. | [Unlearning Attacks for Regression Learning](https://doi.org/10.1109/TNNLS.2025.3553821) | IEEE TNNLS | — | 1 |
| Jiayi Wang et al. | [A Zero-Shot Federated Unlearning Framework With Stability Verification](https://doi.org/10.1109/tccn.2025.3594672) | IEEE Transactions on Cognitive Communications and Networking | [GitHub](https://github.com/kayeewww/fuzv) | 1 |
| Yan Qu et al. | [Fuzzified Federated Multi-Task Unlearning for Efficient and Privacy-Preserving Swarm Consumer Electronics Systems](https://doi.org/10.1109/tce.2025.3571956) | IEEE Transactions on Consumer Electronics | — | 1 |
| Jielong Yang et al. | [Machine Unlearning for Source-Free Unsupervised Partial-Domain Adaptation in Remote Sensing](https://doi.org/10.1109/tgrs.2025.3637240) | IEEE Transactions on Geoscience and Remote Sensing | — | 1 |
| Yuange Liu et al. | [EPFL: Toward Elastic Personalized Federated Learning With Seamless Client Joining and Quitting](https://doi.org/10.1109/TSMC.2025.3613624) | IEEE Transactions on Systems, Man, and Cybernetics: Systems | — | 1 |
| Yuanxiang Gong et al. | [Channel Knowledge Map Updating with Machine Unlearning](https://doi.org/10.1109/icccworkshops67136.2025.11148163) | IEEE/CIC International Conference on Communications in China (ICCC Workshops) | — | 1 |
| Issa Sugiura, Shingo Okamura, Naoto Yanai | [Removing Mislabeled Data from Trained Models via Machine Unlearning](https://doi.org/10.1587/transinf.2024dat0002) | IEICE Trans. Inf. Syst | [GitHub](https://github.com/speed1313/mislabel-unlearning) | 1 |
| Mohammad Partohaghighi et al. | [Roughness-Informed Machine Unlearning: A Call for Fractal and Fractional Calculi](https://doi.org/10.1016/j.ifacol.2026.01.003) | IFAC-PapersOnLine | — | 1 |
| Stefan Schoepf, J. Foster, A. Brintrup | [Machine unlearning in supply chains](https://doi.org/10.1016/j.ifacol.2025.09.495) | IFAC-PapersOnLine | — | 1 |
| Wenhan Wu et al. | [Zero-shot Federated Unlearning via Transforming from Data-Dependent to Personalized Model-Centric](https://doi.org/10.24963/ijcai.2025/733) | IJCAI | — | 1 |
| Zhihao Sui et al. | [Recalling The Forgotten Class Memberships: Unlearned Models Can Be Noisy Labelers to Leak Privacy](https://doi.org/10.48550/arXiv.2506.19486) | IJCAI | [GitHub](https://github.com/rainmilk/mra4mu) | 1 |
| Hong kyu Lee et al. | [Contrastive Unlearning: A Contrastive Approach to Machine Unlearning](https://doi.org/10.24963/ijcai.2025/830) | IJCAI | [GitHub](https://github.com/Hongkyu-Lee/Contrastive-Unlearning) | 1 |
| Pengfei Ding et al. | [Adaptive Graph Unlearning](https://doi.org/10.24963/ijcai.2025/308) | IJCAI | [GitHub](https://github.com/Aliezzz/AGU) | 1 |
| Shreya Pathak et al. | [Quantum-Inspired Audio Unlearning: Towards Privacy-Preserving Voice Biometrics](https://doi.org/10.1109/IJCB65343.2025.11411246) | IJCB | [GitHub](https://github.com/rishi02102017/QPAudioEraser-IndiaAI-Impact-Summit-Demo) | 1 |
| Alessio Mora et al. | [Federated Unlearning in Healthcare: Why It Matters](https://doi.org/10.1109/ijcnn64981.2025.11228665) | IJCNN | [GitHub](https://github.com/alessiomora/medical) | 1 |
| Boxu Xiao, Sijia Liu, Qing Ling | [Federated Unlearning with Oriented Saliency Compression](https://doi.org/10.1109/ijcnn64981.2025.11228643) | IJCNN | [GitHub](https://github.com/RadiumStar/FedUOSC) | 1 |
| Chetia Phukan et al. | [Towards Machine Unlearning for Paralinguistic Speech Processing](https://doi.org/10.48550/arXiv.2506.02230) | INTERSPEECH | [HF](https://huggingface.co/facebook/wav2vec2-xls-r-300m) | 1 |
| Alkis Koudounas et al. | [``Alexa, can you forget me?'' Machine Unlearning Benchmark in Spoken Language Understanding](https://doi.org/10.21437/interspeech.2025-2607) | INTERSPEECH | — | 1 |
| Maximilian Egger, Rawad Bitar, Rüdiger Urbanke | [Efficient Machine Unlearning by Model Splitting and Core Sample Selection](https://doi.org/10.1109/itw62417.2025.11240389) | ITW | — | 1 |
| Saeed Iqbal et al. | [Core unlearning: A multi-modal gradient-efficient architecture for exact and approximate model rewriting](https://doi.org/10.1016/j.ipm.2025.104417) | Information Processing & Management | — | 1 |
| Mr. Veerasagar S S | [Vershachi Unlearning: A Framework for Machine Unlearning](https://doi.org/10.22214/ijraset.2025.67269) | International Journal for Research in Applied Science and Engineering Technology | — | 1 |
| Nishat Mahdiya Khan et al. | [Zero Trust Networks and Federated Unlearning Based <scp>6G</scp> Edge Networks: Attack Scenario, Security Model and Future Directions](https://doi.org/10.1002/itl2.70056) | Internet Technology Letters | — | 1 |
| Kun Gao et al. | [Federated Unlearning With Reinforcement Learning: Adaptive Privacy Preservation for Clients](https://doi.org/10.1016/j.jisa.2025.104164) | Journal of Information Security and Applications | — | 1 |
| Yiyang Huang, Clément L. Canonne | [Tight Bounds for Machine Unlearning via Differential Privacy](https://doi.org/10.29012/jpc.924) | Journal of Privacy and Confidentiality | [GitHub](https://github.com/XiangmanLI/Harmful-Information-Unlearning) | 1 |
| Jiali Wang et al. | [Weight masking in image classification networks: class-specific machine unlearning](https://doi.org/10.1007/s10115-024-02312-2) | Knowledge and Information Systems | — | 1 |
| N. Xu et al. | [Learn to unlearn: meta-learning-based knowledge graph embedding unlearning](https://doi.org/10.1007/s10115-025-02407-4) | Knowledge and Information Systems | — | 1 |
| Yunjian Zhang et al. | [Subspace-constrained graph unlearning for forgetting high-risk compound-protein interactions](https://doi.org/10.1016/j.knosys.2025.115193) | Knowledge-Based Systems | — | 1 |
| Wang Zeng et al. | [SALAD: Systematic Assessment of Machine Unlearning on LLM-Aided Hardware Design](https://doi.org/10.1109/mlcad65511.2025.11189152) | MLCAD | [GitHub](https://github.com/DfX-NYUAD/SALAD) | 1 |
| Deliang Jin et al. | [Machine Unlearning for Robust DNNs: Attribution-Guided Partitioning and Neuron Pruning in Noisy Environments](https://doi.org/10.3390/make7030095) | Machine Learning and Knowledge Extraction | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 1 |
| Ju-Hsuan Weng et al. | [Multimodal Robustness Benchmark for Concept Erasure in Diffusion Models](https://www.semanticscholar.org/paper/1346d7ba4f5e6fd972c261efe99e81758daa55c5) | NeurIPS Workshop GenProCC | — | 1 |
| Lin Li et al. | [Enhancing partition distinction: A contrastive policy to recommendation unlearning](https://doi.org/10.1016/j.neunet.2025.107667) | Neural Networks | [GitHub](https://github.com/linli0818/PDCRU) | 1 |
| Ruotong Geng et al. | [Mitigating sensitive information leakage in LLMs4Code through machine unlearning](https://doi.org/10.1016/j.neunet.2026.108606) | Neural Networks | — | 1 |
| Lei Kang et al. | [Preserving privacy without compromising accuracy: Machine unlearning for handwritten text recognition](https://doi.org/10.1016/j.patcog.2025.112411) | Pattern Recognition | [GitHub](https://github.com/leitro/WIC-WriterIDConfusion-MachineUnlearning) | 1 |
| Xiaoxuan Han et al. | [Probing unlearned diffusion models: A transferable adversarial attack perspective](https://doi.org/10.1016/j.patcog.2025.112916) | Pattern Recognition | [GitHub](https://github.com/SaFo-Lab/Awesome-T2I-safety-Papers) | 1 |
| Jun-Jian Su et al. | [From Membership-Privacy Leakage to Quantum Machine Unlearning](https://doi.org/10.1103/PhysRevApplied.25.044056) | Phys. Rev. Applied | [GitHub](https://github.com/Sujun124/QMU) | 1 |
| Abdulla Alshabanah, Keshav Balasubramanian, Murali Annavaram | [Meta-Learn to Unlearn: Enhanced Exact Machine Unlearning in Recommendation Systems with Meta-Learning](https://doi.org/10.56553/popets-2025-0152) | PoPETs | — | 1 |
| Haocheng Dou, Tao Lian, Xin Xin | [Measuring Interaction-Level Unlearning Difficulty for Collaborative Filtering](https://doi.org/10.1145/3705328.3748092) | RecSys | [GitLab](https://gitlab.com/hcdou/cf-unlearn-difficulty) | 1 |
| Andreza M. C. Falcao, Filipe R. Cordeiro | [Data Augmentation Improves Machine Unlearning](https://doi.org/10.1109/SIBGRAPI67909.2025.11223373) | SIBGRAPI Conference on Graphics, Patterns and Images | — | 1 |
| Guoxuan Chen, Lianghao Xia, Chao Huang | [Pre-training for Recommendation Unlearning](https://doi.org/10.1145/3726302.3730060) | SIGIR | [GitHub](https://github.com/HKUDS/UnlearnRec) | 1 |
| Haruki Yonekura et al. | [MobText-SISA: Efficient Machine Unlearning for Mobility Logs with Spatio-Temporal and Natural-Language Data](https://doi.org/10.1145/3748636.3763226) | SIGSPATIAL/GIS | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 1 |
| Subhodip Panda et al. | [Unlearning in Diffusion models under Data Constraints: A Variational Inference Approach](https://arxiv.org/abs/2510.04058) | TMLR | [GitHub](https://github.com/Subhodip123/VDU) | 1 |
| G. Nahass et al. | [Targeted Unlearning Using Perturbed Sign Gradient Methods With Applications On Medical Images](https://doi.org/10.48550/arXiv.2505.21872) | TMLR | — | 1 |
| Tian Tian et al. | [Blockchain-based verifiable data deletion and software management for cloud storage](https://doi.org/10.1117/12.3067620) | TOCS | — | 1 |
| Wen Cheng et al. | [FlashFox: a secret-sharing approach to securing data deletion for Flash-based SSD](https://doi.org/10.1093/comjnl/bxae145) | The Computer Journal | — | 1 |
| Lang Li et al. | [Inverse correction-optimized vertical federated unlearning](https://doi.org/10.1007/s11227-025-07310-x) | The Journal of Supercomputing | — | 1 |
| Yuhe Leng et al. | [FedSSU: flexible and efficient decentralized unlearning for federated learning](https://doi.org/10.1007/s11227-025-07478-2) | The Journal of Supercomputing | — | 1 |
| Zengyan Li, Qingqing Ye, Haibo Hu | [FUNU: Boosting Machine Unlearning Efficiency by Filtering Unnecessary Unlearning](https://doi.org/10.1145/3696410.3714711) | WWW | — | 1 |
| Fan Liu, Hao Liu | [Subgraph Federated Unlearning](https://doi.org/10.1145/3696410.3714821) | WWW | [GitHub](https://github.com/usail-hkust/FedUnlearnSFU) | 1 |
| Wenbin Wang et al. | [Poisoning Attacks and Defenses to Federated Unlearning](https://doi.org/10.1145/3701716.3715494) | WWW | — | 1 |
| Lu Wei, Yuta Nakashima, Noa García | [EMMA: Concept Erasure Benchmark with Comprehensive Semantic Metrics and Diverse Categories](https://doi.org/10.48550/arXiv.2512.17320) | arXiv | [GitHub](https://github.com/lobsterlulu/EMMA) | 1 |
| Biswas, Shristi Das, Roy, Arani, Roy, Kaushik | [Now You See It, Now You Don't - Instant Concept Erasure for Safe Text-to-Image and Video Generation](https://doi.org/10.48550/arXiv.2511.18684) | arXiv | — | 1 |
| Carla Crivoi, R. Ionescu | [Machine Unlearning in the Era of Quantum Machine Learning: An Empirical Study](https://doi.org/10.48550/arXiv.2512.19253) | arXiv | [GitHub](https://github.com/CrivoiCarla/HQML) | 1 |
| Bokang Zhang et al. | [FedSGT: Exact Federated Unlearning via Sequential Group-based Training](https://doi.org/10.48550/arXiv.2511.23393) | arXiv | [GitHub](https://github.com/deucalionAlpha/FedSGT) | 1 |
| Antoine Boutet, Lucas Magnana | [Leverage Unlearning to Sanitize LLMs](https://doi.org/10.48550/arXiv.2510.21322) | arXiv | [HF](https://huggingface.co/dslim/bert-base-NER) | 1 |
| Kodai Kawamura et al. | [Approximate Domain Unlearning for Vision-Language Models](https://doi.org/10.48550/arXiv.2510.08132) | arXiv | [GitHub](https://github.com/kodaikawamura/domain-unlearning) | 1 |
| Wenhan Wu et al. | [Beyond Sharp Minima: Robust LLM Unlearning via Feedback-Guided Multi-Point Optimization](https://doi.org/10.48550/arXiv.2509.20230) | arXiv | — | 1 |
| Qitan Shi et al. | [ReTrack: Data Unlearning in Diffusion Models through Redirecting the Denoising Trajectory](https://doi.org/10.48550/arXiv.2509.13007) | arXiv | [GitHub](https://github.com/sqt24/ReTrack) | 1 |
| Betty Mayeku, Sandra Hummel, Parisa Memarmoshrefi | [Machine Unlearning for Responsible and Adaptive AI in Education](https://doi.org/10.48550/arXiv.2509.10590) | arXiv | — | 1 |
| A. Balordi et al. | [Tackling Federated Unlearning as a Parameter Estimation Problem](https://doi.org/10.48550/arXiv.2508.19065) | arXiv | [GitHub](https://github.com/lorenzomanini/FedUnlearn-PE) | 1 |
| Nicolò Romandini et al. | [FedUP: Efficient Pruning-based Federated Unlearning for Model Poisoning Attacks](https://doi.org/10.48550/arXiv.2508.13853) | arXiv | — | 1 |
| Xindi Fan et al. | [IMU: Influence-guided Machine Unlearning](https://doi.org/10.48550/arXiv.2508.01620) | arXiv | [GitHub](https://github.com/goodluckisallyouneed/IMU) | 1 |
| Josep Domingo-Ferrer, N. Jebreel, David S'anchez | [Efficient Unlearning with Privacy Guarantees](https://doi.org/10.48550/arXiv.2507.04771) | arXiv | [GitHub](https://github.com/najeebjebreel/EUPG) | 1 |
| Haochen Han et al. | [Unlearning the Noisy Correspondence Makes CLIP More Robust](https://doi.org/10.48550/arXiv.2507.03434) | arXiv | [GitHub](https://github.com/hhc1997/NCU) | 1 |
| Soumya Roy et al. | [NOVO: Unlearning-Compliant Vision Transformers](https://doi.org/10.48550/arXiv.2507.03281) | arXiv | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 1 |
| Yian Wang, Ali Ebrahimpour Boroojeny, Hari Sundaram | [On the Necessity of Output Distribution Reweighting for Effective Class Unlearning](https://doi.org/10.48550/arXiv.2506.20893) | arXiv | — | 1 |
| Prabhav Sanga, Jaskaran Singh, A. K. Dubey | [Train Once, Forget Precisely: Anchored Optimization for Efficient Post-Hoc Unlearning](https://doi.org/10.48550/arXiv.2506.14515) | arXiv | — | 1 |
| Yuwen Tan, Boqing Gong | [Lifting Data-Tracing Machine Unlearning to Knowledge-Tracing for Foundation Models](https://doi.org/10.48550/arXiv.2506.11253) | arXiv | — | 1 |
| Liou Tang, James B. D. Joshi, Ashish Kundu | [Apollo: A Posteriori Label-Only Membership Inference Attack Towards Machine Unlearning](https://doi.org/10.48550/arXiv.2506.09923) | arXiv | — | 1 |
| Jacob L. Block, Aryan Mokhtari, Sanjay Shakkottai | [Machine Unlearning under Overparameterization](https://doi.org/10.48550/arXiv.2505.22601) | arXiv | [GitHub](https://github.com/jacob-block/overparameterized-unlearning) | 1 |
| Le Ma et al. | [Losing is for Cherishing: Data Valuation Based on Machine Unlearning and Shapley Value](https://doi.org/10.48550/arXiv.2505.16147) | arXiv | — | 1 |
| Hanyu Duan et al. | [Ready2Unlearn: A Learning-Time Approach for Preparing Models with Future Unlearning Readiness](https://doi.org/10.48550/arXiv.2505.10845) | arXiv | [HF](https://huggingface.co/meta-llama/Llama-3.2-1B) | 1 |
| Yaxian Hu, Bernhard Scholkopf, Amartya Sanyal | [Online Learning and Unlearning](https://doi.org/10.48550/arXiv.2505.08557) | arXiv | — | 1 |
| Xuran Li et al. | [PRUNE: A Patching Based Repair Framework for Certifiable Unlearning of Neural Networks](https://doi.org/10.48550/arXiv.2505.06520) | arXiv | — | 1 |
| Abha Jha et al. | [Backdoor Defense in Diffusion Models via Spatial Attention Unlearning](https://doi.org/10.48550/arXiv.2504.18563) | arXiv | — | 1 |
| Xiaohua Feng et al. | [A Neuro-inspired Interpretation of Unlearning in Large Language Models through Sample-level Unlearning Difficulty](https://doi.org/10.48550/arXiv.2504.06658) | arXiv | [GitHub](https://github.com/unitaryai/detoxify) | 1 |
| H. Lee et al. | [Node-level Contrastive Unlearning on Graph Neural Networks](https://doi.org/10.48550/arXiv.2503.02959) | arXiv | — | 1 |
| Bo Yang | [CE-U: Cross Entropy Unlearning](https://doi.org/10.48550/arXiv.2503.01224) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Weipeng Jiang et al. | [Holistic Audit Dataset Generation for LLM Unlearning via Knowledge Graph Traversal and Redundancy Removal](https://doi.org/10.48550/arXiv.2502.18810) | arXiv | — | 1 |
| Mingliang Hou et al. | [PrivacyCD: Hierarchical Unlearning for Protecting Student Privacy in Cognitive Diagnosis](https://doi.org/10.48550/arXiv.2511.03966) | arXiv | — | 1 |
| Mingliang Hou et al. | [P-MIA: A Profiled-Based Membership Inference Attack on Cognitive Diagnosis Models](https://doi.org/10.48550/arXiv.2511.04716) | arXiv | — | 1 |
| Tomoya Yamashita et al. | [Sparse-Autoencoder-Guided Internal Representation Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2509.15631) | arXiv | [GitHub](https://github.com/tatsu-lab/alpaca) | 1 |
| Yisheng Zhong, Zhengbang Yang, Zhuangdi Zhu | [Hierarchical Federated Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2510.17895) | arXiv | — | 1 |
| Tomoya Yamashita et al. | [Concept Unlearning in Large Language Models via Self-Constructed Knowledge Triplets](https://doi.org/10.48550/arXiv.2509.15621) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Jiaxing Miao et al. | [CUFG: Curriculum Unlearning Guided by the Forgetting Gradient](https://doi.org/10.48550/arXiv.2509.14633) | arXiv | [GitHub](https://github.com/JiaxingMiao606/CUFG) | 1 |
| Jinwei Hu et al. | [FALCON: Fine-grained Activation Manipulation by Contrastive Orthogonal Unalignment for Large Language Model](https://doi.org/10.48550/arXiv.2502.01472) | arXiv | [GitHub](https://github.com/CharlesJW222/FALCON) | 1 |
| Agnieszka Polowczyk et al. | [Memory Self-Regeneration: Uncovering Hidden Knowledge in Unlearned Models](https://doi.org/10.48550/arXiv.2510.03263) | arXiv | [GitHub](https://github.com/gmum/MemoRa) | 1 |
| Taozhao Chen et al. | [Feature-Selective Representation Misdirection for Machine Unlearning](https://doi.org/10.48550/arXiv.2512.16297) | arXiv | — | 1 |
| Hadi Reisizadeh et al. | [Leak@k: Unlearning Does Not Make LLMs Forget Under Probabilistic Decoding](https://doi.org/10.48550/arXiv.2511.04934) | arXiv | [HF](https://huggingface.co/Jiajunruan/NPO-Fix) | 1 |
| Tatsuki Kawakami et al. | [PULSE: Practical Evaluation Scenarios for Large Multimodal Model Unlearning](https://doi.org/10.48550/arXiv.2507.01271) | arXiv | — | 1 |
| Kyomin Hwang et al. | [Uncovering the Potential Risks in Unlearning: Danger of English-only Unlearning in Multilingual LLMs](https://doi.org/10.48550/arXiv.2510.23949) | arXiv | — | 1 |
| Sungjun Cho et al. | [Reference-Specific Unlearning Metrics Can Hide the Truth: A Reality Check](https://doi.org/10.48550/arXiv.2510.12981) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Ameya Anjarlekar, S. Pombra | [LLM Unlearning using Gradient Ratio-Based Influence Estimation and Noise Injection](https://doi.org/10.48550/arXiv.2508.06467) | arXiv | [HF](https://huggingface.co/datasets/allenai/c4) | 1 |
| Dunyuan Xu et al. | [From Learning to Unlearning: Biomedical Security Protection in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2508.04192) | arXiv | — | 1 |
| Philipp Spohn et al. | [Align-then-Unlearn: Embedding Alignment for LLM Unlearning](https://doi.org/10.48550/arXiv.2506.13181) | arXiv | [GitHub](https://github.com/ExplainableML/align-then-unlearn) | 1 |
| Evelyn Ma et al. | [GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models](https://doi.org/10.48550/arXiv.2506.10946) | arXiv | — | 1 |
| Jan Bronec et al. | [Atyaephyra at SemEval-2025 Task 4: Low-Rank Negative Preference Optimization](https://arxiv.org/abs/2503.13690) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 1 |
| Arpit Garg et al. | [Stable Forgetting: Bounded Parameter-Efficient Unlearning in LLMs](https://doi.org/10.48550/arXiv.2509.24166) | arXiv | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 1 |
| Hongji Li et al. | [Towards Reasoning-Preserving Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2512.17911) | arXiv | — | 1 |
| Timothy Qian et al. | [Layered Unlearning for Adversarial Relearning](https://doi.org/10.48550/arXiv.2505.09500) | arXiv | [GitHub](https://github.com/JasxnNg/6.7960-final) | 1 |
| Ning Han et al. | [GrOCE:Graph-Guided Online Concept Erasure for Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2511.12968) | arXiv | [GitHub](https://github.com/MagicCat-AI/GrOCE) | 1 |
| Abhiram Kusumba et al. | [EraseFlow: Learning Concept Erasure Policies via GFlowNet-Driven Alignment](https://doi.org/10.48550/arXiv.2511.00804) | arXiv | [GitHub](https://github.com/Abhiramkns/EraseFlow) | 1 |
| Tong Zhang et al. | [Beyond Fixed Anchors: Precisely Erasing Concepts with Sibling Exclusive Counterparts](https://doi.org/10.48550/arXiv.2510.16342) | arXiv | — | 1 |
| Nanxiang Jiang et al. | [Erased, But Not Forgotten: Erased Rectified Flow Transformers Still Remain Unsafe Under Concept Attack](https://doi.org/10.48550/arXiv.2510.00635) | arXiv | [GitHub](https://github.com/nxjiang-jnx/ReFlux) | 1 |
| Enrico Cassano et al. | [SAEmnesia: Erasing Concepts in Diffusion Models with Supervised Sparse Autoencoders](https://arxiv.org/abs/2509.21379) | arXiv | — | 1 |
| Feng Han et al. | [VCE: Safe Autoregressive Image Generation via Visual Contrast Exploitation](https://doi.org/10.48550/arXiv.2509.16986) | arXiv | [GitHub](https://github.com/Maplebb/VCE) | 1 |
| Zixuan Fu et al. | [Robust Concept Erasure in Diffusion Models: A Theoretical Perspective on Security and Robustness](https://doi.org/10.48550/arXiv.2509.12024) | arXiv | — | 1 |
| Jinju Kim et al. | [No Encore: Unlearning as Opt-Out in Music Generation](https://doi.org/10.48550/arXiv.2509.06277) | arXiv | [GitHub](https://github.com/mokcho/mokcho) | 1 |
| Eric C. Yeats et al. | [Automating Evaluation of Diffusion Model Unlearning with (Vision-) Language Model World Knowledge](https://doi.org/10.48550/arXiv.2507.07137) | arXiv | — | 1 |
| Haipeng Fan et al. | [EAR: Erasing Concepts from Unified Autoregressive Models](https://doi.org/10.48550/arXiv.2506.20151) | arXiv | [GitHub](https://github.com/immc-lab/ear) | 1 |
| Hongguang Zhu et al. | [SAGE: Exploring the Boundaries of Unsafe Concept Domain with Semantic-Augment Erasing](https://doi.org/10.48550/arXiv.2506.09363) | arXiv | [GitHub](https://github.com/KevinLight831/SAGE) | 1 |
| Simone Facchiano et al. | [Video Unlearning via Low-Rank Refusal Vector](https://doi.org/10.48550/arXiv.2506.07891) | arXiv | [GitHub](https://github.com/simonefacchiano/Video-Unlearning) | 1 |
| Die Chen et al. | [Comprehensive Assessment and Analysis for NSFW Content Erasure in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2502.12527) | arXiv | [GitHub](https://github.com/lzws/ErasureBenchmark) | 1 |
| Zhenyu Yu, Mohd. Yamani Idna Idris, Pei Wang | [Prompt-Driven and Training-Free Forgetting Approach and Dataset for Large Language Models](https://doi.org/10.48550/arXiv.2504.12574) | arXiv | — | 1 |
| Enrico Cassano et al. | [SAEmnesia: Erasing Concepts in Diffusion Models with Sparse Autoencoders](https://doi.org/10.48550/arXiv.2509.21379) | arXiv | — | 1 |
| Anudeep Das et al. | [Do Concept Replacement Techniques Really Erase Unacceptable Concepts?](https://doi.org/10.48550/arXiv.2506.08991) | arXiv | [GitHub](https://github.com/DataSmithLab/Moderator) | 1 |
| Nuo Xu et al. | [VideoEraser: Concept Erasure in Text-to-Video Diffusion Models](https://doi.org/10.18653/v1/2025.emnlp-main.304) | arXiv | [GitHub](https://github.com/bluedream02/VideoEraser) | 1 |
| K. P. K. Devan et al. | [Machine Unlearning In Recommendation Systems](https://doi.org/10.1109/ictest64710.2025.11042432) |  | — | 0 |
| Feng Han et al. | [DuMo: Dual Encoder Modulation Network for Precise Concept Erasure](https://doi.org/10.1609/aaai.v39i3.32343) | AAAI | [GitHub](https://github.com/Maplebb/DuMo) | 0 |
| Huu-Tien Dang et al. | [On Effects of Steering Latent Representation for Large Language Model Unlearning](https://doi.org/10.1609/aaai.v39i22.34544) | AAAI | [GitHub](https://github.com/RebelsNLU-jaist/llm-unlearning) | 0 |
| Qiming Guo et al. | [Efficient Unlearning for Spatio-temporal Graph (Student Abstract)](https://doi.org/10.1609/aaai.v39i28.35259) | AAAI | [GitHub](https://github.com/wenlu-lab/STEPS) | 0 |
| Xue Jiang et al. | [Large Language Model Unlearning for Source Code](https://doi.org/10.48550/arXiv.2506.17125) | AAAI | [GitHub](https://github.com/dinhngoctuyen4125/PROD_test) | 0 |
| Chao-Hui He et al. | [Forgetting by Pruning: Data Deletion in Join Cardinality Estimation](https://doi.org/10.48550/arXiv.2511.20293) | AAAI | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Feng Guo et al. | [Beyond Superficial Forgetting: Thorough Unlearning through Knowledge Density Estimation and Block Re-insertion](https://doi.org/10.48550/arXiv.2511.11667) | AAAI | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Fuyao Zhang et al. | [Oblivionis: A Lightweight Learning and Unlearning Framework for Federated Large Language Models](https://doi.org/10.48550/arXiv.2508.08875) | AAAI | [GitHub](https://github.com/fyzhang1/Oblivionis) | 0 |
| Jiaqi Li et al. | [Forget the Token and Pixel: Rethinking Gradient Ascent for Concept Unlearning in Multimodal Generative Models](https://doi.org/10.18653/v1/2025.findings-acl.630) | ACL | [GitHub](https://github.com/DiWHNJ/FTTP) | 0 |
| Tianle Gu et al. | [From Evasion to Concealment: Stealthy Knowledge Unlearning for LLMs](https://doi.org/10.18653/v1/2025.findings-acl.535) | ACL | — | 0 |
| Ayana Niwa, Masahiro Kaneko, Kentaro Inui | [Rectifying Belief Space via Unlearning to Harness LLMs’ Reasoning](https://doi.org/10.18653/v1/2025.findings-acl.1285) | ACL | — | 0 |
| Haomin Zhuang et al. | [SEUF: Is Unlearning One Expert Enough for Mixture-of-Experts LLMs?](https://doi.org/10.18653/v1/2025.acl-long.424) | ACL | [GitHub](https://github.com/byungsoo-oh/ml-systems-papers) | 0 |
| S. Vasilev et al. | [UvA-DARE (Digital Academic Repository) Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target Self-Distillation](https://www.semanticscholar.org/paper/97ba9e39c1d2969b354b0cd3fcdc39dc253bf576) | ACL | — | 0 |
| Hwan Chang, Hwanhee Lee | [Which Retain Set Matters for LLM Unlearning? A Case Study on Entity Unlearning](https://doi.org/10.18653/v1/2025.findings-acl.310) | ACL | — | 0 |
| Stefan Vasilev et al. | [Unilogit: Robust Machine Unlearning for LLMs Using Uniform-Target Self-Distillation](https://doi.org/10.18653/v1/2025.findings-acl.1154) | ACL | — | 0 |
| Fan Qi et al. | [FORGET ME: Federated Unlearning for Face Generation Models](https://doi.org/10.1145/3746027.3754935) | ACM MM | [GitHub](https://github.com/FanQi-AI/FFGU) | 0 |
| Rutger Hendrix et al. | [Pre-Forgettable Models: Prompt Learning as a Native Mechanism for Unlearning](https://doi.org/10.1145/3746027.3758171) | ACM MM | [GitHub](https://github.com/perceivelab/PreForgettableModels) | 0 |
| Muhammad Shaheryar, Jong Taek Lee, Soon Ki Jung | [Unlearn and Protect: Selective Identity Removal in Diffusion Models for Privacy Preservation](https://doi.org/10.1145/3672608.3707842) | ACM Symposium on Applied Computing | — | 0 |
| Yang Li et al. | [Cross-User Federated Recommendation Unlearning](https://doi.org/10.1145/3749990) | ACM TIST | — | 0 |
| Yi Li et al. | [Graph Unlearning System with Subgraph De-Isolation Measures](https://doi.org/10.1145/3750734) | ACM Transactions on Autonomous and Adaptive Systems | — | 0 |
| Changsheng Wang et al. | [LLM Unlearning on Noisy Forget Sets: A Study of Incomplete, Rewritten, and Watermarked Data](https://doi.org/10.1145/3733799.3762973) | AISec@CCS | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Christian Troiani et al. | [Federated Unlearning using Tree-based Sharding](https://doi.org/10.1145/3733799.3762971) | AISec@CCS | — | 0 |
| Virgile Dine, Teddy Furon, Charly Faure | [Improving Unlearning with Model Updates Probably Aligned with Gradients](https://doi.org/10.1145/3733799.3762975) | AISec@CCS | [GitHub](https://github.com/owl1996/UnlearningFocusVector) | 0 |
| Giuseppe Gallipoli, Luca Cagliero | [In-Context Unlearning for Text Summarization using Large Language Models](https://doi.org/10.1109/AICT67988.2025.11268691) | Advanced Industrial Conference on Telecommunications | — | 0 |
| Fengda Zhao et al. | [Rapid federated unlearning with tuning parameters based on fisher information matrix](https://doi.org/10.1007/s10489-025-06593-0) | Applied Intelligence | — | 0 |
| Jing Zhang et al. | [CAUA: A Realistic and Effective Attack on Machine Unlearning Under Limited Information](https://doi.org/10.1109/ACSAC67867.2025.00080) | Asia-Pacific Computer Systems Architecture Conference | [GitHub](https://github.com/ballinyz/CAUA-A-Realistic-and-Effective-Attack-on-Machine-Unlearning-under-Limited-Information-artifact) | 0 |
| Lei Cen, Guohao Li, Li Yang | [A Scenario-Driven Efficient Federated Unlearning Method for Multi-Granularity Data Removal](https://doi.org/10.1109/BigDIA68682.2025.11383040) | BigDIA | — | 0 |
| Yiming Li et al. | [Merging Erasure and Retention for Balanced Graph Unlearning](https://doi.org/10.1109/cac67268.2025.11486964) | CAC | — | 0 |
| Jin Huang et al. | [Prompt-Tuning for Recommendation Unlearning](https://doi.org/10.1109/cai64502.2025.00152) | CAI | — | 0 |
| Xiaocui Dang et al. | [A Novel Scheme for Recommendation Unlearning Verification (RUV) Using Non-Influential Trigger Data](https://doi.org/10.1109/ccnc54725.2025.10976014) | CCNC | — | 0 |
| Jinyu Hong et al. | [Enhancing Graph Unlearning with Semantic and Structural Counterfactual Distillation](https://doi.org/10.1109/globecom59602.2025.11432697) | CCS | — | 0 |
| Ebuka Chinaechetam Nkoro et al. | [Towards a Privacy Preserving Framework for Mobility as a Service (MaaS)](https://doi.org/10.1109/CIEES66347.2025.11300101) | CIEES | — | 0 |
| Preethi Gurumurthy, P. K. Srijith | [Pseudo-Inverse Prefix Tuning for Effective Unlearning in LLMs](https://doi.org/10.1145/3746252.3760939) | CIKM | — | 0 |
| Ziheng Chen et al. | [FROG: Fair Removal on Graph](https://doi.org/10.1145/3746252.3761341) | CIKM | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Samaneh Mohammadi et al. | [EFU: Enforcing Federated Unlearning via Functional Encryption](https://doi.org/10.1145/3746252.3761091) | CIKM | — | 0 |
| Andrea D'Angelo et al. | [ERASURE: A Modular and Extensible Framework for Machine Unlearning](https://doi.org/10.1145/3746252.3761627) | CIKM | [GitHub](https://github.com/aiim-research/ERASURE) | 0 |
| Nexhi Sula et al. | [Silver Linings in the Shadows: Harnessing Membership Fingerprinting for Machine Unlearning](https://doi.org/10.1109/CNS66487.2025.11195030) | CNS | — | 0 |
| Byung Hyun Lee, Sungjin Lim, Se Young Chun | [Localized Concept Erasure for Text-to-Image Diffusion Models Using Training-Free Gated Low-Rank Adaptation](https://doi.org/10.1109/cvpr52734.2025.01733) | CVPR | [GitHub](https://github.com/Hyun1A/GLoCE) | 0 |
| Jundong Chen et al. | [Learning to Unlearn for Bayesian Personalized Ranking via Influence Function](https://doi.org/10.23919/cje.2023.00.417) | Chinese Journal of Electronics | — | 0 |
| Yifei Zou et al. | [Conditional Machine Unlearning: Balancing Privacy and Regulation](https://doi.org/10.23919/cje.2024.00.343) | Chinese journal of electronics | — | 0 |
| Enting Guo, Chunhua Su, Peng Li | [Efficient unlearning for data security in deep learning systems](https://doi.org/10.1093/comjnl/bxaf031) | Computer/law journal | — | 0 |
| Long Cai, Ke Gu, Jiaqi Lei | [Defending Federated Learning System from Poisoning Attacks via Efficient Unlearning](https://doi.org/10.32604/cmc.2025.061377) | Computers, Materials &amp; Continua | — | 0 |
| R. Karn et al. | [Unlearning in Decision Tree Classifiers and Microcontroller Implementations](https://doi.org/10.1109/CAI64502.2025.00114) | Conference on Algebraic Informatics | — | 0 |
| Jin Huang et al. | [Prompt-Tuning for Recommendation Unlearning](https://doi.org/10.1109/CAI64502.2025.00152) | Conference on Algebraic Informatics | — | 0 |
| Ashley Etheridge et al. | [Tackling Sequential Entanglement in Split Unlearning](https://doi.org/10.1109/MIPR67560.2025.00053) | Conference on Multimedia Information Processing and Retrieval | [GitHub](https://github.com/AshleyJoyE/Split-Unlearning) | 0 |
| Xiaocui Dang et al. | [A Novel Scheme for Recommendation Unlearning Verification (RUV) Using Non-Influential Trigger Data](https://doi.org/10.1109/CCNC54725.2025.10976014) | Consumer Communications and Networking Conference | — | 0 |
| Xinyi Sun et al. | [Unlearning the Spurious Correlations for Improving Generalization of Language Models](https://doi.org/10.3724/2096-7004.di.2025.0180) | Data Intelligence | — | 0 |
| Hrishikesh Kulkarni, Nazli Goharian, O. Frieder | [GUIR at SemEval-2025 Task 4: Adaptive Weight Tuning with Gradual Negative Matching for LLM Unlearning](https://www.semanticscholar.org/paper/5c80117ab9edc3cc7a8140646081a7dcb4fa0ac9) | ECIR (3) | — | 0 |
| Taiming Lu, Philipp Koehn | [Learn and Unlearn: Addressing Misinformation in Multilingual LLMs](https://doi.org/10.18653/v1/2025.emnlp-main.516) | EMNLP | [GitHub](https://github.com/TaiMingLu/learn-unlearn) | 0 |
| Advit Deepak et al. | [Identifying Unlearned Data in LLMs via Membership Inference Attacks](https://doi.org/10.18653/v1/2025.emnlp-main.551) | EMNLP | [GitHub](https://github.com/AdvitDeepak/fuma) | 0 |
| Yixin Wan et al. | [Not Every Token Needs Forgetting: Selective Unlearning Balancing Forgetting and Utility in Large Language Models](https://doi.org/10.18653/v1/2025.findings-emnlp.96) | EMNLP | — | 0 |
| Bang Trinh Tran To, Thái Hoàng Lê | [Harry Potter is Still Here! Probing Knowledge Leakage in Targeted Unlearned Large Language Models](https://doi.org/10.18653/v1/2025.findings-emnlp.778) | EMNLP | [GitHub](https://github.com/Rachel1809/LURK) | 0 |
| Zekun Wang et al. | [Human-Inspired Obfuscation for Model Unlearning: Local and Global Strategies with Hyperbolic Representations](https://doi.org/10.18653/v1/2025.findings-emnlp.774) | EMNLP | — | 0 |
| Anda Cheng, Wei Huang, Yinggui Wang | [A Fully Probabilistic Perspective on Large Language Model Unlearning: Evaluation and Optimization](https://doi.org/10.18653/v1/2025.emnlp-main.452) | EMNLP | — | 0 |
| Linxi Xie et al. | [Reveal and Release: Iterative LLM Unlearning with Self-generated Data](https://doi.org/10.48550/arXiv.2509.14624) | EMNLP | [GitHub](https://github.com/LafouCC/Reveal-and-Release) | 0 |
| Aly M. Kassem et al. | [R EVIVING Y OUR MNEME * Predicting the Side Effects of LLM Unlearning and Fine-Tuning via Sparse Model Diffing](https://www.semanticscholar.org/paper/337a1366195e2eb52b9f18c38124c5e01ff1c41b) | EMNLP | — | 0 |
| Linxi Xie et al. | [Reveal and Release: Iterative LLM Unlearning with Self-generated Data](https://doi.org/10.18653/v1/2025.findings-emnlp.1298) | EMNLP | [GitHub](https://github.com/LafouCC/Reveal-and-Release) | 0 |
| Aly M. Kassem et al. | [REVIVING YOUR MNEME: Predicting The Side Effects of LLM Unlearning and Fine-Tuning via Sparse Model Diffing](https://doi.org/10.18653/v1/2025.emnlp-main.1641) | EMNLP | — | 0 |
| Guangzhi Sun et al. | [Unlearning vs. Obfuscation: Are We Truly Removing Knowledge?](https://doi.org/10.18653/v1/2025.emnlp-main.577) | EMNLP | [GitHub](https://github.com/potsawee/unlearning-dfmcq) | 0 |
| Alexander Krawczyk, Alex Gepperth | [Continual Unlearning through Memory Suppression](https://doi.org/10.14428/esann/2025.es2025-102) | ESANN proceesdings | [GitHub](https://github.com/Alexk1704/scclv2) | 0 |
| Fudu Xing et al. | [A continuous verification mechanism for ensuring client data forgetfulness in Federated Unlearning](https://doi.org/10.1016/j.engappai.2025.112553) | Engineering Applications of Artificial Intelligence | — | 0 |
| H. N. Tran et al. | [FAST: A pioneering unlearning framework integrating fine-tuning, adverse training, and student–teacher methods](https://doi.org/10.1016/j.jestch.2025.101996) | Engineering Science and Technology, an International Journal | — | 0 |
| Shao Shen et al. | [Machine Unlearning for Streaming Forgetting](https://doi.org/10.48550/arXiv.2507.15280) | European Conference on Artificial Intelligence | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 0 |
| Jinyung Hong et al. | [Enhancing Graph Unlearning with Semantic and Structural Counterfactual Distillation](https://doi.org/10.1109/GLOBECOM59602.2025.11432697) | Global Communications Conference | — | 0 |
| Shohei Yamamoto, Soh Yoshida, M. Muneyasu | [Robust Image Classification via Centroid-Aware Machine Unlearning of Noisy Annotations](https://doi.org/10.1109/GCCE65946.2025.11275131) | Global Conference on Consumer Electronics | — | 0 |
| M. Jonathan, Windy Gambetta | [A Comparative Study of Nabla Tau and SCAR Unlearning Algorithms for CNN-Based Facial Race Classification](https://doi.org/10.1109/ICAICTA67604.2025.11335106) | ICAICTA | — | 0 |
| Melvin Kent Jonathan, Windy Gambetta | [A Comparative Study of Nabla Tau and SCAR Unlearning Algorithms for CNN-Based Facial Race Classification](https://doi.org/10.1109/icaicta67604.2025.11335106) | ICAICTA | — | 0 |
| Zhifei Luo et al. | [Signed Graph Unlearning](https://doi.org/10.48550/arXiv.2510.26092) | ICASSP | — | 0 |
| Nicolas Renout et al. | [Fast Unlearning Techniques for Neural Network Prediction and Classification Algorithms](https://doi.org/10.1109/ICC52391.2025.11161398) | ICC | — | 0 |
| Parthaw Goswami, Md Khairul Islam, Ashfak Yeafi | [PrivEraserVerify: Efficient, Private, and Verifiable Federated Unlearning](https://doi.org/10.1109/iccit68739.2025.11491311) | ICCIT | — | 0 |
| K. Thakral et al. | [Genμ: The Generative Machine Unlearning Challenge](https://doi.org/10.1109/ICCVW69036.2025.00266) | ICCV | — | 0 |
| Hongyi Nie et al. | [E RASING C ONCEPT C OMBINATIONS FROM T EXT - TO - I MAGE D IFFUSION M ODEL](https://www.semanticscholar.org/paper/3bfe72f50d55b4050b9b2155c70ef3f1da781ca7) | ICCV | — | 0 |
| Anant Gupta et al. | [Self-Erasing Neural Networks (SENNs): A Neurogenesis-Inspired Framework for GDPR-Compliant Machine Unlearning](https://doi.org/10.1109/ICDDS67737.2025.11344675) | ICDDS | — | 0 |
| Wenhan Wu et al. | [Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning](https://doi.org/10.1109/icde65448.2025.00200) | ICDE | [GitHub](https://github.com/Anya-bond/Awesome-Privacy-RecSys) | 0 |
| Liu Li et al. | [Fairness-aware Graph Unlearning with Knowledge Distillation](https://doi.org/10.1109/swc65939.2025.00109) | ICICS | — | 0 |
| Xiaohua Feng et al. | [Controllable Unlearning for Image-to-Image Generative Models via ϵ-Constrained Optimization](https://www.semanticscholar.org/paper/470c1c5e9885cd170bb638c100e2a0f73a4c4916) | ICLR | — | 0 |
| Yahya Alkhatib, Muhammad Jamal, Wee Peng Tay | [Conformal Unlearning: A New Paradigm for Unlearning in Conformal Predictors](https://arxiv.org/abs/2508.03245) | ICLR Conference Withdrawn Submission | [GitHub](https://github.com/chenyaofo/pytorch-cifar-models) | 0 |
| Youssef Allouah, R. Guerraoui, Sanmi Koyejo | [Distributional Machine Unlearning via Selective Data Removal](https://arxiv.org/abs/2507.15112) | ICLR Poster | [GitHub](https://github.com/ysfalh/unlearning-distribution) | 0 |
| Keivan Rezaei et al. | [Revisiting the Past: Data Unlearning with Model State History](https://arxiv.org/abs/2506.20941) | ICLR Poster | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| Puwei Lian et al. | [Achieving Zero-Glance Unlearning with Data-Free Inversion and Selective Parameters Suppression](https://doi.org/10.1109/ICME59968.2025.11209383) | ICME | — | 0 |
| Haoxuan Ji et al. | [Towards Aligned Data Forgetting via Twin Machine Unlearning](https://doi.org/10.1109/ICME59968.2025.11208918) | ICME | [GitHub](https://github.com/abc321123444/TWIN-unlearning) | 0 |
| Yufan Liu et al. | [Corer: Concept Residue Erasing in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICME59968.2025.11210155) | ICME | — | 0 |
| Haodong Zhang, Liu Yang, Zihan Jiang | [RKU: Relevant Knowledge-aware Unlearning for Federated Continual Learning](https://doi.org/10.1109/ICME59968.2025.11210106) | ICME | [GitHub](https://github.com/zhanghad/RKU) | 0 |
| Puwei Lian et al. | [Achieving Zero-Glance Unlearning with Data-Free Inversion and Selective Parameters Suppression](https://doi.org/10.1109/icme59968.2025.11209383) | ICME | — | 0 |
| Hussien AbdelRaouf, Mohamed I. Ibrahem | [Federated Unlearning: Techniques, Trends, and Future Directions](https://doi.org/10.1109/icmi65310.2025.11141148) | ICMI | — | 0 |
| Xiuyuan Wang et al. | [Efficient Source-free Unlearning via Energy-Guided Data Synthesis and Discrimination-Aware Multitask Optimization](https://www.semanticscholar.org/paper/b4cc7b4d8004ba085563fcdaf67359dca0d98a43) | ICML | — | 0 |
| Ye He, Wei Jiang, Bin Wang | [SCFU: A Collaborative Federated Unlearning Algorithm with Weighted Penalty and Adaptive Rewards](https://doi.org/10.1109/icpads67057.2025.11323166) | ICPADS | — | 0 |
| Jinghan Xu et al. | [GAIA-UL: Surgical Unlearning of Visual Knowledge via Causally-Guided Orthogonalization](https://doi.org/10.1109/ICPADS67057.2025.11323156) | ICPADS | — | 0 |
| Siyun Guo, Leixiao Li, Jinze Du | [Joint-FU: Blockchain-Based Federated Feature Unlearning Method](https://doi.org/10.1109/ICPADS67057.2025.11322875) | ICPADS | — | 0 |
| Sheetal Sehgal, Himani Bansal, Ankita Verma | [Extending GraphEraser: Scalable and Secure Partition-Based Graph Unlearning on Large-Scale Network](https://doi.org/10.1109/ICTBIG68706.2025.11323936) | ICTBIG | — | 0 |
| Sheetal Sehgal, Himani Bansal, Ankita Verma | [Extending GraphEraser: Scalable and Secure Partition-Based Graph Unlearning on Large-Scale Network](https://doi.org/10.1109/ictbig68706.2025.11323936) | ICTBIG | — | 0 |
| Farzeen Basith et al. | [Multi-Agent Machine Unlearning in Healthcare AI: Neural, Symbolic, and Coordination](https://doi.org/10.1109/ICTCT69201.2025.00036) | ICTCT | — | 0 |
| D. K et al. | [Machine Unlearning In Recommendation Systems](https://doi.org/10.1109/ICTEST64710.2025.11042432) | ICTEST | — | 0 |
| Natalie Lang, Alon Helvits, Nir Shlezinger | [Memory-Efficient Distributed Unlearning](https://doi.org/10.1109/ACCESS.2026.3663428) | IEEE Access | [GitHub](https://github.com/alonhelvits/FedUL) | 0 |
| Win Kent Ong, Chee Seng Chan | [Maverick++: Collaboration-Free Unlearning for Medical Privacy Preservation in Healthcare Federated Systems](https://doi.org/10.1109/ACCESS.2025.3611992) | IEEE Access | [GitHub](https://github.com/OngWinKent/Maverick) | 0 |
| Hyun Kwon, Jang-Woon Baek | [A Targeted Machine Unlearning Method for Sensitive Data in Military Helicopter Models](https://doi.org/10.1109/ACCESS.2025.3631684) | IEEE Access | — | 0 |
| Qingyu Tan, Yan Li, Byeong‐Seok Shin | [LAFUL: Lesion-Aware Federated Unlearning via Channel-Wise Gradient Masking and Feature Distillation](https://doi.org/10.1109/bibm66473.2025.11357193) | IEEE International Conference on Bioinformatics and Biomedicine | — | 0 |
| Tejo Vardhan Kattamuri et al. | [Securing Federated Learning: Anomaly Detection and Mitigation via VAEs and Unlearning](https://doi.org/10.1109/CONECCT65861.2025.11306723) | IEEE International Conference on Electronics, Computing and Communication Technologies | — | 0 |
| Chenghao Shao et al. | [Feature Unlearning for EEG-Based Seizure Prediction](https://doi.org/10.1109/JIOT.2024.3514666) | IEEE IoT-J | — | 0 |
| Pengfei Wang et al. | [Eliminating Poor-Quality Data Impacts from Multiple Participants with Federated Unlearning](https://doi.org/10.1109/iwqos65803.2025.11143467) | IEEE J. Sel. Areas Commun | — | 0 |
| Hai Anh Tran | [ULNet: Federated Unlearning for SDN Control-Plane Anomaly Detection](https://doi.org/10.1109/lnet.2025.3645209) | IEEE Networking Letters | — | 0 |
| Md Serajun Nabi, Dema Yuden, Mohammad Faizal Ahmad Fauzi | [Deepfake Detection Using ResNet50V2 with Machine Unlearning Integration](https://doi.org/10.1109/TENCON66050.2025.11375020) | IEEE Region 10 Conference | — | 0 |
| Jiaquan Liang et al. | [Hypergraph Unlearning: A Size-Based Hyperedge Selection and Coverage Aggregation Approach](https://doi.org/10.1109/tifs.2025.3580218) | IEEE T-IFS | [GitHub](https://github.com/Alchemistqqqq/HyperGraph-Unlearning) | 0 |
| Chenxi Hu et al. | [Copyright Protection of General Information via Simulation Task Supervision](https://doi.org/10.1109/TIFS.2025.3638667) | IEEE T-IFS | — | 0 |
| Lei Zhou, Youwen Zhu | [Model Inversion Attack Against Federated Unlearning](https://doi.org/10.1109/TIFS.2026.3666295) | IEEE T-IFS | — | 0 |
| Sayedmoslem Shokrolahi, I.-M. Kim | [MaxDiv: Zero-Shot Machine Unlearning via Distributionally Divergent Erasing Samples](https://doi.org/10.1109/tai.2025.3627517) | IEEE TAI | — | 0 |
| Xinyi Sheng et al. | [FUBA: Backdoor Federated Learning via Federated Unlearning](https://doi.org/10.1109/tai.2025.3630110) | IEEE TAI | [GitHub](https://github.com/stcebra/FUBA) | 0 |
| Yunjiao Lei et al. | [LLM-Based Data Augmentation Method in Reinforcement Learning With Machine-Unlearning and Fine-Tuning](https://doi.org/10.1109/tbdata.2025.3630807) | IEEE TBD | — | 0 |
| Kun Gao et al. | [Hidden Threats in Federated Unlearning: Camouflaged Poisoning Attacks and Their Unlearning Consequences](https://doi.org/10.1109/tdsc.2025.3630811) | IEEE TDSC | — | 0 |
| Xiangshan Gao et al. | [A2E: Black-Box Anti-Adversarial Example Based Watermarking to Verify Federated Unlearning](https://doi.org/10.1109/tdsc.2025.3598987) | IEEE TDSC | — | 0 |
| Lefeng Zhang et al. | [Trojan Attack on Machine Unlearning: Security Risk of the Right to be Forgotten](https://doi.org/10.1109/TDSC.2025.3567848) | IEEE TDSC | — | 0 |
| Wenjun Zeng et al. | [FU-PA: Federated Unlearning via Parameters Adjustment](https://doi.org/10.1109/tetci.2025.3576117) | IEEE TETCI | — | 0 |
| Xinghao Li et al. | [Navigating Unlearning in Medical AI: A Framework for Diabetic Retinopathy Classification](https://doi.org/10.1109/tetci.2025.3641713) | IEEE TETCI | — | 0 |
| Haodong Zhang, Liu Yang, Zihan Jiang | [RKU: Relevant Knowledge-aware Unlearning for Federated Continual Learning](https://doi.org/10.1109/icme59968.2025.11210106) | IEEE TKDE | [GitHub](https://github.com/zhanghad/RKU) | 0 |
| Zhenwei Wang et al. | [Inverse Feature Consistency Federated Unlearning for Vision-Language Model](https://doi.org/10.1109/tmc.2025.3629294) | IEEE TMC | — | 0 |
| Juncheng Jia et al. | [Fed$n$nP: Federated Unlearning With Multiple Client Set Partitions](https://doi.org/10.1109/tmc.2025.3586441) | IEEE TMC | — | 0 |
| Yujun Cheng et al. | [SeFUL: A Selective Federated Unlearning Framework for Client Data Heterogeneity in Intelligent Wireless Networks](https://doi.org/10.1109/tmc.2025.3637775) | IEEE TMC | — | 0 |
| J. Jia et al. | [Fed<inline-formula><tex-math notation="LaTeX">$n$</tex-math><alternatives><mml:math><mml:mi>n</mml:mi></mml:math><inline-graphic xlink:href="jia-ieq1-3586441.gif"/></alternatives></inline-formula>P: Federated Unlearning With Multiple Client Set Partitions](https://doi.org/10.1109/TMC.2025.3586441) | IEEE TMC | — | 0 |
| Yue Cui, Man Hon Cheung | [The Price of Forgetting: Incentive Mechanism Design for Machine Unlearning](https://doi.org/10.1109/TMC.2025.3582904) | IEEE TMC | — | 0 |
| Xiangyun Tang et al. | [LVFUS: Vertical Federated Unlearning for Intelligent Network Security via Adaptive Optimizer Switching](https://doi.org/10.1109/tnse.2025.3637602) | IEEE TNSE | — | 0 |
| Yanghe Pan et al. | [The Right to Be Forgotten Versus the Need to Be Remembered: Efficient Personalized Federated Unlearning With Optimal Incentives](https://doi.org/10.1109/tnse.2025.3597640) | IEEE TNSE | — | 0 |
| Li Duan et al. | [FedHydra: towards Parameter-Efficient and Backdoor-Resistant Federated Unlearning in Human-Centric Metaverse Service](https://doi.org/10.1109/tsc.2025.3620758) | IEEE TSC | — | 0 |
| Jingyi Li et al. | [Efficient Federated Metric Learning and Machine Unlearning Based on Prototype Distillation](https://doi.org/10.1109/tsc.2025.3645435) | IEEE TSC | — | 0 |
| Sakshi Ranjan, Dheeraj Mishra, Sanjay Kumar Singh | [Mitigating Catastrophic Forgetting in Molecular Property Prediction via Refresh Learning and Pareto Optimization](https://doi.org/10.1109/TCBBIO.2025.3571046) | IEEE Transactions on Computational Biology and Bioinformatics | — | 0 |
| Yuhong Huang et al. | [FedUP: Federated Unlearning With Prototypes](https://doi.org/10.1109/tsusc.2025.3612138) | IEEE Transactions on Sustainable Computing | — | 0 |
| Yi Zhang et al. | [Hierarchical Dual-Strategy Unlearning for Biomedical and Healthcare Intelligence Using Imperfect and Privacy-Sensitive Medical Data](https://doi.org/10.48550/arXiv.2511.19498) | IEEE transactions on consumer electronics | — | 0 |
| Jiande Huang et al. | [MAFRO: Optimal-Granularity Fuzzy Decision Rule-Based Classification Architecture for Attribute Unlearning](https://doi.org/10.1109/TFUZZ.2025.3586297) | IEEE transactions on fuzzy systems | — | 0 |
| Haitham Y. Adarbah, Kewei Sha, Afzel Noore | [Toward Design of a Scalable Federated Unlearning Framework for Trustworthy Edge Intelligence](https://doi.org/10.1145/3769102.3774631) | IFIP International Information Security Conference | — | 0 |
| Hongyi Lyu et al. | [Fine-Grained and Efficient Self-Unlearning with Layered Iteration](https://doi.org/10.24963/ijcai.2025/850) | IJCAI | [GitHub](https://github.com/Hongyi-Lyu-MQ/SULI) | 0 |
| Huiqiang Chen et al. | [Zero-Shot Machine Unlearning with Proxy Adversarial Data Generation](https://doi.org/10.48550/arXiv.2507.21738) | IJCAI | — | 0 |
| Fnu Shivam et al. | [CURE: Centroid-guided Unsupervised Representation Erasure for Facial Recognition Systems](https://doi.org/10.1109/IJCB65343.2025.11410631) | IJCB | [GitHub](https://github.com/Shivam101s/CURE_FaceUnlearning) | 0 |
| Zhenkang Hu, Zhe Yang | [NPFGLU: Unlearning Links in Graph Neural Networks](https://doi.org/10.1109/IJCNN64981.2025.11228853) | IJCNN | — | 0 |
| Miaolin Xing et al. | [Towards Effective Edge Unlearning: Enhancing Graph Unlearning via Contrastive Learning with Adversarial Example](https://doi.org/10.1109/IJCNN64981.2025.11227397) | IJCNN | — | 0 |
| Changchun Yin, Liming Fang, Lu Zhou | [An Effective Approach to Class-Wise Unlearning in Pre-trained Encoders for Contrastive Learning](https://doi.org/10.1109/IJCNN64981.2025.11228327) | IJCNN | — | 0 |
| Boxu Xiao, Sijia Liu, Qing Ling | [Federated Unlearning with Oriented Saliency Compression](https://doi.org/10.1109/IJCNN64981.2025.11228643) | IJCNN | [GitHub](https://github.com/RadiumStar/FedUOSC) | 0 |
| Kun‐Woo Kim et al. | [GRAIL: Gradient-Based Adaptive Unlearning for Privacy and Copyright in LLMs](https://doi.org/10.1109/ijcnn64981.2025.11229073) | IJCNN | [GitHub](https://github.com/piso7/piso7) | 0 |
| Miaolin Xing et al. | [Towards Effective Edge Unlearning: Enhancing Graph Unlearning via Contrastive Learning with Adversarial Example](https://doi.org/10.1109/ijcnn64981.2025.11227397) | IJCNN | — | 0 |
| Zhen Hu, Zhe Yang | [NPFGLU: Unlearning Links in Graph Neural Networks](https://doi.org/10.1109/ijcnn64981.2025.11228853) | IJCNN | — | 0 |
| Zhe Liu | [Unlearning LLM-Based Speech Recognition Models](https://doi.org/10.21437/interspeech.2025-287) | INTERSPEECH | — | 0 |
| Daniela Pisanu, Jonas Walter, Jörg Franke | [Balancing Utility and Privacy: Machine Unlearning for Medical Robotics](https://doi.org/10.1109/ISMT68188.2025.11488082) | ISMT | — | 0 |
| So Yeon Kim et al. | [Selective LLM Unlearning via SAE-Based Token Importance Score](https://doi.org/10.1109/isncc66965.2025.11250473) | ISNCC | — | 0 |
| Yanbing Zhou et al. | [Layer-Wise Unlearning for Model Adaption in Non-Stationary Environments](https://doi.org/10.1109/ICDM65498.2025.00186) | Industrial Conference on Data Mining | [GitHub](https://github.com/mlmmwym/LwU) | 0 |
| Haichao Zhang et al. | [Customized Retrieval-Augmented Generation with LLM for Debiasing Recommendation Unlearning](https://doi.org/10.1109/ICDM65498.2025.00183) | Industrial Conference on Data Mining | [GitHub](https://github.com/zhanghaichao520/LLM_rec_unlearning) | 0 |
| Ning Pang et al. | [Perturb and restore: Efficient category revocation in federated unlearning](https://doi.org/10.1016/j.inffus.2025.103994) | Information Fusion | — | 0 |
| Muhammad Usmani et al. | [Federated unlearning using diffusive noise injection](https://doi.org/10.1016/j.inffus.2025.103796) | Information Fusion | — | 0 |
| Maximilian Egger, Rawad Bitar, Rüdiger L. Urbanke | [Efficient Machine Unlearning by Model Splitting and Core Sample Selection](https://doi.org/10.1109/ITW62417.2025.11240389) | Information Theory Workshop | — | 0 |
| Imran Ahsan, Hyunwook Yu, Mucheol Kim | [GNN Unlearning Reality Checklist (GURC): A Standard for Robust, Reproducible, and Privacy-Safe Evaluation](https://doi.org/10.1109/ictc66702.2025.11387905) | Information and Communication Technology Convergence | — | 0 |
| Thang Hiep Duc Tran, Thai Hoang Le | [WSS-CL: Weight Saliency Soft-Guided Contrastive Learning for Efficient Machine Unlearning Image Classification](https://doi.org/10.48550/arXiv.2508.04308) | International Conference on Computational Collective Intelligence | — | 0 |
| Anil Babu Bathula, Subba Rao Peram | [GAD-SISA: A Scalable Defense Against Label Flipping Attack](https://doi.org/10.1109/CICN67655.2025.11368228) | International Conference on Computational Intelligence and Communication Networks | — | 0 |
| Yongpei Zhang et al. | [Rethinking Privacy Protection for Recommender System in a Collaborative Way](https://doi.org/10.1109/CSCWD64889.2025.11033239) | International Conference on Computer Supported Cooperative Work in Design | — | 0 |
| A. Chahal et al. | [Efficient Machine Unlearning using Mislabel Unlearning](https://doi.org/10.1109/IC366947.2025.11290239) | International Conference on Contemporary Computing | [GitHub](https://github.com/yatin-shrma/mislabel-unlearning) | 0 |
| Xuanming Hu et al. | [Privacy-Aware Machine Unlearning for Stable Association Rules in Retail Recommendations](https://doi.org/10.1109/iceei68459.2025.11330842) | International Conference on Electrical Engineering and Informatics | — | 0 |
| Hongyu Lin et al. | [CEFU-QoS: A Cloud-Edge Federated Unlearning Framework for Rapid QoS Prediction via Collaborative Mechanisms](https://doi.org/10.1145/3787330.3787356) | International Conference on Industrial Technology | — | 0 |
| Hussien AbdelRaouf, Mohamed I. Ibrahem | [Federated Unlearning: Techniques, Trends, and Future Directions](https://doi.org/10.1109/ICMI65310.2025.11141148) | International Conference on Multimodal Interaction | — | 0 |
| Dhairya Sindhwani | [Beyond Permanent Memory: Digital Forgetting in the Age of Intelligent Systems, Reconciling Human Cognition, Machine Unlearning, and the Right to Be Forgotten](https://doi.org/10.36948/ijfmr.2025.v07i05.58292) | International Journal For Multidisciplinary Research | — | 0 |
| Deepika Rajwade et al. | [Machine Unlearning: A Comprehensive Framework for Efficient Data Removal in Deep Learning Systems](https://doi.org/10.38124/ijisrt/25oct892) | International Journal of Innovative Science and Research Technology | — | 0 |
| Smieee G. Pradeep Reddy et al. | [Machine Unlearning: The Right to Be Forgotten for Privacy-Preserving Artificial Intelligence](https://doi.org/10.1109/ISAECT68904.2025.11318751) | International Symposium Advanced Electrical and Communication Technologies | — | 0 |
| So Yeon Kim et al. | [Selective LLM Unlearning via SAE-Based Token Importance Score](https://doi.org/10.1109/ISNCC66965.2025.11250473) | International Symposium on Networks, Computers and Communications | — | 0 |
| Bingguang Lu et al. | [BadFU: Backdoor Federated Learning through Adversarial Machine Unlearning](https://doi.org/10.1109/RAID67961.2025.00020) | International Symposium on Recent Advances in Intrusion Detection | [GitHub](https://github.com/BingguangLu/BadFU) | 0 |
| Jie Zhang et al. | [EMMU: Efficient Information-Level Multimodal Machine Unlearning with High Model Fidelity](https://doi.org/10.1109/IWQoS65803.2025.11143267) | International Workshop on Quality of Service | — | 0 |
| Pengfei Wang et al. | [Eliminating Poor-Quality Data Impacts from Multiple Participants with Federated Unlearning](https://doi.org/10.1109/IWQoS65803.2025.11143467) | International Workshop on Quality of Service | — | 0 |
| Risto Halonen et al. | [Anxiety moderates the effect of sleep on selective forgetting](https://doi.org/10.1016/j.jad.2025.119562) | Journal of Affective Disorders | — | 0 |
| Weiping Peng et al. | [Machine Unlearning Scheme for Recommendation System Based on Gradient Attribution](https://doi.org/10.54097/gqxpaf75) | Journal of Computer Science and Artificial Intelligence | — | 0 |
| Rongxin Zhu | [Unlearning in Tabular-to-Hypergraph Learning via Selective Distillation](https://doi.org/10.63313/jcsft.9035) | Journal of Computer Science and Frontier Technologies | — | 0 |
| Qipeng Song et al. | [DelRightGuard: A Secure yet Lightweight Data Deletion Notification Distribution Protocol for Safeguarding Right to Deletion](https://doi.org/10.1016/j.jiixd.2024.11.001) | Journal of Information and Intelligence | — | 0 |
| Min Chen et al. | [From Expansion to Retraction: Long-tailed Machine Unlearning via Boundary Manipulation](https://doi.org/10.1145/3711896.3736970) | KDD | — | 0 |
| T. S, D. K S | [Ghost Data: Representational Inertia and the Quest for Verifiable Forgetting in Modern Artificial Intelligence](https://doi.org/10.59176/kjcs.v5i1.2550) | KJCS | — | 0 |
| Faqian Guan et al. | [Graph Unlearning: Efficient Node Removal in Graph Neural Networks](https://doi.org/10.48550/arXiv.2509.04785) | Knowledge-Based Systems | — | 0 |
| Paolo De los Santos et al. | [Misinformation Representation and Feature Shifts from Machine Unlearning in Large Language Models (LLMs)](https://doi.org/10.5109/7395735) | Kyushu University Institutional Repository (QIR) (Kyushu University) | — | 0 |
| Paolo De los Santos et al. | [Misinformation Representation and Feature Shifts from Machine Unlearning in Large Language Models (LLMs)](https://openalex.org/W7116642274) | Kyushu University Institutional Repository (QIR) (Kyushu University) | — | 0 |
| Yuhang Wang et al. | [Robust MLLM Unlearning via Visual Knowledge Distillation](https://arxiv.org/abs/2512.11325) | Lecture Notes in Computer Science | — | 0 |
| L. Chai, Jay Gupta | [Exploring Machine Unlearning in Large Language Models](https://www.semanticscholar.org/paper/9cd443a6fd4b80b1d70002687dfc3d8fd0660b56) | Lecture Notes on Data Engineering and Communications Technologies | — | 0 |
| Hai Anh Tran, Abdelhamid Mellouk | [Domain-Aware Federated Unlearning With Adaptive Multi-Resolution Models for Resource-Constrained IoT Networks](https://doi.org/10.1109/mecom67453.2025.11439237) | MECOM | — | 0 |
| Andrea D’Angelo, Francesco Gullo, Giovanni Stilo | [The forget-set identification problem](https://doi.org/10.1007/s10994-025-06897-9) | Machine Learning | — | 0 |
| Devulapally, Naresh Kumar et al. | [Latent Diffusion Unlearning: Protecting Against Unauthorized Personalization Through Trajectory Shifted Perturbations](https://doi.org/10.13016/m2gvnj-76zd) | Maryland Shared Open Access Repository (USMAI Consortium) | — | 0 |
| Zhongbin Huang et al. | [ConceptVoid: Precision Multi-Concept Erasure in Generative Video Diffusion](https://doi.org/10.3390/math13162652) | Mathematics | — | 0 |
| Neil Sharma | [Computationally Efficient Federated Unlearning](https://doi.org/10.1145/3721464.3777434) | Middleware Demos/Posters/Doctoral Symposium | — | 0 |
| Bichen Wang et al. | [Balancing Forget Quality and Model Utility: A Reverse KL-Divergence Knowledge Distillation Approach for Better Unlearning in LLMs](https://doi.org/10.18653/v1/2025.naacl-long.60) | NAACL | — | 0 |
| Dan Parii, Thomas van Osch, Chang Sun | [Machine Unlearning of Personally Identifiable Information in Large Language Models](https://doi.org/10.18653/v1/2025.nllp-1.6) | Natural Legal Language Processing Workshop | — | 0 |
| Linlin Wang et al. | [Invisible watermarking framework for unlearned diffusion model in online service](https://doi.org/10.1016/j.neunet.2025.108477) | Neural Networks | — | 0 |
| Liang Xie et al. | [A Truthful Incentive Scheme Based on Data Forgetting Game for Federated Unlearning](https://doi.org/10.1109/pcds65695.2025.00030) | PCDS | — | 0 |
| Chengzhi Shangguan et al. | [Boundary-Anchored Functional Duplication Attacks on Machine Unlearning](https://doi.org/10.1109/PCDS65695.2025.00035) | PCDS | — | 0 |
| Sagar S. Bhumkar, Nilesh Joshi, Manisha Bharati | [A Federated Unlearning Approach for Aerospace MRO Using Digital Twins](https://doi.org/10.1109/punecon67554.2025.11378514) | PuneCon | — | 0 |
| Qi-Ang Hu et al. | [ETCE: Efficient Two-Stage Concept Erasure for Text-to-Image Diffusion Models](https://doi.org/10.1145/3757374.3771453) | SIGGRAPH | — | 0 |
| Yiling Tao et al. | [Unlearning for Federated Online Learning to Rank: A Reproducibility Study](https://doi.org/10.1145/3726302.3730336) | SIGIR | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Liu Li et al. | [Fairness-aware Graph Unlearning with Knowledge Distillation](https://doi.org/10.1109/SWC65939.2025.00109) | SWC | — | 0 |
| Teng Wang et al. | [Differentially private federated unlearning mechanism based on update residuals](https://doi.org/10.1360/ssi-2025-0243) | Scientia Sinica Informationis | — | 0 |
| Yijing Lin et al. | [Efficient and trusted federated unlearning for multi-user semantic knowledge base](https://doi.org/10.1360/ssi-2024-0304) | Scientia Sinica Informationis | — | 0 |
| Yajie Wang et al. | [Federated Meta Unlearning Based on Model Decomposition and Weighted Aggregation](https://doi.org/10.1360/ssi-2025-0221) | Scientia Sinica Informationis | — | 0 |
| Angel Navia-Vázquez | [Unlearning in distributed budget support vector machine](https://doi.org/10.1007/s00500-025-10929-w) | Soft Computing - A Fusion of Foundations, Methodologies and Applications | — | 0 |
| A. Singh et al. | [Concept Siever : Towards Controllable Erasure of Concepts from Diffusion Models without Side-effect](https://www.semanticscholar.org/paper/84b9b21921728f4a00751d93b869fd013f6a0d6a) | TMLR | — | 0 |
| Subhodip Panda et al. | [Concept Forgetting via Label Annealing](https://www.semanticscholar.org/paper/098eee0ab8d7df913ef66a0f8d7f2ef4f875241c) | UAI | [GitHub](https://github.com/Subhodip123/LAN) | 0 |
| Yuanshun Yao et al. | [Rethinking machine unlearning for large language models](https://doi.org/10.17615/p1gj-a595) | UNC Libraries | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 0 |
| Amartya Hatua, Trung T. Nguyen | [Machine Unlearning Across Scales: Evaluation of Optimization Methods on Language Models](https://doi.org/10.1109/UEMCON67449.2025.11267758) | Ubiquitous Computing, Electronics & Mobile Communication Conference | [GitHub](https://github.com/amartyahatua/LLM_Unlearning) | 0 |
| Thanh Tu Nguyen | [Towards Verifiable Federated Unlearning](https://openalex.org/W7117095252) | VUBIR (Vrije Universiteit Brussel) | — | 0 |
| Imran Ahsan et al. | [Forget and Explain: Transparent Verification of GNN Unlearning](https://doi.org/10.48550/arXiv.2512.07450) | WSDM | [GitHub](https://github.com/ImranAhsan23/F-E) | 0 |
| Kakul Srivastava, Himani Bansal | [Operative Study of Federated Unlearning among Various Datasets](https://doi.org/10.1109/worldsuas66815.2025.11198923) | WorldSUAS | — | 0 |
| Kakul Srivastava, Himani Bansal | [Operative Study of Federated Unlearning among Various Datasets](https://doi.org/10.1109/worldsuas66815.2025.11199121) | WorldSUAS | — | 0 |
| Jian Weng et al. | [M-ErasureBench: A Comprehensive Multimodal Evaluation Benchmark for Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2512.22877) | arXiv | — | 0 |
| Kien Nguyen, Anh Tran, Cuong Pham | [SuMa: A Subspace Mapping Approach for Robust and Effective Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1109/iccv51701.2025.01821) | arXiv | — | 0 |
| Ruidong Chen et al. | [TRCE: Towards Reliable Malicious Concept Erasure in Text-to-Image Diffusion Models](https://doi.org/10.1109/iccv51701.2025.01759) | arXiv | [GitHub](https://github.com/ddgoodgood/TRCE) | 0 |
| Jiahui Geng, Qing Li | [SAUCE: Selective Concept Unlearning in Vision-Language Models with Sparse Autoencoders](https://doi.org/10.1109/iccv51701.2025.00290) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Mushtaq, Erum et al. | [From Narrow Unlearning to Emergent Misalignment: Causes, Consequences, and Containment in LLMs](https://openalex.org/W7106206980) | arXiv | — | 0 |
| Zhao, Junpeng et al. | [Certified Signed Graph Unlearning](https://openalex.org/W7106207050) | arXiv | — | 0 |
| Xiaoqi Han et al. | [Consistency-Aware Editing for Entity-level Unlearning in Language Models](https://doi.org/10.48550/arXiv.2601.08840) | arXiv | [GitHub](https://github.com/tatsu-lab/alpaca) | 0 |
| Claudio Savelli et al. | [FAME: Fictional Actors for Multilingual Erasure](https://doi.org/10.48550/arXiv.2512.15235) | arXiv | [HF](https://huggingface.co/ClaudioSavelli/FAME_base_llama32-1b-instruct-qa) | 0 |
| Ashish Mishra et al. | [Erasing CLIP Memories: Non-Destructive, Data-Free Zero-Shot class Unlearning in CLIP Models](https://doi.org/10.48550/arXiv.2512.14137) | arXiv | — | 0 |
| Ashish Mishra et al. | [Selective, Controlled and Domain-Agnostic Unlearning in Pretrained CLIP: A Training- and Data-Free Approach](https://doi.org/10.48550/arXiv.2512.14113) | arXiv | — | 0 |
| M. Zakharov | [Face Identity Unlearning for Retrieval via Embedding Dispersion](https://doi.org/10.48550/arXiv.2512.13317) | arXiv | — | 0 |
| D. T. Nguyen et al. | [SUGAR: A Sweeter Spot for Generative Unlearning of Many Identities](https://doi.org/10.48550/arXiv.2512.06562) | arXiv | [GitHub](https://github.com/judydnguyen/SUGAR-Generative-Unlearn) | 0 |
| Guoshenghui Zhao, Huawei Lin, Weijie Zhao | [RapidUn: Influence-Driven Parameter Reweighting for Efficient Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2512.04457) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Yuanbang Liang, Yang Li | [Grokked Models are Better Unlearners](https://doi.org/10.48550/arXiv.2512.03437) | arXiv | — | 0 |
| MohammadParsa Dini, Human Jafari | [Adaptive-lambda Subtracted Importance Sampled Scores in Machine Unlearning for DDPMs and VAEs](https://arxiv.org/abs/2512.01054) | arXiv | — | 0 |
| Tien Dat Hoang | [Illuminating the Black Box: Real-Time Monitoring of Backdoor Unlearning in CNNs via Explainable AI](https://doi.org/10.48550/arXiv.2511.21291) | arXiv | — | 0 |
| Anjie Le et al. | [POUR: A Provably Optimal Method for Unlearning Representations via Neural Collapse](https://doi.org/10.48550/arXiv.2511.19339) | arXiv | — | 0 |
| Arpit Garg, Hemanth Saratchandran, Simon Lucey | [SineProject: Machine Unlearning for Stable Vision Language Alignment](https://doi.org/10.48550/arXiv.2511.18444) | arXiv | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 0 |
| Nirjhor Datta, Md. Golam Raibul Alam | [Erase to Retain: Low Rank Adaptation Guided Selective Unlearning in Medical Segmentation Networks](https://doi.org/10.48550/arXiv.2511.16574) | arXiv | — | 0 |
| Ahmet Umur Özsoy | [Selective Forgetting in Option Calibration: An Operator-Theoretic Gauss-Newton Framework](https://doi.org/10.48550/arXiv.2511.14980) | arXiv | — | 0 |
| Shizhou Xu et al. | [Forgetting-MarI: LLM Unlearning via Marginal Information Regularization](https://doi.org/10.48550/arXiv.2511.11914) | arXiv | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 0 |
| Lisong He, Yi Yang, Xiangyu Chang | [Beyond Uniform Deletion: A Data Value-Weighted Framework for Certified Machine Unlearning](https://doi.org/10.48550/arXiv.2511.06794) | arXiv | — | 0 |
| Junpeng Zhao et al. | [Learning to Fast Unrank in Collaborative Filtering Recommendation](https://doi.org/10.48550/arXiv.2511.06803) | arXiv | [GitHub](https://github.com/Juniper42/L2UnRank) | 0 |
| Eun-su Cho et al. | [FiCABU: A Fisher-Based, Context-Adaptive Machine Unlearning Processor for Edge AI](https://doi.org/10.48550/arXiv.2511.05605) | arXiv | [GitHub](https://github.com/chipsalliance/rocket-chip) | 0 |
| Minyi Peng et al. | [MPRU: Modular Projection-Redistribution Unlearning as Output Filter for Classification Pipelines](https://doi.org/10.48550/arXiv.2510.26230) | arXiv | [GitHub](https://github.com/dgunamardi/MPRU) | 0 |
| J. Lanyon et al. | [On the limitation of evaluating machine unlearning using only a single training seed](https://doi.org/10.48550/arXiv.2510.26714) | arXiv | [GitHub](https://github.com/jtlan90/evaluating-machine-unlearning-using-only-a-single-training-seed) | 0 |
| Jinseong Park, Mijung Park | [Data Unlearning Beyond Uniform Forgetting via Diffusion Time and Frequency Selection](https://doi.org/10.48550/arXiv.2510.17917) | arXiv | [GitHub](https://github.com/christophschuhmann/improved-aesthetic-predictor) | 0 |
| Amel Abdelraheem et al. | [Backdoor Unlearning by Linear Task Decomposition](https://doi.org/10.48550/arXiv.2510.14845) | arXiv | — | 0 |
| Ziheng Huang et al. | [Federated Unlearning in the Wild: Rethinking Fairness and Data Discrepancy](https://doi.org/10.48550/arXiv.2510.07022) | arXiv | — | 0 |
| Karuna Bhaila et al. | [Cross-Modal Attention Guided Unlearning in Vision-Language Models](https://doi.org/10.48550/arXiv.2510.07567) | arXiv | — | 0 |
| Zhao Ren et al. | [Machine Unlearning in Speech Emotion Recognition via Forget Set Alone](https://doi.org/10.48550/arXiv.2510.04251) | arXiv | — | 0 |
| Xiang Zhang et al. | [Rotation Control Unlearning: Quantifying and Controlling Continuous Unlearning for LLM with The Cognitive Rotation Space](https://doi.org/10.48550/arXiv.2509.25743) | arXiv | — | 0 |
| Jinghan Xu et al. | [Preserving Cross-Modal Stability for Visual Unlearning in Multimodal Scenarios](https://doi.org/10.48550/arXiv.2509.23895) | arXiv | — | 0 |
| Sadia Asif, Mohammad Mohammadi Amiri | [OFMU: Optimization-Driven Framework for Machine Unlearning](https://doi.org/10.48550/arXiv.2509.22483) | arXiv | [HF](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf) | 0 |
| Nicola Novello et al. | [A Unified Framework for Diffusion Model Unlearning with f-Divergence](https://doi.org/10.48550/arXiv.2509.21167) | arXiv | — | 0 |
| Ali Faraji, M. Papagelis | [TraceHiding: Scalable Machine Unlearning for Mobility Data](https://doi.org/10.48550/arXiv.2509.17241) | arXiv | [GitHub](https://github.com/alifa98/TraceHiding) | 0 |
| Bihao Zhan et al. | [Forget What's Sensitive, Remember What Matters: Token-Level Differential Privacy in Memory Sculpting for Continual Learning](https://doi.org/10.48550/arXiv.2509.12958) | arXiv | [HF](https://huggingface.co/datasets/mavinsao/reddit-mental-illnes) | 0 |
| A. K. Patra, Lingaraj Sahoo | [MRD-LiNet: A Novel Lightweight Hybrid CNN with Gradient-Guided Unlearning for Improved Drought Stress Identification](https://doi.org/10.48550/arXiv.2509.06367) | arXiv | [GitHub](https://github.com/tzutalin/labelImg) | 0 |
| Nan Wang et al. | [zkUnlearner: A Zero-Knowledge Framework for Verifiable Unlearning with Multi-Granularity and Forgery-Resistance](https://doi.org/10.48550/arXiv.2509.07290) | arXiv | — | 0 |
| Rishabh Dixit, Yuan Hui, Rayan Saab | [The Measure of Deception: An Analysis of Data Forging in Machine Unlearning](https://doi.org/10.48550/arXiv.2509.05865) | arXiv | — | 0 |
| Zhihao Liu et al. | [Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Guidance with Proxy Constraint](https://arxiv.org/abs/2508.20443) | arXiv | [GitHub](https://github.com/KJaebye/EmbodiedAI-Robotics-arXiv-Daily-Reporter) | 0 |
| Wenjie Bao et al. | [Module-Aware Parameter-Efficient Machine Unlearning on Transformers](https://doi.org/10.48550/arXiv.2508.17233) | arXiv | — | 0 |
| Aristeidis Sidiropoulos et al. | [Evaluating the Defense Potential of Machine Unlearning against Membership Inference Attacks](https://doi.org/10.48550/arXiv.2508.16150) | arXiv | — | 0 |
| Liu Yang et al. | [Curriculum Approximate Unlearning for Session-based Recommendation](https://doi.org/10.48550/arXiv.2508.15263) | arXiv | — | 0 |
| X. Abdullah | [Unlearning at Scale: Implementing the Right to be Forgotten in Large Language Models](https://doi.org/10.48550/arXiv.2508.12220) | arXiv | [GitHub](https://github.com/zepharaai/artifact) | 0 |
| Yuhao Sun et al. | [Invisible Watermarks, Visible Gains: Steering Machine Unlearning with Bi-Level Watermarking Design](https://doi.org/10.48550/arXiv.2508.10065) | arXiv | — | 0 |
| Hang Yin et al. | [Graph Unlearning via Embedding Reconstruction - A Range-Null Space Decomposition Approach](https://doi.org/10.48550/arXiv.2508.02044) | arXiv | — | 0 |
| Kehao Miao et al. | [Towards Evaluation for Real-World LLM Unlearning](https://doi.org/10.48550/arXiv.2508.01324) | arXiv | — | 0 |
| Jiawei Liu et al. | [Efficient Machine Unlearning via Influence Approximation](https://doi.org/10.48550/arXiv.2507.23257) | arXiv | [GitHub](https://github.com/Lolo1222/IAU) | 0 |
| Xin Wang, R. T. Rockafellar, X. Ban | [Machine Unlearning of Traffic State Estimation and Prediction](https://doi.org/10.48550/arXiv.2507.17984) | arXiv | — | 0 |
| Patryk Jasiorski, Marek Klonowski, Michal Wo'zniak | [How to Protect Models against Adversarial Unlearning?](https://doi.org/10.48550/arXiv.2507.10886) | arXiv | — | 0 |
| J. Khan | [Leveraging Distribution Matching to Make Approximate Machine Unlearning Faster](https://doi.org/10.48550/arXiv.2507.09786) | arXiv | [GitHub](https://github.com/algebraicdianuj/DC_Unlearning) | 0 |
| Qing Gong, Xue Yang, Xiaohu Tang | [Orthogonal Soft Pruning for Efficient Class Unlearning](https://doi.org/10.48550/arXiv.2506.19891) | arXiv | — | 0 |
| Ruihan Wu, Konstantin Garov, Kamalika Chaudhuri | [Learning-Time Encoding Shapes Unlearning in LLMs](https://doi.org/10.48550/arXiv.2506.15076) | arXiv | [GitHub](https://github.com/wrh14/learning_time_shapes_unlearning) | 0 |
| Xiangman Li et al. | [PDLRecover: Privacy-preserving Decentralized Model Recovery with Machine Unlearning](https://doi.org/10.48550/arXiv.2506.15112) | arXiv | — | 0 |
| Ya-Nan Yuan et al. | [Unlearning-Enhanced Website Fingerprinting Attack: Against Backdoor Poisoning in Anonymous Networks](https://doi.org/10.48550/arXiv.2506.13563) | arXiv | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 0 |
| Aleksey Kudelya, Alexander Shirnin | [Lacuna Inc. at SemEval-2025 Task 4: LoRA-Enhanced Influence-Based Unlearning for LLMs](https://doi.org/10.48550/arXiv.2506.04044) | arXiv | — | 0 |
| Minsu Kim, Nakyeong Yang, Kyomin Jung | [Rethinking Post-Unlearning Behavior of Large Vision-Language Models](https://doi.org/10.48550/arXiv.2506.02541) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| SeungBum Ha, Saerom Park, Sung Whan Yoon | [Unlearning's Blind Spots: Over-Unlearning and Prototypical Relearning Attack](https://doi.org/10.48550/arXiv.2506.01318) | arXiv | [GitHub](https://github.com/Seung-B/Spotter-Unlearning) | 0 |
| Öykü Deniz Köse, Gonzalo Mateos, Yanning Shen | [Unlearning Algorithmic Biases over Graphs](https://doi.org/10.48550/arXiv.2505.14945) | arXiv | — | 0 |
| Brennon Brimhall et al. | [Mirror Mirror on the Wall, Have I Forgotten it All? A New Framework for Evaluating Machine Unlearning](https://doi.org/10.48550/arXiv.2505.08138) | arXiv | — | 0 |
| Xinyang Lu et al. | [WaterDrum: Watermarking for Data-centric Unlearning Metric](https://doi.org/10.48550/arXiv.2505.05064) | arXiv | [GitHub](https://github.com/lululu008/WaterDrum) | 0 |
| Saber Malekmohammadi, H. Lee, Li Xiong | [Sharpness-Aware Parameter Selection for Machine Unlearning](https://doi.org/10.48550/arXiv.2504.06398) | arXiv | — | 0 |
| Mahabub Uz Zaman, Xiang Sun, Jingjing Yao | [Sky of Unlearning (SoUL): Rewiring Federated Machine Unlearning via Selective Pruning](https://doi.org/10.48550/arXiv.2504.01705) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Chenguang Xiao et al. | [Benchmarking Federated Machine Unlearning methods for Tabular Data](https://doi.org/10.48550/arXiv.2504.00921) | arXiv | — | 0 |
| Piyush Nagasubramaniam et al. | [Prompting Forgetting: Unlearning in GANs via Textual Guidance](https://doi.org/10.48550/arXiv.2504.01218) | arXiv | — | 0 |
| Tetsuya Hoya, Shunpei Morita | [Automatic Construction of Pattern Classifiers Capable of Continuous Incremental Learning and Unlearning Tasks Based on Compact-Sized Probabilistic Neural Network](https://doi.org/10.48550/arXiv.2501.00725) | arXiv | — | 0 |
| Hithem Lamri, Michail Maniatakos | [Fully Decentralized Certified Unlearning](https://doi.org/10.48550/arXiv.2512.08443) | arXiv | — | 0 |
| Mostafa Mozafari et al. | [Subtract the Corruption: Training-Data-Free Corrective Machine Unlearning using Task Arithmetic](https://doi.org/10.48550/arXiv.2511.18660) | arXiv | [GitHub](https://github.com/mosix11/CUTS) | 0 |
| Siqiao Mu, Diego Klabjan | [Descend or Rewind? Stochastic Gradient Descent Unlearning](https://doi.org/10.48550/arXiv.2511.15983) | arXiv | [GitHub](https://github.com/anonymous-1234567/r2d2) | 0 |
| Yinyi Luo et al. | [KnowledgeSmith: Uncovering Knowledge Updating in LLMs with Model Editing and Unlearning](https://doi.org/10.48550/arXiv.2510.02392) | arXiv | [GitHub](https://github.com/AIFrontierLab/KnowledgeSmith) | 0 |
| Wenhao Yang et al. | [Factor Decorrelation Enhanced Data Removal from Deep Predictive Models](https://doi.org/10.48550/arXiv.2509.23443) | arXiv | [GitHub](https://github.com/WUT-IDEA/DecoRemoval) | 0 |
| Anna Mazhar, Sainyam Galhotra | [Causal Fuzzing for Verifying Machine Unlearning](https://doi.org/10.48550/arXiv.2509.16525) | arXiv | — | 0 |
| Ashwath Vaithinathan Aravindan et al. | [Sealing The Backdoor: Unlearning Adversarial Text Triggers In Diffusion Models Using Knowledge Distillation](https://doi.org/10.48550/arXiv.2508.18235) | arXiv | [GitHub](https://github.com/Mystic-Slice/Sealing-The-Backdoor) | 0 |
| Ken Stewart | [Mo' Memory, Mo' Problems: Stream-Native Machine Unlearning](https://doi.org/10.48550/arXiv.2508.10193) | arXiv | — | 0 |
| Xinbao Qiao et al. | [Soft Weighted Machine Unlearning](https://doi.org/10.48550/arXiv.2505.18783) | arXiv | — | 0 |
| Yingdan Shi, Ren Wang | [MCU: Improving Machine Unlearning through Mode Connectivity](https://doi.org/10.48550/arXiv.2505.10859) | arXiv | [GitHub](https://github.com/TIML-Group/Mode-Connectivity-Unlearning) | 0 |
| Fengli Wu et al. | [MedForget: Hierarchy-Aware Multimodal Unlearning Testbed for Medical AI](https://doi.org/10.48550/arXiv.2512.09867) | arXiv | — | 0 |
| Aadya Goel, Mayuri Sridhar | [Delete and Retain: Efficient Unlearning for Document Classification](https://doi.org/10.48550/arXiv.2512.13711) | arXiv | — | 0 |
| Hang Chen et al. | [CLUE: Conflict-guided Localization for LLM Unlearning Framework](https://doi.org/10.48550/arXiv.2509.20977) | arXiv | [GitHub](https://github.com/Zodiark-ch/CLUE) | 0 |
| Pinak Mandal, G. Gottwald | [UNO: Unlearning via Orthogonalization in Generative models](https://doi.org/10.48550/arXiv.2506.04712) | arXiv | [GitHub](https://github.com/pinakm9/forget) | 0 |
| Cheng Shu et al. | [Classifying Long-tailed and Label-noise Data via Disentangling and Unlearning](https://doi.org/10.48550/arXiv.2503.11414) | arXiv | — | 0 |
| Yasser H. Khalil, Mehdi Setayesh, Hongliang Li | [CoUn: Empowering Machine Unlearning via Contrastive Learning](https://doi.org/10.48550/arXiv.2509.16391) | arXiv | [GitHub](https://github.com/sheltparkle/CoUn_Code) | 0 |
| Christoforos N. Spartalis et al. | [Unleashing Uncertainty: Efficient Machine Unlearning for Generative AI](https://doi.org/10.48550/arXiv.2508.20773) | arXiv | — | 0 |
| Roy Rinberg et al. | [RippleBench: Capturing Ripple Effects Using Existing Knowledge Repositories](https://doi.org/10.48550/arXiv.2512.04144) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 0 |
| Aakash Sen Sharma et al. | [The Realignment Problem: When Right becomes Wrong in LLMs](https://doi.org/10.48550/arXiv.2511.02623) | arXiv | [GitHub](https://github.com/respailab/TRACE) | 0 |
| Aakriti Shah, Thai Le | [The Limits of Obliviate: Evaluating Unlearning in LLMs via Stimulus-Knowledge Entanglement-Behavior Framework](https://doi.org/10.48550/arXiv.2510.25732) | arXiv | — | 0 |
| Anu Agarwal, Mihir Pamnani, Dilek Hakkani-Tur | [SIMU: Selective Influence Machine Unlearning](https://doi.org/10.48550/arXiv.2510.07822) | arXiv | — | 0 |
| Yicheng Lang et al. | [Downgrade to Upgrade: Optimizer Simplification Enhances Robustness in LLM Unlearning](https://doi.org/10.48550/arXiv.2510.00761) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn_Optimizer) | 0 |
| Yujian Sun, Tian Li | [iShumei-Chinchunmei at SemEval-2025 Task 4: A balanced forgetting and retention multi-task framework using effective unlearning loss](https://doi.org/10.48550/arXiv.2507.16263) | arXiv | — | 0 |
| Arjun Dosajh, Mihika Sanghi | [Mr. Snuffleupagus at SemEval-2025 Task 4: Unlearning Factual Knowledge from LLMs Using Adaptive RMU](https://doi.org/10.48550/arXiv.2506.16548) | arXiv | — | 0 |
| Xiaotian Ye, Mengqi Zhang, Shu Wu | [LLM Unlearning Should Be Form-Independent](https://doi.org/10.48550/arXiv.2506.07795) | arXiv | [GitHub](https://github.com/Acruxos/ORT) | 0 |
| Zhihao Liu et al. | [Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Aware Unlearning with Proxy Constraint](https://doi.org/10.48550/arXiv.2508.20443) | arXiv | — | 0 |
| Rishub Tamirisa et al. | [T OWARD R OBUST U NLEARNING FOR LLM S](https://arxiv.org/abs/2510.19422) | arXiv | — | 0 |
| Yiwen Liang et al. | [When Forgetting Builds Reliability: LLM Unlearning for Reliable Hardware Code Generation](https://doi.org/10.48550/arXiv.2512.05341) | arXiv | — | 0 |
| Liran Cohen, Yaniv Nemcovesky, Avi Mendelson | [REMIND: Input Loss Landscapes Reveal Residual Memorization in Post-Unlearning LLMs](https://doi.org/10.48550/arXiv.2511.04228) | arXiv | — | 0 |
| Myeongseob Ko et al. | [Probing Knowledge Holes in Unlearned LLMs](https://doi.org/10.48550/arXiv.2511.00030) | arXiv | — | 0 |
| Yuefeng Peng et al. | [Forget to Know, Remember to Use: Context-Aware Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2510.17620) | arXiv | — | 0 |
| Praveen Bushipaka, Lucia C. Passaro, Tommaso Cucinotta | [Standard vs. Modular Sampling: Best Practices for Reliable LLM Unlearning](https://doi.org/10.48550/arXiv.2509.05316) | arXiv | [GitHub](https://github.com/praveensonu/MELU) | 0 |
| Saransh Agrawal, Kuan-Hao Huang | [SHA256 at SemEval-2025 Task 4: Selective Amnesia - Constrained Unlearning for Large Language Models via Knowledge Isolation](https://doi.org/10.48550/arXiv.2504.12996) | arXiv | [GitHub](https://github.com/LAB-FLAIR/Constrained-Unlearning-for-LLM) | 0 |
| Weiwei Wang | [Real Time Detection and Quantitative Analysis of Spurious Forgetting in Continual Learning](https://doi.org/10.48550/arXiv.2512.20634) | arXiv | [GitHub](https://github.com/charles-wang888/spurious-forgetting-analysis) | 0 |
| Dinesh P. Srivasthav, B. Garlapati | [Cyber for AI at SemEval-2025 Task 4: Forgotten but Not Lost: The Balancing Act of Selective Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2503.04795) | arXiv | [HF](https://huggingface.co/datasets/allenai/dolma) | 0 |
| Changjun Zhou et al. | [Dual-Phase Federated Deep Unlearning via Weight-Aware Rollback and Reconstruction](https://doi.org/10.48550/arXiv.2512.13381) | arXiv | [GitHub](https://github.com/00taotao/DPUL) | 0 |
| Lorenzo Simone, Davide Bacciu, Shuangge Ma | [ContinualFlow: Learning and Unlearning with Neural Flow Matching](https://doi.org/10.48550/arXiv.2506.18747) | arXiv | — | 0 |
| Hao Chen, Yiwei Wang, Songze Li | [Bi-Erasing: A Bidirectional Framework for Concept Removal in Diffusion Models](https://doi.org/10.48550/arXiv.2512.13039) | arXiv | [GitHub](https://github.com/chenahong/Bi-Erasing) | 0 |
| Dawid Malarz et al. | [From Unlearning to UNBRANDING: A Benchmark for Trademark-Safe Text-to-Image Generation](https://doi.org/10.48550/arXiv.2512.13953) | arXiv | [GitHub](https://github.com/gmum/UNBRANDING) | 0 |
| Naveen George et al. | [Distill, Forget, Repeat: A Framework for Continual Unlearning in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2512.02657) | arXiv | [GitHub](https://github.com/CSQianDong/Awesome-arXiv-Daily-Reporter) | 0 |
| Jiwoo Shin et al. | [Prompt-Based Safety Guidance Is Ineffective for Unlearned Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2511.04834) | arXiv | [GitHub](https://github.com/naver-ai/DUO) | 0 |
| Qinghong Yin, Yu Tian, Yue Zhang | [Rethinking Robust Adversarial Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2510.27285) | arXiv | [GitHub](https://github.com/Qhong-522/S-GRACE) | 0 |
| Youngsik Hwang, Dong-Young Lim | [Controllable Machine Unlearning via Gradient Pivoting](https://doi.org/10.48550/arXiv.2510.19226) | arXiv | — | 0 |
| Hongxu Chen et al. | [Zero-Residual Concept Erasure via Progressive Alignment in Text-to-Image Model](https://doi.org/10.48550/arXiv.2508.04472) | arXiv | — | 0 |
| Hyun Jun Yook et al. | [ZIUM: Zero-Shot Intent-Aware Adversarial Attack on Unlearned Models](https://doi.org/10.48550/arXiv.2507.21985) | arXiv | — | 0 |
| Zixuan Fu et al. | [FADE: Adversarial Concept Erasure in Flow Models](https://doi.org/10.48550/arXiv.2507.12283) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 0 |
| Shreyas Udaya, A. Lakshmi | [Few-Shot Concept Unlearning with Low Rank Adaptation](https://doi.org/10.48550/arXiv.2505.12395) | arXiv | — | 0 |
| Siyi Chen et al. | [The Dual Power of Interpretable Token Embeddings: Jailbreaking Attacks and Defenses for Diffusion Model Unlearning](https://doi.org/10.48550/arXiv.2504.21307) | arXiv | [GitHub](https://github.com/YiweiXie/Awesome-Comprehensive-Concept-Suppression) | 0 |
| Bocheng Ju et al. | [DRAGD: A Federated Unlearning Data Reconstruction Attack Based on Gradient Differences](https://doi.org/10.48550/arXiv.2507.09602) | arXiv | — | 0 |
| K. Basha, Athira Nambiar | [Supervised Contrastive Machine Unlearning of Background Bias in Sonar Image Classification with Fine-Grained Explainable AI](https://doi.org/10.48550/arXiv.2512.01291) | arXiv | — | 0 |
| Yuyuan Li et al. | [Reproducibility Companion Paper: Making Users Indistinguishable: Attribute-wise Unlearning in Recommender Systems](https://doi.org/10.48550/arXiv.2503.23032) | arXiv | [GitHub](https://github.com/oktton/Attribute-wise-Unlearning) | 0 |
| Wonje Jeung, Sangyeon Yoon, Albert No | [SEPS: A Separability Measure for Robust Unlearning in LLMs](https://doi.org/10.18653/v1/2025.emnlp-main.283) | arXiv | [GitHub](https://github.com/AI-ISL/SEPS.Table) | 0 |
| Zibin Pan et al. | [Multi-Objective Large Language Model Unlearning](https://doi.org/10.1109/icassp49660.2025.10889776) | arXiv | [GitHub](https://github.com/zibinpan/MOLLM) | 0 |
| Nguyen, Viet, Patel, Vishal M. | [CGCE: Classifier-Guided Concept Erasure in Generative Models](https://openalex.org/W7105506933) | arXiv | — | 0 |
| Lu Wei, Yuta Nakashima, Noa García | [EMMA: Concept Erasure Benchmark with Comprehensive Semantic Metrics and Diverse Categories](https://openalex.org/W7117078636) | arXiv | [GitHub](https://github.com/lobsterlulu/EMMA) | 0 |
| Jian Weng et al. | [M-ErasureBench: A Comprehensive Multimodal Evaluation Benchmark for Concept Erasure in Diffusion Models](https://openalex.org/W7117851569) | arXiv | — | 0 |
| Yoav Gur-Arieh et al. | [Precise In-Parameter Concept Erasure in Large Language Models](https://doi.org/10.18653/v1/2025.emnlp-main.960) | arXiv | [GitHub](https://github.com/yoavgur/PISCES) | 0 |
| Biswas, Shristi Das, Roy, Arani, Roy, Kaushik | [Now You See It, Now You Don't - Instant Concept Erasure for Safe Text-to-Image and Video Generation](https://openalex.org/W7106782335) | arXiv | — | 0 |
| Anil Ramakrishna et al. | [LUME: LLM Unlearning with Multitask Evaluations](https://doi.org/10.18653/v1/2025.findings-emnlp.347) | arXiv | [GitHub](https://github.com/amazon-science/lume-llm-unlearning) | 0 |
| Wenyu Wang et al. | [UIPE: Enhancing LLM Unlearning by Removing Knowledge Related to Forgetting Targets](https://doi.org/10.18653/v1/2025.findings-emnlp.1374) | arXiv | — | 0 |
| Wang, Yaxuan et al. | [DRAGON: Guard LLM Unlearning in Context via Negative Detection and Reasoning](https://openalex.org/W7105639423) | arXiv | [GitHub](https://github.com/supergirl-os/DRAGON) | 0 |
| Liu, Yezi et al. | [Recover-to-Forget: Gradient Reconstruction from LoRA for Efficient LLM Unlearning](https://openalex.org/W7113915861) | arXiv | — | 0 |
| Liu, Yezi et al. | [LUNE: Efficient LLM Unlearning via LoRA Fine-Tuning with Negative Examples](https://openalex.org/W7113916245) | arXiv | [GitHub](https://github.com/ozturkoktay/awesome-unlearnable-examples) | 0 |
| Yicheng Lang et al. | [Beyond Single-Value Metrics: Evaluating and Enhancing LLM Unlearning with Cognitive Diagnosis](https://doi.org/10.18653/v1/2025.findings-acl.1102) | arXiv | — | 0 |
| Haichao Zhang et al. | [Customized Retrieval-Augmented Generation with LLM for Debiasing Recommendation Unlearning](https://doi.org/10.1109/icdm65498.2025.00183) | arXiv | [GitHub](https://github.com/zhanghaichao520/LLM_rec_unlearning) | 0 |
| Lei Cen, Guohao Li, Li Yang | [A Scenario-Driven Efficient Federated Unlearning Method for Multi-Granularity Data Removal](https://doi.org/10.1109/bigdia68682.2025.11383040) | arXiv | — | 0 |
| Bingguang Lu et al. | [BadFU: Backdoor Federated Learning through Adversarial Machine Unlearning](https://doi.org/10.1109/raid67961.2025.00020) | arXiv | — | 0 |

## 2024

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Pratyush Maini et al. | [TOFU: A Task of Fictitious Unlearning for LLMs](https://doi.org/10.48550/arXiv.2401.06121) | arXiv | [GitHub](https://github.com/locuslab/tofu) | 399 |
| Ruiqi Zhang et al. | [Negative Preference Optimization: From Catastrophic Collapse to Effective Unlearning](https://doi.org/10.48550/arXiv.2404.05868) | arXiv | [HF](https://huggingface.co/girishgupta/deep-ignorance-unfiltered_unlearned_npo) | 393 |
| Nathaniel Li et al. | [The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning](https://arxiv.org/abs/2403.03218) | ICML | [GitHub](https://github.com/centerforaisafety/wmdp) | 388 |
| Shilin Lu et al. | [MACE: Mass Concept Erasure in Diffusion Models](https://doi.org/10.1109/CVPR52733.2024.00615) | CVPR | [GitHub](https://github.com/Shilin-LU/MACE) | 269 |
| Weijia Shi et al. | [MUSE: Machine Unlearning Six-Way Evaluation for Language Models](https://doi.org/10.48550/arXiv.2407.06460) | ICLR | [GitHub](https://github.com/swj0419/muse_bench) | 198 |
| Zheyuan Liu et al. | [Towards Safer Large Language Models through Machine Unlearning](https://doi.org/10.48550/arXiv.2402.10058) | ACL | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 147 |
| Yimeng Zhang et al. | [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://doi.org/10.48550/arXiv.2405.15234) | NeurIPS | [GitHub](https://github.com/optml-group/advunlearn) | 144 |
| Aengus Lynch et al. | [Eight Methods to Evaluate Robust Unlearning in LLMs](https://doi.org/10.48550/arXiv.2402.16835) | arXiv | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 140 |
| Nathaniel Li et al. | [LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet](https://doi.org/10.48550/arXiv.2408.15221) | arXiv | [HF](https://huggingface.co/ScaleAI/mhj-llama3-8b-rmu) | 138 |
| A. Sheshadri et al. | [Latent Adversarial Training Improves Robustness to Persistent Harmful Behaviors in LLMs](https://arxiv.org/abs/2407.15549) | TMLR | [GitHub](https://github.com/aengusl/latent-adversarial-training) | 127 |
| Chris Liu et al. | [Large Language Model Unlearning via Embedding-Corrupted Prompts](https://doi.org/10.48550/arXiv.2406.07933) | NeurIPS | [GitHub](https://github.com/chrisliu298/llm-unlearn-eco) | 112 |
| Jin Yao et al. | [Machine Unlearning of Pre-trained Large Language Models](https://doi.org/10.48550/arXiv.2402.15159) | ACL | [GitHub](https://github.com/yaojin17/unlearning_llm) | 110 |
| Jinghan Jia et al. | [SOUL: Unlocking the Power of Second-Order Optimization for LLM Unlearning](https://doi.org/10.48550/arXiv.2404.18239) | EMNLP | [GitHub](https://github.com/optml-group/soul) | 106 |
| Chao Gong et al. | [Reliable and Efficient Concept Erasure of Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2407.12383) | ECCV | [GitHub](https://github.com/charlesgong12/rece) | 101 |
| Jakub Lucki et al. | [An Adversarial Perspective on Machine Unlearning for AI Safety](https://doi.org/10.48550/arXiv.2409.18025) | TMLR | [GitHub](https://github.com/ethz-spylab/unlearning-vs-safety) | 100 |
| Chongyu Fan et al. | [Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning](https://doi.org/10.48550/arXiv.2410.07163) | arXiv | [GitHub](https://github.com/OPTML-Group/Unlearn-Simple) | 98 |
| Leo Schwinn et al. | [Soft Prompt Threats: Attacking Safety Alignment and Unlearning in Open-Source LLMs through the Embedding Space](https://doi.org/10.48550/arXiv.2402.09063) | NeurIPS | [GitHub](https://github.com/SchwinnL/LLM_Embedding_Attack) | 94 |
| Pratiksha Thaker, Yash Maurya, Virginia Smith | [Guardrail Baselines for Unlearning in LLMs](https://doi.org/10.48550/arXiv.2403.03329) | arXiv | [GitHub](https://github.com/pratiksha/guardrail-baselines) | 91 |
| Jiabao Ji et al. | [Reversing the Forget-Retain Objectives: An Efficient LLM Unlearning Framework from Logit Difference](https://doi.org/10.48550/arXiv.2406.08607) | NeurIPS | [GitHub](https://github.com/UCSB-NLP-Chang/ULD) | 77 |
| Jamie Hayes et al. | [Inexact Unlearning Needs More Careful Evaluations to Avoid a False Sense of Privacy](https://doi.org/10.1109/SaTML64287.2025.00034) | SaTML | — | 77 |
| Rohit Gandikota et al. | [Unified Concept Editing in Diffusion Models](https://doi.org/10.1109/wacv57701.2024.00503) | arXiv | [GitHub](https://github.com/rohitgandikota/unified-concept-editing) | 77 |
| Jie Xu et al. | [Machine Unlearning: Solutions and Challenges](https://doi.org/10.1109/tetci.2024.3379240) | IEEE TETCI | [GitHub](https://github.com/pybrush/pybrush) | 72 |
| Kairan Zhao et al. | [What makes unlearning hard and what to do about it](https://doi.org/10.48550/arXiv.2406.01257) | NeurIPS | [GitHub](https://github.com/kairanzhao/RUM) | 72 |
| Daiheng Gao et al. | [EraseAnything: Enabling Concept Erasure in Rectified Flow Transformers](https://doi.org/10.48550/arXiv.2412.20413) | arXiv | [GitHub](https://github.com/tomguluson92/eraseanything) | 71 |
| Pengfei Wang et al. | [Server-Initiated Federated Unlearning to Eliminate Impacts of Low-Quality Data](https://doi.org/10.1109/tsc.2024.3355188) | IEEE TSC | — | 70 |
| Debeshee Das, Jie Zhang, F. Tramèr | [Blind Baselines Beat Membership Inference Attacks for Foundation Models](https://doi.org/10.1109/SPW67851.2025.00016) | SPW | [GitHub](https://github.com/ethz-spylab/Blind-MIA) | 68 |
| Zhuoran Jin et al. | [RWKU: Benchmarking Real-World Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2406.10890) | NeurIPS | [GitHub](https://github.com/jinzhuoran/rwku) | 66 |
| Yaxuan Wang et al. | [LLM Unlearning via Loss Adjustment with Only Forget Data](https://doi.org/10.48550/arXiv.2410.11143) | ICLR | [GitHub](https://github.com/UCSC-REAL/FLAT) | 63 |
| Hongsheng Hu et al. | [Learn What You Want to Unlearn: Unlearning Inversion Attacks against Machine Unlearning](https://doi.org/10.1109/SP54263.2024.00248) | IEEE S&P | [GitHub](https://github.com/pytorch/opacus/blob) | 62 |
| Yihua Zhang et al. | [UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models](https://doi.org/10.48550/arXiv.2402.11846) | arXiv | — | 62 |
| Zhiwei Zhang et al. | [Catastrophic Failure of LLM Unlearning via Quantization](https://arxiv.org/abs/2410.16454) | ICLR | [GitHub](https://github.com/zzwjames/FailureLLMUnlearning) | 59 |
| Ziyao Liu et al. | [Threats, Attacks, and Defenses in Machine Unlearning: A Survey](https://doi.org/10.1109/OJCS.2025.3543483) | IEEE Open Journal of the Computer Society | — | 59 |
| Xiangshan Gao et al. | [VeriFi: Towards Verifiable Federated Unlearning](https://doi.org/10.1109/tdsc.2024.3382321) | IEEE TDSC | — | 58 |
| Aghyad Deeb, Fabien Roger | [Do Unlearning Methods Remove Information from Language Model Weights?](https://doi.org/10.48550/arXiv.2410.08827) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 58 |
| Guihong Li et al. | [Machine Unlearning for Image-to-Image Generative Models](https://doi.org/10.48550/arXiv.2402.00351) | ICLR | [GitHub](https://github.com/jpmorganchase/i2i-generator-unlearning) | 56 |
| Jack Foster, Stefan Schoepf, Alexandra Brintrup | [Fast Machine Unlearning without Retraining through Selective Synaptic Dampening](https://doi.org/10.1609/aaai.v38i11.29092) | AAAI | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 54 |
| Chongyu Fan et al. | [Challenging Forgets: Unveiling the Worst-Case Forget Sets in Machine Unlearning](https://doi.org/10.48550/arXiv.2403.07362) | ECCV | [GitHub](https://github.com/optml-group/unlearn-worstcase) | 54 |
| Ilia Shumailov et al. | [UnUnlearning: Unlearning is not sufficient for content regulation in advanced generative AI](https://doi.org/10.48550/arXiv.2407.00106) | arXiv | — | 54 |
| C. Kim, Kyle Min, Yezhou Yang | [R.A.C.E.: Robust Adversarial Concept Erasure for Secure Text-to-Image Diffusion Model](https://doi.org/10.48550/arXiv.2405.16341) | ECCV | [GitHub](https://github.com/chkimmmmm/R.A.C.E) | 53 |
| Weikai Lu et al. | [Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge](https://doi.org/10.48550/arXiv.2404.05880) | arXiv | [GitHub](https://github.com/ZeroNLP/Eraser) | 53 |
| Eoin Farrell, Yeu-Tong Lau, Arthur Conmy | [Applying sparse autoencoders to unlearn knowledge in language models](https://doi.org/10.48550/arXiv.2410.19278) | arXiv | [GitHub](https://github.com/efarrell1/train_sparse_autoencoder) | 53 |
| Jing Huang, Diyi Yang, Christopher Potts | [Demystifying Verbatim Memorization in Large Language Models](https://doi.org/10.48550/arXiv.2407.17817) | EMNLP | [GitHub](https://github.com/explanare/verbatim-memorization) | 52 |
| Shengyuan Hu et al. | [Unlearning or Obfuscating? Jogging the Memory of Unlearned LLMs via Benign Relearning](https://arxiv.org/abs/2406.13356) | ICLR | [GitHub](https://github.com/s-huu/jog_llm_memory) | 50 |
| Zheyuan Liu et al. | [Machine Unlearning in Generative AI: A Survey](https://doi.org/10.48550/arXiv.2407.20516) | arXiv | [GitHub](https://github.com/franciscoliu/GenAI-MU-Reading) | 50 |
| Jing Wu, Mehrtash Harandi | [Scissorhands: Scrub Data Influence via Connection Sensitivity in Networks](https://doi.org/10.48550/arXiv.2401.06187) | ECCV | [GitHub](https://github.com/JingWu321/Scissorhands) | 49 |
| Pratiksha Thaker et al. | [Position: LLM Unlearning Benchmarks are Weak Measures of Progress](https://doi.org/10.1109/SaTML64287.2025.00035) | SaTML | [HF](https://huggingface.co/datasets/forgelab/wmdp-swap) | 49 |
| Weiqi Wang, Zhiyi Tian, Shui Yu | [Machine Unlearning: A Comprehensive Survey](https://doi.org/10.48550/arXiv.2405.07406) | arXiv | [GitHub](https://github.com/pybrush/pybrush) | 49 |
| Yong-Hyun Park et al. | [Direct Unlearning Optimization for Robust and Safe Text-to-Image Models](https://doi.org/10.48550/arXiv.2407.21035) | NeurIPS | [GitHub](https://github.com/naver-ai/DUO) | 48 |
| Jing Wu et al. | [EraseDiff: Erasing Data Influence in Diffusion Models](https://doi.org/10.48550/arXiv.2401.05779) | arXiv | [GitHub](https://github.com/JingWu321/EraseDiff) | 48 |
| Ruchika Chavhan, Da Li, Timothy M. Hospedales | [ConceptPrune: Concept Editing in Diffusion Models via Skilled Neuron Pruning](https://doi.org/10.48550/arXiv.2405.19237) | ICLR | [GitHub](https://github.com/liuxuannan/Awesome-Multimodal-Jailbreak) | 47 |
| Eleni Triantafillou et al. | [Are we making progress in unlearning? Findings from the first NeurIPS unlearning competition](https://doi.org/10.48550/arXiv.2406.09073) | arXiv | [GitHub](https://github.com/google-deepmind/unlearning_evaluation) | 47 |
| Eli Chien et al. | [Langevin Unlearning: A New Perspective of Noisy Gradient Descent for Machine Unlearning](https://doi.org/10.48550/arXiv.2401.10371) | NeurIPS | [GitHub](https://github.com/Graph-COM/Langevin_unlearning) | 45 |
| Boyi Wei et al. | [Evaluating Copyright Takedown Methods for Language Models](https://doi.org/10.48550/arXiv.2406.18664) | NeurIPS | [HF](https://huggingface.co/spaces/boyiwei/CoTaEval_leaderboard) | 44 |
| Lingzhi Wang et al. | [Selective Forgetting: Advancing Machine Unlearning Techniques and Evaluation in Language Models](https://doi.org/10.48550/arXiv.2402.05813) | AAAI | [GitHub](https://github.com/google-research/lm-extraction-benchmark) | 43 |
| Shilin Lu et al. | [MACE: Mass Concept Erasure in Diffusion Models](https://doi.org/10.1109/cvpr52733.2024.00615) | CVPR | [GitHub](https://github.com/Shilin-LU/MACE) | 42 |
| Zheyuan Liu et al. | [Protecting Privacy in Multimodal Large Language Models with MLLMU-Bench](https://doi.org/10.48550/arXiv.2410.22108) | NAACL | [GitHub](https://github.com/franciscoliu/MLLMU-Bench) | 42 |
| A. Cooper et al. | [Machine Unlearning Doesn't Do What You Think: Lessons for Generative AI Policy, Research, and Practice](https://doi.org/10.48550/arXiv.2412.06966) | arXiv | — | 42 |
| J. Olivo et al. | [Optimal design of steel exoskeleton for the retrofitting of RC buildings via genetic algorithm](https://doi.org/10.1016/j.compstruc.2024.107396) | Computers &amp; Structures | — | 41 |
| George-Octavian Barbulescu, Peter Triantafillou | [To Each (Textual Sequence) Its Own: Improving Memorized-Data Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2405.03097) | ICML | [GitHub](https://github.com/GeorgeOctavian/selective_unlearning) | 41 |
| Nicolò Romandini et al. | [Federated Unlearning: A Survey on Methods, Design Guidelines, and Evaluation Metrics](https://doi.org/10.1109/tnnls.2024.3478334) | IEEE TNNLS | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 41 |
| Xiaojian \ Yuan et al. | [A Closer Look at Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2410.08109) | ICLR | [GitHub](https://github.com/sail-sg/closer-look-LLM-unlearning) | 40 |
| Thanveer Shaik et al. | [Exploring the Landscape of Machine Unlearning: A Comprehensive Survey and Taxonomy](https://doi.org/10.1109/tnnls.2024.3486109) | IEEE TNNLS | — | 40 |
| Jiaqi Li et al. | [Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2405.12523) | NeurIPS | — | 40 |
| Nicholas Pochinkov, Nandi Schoots | [Dissecting Language Models: Machine Unlearning via Selective Pruning](https://doi.org/10.48550/arXiv.2403.01267) | arXiv | [GitHub](https://github.com/nickypro/selective-pruning) | 40 |
| Anh-Vu Bui et al. | [Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation](https://doi.org/10.48550/arXiv.2410.15618) | NeurIPS | [GitHub](https://github.com/tuananhbui89/Erasing-Adversarial-Preservation) | 39 |
| Zhehao Huang et al. | [Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://doi.org/10.48550/arXiv.2409.19732) | NeurIPS | [GitHub](https://github.com/K1nght/Unified-Unlearning-w-Remain-Geometry) | 38 |
| Chongyang Gao et al. | [On Large Language Model Continual Unlearning](https://arxiv.org/abs/2407.10223) | ICLR | [GitHub](https://github.com/gcyzsl/o3-llm-unlearning) | 37 |
| Yujian Liu et al. | [Revisiting Who’s Harry Potter: Towards Targeted Unlearning from a Causal Intervention Perspective](https://doi.org/10.48550/arXiv.2407.16997) | EMNLP | [GitHub](https://github.com/ucsb-nlp-chang/causal_unlearn) | 35 |
| Jing Wu et al. | [Erasing Undesirable Influence in Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02632) | CVPR | [GitHub](https://github.com/hxxdtd/Awesome-Diffusion-Model-Unlearning) | 33 |
| Martin Pawelczyk et al. | [Machine Unlearning Fails to Remove Data Poisoning Attacks](https://doi.org/10.48550/arXiv.2406.17216) | ICLR | [GitHub](https://github.com/MartinPawelczyk/OpenUnlearn) | 33 |
| Binchi Zhang et al. | [Towards Certified Unlearning for Deep Neural Networks](https://doi.org/10.48550/arXiv.2408.00920) | ICML | [GitHub](https://github.com/zhangbinchi/certified-deep-unlearning) | 31 |
| James Y. Huang et al. | [Offset Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2404.11045) | TMLR | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 31 |
| Siyuan Liang et al. | [Unlearning Backdoor Threats: Enhancing Backdoor Defense in Multimodal Contrastive Learning via Local Token Unlearning](https://doi.org/10.48550/arXiv.2403.16257) | arXiv | [GitHub](https://github.com/usnistgov/trojai-literature) | 31 |
| Masane Fuchi, Tomohiro Takagi | [Erasing Concepts from Text-to-Image Diffusion Models with Few-shot Unlearning](https://doi.org/10.48550/arXiv.2405.07288) | BMVC | [GitHub](https://github.com/fmp453/few-shot-erasing) | 30 |
| Karuna Bhaila, Minh-Hao Van, Xintao Wu | [Soft Prompting for Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2406.12038) | NAACL | [GitHub](https://github.com/karuna-bhaila/llm_unlearning) | 30 |
| Hongbo Zhao et al. | [Continual Forgetting for Pre-Trained Vision Models](https://doi.org/10.1109/CVPR52733.2024.02705) | CVPR | [GitHub](https://github.com/bjzhb666/GS-LoRA) | 29 |
| Ali Satvaty, Suzan Verberne, Fatih Turkmen | [Undesirable Memorization in Large Language Models: A Survey](https://doi.org/10.48550/arXiv.2410.02650) | arXiv | [GitHub](https://github.com/alistvt/undesirable-llm-memorization) | 29 |
| Minh Pham et al. | [Robust Concept Erasure Using Task Vectors](https://doi.org/10.48550/arXiv.2404.03631) | arXiv | [GitHub](https://github.com/mnpham0417/prompt-agnostic-concept-erasure) | 29 |
| Dawen Zhang et al. | [Right to be forgotten in the Era of large language models: implications, challenges, and solutions](https://doi.org/10.1007/s43681-024-00573-9) | AI and Ethics | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 28 |
| Chen Wu et al. | [Unlearning Backdoor Attacks in Federated Learning](https://doi.org/10.1109/CNS62487.2024.10735680) | CNS | — | 28 |
| Somnath Basu Roy Chowdhury et al. | [Towards Scalable Exact Machine Unlearning Using Parameter-Efficient Fine-Tuning](https://doi.org/10.48550/arXiv.2406.16257) | ICLR | [GitHub](https://github.com/brcsomnath/S3T) | 28 |
| Sungmin Cha et al. | [Towards Robust and Parameter-Efficient Knowledge Unlearning for LLMs](https://arxiv.org/abs/2408.06621) | ICLR | [GitHub](https://github.com/csm9493/efficient-llm-unlearning) | 28 |
| Zhiqi Bu et al. | [Unlearning as multi-task optimization: A normalized gradient difference approach with an adaptive learning rate](https://doi.org/10.48550/arXiv.2410.22086) | NAACL | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 28 |
| Anmol Reddy Mekala et al. | [Alternate Preference Optimization for Unlearning Factual Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2409.13474) | arXiv | [GitHub](https://github.com/molereddy/Alternate-Preference-Optimization) | 28 |
| Hongcheng Gao et al. | [Meta-Unlearning on Diffusion Models: Preventing Relearning Unlearned Concepts](https://doi.org/10.48550/arXiv.2410.12777) | arXiv | [GitHub](https://github.com/sail-sg/Meta-Unlearning) | 28 |
| Sungmin Cha et al. | [Learning to Unlearn: Instance-Wise Unlearning for Pre-trained Classifiers](https://doi.org/10.1609/aaai.v38i10.28996) | AAAI | [GitHub](https://github.com/csm9493/L2UL) | 27 |
| Martin Bertran et al. | [Reconstruction Attacks on Machine Unlearning: Simple Models are Vulnerable](https://doi.org/10.48550/arXiv.2405.20272) | NeurIPS | — | 27 |
| Hongsheng Hu et al. | [Learn What You Want to Unlearn: Unlearning Inversion Attacks against Machine Unlearning](https://doi.org/10.1109/sp54263.2024.00248) | SP | — | 27 |
| Hongbang Yuan et al. | [Towards Robust Knowledge Unlearning: An Adversarial Framework for Assessing and Improving Unlearning Robustness in Large Language Models](https://doi.org/10.48550/arXiv.2408.10682) | AAAI | [HF](https://huggingface.co/muse-bench/MUSE-news) | 26 |
| Bo Tian et al. | [To Forget or Not? Towards Practical Knowledge Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2407.01920) | EMNLP | [GitHub](https://github.com/zjunlp/knowundo) | 26 |
| Qizhou Wang et al. | [Towards Effective Evaluations and Comparisons for LLM Unlearning Methods](https://arxiv.org/abs/2406.09179) | ICLR | [GitHub](https://github.com/tmlr-group/Unlearning-with-Control) | 26 |
| Andrei Muresanu et al. | [Fast Exact Unlearning for In-Context Learning Data for LLMs](https://arxiv.org/abs/2402.00751) | ICML | — | 26 |
| ZhiYu Hu et al. | [Exact and Efficient Unlearning for Large Language Model-Based Recommendation](https://doi.org/10.1109/TKDE.2025.3594687) | IEEE TKDE | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 26 |
| Hengzhu Liu et al. | [A Survey on Machine Unlearning: Techniques and New Emerged Privacy Risks](https://doi.org/10.48550/arXiv.2406.06186) | Journal of Information Security and Applications | [GitHub](https://github.com/awatson246/forecast-unlearning) | 26 |
| Guangyao Dou et al. | [Avoiding Copyright Infringement via Large Language Model Unlearning](https://doi.org/10.18653/v1/2025.findings-naacl.288) | NAACL | [GitHub](https://github.com/guangyaodou/SSU_Unlearn) | 26 |
| Shashwat Goel et al. | [Corrective Machine Unlearning](https://doi.org/10.48550/arXiv.2402.14015) | TMLR | [GitHub](https://github.com/drimpossible/corrective-unlearning-bench) | 26 |
| Tianyun Yang, Juan Cao, Chang Xu | [Pruning for Robust Concept Erasing in Diffusion Models](https://doi.org/10.48550/arXiv.2405.16534) | arXiv | [GitHub](https://github.com/xiye7lai/Awesome-Generative-Image-Unlearning) | 26 |
| Trishna Chakraborty et al. | [Cross-Modal Safety Alignment: Is textual unlearning all you need?](https://doi.org/10.48550/arXiv.2406.02575) | EMNLP | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 25 |
| Tianqi Chen, Shujian Zhang, Mi Zhou | [Score Forgetting Distillation: A Swift, Data-Free Method for Machine Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2409.11219) | ICLR | [GitHub](https://github.com/tqch/score-forgetting-distillation) | 25 |
| Rohit Gandikota et al. | [Erasing Conceptual Knowledge from Language Models](https://doi.org/10.48550/arXiv.2410.02760) | arXiv | [GitHub](https://github.com/rohitgandikota/erasing-llm) | 25 |
| Yuan Wang et al. | [Precise, Fast, and Low-cost Concept Erasure in Value Space: Orthogonal Complement Matters](https://doi.org/10.1109/CVPR52734.2025.02678) | CVPR | [GitHub](https://github.com/WYuan1001/AdaVD) | 24 |
| Mark He Huang, Lin Geng Foo, Jun Liu | [Learning to Unlearn for Robust Machine Unlearning](https://doi.org/10.48550/arXiv.2407.10494) | ECCV | — | 24 |
| Hanlin Gu et al. | [Unlearning during Learning: An Efficient Federated Machine Unlearning Method](https://doi.org/10.48550/arXiv.2405.15474) | IJCAI | [GitHub](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) | 24 |
| Youyang Qu et al. | [The Frontier of Data Erasure: Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2403.15779) | arXiv | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 24 |
| Mengnan Zhao et al. | [Separable Multi-Concept Erasure from Diffusion Models](https://doi.org/10.48550/arXiv.2402.05947) | arXiv | [GitHub](https://github.com/xiye7lai/Awesome-Generative-Image-Unlearning) | 24 |
| Kongyang Chen et al. | [Machine Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2404.16841) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 24 |
| Chaochao Chen et al. | [Post-Training Attribute Unlearning in Recommender Systems](https://doi.org/10.1145/3701987) | ACM Transactions on Information Systems | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 23 |
| Yang Zhang et al. | [Recommendation Unlearning via Influence Function](https://doi.org/10.1145/3701763) | ACM Transactions on Recommender Systems | [GitHub](https://github.com/baiyimeng/IFRU) | 23 |
| Jacopo Bonato, Marco Cotogni, Luigi Sabetta | [Is Retain Set All You Need in Machine Unlearning? Restoring Performance of Unlearned Models with Out-Of-Distribution Images](https://doi.org/10.48550/arXiv.2404.12922) | ECCV | [GitHub](https://github.com/jbonato1/scar) | 23 |
| Yihuai Hong et al. | [Intrinsic Test of Unlearning Using Parametric Knowledge Traces](https://doi.org/10.18653/v1/2025.emnlp-main.985) | EMNLP | [GitHub](https://github.com/yihuaihong/conceptvectors) | 23 |
| P. Guo et al. | [Mechanistic Unlearning: Robust Knowledge Unlearning and Editing via Mechanistic Localization](https://doi.org/10.48550/arXiv.2410.12949) | ICML | — | 23 |
| Zihao Liu et al. | [Backdoor Attacks via Machine Unlearning](https://doi.org/10.1609/aaai.v38i13.29321) | AAAI | [GitHub](https://github.com/diadai/Machine-Unlearning) | 22 |
| Youyang Qu et al. | [Learn to Unlearn: Insights Into Machine Unlearning](https://doi.org/10.1109/mc.2023.3333319) | Computer | — | 22 |
| Huajie Chen et al. | [QUEEN: Query Unlearning Against Model Extraction](https://doi.org/10.1109/TIFS.2025.3538266) | IEEE T-IFS | [GitHub](https://github.com/MaraPapMann/QUEEN) | 22 |
| Huiqiang Chen et al. | [Machine Unlearning via Null Space Calibration](https://doi.org/10.48550/arXiv.2404.13588) | IJCAI | [GitHub](https://github.com/HQC-ML/UNSC) | 22 |
| Hongsheng Hu et al. | [A Duty to Forget, a Right to be Assured? Exposing Vulnerabilities in Machine Unlearning Services](https://doi.org/10.14722/ndss.2024.24252) | NDSS | — | 22 |
| Daniel Trippa et al. | [∇ τ: Gradient-based and Task-Agnostic machine Unlearning](https://doi.org/10.48550/arXiv.2403.14339) | arXiv | — | 22 |
| Jai Doshi, Asa Cooper Stickland | [Does Unlearning Truly Unlearn? A Black Box Evaluation of LLM Unlearning Methods](https://doi.org/10.48550/arXiv.2411.12103) | arXiv | [GitHub](https://github.com/jaidoshi/knowledge-erasure) | 22 |
| Yao Jin et al. | [Machine Unlearning of Pre-trained Large Language Models](https://doi.org/10.18653/v1/2024.acl-long.457) | arXiv | [GitHub](https://github.com/yaojin17/Unlearning_LLM) | 22 |
| Zhenhua Liu et al. | [Learning to Refuse: Towards Mitigating Privacy Risks in LLMs](https://doi.org/10.48550/arXiv.2407.10058) | COLING | [GitHub](https://github.com/zhliu0106/learning-to-refuse) | 21 |
| Binchi Zhang et al. | [Verification of Machine Unlearning is Fragile](https://doi.org/10.48550/arXiv.2408.00929) | ICML | [GitHub](https://github.com/zhangbinchi/unlearning-verification-is-fragile) | 21 |
| Shang Wang et al. | [When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?](https://doi.org/10.1109/TDSC.2025.3620832) | IEEE TDSC | [GitHub](https://github.com/infiniflow/ragflow) | 21 |
| Xuhan Zuo et al. | [Federated Learning With Blockchain-Enhanced Machine Unlearning: A Trustworthy Approach](https://doi.org/10.1109/TSC.2025.3553709) | IEEE TSC | — | 21 |
| Sheng-Yu Wang et al. | [Data Attribution for Text-to-Image Models by Unlearning Synthesized Images](https://doi.org/10.48550/arXiv.2406.09408) | NeurIPS | [GitHub](https://github.com/PeterWang512/AttributeByUnlearning) | 21 |
| Hanlin Gu et al. | [Ferrari: Federated Feature Unlearning via Optimizing Feature Sensitivity](https://doi.org/10.48550/arXiv.2405.17462) | NeurIPS | [GitHub](https://github.com/OngWinKent/Federated-Feature-Unlearning) | 21 |
| Yu Jiang et al. | [Efficient Federated Unlearning with Adaptive Differential Privacy Preservation](https://doi.org/10.1109/BigData62323.2024.10825236) | BigData Congress [Services Society] | — | 20 |
| T. Huynh et al. | [Fast-FedUL: A Training-Free Federated Unlearning with Provable Skew Resilience](https://doi.org/10.48550/arXiv.2405.18040) | ECML/PKDD | [GitHub](https://github.com/thanhtrunghuynh93/fastFedUL) | 20 |
| Yihuai Hong et al. | [Dissecting Fine-Tuning Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2410.06606) | EMNLP | [GitHub](https://github.com/yihuaihong/Dissecting-FT-Unlearning) | 20 |
| Shao Shen et al. | [Label-Agnostic Forgetting: A Supervision-Free Unlearning in Deep Models](https://doi.org/10.48550/arXiv.2404.00506) | ICLR | [GitHub](https://github.com/shaofeishen768/laf) | 20 |
| Jiajun Tan et al. | [Unlink to Unlearn: Simplifying Edge Unlearning in GNNs](https://doi.org/10.48550/arXiv.2402.10695) | WWW | [GitHub](https://github.com/Sumsky21/Unlink-to-Unlearn) | 20 |
| S. Kadhe et al. | [Split, Unlearn, Merge: Leveraging Data Attributes for More Effective Unlearning in LLMs](https://doi.org/10.48550/arXiv.2406.11780) | arXiv | — | 20 |
| Bichen Wang et al. | [RKLD: Reverse KL-Divergence-based Knowledge Distillation for Unlearning Personal Information in Large Language Models](https://doi.org/10.48550/arXiv.2406.01983) | arXiv | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 20 |
| Chen Wu et al. | [Unlearning Backdoor Attacks in Federated Learning](https://doi.org/10.1109/cns62487.2024.10735680) | CNS | — | 19 |
| Chenlu Ding et al. | [Unified Parameter-Efficient Unlearning for LLMs](https://doi.org/10.48550/arXiv.2412.00383) | ICLR | [GitHub](https://github.com/oceanoceanna/LLMEraser) | 19 |
| Yan Scholten, Stephan Günnemann, Leo Schwinn | [A Probabilistic Perspective on Unlearning and Alignment for Large Language Models](https://doi.org/10.48550/arXiv.2410.03523) | ICLR | [GitHub](https://github.com/yascho/probabilistic-unlearning) | 19 |
| Lijie Hu et al. | [Editable Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2405.15476) | ICML | [GitHub](https://github.com/kaustpradalab/ECBM) | 19 |
| Yijing Lin et al. | [Scalable Federated Unlearning via Isolated and Coded Sharding](https://doi.org/10.48550/arXiv.2401.15957) | IJCAI | [GitHub](https://github.com/karpathy/nanoGPT) | 19 |
| Yijing Lin et al. | [Incentive and Dynamic Client Selection for Federated Unlearning](https://doi.org/10.1145/3589334.3645462) | WWW | — | 19 |
| Alex Cloud et al. | [Gradient Routing: Masking Gradients to Localize Computation in Neural Networks](https://doi.org/10.48550/arXiv.2410.04332) | arXiv | [GitHub](https://github.com/kxcloud/gradient-routing) | 19 |
| Kang Gu et al. | [Second-Order Information Matters: Revisiting Machine Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2403.10557) | arXiv | — | 19 |
| Tianyu Yang et al. | [CLIPErase: Efficient Unlearning of Visual-Textual Associations in CLIP](https://doi.org/10.48550/arXiv.2410.23330) | ACL | [GitHub](https://github.com/Tianyu-yang-anna/ClipErase-ACL) | 18 |
| Juwon Seo et al. | [Generative Unlearning for Any Identity](https://doi.org/10.1109/CVPR52733.2024.00874) | CVPR | [GitHub](https://github.com/KHU-AGI/GUIDE) | 18 |
| K. Srivatsan et al. | [STEREO: A Two-Stage Framework for Adversarially Robust Concept Erasing from Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02213) | CVPR | [GitHub](https://github.com/koushiksrivats/robust-concept-erasing) | 18 |
| Jiasi Weng et al. | [Proof of Unlearning: Definitions and Instantiation](https://doi.org/10.1109/tifs.2024.3358993) | IEEE T-IFS | [GitHub](https://github.com/James-yaoshenglong/unlearning-TEE) | 18 |
| Thanveer Shaik et al. | [FRAMU: Attention-Based Machine Unlearning Using Federated Reinforcement Learning](https://doi.org/10.1109/tkde.2024.3382726) | IEEE TKDE | — | 18 |
| H. Lee et al. | [Contrastive Unlearning: A Contrastive Approach to Machine Unlearning](https://doi.org/10.48550/arXiv.2401.10458) | IJCAI | [GitHub](https://github.com/Hongkyu-Lee/Contrastive-Unlearning) | 18 |
| Myeongseob Ko et al. | [Boosting Alignment for Post-Unlearning Text-to-Image Generative Models](https://doi.org/10.48550/arXiv.2412.07808) | NeurIPS | [GitHub](https://github.com/reds-lab/Restricted_gradient_diversity_unlearning) | 18 |
| Jinghan Jia et al. | [WAGLE: Strategic Weight Attribution for Effective and Modular Unlearning in Large Language Models](https://doi.org/10.48550/arXiv.2410.17509) | NeurIPS | [GitHub](https://github.com/OPTML-Group/WAGLE) | 18 |
| Youming Tao et al. | [Communication Efficient and Provable Federated Unlearning](https://doi.org/10.14778/3641204.3641220) | VLDB Endowment | [GitHub](https://github.com/Happy2Git/FATS_supplement) | 18 |
| Zhiwei Zhang et al. | [Does your LLM truly unlearn? An embarrassingly simple approach to recover unlearned knowledge](https://doi.org/10.48550/arXiv.2410.16454) | arXiv | — | 18 |
| Tianle Gu et al. | [MEOW: MEMOry Supervised LLM Unlearning Via Inverted Facts](https://doi.org/10.48550/arXiv.2409.11844) | arXiv | [GitHub](https://github.com/Carol-gutianle/MEOW) | 18 |
| Md. Rafi Ur Rashid et al. | [Forget to Flourish: Leveraging Machine-Unlearning on Pretrained Language Models for Privacy Leakage](https://doi.org/10.48550/arXiv.2408.17354) | AAAI | [HF](https://huggingface.co/docs/hub/en) | 17 |
| Zheyuan Liu et al. | [Towards Safer Large Language Models through Machine Unlearning](https://doi.org/10.18653/v1/2024.findings-acl.107) | Findings | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 17 |
| Yash Sinha, Murari Mandal, Mohan S. Kankanhalli | [UnStar: Unlearning with Self-Taught Anti-Sample Reasoning for LLMs](https://doi.org/10.48550/arXiv.2410.17050) | TMLR | — | 17 |
| Zhexin Zhang et al. | [From Theft to Bomb-Making: The Ripple Effect of Unlearning in Defending Against Jailbreak Attacks](https://arxiv.org/abs/2407.02855) | arXiv | [GitHub](https://github.com/thu-coai/safeunlearning) | 17 |
| Siqiao Mu, Diego Klabjan | [Rewind-to-Delete: Certified Machine Unlearning for Nonconvex Functions](https://doi.org/10.48550/arXiv.2409.09778) | arXiv | [GitHub](https://github.com/siqiaomu/r2d) | 17 |
| Minseok Choi et al. | [SNAP: Unlearning Selective Knowledge in Large Language Models with Negative Instructions](https://doi.org/10.48550/arXiv.2406.12329) | arXiv | — | 17 |
| Tomer Ashuach, Martin Tutek, Yonatan Belinkov | [REVS: Unlearning Sensitive Information in Language Models via Rank Editing in the Vocabulary Space](https://doi.org/10.48550/arXiv.2406.09325) | ACL | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 16 |
| Shangyu Xing et al. | [EFUF: Efficient Fine-Grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models](https://doi.org/10.48550/arXiv.2402.09801) | EMNLP | [GitHub](https://github.com/starreeze/efuf) | 16 |
| Yingzi Ma et al. | [Benchmarking Vision Language Model Unlearning via Fictitious Facial Identity Dataset](https://doi.org/10.48550/arXiv.2411.03554) | ICLR | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 16 |
| Yangsibo Huang et al. | [Unlearn and Burn: Adversarial Machine Unlearning Requests Destroy Model Accuracy](https://doi.org/10.48550/arXiv.2410.09591) | ICLR | [GitHub](https://github.com/daogaoliu/unlearning-under-adversary) | 16 |
| Yiming Fei, Jiangang Li, Yanan Li | [Selective Memory Recursive Least Squares: Recast Forgetting Into Memory in RBF Neural Network-Based Real-Time Learning](https://doi.org/10.1109/tnnls.2024.3385407) | IEEE TNNLS | — | 16 |
| Anik Islam et al. | [A Federated Unlearning-Based Secure Management Scheme to Enable Automation in Smart Consumer Electronics Facilitated by Digital Twin](https://doi.org/10.1109/tce.2024.3396723) | IEEE Transactions on Consumer Electronics | — | 16 |
| Zirui Huang, Yunlong Mao, Sheng Zhong | [UBA-Inf: Unlearning Activated Backdoor Attack with Influence-Driven Camouflage](https://www.semanticscholar.org/paper/3cbddd0096c05459f8589f0dd6ec2c49e3f8a00f) | USENIX Security | [GitHub](https://github.com/Huangzirui1206/UBA-Inf) | 16 |
| Xunkai Li et al. | [Towards Effective and General Graph Unlearning via Mutual Evolution](https://doi.org/10.1609/aaai.v38i12.29273) | AAAI | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 15 |
| Alexey Dontsov et al. | [CLEAR: Character Unlearning in Textual and Visual Modalities](https://doi.org/10.18653/v1/2025.findings-acl.1058) | ACL | [GitHub](https://github.com/somvy/multimodal_unlearning) | 15 |
| Yu Wang et al. | [Large Scale Knowledge Washing](https://doi.org/10.48550/arXiv.2405.16720) | ICLR | [GitHub](https://github.com/wangyu-ustc/LargeScaleWashing) | 15 |
| Mengde Han et al. | [Vertical Federated Unlearning via Backdoor Certification](https://doi.org/10.1109/TSC.2025.3536312) | IEEE TSC | — | 15 |
| Mark Lawler, Grazia Scocca, Françoise Meunier | [Ending financial discrimination for cancer survivors: embedding the Right to be Forgotten in legislation across Europe](https://doi.org/10.1016/s1470-2045(24)00312-7) | The Lancet Oncology | — | 15 |
| Alexey Kravets, Vinay P. Namboodiri | [Zero-Shot Class Unlearning in CLIP with Synthetic Samples](https://doi.org/10.1109/WACV61041.2025.00629) | WACV | [GitHub](https://github.com/akres001/Zero-Shot-Class-Unlearning-in-CLIP-with-Synthetic-Samples) | 15 |
| Vinith M. Suriyakumar et al. | [Unstable Unlearning: The Hidden Risk of Concept Resurgence in Diffusion Models](https://doi.org/10.48550/arXiv.2410.08074) | arXiv | [GitHub](https://github.com/Giphy/celeb-detection-oss) | 15 |
| Shiji Zhou et al. | [On the Limitations and Prospects of Machine Unlearning for Generative AI](https://doi.org/10.48550/arXiv.2408.00376) | arXiv | — | 15 |
| Li Shan et al. | [Lifelong Learning and Selective Forgetting via Contrastive Strategy](https://doi.org/10.48550/arXiv.2405.18663) | arXiv | [GitHub](https://github.com/XikunHuang/daily_paper) | 15 |
| Yi Xu | [Machine Unlearning for Traditional Models and Large Language Models: A Short Survey](https://doi.org/10.48550/arXiv.2404.01206) | arXiv | — | 15 |
| Chongyang Gao et al. | [Practical Unlearning for Large Language Models](https://doi.org/10.48550/arXiv.2407.10223) | arXiv | — | 15 |
| Hyunjune Kim, Sang‐Yong Tom Lee, Simon S. Woo | [Layer Attack Unlearning: Fast and Accurate Machine Unlearning via Layer Level Attack and Knowledge Distillation](https://doi.org/10.1609/aaai.v38i19.30118) | AAAI | — | 14 |
| Yuke Hu et al. | [ERASER: Machine Unlearning in MLaaS via an Inference Serving-Aware Approach](https://doi.org/10.1145/3658644.3670398) | CCS | [GitHub](https://github.com/gnipping/Awesome-ML-SP-Papers) | 14 |
| Anudeep Das et al. | [Espresso: Robust Concept Filtering in Text-to-Image Models](https://doi.org/10.1145/3714393.3726502) | Conference on Data and Application Security and Privacy | [GitHub](https://github.com/ssg-research/concept-filtering) | 14 |
| Lu Yi, Zhewei Wei | [Scalable and Certifiable Graph Unlearning: Overcoming the Approximation Error Barrier](https://arxiv.org/abs/2408.09212) | ICLR | [GitHub](https://github.com/luyi256/ScaleGUN) | 14 |
| Zonglin Di et al. | [Adversarial Machine Unlearning](https://doi.org/10.48550/arXiv.2406.07687) | ICLR | [GitHub](https://github.com/daogaoliu/unlearning-under-adversary) | 14 |
| Ziyao Liu et al. | [Privacy-Preserving Federated Unlearning With Certified Client Removal](https://doi.org/10.1109/TIFS.2025.3555868) | IEEE T-IFS | — | 14 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [<i>Get Rid of Your Trail</i>: Remotely Erasing Backdoors in Federated Learning](https://doi.org/10.1109/tai.2024.3465441) | IEEE TAI | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 14 |
| Heng Xu et al. | [Update Selective Parameters: Federated Machine Unlearning Based on Model Explanation](https://doi.org/10.1109/tbdata.2024.3409947) | IEEE TBD | — | 14 |
| Kun Gao et al. | [Defending against gradient inversion attacks in federated learning via statistical machine unlearning](https://doi.org/10.1016/j.knosys.2024.111983) | Knowledge-Based Systems | — | 14 |
| Adrian Klammer et al. | [Organizational unlearning as a process: What we know, what we don’t know, what we should know](https://doi.org/10.1007/s11301-024-00430-3) | Management Review Quarterly | — | 14 |
| Shao Shen et al. | [CaMU: Disentangling Causal Effects in Deep Model Unlearning](https://doi.org/10.48550/arXiv.2401.17504) | SDM | [GitHub](https://github.com/ShaofeiShen768/CaMU) | 14 |
| O. Dige et al. | [Mitigating Social Biases in Language Models through Unlearning](https://doi.org/10.48550/arXiv.2406.13551) | arXiv | [GitHub](https://github.com/EleutherAI/lm-evaluation-harness) | 14 |
| Jianing Zhu et al. | [Decoupling the Class Label and the Target Concept in Machine Unlearning](https://doi.org/10.48550/arXiv.2406.08288) | arXiv | [GitHub](https://github.com/ZFancy/TARF) | 14 |
| Atakan Seyitoglu et al. | [Extracting Unlearned Information from LLMs with Activation Steering](https://doi.org/10.48550/arXiv.2411.02631) | arXiv | — | 14 |
| Jia Li et al. | [Text Guided Image Editing with Automatic Concept Locating and Forgetting](https://doi.org/10.48550/arXiv.2405.19708) | arXiv | — | 14 |
| Anh-Vu Bui et al. | [Removing Undesirable Concepts in Text-to-Image Generative Models with Learnable Prompts](https://doi.org/10.48550/arXiv.2403.12326) | arXiv | [GitHub](https://github.com/tuananhbui89/Adaptive-Guided-Erasure) | 14 |
| Thanh Trung Huynh et al. | [Certified Unlearning for Federated Recommendation](https://doi.org/10.1145/3706419) | ACM Transactions on Information Systems | [GitHub](https://github.com/sohaib0075/CFRU-Federated-Recommendation-Unlearning) | 13 |
| Weitao Ma et al. | [Unveiling Entity-Level Unlearning for Large Language Models: A Comprehensive Analysis](https://arxiv.org/abs/2406.15796) | COLING | — | 13 |
| Minseok Choi, Kyunghyun Min, Jaegul Choo | [Cross-Lingual Unlearning of Selective Knowledge in Multilingual Language Models](https://doi.org/10.48550/arXiv.2406.12354) | EMNLP | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 13 |
| Chunxiao Li et al. | [An overview of machine unlearning](https://doi.org/10.1016/j.hcc.2024.100254) | High-Confidence Computing | [GitHub](https://github.com/DlEnginner/bias_chest_xrays) | 13 |
| Xiaoyu Xia et al. | [Edge Unlearning is Not “on Edge”! an Adaptive Exact Unlearning System on Resource-Constrained Devices](https://doi.org/10.1109/SP61157.2025.00095) | IEEE S&P | [GitHub](https://github.com/XLab-hub/CAUSE) | 13 |
| Stefan Schoepf, Jack Foster, A. Brintrup | [Potion: Towards Poison Unlearning](https://doi.org/10.48550/arXiv.2406.09173) | J. Data-centric Mach. Learn. Res | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 13 |
| Chao-Jun Chen et al. | [CURE4Rec: A Benchmark for Recommendation Unlearning with Deeper Influence](https://doi.org/10.48550/arXiv.2408.14393) | NeurIPS | [GitHub](https://github.com/xiye7lai/CURE4Rec) | 13 |
| Zheyuan Liu et al. | [Breaking the Trilemma of Privacy, Utility, and Efficiency via Controllable Machine Unlearning](https://doi.org/10.1145/3589334.3645669) | WWW | [GitHub](https://github.com/mtuann/machine-unlearning-papers) | 13 |
| Youssef Allouah et al. | [The Utility and Complexity of In- and Out-of-Distribution Machine Unlearning](https://doi.org/10.48550/arXiv.2412.09119) | arXiv | — | 13 |
| Kristian Georgiev et al. | [Attribute-to-Delete: Machine Unlearning via Datamodel Matching](https://doi.org/10.48550/arXiv.2410.23232) | arXiv | [HF](https://huggingface.co/datasets/machine-unlearning-bench/data-unlearning-bench) | 13 |
| Yufan Liu et al. | [RealEra: Semantic-level Concept Erasure via Neighbor-Concept Mining](https://doi.org/10.48550/arXiv.2410.09140) | arXiv | — | 13 |
| Zhe-Rui Yang et al. | [Erase then Rectify: A Training-Free Parameter Editing Approach for Cost-Effective Graph Unlearning](https://doi.org/10.48550/arXiv.2409.16684) | AAAI | [GitHub](https://github.com/AllminerLab/ETR) | 12 |
| Dohyun Lee et al. | [Protecting Privacy Through Approximating Optimal Parameters for Sequence Unlearning in Language Models](https://doi.org/10.48550/arXiv.2406.14091) | ACL | [HF](https://huggingface.co/datasets/monology) | 12 |
| Reza Shirkavand et al. | [Efficient Fine-Tuning and Concept Suppression for Pruned Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.01735) | CVPR | [GitHub](https://github.com/rezashkv/unlearn-ft) | 12 |
| Sivaramakrishnan Rajaraman et al. | [Semantically redundant training data removal and deep model classification performance: A study with chest X-rays](https://doi.org/10.1016/j.compmedimag.2024.102379) | Computerized Medical Imaging and Graphics | — | 12 |
| Houzhe Wang et al. | [Goldfish: An Efficient Federated Unlearning Framework](https://doi.org/10.1109/DSN58291.2024.00035) | Dependable Systems and Networks | [GitHub](https://github.com/xiao-jian-zi/MU-Goldfish-An-Efficient-Federated-Unlearning-Framework) | 12 |
| Shuyi Wang, Bing Liu, G. Zuccon | [How to Forget Clients in Federated Online Learning to Rank?](https://doi.org/10.48550/arXiv.2401.13410) | European Conference on Information Retrieval | [GitHub](https://github.com/ielab/2024-ECIR-foltr-unlearning) | 12 |
| Chenxu Zhao et al. | [Rethinking Adversarial Robustness in the Context of the Right to be Forgotten](https://doi.org/10.31274/td-20251215-153) | ICML | — | 12 |
| Yanli Yuan et al. | [Toward Efficient and Robust Federated Unlearning in IoT Networks](https://doi.org/10.1109/jiot.2024.3378329) | IEEE IoT-J | — | 12 |
| Jack Foster et al. | [An Information Theoretic Approach to Machine Unlearning](https://arxiv.org/abs/2402.01401) | TMLR | [GitHub](https://github.com/jwf40/Information-Theoretic-Unlearning) | 12 |
| Jiaqi Shao et al. | [Federated Unlearning: a Perspective of Stability and Fairness](https://doi.org/10.48550/arXiv.2402.01276) | arXiv | — | 12 |
| Jing Wu, Mehrtash Harandi | [MUNBa: Machine Unlearning via Nash Bargaining](https://doi.org/10.48550/arXiv.2411.15537) | arXiv | [GitHub](https://github.com/JingWu321/MUNBa) | 12 |
| Keltin Grimes et al. | [Gone but Not Forgotten: Improved Benchmarks for Machine Unlearning](https://doi.org/10.48550/arXiv.2405.19211) | arXiv | — | 12 |
| Stefan Schoepf, Jack Foster, A. Brintrup | [Parameter-tuning-free data entry error unlearning with adaptive selective synaptic dampening](https://doi.org/10.48550/arXiv.2402.10098) | arXiv | — | 12 |
| Anubhav Jain et al. | [TraSCE: Trajectory Steering for Concept Erasure](https://doi.org/10.48550/arXiv.2412.07658) | arXiv | [GitHub](https://github.com/anubhav1997/TraSCE) | 12 |
| Saemi Moon et al. | [Holistic Unlearning Benchmark: A Multi-Faceted Evaluation for Text-to-Image Diffusion Model Unlearning](https://doi.org/10.48550/arXiv.2410.05664) | arXiv | [GitHub](https://github.com/ml-postech/HUB) | 12 |
| SeungHoo Hong, J.Y. Lee, Simon S. Woo | [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://doi.org/10.1609/aaai.v38i19.30107) | AAAI | — | 11 |
| Zichen Wang et al. | [Efficient Vertical Federated Unlearning via Fast Retraining](https://doi.org/10.1145/3657290) | ACM Transactions on Internet Technology | [GitHub](https://github.com/fizzasarfraz515/Efficient-Vertical-Federated-Unlearning-via-Fast-Retraining) | 11 |
| Dawen Zhang et al. | [To be forgotten or to be fair: unveiling fairness implications of machine unlearning methods](https://doi.org/10.1007/s43681-023-00398-y) | AI and Ethics | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 11 |
| Dasol Choi et al. | [Towards Efficient Machine Unlearning with Data Augmentation: Guided Loss-Increasing (GLI) to Prevent the Catastrophic Model Utility Drop](https://doi.org/10.1109/CVPRW63382.2024.00014) | CVPR | [GitHub](https://github.com/Dasol-Choi/Guided_Loss_Increasing) | 11 |
| Michalinos Zembylas | [Unlearning emotional imperialism in education: political, theoretical and pedagogical implications](https://doi.org/10.1080/01596306.2024.2360091) | Discourse Studies in the Cultural Politics of Education | — | 11 |
| Juan‐Gabriel Cegarra‐Navarro, Laura Di Chiacchio, Clara Cubillas‐Para | [Enhancing green process innovation performance: The role of regenerative unlearning and knowledge base management](https://doi.org/10.1016/j.emj.2024.05.004) | European Management Journal | — | 11 |
| Hangyu Wang et al. | [Towards efficient and effective unlearning of large language models for recommendation](https://doi.org/10.1007/s11704-024-40044-2) | Frontiers of Computer Science | [GitHub](https://github.com/CHIANGEL/Awesome-LLM-for-RecSys) | 11 |
| Zibin Pan et al. | [Multi-Objective Large Language Model Unlearning](https://doi.org/10.1109/ICASSP49660.2025.10889776) | ICASSP | [GitHub](https://github.com/zibinpan/MOLLM) | 11 |
| Mansi Sakarvadia et al. | [Mitigating Memorization In Language Models](https://doi.org/10.48550/arXiv.2410.02159) | ICLR | [GitHub](https://github.com/msakarvadia/memorization) | 11 |
| Syed Irfan Ali Meerza, Amir Sadovnik, Jian Liu | [ConFUSE: Confusion-based Federated Unlearning with Salience Exploration](https://doi.org/10.1109/ISVLSI61997.2024.00083) | IEEE Computer Society Annual Symposium on VLSI | — | 11 |
| Zhengbao He et al. | [Towards Natural Machine Unlearning](https://doi.org/10.1109/TPAMI.2025.3597350) | IEEE TPAMI | [GitHub](https://github.com/ZhengbaoHe/NatMU) | 11 |
| Layan Jaman, Reem Alsharabi, Passent Elkafrawy | [Machine Unlearning: An Overview of the Paradigm Shift in the Evolution of AI](https://doi.org/10.1109/LT60077.2024.10469232) | L&T | — | 11 |
| Jiali Cheng, Hadi Amiri | [MU-Bench: A Multitask Multimodal Benchmark for Machine Unlearning](https://doi.org/10.48550/arXiv.2406.14796) | arXiv | [GitHub](https://github.com/CLU-UML/MU-Bench) | 11 |
| Romit Chatterjee et al. | [A Unified Framework for Continual Learning and Machine Unlearning](https://doi.org/10.48550/arXiv.2408.11374) | arXiv | [GitHub](https://github.com/respailab/CLMUL) | 11 |
| Bhavika Sachdeva et al. | [Machine Unlearning for Recommendation Systems: An Insight](https://doi.org/10.48550/arXiv.2401.10942) | arXiv | — | 11 |
| Jiajun Tan et al. | [Unlink to Unlearn: Simplifying Edge Unlearning in GNNs](https://doi.org/10.1145/3589335.3651578) | arXiv | [GitHub](https://github.com/Sumsky21/Unlink-to-Unlearn) | 11 |
| Dongjae Jeon et al. | [An Information Theoretic Evaluation Metric for Strong Unlearning](https://doi.org/10.1609/aaai.v40i26.39373) | AAAI | [GitHub](https://github.com/pytorch/examples/tree) | 10 |
| Jinghan Jia et al. | [SOUL: Unlocking the Power of Second-Order Optimization for LLM Unlearning](https://doi.org/10.18653/v1/2024.emnlp-main.245) | EMNLP | [GitHub](https://github.com/OPTML-Group/SOUL) | 10 |
| Jiacheng Du, Zhibo Wang, Kui Ren | [Textual Unlearning Gives a False Sense of Unlearning](https://doi.org/10.48550/arXiv.2406.13348) | ICML | [GitHub](https://github.com/wanggroupAI/TextualUnlearning) | 10 |
| Yu Jiang et al. | [Efficient Federated Unlearning with Adaptive Differential Privacy Preservation](https://doi.org/10.1109/bigdata62323.2024.10825236) | IEEE Big Data | — | 10 |
| Weijian Su et al. | [F2UL: Fairness-Aware Federated Unlearning for Data Trading](https://doi.org/10.1109/tmc.2024.3429228) | IEEE TMC | [GitHub](https://github.com/suweijian1996/F2UL) | 10 |
| Yushun Dong et al. | [IDEA: A Flexible Framework of Certified Unlearning for Graph Neural Networks](https://doi.org/10.1145/3637528.3671744) | KDD | [GitHub](https://github.com/yushundong/IDEA) | 10 |
| Jiadong Pan et al. | [Leveraging Catastrophic Forgetting to Develop Safe Diffusion Models against Malicious Finetuning](https://doi.org/10.52202/079017-3658) | NeurIPS | — | 10 |
| Jiahao Zhang | [Graph Unlearning with Efficient Partial Retraining](https://doi.org/10.1145/3589335.3651265) | WWW | — | 10 |
| Aakash Sen Sharma et al. | [Unlearning or Concealment? A Critical Analysis and Evaluation Metrics for Unlearning in Diffusion Models](https://doi.org/10.48550/arXiv.2409.05668) | arXiv | [GitHub](https://github.com/respailab/unlearning-or-concealment) | 10 |
| Yoon Wha Jung et al. | [Attack and Reset for Unlearning: Exploiting Adversarial Noise toward Machine Unlearning through Parameter Re-initialization](https://doi.org/10.48550/arXiv.2401.08998) | arXiv | — | 10 |
| Meghdad Kurmanji, Eleni Triantafillou, Peter Triantafillou | [Machine Unlearning in Learned Databases: An Experimental Analysis](https://doi.org/10.1145/3639304) | ACM on Management of Data | [GitHub](https://github.com/TsinghuaDatabaseGroup/AIDB) | 9 |
| Xinyi Sheng, Wei Bao, Liming Ge | [Robust Federated Unlearning](https://doi.org/10.1145/3627673.3679817) | CIKM | [GitHub](https://github.com/stcebra/Robust-Federated-Unlearning) | 9 |
| Zhaohan Zhang, Ziquan Liu, Ioannis Patras | [Get Confused Cautiously: Textual Sequence Memorization Erasure with Selective Entropy Maximization](https://doi.org/10.48550/arXiv.2408.04983) | COLING | — | 9 |
| Vitali Petsiuk, K. Saenko | [Concept Arithmetics for Circumventing Concept Inhibition in Diffusion Models](https://doi.org/10.48550/arXiv.2404.13706) | ECCV | [GitHub](https://github.com/SarahRastegar/Best-Papers-Top-Venues) | 9 |
| Weiqi Wang et al. | [FedU: Federated Unlearning via User-Side Influence Approximation Forgetting](https://doi.org/10.1109/tdsc.2024.3520614) | IEEE TDSC | — | 9 |
| Yuyuan Li et al. | [A Survey on Recommendation Unlearning: Fundamentals, Taxonomy, Evaluation, and Open Questions](https://doi.org/10.1109/TKDE.2025.3638174) | IEEE TKDE | — | 9 |
| Rui Ma et al. | [A Dataset and Benchmark for Copyright Infringement Unlearning from Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.12052) | Lecture Notes in Computer Science | [GitHub](https://github.com/datar001/Awesome-AD-on-T2IDM) | 9 |
| Zhi-Hui Deng, Luyang Luo, Hao Chen | [Enable the Right to be Forgotten with Federated Client Unlearning in Medical Imaging](https://doi.org/10.48550/arXiv.2407.02356) | MICCAI | [GitHub](https://github.com/dzp2095/FCU) | 9 |
| Alessandro Achille et al. | [AI model disgorgement: Methods and choices](https://doi.org/10.1073/pnas.2307304121) | National Academy of Sciences | — | 9 |
| Seonguk Seo, Dongwan Kim, Bohyung Han | [Revisiting Machine Unlearning with Dimensional Alignment](https://doi.org/10.1109/WACV61041.2025.00317) | WACV | — | 9 |
| Wenhan Chang et al. | [Class Machine Unlearning for Complex Data via Concepts Inference and Data Poisoning](https://doi.org/10.48550/arXiv.2405.15662) | arXiv | [HF](https://huggingface.co/changwh5/Concepts_Poison_Unlearning_7B) | 9 |
| Yiwen Tu, Pingbang Hu, Jiaqi Ma | [Towards Reliable Empirical Machine Unlearning Evaluation: A Game-Theoretic View](https://doi.org/10.48550/arXiv.2404.11577) | arXiv | — | 9 |
| Chonghua Liao et al. | [Exploring Forgetting in Large Language Model Pre-Training](https://doi.org/10.48550/arXiv.2410.17018) | ACL | [GitHub](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) | 8 |
| Minseok Choi et al. | [Opt-Out: Investigating Entity-Level Unlearning for Large Language Models via Optimal Transport](https://doi.org/10.18653/v1/2025.acl-long.1371) | ACL | [HF](https://huggingface.co/datasets/6rightjade/ELUDe) | 8 |
| Yizhou Dang et al. | [Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences](https://doi.org/10.1145/3706633) | ACM Transactions on Information Systems | [GitHub](https://github.com/KingGugu/GFEraser) | 8 |
| Guanhua Ye et al. | [Heterogeneous decentralised machine unlearning with seed model distillation](https://doi.org/10.1049/cit2.12281) | CAAI Transactions on Intelligence Technology | — | 8 |
| Shaojie Shi et al. | [ULMR: Unlearning Large Language Models via Negative Response and Model Parameter Average](https://doi.org/10.18653/v1/2024.emnlp-industry.57) | EMNLP | — | 8 |
| Xinwen Cheng et al. | [Remaining-data-free Machine Unlearning by Suppressing Sample Contribution](https://arxiv.org/abs/2402.15109) | ICLR Poster | [GitHub](https://github.com/poppopbean0903/MU-Mis) | 8 |
| Zikui Cai, Yaoteng Tan, M. S. Asif | [Targeted Unlearning with Single Layer Unlearning Gradient](https://arxiv.org/abs/2407.11867) | ICML | [GitHub](https://github.com/CSIPlab/slug) | 8 |
| Zhiqiang Xie et al. | [Adaptive Clipping and Distillation Enabled Federated Unlearning](https://doi.org/10.1109/ICWS62655.2024.00094) | ICWS | — | 8 |
| Heng Xu et al. | [Really Unlearned? Verifying Machine Unlearning via Influential Sample Pairs](https://doi.org/10.1109/TDSC.2025.3620308) | IEEE TDSC | — | 8 |
| Suqin Liao, Zaiyang Xie | [Unlearn Success or Failure Beliefs?: How Do Big Data Analytic Capabilities Affect the Incumbents’ Business Model Innovation in Deep Uncertainty](https://doi.org/10.1109/tem.2024.3457874) | IEEE Transactions on Engineering Management | — | 8 |
| Tapiwa Gundu | [Learn, Unlearn and Relearn: Adaptive Cybersecurity Culture Model](https://doi.org/10.34190/iccws.19.1.2177) | International Conference on Cyber Warfare and Security | — | 8 |
| Mumin Dayan et al. | [How much internationalization is innovation-worthy for SMEs? Roles of the degree of internationalization and organizational unlearning on the joint innovation capabilities-exploratory innovation relationship](https://doi.org/10.1016/j.jik.2024.100614) | Journal of Innovation & Knowledge | — | 8 |
| Tyler Lizzo, Larry Heck | [UNLEARN Efficient Removal of Knowledge in Large Language Models](https://doi.org/10.48550/arXiv.2408.04140) | NAACL | — | 8 |
| Weilin Lin et al. | [Unveiling and Mitigating Backdoor Vulnerabilities based on Unlearning Weight Changes and Backdoor Activeness](https://doi.org/10.48550/arXiv.2405.20291) | NeurIPS | [GitHub](https://github.com/bboylyg/RNP) | 8 |
| Universitas Indonesia et al. | [Right to be Forgotten as a Legal Protection for The Victims of Electronic Sexual Violence Cases](https://doi.org/10.54828/ijsls.2024v3n2.4) | The Indonesian Journal of Socio-Legal Studies | — | 8 |
| Jack Foster, Stefan Schoepf, A. Brintrup | [Loss-Free Machine Unlearning](https://doi.org/10.48550/arXiv.2402.19308) | Tiny Papers @ ICLR | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 8 |
| Jiahao Xu, Zikai Zhang, Rui Hu | [Identify Backdoored Model in Federated Learning via Individual Unlearning](https://doi.org/10.1109/WACV61041.2025.00773) | WACV | [GitHub](https://github.com/JiiahaoXU/MASA) | 8 |
| Chenhao Zhang et al. | [GENIU: A Restricted Data Access Unlearning for Imbalanced Data](https://doi.org/10.48550/arXiv.2406.07885) | arXiv | — | 8 |
| Zonglin Di et al. | [Label Smoothing Improves Machine Unlearning](https://doi.org/10.48550/arXiv.2406.07698) | arXiv | — | 8 |
| Ling Han et al. | [Towards Independence Criterion in Machine Unlearning of Features and Labels](https://doi.org/10.48550/arXiv.2403.08124) | arXiv | — | 8 |
| Yijing Lin et al. | [Blockchain-enabled Trustworthy Federated Unlearning](https://doi.org/10.48550/arXiv.2401.15917) | arXiv | [GitHub](https://github.com/xuperchain/xuperchain) | 8 |
| Quang H. Nguyen, Hoang Phan, Khoa D. Doan | [Unveiling Concept Attribution in Diffusion Models](https://doi.org/10.48550/arXiv.2412.02542) | arXiv | [GitHub](https://github.com/mail-research/CAD-attribution4diffusion) | 8 |
| Ningning Ding, Ermin Wei, Randall Berry | [Strategic Data Revocation in Federated Unlearning](https://doi.org/10.1109/infocom52122.2024.10621201) | arXiv | — | 8 |
| Jie Chen et al. | [Unveiling the Flaws: Exploring Imperfections in Synthetic Data and Mitigation Strategies for Large Language Models](https://doi.org/10.18653/v1/2024.findings-emnlp.873) | arXiv | — | 8 |
| Xinshuo Hu et al. | [Separate the Wheat from the Chaff: Model Deficiency Unlearning via Parameter-Efficient Module Operation](https://doi.org/10.1609/aaai.v38i16.29784) | AAAI | — | 7 |
| Michael Fore et al. | [Unlearning Climate Misinformation in Large Language Models](https://doi.org/10.48550/arXiv.2405.19563) | CLIMATENLP | [GitHub](https://github.com/mikeFore4/climateQA) | 7 |
| Dasol Choi et al. | [Towards Efficient Machine Unlearning with Data Augmentation: Guided Loss-Increasing (GLI) to Prevent the Catastrophic Model Utility Drop](https://doi.org/10.1109/cvprw63382.2024.00014) | CVPR Workshops | [GitHub](https://github.com/Dasol-Choi/Guided_Loss_Increasing) | 7 |
| Bozhong Tian et al. | [To Forget or Not? Towards Practical Knowledge Unlearning for Large Language Models](https://doi.org/10.18653/v1/2024.findings-emnlp.82) | EMNLP | [GitHub](https://github.com/jujingliuzy/Unlearning-LLM-papers) | 7 |
| Xiao Liu et al. | [BlockFUL: Enabling Unlearning in Blockchained Federated Learning](https://doi.org/10.1109/TIFS.2025.3583109) | IEEE T-IFS | — | 7 |
| Miao Xu | [Machine Unlearning: Challenges in Data Quality and Access](https://doi.org/10.24963/ijcai.2024/987) | IJCAI | — | 7 |
| Haoyu Tang et al. | [Learn while Unlearn: An Iterative Unlearning Framework for Generative Language Models](https://doi.org/10.1109/ICDM65498.2025.00082) | Industrial Conference on Data Mining | [GitHub](https://github.com/himalalps/ICU) | 7 |
| Muhammad Ameen et al. | [Addressing unreliable local models in federated learning through unlearning](https://doi.org/10.1016/j.neunet.2024.106688) | Neural Networks | — | 7 |
| Reihaneh Torkzadehmahani et al. | [Improved Localized Machine Unlearning Through the Lens of Memorization](https://doi.org/10.48550/arXiv.2412.02432) | TMLR | [GitHub](https://github.com/reihaneh-torkzadehmahani/DEL-Unlearning) | 7 |
| Reza Nasirigerdeh et al. | [Machine Unlearning for Medical Imaging](https://doi.org/10.48550/arXiv.2407.07539) | arXiv | [GitHub](https://github.com/threadedrabbit/machine-unlearning-arxiv-daily) | 7 |
| Cheng-Long Wang et al. | [Towards Lifecycle Unlearning Commitment Management: Measuring Sample-level Approximate Unlearning Completeness](https://arxiv.org/abs/2403.12830) | arXiv | — | 7 |
| Hongxiang Zhang, Yifeng He, Hao Chen | [SteerDiff: Steering towards Safe Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2410.02710) | arXiv | — | 7 |
| X. You et al. | [RRL: Recommendation Reverse Learning](https://doi.org/10.1609/aaai.v38i8.28782) | AAAI | — | 6 |
| Shota Takashiro et al. | [Answer When Needed, Forget When Not: Language Models Pretend to Forget via In-Context Knowledge Unlearning](https://doi.org/10.48550/arXiv.2410.00382) | ACL | — | 6 |
| M. Rusanovsky et al. | [Memories of Forgotten Concepts](https://doi.org/10.1109/CVPR52734.2025.00282) | CVPR | [GitHub](https://github.com/matanr/Memories_of_Forgotten_Concepts) | 6 |
| Houzhe Wang et al. | [Goldfish: An Efficient Federated Unlearning Framework](https://doi.org/10.1109/dsn58291.2024.00035) | DSN | [GitHub](https://github.com/xiao-jian-zi/MU-Goldfish-An-Efficient-Federated-Unlearning-Framework) | 6 |
| XiaoHua Feng et al. | [Fine-grained Pluggable Gradient Ascent for Knowledge Unlearning in Language Models](https://doi.org/10.18653/v1/2024.emnlp-main.566) | EMNLP | — | 6 |
| Xisen Jin, Xiang Ren | [Demystifying Language Model Forgetting with Low-rank Example Associations](https://arxiv.org/abs/2406.14026) | ES-FoMo III | [GitHub](https://github.com/AuCson/low-rank-forgetting) | 6 |
| Xavier F. Cadet et al. | [Deep Unlearn: Benchmarking Machine Unlearning for Image Classification](https://doi.org/10.1109/EuroSP63326.2025.00058) | European Symposium on Security and Privacy | [GitHub](https://github.com/xcadet/deepunlearn) | 6 |
| Chaohao Fu, Weijia Jia, Na Ruan | [Client-Free Federated Unlearning via Training Reconstruction with Anchor Subspace Calibration](https://doi.org/10.1109/icassp48485.2024.10447085) | ICASSP | — | 6 |
| Arinbjörn Kolbeinsson et al. | [Composable Interventions for Language Models](https://doi.org/10.48550/arXiv.2407.06483) | ICLR | [GitHub](https://github.com/hartvigsen-group/composable-interventions) | 6 |
| Zhenguo Ma et al. | [Hier-FUN: Hierarchical Federated Learning and Unlearning in Heterogeneous Edge Computing](https://doi.org/10.1109/jiot.2024.3502666) | IEEE IoT-J | — | 6 |
| Chenhan Zhang et al. | [Forgetting and Remembering Are Both You Need: Balanced Graph Structure Unlearning](https://doi.org/10.1109/tifs.2024.3422799) | IEEE T-IFS | — | 6 |
| Ziyao Liu et al. | [Guaranteeing Data Privacy in Federated Unlearning With Dynamic User Participation](https://doi.org/10.1109/tdsc.2024.3476533) | IEEE TDSC | — | 6 |
| Hong kyu Lee et al. | [Contrastive Unlearning: A Contrastive Approach to Machine Unlearning](https://doi.org/10.24963/ijcai.2024/830) | IJCAI | [GitHub](https://github.com/Hongkyu-Lee/Contrastive-Unlearning) | 6 |
| Zuobin Xiong, Wei Li, Zhipeng Cai | [Appro-Fun: Approximate Machine Unlearning in Federated Setting](https://doi.org/10.1109/ICCCN61486.2024.10637564) | International Conference on Computer Communications and Networks | — | 6 |
| Àlex Pujol Vidal et al. | [Verifying Machine Unlearning with Explainable AI](https://doi.org/10.48550/arXiv.2411.13332) | International Conference on Pattern Recognition | — | 6 |
| Akash Dhasade et al. | [QuickDrop: Efficient Federated Unlearning via Synthetic Data Generation](https://doi.org/10.1145/3652892.3700764) | International Middleware Conference | [GitHub](https://github.com/fardeenfarhat/quickdrop-federated-unlearning) | 6 |
| Emmie Hine et al. | [Supporting Trustworthy AI Through Machine Unlearning](https://doi.org/10.1007/s11948-024-00500-5) | Science and Engineering Ethics | — | 6 |
| Andrea Schioppa, E. Hoogeboom, J. Heek | [Model Integrity when Unlearning with T2I Diffusion Models](https://doi.org/10.48550/arXiv.2411.02068) | arXiv | — | 6 |
| Vikram S Chundawat et al. | [ConDa: Fast Federated Unlearning with Contribution Dampening](https://doi.org/10.48550/arXiv.2410.04144) | arXiv | [GitHub](https://github.com/if-loops/if-loops) | 6 |
| Xiaohua Feng et al. | [Controllable Unlearning for Image-to-Image Generative Models via ε-Constrained Optimization](https://doi.org/10.48550/arXiv.2408.01689) | arXiv | — | 6 |
| Binhao Ma et al. | [Releasing Malevolence from Benevolence: The Menace of Benign Data on Machine Unlearning](https://doi.org/10.48550/arXiv.2407.05112) | arXiv | — | 6 |
| David Zagardo | [A More Practical Approach to Machine Unlearning](https://doi.org/10.48550/arXiv.2406.09391) | arXiv | — | 6 |
| A. Sha, B. Nunes, Armin Haller | ["Forgetting" in Machine Learning and Beyond: A Survey](https://doi.org/10.48550/arXiv.2405.20620) | arXiv | — | 6 |
| Subhodip Panda, Shashwat Sourav, Prathosh A.P. | [Partially Blinded Unlearning: Class Unlearning for Deep Networks a Bayesian Perspective](https://doi.org/10.48550/arXiv.2403.16246) | arXiv | — | 6 |
| Eleni Triantaﬁllou, P. Kairouz | [Evaluation for the NeurIPS Machine Unlearning Competition](https://www.semanticscholar.org/paper/f71ea29a845839efbcb735b3c89b71fbc1887a02) | arXiv | [GitHub](https://github.com/tinee29/ETH-Deep-Learning) | 6 |
| Cheng-Long Wang et al. | [Has Approximate Machine Unlearning been evaluated properly? From Auditing to Side Effects](https://doi.org/10.48550/arXiv.2403.12830) | arXiv | — | 6 |
| Alessio Mora et al. | [FedQUIT: On-Device Federated Unlearning via a Quasi-Competent Virtual Teacher](https://doi.org/10.48550/arXiv.2408.07587) | arXiv | [GitHub](https://github.com/alessiomora/FedQUIT) | 6 |
| Kairan Zhao, Peter Triantafillou | [Scalability of memorization-based machine unlearning](https://doi.org/10.48550/arXiv.2410.16516) | arXiv | [GitHub](https://github.com/kairanzhao/RUM) | 6 |
| Yue Zhao, Congyi Li, Kai Chen | [UMA: Facilitating Backdoor Scanning via Unlearning-Based Model Ablation](https://doi.org/10.1609/aaai.v38i19.30183) | AAAI | — | 5 |
| Jie Ren et al. | [Six-CD: Benchmarking Concept Removals for Text-to-image Diffusion Models](https://doi.org/10.1109/CVPR52734.2025.02679) | CVPR | [GitHub](https://github.com/deep-floyd/if) | 5 |
| Guofeng Li et al. | [Federated Unlearning in the Internet of Vehicles](https://doi.org/10.1109/DSN-S60304.2024.00034) | DSN-S | — | 5 |
| Wei-gang Zhu et al. | [Federated Unlearning with Multiple Client Partitions](https://doi.org/10.1109/ICC51166.2024.10622238) | ICC | — | 5 |
| Wathsara Daluwatta et al. | [DT-FU: Digital Twin-Driven Federated Unlearning for Resilient Vehicular Networks in the 6G Era](https://doi.org/10.1109/mcom.001.2400229) | IEEE Communications Magazine | — | 5 |
| Lei Kang et al. | [Machine Unlearning for Document Classification](https://doi.org/10.48550/arXiv.2404.19031) | IEEE International Conference on Document Analysis and Recognition | [GitHub](https://github.com/leitro/MachineUnlearning-DocClassification) | 5 |
| Yijing Lin et al. | [Decentralized Unlearning for Trustworthy AI-Generated Content (AIGC) Services](https://doi.org/10.1109/mnet.2024.3439411) | IEEE Network | — | 5 |
| Weiqi Wang et al. | [SCU: An Efficient Machine Unlearning Scheme for Deep Learning Enabled Semantic Communications](https://doi.org/10.1109/tifs.2024.3516576) | IEEE T-IFS | [GitHub](https://github.com/wwq5-code/SCU) | 5 |
| Zhiwei Zuo et al. | [Machine Unlearning Through Fine-Grained Model Parameters Perturbation](https://doi.org/10.1109/TKDE.2025.3528551) | IEEE TKDE | — | 5 |
| Wathsara Daluwatta et al. | [UaaS-SFL: Unlearning as a Service for Safeguarding Federated Learning](https://doi.org/10.1109/tnsm.2024.3520109) | IEEE Transactions on Network and Service Management | — | 5 |
| Samuele Poppi et al. | [Unlearning Vision Transformers Without Retaining Data via Low-Rank Decompositions](https://doi.org/10.1007/978-3-031-78122-3_10) | International Conference on Pattern Recognition | — | 5 |
| Paul Youssef et al. | [How to Make LLMs Forget: On Reversing In-Context Knowledge Edits](https://doi.org/10.18653/v1/2025.naacl-long.630) | NAACL | [GitHub](https://github.com/paulyoussef/reed) | 5 |
| Giulia Champion, Mia Strand | [“Other(ed)” Ocean Knowledges: Unlearning Integration in Ocean Governance for Recognitional Justice](https://doi.org/10.17645/oas.8875) | Ocean and Society | — | 5 |
| Yuyao Zhong | [Federated unlearning for medical image analysis](https://doi.org/10.1117/12.3030004) | Other Conferences | — | 5 |
| Zhongcheng Wei et al. | [CIU-L: A class-incremental learning and machine unlearning passive sensing system for human identification](https://doi.org/10.1016/j.pmcj.2024.101947) | Pervasive and Mobile Computing | — | 5 |
| Minseok Choi et al. | [Breaking Chains: Unraveling the Links in Multi-Hop Knowledge Unlearning](https://doi.org/10.48550/arXiv.2410.13274) | arXiv | — | 5 |
| Nhung Bui et al. | [On Newton's Method to Unlearn Neural Networks](https://doi.org/10.48550/arXiv.2406.14507) | arXiv | [HF](https://huggingface.co/meta-llama/Llama-2-7b-hf) | 5 |
| N. Sepahvand et al. | [Data Selection for Transfer Unlearning](https://doi.org/10.48550/arXiv.2405.10425) | arXiv | — | 5 |
| T. Surve, Romila Pradhan | [Example-based Explanations for Random Forests using Machine Unlearning](https://doi.org/10.48550/arXiv.2402.05007) | arXiv | — | 5 |
| Martín Bertrán et al. | [Reconstruction Attacks on Machine Unlearning: Simple Models are Vulnerable](https://doi.org/10.52202/079017-3334) | arXiv | — | 5 |
| Chaochao Chen et al. | [CURE4Rec: A Benchmark for Recommendation Unlearning with Deeper Influence](https://doi.org/10.52202/079017-3144) | arXiv | [GitHub](https://github.com/xiye7lai/CURE4Rec) | 5 |
| Yi Li et al. | [Community-Centric Graph Unlearning](https://doi.org/10.48550/arXiv.2408.09705) | AAAI | [GitHub](https://github.com/liiiyi/CCGU) | 4 |
| Chenhao Zhang et al. | [Toward Efficient Data-Free Unlearning](https://doi.org/10.48550/arXiv.2412.13790) | AAAI | [GitHub](https://github.com/ChildEden/ISPF) | 4 |
| Shahnewaz Karim Sakib, Mengjun Xie | [Machine Unlearning in Digital Healthcare: Addressing Technical and Ethical Challenges](https://doi.org/10.1609/aaaiss.v4i1.31809) | AAAI Symposium Series | — | 4 |
| Yang Zhao et al. | [Deciphering the Impact of Pretraining Data on Large Language Models through Machine Unlearning](https://doi.org/10.18653/v1/2024.findings-acl.559) | ACL | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 4 |
| Akshat Gupta, Anurag Rao, Gopala Anumanchipalli | [Model Editing at Scale leads to Gradual and Catastrophic Forgetting](https://doi.org/10.18653/v1/2024.findings-acl.902) | ACL | [GitHub](https://github.com/scalable-model-editing/unified-model-editing) | 4 |
| Shen Lin et al. | [GDR-GMA: Machine Unlearning via Direction-Rectified and Magnitude-Adjusted Gradients](https://doi.org/10.1145/3664647.3680775) | ACM MM | — | 4 |
| Zhenwu Xu et al. | [Empowering Data Owners: An Efficient and Verifiable Scheme for Secure Data Deletion](https://doi.org/10.1016/j.cose.2024.103978) | Computers & Security | — | 4 |
| V. Perifanis et al. | [SFTC: Machine Unlearning via Selective Fine-tuning and Targeted Confusion](https://doi.org/10.1145/3655693.3655697) | European Interdisciplinary Cybersecurity Conference | [GitHub](https://github.com/vperifan/SFTC-Unlearn) | 4 |
| Zhiwei Zuo et al. | [ECIL-MU: Embedding Based Class Incremental Learning and Machine Unlearning](https://doi.org/10.1109/icassp48485.2024.10446273) | ICASSP | — | 4 |
| Yue Cui, Man Hon Cheung | [The Price of Forgetting: Data Redemption Mechanism Design for Machine Unlearning](https://doi.org/10.1109/ICC51166.2024.10622287) | ICC | — | 4 |
| Stanley Wei et al. | [Provable unlearning in topic modeling and downstream tasks](https://doi.org/10.48550/arXiv.2411.12600) | ICLR | — | 4 |
| Zhiqiang Xie et al. | [Adaptive Clipping and Distillation Enabled Federated Unlearning](https://doi.org/10.1109/icws62655.2024.00094) | ICWS | — | 4 |
| Youngsik Yoon et al. | [Few-shot Unlearning](https://doi.org/10.1109/SP54263.2024.00249) | IEEE S&P | [GitHub](https://github.com/ml-postech/Few-shot-Unlearning) | 4 |
| Wenhan Chang et al. | [Zero-shot Class Unlearning via Layer-wise Relevance Analysis and Neuronal Path Perturbation](https://doi.org/10.48550/arXiv.2410.23693) | IEEE TDSC | — | 4 |
| Jiaxing Miao et al. | [Graph Memory Learning: Imitating Lifelong Remembering and Forgetting of Brain Networks](https://doi.org/10.1109/TPAMI.2025.3599898) | IEEE TPAMI | — | 4 |
| Wangkun Xu, Fei Teng | [Task-Aware Machine Unlearning and Its Application in Load Forecasting](https://doi.org/10.1109/tpwrs.2024.3376828) | IEEE Transactions on Power Systems | [GitHub](https://github.com/xuwkk/task_aware_machine_unlearning) | 4 |
| Amartya Hatua et al. | [Machine Unlearning using Forgetting Neural Networks](https://doi.org/10.48550/arXiv.2410.22374) | International Conference on Agents and Artificial Intelligence | — | 4 |
| Wenqin Li et al. | [Enhancing Privacy Protection for Online Learning Resource Recommendation with Machine Unlearning](https://doi.org/10.1109/cscwd61410.2024.10580315) | International Conference on Computer Supported Cooperative Work in Design | — | 4 |
| Layan Jaman, Reem Alsharabi, Passent Elkafrawy | [Machine Unlearning: An Overview of the Paradigm Shift in the Evolution of AI](https://doi.org/10.1109/lt60077.2024.10469232) | L&amp;amp;T | — | 4 |
| Kongyang Chen, Zixin Wang, Bing Mi | [Private Data Protection with Machine Unlearning in Contrastive Learning Networks](https://doi.org/10.3390/math12244001) | Mathematics | — | 4 |
| Chen Jiang, Zobo Ongono Emilienne Charlotte, Yana Yuan | [Organizational Unlearning: A Bibliometric Study and Visualization Analysis Via CiteSpace](https://doi.org/10.1177/21582440241251648) | SAGE Open | — | 4 |
| Y. Kanza, Balachander Krishnamurthy, Divesh Srivastava | [A Geospatial Perspective on Data Ownership, the Right to be Forgotten, Copyrights, and Plagiarism in Generative AI](https://doi.org/10.1145/3678717.3691269) | SIGSPATIAL/GIS | — | 4 |
| Thomas De Min et al. | [Unlearning Personal Data from a Single Image](https://arxiv.org/abs/2407.12069) | TMLR | [GitHub](https://github.com/tdemin16/one-shui) | 4 |
| Aviraj Newatia, Michael Cooper, R. Krishnan | [Unlearning Tabular Data Without a “Forget Set”](https://www.semanticscholar.org/paper/9b4a5a920a7b784ab9fb295236feda970a1d9286) | TRL @ NeurIPS Poster | — | 4 |
| Kerem Zaman, Leshem Choshen, Shashank Srivastava | [Fuse to Forget: Bias Reduction and Selective Memorization through Model Fusion](https://doi.org/10.18653/v1/2024.emnlp-main.1045) | arXiv | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 4 |
| Jose Miguel Lara Rangel et al. | [Learning to Forget using Hypernetworks](https://doi.org/10.48550/arXiv.2412.00761) | arXiv | [GitHub](https://github.com/if-loops/if-loops) | 4 |
| Eric Zhang, Leshem Choshen, Jacob Andreas | [Unforgettable Generalization in Language Models](https://doi.org/10.48550/arXiv.2409.02228) | arXiv | — | 4 |
| Shiqi Liu, Yihua Tan | [Unlearning Concepts from Text-to-Video Diffusion Models](https://doi.org/10.48550/arXiv.2407.14209) | arXiv | — | 4 |
| Ziheng Chen et al. | [Debiasing Machine Unlearning with Counterfactual Examples](https://doi.org/10.48550/arXiv.2404.15760) | arXiv | — | 4 |
| Changchang Sun et al. | [Forget Vectors at Play: Universal Input Perturbations Driving Machine Unlearning in Image Classification](https://doi.org/10.48550/arXiv.2412.16780) | arXiv | [GitHub](https://github.com/Changchangsun/Forget-Vector) | 4 |
| Rongzhe Wei et al. | [Underestimated Privacy Risks for Minority Populations in Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2412.08559) | arXiv | — | 4 |
| Teodora Baluta et al. | [Unlearning in- vs. out-of-distribution data in LLMs under gradient-based method](https://doi.org/10.48550/arXiv.2411.04388) | arXiv | — | 4 |
| Xuhan Zuo et al. | [Large Language Model Federated Learning with Blockchain and Unlearning for Cross-Organizational Collaboration](https://doi.org/10.48550/arXiv.2412.13551) | arXiv | — | 4 |
| Kuanrong Liu et al. | [Efficient Backdoor Defense in Multimodal Contrastive Learning: A Token-Level Unlearning Method for Mitigating Threats](https://doi.org/10.48550/arXiv.2409.19526) | arXiv | — | 4 |
| A. Veldanda et al. | [LLM Surgery: Efficient Knowledge Unlearning and Editing in Large Language Models](https://doi.org/10.48550/arXiv.2409.13054) | arXiv | [GitHub](https://github.com/akshajkumarv/llm_surgery_code) | 4 |
| Xiao Liu et al. | [Decentralized Federated Unlearning on Blockchain](https://doi.org/10.48550/arXiv.2402.16294) | arXiv | — | 4 |
| Romit Chatterjee et al. | [A Unified Framework for Continual Learning and Unlearning](https://arxiv.org/abs/2408.11374) | arXiv | [GitHub](https://github.com/respailab/CLMUL) | 4 |
| Shashwat Goel et al. | [Corrective Machine Unlearning](https://doi.org/10.48550/arxiv.2402.14015) | arXiv | [GitHub](https://github.com/drimpossible/corrective-unlearning-bench) | 4 |
| Lefeng Zhang et al. | [The Price of Unlearning: Identifying Unlearning Risk in Edge Computing](https://doi.org/10.1145/3662184) | ACM Trans. Multim. Comput. Commun. Appl | — | 3 |
| Yongjing Hao et al. | [A General Strategy Graph Collaborative Filtering for Recommendation Unlearning](https://doi.org/10.1145/3627673.3679637) | CIKM | [GitHub](https://github.com/YongjingHao/GSGCF-RU) | 3 |
| Zirui Ling, Chaoyu Zhang, Zijie Pan | [Multi-step and Iterative Backdoor Injection in Federated Machine Unlearning](https://doi.org/10.1109/CSRSWTC64338.2024.10811514) | CSRSWTC | — | 3 |
| Guofeng Li et al. | [Federated Unlearning in the Internet of Vehicles](https://doi.org/10.1109/dsn-s60304.2024.00034) | DSN-S | — | 3 |
| Leon Wichert, Sandipan Sikdar | [Rethinking Evaluation Methods for Machine Unlearning](https://doi.org/10.18653/v1/2024.findings-emnlp.271) | EMNLP | [GitHub](https://github.com/Kartoffelpuffa/Rethinking-MU-Evaluation) | 3 |
| Zulfiqar Ali et al. | [Evaluating Machine Unlearning: Applications, Approaches, and Accuracy](https://doi.org/10.1002/eng2.13081) | Engineering Reports | — | 3 |
| Guitao Chen et al. | [WPN: An Unlearning Method Based on N-pair Contrastive Learning in Language Models](https://doi.org/10.48550/arXiv.2408.09459) | European Conference on Artificial Intelligence | [GitHub](https://github.com/baojunshan/nlp-fluency) | 3 |
| Emircan Gündoğdu, Altay Unal, Gözde Ünal | [A Study Regarding Machine Unlearning on Facial Attribute Data](https://doi.org/10.1109/fg59268.2024.10581972) | FG | [GitHub](https://github.com/ituvisionlab/face-attribute-unlearning) | 3 |
| Yixiong Wang et al. | [Learning to Unlearn in Federated Learning](https://doi.org/10.1109/FLTA63145.2024.10840121) | FLTA | — | 3 |
| Chaoyi Wang, Zuobin Ying, Zijie Pan | [Machine unlearning in brain-inspired neural network paradigms](https://doi.org/10.3389/fnbot.2024.1361577) | Frontiers in Neurorobotics | — | 3 |
| Hanlin Gu et al. | [Towards Privacy-Guaranteed Label Unlearning in Vertical Federated Learning: Few-Shot Forgetting without Disclosure](https://arxiv.org/abs/2410.10922) | ICLR Poster | [GitHub](https://github.com/bryanhx/Towards-Privacy-Guaranteed-Label-Unlearning-in-Vertical-Federated-Learning) | 3 |
| Varshita Kolipaka et al. | [A Cognac Shot To Forget Bad Memories: Corrective Unlearning for Graph Neural Networks](https://arxiv.org/abs/2412.00789) | ICML | [GitHub](https://github.com/cognac-gnn-unlearning/corrective-unlearning-for-gnns) | 3 |
| Emircan Gündogdu, Altay Unal, Gozde Unal | [A Study Regarding Machine Unlearning on Facial Attribute Data](https://doi.org/10.1109/FG59268.2024.10581972) | IEEE International Conference on Automatic Face & Gesture Recognition | [GitHub](https://github.com/ituvisionlab/face-attribute-unlearning) | 3 |
| Yi Tang et al. | [Unlearning from Weakly Supervised Learning](https://doi.org/10.24963/ijcai.2024/553) | IJCAI | — | 3 |
| Bashirat Bukola Atata | [Artificial Intelligence and the Right to be Forgotten](https://doi.org/10.55248/gengpi.5.0824.2310) | International Journal of Research Publication and Reviews | — | 3 |
| Samuele Maccioni, Cristiano Ghiringhelli | [Digital transformation through organisational unlearning: insights from practitioners’ voice](https://doi.org/10.1080/14778238.2024.2383371) | Knowledge Management Research & Practice | — | 3 |
| Enrico Ventura et al. | [Unlearning regularization for Boltzmann machines](https://doi.org/10.1088/2632-2153/ad5a5f) | Machine Learning Science and Technology | — | 3 |
| Ruikai Yang et al. | [MUSO: achieving exact machine unlearning in over-parameterized regimes](https://doi.org/10.1007/s10994-025-06806-0) | Machine-mediated learning | [GitHub](https://github.com/Yruikk/MUSO) | 3 |
| Chen Gong et al. | [TrajDeleter: Enabling Trajectory Forgetting in Offline Reinforcement Learning Agents](https://doi.org/10.48550/arXiv.2404.12530) | NDSS | [GitHub](https://github.com/2019ChenGong/TrajDeleter) | 3 |
| Ewen Callaway | [‘Set it and forget it’: automated lab uses AI and robotics to improve proteins](https://doi.org/10.1038/d41586-024-00093-w) | Nature | — | 3 |
| Yusuke Kuwana et al. | [Black-Box Forgetting](https://doi.org/10.48550/arXiv.2411.00409) | NeurIPS | [GitHub](https://github.com/yusukekwn/Black-Box-Forgetting) | 3 |
| Peiran Dong et al. | [Towards Safe Concept Transfer of Multi-Modal Diffusion via Causal Representation Editing](https://doi.org/10.52202/079017-0404) | NeurIPS | — | 3 |
| Shiyu Chang et al. | [Reversing the Forget-Retain Objectives: An Efficient LLM Unlearning Framework from Logit Difference](https://doi.org/10.52202/079017-0400) | NeurIPS | — | 3 |
| Yiwen Tu, Pingbang Hu, Jiaqi W. Ma | [A Reliable Cryptographic Framework for Empirical Machine Unlearning Evaluation](https://arxiv.org/abs/2404.11577) | NeurIPS poster | — | 3 |
| P. Guo et al. | [Robust Knowledge Unlearning via Mechanistic Localizations](https://www.semanticscholar.org/paper/359d4db8585317f0f1eafc873220e2b9d0c62c34) | NextGenAISafety Poster | — | 3 |
| Zhuo Ma et al. | [Mitigate noisy data for smart IoT via GAN based machine unlearning](https://doi.org/10.1007/s11432-022-3671-9) | Science China Information Sciences | — | 3 |
| Meng Ding et al. | [Understanding Fine-tuning in Approximate Unlearning: A Theoretical Perspective](https://arxiv.org/abs/2410.03833) | TMLR | — | 3 |
| Qi Guo et al. | [Forgetting Through Transforming: Enabling Federated Unlearning via Class-Aware Representation Transformation](https://doi.org/10.48550/arXiv.2410.06848) | arXiv | — | 3 |
| Tao Wu et al. | [GraphMU: Repairing Robustness of Graph Neural Networks via Machine Unlearning](https://doi.org/10.48550/arXiv.2406.13499) | arXiv | — | 3 |
| Wei Qian et al. | [Exploring Fairness in Educational Data Mining in the Context of the Right to be Forgotten](https://doi.org/10.48550/arXiv.2405.16798) | arXiv | — | 3 |
| Ling Han et al. | [Unlearning Information Bottleneck: Machine Unlearning of Systematic Patterns and Biases](https://doi.org/10.48550/arXiv.2405.14020) | arXiv | [GitHub](https://github.com/brianhan-coder/research) | 3 |
| Xinbao Qiao et al. | [Efficient Online Unlearning via Hessian-Free Recollection of Individual Data Statistics](https://doi.org/10.48550/arXiv.2404.01712) | arXiv | — | 3 |
| Tingxu Han et al. | [Continuous Concepts Removal in Text-to-image Diffusion Models](https://doi.org/10.48550/arXiv.2412.00580) | arXiv | [GitHub](https://github.com/wssun/CCRT) | 3 |
| Wanzhu Jiang et al. | [Moderating the Generalization of Score-based Generative Model](https://doi.org/10.48550/arXiv.2412.07229) | arXiv | [GitHub](https://github.com/yunfengdiao/Moderated-Score-based-Generative-Model) | 3 |
| Varshita Kolipaka et al. | [A Cognac shot to forget bad memories: Corrective Unlearning in GNNs](https://doi.org/10.48550/arXiv.2412.00789) | arXiv | [GitHub](https://github.com/viciousAegis/CorrectiveUnlearningForGNNs) | 3 |
| Xin Chen et al. | [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://doi.org/10.52202/079017-1158) | arXiv | — | 3 |
| Jing Huang, Diyi Yang, Christopher Potts | [Demystifying Verbatim Memorization in Large Language Models](https://doi.org/10.18653/v1/2024.emnlp-main.598) | arXiv | [GitHub](https://github.com/explanare/verbatim-memorization) | 3 |
| Syed Irfan Ali Meerza, Amir Sadovnik, Jian Liu | [ConFUSE: Confusion-based Federated Unlearning with Salience Exploration](https://doi.org/10.1109/isvlsi61997.2024.00083) | arXiv | — | 3 |
| Alessio Mora, Luca Dominici, Paolo Bellavista | [FedUNRAN: On-device Federated Unlearning via Random Labels](https://doi.org/10.1109/bigdata62323.2024.10825563) | BigData Congress [Services Society] | [GitHub](https://github.com/alessiomora/FedUNRAN) | 2 |
| Omkar Dige et al. | [Can Machine Unlearning Reduce Social Bias in Language Models?](https://doi.org/10.18653/v1/2024.emnlp-industry.71) | EMNLP | [GitHub](https://github.com/VectorInstitute/bias-mitigation-unlearning) | 2 |
| Trishna Chakraborty et al. | [Can Textual Unlearning Solve Cross-Modality Safety Alignment?](https://doi.org/10.18653/v1/2024.findings-emnlp.574) | EMNLP | — | 2 |
| Yujian Liu et al. | [Revisiting Who’s Harry Potter: Towards Targeted Unlearning from a Causal Intervention Perspective](https://doi.org/10.18653/v1/2024.emnlp-main.495) | EMNLP | — | 2 |
| Xiangman Li, Xiaodong Wu, Jianbing Ni | [Accelerating Secure and Verifiable Data Deletion in Cloud Storage via SGX and Blockchain](https://doi.org/10.1109/globecom52923.2024.10901101) | Global Communications Conference | — | 2 |
| Yue Cui, Man Hon Cheung | [The Price of Forgetting: Data Redemption Mechanism Design for Machine Unlearning](https://doi.org/10.1109/icc51166.2024.10622287) | ICC | — | 2 |
| Weipeng Zhu et al. | [Federated Unlearning with Multiple Client Partitions](https://doi.org/10.1109/icc51166.2024.10622238) | ICC | — | 2 |
| Zuobin Xiong, Wei Li, Zhipeng Cai | [Appro-Fun: Approximate Machine Unlearning in Federated Setting](https://doi.org/10.1109/icccn61486.2024.10637564) | ICCCN | — | 2 |
| Shurong Wang et al. | [DynFrs: An Efficient Framework for Machine Unlearning in Random Forest](https://doi.org/10.48550/arXiv.2410.01588) | ICLR | [GitHub](https://github.com/shurongwang/DynFrs) | 2 |
| Kongyang Chen et al. | [Private Data Protection With Machine Unlearning for Next-Generation Networks](https://doi.org/10.1109/ojcoms.2024.3518503) | IEEE Open Journal of the Communications Society | — | 2 |
| Xiao Liu et al. | [Parallel Unlearning in Inherited Model Networks](https://doi.org/10.1109/TIFS.2025.3627869) | IEEE T-IFS | [GitHub](https://github.com/MJLee00/Parallel-Unlearning-in-Inherited-Model-Networks) | 2 |
| Heng Xu et al. | [Don't Forget Too Much: Towards Machine Unlearning on Feature Level](https://doi.org/10.1109/tdsc.2024.3432169) | IEEE TDSC | — | 2 |
| Xiaoyu Zhang et al. | [DuplexGuard: Safeguarding Deletion Right in Machine Unlearning via Duplex Watermarking](https://doi.org/10.1109/tdsc.2024.3456811) | IEEE TDSC | — | 2 |
| Jingrui Hou, Axel Finke, Georgina Cosma | [Neural Machine Unranking](https://doi.org/10.48550/arXiv.2408.05330) | IEEE TNNLS | — | 2 |
| Chenghao Shao et al. | [Machine Unlearning for Seizure Prediction](https://doi.org/10.1109/tcds.2024.3395663) | IEEE Transactions on Cognitive and Developmental Systems | — | 2 |
| A. Seetha et al. | [DiEvD-SF: Disruptive Event Detection Using Continual Machine Learning With Selective Forgetting](https://doi.org/10.1109/TCSS.2024.3364544) | IEEE Transactions on Computational Social Systems | — | 2 |
| Andrea D'Angelo et al. | [How to Make Reproducible Research in Machine Unlearning with ERASURE](https://doi.org/10.24963/ijcai.2024/1255) | IJCAI | [GitHub](https://github.com/aiim-research/ERASURE) | 2 |
| Wenhan Wu et al. | [Zero-shot Federated Unlearning via Transforming from Data-Dependent to Personalized Model-Centric](https://doi.org/10.24963/ijcai.2024/733) | IJCAI | — | 2 |
| Yuyang Xue et al. | [Erase to Enhance: Data-Efficient Machine Unlearning in MRI Reconstruction](https://doi.org/10.48550/arXiv.2405.15517) | International Conference on Medical Imaging with Deep Learning | [GitHub](https://github.com/yuyangxueed/reconunlearning) | 2 |
| Liou Tang, James Joshi | [Towards Privacy-Preserving and Secure Machine Unlearning: Taxonomy, Challenges and Research Directions](https://doi.org/10.1109/TPS-ISA62245.2024.00040) | International Conference on Trust, Privacy and Security in Intelligent Systems and Applications | — | 2 |
| Sheng Bi et al. | [Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://doi.org/10.52202/079017-1116) | NeurIPS | — | 2 |
| Ziang Chen et al. | [Langevin Unlearning: A New Perspective of Noisy Gradient Descent for Machine Unlearning](https://doi.org/10.52202/079017-2530) | NeurIPS spotlight | — | 2 |
| Xinwen Cheng et al. | [Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://doi.org/10.52202/079017-0831) | NeurIPS spotlight | [GitHub](https://github.com/K1nght/Unified-Unlearning-w-Remain-Geometry) | 2 |
| Changsong Yang, Yueling Liu, Yong Ding | [Fine-grained data deletion supporting dynamic data insertion for cloud storage](https://doi.org/10.1007/s12083-024-01818-4) | Peer-to-Peer Networking and Applications | — | 2 |
| Scott Casleton | [Privacy and Assurance: On the Right to Be Forgotten](https://doi.org/10.16995/pp.15215) | Political Philosophy | — | 2 |
| Keivan Rezaei et al. | [RESTOR: Knowledge Recovery in Machine Unlearning](https://arxiv.org/abs/2411.00204) | TMLR | [GitHub](https://github.com/k1rezaei/restor) | 2 |
| Shivank Garg, Manyana Tiwari | [Unmasking the Veil: An Investigation into Concept Ablation for Privacy and Copyright Protection in Images](https://doi.org/10.48550/arXiv.2406.12592) | TMLR | [GitHub](https://github.com/taited/clip-score) | 2 |
| Yinghua Hua, Hui Xia, Shuo Xu | [Federated Unlearning for Samples Based on Adaptive Gradient Ascent of Angles](https://doi.org/10.1109/TrustCom63139.2024.00125) | TrustCom | — | 2 |
| D.M. Byelov, M. V. Bіelova, O. T. Gornylo | [A person’s right to be forgotten](https://doi.org/10.24144/2307-3322.2024.81.2.9) | Uzhhorod National University Herald Series Law | — | 2 |
| Sebastian Schelter, Stefan Grafberger, Maarten de Rijke | [Snarcase - Regain Control over Your Predictions with Low-Latency Machine Unlearning](https://doi.org/10.14778/3685800.3685853) | VLDB Endowment | — | 2 |
| A. Cooper et al. | [Machine Unlearning Doesn't Do What You Think: Lessons for Generative AI Policy and Research](https://arxiv.org/abs/2412.06966) | arXiv | — | 2 |
| Yuncong Yang et al. | [From Machine Learning to Machine Unlearning: Complying with GDPR's Right to be Forgotten while Maintaining Business Value of Predictive Models](https://doi.org/10.48550/arXiv.2411.17126) | arXiv | — | 2 |
| Heng Xu, Tianqing Zhu, Wanlei Zhou | [Evaluating of Machine Unlearning: Robustness Verification Without Prior Modifications](https://doi.org/10.48550/arXiv.2410.10120) | arXiv | — | 2 |
| Zhangjie Xia, ChiHua Wang, Guang Cheng | [Data Deletion for Linear Regression with Noisy SGD](https://doi.org/10.48550/arXiv.2410.09311) | arXiv | — | 2 |
| Xinchi Qiu et al. | [How Data Inter-connectivity Shapes LLMs Unlearning: A Structural Unlearning Perspective](https://arxiv.org/abs/2406.16810) | arXiv | [HF](https://huggingface.co/datasets/xinchiqiu/PISTOL) | 2 |
| Heng Xu et al. | [Towards Efficient Target-Level Machine Unlearning Based on Essential Graph](https://doi.org/10.48550/arXiv.2406.10954) | arXiv | [GitHub](https://github.com/IMoonKeyBoy/Towards-Efficient-Target-Level-Machine-Unlearning-Based-on-Essential-Graph) | 2 |
| Jie Xu et al. | [LMEraser: Large Model Unlearning through Adaptive Prompt Tuning](https://doi.org/10.48550/arXiv.2404.11056) | arXiv | [GitHub](https://github.com/lmeraser/lmeraser) | 2 |
| Rohan Sharma et al. | [Discriminative Adversarial Unlearning](https://doi.org/10.48550/arXiv.2402.06864) | arXiv | — | 2 |
| Yuxuan Wu, Bonaventure F. P. Dossou, Dianbo Liu | [CodeUnlearn: Amortized Zero-Shot Machine Unlearning in Language Models Using Discrete Concept](https://doi.org/10.48550/arXiv.2410.10866) | arXiv | — | 2 |
| Lu Yi, Zhewei Wei | [Scalable and Certifiable Graph Unlearning via Lazy Local Propagation](https://doi.org/10.48550/arXiv.2408.09212) | arXiv | — | 2 |
| Zihao Zhao et al. | [Pseudo-Probability Unlearning: Towards Efficient and Privacy-Preserving Machine Unlearning](https://doi.org/10.48550/arXiv.2411.02622) | arXiv | — | 2 |
| Matthew Wicker et al. | [Certificates of Differential Privacy and Unlearning for Gradient-Based Training](https://doi.org/10.48550/arXiv.2406.13433) | arXiv | [GitHub](https://github.com/Mihneaghitu/ModelGuidanceViaRobustFeatureAttribution) | 2 |
| Xiao Liu et al. | [Fishers Harvest Parallel Unlearning in Inherited Model Networks](https://doi.org/10.48550/arXiv.2408.08493) | arXiv | — | 2 |
| Bingchen Liu, Yuanyuan Fang | [Federated Knowledge Graph Unlearning via Diffusion Model](https://doi.org/10.48550/arXiv.2403.08554) | arXiv | — | 2 |
| Kahou Tam et al. | [Towards Federated Domain Unlearning: Verification Methodologies and Challenges](https://doi.org/10.48550/arXiv.2406.03078) | arXiv | — | 2 |
| Mingchen Li et al. | [Unlearning Virus Knowledge Toward Safe and Responsible Mutation Effect Predictions](https://doi.org/10.1101/2024.10.02.616274) | bioRxiv | — | 2 |
| Zeynep G. Saribatur, Stefan Woltran | [A Unified View on Forgetting and Strong Equivalence Notions in Answer Set Programming](https://doi.org/10.1609/aaai.v38i9.28940) | AAAI | — | 1 |
| Peng Deng et al. | [Cooperation Among Multiple Medical Institutions on Retinal Disease Identification Based on Federated Learning and Unlearning](https://doi.org/10.1109/ACCTCS61748.2024.00100) | ACCTCS | — | 1 |
| Masaru Isonuma, Ivan Titov | [Unlearning Traces the Influential Training Data of Language Models](https://doi.org/10.18653/v1/2024.acl-long.343) | ACL | [GitHub](https://github.com/misonuma/untrac) | 1 |
| Amartya Hatua, Trung T. Nguyen, Andrew H. Sung | [Machine Unlearning using a Multi-GAN based Model](https://doi.org/10.48550/arXiv.2407.18467) | AIP Conference Proceedings | — | 1 |
| Kai Cui, Yong Liao | [A Highly Efficient and Lightweight Graph Unlearning Method with Balanced Graph Partitioning and Adaptive Aggregation](https://doi.org/10.1109/CISCE62493.2024.10653362) | CISCE | — | 1 |
| Zirui Ling, Chao Zhang, Zijie Pan | [Multi-step and Iterative Backdoor Injection in Federated Machine Unlearning](https://doi.org/10.1109/csrswtc64338.2024.10811514) | CSRSWTC | — | 1 |
| Abhinav Joshi et al. | [Towards Robust Evaluation of Unlearning in LLMs via Data Transformations](https://doi.org/10.18653/v1/2024.findings-emnlp.706) | EMNLP | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 1 |
| Lowry Pressly | [The Right to Be Forgotten and the Value of an Open Future](https://doi.org/10.1086/731431) | Ethics | — | 1 |
| Eray Guven, Günes Karabulut-Kurt | [Machine Unlearning for Uplink Interference Cancellation](https://doi.org/10.1109/GLOBECOM52923.2024.10901616) | Global Communications Conference | [GitHub](https://github.com/riguwen/MULforIC) | 1 |
| Mansi, S. R. N. Reddy, Rishika Anand | [Comparison of Model Adaptation Techniques with Machine Unlearning](https://doi.org/10.1109/icccnt61001.2024.10723921) | ICCCNT | — | 1 |
| Naeem Ullah et al. | [DelSec: An Anti-Forensics Data Deletion Framework for Smartphones, IoT, and Edge Devices](https://doi.org/10.1109/icect61618.2024.10581213) | ICECT | — | 1 |
| Alekh Shrivastava, Mitul Kumar Ahirwal | [Refining of Learning in Human Decision Making Models: A Simple Step towards Machine Unlearning](https://doi.org/10.1109/icic3s61846.2024.10603026) | ICIC3S | — | 1 |
| Ching Lam Choi, Alexandre Duplessis, S. Belongie | [Unlearning-based Neural Interpretations](https://doi.org/10.48550/arXiv.2410.08069) | ICLR | — | 1 |
| I Putu Surya Pratama, Windy Gambetta | [Implementation of Exact Machine Unlearning Algorithm in Credit Scoring Cases](https://doi.org/10.1109/icodse63307.2024.10829911) | ICoDSE | — | 1 |
| Sangyoon Lee, Dae-Hyun Choi | [Learning and Unlearning to Operate Profitable Secure Electric Vehicle Charging](https://doi.org/10.1109/TII.2024.3396524) | IEEE T-II | — | 1 |
| Heng Xu et al. | [Toward Efficient Target-Level Machine Unlearning Based on Essential Graph](https://doi.org/10.1109/tnnls.2024.3514607) | IEEE TNNLS | — | 1 |
| Aditi Seetha et al. | [<i>DiEvD-SF</i>: Disruptive Event Detection Using Continual Machine Learning With Selective Forgetting](https://doi.org/10.1109/tcss.2024.3364544) | IEEE Transactions on Computational Social Systems | — | 1 |
| Wen‐Hung Liao, Y. Lin | [Investigation of Feature Distribution and Network Weight Updates in the Machine Unlearning Process](https://doi.org/10.1109/ism63611.2024.00022) | ISM | — | 1 |
| Ivana Halfpap, Željko Đurović | [Overcoming Catastrophic Forgetting in Neural Network During Continuous Learning: A Selective Layer Freezing Approach for Crack Detection](https://doi.org/10.1109/icetran62308.2024.10645158) | IcETRAN | — | 1 |
| Jingrui Hou, Axel Finke, Georgina Cosma | [Neural Corrective Machine Unranking](https://doi.org/10.48550/arXiv.2411.08562) | Information Sciences | [GitHub](https://github.com/JingruiHou/CorrectiveUnranking) | 1 |
| Yu Jiang, Chee Wei Tan, Kwok‐Yan Lam | [FedUHB: Accelerating Federated Unlearning via Polyak Heavy Ball Method](https://doi.org/10.1109/itw61385.2024.10807033) | Information Theory Workshop | — | 1 |
| Yong Zhang et al. | [A Novel Model-Knowledge Transfer Approach for Effective Machine Unlearning and Performance Preservation](https://doi.org/10.1145/3714334.3714371) | International Conference on Artificial Intelligence, Systems and Network Security | — | 1 |
| Indira Gandhi Delhi, S. Reddy, Rishika Anand | [Comparison of Model Adaptation Techniques with Machine Unlearning](https://doi.org/10.1109/ICCCNT61001.2024.10723921) | International Conference on Computing Communication and Networking Technologies | — | 1 |
| Lingyue Ge | [Erasing memories: implementing client unlearning in medical image analysis](https://doi.org/10.1117/12.3035404) | International Conference on Image Processing and Artificial Intelligence | — | 1 |
| Muhammad Ameen, Pengfei Wang | [Lightweight Federated Unlearning for IoT Sensing Systems](https://doi.org/10.1109/MSN63567.2024.00028) | International Conference on Mobile Ad-hoc and Sensor Networks | — | 1 |
| V. C. Gogineni, E. Nadimi | [Efficient Knowledge Deletion from Trained Models through Layer-wise Partial Machine Unlearning](https://doi.org/10.48550/arXiv.2403.07611) | JMLR | — | 1 |
| Ni Kadek Dhea Ardi Prabasari, Kadek Januarsa Adi Sudharma, Michael Angelo | [The Right to be Forgotten: Regulation of Personal Data Deletion in Indonesia](https://doi.org/10.31599/krtha.v18i3.3291) | KRTHA BHAYANGKARA | — | 1 |
| Pelin Tanberg et al. | [How varying cue duration influences item-method directed forgetting: A novel selective retrieval interpretation](https://doi.org/10.3758/s13421-024-01617-5) | Memory & Cognition | — | 1 |
| Li Cui, Pengfei Wang, Yuqi Han | [Edge Caching with Federated Unlearning in Cluster-Centric Small Cell Networks](https://doi.org/10.1109/ngdn61651.2024.10744106) | NGDN | — | 1 |
| Ziang Chen et al. | [Certified Machine Unlearning via Noisy Stochastic Gradient Descent](https://doi.org/10.52202/079017-1228) | NeurIPS | [GitHub](https://github.com/Graph-COM/SGD_unlearning) | 1 |
| Chongyu Fan et al. | [UnlearnCanvas: Stylized Image Dataset for Enhanced Machine Unlearning Evaluation in Diffusion Models](https://doi.org/10.52202/079017-3055) | NeurIPS | [GitHub](https://github.com/optml-group/unlearncanvas) | 1 |
| Changsong Yang et al. | [Block-based fine-grained and publicly verifiable data deletion for cloud storage](https://doi.org/10.1007/s00500-024-10359-0) | Soft Computing | — | 1 |
| Ying Hua, Hui Xia, Shuo Xu | [Federated Unlearning for Samples Based on Adaptive Gradient Ascent of Angles](https://doi.org/10.1109/trustcom63139.2024.00125) | TrustCom | — | 1 |
| Lei Zhou et al. | [Streamlined Federated Unlearning: Unite as One to Be Highly Efficient](https://doi.org/10.48550/arXiv.2412.00126) | arXiv | — | 1 |
| Hammad Rizwan et al. | [Instance-Level Difficulty: A Missing Perspective in Machine Unlearning](https://arxiv.org/abs/2410.03043) | arXiv | — | 1 |
| Xin Su, Zhuoran Zheng | [Accurate Forgetting for All-in-One Image Restoration Model](https://doi.org/10.48550/arXiv.2409.00685) | arXiv | [GitHub](https://github.com/Harbinzzy/All-in-One-Image-Restoration-Survey) | 1 |
| Ahan Chatterjee et al. | [Remembering Everything Makes You Vulnerable: A Limelight on Machine Unlearning for Personalized Healthcare Sector](https://doi.org/10.48550/arXiv.2407.04589) | arXiv | — | 1 |
| Nexhi Sula et al. | [Silver Linings in the Shadows: Harnessing Membership Inference for Machine Unlearning](https://doi.org/10.48550/arXiv.2407.00866) | arXiv | — | 1 |
| Zhixin Pan et al. | [Privacy-Preserving Debiasing using Data Augmentation and Machine Unlearning](https://doi.org/10.48550/arXiv.2404.13194) | arXiv | — | 1 |
| Ikhyun Cho, Changyeon Park, J. Hockenmaier | [ViT-MUL: A Baseline Study on Recent Machine Unlearning Methods Applied to Vision Transformers](https://doi.org/10.48550/arXiv.2403.09681) | arXiv | [GitHub](https://github.com/ihcho2/ViTMUL) | 1 |
| J. Khan | [Dataset Condensation Driven Machine Unlearning](https://doi.org/10.48550/arXiv.2402.00195) | arXiv | [GitHub](https://github.com/algebraicdianuj/DC_U) | 1 |
| Carl E.J. Brodzinski | [Survey of Security and Data Attacks on Machine Unlearning In Financial and E-Commerce](https://doi.org/10.48550/arXiv.2410.00055) | arXiv | — | 1 |
| R. Smirnov | [Classifier-free guidance in LLMs Safety](https://doi.org/10.48550/arXiv.2412.06846) | arXiv | — | 1 |
| Héctor Laria Mantecón et al. | [Assessing Open-world Forgetting in Generative Image Model Customization](https://doi.org/10.48550/arXiv.2410.14159) | arXiv | [GitHub](https://github.com/danelpeng/Awesome-Continual-Leaning-with-PTMs) | 1 |
| Xinrui Yu et al. | [Federated Unlearning Model Recovery in Data with Skewed Label Distributions](https://doi.org/10.48550/arXiv.2412.13466) | arXiv | — | 1 |
| Youyang Qu et al. | [Continuous Verification of Catastrophic Recalling in Machine Unlearning via Adversarial Testing](https://doi.org/10.1109/dsc63484.2024.00056) | arXiv | — | 1 |
| Chee Chan et al. | [Ferrari: Federated Feature Unlearning via Optimizing Feature Sensitivity](https://doi.org/10.52202/079017-0761) | arXiv | [GitHub](https://github.com/OngWinKent/Federated-Feature-Unlearning) | 1 |
| Felix Hsieh et al. | [Mitigating Backdoor Attacks using Activation-Guided Model Editing](https://doi.org/10.48550/arXiv.2407.07662) | ACCV Workshops | — | 0 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Training-free Class For-getting](https://www.semanticscholar.org/paper/0499ce47dee94383309fe2e5ddb4197dbc1bbefd) | Accepted by TMLR | — | 0 |
| Laman Aliyeva et al. | [Deep Unlearning of Breast Cancer Histopathological Images for Enhanced Responsibility in Classification](https://doi.org/10.1109/AICT61888.2024.10740413) | Advanced Industrial Conference on Telecommunications | — | 0 |
| Kai Cui, Yong Liao | [A Highly Efficient and Lightweight Graph Unlearning Method with Balanced Graph Partitioning and Adaptive Aggregation](https://doi.org/10.1109/cisce62493.2024.10653362) | CISCE | — | 0 |
| Huanyi Ye et al. | [Malicious Unlearning in Ensemble Models](https://doi.org/10.1109/PST62714.2024.10788066) | Conference on Privacy, Security and Trust | — | 0 |
| Sofiane Azogagh et al. | [Oblivious Exact (Un)Learning of Extremely Randomized Trees](https://www.semanticscholar.org/paper/471f49452591e17a356dc32bc865fb3c2275f6df) | EDCC | — | 0 |
| Jianfang Wang, Meng Liang, Guangwen Chai | [Recommendation Unlearning with Dynamic Sampling and Interest Boundary Perception](https://doi.org/10.1109/hpcc64274.2024.00183) | HPCC | — | 0 |
| Maryam Solaiman et al. | [Modeling Unlearning and Relearning with Multi-Agent Q-Learning Systems](https://doi.org/10.1109/ICCCMLA63077.2024.10871690) | ICCCMLA | — | 0 |
| Alekh Shrivastava, M. K. Ahirwal | [Refining of Learning in Human Decision Making Models: A Simple Step towards Machine Unlearning](https://doi.org/10.1109/ICIC3S61846.2024.10603026) | ICIC3S | — | 0 |
| Zheling Meng et al. | [Dark Miner: Defend against undesirable generation for text-to-image diffusion models](https://arxiv.org/abs/2409.17682) | ICLR Conference Withdrawn Submission | [GitHub](https://github.com/ultralytics/ultralytics) | 0 |
| Zihao Zhao et al. | [AdaProb: Efficient Machine Unlearning via Adaptive Probability](https://arxiv.org/abs/2411.02622) | ICLR Workshop DATA-FM | [GitHub](https://github.com/zzhao71/AdaProb) | 0 |
| R. Karn, J. Knechtel, Ozgur Sinanoglu | [Selective Forgetting in Task-Progressive Learning Through Machine Unlearning](https://doi.org/10.1109/ICMLC63072.2024.10935063) | ICML | — | 0 |
| Rupesh Raj Karn, Johann Knechtel, Ozgur Sinanoglu | [Selective Forgetting in Task-Progressive Learning Through Machine Unlearning](https://doi.org/10.1109/icmlc63072.2024.10935063) | ICMLC | — | 0 |
| Ching-Chun Chang et al. | [Hypnopaedia-Aware Machine Unlearning via Psychometrics of Artificial Mental Imagery](https://doi.org/10.1109/ACCESS.2025.3576800) | IEEE Access | — | 0 |
| Jianfang Wang, Menghao Liang, G. Chai | [Recommendation Unlearning with Dynamic Sampling and Interest Boundary Perception](https://doi.org/10.1109/HPCC64274.2024.00183) | IEEE International Conference on High Performance Computing and Communications | — | 0 |
| Wen-Hung Liao, Yang-Jing Lin | [Investigation of Feature Distribution and Network Weight Updates in the Machine Unlearning Process](https://doi.org/10.1109/ISM63611.2024.00022) | IEEE International Symposium on Multimedia | — | 0 |
| Hengzhu Liu et al. | [Game-Theoretic Machine Unlearning: Mitigating Extra Privacy Leakage](https://doi.org/10.1109/TIFS.2025.3623364) | IEEE T-IFS | — | 0 |
| Pengfei Ding et al. | [Adaptive Graph Unlearning](https://doi.org/10.24963/ijcai.2024/308) | IJCAI | [GitHub](https://github.com/Aliezzz/AGU) | 0 |
| Wenxiao Zhang | [A Comprehensive Investigation of Federated Unlearning: Challenges, Methods and Future Prospects in Privacy-Sensitive Applications](https://doi.org/10.5220/0013528500004619) | International Conference on Data Analysis and Machine Learning | — | 0 |
| Y. Qu et al. | [Continuous Verification of Catastrophic Recalling in Machine Unlearning via Adversarial Testing](https://doi.org/10.1109/DSC63484.2024.00056) | International Conference on Data Science in Cyberspace | — | 0 |
| I. Pratama, Windy Gambetta | [Implementation of Exact Machine Unlearning Algorithm in Credit Scoring Cases](https://doi.org/10.1109/ICoDSE63307.2024.10829911) | International Conference on Data and Software Engineering | — | 0 |
| Jeremy Syaloom Okey Nathanael Simbolon, Windy Gambetta | [On Performance Comparison between Strong Machine Unlearning Algorithms for Logistic Regression Credit Assessment Models](https://doi.org/10.1109/ICoDSE63307.2024.10829916) | International Conference on Data and Software Engineering | — | 0 |
| U. G et al. | [Securing Personal Identity in Facial Recognition: The Shift to Machine Unlearning](https://doi.org/10.1109/ICSES63445.2024.10763384) | International Conference on Signals and Electronic Systems | — | 0 |
| Shanshan Chen et al. | [A Continuous Verification Mechanism for Clients in Federated Unlearning to Defend the Right to be Forgotten](https://doi.org/10.1109/ispa63168.2024.00115) | International Symposium on Image and Signal Processing and Analysis | [GitHub](https://github.com/paper-liu/BAFV-master) | 0 |
| G. Brahmani et al. | [Emerging Challenges and Future Directions in Federated Unlearning](https://doi.org/10.48001/jocsvl.2024.127-14) | Journal of Computer Systems, Virtualization and Languages | — | 0 |
| Florian Stadtmann, Adil Rasheed | [Federated Learning and Unlearning as Enablers of Wind Turbine Digital Twins](https://doi.org/10.1088/1742-6596/2767/5/052031) | Journal of Physics: Conference Series | — | 0 |
| Muhammad Ameen, Pengfei Wang | [Lightweight Federated Unlearning for IoT Sensing Systems](https://doi.org/10.1109/msn63567.2024.00028) | MSN | — | 0 |
| Yong-Hyun Park et al. | [Diffusion Unlearning Optimization for Robust and Safe Text-to-Image Models](https://www.semanticscholar.org/paper/01795cf6da0374bdb35a61d50ccf886e5b472329) | NeurIPS | — | 0 |
| David Dobre et al. | [Soft Prompt Threats: Attacking Safety Alignment and Unlearning in Open-Source LLMs through the Embedding Space](https://doi.org/10.52202/079017-0288) | NeurIPS | [GitHub](https://github.com/SchwinnL/LLM_Embedding_Attack) | 0 |
| Xiwen Wei, Guihong Li, R. Marculescu | [Fairness Implications of Machine Unlearning: Bias Risks in Removing NSFW Content from Text-to-Image Models](https://www.semanticscholar.org/paper/5ad0199e38cd61df8c81b55d46366006dcb3e40c) | RegML | — | 0 |
| Xinghui Yue et al. | [Research on Machine Unlearning Verification Based on Predictive Cross-Entropy](https://doi.org/10.1109/SWC62898.2024.00139) | SWC | — | 0 |
| K. Salas-Jimenez et al. | [GIL-IIMAS UNAM at SemEval-2025 Task 4: LA-Min(E): LLM Unlearning Approaches Under Function Minimizing Evaluation Constraints](https://www.semanticscholar.org/paper/86222121bff9302a2f7d0ef7a3b17acd792b258f) | SemEval | — | 0 |
| Claudio Savelli et al. | [MALTO at SemEval-2025 Task 4: Dual Teachers for Unlearning Sensitive Content in LLMs](https://www.semanticscholar.org/paper/463cef51494fbc82ea38b9594c53d18778b043c6) | SemEval@NAACL | — | 0 |
| Yihan Wang et al. | [MUC: Machine Unlearning for Contrastive Learning with Black-box Evaluation](https://arxiv.org/abs/2406.03603) | TMLR | [GitHub](https://github.com/EhanW/Alignment-Calibration) | 0 |
| Qipeng Song et al. | [TrustNotify: A Lightweight Framework for Complete and Trustworthy Data Deletion Notification Distribution](https://doi.org/10.1109/TrustCom63139.2024.00084) | TrustCom | — | 0 |
| Chenhan Zhang et al. | [Targeted Therapy in Data Removal: Object Unlearning Based on Scene Graphs](https://doi.org/10.48550/arXiv.2412.00067) | arXiv | [GitHub](https://github.com/democode-CC/Object-Unlearning-Based-on-Scene-Graphs) | 0 |
| Junjie Chen et al. | [Machine Unlearning in Forgettability Sequence](https://doi.org/10.48550/arXiv.2410.06446) | arXiv | — | 0 |
| Zixin Wang, Kongyang Chen | [Machine Unlearning in Contrastive Learning](https://doi.org/10.48550/arXiv.2405.07317) | arXiv | — | 0 |
| Tao Huang et al. | [Machine Unlearning with Minimal Gradient Dependence for High Unlearning Ratios](https://doi.org/10.48550/arXiv.2406.16986) | arXiv | — | 0 |
| V. C. Gogineni, E. Nadimi | [Eﬃcient Knowledge Deletion from Trained Models Through Layer-wise Partial Machine Unlearning](https://arxiv.org/abs/2403.07611) | arXiv | — | 0 |
| Haoxuan Ji et al. | [Towards Aligned Data Removal via Twin Machine Unlearning](https://doi.org/10.48550/arXiv.2408.11433) | arXiv | — | 0 |
| Adam Shostack | [: R EMOVING H ARRY P OTTER FROM AN LLM IS HARDER THAN REPORTED](https://www.semanticscholar.org/paper/f1723094e3db36bac5125fbe8b86d31e32bba3dd) | arXiv | — | 0 |
| Anh-Vu Bui et al. | [Removing Undesirable Concepts in Text-to-Image Diffusion Models with Learnable Prompts](https://www.semanticscholar.org/paper/ea8bc2df279e00420167312c3ed0c38dfb396fd1) | arXiv | — | 0 |
| He Zhang et al. | [Gradient Transformation: Towards Efficient and Model-Agnostic Unlearning for Dynamic Graph Neural Networks](https://doi.org/10.48550/arXiv.2405.14407) | arXiv | — | 0 |

## 2023

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Rohit Gandikota et al. | [Erasing Concepts from Diffusion Models](https://doi.org/10.1109/ICCV51070.2023.00230) | ICCV | [GitHub](https://github.com/rohitgandikota/erasing) | 533 |
| Rohit Gandikota et al. | [Unified Concept Editing in Diffusion Models](https://doi.org/10.1109/WACV57701.2024.00503) | WACV | [GitHub](https://github.com/rohitgandikota/unified-concept-editing) | 365 |
| Ronen Eldan, M. Russinovich | [Who's Harry Potter? Approximate Unlearning in LLMs](https://arxiv.org/abs/2310.02238) | arXiv | [HF](https://huggingface.co/datasets/PhillipGuo/WHP_Generic_Predictions) | 362 |
| Chongyu Fan et al. | [SalUn: Empowering Machine Unlearning via Gradient-based Weight Saliency in Both Image Classification and Generation](https://doi.org/10.48550/arXiv.2310.12508) | ICLR | [GitHub](https://github.com/optml-group/unlearn-saliency) | 347 |
| Nupur Kumari et al. | [Ablating Concepts in Text-to-Image Diffusion Models](https://doi.org/10.1109/ICCV51070.2023.02074) | ICCV | [GitHub](https://github.com/nupurkmr9/concept-ablation) | 327 |
| Eric J. Zhang et al. | [Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models](https://doi.org/10.1109/CVPRW63382.2024.00182) | CVPR | [GitHub](https://github.com/SHI-Labs/Forget-Me-Not) | 312 |
| Yuanshun Yao, Xiaojun Xu, Yang Liu | [Large Language Model Unlearning](https://doi.org/10.48550/arXiv.2310.10683) | NeurIPS | [GitHub](https://github.com/kevinyaobytedance/llm_unlearn) | 281 |
| Meghdad Kurmanji, P. Triantafillou, Eleni Triantafillou | [Towards Unbounded Machine Unlearning](https://doi.org/10.48550/arXiv.2302.09880) | NeurIPS | [GitHub](https://github.com/meghdadk/SCRUB) | 279 |
| Jiaao Chen, Diyi Yang | [Unlearn What You Want to Forget: Efficient Unlearning for LLMs](https://doi.org/10.48550/arXiv.2310.20150) | EMNLP | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 241 |
| Martin Pawelczyk, Seth Neel, Himabindu Lakkaraju | [In-Context Unlearning: Language Models as Few Shot Unlearners](https://doi.org/10.48550/arXiv.2310.07579) | ICML | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 216 |
| Yu-Lin Tsai et al. | [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://doi.org/10.48550/arXiv.2310.10012) | ICLR | [GitHub](https://github.com/chiayi-hsu/Ring-A-Bell) | 207 |
| Jack Foster, Stefan Schoepf, A. Brintrup | [Fast Machine Unlearning Without Retraining Through Selective Synaptic Dampening](https://doi.org/10.48550/arXiv.2308.07707) | AAAI | [GitHub](https://github.com/if-loops/selective-synaptic-dampening) | 206 |
| Yimeng Zhang et al. | [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://doi.org/10.48550/arXiv.2310.11868) | ECCV | [GitHub](https://github.com/optml-group/diffusion-mu-attack) | 205 |
| Alvin Heng, Harold Soh | [Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models](https://doi.org/10.48550/arXiv.2305.10120) | NeurIPS | [GitHub](https://github.com/clear-nus/selective-amnesia) | 187 |
| Vaidehi Patil, Peter Hase, Mohit Bansal | [Can Sensitive Information Be Deleted From LLMs? Objectives for Defending Against Extraction Attacks](https://doi.org/10.48550/arXiv.2309.17410) | ICLR | [GitHub](https://github.com/vaidehi99/infodeletionattacks) | 165 |
| Min Chen et al. | [Boundary Unlearning: Rapid Forgetting of Deep Networks via Shifting the Decision Boundary](https://doi.org/10.1109/CVPR52729.2023.00750) | CVPR | [GitHub](https://github.com/OngWinKent/MachineUnlearning) | 162 |
| Rohit Gandikota et al. | [Erasing Concepts from Diffusion Models](https://doi.org/10.1109/iccv51070.2023.00230) | ICCV | [GitHub](https://github.com/rohitgandikota/erasing) | 155 |
| Charles Yu et al. | [Unlearning Bias in Language Models by Partitioning Gradients](https://doi.org/10.18653/v1/2023.findings-acl.375) | ACL | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 148 |
| Mengyao Lyu et al. | [One-dimensional Adapter to Rule Them All: Concepts, Diffusion Models and Erasing Applications](https://doi.org/10.1109/CVPR52733.2024.00722) | CVPR | [GitHub](https://github.com/Con6924/SPM) | 145 |
| Ayush K Tarun et al. | [Fast Yet Effective Machine Unlearning](https://doi.org/10.1109/tnnls.2023.3266233) | IEEE TNNLS | [GitHub](https://github.com/vikram2000b/Fast-Machine-Unlearning) | 141 |
| Vikram S Chundawat et al. | [Zero-Shot Machine Unlearning](https://doi.org/10.1109/tifs.2023.3265506) | IEEE T-IFS | [GitHub](https://github.com/ayu987/zero-shot-unlearning) | 129 |
| Jie Xu et al. | [Machine Unlearning: Solutions and Challenges](https://doi.org/10.1109/TETCI.2024.3379240) | IEEE TETCI | [GitHub](https://github.com/pybrush/pybrush) | 127 |
| Ziyao Liu et al. | [A Survey on Federated Unlearning: Challenges, Methods, and Future Directions](https://doi.org/10.1145/3679014) | ACM Computing Surveys | — | 125 |
| Chi-Pin Huang et al. | [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://doi.org/10.48550/arXiv.2311.17717) | ECCV | [GitHub](https://github.com/jasper0314-huang/Receler) | 115 |
| Lingzhi Wang et al. | [KGA: A General Machine Unlearning Framework Based on Knowledge Gap Alignment](https://doi.org/10.48550/arXiv.2305.06535) | ACL | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 107 |
| Wei Yuan et al. | [Federated Unlearning for On-Device Recommendation](https://doi.org/10.1145/3539597.3570463) | WSDM | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 106 |
| Ruizhe Chen et al. | [Fast Model Debias with Machine Unlearning](https://doi.org/10.48550/arXiv.2310.12560) | NeurIPS | [GitHub](https://github.com/diadai/Machine-Unlearning) | 102 |
| Zhenyi Wang et al. | [A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning](https://doi.org/10.1109/TPAMI.2024.3498346) | IEEE TPAMI | [GitHub](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) | 100 |
| Vikram S Chundawat et al. | [Can Bad Teaching Induce Forgetting? Unlearning in Deep Networks Using an Incompetent Teacher](https://doi.org/10.1609/aaai.v37i6.25879) | AAAI | — | 89 |
| Haibo Zhang et al. | [A Review on Machine Unlearning](https://doi.org/10.1007/s42979-023-01767-4) | SN Computer Science | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 88 |
| Lefeng Zhang et al. | [FedRecovery: Differentially Private Machine Unlearning for Federated Learning Frameworks](https://doi.org/10.1109/tifs.2023.3297905) | IEEE T-IFS | — | 83 |
| Minh Pham, Kelly O. Marshall, C. Hegde | [Circumventing Concept Erasure Methods For Text-to-Image Generative Models](https://doi.org/10.48550/arXiv.2308.01508) | ICLR | [GitHub](https://github.com/nyu-dice-lab/circumventing-concept-erasure) | 82 |
| Sungmin Cha et al. | [Learning to Unlearn: Instance-wise Unlearning for Pre-trained Classifiers](https://doi.org/10.48550/arXiv.2301.11578) | AAAI | [GitHub](https://github.com/csm9493/L2UL) | 78 |
| Tianshi Che et al. | [Fast Federated Machine Unlearning with Nonlinear Functional Theory](https://www.semanticscholar.org/paper/bcd2c4ef6b1e985e0783e886b2576abe3c7983f9) | ICML | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 77 |
| Ningxin Su, Baochun Li | [Asynchronous Federated Unlearning](https://doi.org/10.1109/INFOCOM53939.2023.10229075) | IEEE Conference on Computer Communications | — | 74 |
| T. Shaik et al. | [Exploring the Landscape of Machine Unlearning: A Comprehensive Survey and Taxonomy](https://doi.org/10.1109/TNNLS.2024.3486109) | IEEE TNNLS | — | 66 |
| Xiangrong Zhu, Guangyao Li, Wei Hu | [Heterogeneous Federated Knowledge Graph Embedding Learning and Unlearning](https://doi.org/10.1145/3543507.3583305) | WWW | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 64 |
| Min Chen et al. | [Boundary Unlearning: Rapid Forgetting of Deep Networks via Shifting the Decision Boundary](https://doi.org/10.1109/cvpr52729.2023.00750) | CVPR | [GitHub](https://github.com/OngWinKent/MachineUnlearning) | 61 |
| Shen Lin et al. | [ERM-KTP: Knowledge-Level Machine Unlearning via Knowledge Transfer](https://doi.org/10.1109/CVPR52729.2023.01929) | CVPR | [GitHub](https://github.com/RUIYUN-ML/ERM-KTP) | 58 |
| Aly M. Kassem, Omar Mahmoud, Sherif Saad | [Preserving Privacy Through Dememorization: An Unlearning Technique For Mitigating Memorization Risks In Language Models](https://doi.org/10.18653/v1/2023.emnlp-main.265) | EMNLP | [GitHub](https://github.com/Alymostafa/DeMemorization) | 57 |
| Eli Chien, Chao Pan, O. Milenkovic | [Efficient Model Updates for Approximate Unlearning of Graph-Structured Data](https://www.semanticscholar.org/paper/5e04e20d9c550fc1cef1f1f86b30aadf0492fbac) | ICLR | [GitHub](https://github.com/thupchnsky/sgc_unlearn) | 55 |
| Jiali Cheng et al. | [GNNDelete: A General Strategy for Unlearning in Graph Neural Networks](https://doi.org/10.48550/arXiv.2302.13406) | ICLR | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 54 |
| Hui Xia et al. | [FedME<sup>2</sup>: Memory Evaluation &amp; Erase Promoting Federated Unlearning in DTMN](https://doi.org/10.1109/jsac.2023.3310049) | IEEE Journal on Selected Areas in Communications | — | 53 |
| Yian Zhao et al. | [Federated Unlearning With Momentum Degradation](https://doi.org/10.1109/jiot.2023.3321594) | IEEE IoT-J | — | 52 |
| Heng Xu et al. | [Machine Unlearning: A Survey](https://doi.org/10.1145/3603620) | ACM Computing Surveys | — | 51 |
| Ningxin Su, Baochun Li | [Asynchronous Federated Unlearning](https://doi.org/10.1109/infocom53939.2023.10229075) | Future Gener. Comput. Syst | — | 50 |
| Joel Jang et al. | [Knowledge Unlearning for Mitigating Privacy Risks in Language Models](https://doi.org/10.18653/v1/2023.acl-long.805) | arXiv | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 49 |
| Jiancan Wu et al. | [GIF: A General Graph Unlearning Strategy via Influence Function](https://doi.org/10.1145/3543507.3583521) | WWW | [GitHub](https://github.com/SJTU-DMTai/awesome-ml-data-quality-papers) | 47 |
| Hui Xia et al. | [FedME2: Memory Evaluation & Erase Promoting Federated Unlearning in DTMN](https://doi.org/10.1109/JSAC.2023.3310049) | IEEE Journal on Selected Areas in Communications | — | 46 |
| Laura van Oers et al. | [Unlearning in sustainability transitions: Insight from two Dutch community-supported agriculture farms](https://doi.org/10.1016/j.eist.2023.100693) | Environmental Innovation and Societal Transitions | — | 45 |
| Hongsheng Hu et al. | [A Duty to Forget, a Right to be Assured? Exposing Vulnerabilities in Machine Unlearning Services](https://doi.org/10.48550/arXiv.2309.08230) | NDSS | — | 45 |
| Xinshuo Hu et al. | [Separate the Wheat from the Chaff: Model Deficiency Unlearning via Parameter-Efficient Module Operation](https://doi.org/10.48550/arXiv.2308.08090) | AAAI | [GitHub](https://github.com/HITsz-TMG/Ext-Sub) | 43 |
| Cheng-Long Wang, Mengdi Huai, Di Wang | [Inductive Graph Unlearning](https://doi.org/10.48550/arXiv.2304.03093) | USENIX Security | [GitHub](https://github.com/Happy2Git/GUIDE) | 43 |
| Nianwen Si et al. | [Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges](https://doi.org/10.48550/arXiv.2311.15766) | arXiv | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 43 |
| Tuan Hoang et al. | [Learn to Unlearn for Deep Neural Networks: Minimizing Unlearning Interference with Gradient Projection](https://doi.org/10.1109/WACV57701.2024.00475) | WACV | [GitHub](https://github.com/hnanhtuan/projected_gradient_unlearning) | 41 |
| Jinghan Jia et al. | [Model Sparsification Can Simplify Machine Unlearning](https://doi.org/10.48550/arXiv.2304.04934) | arXiv | — | 41 |
| Sanghyun Kim et al. | [Towards Safe Self-Distillation of Internet-Scale Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2307.05977) | arXiv | [GitHub](https://github.com/nannullna/safe-diffusion) | 39 |
| Jiaao Chen, Diyi Yang | [Unlearn What You Want to Forget: Efficient Unlearning for LLMs](https://doi.org/10.18653/v1/2023.emnlp-main.738) | EMNLP Main | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 38 |
| Yuyuan Li et al. | [Making recommender systems forget: Learning and unlearning for erasable recommendation](https://doi.org/10.1016/j.knosys.2023.111124) | Knowledge-Based Systems | — | 38 |
| Wei Qian et al. | [Towards Understanding and Enhancing Robustness of Deep Learning Models against Malicious Unlearning Attacks](https://doi.org/10.1145/3580305.3599526) | KDD | — | 37 |
| Junxu Liu et al. | [MUter: Machine Unlearning on Adversarially Trained Models](https://doi.org/10.1109/ICCV51070.2023.00451) | ICCV | [GitHub](https://github.com/JunxuLiu/MUter) | 36 |
| Pengfei Wang et al. | [Mitigating Poor Data Quality Impact with Federated Unlearning for Human-Centric Metaverse](https://doi.org/10.1109/jsac.2023.3345388) | IEEE Journal on Selected Areas in Communications | — | 36 |
| Zuobin Xiong et al. | [Exact-Fun: An Exact and Efficient Federated Unlearning Approach](https://doi.org/10.1109/ICDM58522.2023.00188) | Industrial Conference on Data Mining | — | 36 |
| Korbinian Koch, Marcus Soll | [No Matter How You Slice It: Machine Unlearning with SISA Comes at the Expense of Minority Classes](https://doi.org/10.1109/SaTML54575.2023.00047) | SaTML | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 36 |
| Guang-Ming Li et al. | [Subspace based Federated Unlearning](https://doi.org/10.48550/arXiv.2302.12448) | TMLR | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 36 |
| Yuyuan Li et al. | [Making Users Indistinguishable: Attribute-wise Unlearning in Recommender Systems](https://doi.org/10.1145/3581783.3612418) | ACM MM | [GitHub](https://github.com/ZhangYizhao/RecAU) | 35 |
| Jiaqi Liu et al. | [Certified Minimax Unlearning with Generalization Rates and Deletion Capacity](https://doi.org/10.48550/arXiv.2312.10336) | NeurIPS | [GitHub](https://github.com/M1LKzzz/Sensitive-Data-Collection-and-Analysis-Mechanism-with-Local-Differential-Privacy-Preservation) | 35 |
| Yu Guo et al. | [Verifying in the Dark: Verifiable Machine Unlearning by Using Invisible Backdoor Triggers](https://doi.org/10.1109/tifs.2023.3328269) | IEEE T-IFS | [GitHub](https://github.com/techyangj/VD) | 34 |
| Dasol Choi, Dongbin Na | [Towards Machine Unlearning Benchmarks: Forgetting the Personal Identities in Facial Recognition Systems](https://doi.org/10.48550/arXiv.2311.02240) | arXiv | [GitHub](https://github.com/ndb796/machineunlearning) | 34 |
| Seunghoo Hong, Juhun Lee, Simon S. Woo | [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://doi.org/10.48550/arXiv.2312.12807) | AAAI | — | 33 |
| Shen Lin et al. | [ERM-KTP: Knowledge-Level Machine Unlearning via Knowledge Transfer](https://doi.org/10.1109/cvpr52729.2023.01929) | CVPR | [GitHub](https://github.com/RUIYUN-ML/ERM-KTP) | 33 |
| Wang Fei, Baochun Li, Bo Li | [Federated Unlearning and Its Privacy Threats](https://doi.org/10.1109/mnet.004.2300056) | IEEE Network | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 33 |
| Yonatan Dukler et al. | [SAFE: Machine Unlearning With Shard Graphs](https://doi.org/10.1109/ICCV51070.2023.01569) | ICCV | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 32 |
| Zixuan Ni et al. | [Degeneration-Tuning: Using Scrambled Grid shield Unwanted Concepts from Stable Diffusion](https://doi.org/10.1145/3581783.3611867) | ACM MM | [GitHub](https://github.com/openai/dalle-2-preview/blob) | 31 |
| T. Shaik et al. | [FRAMU: Attention-Based Machine Unlearning Using Federated Reinforcement Learning](https://doi.org/10.1109/TKDE.2024.3382726) | IEEE TKDE | — | 31 |
| Alexander X. Oesterling et al. | [Fair Machine Unlearning: Data Removal while Mitigating Disparities](https://doi.org/10.48550/arXiv.2307.14754) | AISTATS | [GitHub](https://github.com/AI4LIFE-GROUP/fair-unlearning) | 30 |
| Yuyuan Li et al. | [Selective and collaborative influence function for efficient recommendation unlearning](https://doi.org/10.1016/j.eswa.2023.121025) | Expert Systems with Applications | — | 28 |
| Manaar Alam, Hithem Lamri, Michail Maniatakos | [Get Rid of Your Trail: Remotely Erasing Backdoors in Federated Learning](https://doi.org/10.1109/TAI.2024.3465441) | IEEE TAI | [GitHub](https://github.com/momalab/federated_backdoor_unlearning) | 28 |
| Weilin Cong, Mehrdad Mahdavi | [Efficiently Forgetting What You Have Learned in Graph Representation Learning via Projection](https://doi.org/10.48550/arXiv.2302.08990) | AISTATS | [GitHub](https://github.com/MinChen00/Graph-Unlearning) | 27 |
| Yavuz Faruk Bakman et al. | [Federated Orthogonal Training: Mitigating Global Catastrophic Forgetting in Continual Federated Learning](https://doi.org/10.48550/arXiv.2309.01289) | ICLR | [GitHub](https://github.com/duygunuryldz/Federated_Orthogonal_Training) | 27 |
| Korbinian Koch, Marcus Soll | [No Matter How You Slice It: Machine Unlearning with SISA Comes at the Expense of Minority Classes](https://doi.org/10.1109/satml54575.2023.00047) | SaTML | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 27 |
| Xintong Guo et al. | [FAST: Adopting Federated Unlearning to Eliminating Malicious Terminals at Server Side](https://doi.org/10.1109/tnse.2023.3343117) | IEEE TNSE | — | 26 |
| Weilin Cong, Mehrdad Mahrdavi | [GraphEditor : An Efficient Graph Representation Learning and Unlearning Approach](https://www.semanticscholar.org/paper/6d00fbb3c7aad35066efc09971fbb38c420741be) | arXiv | — | 26 |
| Rui Jin et al. | [Forgettable Federated Linear Learning with Certified Data Removal](https://doi.org/10.48550/arXiv.2306.02216) | arXiv | [GitHub](https://github.com/Nanboy-Ronan/2F2L-Federated-Unlearning) | 25 |
| Zuobin Xiong et al. | [Exact-Fun: An Exact and Efficient Federated Unlearning Approach](https://doi.org/10.1109/icdm58522.2023.00188) | ICDM | — | 24 |
| Kun Wu et al. | [Certified Edge Unlearning for Graph Neural Networks](https://doi.org/10.1145/3580305.3599271) | KDD | [GitHub](https://github.com/kunwu522/certified_edge_unlearning) | 23 |
| Maximilian Dreyer et al. | [From Hope to Safety: Unlearning Biases of Deep Models via Gradient Penalization in Latent Space](https://doi.org/10.1609/aaai.v38i19.30096) | AAAI | [GitHub](https://github.com/frederikpahde/rrclarc) | 22 |
| Saemi Moon, Seunghyuk Cho, Dongwoo Kim | [Feature Unlearning for Pre-trained GANs and VAEs](https://doi.org/10.1609/aaai.v38i19.30138) | AAAI | [GitHub](https://github.com/NVlabs/stylegan) | 22 |
| Weiqi Wang et al. | [BFU: Bayesian Federated Unlearning with Parameter Self-Sharing](https://doi.org/10.1145/3579856.3590327) | CCS | [GitHub](https://github.com/wwq5-code/BFU-Code) | 22 |
| Marco Cotogni et al. | [DUCK: Distance-based Unlearning via Centroid Kinematics](https://doi.org/10.48550/arXiv.2312.02052) | arXiv | [GitHub](https://github.com/ocram17/duck) | 22 |
| Pengfei Wang et al. | [Edge Caching with Federated Unlearning for Low-Latency V2X Communications](https://doi.org/10.1109/mcom.001.2300272) | IEEE Communications Magazine | — | 21 |
| Jiaxi Yang, Yang Zhao, Lixu Wang | [A Survey of Federated Unlearning: A Taxonomy, Challenges and Future Directions](https://doi.org/10.48550/arXiv.2310.19218) | arXiv | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 21 |
| T. Shaik et al. | [Exploring the Landscape of Machine Unlearning: A Survey and Taxonomy](https://www.semanticscholar.org/paper/3360d8d78e04579f5778b988506a0439115ceece) | arXiv | — | 21 |
| Zhili Liu et al. | [Implicit Concept Removal of Diffusion Models](https://doi.org/10.1007/978-3-031-72664-4_26) | ECCV | [HF](https://huggingface.co/datasets/zhili-liu/implicit-concept-dataset) | 20 |
| Weiqi Wang et al. | [Machine Unlearning via Representation Forgetting With Parameter Self-Sharing](https://doi.org/10.1109/tifs.2023.3331239) | IEEE T-IFS | [GitHub](https://github.com/wwq5-code/RFU-SS) | 20 |
| Yiyang Huang, C. Canonne | [Tight Bounds for Machine Unlearning via Differential Privacy](https://doi.org/10.48550/arXiv.2309.00886) | Journal of Privacy and Confidentiality | [GitHub](https://github.com/XiangmanLI/Harmful-Information-Unlearning) | 20 |
| Akash Dhasade et al. | [QuickDrop: Efficient Federated Unlearning by Integrated Dataset Distillation](https://doi.org/10.48550/arXiv.2311.15603) | arXiv | [GitHub](https://github.com/sacs-epfl/quickdrop) | 20 |
| Hyunjun Kim, Sangyong Lee, Simon S. Woo | [Layer Attack Unlearning: Fast and Accurate Machine Unlearning via Layer Level Attack and Knowledge Distillation](https://doi.org/10.48550/arXiv.2312.16823) | AAAI | — | 19 |
| Hongyu Qiu et al. | [FedCIO: Efficient Exact Federated Unlearning with Clustering, Isolation, and One-shot Aggregation](https://doi.org/10.1109/BigData59044.2023.10386788) | BigData Congress [Services Society] | — | 19 |
| Siva Sai et al. | [Machine Un-learning: An Overview of Techniques, Applications, and Future Directions](https://doi.org/10.1007/s12559-023-10219-3) | Cognitive Computation | — | 19 |
| Jiali Cheng, Hadi Amiri | [MultiDelete for Multimodal Machine Unlearning](https://doi.org/10.1007/978-3-031-72940-9_10) | ECCV | [GitHub](https://github.com/CLU-UML/MultiDelete) | 19 |
| Yash Sinha, Murari Mandal, Mohan Kankanhalli | [Distill to Delete: Unlearning in Graph Networks With Knowledge Distillation](https://doi.org/10.1109/TNNLS.2025.3607995) | IEEE TNNLS | [GitHub](https://github.com/MachineUnlearn/D2DGN) | 19 |
| Chao Pan, Eli Chien, Olgica Milenković | [Unlearning Graph Classifiers with Limited Data Resources](https://doi.org/10.1145/3543507.3583547) | WWW | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 19 |
| Zhili Liu et al. | [Geom-Erasing: Geometry-Driven Removal of Implicit Concept in Diffusion Models](https://doi.org/10.48550/arXiv.2310.05873) | arXiv | — | 19 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Gradient-free Class Forgetting](https://arxiv.org/abs/2312.00761) | TMLR | [GitHub](https://github.com/sangamesh-kodge/class_forgetting) | 18 |
| Haocheng Xia et al. | [Equitable Data Valuation Meets the Right to Be Forgotten in Model Markets](https://doi.org/10.14778/3611479.3611531) | VLDB Endowment | [GitHub](https://github.com/ZJU-DIVER/ValuationMeetsRTBF) | 18 |
| Seohui Bae et al. | [Gradient Surgery for One-shot Unlearning on Generative Model](https://doi.org/10.48550/arXiv.2307.04550) | arXiv | — | 18 |
| Mimee Xu et al. | [Netflix and Forget: Efficient and Exact Machine Unlearning from Bi-linear Recommendations](https://doi.org/10.48550/arXiv.2302.06676) | arXiv | — | 18 |
| Saemi Moon, Seunghyuk Cho, Dongwoo Kim | [Feature Unlearning for Generative Models via Implicit Feedback](https://doi.org/10.48550/arXiv.2303.05699) | arXiv | — | 18 |
| Lingzhi Wang et al. | [KGA: A General Machine Unlearning Framework Based on Knowledge Gap Alignment](https://doi.org/10.18653/v1/2023.acl-long.740) | arXiv | [GitHub](https://github.com/snw2021/LLM_Unlearning_Papers) | 18 |
| Bjørn Aslak Juliussen, Jon Petter Rui, Dag Johansen | [Algorithms that forget: Machine unlearning and the right to erasure](https://doi.org/10.1016/j.clsr.2023.105885) | Computer law & security review | — | 17 |
| Ningning Ding, Ermin Wei, Randall Berry | [Strategic Data Revocation in Federated Unlearning](https://doi.org/10.1109/INFOCOM52122.2024.10621201) | IEEE Conference on Computer Communications | — | 17 |
| Hui Sun et al. | [Generative Adversarial Networks Unlearning](https://doi.org/10.1109/TDSC.2025.3564992) | IEEE TDSC | — | 16 |
| Bang Wu et al. | [GraphGuard: Detecting and Counteracting Training Data Misuse in Graph Neural Networks](https://doi.org/10.48550/arXiv.2312.07861) | NDSS | [GitHub](https://github.com/awslabs/g) | 16 |
| Ningning Ding et al. | [Incentive Mechanism Design for Federated Learning and Unlearning](https://doi.org/10.1145/3565287.3610269) | ACM Interational Symposium on Mobile Ad Hoc Networking and Computing | — | 15 |
| Tian-Yu Liu, Aditya Golatkar, S. Soatto | [Tangent Transformers for Composition, Privacy and Removal](https://doi.org/10.48550/arXiv.2307.08122) | ICLR | [GitHub](https://github.com/tianyu139/tangent-model-composition) | 15 |
| Juexiao Zhou et al. | [A unified method to revoke the private data of patients in intelligent healthcare with audit to forget](https://doi.org/10.1038/s41467-023-41703-x) | Nature Communications | [GitHub](https://github.com/Krimmyjack/Fine-tuning-of-medical-privacy) | 15 |
| Luciano Floridi | [Machine Unlearning: Its Nature, Scope, and Importance for a “Delete Culture”](https://doi.org/10.1007/s13347-023-00644-5) | Philosophy & Technology | [GitHub](https://github.com/chrisliu298/awesome-llm-unlearning) | 15 |
| Xin Xin et al. | [On the Effectiveness of Unlearning in Session-Based Recommendation](https://doi.org/10.1145/3616855.3635823) | WSDM | [GitHub](https://github.com/shirryliu/SRU-code) | 15 |
| Aditya Golatkar et al. | [Training Data Protection with Compositional Diffusion Models](https://doi.org/10.48550/arXiv.2308.01937) | arXiv | [GitHub](https://github.com/Zoky-2020/Security_and_Privacy_in_AIGC) | 15 |
| Yuyuan Li et al. | [Federated Unlearning via Active Forgetting](https://doi.org/10.48550/arXiv.2307.03363) | arXiv | — | 15 |
| Satyapriya Krishna, Jiaqi W. Ma, Himabindu Lakkaraju | [Towards Bridging the Gaps between the Right to Explanation and the Right to be Forgotten](https://doi.org/10.48550/arXiv.2302.04288) | ICML | — | 14 |
| Piyush Tiwary et al. | [Adapt then Unlearn: Exploiting Parameter Space Semantics for Unlearning in Generative Adversarial Networks](https://doi.org/10.48550/arXiv.2309.14054) | TMLR | [GitHub](https://github.com/atriguha/Adapt_Unlearn) | 14 |
| S. Kadhe et al. | [FairSISA: Ensemble Post-Processing to Improve Fairness of Unlearning in LLMs](https://doi.org/10.48550/arXiv.2312.07420) | arXiv | [GitHub](https://github.com/KID-22/LLM-Unlearning-Paper-List) | 14 |
| Kongyang Chen et al. | [Privacy preserving machine unlearning for smart cities](https://doi.org/10.1007/s12243-023-00960-z) | Annals of Telecommunications | — | 13 |
| Hmeda Musbah, Hamed H. Aly, Timothy Little | [A proposed novel adaptive DC technique for non-stationary data removal](https://doi.org/10.1016/j.heliyon.2023.e13903) | Heliyon | — | 13 |
| Junxu Liu et al. | [MUter: Machine Unlearning on Adversarially Trained Models](https://doi.org/10.1109/iccv51070.2023.00451) | ICCV | [GitHub](https://github.com/JunxuLiu/MUter) | 13 |
| Huawei Lin et al. | [Machine Unlearning in Gradient Boosting Decision Trees](https://doi.org/10.1145/3580305.3599420) | KDD | [GitHub](https://github.com/huawei-lin/GBDT_unlearning) | 13 |
| Dayong Ye et al. | [Reinforcement Unlearning](https://doi.org/10.48550/arXiv.2312.15910) | NDSS | [GitHub](https://github.com/cp-lab-uts/Reinforcement-Unlearning) | 13 |
| Zhaomin Wu et al. | [DeltaBoost: Gradient Boosting Decision Trees with Efficient Machine Unlearning](https://doi.org/10.1145/3589313) | ACM on Management of Data | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 12 |
| Zihao Deng et al. | [Vertical Federated Unlearning on the Logistic Regression Model](https://doi.org/10.3390/electronics12143182) | Electronics | [GitHub](https://github.com/bryanhx/Vertical-Federated-Unlearning-Benchmark) | 12 |
| Sebastian Schelter, Mozhdeh Ariannezhad, Maarten de Rijke | [Forget Me Now: Fast and Exact Unlearning in Neighborhood-based Recommendation](https://doi.org/10.1145/3539618.3591989) | SIGIR | — | 12 |
| Vedant Shah et al. | [Unlearning via Sparse Representations](https://doi.org/10.48550/arXiv.2311.15268) | TMLR | [GitHub](https://github.com/facebookresearch/fvcore) | 12 |
| Badih Ghazi et al. | [Ticketed Learning-Unlearning Schemes](https://doi.org/10.48550/arXiv.2306.15744) | Annual Conference Computational Learning Theory | — | 11 |
| Jia Shi et al. | [DeepClean: Machine Unlearning on the Cheap by Resetting Privacy Sensitive Weights using the Fisher Diagonal](https://doi.org/10.48550/arXiv.2311.10448) | ECCV Workshops | — | 11 |
| Yonatan Dukler et al. | [SAFE: Machine Unlearning With Shard Graphs](https://doi.org/10.1109/iccv51070.2023.01569) | ICCV | [GitHub](https://github.com/hannahshubby/NeurIPS_2023_Unlearning) | 11 |
| Rui Zhu et al. | [Selective Amnesia: On Efficient, High-Fidelity and Blind Suppression of Backdoor Effects in Trojaned Machine Learning Models](https://doi.org/10.1109/sp46215.2023.10351028) | IEEE S&P | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 11 |
| Vinayshekhar Bannihatti Kumar, Rashmi Gangadharaiah, Dan Roth | [Privacy Adhering Machine Un-learning in NLP](https://doi.org/10.18653/v1/2023.findings-ijcnlp.25) | IJCNLP | [GitHub](https://github.com/awslabs/privacy-adhering-machine-unlearning-nlp) | 11 |
| Anwar Said et al. | [A Survey of Graph Unlearning](https://doi.org/10.48550/arXiv.2310.02164) | arXiv | — | 11 |
| Samuele Poppi et al. | [Removing NSFW Concepts from Vision-and-Language Models for Text-to-Image Retrieval and Generation](https://doi.org/10.48550/arXiv.2311.16254) | ECCV | [GitHub](https://github.com/aimagelab/safe-clip) | 10 |
| Hongyu Qiu et al. | [FedCIO: Efficient Exact Federated Unlearning with Clustering, Isolation, and One-shot Aggregation](https://doi.org/10.1109/bigdata59044.2023.10386788) | IEEE Big Data | — | 10 |
| Samuele Poppi et al. | [Multiclass Unlearning for Image Classification via Weight Filtering](https://doi.org/10.1109/MIS.2024.3412742) | IEEE Intelligent Systems | — | 10 |
| Xulong Zhang et al. | [Machine Unlearning Methodology Based on Stochastic Teacher Network](https://doi.org/10.1007/978-3-031-46677-9_18) | International Conference on Advanced Data Mining and Applications | — | 10 |
| Uta Kohl | [THE RIGHT TO BE FORGOTTEN IN DATA PROTECTION LAW AND TWO WESTERN CULTURES OF PRIVACY](https://doi.org/10.1017/s0020589323000258) | International and Comparative Law Quarterly | — | 10 |
| Ziyi Zhao, Yulu Yan | [The Role of Organizational Unlearning in Manufacturing Firms’ Sustainable Digital Innovation: The Mechanism of Strategic Flexibility and Organizational Slack](https://doi.org/10.3390/su151310371) | Sustainability | — | 10 |
| Ali Abbasi et al. | [BrainWash: A Poisoning Attack to Forget in Continual Learning](https://doi.org/10.1109/CVPR52733.2024.02271) | CVPR | [GitHub](https://github.com/mint-vu/Brainwash) | 9 |
| Ningning Ding et al. | [Incentivized Federated Learning and Unlearning](https://doi.org/10.1109/TMC.2025.3557857) | IEEE TMC | — | 9 |
| Wangkun Xu, Fei Teng | [Task-Aware Machine Unlearning and Its Application in Load Forecasting](https://doi.org/10.1109/TPWRS.2024.3376828) | IEEE Transactions on Power Systems | [GitHub](https://github.com/xuwkk/task_aware_machine_unlearning) | 9 |
| Yufang Liu et al. | [Unlearning with Fisher Masking](https://doi.org/10.48550/arXiv.2310.05331) | arXiv | — | 9 |
| Sangamesh Kodge, Gobinda Saha, Kaushik Roy | [Deep Unlearning: Fast and Efficient Training-free Approach to Controlled Forgetting](https://doi.org/10.48550/arXiv.2312.00761) | arXiv | — | 9 |
| Yanna Jiang et al. | [Split Unlearning](https://doi.org/10.1145/3719027.3744787) | CCS | — | 8 |
| Sangyong Lee, Simon S. Woo | [UNDO: Effective and Accurate Unlearning Method for Deep Neural Networks](https://doi.org/10.1145/3583780.3615235) | CIKM | [GitHub](https://github.com/DASH-Lab/ML_privacy_research) | 8 |
| Kaiyue Zhang et al. | [Conditional Matching GAN Guided Reconstruction Attack in Machine Unlearning](https://doi.org/10.1109/GLOBECOM54140.2023.10437231) | Global Communications Conference | — | 8 |
| Peixin Zhang et al. | [Exploiting Machine Unlearning for Backdoor Attacks in Deep Learning System](https://arxiv.org/abs/2310.10659) | arXiv | [GitHub](https://github.com/seartifacts/bau) | 8 |
| Rui-Zhen Xu et al. | [A Revocation Key-based Approach Towards Efficient Federated Unlearning](https://doi.org/10.1109/AsiaJCIS60284.2023.00014) | Asia Joint Conference on Information Security | — | 7 |
| Guihong Li et al. | [Fast-NTK: Parameter-Efficient Unlearning for Large-Scale Models](https://doi.org/10.1109/CVPRW63382.2024.00027) | CVPR | [GitHub](https://github.com/ksasi/ModelEditingPapers) | 7 |
| Enayat Ullah, R. Arora | [From Adaptive Query Release to Machine Unlearning](https://doi.org/10.48550/arXiv.2307.11228) | ICML | [GitHub](https://github.com/XiangmanLI/Harmful-Information-Unlearning) | 7 |
| Hannah Carnegy-Arbuthnott | [Privacy, Publicity, and the Right to Be Forgotten](https://doi.org/10.1111/jopp.12308) | Journal of Political Philosophy | — | 7 |
| Jinghan Jia et al. | [Model Sparsity Can Simplify Machine Unlearning](https://doi.org/10.52202/075280-2246) | NeurIPS | [GitHub](https://github.com/optml-group/unlearn-sparse) | 7 |
| Jens Leysen | [Exploring Unlearning Methods to Ensure the Privacy, Security, and Usability of Recommender Systems](https://doi.org/10.1145/3604915.3608862) | RecSys | — | 7 |
| Oscar K Keyes, Adam Hyland | [Hands Are Hard: Unlearning How We Talk About Machine Learning in the Arts](https://doi.org/10.9741/2996-4873.1004) | Tradition Innovations in Arts Design and Media Higher Education | — | 7 |
| Jiahao Liu et al. | [Recommendation Unlearning via Matrix Correction](https://doi.org/10.48550/arXiv.2307.15960) | arXiv | — | 7 |
| Alvin Heng, Harold Soh | [Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models](https://doi.org/10.52202/075280-0751) | arXiv | [GitHub](https://github.com/clear-nus/selective-amnesia) | 7 |
| Yongjing Zhang et al. | [Machine Unlearning by Reversing the Continual Learning](https://doi.org/10.3390/app13169341) | Applied Sciences | — | 6 |
| Tzu-Hsuan Yang, Cheng-Te Li | [When Contrastive Learning Meets Graph Unlearning: Graph Contrastive Unlearning for Link Prediction](https://doi.org/10.1109/BigData59044.2023.10386624) | BigData Congress [Services Society] | — | 6 |
| Jesús L. Lobo, Sergio Gil-López, Javier Del Ser | [The Right to Be Forgotten in Artificial Intelligence: Issues, Approaches, Limitations and Challenges](https://doi.org/10.1109/cai54212.2023.00085) | CAI | — | 6 |
| Aloni Cohen et al. | [Control, Confidentiality, and the Right to be Forgotten](https://doi.org/10.1145/3576915.3616585) | CCS | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 6 |
| Javier Martínez Llamas, D. Preuveneers, W. Joosen | [Effective Machine Learning-based Access Control Administration through Unlearning](https://doi.org/10.1109/EuroSPW59978.2023.00011) | Euro S&P | — | 6 |
| Javier Martínez Llamas, Davy Preuveneers, Wouter Joosen | [Effective Machine Learning-based Access Control Administration through Unlearning](https://doi.org/10.1109/eurospw59978.2023.00011) | EuroS&amp;P Workshops | — | 6 |
| Zhe Liu, Ozlem Kalinli | [Forgetting Private Textual Sequences in Language Models Via Leave-One-Out Ensemble](https://doi.org/10.1109/ICASSP48485.2024.10446299) | ICASSP | — | 6 |
| Zhen Wang et al. | [FedCSA: Boosting the Convergence Speed of Federated Unlearning under Data Heterogeneity](https://doi.org/10.1109/ISPA-BDCloud-SocialCom-SustainCom59178.2023.00083) | IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom) | [GitHub](https://github.com/ZhenWang9/FedCSA) | 6 |
| Yang Zhao et al. | [Exploring Federated Unlearning: Review, Comparison, and Insights](https://doi.org/10.1109/MNET.2025.3571462) | IEEE Network | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 6 |
| André Artelt et al. | [Unsupervised Unlearning of Concept Drift with Autoencoders](https://doi.org/10.1109/ssci52147.2023.10372001) | IEEE Symposium Series on Computational Intelligence | [GitHub](https://github.com/HammerLabML/UnsupervisedUnlearningConceptDriftAutoencoders) | 6 |
| Subhodip Panda, AP Prathosh | [FAST: Feature Aware Similarity Thresholding for Weak Unlearning in Black-Box Generative Models](https://doi.org/10.1109/TAI.2024.3499939) | IEEE TAI | [GitHub](https://github.com/Subhodip123/weak-unlearning-gan) | 6 |
| Lucas Goodman, Anita Mukherjee, Shanthi Ramnath | [Set it and forget it? Financing retirement in an age of defaults](https://doi.org/10.1016/j.jfineco.2023.02.002) | Journal of Financial Economics | — | 6 |
| Gunardi Lie, Dylan Aldianza Ramadhan, Ahmad Redi | [KOMISI INDEPENDEN PERLINDUNGAN DATA PRIBADI: QUASI PERADILAN DAN UPAYA TERCIPTANYA RIGHT TO BE FORGOTTEN DI INDONESIA](https://doi.org/10.29123/jy.v15i2.530) | Jurnal Yudisial | — | 6 |
| Jamie Hayes et al. | [Towards Unbounded Machine Unlearning](https://doi.org/10.52202/075280-0095) | NeurIPS | [GitHub](https://github.com/meghdadk/SCRUB) | 6 |
| Marianna Papastephanou, Kalli Drousioti | [On learning and unlearning](https://doi.org/10.1177/14782103231176605) | Policy Futures in Education | — | 6 |
| Emmie Hine et al. | [Supporting Trustworthy AI Through Machine Unlearning](https://doi.org/10.2139/ssrn.4643518) | SSRN Electronic Journal | — | 6 |
| Ali Abbasi et al. | [CovarNav: Machine Unlearning via Model Inversion and Covariance Navigation](https://doi.org/10.48550/arXiv.2311.12999) | arXiv | — | 6 |
| Jian Zhang et al. | [SecureCut: Federated Gradient Boosting Decision Trees with Efficient Machine Unlearning](https://doi.org/10.48550/arXiv.2311.13174) | arXiv | — | 6 |
| Junde Li, Swaroop Ghosh | [Random Relabeling for Efficient Machine Unlearning](https://doi.org/10.48550/arXiv.2305.12320) | arXiv | — | 6 |
| Peixin Zhang et al. | [Backdoor Attack through Machine Unlearning](https://doi.org/10.48550/arXiv.2310.10659) | arXiv | [GitHub](https://github.com/seartifacts/bau) | 5 |
| Lusine Vardanyan et al. | [The Unwanted Paradoxes Of the Right to Be Forgotten](https://doi.org/10.5817/mujlt2023-1-3) | Masaryk University Journal of Law and Technology | — | 4 |
| Marta Paterlini | [Italy passes right to be forgotten for cancer survivors](https://doi.org/10.1016/s0140-6736(23)01730-0) | The Lancet | — | 4 |
| Guanhua Ye et al. | [Heterogeneous Decentralized Machine Unlearning with Seed Model Distillation](https://doi.org/10.48550/arXiv.2308.13269) | arXiv | — | 4 |
| Leijie Wu et al. | [On Knowledge Editing in Federated Learning: Perspectives, Challenges, and Future Directions](https://doi.org/10.48550/arXiv.2306.01431) | arXiv | — | 4 |
| Tomoya Yamashita, Masanori Yamada, Takashi Shibata | [One-Shot Machine Unlearning with Mnemonic Code](https://doi.org/10.48550/arXiv.2306.05670) | Asian Conference on Machine Learning | [GitHub](https://github.com/tomyamkum/OneShotMU-with-MNCode) | 3 |
| Manal A. Alshehri, Xiangliang Zhang | [Forgetting User Preference in Recommendation Systems with Label-Flipping](https://doi.org/10.1109/BigData59044.2023.10386603) | BigData Congress [Services Society] | — | 3 |
| Qun Song, Rui Tan, Jianping Wang | [Towards Efficient Personalized Driver Behavior Modeling with Machine Unlearning](https://doi.org/10.1145/3576914.3587489) | CPS-IoT Week Workshops | — | 3 |
| J. Lobo, S. Gil-Lopez, J. Ser | [The Right to Be Forgotten in Artificial Intelligence: Issues, Approaches, Limitations and Challenges](https://doi.org/10.1109/CAI54212.2023.00085) | Conference on Algebraic Informatics | — | 3 |
| Srijita Basu et al. | [Hyperledger based Verifiable and Secure Cloud Data Deletion](https://doi.org/10.1109/infocomwkshps57453.2023.10226125) | Conference on Computer Communications Workshops | — | 3 |
| Kaiyue Zhang et al. | [Conditional Matching GAN Guided Reconstruction Attack in Machine Unlearning](https://doi.org/10.1109/globecom54140.2023.10437231) | GLOBECOM | — | 3 |
| Yuxiang Zeng et al. | [Toward Highly-Efficient and Accurate Services QoS Prediction via Machine Unlearning](https://doi.org/10.1109/access.2023.3291410) | IEEE Access | — | 3 |
| Yashaswini Viswanath et al. | [Machine unlearning for generative AI](https://doi.org/10.69554/kzrs2422) | Journal of AI, robotics & workplace automation | [GitHub](https://github.com/ExplainableML/align-then-unlearn) | 3 |
| Josh Hogan | [Archives in the Digital Age: Preservation and the Right to Be Forgotten](https://doi.org/10.17723/2327-9702-86.2.661) | The American Archivist | — | 3 |
| Xulong Zhang et al. | [Machine Unlearning Methodology base on Stochastic Teacher Network](https://doi.org/10.48550/arXiv.2308.14322) | arXiv | [HF](https://huggingface.co/spaces/llam/Papers) | 3 |
| Crisanto F. Gulay, Arnel C. Fajardo | [Performance Enhancement of Long Short-Term Memory Through Unlearning-Relearning Soil Quality Parameters Data](https://doi.org/10.1109/agers61027.2023.10490639) | AGERS | — | 2 |
| Shuijing Zhang et al. | [Closed-form Machine Unlearning for Matrix Factorization](https://doi.org/10.1145/3583780.3614811) | CIKM | — | 2 |
| Seunghee Koh et al. | [Disposable Transfer Learning for Selective Source Task Unlearning](https://doi.org/10.1109/ICCV51070.2023.01079) | ICCV | — | 2 |
| Zhen Wang et al. | [FedCSA: Boosting the Convergence Speed of Federated Unlearning under Data Heterogeneity](https://doi.org/10.1109/ispa-bdcloud-socialcom-sustaincom59178.2023.00083) | ISPA/BDCloud/SocialCom/SustainCom | [GitHub](https://github.com/ZhenWang9/FedCSA) | 2 |
| Yuxin Tang et al. | [Fuzzy rough unlearning model for feature selection](https://doi.org/10.1016/j.ijar.2023.109102) | International Journal of Approximate Reasoning | [GitHub](https://github.com/yuxin370/ARU) | 2 |
| Khaoula ElBedoui | [ECG Classifiction Based on Federated Unlearning](https://doi.org/10.1109/isncc58260.2023.10323758) | International Symposium on Networks, Computers and Communications | — | 2 |
| Tereziia Popovych et al. | [Right to be Forgotten as a Special Digital Right](https://doi.org/10.26512/lstr.v15i2.44692) | Law State and Telecommunications Review | — | 2 |
| Mengdi Huai et al. | [Static and Sequential Malicious Attacks in the Context of Selective Forgetting](https://doi.org/10.52202/075280-3276) | NeurIPS | — | 2 |
| Rui-Zhen Xu et al. | [A Revocation Key-based Approach Towards Efficient Federated Unlearning](https://doi.org/10.1109/asiajcis60284.2023.00014) | arXiv | — | 2 |
| K. Hawkins et al. | [A Decision-Making Process to Implement the 'Right to Be Forgotten' in Machine Learning](https://doi.org/10.1007/978-3-031-61089-9_2) | Annual Privacy Forum | — | 1 |
| Shubhi Asthana et al. | [IDMU: Impact Driven Machine Unlearning](https://doi.org/10.1109/BigData59044.2023.10386841) | BigData Congress [Services Society] | — | 1 |
| Manal Alshehri, Xiangliang Zhang | [Forgetting User Preference in Recommendation Systems with Label-Flipping](https://doi.org/10.1109/bigdata59044.2023.10386603) | IEEE Big Data | — | 1 |
| Chaochao Chen et al. | [UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition](https://doi.org/10.52202/075280-0553) | NeurIPS | — | 1 |
| Long-Kai Huang et al. | [Retaining Beneficial Information from Detrimental Data for Neural Network Repair](https://doi.org/10.52202/075280-2084) | NeurIPS | — | 1 |
| Yuxiang Zeng et al. | [QoSEraser: A Data Erasable Framework for Web Service QoS Prediction](https://doi.org/10.1109/SSE60056.2023.00022) | SSE | [GitHub](https://github.com/ZengYuXiang7/QoSEraser) | 1 |
| Yuxiang Zeng et al. | [QoSEraser: A Data Erasable Framework for Web Service QoS Prediction](https://doi.org/10.1109/sse60056.2023.00022) | SSE | [GitHub](https://github.com/ZengYuXiang7/QoSEraser) | 1 |
| Shubhi Asthana et al. | [IDMU: Impact Driven Machine Unlearning](https://doi.org/10.1109/bigdata59044.2023.10386841) | arXiv | — | 1 |
| Jianhong Bai et al. | [Fast Model DeBias with Machine Unlearning](https://doi.org/10.52202/075280-0639) | arXiv | [GitHub](https://github.com/diadai/Machine-Unlearning) | 1 |
| Aditya Golatkar | [Unlearning and Privacy in Deep Neural Networks](https://www.semanticscholar.org/paper/51ff9fcf855568ec0c9e9a9265d12bec3e56375e) |  | — | 0 |
| Thai-Hung Nguyen et al. | [An Empirical Study of Federated Unlearning: Efficiency and Effectiveness](https://www.semanticscholar.org/paper/6d6612fa08179826513c2f18998db2662c5d1945) | ACML | — | 0 |
| Hsuan-Cheng Lin, Shih-Hsuan Yang | [Using Shadow Models to Protect Private Data on Machine Unlearning](https://doi.org/10.1109/ICCE-Taiwan58799.2023.10226994) | ICCE-Taiwan | — | 0 |
| Tzu-Hsuan Yang, Cheng–Te Li | [When Contrastive Learning Meets Graph Unlearning: Graph Contrastive Unlearning for Link Prediction](https://doi.org/10.1109/bigdata59044.2023.10386624) | IEEE Big Data | — | 0 |
| Fahao Chen, Peng Li, Shui Yu | [Efficient Giant Graph Unlearning via Push-Pull Tuning](https://doi.org/10.1109/ISPA-BDCloud-SocialCom-SustainCom59178.2023.00151) | IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom) | — | 0 |
| Fahao Chen, Peng Li, Shui Yu | [Efficient Giant Graph Unlearning via Push-Pull Tuning](https://doi.org/10.1109/ispa-bdcloud-socialcom-sustaincom59178.2023.00151) | ISPA/BDCloud/SocialCom/SustainCom | — | 0 |
| Adithyan M Nair et al. | [Selective Unlearning in Face Recognition: Forgetting Faces without Compromising Accuracy](https://doi.org/10.1109/ICIMIA60377.2023.10426386) | International Conference on Innovative Mechanisms for Industry Applications | — | 0 |
| Amr AbdelFatah Ahmed et al. | [Robust Concept Erasure via Kernelized Rate-Distortion Maximization](https://doi.org/10.52202/075280-1875) | NeurIPS | [GitHub](https://github.com/brcsomnath/KRaM) | 0 |
| Anwar Said et al. | [G RAPH U NLEARNING : A R EVIEW](https://www.semanticscholar.org/paper/a1862a376102751cef5bce3d3a4e3bca01706d16) | NeurIPS | — | 0 |
| Mingjian Tang et al. | [RUE: Realising Unlearning from the Perspective of Economics](https://doi.org/10.1109/TrustCom60117.2023.00159) | TrustCom | — | 0 |
| Youyang Qu et al. | [Learn to Unlearn: A Survey on Machine Unlearning](https://doi.org/10.48550/arXiv.2305.07512) | arXiv | [GitHub](https://github.com/thuwuyinjun/DeltaGrad) | 0 |

## 2022

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Joel Jang et al. | [Knowledge Unlearning for Mitigating Privacy Risks in Language Models](https://doi.org/10.48550/arXiv.2210.01504) | ACL | [GitHub](https://github.com/joeljang/knowledge-unlearning) | 427 |
| Ximing Lu et al. | [Quark: Controllable Text Generation with Reinforced Unlearning](https://doi.org/10.48550/arXiv.2205.13636) | NeurIPS | [GitHub](https://github.com/gximinglu/quark) | 266 |
| Vikram S Chundawat et al. | [Can Bad Teaching Induce Forgetting? Unlearning in Deep Networks using an Incompetent Teacher](https://doi.org/10.48550/arXiv.2205.08096) | AAAI | — | 247 |
| Yi Liu et al. | [The Right to be Forgotten in Federated Learning: An Efficient Realization with Rapid Retraining](https://doi.org/10.1109/INFOCOM48880.2022.9796721) | IEEE Conference on Computer Communications | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 234 |
| Vikram S Chundawat et al. | [Zero-Shot Machine Unlearning](https://doi.org/10.1109/TIFS.2023.3265506) | IEEE T-IFS | [GitHub](https://github.com/ayu987/zero-shot-unlearning) | 201 |
| Anisa Halimi et al. | [Federated Unlearning: How to Efficiently Erase a Client in FL?](https://doi.org/10.48550/arXiv.2207.05521) | arXiv | [GitHub](https://github.com/IBM/federated-unlearning) | 200 |
| Chen Wu, Sencun Zhu, P. Mitra | [Federated Unlearning with Knowledge Distillation](https://arxiv.org/abs/2201.09441) | arXiv | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 160 |
| Matthew Jagielski et al. | [Measuring Forgetting of Memorized Training Examples](https://doi.org/10.48550/arXiv.2207.00099) | ICLR | [GitHub](https://github.com/safr-ai-lab/survey-llm) | 141 |
| B. Liu, Qian Liu, P. Stone | [Continual Learning and Private Unlearning](https://doi.org/10.48550/arXiv.2203.12817) | CoLLAs | [GitHub](https://github.com/cranial-xix/continual-learning-private-unlearning) | 128 |
| Junxiao Wang et al. | [Federated Unlearning via Class-Discriminative Pruning](https://doi.org/10.1145/3485447.3512222) | WWW | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 126 |
| Min Chen et al. | [Graph Unlearning](https://doi.org/10.1145/3548606.3559352) | CCS | [GitHub](https://github.com/MinChen00/Graph-Unlearning) | 109 |
| Thomas Baumhauer, Pascal Schöttle, Matthias Zeppelzauer | [Machine unlearning: linear filtration for logit-based classifiers](https://doi.org/10.1007/s10994-022-06178-9) | Machine Learning | [GitHub](https://github.com/th-b/linear_filtration) | 95 |
| Chong Chen et al. | [Recommendation Unlearning](https://doi.org/10.1145/3485447.3511997) | WWW | [GitHub](https://github.com/chenchongthu/Recommendation-Unlearning) | 93 |
| Shashwat Goel et al. | [Towards Adversarial Evaluations for Inexact Machine Unlearning](https://arxiv.org/abs/2201.06640) | arXiv | [GitHub](https://github.com/shash42/Evaluating-Inexact-Unlearning) | 93 |
| Xiangshan Gao et al. | [VeriFi: Towards Verifiable Federated Unlearning](https://doi.org/10.1109/TDSC.2024.3382321) | IEEE TDSC | — | 79 |
| Haonan Yan et al. | [ARCANE: An Efficient Architecture for Exact Machine Unlearning](https://doi.org/10.24963/ijcai.2022/556) | IJCAI | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 79 |
| Yang Liu et al. | [Backdoor Defense with Machine Unlearning](https://doi.org/10.1109/infocom48880.2022.9796974) | IEEE INFOCOM - IEEE Conference on Computer Communications | [GitHub](https://github.com/THUYimingLi/backdoor-learning-resources) | 77 |
| Rishav Chourasia, Neil Shah, R. Shokri | [Forget Unlearning: Towards True Data-Deletion in Machine Learning](https://doi.org/10.48550/arXiv.2210.08911) | ICML | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 73 |
| Yuyuan Li et al. | [Making Recommender Systems Forget: Learning and Unlearning for Erasable Recommendation](https://doi.org/10.48550/arXiv.2203.11491) | Knowledge-Based Systems | — | 72 |
| Jimmy Z. Di et al. | [Hidden Poison: Machine Unlearning Enables Camouflaged Poisoning Attacks](https://doi.org/10.48550/arXiv.2212.10717) | NeurIPS | [GitHub](https://github.com/Jimmy-di/camouflage-poisoning) | 66 |
| Neil G. Marchant, Benjamin I. P. Rubinstein, Scott Alfeld | [Hard to Forget: Poisoning Attacks on Certified Machine Unlearning](https://doi.org/10.1609/aaai.v36i7.20736) | AAAI | [GitHub](https://github.com/ngmarchant/attack-unlearning) | 59 |
| Leijie Wu et al. | [Federated Unlearning: Guarantee the Right of Clients to Forget](https://doi.org/10.1109/mnet.001.2200198) | IEEE Network | — | 57 |
| Eli Chien, Chao Pan, O. Milenkovic | [Certified Graph Unlearning](https://doi.org/10.48550/arXiv.2206.09140) | arXiv | [GitHub](https://github.com/mims-harvard/GNNDelete) | 57 |
| Jingwen Ye et al. | [Learning with Recoverable Forgetting](https://doi.org/10.48550/arXiv.2207.08224) | ECCV | [GitHub](https://github.com/JngwenYe/LIRF) | 53 |
| Zijie Zhang et al. | [Prompt Certified Machine Unlearning with Randomized Gradient Smoothing and Quantization](https://www.semanticscholar.org/paper/87d50f6f5bcbc0270375669f4bfc424135921397) | NeurIPS | — | 52 |
| Alexander Becker, T. Liebig | [Evaluating Machine Unlearning via Epistemic Uncertainty](https://doi.org/10.48550/arXiv.2208.10836) | arXiv | [GitHub](https://github.com/ROYALBEFF/evaluating_machine_unlearning_via_epistemic_uncertainty) | 52 |
| A. Tarun et al. | [Deep Regression Unlearning](https://doi.org/10.48550/arXiv.2210.08196) | ICML | [GitHub](https://github.com/ayu987/deep-regression-unlearning) | 51 |
| Ronak Mehta et al. | [Deep Unlearning via Randomized Conditionally Independent Hessians](https://doi.org/10.1109/cvpr52688.2022.01017) | CVPR | [GitHub](https://github.com/vsingh-group/LCODEC-deep-unlearning) | 50 |
| Zhuo Ma et al. | [Learn to Forget: Machine Unlearning via Neuron Masking](https://doi.org/10.1109/tdsc.2022.3194884) | IEEE TDSC | — | 50 |
| Vinith M. Suriyakumar, Ashia C. Wilson | [Algorithms that Approximate Data Removal: New Results and Limitations](https://doi.org/10.48550/arXiv.2209.12269) | NeurIPS | [GitHub](https://github.com/VMS-6511/online-data-deletion) | 50 |
| David Sommer et al. | [Athena: Probabilistic Verification of Machine Unlearning](https://doi.org/10.56553/popets-2022-0072) | PoPETs | [GitHub](https://github.com/inspire-group/unlearning-verification) | 49 |
| Vinayshekhar Bannihatti Kumar, Rashmi Gangadharaiah, Dan Roth | [Privacy Adhering Machine Un-learning in NLP](https://doi.org/10.48550/arXiv.2212.09573) | International Joint Conference on Natural Language Processing | [GitHub](https://github.com/awslabs/privacy-adhering-machine-unlearning-nlp) | 46 |
| Christian Ganhör et al. | [Unlearning Protected User Attributes in Recommendations with Adversarial Training](https://doi.org/10.1145/3477495.3531820) | SIGIR | [GitHub](https://github.com/CPJKU/adv-multvae) | 44 |
| Chao Pan et al. | [Machine Unlearning of Federated Clusters](https://doi.org/10.48550/arXiv.2210.16424) | ICLR | [GitHub](https://github.com/thupchnsky/mufc) | 43 |
| Thorsten Eisenhofer et al. | [Verifiable and Provably Secure Machine Unlearning](https://doi.org/10.1109/SaTML64287.2025.00033) | SaTML | [GitHub](https://github.com/cleverhans-lab/verifiable-unlearning) | 42 |
| Ga Wu, Masoud Hashemi, Christopher Srinivasa | [PUMA: Performance Unchanged Model Augmentation for Training Data Removal](https://doi.org/10.1609/aaai.v36i8.20846) | AAAI | — | 41 |
| Junyaup Kim, Simon S. Woo | [Efficient Two-stage Model Retraining for Machine Unlearning](https://doi.org/10.1109/cvprw56347.2022.00482) | CVPR | [GitHub](https://github.com/DASH-Lab/ML_privacy_research) | 40 |
| Ryutaro Tanno et al. | [Repairing Neural Networks by Leaving the Right Past Behind](https://doi.org/10.48550/arXiv.2207.04806) | NeurIPS | [GitHub](https://github.com/tejasr20/CS772-project) | 40 |
| Shaopeng Fu, Fengxiang He, Dacheng Tao | [Knowledge Removal in Sampling-based Bayesian Inference](https://doi.org/10.48550/arXiv.2203.12964) | ICLR | [GitHub](https://github.com/fshp971/mcmc-unlearning) | 37 |
| Changsong Yang et al. | [Provable data deletion from efficient data integrity auditing and insertion in cloud storage](https://doi.org/10.1016/j.csi.2022.103629) | Computer Standards & Interfaces | — | 35 |
| Jiguo Li et al. | [Multiauthority Attribute-Based Encryption for Assuring Data Deletion](https://doi.org/10.1109/jsyst.2022.3208149) | IEEE Systems Journal | — | 33 |
| Qian Mei et al. | [Expressive Data Sharing and Self-Controlled Fine-Grained Data Deletion in Cloud-Assisted IoT](https://doi.org/10.1109/tdsc.2022.3188740) | IEEE TDSC | — | 32 |
| Yann Fraboni et al. | [SIFU: Sequential Informed Federated Unlearning for Efficient and Provable Client Unlearning in Federated Optimization](https://arxiv.org/abs/2211.11656) | AISTATS | — | 29 |
| Quoc Phong Nguyen et al. | [Markov Chain Monte Carlo-Based Machine Unlearning](https://doi.org/10.1145/3488932.3517406) | CCS | [GitHub](https://github.com/egstatsml/arxivsearch) | 28 |
| Tao Guo et al. | [Efficient Attribute Unlearning: Towards Selective Removal of Input Attributes from Feature Representations](https://arxiv.org/abs/2202.13295) | ACM Trans. Inf. Syst | — | 27 |
| Jiasi Weng et al. | [Proof of Unlearning: Definitions and Instantiation](https://doi.org/10.1109/TIFS.2024.3358993) | IEEE T-IFS | [GitHub](https://github.com/jjbrophy47/machine_unlearning) | 27 |
| Zhaobo Lu et al. | [Label‐only membership inference attacks on machine unlearning without dependence of posteriors](https://doi.org/10.1002/int.23000) | International Journal of Intelligent Systems | — | 25 |
| Youngsik Yoon et al. | [Few-Shot Unlearning by Model Inversion](https://doi.org/10.48550/arXiv.2205.15567) | arXiv | — | 25 |
| Gaurav Bansal, Fiona Fui‐Hoon Nah | [Internet Privacy Concerns Revisited: Oversight from Surveillance and Right To Be Forgotten as New Dimensions](https://doi.org/10.1016/j.im.2022.103618) | Information & Management | — | 24 |
| Christopher A. Kearney, Patricia A. Graczyk | [Multi-tiered systems of support for school attendance and its problems: An unlearning perspective for areas of high chronic absenteeism](https://doi.org/10.3389/feduc.2022.1020150) | Frontiers in Education | — | 23 |
| Ji Gao et al. | [Deletion inference, reconstruction, and compliance in machine (un)learning](https://doi.org/10.56553/popets-2022-0079) | PoPETs | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 21 |
| Marco Benedetti et al. | [Supervised perceptron learning vs unsupervised Hebbian unlearning: Approaching optimal memory retrieval in Hopfield-like networks](https://doi.org/10.1063/5.0084219) | The Journal of Chemical Physics | — | 21 |
| Yann Fraboni et al. | [Sequential Informed Federated Unlearning: Efficient and Provable Client Unlearning in Federated Optimization](https://doi.org/10.48550/arXiv.2211.11656) | arXiv | — | 21 |
| Graham H. Diering | [Remembering and forgetting in sleep: Selective synaptic plasticity during sleep driven by scaling factors Homer1a and Arc](https://doi.org/10.1016/j.ynstr.2022.100512) | Neurobiology of Stress | — | 20 |
| Salvatore Mercuri et al. | [An Introduction to Machine Unlearning](https://doi.org/10.48550/arXiv.2209.00939) | arXiv | [GitHub](https://github.com/susiesyli/Machine-Unlearning-Papers) | 20 |
| Shashwat Goel, Ameya Prabhu, P. Kumaraguru | [Evaluating Inexact Unlearning Requires Revisiting Forgetting](https://www.semanticscholar.org/paper/d98484eac2c42e54585a3b09c7ed85c920548120) | arXiv | — | 20 |
| Zhifeng Kong, Kamalika Chaudhuri | [Data Redaction from Pre-trained GANs](https://doi.org/10.1109/SaTML54575.2023.00048) | SaTML | [GitHub](https://github.com/sbaresearch/GenAI-IP-protection) | 19 |
| Yun Zhang et al. | [‘A right to be forgotten’: retrospective privacy concerns in social networking services](https://doi.org/10.1080/0144929x.2022.2046162) | Behaviour and Information Technology | — | 16 |
| Jiamin Fan et al. | [Fast Model Update for IoT Traffic Anomaly Detection With Machine Unlearning](https://doi.org/10.1109/jiot.2022.3214840) | IEEE IoT-J | — | 15 |
| Changsong Yang, Yueling Liu, Yong Ding | [Efficient data transfer supporting provable data deletion for secure cloud storage](https://doi.org/10.1007/s00500-022-07116-6) | Soft Computing | — | 15 |
| Peng-Fei Zhang et al. | [Machine Unlearning for Image Retrieval](https://doi.org/10.1145/3503161.3548378) | ACM MM | [GitHub](https://github.com/sduzpf/Machine-Unlearning-for-Image-Retrieval-A-Generative-Scrubbing-Approach) | 14 |
| Jinu Gong, Osvaldo Simeone, Joonhyuk Kang | [Compressed Particle-Based Federated Bayesian Learning and Unlearning](https://doi.org/10.1109/lcomm.2022.3223655) | IEEE Communications Letters | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 12 |
| Teguh Cahya Yudiana, Sinta Dewi Rosadi, Enni Soerjati Priowirjanto | [The Urgency of Doxing on Social Media Regulation and the Implementation of Right to Be Forgotten on Related Content for the Optimization of Data Privacy Protection in Indonesia](https://doi.org/10.22304/pjih.v9n1.a2) | Padjadjaran | — | 12 |
| Dillon H. Murphy, Alan D. Castel | [Selective remembering and directed forgetting are influenced by similar stimulus properties](https://doi.org/10.1080/09658211.2022.2092152) | Memory | — | 11 |
| Sihao Yu et al. | [LegoNet: A Fast and Exact Unlearning Architecture](https://doi.org/10.48550/arXiv.2210.16023) | arXiv | — | 11 |
| Wenyan Liu et al. | [Forgetting Fast in Recommender Systems](https://doi.org/10.48550/arXiv.2208.06875) | arXiv | [GitHub](https://github.com/chenchongthu/ENMF) | 11 |
| Ananth Mahadevan, Michael Mathioudakis | [Certifiable Unlearning Pipelines for Logistic Regression: An Experimental Study](https://doi.org/10.3390/make4030028) | Machine Learning and Knowledge Extraction | — | 10 |
| Kejsi Take et al. | [“It Feels Like Whack-a-mole”: User Experiences of Data Removal from People Search Websites](https://doi.org/10.56553/popets-2022-0067) | PoPETs | — | 9 |
| Weijun Qian et al. | [Patient Similarity Learning with Selective Forgetting](https://doi.org/10.1109/bibm55620.2022.9995016) | BIBM | — | 8 |
| Zihao Cao et al. | [Machine Unlearning Method Based On Projection Residual](https://doi.org/10.1109/dsaa54385.2022.10032413) | DSAA | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 8 |
| Zhifeng Kong, Scott Alfeld | [Approximate Data Deletion in Generative Models](https://doi.org/10.48550/arXiv.2206.14439) | European Conference on Artificial Intelligence | [GitHub](https://github.com/aaron-xichen/pytorch-playground) | 8 |
| Qi Zhong et al. | [Attention Distraction: Watermark Removal Through Continual Learning with Selective Forgetting](https://doi.org/10.1109/icme52920.2022.9858930) | ICME | [GitHub](https://github.com/20110240069/Watermark-Learning-Resources) | 8 |
| Ben Wang, Sebastian Schelter | [Efficiently Maintaining Next Basket Recommendations under Additions and Deletions of Baskets and Items](https://arxiv.org/abs/2201.13313) | arXiv | [GitHub](https://github.com/0xeeff/amnesiac_recsys) | 8 |
| Yassine El Khanboubi, Mostafa Hanoune, Mohamed El Ghazouani | [A New Data Deletion Scheme for a Blockchain-based De-duplication System in the Cloud](https://doi.org/10.17762/ijcnis.v13i2.4975) | IJCNIS | — | 7 |
| Zhifeng Kong, Amrita Roy Chowdhury, Kamalika Chaudhuri | [Forgeability and Membership Inference Attacks](https://doi.org/10.1145/3560830.3563731) | AISec@CCS | — | 6 |
| Tiffany Li | [Algorithmic Destruction](https://doi.org/10.25172/smulr.75.3.2) | SMU Law Review | — | 6 |
| Zhiwen Zhou et al. | [Dynamically Selected Mixup Machine Unlearning](https://doi.org/10.1109/TrustCom56396.2022.00077) | TrustCom | — | 6 |
| Amr Osman | [The Right to be Forgotten: an Islamic Perspective](https://doi.org/10.1007/s12142-022-00672-2) | Human Rights Review | — | 5 |
| Zhengming Zhang et al. | [Poison Neural Network-Based mmWave Beam Selection and Detoxification With Machine Unlearning](https://doi.org/10.1109/tcomm.2022.3232794) | IEEE Transactions on Communications | — | 5 |
| Xianjia Meng et al. | [Active forgetting via influence estimation for neural networks](https://doi.org/10.1002/int.22981) | International Journal of Intelligent Systems | — | 5 |
| Yiwen Jiang et al. | [Machine unlearning survey](https://doi.org/10.1117/12.2660330) | MCTE | [GitHub](https://github.com/jessecu2024/unlearningsurvey) | 5 |
| Andreea Stamate et al. | [The effect of selective retrieval practice on forgetting rates in younger and older adults.](https://doi.org/10.1037/pag0000691) | Psychology and Aging | — | 5 |
| Stephen R. Griffiths et al. | [“Set and forget” does not work when it comes to fissure roosts carved into live trees for bats](https://doi.org/10.1111/rec.13751) | Restoration Ecology | — | 5 |
| Rodrigo Cetina Presuel, Fernando Gutiérrez Atala | [The Limits of Memory and the News: Archival Journalism, Law, Ethics, and the Right to be Forgotten](https://doi.org/10.26441/rc21.1-2022-a4) | Revista de Comunicación | — | 5 |
| Chao Pan, Eli Chien, O. Milenkovic | [Unlearning Nonlinear Graph Classifiers in the Limited Training Data Regime](https://doi.org/10.48550/arXiv.2211.03216) | arXiv | [GitHub](https://github.com/thupchnsky/sgc_unlearn) | 5 |
| Martin Mach | [Streisand Effect in the Context of the Right to be Forgotten](https://doi.org/10.2478/eustu-2022-0005) | European Studies. The Review of European Law, Economics and Politics | — | 4 |
| Bernhard Pastötter, Céline C. Haciahmet | [Can People Intentionally and Selectively Forget Prose Material?](https://doi.org/10.3389/fpsyg.2022.928533) | Frontiers in Psychology | — | 4 |
| Joshua Stock et al. | [Property Unlearning: A Defense Strategy Against Property Inference Attacks](https://doi.org/10.48550/arXiv.2205.08821) | arXiv | — | 4 |
| Junfeng Tian, Ruxin Bai, Tianfeng Zhang | [Multi-authoritative Users Assured Data Deletion Scheme in Cloud Computing](https://doi.org/10.1109/dsn-w54100.2022.00033) | DSN-W | — | 3 |
| E. S. Chub | [The right to be forgotten: A new human right?](https://doi.org/10.38044/2686-9136-2022-3-4-89-106) | Digital Law Journal | — | 3 |
| Pravendra Singh, Pratik Mazumder, Mohammed Asad Karim | [Attaining Class-level Forgetting in Pretrained Model using Few Samples](https://doi.org/10.48550/arXiv.2210.10670) | ECCV | — | 3 |
| Alexander Becker, T. Liebig | [Certified Data Removal in Sum-Product Networks](https://doi.org/10.1109/ICKG55886.2022.00010) | ICKG | [GitHub](https://github.com/ROYALBEFF/UnlearnSPN) | 3 |
| Zheng-Yu Yue et al. | [ATDD: Fine-Grained Assured Time-Sensitive Data Deletion Scheme in Cloud Storage](https://doi.org/10.1109/icc45855.2022.9838336) | ICC | — | 2 |
| Vinith Suriyakumar, Ashia Wilson | [Algorithms that Approximate Data Removal: New Results and Limitations](https://doi.org/10.52202/068431-1372) | NeurIPS | [GitHub](https://github.com/VMS-6511/online-data-deletion) | 2 |
| Zhiwen Zhou et al. | [Dynamically Selected Mixup Machine Unlearning](https://doi.org/10.1109/trustcom56396.2022.00077) | TrustCom | — | 2 |
| Geraldine O. Mbah | [Data privacy and the right to be forgotten](https://doi.org/10.30574/wjarr.2022.16.2.1079) | World Journal of Advanced Research and Reviews | [GitHub](https://github.com/Kaiboy55/MLForget) | 2 |
| Alicia M. Pike Lacy, Kenneth C. Lam, Cailee E. Welch Bacon | [Addressing the Habitual Practice Issue: The Role of Unlearning in Promoting Evidence-Based Practice and Lifelong Learning](https://doi.org/10.4085/1947-380x-21-050) | Athletic Training Education Journal | — | 1 |
| J. Gong et al. | [Forget-SVGD: Particle-Based Bayesian Federated Unlearning](https://doi.org/10.1109/dslw53931.2022.9820602) | DSLW | — | 1 |
| Kawa Qambar Aziz, Baban A. Mahmood | [Assured data deletion in cloud computing: security analysis and requirements](https://doi.org/10.11591/ijeecs.v28.i2.pp1174-1183) | Indonesian Journal of Electrical Engineering and Computer Science | — | 1 |
| Tianshi Che et al. | [Prompt Certified Machine Unlearning with Randomized Gradient Smoothing and Quantization](https://doi.org/10.52202/068431-0977) | NeurIPS | — | 1 |

## 2021

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Lucas Bourtoule et al. | [Machine Unlearning](https://doi.org/10.1109/sp40001.2021.00019) | arXiv | — | 564 |
| Ayush Sekhari et al. | [Remember What You Want to Forget: Algorithms for Machine Unlearning](https://arxiv.org/abs/2103.03279) | NeurIPS | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 443 |
| Anvith Thudi et al. | [Unrolling SGD: Understanding Factors Influencing Machine Unlearning](https://doi.org/10.1109/EuroSP53844.2022.00027) | European Symposium on Security and Privacy | [GitHub](https://github.com/OngWinKent/MachineUnlearning) | 308 |
| A. Tarun et al. | [Fast Yet Effective Machine Unlearning](https://doi.org/10.1109/TNNLS.2023.3266233) | IEEE TNNLS | [GitHub](https://github.com/vikram2000b/Fast-Machine-Unlearning) | 299 |
| Alexander Warnecke et al. | [Machine Unlearning of Features and Labels](https://doi.org/10.14722/ndss.2023.23087) | NDSS | [GitHub](https://github.com/alewarne/MachineUnlearning) | 299 |
| Gaoyang Liu et al. | [FedEraser: Enabling Efficient Client-Level Data Removal from Federated Learning Models](https://doi.org/10.1109/IWQOS52092.2021.9521274) | International Workshop on Quality of Service | — | 254 |
| Varun Gupta et al. | [Adaptive Machine Unlearning](https://arxiv.org/abs/2106.04378) | NeurIPS | [GitHub](https://github.com/Simoni2412/Machine-Unlearning) | 235 |
| Anvith Thudi et al. | [On the Necessity of Auditable Algorithmic Definitions for Machine Unlearning](https://arxiv.org/abs/2110.11891) | USENIX Security | [GitHub](https://github.com/cleverhans-lab/Forging) | 221 |
| Gaoyang Liu et al. | [FedEraser: Enabling Efficient Client-Level Data Removal from Federated Learning Models](https://doi.org/10.1109/iwqos52092.2021.9521274) | IWQoS | — | 183 |
| Enayat Ullah et al. | [Machine Unlearning via Algorithmic Stability](https://arxiv.org/abs/2102.13179) | Annual Conference Computational Learning Theory | — | 152 |
| Min Chen et al. | [When Machine Unlearning Jeopardizes Privacy](https://doi.org/10.1145/3460120.3484756) | CCS | [GitHub](https://github.com/MinChen00/UnlearningLeaks) | 148 |
| Feng Zhang, Lei Zhu | [Social media strategic capability, organizational unlearning, and disruptive innovation of SMEs: The moderating roles of TMT heterogeneity and environmental dynamism](https://doi.org/10.1016/j.jbusres.2021.04.071) | Journal of Business Research | — | 144 |
| Daniel Orth, Philipa Maria Schuldis | [Organizational learning and unlearning capabilities for resilience during COVID-19](https://doi.org/10.1108/tlo-07-2020-0130) | The Learning Organization | — | 92 |
| Chongchong Lyu et al. | [Competitive intensity and new product development outcomes: The roles of knowledge integration and organizational unlearning](https://doi.org/10.1016/j.jbusres.2021.09.049) | Journal of Business Research | — | 87 |
| Sebastian Schelter, Stefan Grafberger, Ted Dunning | [HedgeCut: Maintaining Randomised Trees for Low-Latency Machine Unlearning](https://doi.org/10.1145/3448016.3457239) | SIGMOD Conference | [GitHub](https://github.com/schelterlabs/hedgecut) | 78 |
| Ananth Mahadevan, M. Mathioudakis | [Certifiable Machine Unlearning for Linear Models](https://arxiv.org/abs/2106.15093) | arXiv | [GitHub](https://github.com/testc2/unlearning-experiments) | 57 |
| Juan‐Gabriel Cegarra‐Navarro et al. | [Minimizing the effects of defensive routines on knowledge hiding though unlearning](https://doi.org/10.1016/j.jbusres.2021.08.021) | Journal of Business Research | — | 46 |
| Alexandra Peste, Dan Alistarh, Christoph H. Lampert | [SSSE: Efficiently Erasing Samples from Trained Machine Learning Models](https://arxiv.org/abs/2107.03860) | arXiv | — | 39 |
| Takashi Shibata et al. | [Learning with Selective Forgetting](https://doi.org/10.24963/ijcai.2021/137) | IJCAI | [GitHub](https://github.com/nttcslab/Learning-with-Selective-Forgetting) | 36 |
| Quang-Vinh Dang | [Right to Be Forgotten in the Age of Machine Learning](https://doi.org/10.1007/978-3-030-71782-7_35) | Advances in Intelligent Systems and Computing | — | 35 |
| Eugenio Balistri et al. | [BlockHealth: Blockchain-based secure and peer-to-peer health information sharing with data protection and right to be forgotten](https://doi.org/10.1016/j.icte.2021.08.006) | ICT Express | — | 35 |
| Yingzhe He et al. | [DeepObliviate: A Powerful Charm for Erasing Data Residual Memory in Deep Neural Networks](https://arxiv.org/abs/2105.06209) | arXiv | — | 34 |
| Min Chen et al. | [When Machine Unlearning Jeopardizes Privacy](https://doi.org/10.60882/cispa.24613773.v1) | Figshare | [GitHub](https://github.com/moondayc/unFL_Leaks) | 32 |
| Yin Jun | [Effects of the paradox mindset on work engagement: The mediating role of seeking challenges and individual unlearning](https://doi.org/10.1007/s12144-021-01597-8) | Current Psychology | — | 31 |
| Feng Zhang, Chongchong Lyu, Lei Zhu | [Organizational unlearning, knowledge generation strategies and radical innovation performance: evidence from a transitional economy](https://doi.org/10.1108/ejm-10-2019-0756) | European Journal of Marketing | — | 31 |
| Shubham Sharma, Usha Lenka | [On the shoulders of giants: uncovering key themes of organizational unlearning research in mainstream management journals](https://doi.org/10.1007/s11846-021-00492-7) | Review of Managerial Science | — | 31 |
| George Christou, Imir Rashid | [Interest group lobbying in the European Union: privacy, data protection and the right to be forgotten](https://doi.org/10.1057/s41295-021-00238-5) | Comparative European Politics | — | 27 |
| Eun Jee Kim, Sunyoung Park | [Unlearning in the workplace: Antecedents and outcomes](https://doi.org/10.1002/hrdq.21457) | Human Resource Development Quarterly | — | 27 |
| Nasser Aldaghri, Hessam Mahdavifar, Ahmad Beirami | [Coded Machine Unlearning](https://doi.org/10.1109/access.2021.3090019) | IEEE Access | — | 27 |
| Jun Ma et al. | [CP-ABE-Based Secure and Verifiable Data Deletion in Cloud](https://doi.org/10.1155/2021/8855341) | Security and Communication Networks | — | 23 |
| Atif Açıkgöz et al. | [The Relationship Between Unlearning and Innovation Ambidexterity with the Performance of New Product Development Teams](https://doi.org/10.1007/s10726-021-09743-0) | Group Decision and Negotiation | — | 18 |
| Vitaly Shaferman et al. | [Continuous-time least-squares forgetting algorithms for indirect adaptive control](https://doi.org/10.1016/j.ejcon.2021.06.015) | European Journal of Control | — | 17 |
| Yangsibo Huang, Xiaoxiao Li, Kai Li | [EMA: Auditing Data Removal from Trained Models](https://doi.org/10.1007/978-3-030-87240-3_76) | MICCAI | [GitHub](https://github.com/Hazelsuko07/EMA) | 16 |
| Hovsep Kocharyan et al. | [Critical Views on the Right to Be Forgotten After the Entry Into Force of the GDPR: Is it Able to Effectively Ensure Our Privacy?](https://doi.org/10.2478/iclr-2021-0015) | Mezinárodní a srovnávací právní revue/International and Comparative Law Review | — | 15 |
| Sungyong Baik et al. | [Learning to Forget for Meta-Learning via Task-and-Layer-Wise Attenuation](https://doi.org/10.1109/tpami.2021.3102098) | IEEE TPAMI | — | 14 |
| David Erdos | [The ‘right to be forgotten’ beyond the EU: an analysis of wider G20 regulatory action and potential next steps](https://doi.org/10.1080/17577632.2021.1884947) | Journal of Media Law | — | 14 |
| Seven Ağır, Cihan Artunç | [Set and Forget? The Evolution of Business Law in the Ottoman Empire and Turkey](https://doi.org/10.1017/s000768052000094x) | The Business History Review | — | 14 |
| Mónica Correia, Guilhermina Rêgo, Rui Nunes | [The Right to Be Forgotten and COVID-19: Privacy versus Public Interest](https://doi.org/10.4067/s1726-569x2021000100059) | Acta bioethica | — | 13 |
| Mónica Correia, Guilhermina Rêgo, Rui Nunes | [Gender Transition: Is There a Right to Be Forgotten?](https://doi.org/10.1007/s10728-021-00433-1) | Health Care Analysis | — | 13 |
| Shaopeng Fu et al. | [Bayesian Inference Forgetting](https://arxiv.org/abs/2101.06417) | arXiv | [GitHub](https://github.com/fshp971/BIF) | 12 |
| Shubham Sharma, Usha Lenka | [Counterintuitive, Yet Essential: Taking Stock of Organizational Unlearning Research Through a Scientometric Analysis (1976-2019)](https://doi.org/10.1080/14778238.2021.1943553) | Knowledge Management Research & Practice | — | 11 |
| Cristián Candia, Brian Uzzi | [Quantifying the selective forgetting and integration of ideas in science and technology.](https://doi.org/10.1037/amp0000863) | American Psychologist | — | 10 |
| Elizabeth Stainforth | [Collective memory or the right to be forgotten? Cultures of digital memory and forgetting in the European Union](https://doi.org/10.1177/17506980211044707) | Memory Studies | — | 10 |
| Kongyang Chen, Yao Huang, Yiwen Wang | [Machine unlearning via GAN](https://arxiv.org/abs/2111.11869) | arXiv | — | 10 |
| Juan J. Imbernón, Carmen Aguirre, Carlos J. Gómez‐Ariza | [Selective directed forgetting is mediated by the lateral prefrontal cortex: Preliminary evidence with transcranial direct current stimulation](https://doi.org/10.1080/17588928.2021.1953973) | Cognitive Neuroscience | — | 9 |
| Daniel Felps et al. | [Class Clown: Data Redaction in Machine Unlearning at Enterprise Scale](https://doi.org/10.5220/0010419600070014) | International Conference on Operations Research and Enterprise Systems | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 9 |
| Sharu Theresa Jose, O. Simeone | [A Unified PAC-Bayesian Framework for Machine Unlearning via Information Risk Minimization](https://doi.org/10.1109/mlsp52302.2021.9596170) | International Workshop on Machine Learning for Signal Processing | — | 9 |
| Kongyang Chen, Yiwen Wang, Yao Huang | [Lightweight machine unlearning in neural network](https://arxiv.org/abs/2111.05528) | arXiv | — | 9 |
| Zachary Izzo et al. | [Approximate Data Deletion from Machine Learning Models](https://openalex.org/W3158390351) | AISTATS | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 8 |
| Kamrul Faisal | [Balancing between Right to Be Forgotten and Right to Freedom of Expression in Spent Criminal Convictions](https://doi.org/10.1002/spy2.157) | Security and Privacy | — | 8 |
| Kunle Oparinde | [Postgraduate Supervision: A Heuristic Approach to Learning, Unlearning, and Relearning](https://doi.org/10.24191/ajue.v17i4.16202) | Asian Journal of University Education | — | 7 |
| Markus Schmidt, Christian Frings, Tobias Tempel | [Selective directed forgetting of motor sequences](https://doi.org/10.1016/j.actpsy.2021.103352) | Acta Psychologica | — | 6 |
| Aman Tahiliani et al. | [Machine Unlearning: Its Need and Implementation Strategies](https://doi.org/10.1145/3474124.3474158) | International Conference on Contemporary Computing | — | 5 |
| Olha Sovhyria, Yuliia Reminska | [The right to be forgotten: remarks about its constitutional «canvas»](https://doi.org/10.30970/jcl.3.2021.2) | Ukrainian Journal of Constitutional Law | — | 5 |
| Carsten M. Wulff | [The Right to be Forgotten in Post-Google Spain Case Law: an Example of Legal Interpretivism in Action?](https://doi.org/10.12775/clr.2020.010) | Comparative Law Review | — | 4 |
| Jinu Gong, Osvaldo Simeone, Joonhyuk Kang | [Bayesian Variational Federated Learning and Unlearning in Decentralized Networks](https://doi.org/10.1109/spawc51858.2021.9593225) | International Workshop on Signal Processing Advances in Wireless Communications | [GitHub](https://github.com/abbottyanginchina/Awesome-Federated-Unlearning) | 4 |
| Adit Goyal, Vikas Hassija, V. Albuquerque | [Revisiting Machine Learning Training Process for Enhanced Data Privacy](https://doi.org/10.1145/3474124.3474208) | International Conference on Contemporary Computing | — | 3 |
| Nishchal Parne et al. | [An Investigation on Learning, Polluting, and Unlearning the Spam Emails for Lifelong Learning](https://arxiv.org/abs/2111.14609) | arXiv | — | 3 |
| Yassine El Khanboubi, Mostafa Hanoune, Mohamed El Ghazouani | [A New Data Deletion Scheme for a Blockchain-based De-duplication System in the Cloud](https://doi.org/10.54039/ijcnis.v13i2.4975) | Int. J. Commun. Networks Inf. Secur | — | 2 |
| Hyungchan Kim et al. | [Data Deletion and Recovery of Androd Plaforms](https://doi.org/10.1109/csci54926.2021.00171) | CSCI | — | 1 |
| Nishchal Parne et al. | [Machine Unlearning: Learning, Polluting, and Unlearning for Spam Email](https://www.semanticscholar.org/paper/d7cc0015257bba726fbad0dad210932ebb773ec6) | arXiv | — | 1 |
| J. Sengewald, R. Lackes | [The Impact of the 'Right to Be Forgotten' on Algorithmic Fairness](https://doi.org/10.1007/978-3-030-87205-2_14) | International Workshop on Bibliometric-enhanced Information Retrieval | — | 0 |

## 2020

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Laura Graves, Vineel Nagisetty, Vijay Ganesh | [Amnesiac Machine Learning](https://doi.org/10.1609/aaai.v35i13.17371) | AAAI | [GitHub](https://github.com/lmgraves/AmnesiacML) | 413 |
| Seth Neel, Aaron Roth, Saeed Sharifi-Malvajerdi | [Descent-to-Delete: Gradient-Based Methods for Machine Unlearning](https://arxiv.org/abs/2007.02923) | ALT | [GitHub](https://github.com/safr-ai-lab/survey-llm) | 377 |
| Zachary Izzo et al. | [Approximate Data Deletion from Machine Learning Models: Algorithms and Evaluations](https://arxiv.org/abs/2002.10077) | AISTATS | [GitHub](https://github.com/tamlhp/awesome-machine-unlearning) | 355 |
| Bianca van Laun | [Ariella Aïsha Azoulay, Potential History: Unlearning Imperialism (London: Verso, 2019), 656 pp, ISBN 9781788735711](https://doi.org/10.17159/2309-9585/2020/v46a15) | Kronos | — | 274 |
| Yinjun Wu, Edgar Dobriban, S. Davidson | [DeltaGrad: Rapid retraining of machine learning models](https://arxiv.org/abs/2006.14755) | ICML | [GitHub](https://github.com/wuyinjun-1993/DeltaGrad) | 262 |
| Aditya Golatkar, A. Achille, Stefano Soatto | [Forgetting Outside the Box: Scrubbing Deep Networks of Information Accessible from Input-Output Observations](https://doi.org/10.1007/978-3-030-58526-6_23) | ECCV | — | 244 |
| Aditya Golatkar et al. | [Mixed-Privacy Forgetting in Deep Networks](https://doi.org/10.1109/CVPR46437.2021.00085) | CVPR | [GitHub](https://github.com/52CV/CVPR-2021-Papers) | 218 |
| Quoc Phong Nguyen, Bryan Kian Hsiang Low, Patrick Jaillet | [Variational Bayesian Unlearning](https://arxiv.org/abs/2010.12883) | NeurIPS | [GitHub](https://github.com/Mahanth-Maha/Unlearn) | 175 |
| Nicola K. Dinsdale, Mark Jenkinson, Ana I. L. Namburete | [Deep learning-based unlearning of dataset bias for MRI harmonisation and confound removal](https://doi.org/10.1016/j.neuroimage.2020.117689) | NeuroImage | — | 172 |
| Huihui Liu, Yiding Yang, Xinchao Wang | [Overcoming Catastrophic Forgetting in Graph Neural Networks](https://doi.org/10.1609/aaai.v35i10.17049) | AAAI | [GitHub](https://github.com/hhliu79/TWP) | 166 |
| Luke Urbain | [Potential History: Unlearning Imperialism](https://doi.org/10.47761/494a02f6.9532de85) | InVisible Culture | [GitHub](https://github.com/SGSSSonline/Archives-for-Justice) | 160 |
| Hana Habib et al. | ["It's a scavenger hunt": Usability of Websites' Opt-Out and Data Deletion Choices](https://doi.org/10.1145/3313831.3376511) | CHI | — | 107 |
| Christine Coombe, Hossein Vafadar, Hassan Mohebbi | [Language assessment literacy: what do we need to learn, unlearn, and relearn?](https://doi.org/10.1186/s40468-020-00101-6) | Language Testing in Asia | — | 106 |
| Sanjam Garg, S. Goldwasser, Prashant Nalini Vasudevan | [Formalizing Data Deletion in the Context of the Right to Be Forgotten](https://doi.org/10.1007/978-3-030-45724-2_13) | IACR Cryptology ePrint Archive | — | 96 |
| Yang Liu et al. | [Learn to Forget: Machine Unlearning via Neuron Masking](https://doi.org/10.1109/TDSC.2022.3194884) | IEEE TDSC | [GitHub](https://github.com/hendrycks/error-detection/tree) | 88 |
| D. Sommer et al. | [Towards Probabilistic Verification of Machine Unlearning](https://arxiv.org/abs/2003.04247) | arXiv | [GitHub](https://github.com/TouchSky-Lab/Awesome-Memorization-Elimination) | 83 |
| Gaoyang Liu et al. | [Federated Unlearning](https://arxiv.org/abs/2012.13891) | arXiv | — | 79 |
| Irina Surdu, Rajneesh Narula | [Organizational learning, unlearning and re-internationalization timing: Differences between emerging- versus developed-market MNEs](https://doi.org/10.1016/j.intman.2020.100784) | Journal of International Management | — | 77 |
| Rasha Kashef | [A boosted SVM classifier trained by incremental learning and decremental unlearning approach](https://doi.org/10.1016/j.eswa.2020.114154) | Expert Systems with Applications | — | 72 |
| Sam C. Berens, Blake A. Richards, Aidan J. Horner | [Dissociating memory accessibility and precision in forgetting](https://doi.org/10.1038/s41562-020-0888-8) | Nature Human Behaviour | — | 63 |
| Marie-Christin Fellner, Gerd T. Waldhauser, Nikolai Axmacher | [Tracking Selective Rehearsal and Active Inhibition of Memory Traces in Directed Forgetting](https://doi.org/10.1016/j.cub.2020.04.091) | Current Biology | — | 59 |
| George Burt, Anup Karath Nair | [Rigidities of imagination in scenario planning: Strategic foresight through ‘Unlearning’](https://doi.org/10.1016/j.techfore.2020.119927) | Technological Forecasting and Social Change | — | 57 |
| Hana Habib et al. | [An Empirical Analysis of Data Deletion and Opt-Out Choices on 150 Websites](https://doi.org/10.1184/r1/13050419) | Figshare | — | 50 |
| Jure Globočnik | [The Right to Be Forgotten is Taking Shape: CJEU Judgments in GC and Others (C-136/17) and Google v CNIL (C-507/17)](https://doi.org/10.1093/grurint/ikaa002) | GRUR International | — | 48 |
| Nasser Aldaghri, Hessam Mahdavifar, Ahmad Beirami | [Coded Machine Unlearning](https://doi.org/10.1109/ACCESS.2021.3090019) | IEEE Access | — | 48 |
| Yinjun Wu, V. Tannen, S. Davidson | [PrIU: A Provenance-Based Approach for Incrementally Updating Regression Models](https://doi.org/10.1145/3318464.3380571) | SIGMOD Conference | — | 43 |
| Dirk Martignoni, Thomas Keil | [It did not work? Unlearn and try again—Unlearning success and failure beliefs in changing environments](https://doi.org/10.1002/smj.3261) | Strategic Management Journal | — | 37 |
| Yingxin Zhao, Xiangyang Wang | [Organisational unlearning, relearning and strategic flexibility: from the perspective of updating routines and knowledge](https://doi.org/10.1080/09537325.2020.1758656) | Technology Analysis and Strategic Management | — | 37 |
| Kim McLeod et al. | [Principles for a pedagogy of unlearning](https://doi.org/10.1080/14623943.2020.1730782) | Reflective Practice | — | 36 |
| Thomas Grisold, Adrian Klammer, Florian Kragulj | [Two forms of organizational unlearning: Insights from engaged scholarship research with change consultants](https://doi.org/10.1177/1350507620916042) | Management Learning | — | 35 |
| Vincenzo Mangini, Irina Tal, Arghir-Nicolae Moldovan | [An empirical study on the impact of GDPR and right to be forgotten - organisations and users perspective](https://doi.org/10.1145/3407023.3407080) | ARES | — | 34 |
| Federico Fabbrini, Edoardo Celeste | [The Right to Be Forgotten in the Digital Age: The Challenges of Data Protection Beyond Borders](https://doi.org/10.1017/glj.2020.14) | German Law Journal | — | 33 |
| Roman Kmieciak | [Critical reflection and innovative work behavior: the mediating role of individual unlearning](https://doi.org/10.1108/pr-10-2018-0406) | Personnel Review | — | 30 |
| Sebastian Schelter | ["Amnesia" - Machine Learning Models That Can Forget User Data Very Fast](https://www.semanticscholar.org/paper/4e99e7af4b9f08b0a89577cd8ea92a37d4744e1e) | Conference on Innovative Data Systems Research | — | 29 |
| Changsong Yang et al. | [Publicly Verifiable and Efficient Fine-Grained Data Deletion Scheme in Cloud Computing](https://doi.org/10.1109/access.2020.2997351) | IEEE Access | — | 29 |
| Grazia Scocca, Françoise Meunier | [A right to be forgotten for cancer survivors: A legal development expected to reflect the medical progress in the fight against cancer](https://doi.org/10.1016/j.jcpo.2020.100246) | Journal of Cancer Policy | — | 29 |
| Xiao Liu, S. Tsaftaris | [Have you forgotten? A method to assess if machine learning models have forgotten data](https://doi.org/10.1007/978-3-030-59710-8_10) | MICCAI | — | 29 |
| Yuantong Li, ChiHua Wang, Guang Cheng | [Online Forgetting Process for Linear Regression Models](https://arxiv.org/abs/2012.01668) | AISTATS | — | 28 |
| N. Dinsdale, M. Jenkinson, A. Namburete | [Unlearning Scanner Bias for MRI Harmonisation in Medical Image Segmentation](https://doi.org/10.1007/978-3-030-52791-4_2) | Annual Conference on Medical Image Understanding and Analysis | — | 28 |
| Pelin Tan et al. | [In support of selective rehearsal: Double-item presentation in item-method directed forgetting](https://doi.org/10.3758/s13423-020-01723-w) | Psychonomic Bulletin & Review | — | 27 |
| Keltie Haley | [Sharenting and the (Potential) Right to Be Forgotten](https://openalex.org/W3032567077) | Indiana law journal | — | 26 |
| Dong Zheng et al. | [Toward Assured Data Deletion in Cloud Storage](https://doi.org/10.1109/mnet.011.1900165) | IEEE Network | — | 23 |
| Mary Jane C. Samonte | [Google v. CNIL: The Territorial Scope of the Right to Be Forgotten Under EU Law](https://doi.org/10.15166/2499-8249/332) | SHILAP Revista de lepidopterología | — | 22 |
| Yulia Razmetaeva | [The Right to Be Forgotten in the European Perspective](https://doi.org/10.1515/bjes-2020-0004) | TalTech journal of European studies/TalTech journal of European studies | — | 19 |
| Tomohiro Hayase, S. Yasutomi, Takashi Katoh | [Selective Forgetting of Deep Networks at a Finer Level than Samples](https://arxiv.org/abs/2012.11849) | arXiv | — | 17 |
| Carmen Aguirre, Carlos J. Gómez‐Ariza, M. Teresa Bajo | [Selective directed forgetting: Eliminating output order and demand characteristics explanations](https://doi.org/10.1177/1747021820915100) | Quarterly Journal of Experimental Psychology | — | 14 |
| Junfeng Tian, Zhidan Wang | [Fine-grained assured data deletion scheme based on attribute association](https://doi.org/10.1016/j.cose.2020.101936) | Computers & Security | — | 13 |
| Quoc Phong Nguyen, Bryan Kian Hsiang Low, Patrick Jaillet | [Variational Bayesian Unlearning](https://openalex.org/W3105631581) | NeurIPS | [GitHub](https://github.com/qphong/variational-bayesian-unlearning) | 12 |
| Susanne Durst et al. | [Unlearning: a systematic literature review](https://doi.org/10.1504/ijbg.2020.106959) | International Journal of Business and Globalisation | — | 9 |
| Jonathan Brophy | [Exit Through the Training Data: A Look into Instance-Attribution Explanations and Efﬁcient Data Deletion in Machine Learning](https://www.semanticscholar.org/paper/86407c30ec00d742ae44f125e9833ba23323eb87) |  | — | 8 |
| Seth Neel, Aaron Roth, Saeed Sharifi-Malvajerdi | [Descent-to-Delete: Gradient-Based Methods for Machine Unlearning](https://openalex.org/W3148413297) | ALT | [GitHub](https://github.com/anminhhung/data-deletion) | 8 |
| Ricardo Gonçalves et al. | [On the limits of forgetting in Answer Set Programming](https://doi.org/10.1016/j.artint.2020.103307) | Artificial Intelligence | — | 7 |
| Lu Chen, Masayuki Murata | [Enhancing network modularity to mitigate catastrophic forgetting](https://doi.org/10.1007/s41109-020-00332-9) | Applied Network Science | [GitHub](https://github.com/luchen-cn/modularity_cnn) | 6 |
| Mark Leiser | [‘Private jurisprudence’ and the right to be forgotten balancing test](https://doi.org/10.1016/j.clsr.2020.105458) | Computer law & security review | — | 6 |
| Jonathan Brophy, Daniel Lowd | [Machine Unlearning for Random Forests](https://doi.org/10.48550/arxiv.2009.05567) | ICML | [GitHub](https://github.com/jjbrophy47/dare_rf) | 6 |
| Oliver Kliegl, Bernhard Pastötter, Karl‐Heinz T. Bäuml | [Does Amount of Pre-cue Encoding Modulate Selective List Method Directed Forgetting?](https://doi.org/10.3389/fpsyg.2020.01403) | Frontiers in Psychology | — | 5 |
| P.T.J. Wolters | [The territorial effect of the right to be forgotten after <i>Google v CNIL</i>](https://doi.org/10.1093/ijlit/eaaa022) | International Journal of Law and Information Technology | — | 5 |
| Victoria Vovk, Ulyana Olijnyk | [The right to be forgotten as a "new right" of man in to the digitalized society](https://doi.org/10.33098/2078-6670.10.22.16-22) | Scientific and informational bulletin of Ivano-Frankivsk University of Law named after King Danylo Halytskyi | — | 5 |
| Dmitry Belyavsky et al. | [Set It and Forget It! Turnkey ECC for Instant Integration](https://doi.org/10.1145/3427228.3427291) | Annual Computer Security Applications Conference | [GitHub](https://github.com/gost-engine/engine) | 4 |
| Kristi Bushman, Alexandros Labrinidis | [Set it and forget it: utility-based scheduling for public displays](https://doi.org/10.1007/s00779-020-01423-1) | Personal and Ubiquitous Computing | — | 4 |
| Changsong Yang, Xiaoling Tao, Qiyu Chen | [New Publicly Verifiable Data Deletion Supporting Efficient Tracking for Cloud Storage.](https://openalex.org/W3082307348) | Int. J. Netw. Secur | — | 3 |
| Sachiko Yanagihara, Hiroshi Koga | [Differences in Human and AI Memory for Memorization, Recall, And Selective Forgetting](https://openalex.org/W3039375895) | Dialnet (Universidad de la Rioja) | — | 2 |
| Minyao Hua, Yinyuan Zhao, Tao Jiang | [Secure data deletion in cloud storage: a survey](https://doi.org/10.1504/ijes.2020.105939) | International Journal of Embedded Systems | — | 2 |
| Zhanpeng Yang et al. | [Fine-grained outsourced data deletion in cloud storage](https://doi.org/10.1088/1742-6596/1656/1/012025) | Journal of Physics Conference Series | — | 2 |
| Angelo Maietta | [The Right to be forgotten](https://doi.org/10.4013/rechtd.2020.122.03) | Revista de Estudos Constitucionais Hermenêutica e Teoria do Direito | — | 2 |
| Slaven Zulj, Damir Delija, Goran Sirovatka | [Analysis of secure data deletion and recovery with common digital forensic tools and procedures](https://doi.org/10.23919/mipro48935.2020.9245197) | International Convention on Information and Communication Technology, Electronics and Microelectronics | — | 1 |

## 2019

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Lucas Bourtoule et al. | [Machine Unlearning](https://doi.org/10.1109/SP40001.2021.00019) | IEEE S&P | [GitHub](https://github.com/cleverhans-lab/machine-unlearning) | 1378 |
| Aditya Golatkar, A. Achille, Stefano Soatto | [Eternal Sunshine of the Spotless Net: Selective Forgetting in Deep Networks](https://doi.org/10.1109/cvpr42600.2020.00932) | CVPR | [GitHub](https://github.com/AdityaGolatkar/SelectiveForgetting) | 770 |
| Antonio A. Ginart et al. | [Making AI Forget You: Data Deletion in Machine Learning](https://arxiv.org/abs/1907.05012) | NeurIPS | [GitHub](https://github.com/tginart/deletion-efficient-kmeans) | 671 |
| Chuan Guo et al. | [Certified Data Removal from Machine Learning Models](https://arxiv.org/abs/1911.03030) | ICML | [GitHub](https://github.com/facebookresearch/certified-removal) | 631 |
| He He, Sheng Zha, Haohan Wang | [Unlearn Dataset Bias in Natural Language Inference by Fitting the Residual](https://doi.org/10.18653/v1/D19-6115) | EMNLP | [GitHub](https://github.com/alinlab/MASKER) | 214 |
| He He, Sheng Zha, Haohan Wang | [Unlearn Dataset Bias in Natural Language Inference by Fitting the Residual](https://doi.org/10.18653/v1/d19-6115) | DeepLo@EMNLP-IJCNLP | [GitHub](https://github.com/alinlab/MASKER) | 165 |
| Małgorzata Magdziarczyk | [RIGHT TO BE FORGOTTEN IN LIGHT OF REGULATION (EU) 2016/679 OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL OF 27 APRIL 2016 ON THE PROTECTION OF NATURAL PERSONS WITH REGARD TO THE PROCESSING OF PERSONAL DATA AND ON THE FREE MOVEMENT OF SUCH DATA, AND REPEALING DIRECTIVE 95/46/EC](https://doi.org/10.5593/sgemsocial2019v/1.1/s02.022) | SGEM International Multidisciplinary Scientific Conferences on Social Sciences and Arts | — | 127 |
| Min Du et al. | [Lifelong Anomaly Detection Through Unlearning](https://doi.org/10.1145/3319535.3363226) | CCS | [GitHub](https://github.com/YifeiLin0226/LifeLongAnomalyUnlearn) | 118 |
| Jenalee Kluttz, Jude Walker, Pierre Walter | [Unsettling allyship, unlearning and learning towards decolonising solidarity](https://doi.org/10.1080/02660830.2019.1654591) | Studies in the Education of Adults | — | 83 |
| Konstantina Kilteni, Christian Houborg, H. Henrik Ehrsson | [Rapid learning and unlearning of predicted sensory delays in self-generated touch](https://doi.org/10.7554/elife.42888) | eLife | — | 82 |
| Wenpeng Hu et al. | [OVERCOMING CATASTROPHIC FORGETTING FOR CONTINUAL LEARNING VIA MODEL ADAPTATION](https://openalex.org/W2906141031) | ICLR | [GitHub](https://github.com/morning-dews/PGMA_tensorflow) | 81 |
| Karen Becker, Adelle Bish | [A framework for understanding the role of unlearning in onboarding](https://doi.org/10.1016/j.hrmr.2019.100730) | Human Resource Management Review | — | 70 |
| Chongchong Lyu et al. | [Antecedents and consequence of organizational unlearning: Evidence from China](https://doi.org/10.1016/j.indmarman.2019.07.013) | Industrial Marketing Management | — | 67 |
| Juan‐Gabriel Cegarra‐Navarro, Anthony Wensley | [Promoting intentional unlearning through an unlearning cycle](https://doi.org/10.1108/jocm-04-2018-0107) | Journal of Organizational Change Management | — | 67 |
| Theo Bertram et al. | [Five Years of the Right to be Forgotten](https://doi.org/10.1145/3319535.3354208) | CCS | — | 55 |
| Jinbo Xiong et al. | [A secure data deletion scheme for IoT devices through key derivation encryption and data analysis](https://doi.org/10.1016/j.future.2019.10.017) | Future Generation Computer Systems | — | 40 |
| Makoto Matsuo | [Critical reflection, unlearning, and engagement](https://doi.org/10.1177/1350507619859681) | Management Learning | — | 40 |
| Shubham Sharma, Usha Lenka | [Exploring linkages between unlearning and relearning in organizations](https://doi.org/10.1108/tlo-10-2018-0164) | The Learning Organization | — | 40 |
| Jialu Hao et al. | [Secure and Fine-Grained Self-Controlled Outsourced Data Deletion in Cloud-Based IoT](https://doi.org/10.1109/jiot.2019.2953082) | IEEE IoT-J | — | 35 |
| Markus F. Peschl | [Unlearning towards an uncertain future: on the back end of future-driven unlearning](https://doi.org/10.1108/tlo-11-2018-0192) | The Learning Organization | — | 33 |
| Sebastian Schelter | [“Amnesia” – Towards Machine Learning Models That Can Forget User Data Very Fast](https://www.semanticscholar.org/paper/2e8528d78d6f273c72ad8e60b6d7de5c29dc2aef) | CIDR | — | 29 |
| Mainack Mondal et al. | [Moving Beyond Set-It-And-Forget-It Privacy Settings on Social Media](https://doi.org/10.1145/3319535.3354202) | CCS | — | 26 |
| Eva Lievens, Carl Vander Maelen | [A Child’s Right to be Forgotten: Letting Go of the Past and Embracing the Future?](https://doi.org/10.29263/lar02.2019.03) | Latin American Law Review | — | 25 |
| Adrian Klammer, Stefan Gueldenberg | [Honor the old, welcome the new: an account of unlearning and forgetting in NPD teams](https://doi.org/10.1108/ejim-12-2018-0255) | European Journal of Innovation Management | — | 23 |
| Karen Becker | [Organizational unlearning: the challenges of a developing phenomenon](https://doi.org/10.1108/tlo-05-2019-0082) | The Learning Organization | — | 20 |
| S. Shintre, Kevin A. Roundy, Jasjeet Dhaliwal | [Making Machine Learning Forget](https://doi.org/10.1007/978-3-030-21752-5_6) | Annual Privacy Forum | [GitHub](https://github.com/JordiCondom/MachineUnlearning) | 19 |
| Peiqiu Chen et al. | [Overcoming Catastrophic Forgetting by Bayesian Generative Regularization](https://arxiv.org/abs/1912.01238) | ICML | [GitHub](https://github.com/drimpossible/GDumb) | 19 |
| Gurkeerat Singh, Christina Chien, Sharad Patel | [Pressure Regulated Volume Control (PRVC): Set it and forget it?](https://doi.org/10.1016/j.rmcr.2019.03.001) | Respiratory Medicine Case Reports | — | 15 |
| Yann Padova | [Is the right to be forgotten a universal, regional, or ‘glocal’ right?](https://doi.org/10.1093/idpl/ipy025) | International Data Privacy Law | — | 13 |
| Ricardo Gonçalves et al. | [Forgetting in Modular Answer Set Programming](https://doi.org/10.1609/aaai.v33i01.33012843) | AAAI | — | 12 |
| Syed Ali Nawaid ALAM | [Managing Organizational Knowledge by Unlearning? A Systematic Literature Review](https://doi.org/10.1109/iccike47802.2019.9004409) | ICCIKE | — | 7 |
| Wenjuan Meng, Jianhua Ge, Tao Jiang | [Secure Data Deduplication with Reliable Data Deletion in Cloud](https://doi.org/10.1142/s0129054119400124) | International Journal of Foundations of Computer Science | — | 7 |
| Anna Bunn | [Children and the ‘Right to be Forgotten’: what the right to erasure means for European children, and why Australian children should be afforded a similar right](https://doi.org/10.1177/1329878x19848503) | Media International Australia | — | 7 |
| Bruno Zeller et al. | [The Right to be Forgotten—The EU and Asia Pacific Experience (Australia, Indonesia, Japan and Singapore)](https://doi.org/10.2139/ssrn.3320860) | SSRN Electronic Journal | — | 7 |
| Rashid Zaman, Marwan Hassani | [Process mining meets GDPR compliance : the right to be forgotten as a use case](https://openalex.org/W2979693573) | TU/e Research Portal | — | 7 |
| Sydney Goggins | [Reshaping public memory in<i>the 1619 project</i>: rhetorical interventions against selective forgetting](https://doi.org/10.1080/15596893.2019.1992832) | Museums & Social Issues | — | 6 |
| Mirek Dymitrow | [The concept of ‘rural’ as a psychosocial process: From concept attainment to concept unlearning](https://doi.org/10.2478/quageo-2019-0036) | Quaestiones Geographicae | — | 6 |
| Jonathan Adam Holland | [Contemporary Practical Alternatives to a “Right To Be Forgotten” in the United States](https://doi.org/10.29263/lar02.2019.02) | Latin American Law Review | — | 4 |
| Rene Rautenbach, Margie Sutherland, Caren Brenda Scheepers | [The process by which executives unlearn their attachments in order to facilitate change](https://doi.org/10.25159/2520-3223/5876) | African Journal of Employee Relations | — | 3 |
| Peng Xiao, Haoran Lin | [The Right to Be Forgotten Debate: Pros and Cons](https://openalex.org/W2972224906) | CBR | — | 3 |
| Xi Zheng | [Return Of A Forgotten Right: Application Of The Right To Be Forgotten In Criminal Justice](https://doi.org/10.24966/flis-733x/100035) | Forensic Legal & Investigative Sciences | — | 3 |
| Maja Ovčak Kos Maja Ovčak Kos | [The Right to be Forgotten and the Media](https://doi.org/10.18690/lexonomica.11.2.195-212.2019) | Lexonomica | — | 2 |
| Yash Doshi, Harshal Shah | [Now You See It, Now You Don't: Uber's Data Deletion Service](https://openalex.org/W2955794748) |  | — | 1 |
| Rechell Yee Shun Lam | [Applying the concept of 'unlearn to learn' for sustainability in vocational and professional education and training (VPET): implications for teacher training](https://openalex.org/W3016905369) |  | — | 1 |
| Jane Lewis | [“Set and forget” is not an ideal approach to pressure support ventilation: the ongoing saga of high tidal volumes](https://doi.org/10.1016/s1441-2772(23)00578-1) | Critical Care and Resuscitation | — | 1 |
| Fulin Wang et al. | [Complete Data Deletion Based on Hadoop Distributed File System](https://doi.org/10.1145/3331453.3360966) | International Conference on Computer Science and Application Engineering | — | 1 |
| Seema Joshi, Shailesh Panchal | [A Survey on Assured Data Deletion in Cloud Storage](https://doi.org/10.26438/ijcse/v7i6.548553) | International Journal of Computer Sciences and Engineering | — | 1 |
| Jenny Rosenfeld, Todd Enoch | [Beyond “Set It and Forget It”: Proactively Managing Your EZproxy Server](https://doi.org/10.1080/0361526x.2019.1551041) | The Serials Librarian | — | 1 |
| Byung Cheol Lee, Gita Venkataramani Johar | [Preference Unlearning: When Personalized Recommendations Reduce Preference Clarity](https://openalex.org/W3120218913) | ACR North American Advances | — | 0 |

## 2018

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Liang Xue et al. | [Efficient attribute-based encryption with attribute revocation for assured data deletion](https://doi.org/10.1016/j.ins.2018.02.015) | Information Sciences | — | 140 |
| Christian D. Helfrich et al. | [How the dual process model of human cognition can inform efforts to de‐implement ineffective and harmful clinical practices: A preliminary model of unlearning and substitution](https://doi.org/10.1111/jep.12855) | Journal of Evaluation in Clinical Practice | — | 129 |
| Philip S.J. Weston et al. | [Accelerated long-term forgetting in presymptomatic autosomal dominant Alzheimer's disease: a cross-sectional study](https://doi.org/10.1016/s1474-4422(17)30434-9) | The Lancet Neurology | — | 123 |
| Mariya Toneva et al. | [An Empirical Study of Example Forgetting during Deep Neural Network Learning](https://doi.org/10.48550/arxiv.1812.05159) | arXiv | [GitHub](https://github.com/mtoneva/example_forgetting) | 114 |
| Yong Yu et al. | [Assured Data Deletion With Fine-Grained Access Control for Fog-Based Industrial Applications](https://doi.org/10.1109/tii.2018.2841047) | IEEE T-II | — | 88 |
| Eugenia Politou et al. | [Backups and the right to be forgotten in the GDPR: An uneasy relationship](https://doi.org/10.1016/j.clsr.2018.08.006) | Computer law & security review | — | 74 |
| Thomas Eiter, Gabriele Kern-Isberner | [A Brief Survey on Forgetting from a Knowledge Representation and Reasoning Perspective](https://doi.org/10.1007/s13218-018-0564-6) | KI - Künstliche Intelligenz | — | 49 |
| Xiangyang Wang, Ying Qi, Yingxin Zhao | [Individual unlearning, organizational unlearning and strategic flexibility](https://doi.org/10.1108/bjm-10-2017-0324) | Baltic Journal of Management | — | 47 |
| Aurelie Bayle et al. | [When Blockchain Meets the Right to Be Forgotten: Technology versus Law in the Healthcare Industry](https://doi.org/10.1109/wi.2018.00133) | International Conference on Wirtschaftsinformatik | — | 35 |
| Karen Becker | [Organizational unlearning: time to expand our horizons?](https://doi.org/10.1108/tlo-10-2017-0095) | The Learning Organization | — | 34 |
| Yuliya Snihur | [Responding to business model innovation: organizational unlearning and firm failure](https://doi.org/10.1108/tlo-03-2017-0032) | The Learning Organization | — | 33 |
| Yinzhi Cao et al. | [Efficient Repair of Polluted Machine Learning Systems via Causal Unlearning](https://doi.org/10.1145/3196494.3196517) | CCS | — | 32 |
| Ashley Nicole Vavra | [The Right to Be Forgotten: An Archival Perspective](https://doi.org/10.17723/0360-9081-81.1.100) | The American Archivist | — | 28 |
| Muhammad Usman, Ahmed Abdul Hameed, Shahid Manzoor | [Exploring the links between Ethical Leadership and Organizational Unlearning: A Case Study of a European Multinational Company](https://doi.org/10.22547/ber/10.2.2) | Business & Economic Review | — | 20 |
| Li Yang et al. | [SADUS: Secure data deletion in user space for mobile devices](https://doi.org/10.1016/j.cose.2018.05.013) | Computers & Security | — | 19 |
| Vahid Delshab, Saeed Sadeghi Boroujerdi | [Investigating the influence of unlearning on knowledge management in sport organizations](https://doi.org/10.1108/k-11-2017-0449) | Kybernetes | — | 17 |
| Kevin Potter, Lucas Huszar, David E. Huber | [Does inhibition cause forgetting after selective retrieval? A reanalysis and failure to replicate](https://doi.org/10.1016/j.cortex.2018.03.026) | Cortex | — | 15 |
| Makoto Matsuo | [Effects of team unlearning on employee creativity](https://doi.org/10.1108/jwl-03-2018-0045) | Journal of Workplace Learning | — | 14 |
| Richard Cheston et al. | [Selective forgetting of self‐threatening statements: Mnemic neglect for dementia information in people with mild dementia](https://doi.org/10.1002/gps.4894) | International Journal of Geriatric Psychiatry | — | 13 |
| Leticia Bode, Meg Leta Jones | [Do Americans Want a Right to be Forgotten? Estimating Public Support for Digital Erasure Legislation](https://doi.org/10.1002/poi3.174) | Policy & Internet | — | 13 |
| Ambar Murillo et al. | ["If I press delete, it's gone" - User Understanding of Online Data Deletion and Expiration](https://openalex.org/W2889179041) | Symposium On Usable Privacy and Security | — | 13 |
| Crespo Am, Sanjit R. Konda, Kenneth A. Egol | [Set it and Forget it: Diaphyseal Fractures of the Humerus Undergo Minimal Change in Angulation After Functional Brace Application.](https://openalex.org/W2983198066) | PubMed | — | 12 |
| Dawn Carla Nunziato | [The Fourth Year of Forgetting: The Troubling Expansion of the Right to Be Forgotten](https://doi.org/10.2139/ssrn.3191068) | SSRN Electronic Journal | — | 12 |
| Wenlong Li | [A tale of two rights: exploring the potential conflict between right to data portability and right to be forgotten under the General Data Protection Regulation](https://doi.org/10.1093/idpl/ipy007) | International Data Privacy Law | — | 10 |
| Marie Mesnil | [What do we mean by the right to be forgotten? An analysis of the French case study from a lawyer’s perspective](https://doi.org/10.1016/j.jcpo.2018.01.001) | Journal of Cancer Policy | — | 9 |
| Robert C. Post | [Data Privacy and Dignitary Privacy: Google Spain, the Right To Be Forgotten, and the Construction of the Public Sphere](https://openalex.org/W3124548120) | SSRN Journal | — | 8 |
| Veronika Szeghalmi | [Difficulties Regarding the Right to Be Forgotten in the Case Law of the Strasbourg Court](https://doi.org/10.30958/ajl.4-3-4) | Athens Journal of Law | — | 7 |
| Linnéa Lindsköld | [Google as a political subject: the right to be forgotten debate 2014-2016](https://doi.org/10.1108/oir-06-2017-0198) | Online Information Review | — | 5 |
| Fiona Brimblecombe, Gavin Phillipson | [Regaining digital privacy? The new “right to be forgotten” and online expression.](https://openalex.org/W2899275771) | Durham Research Online (Durham University) | — | 4 |
| Stephen Goggin | [How Quickly We Selectively Forget: Experimental Tests of Information Order on Memory and Candidate Evaluation](https://doi.org/10.1111/pops.12499) | Political Psychology | — | 4 |
| Ruishan Xin et al. | [Data deletion method for security improvement of Flash memories](https://doi.org/10.1587/elex.15.20180152) | IEICE Electronics Express | — | 2 |
| Chunyang Lu, Feng Wen | [Geographic information system query optimisation algorithm based on redundant data deletion and filtering technology](https://doi.org/10.1504/ijipt.2018.095412) | International Journal of Internet Protocol Technology | — | 1 |

## 2017

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| James Kirkpatrick et al. | [Overcoming catastrophic forgetting in neural networks](https://doi.org/10.1073/pnas.1611835114) | National Academy of Sciences | [HF](https://huggingface.co/infgrad/stella-large-zh-v2) | 6988 |
| Ronald Kemker et al. | [Measuring Catastrophic Forgetting in Neural Networks](https://doi.org/10.1609/aaai.v32i1.11651) | AAAI | [GitHub](https://github.com/giangnguyen2412/paper-review-continual-learning) | 863 |
| Randolph F. Helfrich et al. | [Old Brains Come Uncoupled in Sleep: Slow Wave-Spindle Synchrony, Brain Atrophy, and Forgetting](https://doi.org/10.1016/j.neuron.2017.11.020) | Neuron | — | 513 |
| Divya Gupta, Richard J. Boland, David C. Aron | [The physician’s experience of changing clinical practice: a struggle to unlearn](https://doi.org/10.1186/s13012-017-0555-2) | Implementation Science | — | 265 |
| Eduard Fosch‐Villaronga, Peter Kieseberg, Tiffany Li | [Humans forget, machines remember: Artificial intelligence and the Right to Be Forgotten](https://doi.org/10.1016/j.clsr.2017.08.007) | Computer law & security review | — | 158 |
| Changsong Yang, Xiaofeng Chen, Yang Xiang | [Blockchain-based publicly verifiable data deletion scheme for cloud storage](https://doi.org/10.1016/j.jnca.2017.11.011) | Journal of Network and Computer Applications | [GitHub](https://github.com/TonyWu1995/audit_method) | 144 |
| William H. Starbuck | [Organizational learning and unlearning](https://doi.org/10.1108/tlo-11-2016-0073) | The Learning Organization | — | 103 |
| Marlena Fiol, Edward J. O’Connor | [Unlearning established organizational routines – Part I](https://doi.org/10.1108/tlo-09-2016-0056) | The Learning Organization | — | 85 |
| Marta Morais‐Storz, Nhien Nguyen | [The role of unlearning in metamorphosis and strategic resilience](https://doi.org/10.1108/tlo-12-2016-0091) | The Learning Organization | — | 78 |
| Xiangyang Wang et al. | [Organizational unlearning and knowledge transfer in cross-border M&amp;A: the roles of routine and knowledge compatibility](https://doi.org/10.1108/jkm-03-2017-0091) | Journal of Knowledge Management | — | 61 |
| Jean-Marie Chenou, Roxana Radu | [The “Right to Be Forgotten”: Negotiating Public and Private Ordering in the European Union](https://doi.org/10.1177/0007650317717720) | Business & Society | — | 59 |
| Max Visser | [Learning and unlearning: a conceptual note](https://doi.org/10.1108/tlo-10-2016-0070) | The Learning Organization | — | 56 |
| Elena Esposito | [Algorithmic memory and the right to be forgotten on the web](https://doi.org/10.1177/2053951717703996) | Big Data & Society | — | 55 |
| Eric W. K. Tsang | [How the concept of organizational unlearning contributes to studies of learning organizations](https://doi.org/10.1108/tlo-10-2016-0064) | The Learning Organization | — | 51 |
| Robert C. Post | [Data Privacy and Dignitary Privacy: Google Spain, the Right to Be Forgotten, and the Construction of the Public Sphere](https://doi.org/10.2139/ssrn.2953468) | SSRN Electronic Journal | — | 49 |
| C. Marlene Fiol, Edward J. O’Connor | [Unlearning established organizational routines – Part II](https://doi.org/10.1108/tlo-09-2016-0063) | The Learning Organization | — | 49 |
| Baharan Mirzasoleiman, Amin Karbasi, Andreas Krause | [Deletion-Robust Submodular Maximization: Data Summarization with "the Right to be Forgotten"](https://openalex.org/W2741807132) | ICML | — | 46 |
| James P. Delgrande | [A Knowledge Level Account of Forgetting](https://doi.org/10.1613/jair.5530) | Journal of Artificial Intelligence Research | — | 41 |
| Thomas Grisold, Alexander Kaiser | [Leaving Behind What We are Not: Applying a Systems Thinking Perspective to Present Unlearning as an Enabler for Finding the Best Version of the Self](https://doi.org/10.1080/14779633.2017.1291145) | Journal of Organisational Transformation & Social Change | — | 41 |
| Carmen Aguirre et al. | [Exploring Mechanisms of Selective Directed Forgetting](https://doi.org/10.3389/fpsyg.2017.00316) | Frontiers in Psychology | — | 37 |
| Giancarlo Frosio | [Right to Be Forgotten: Much Ado About Nothing](https://doi.org/10.2139/ssrn.3009153) | SSRN Electronic Journal | — | 35 |
| Nhien Nguyen | [The journey of organizational unlearning: a conversation with William H. Starbuck](https://doi.org/10.1108/tlo-11-2016-0076) | The Learning Organization | — | 35 |
| Agnès Dumas et al. | [The right to be forgotten: a change in access to insurance and loans after childhood cancer?](https://doi.org/10.1007/s11764-017-0600-9) | Journal of Cancer Survivorship | — | 34 |
| Soyeon Moon, Sun-Young Oh | [Unlearning overgenerated be through data-driven learning in the secondary EFL classroom](https://doi.org/10.1017/s0958344017000246) | ReCALL | — | 33 |
| Tiffany Li, Eduard Fosch‐Villaronga, Peter Kieseberg | [Humans Forget, Machines Remember: Artificial Intelligence and the Right to Be Forgotten](https://doi.org/10.31228/osf.io/zs8kb) | Comput. Law Secur. Rev | — | 32 |
| Makoto Matsuo | [Goal orientation, critical reflection, and unlearning: An individual‐level study](https://doi.org/10.1002/hrdq.21303) | Human Resource Development Quarterly | — | 32 |
| Thomas Grisold, Alexander Kaiser, Julee Hafner | [Unlearning before Creating new Knowledge: A Cognitive Process.](https://doi.org/10.24251/hicss.2017.561) | HICSS | — | 29 |
| Makoto Matsuo | [The Unlearning of Managerial Skills: A Qualitative Study of Executive Officers](https://doi.org/10.1111/emre.12122) | European Management Review | — | 25 |
| Jannice Käll | [A Posthuman Data Subject? The Right to Be Forgotten and Beyond](https://doi.org/10.1017/s2071832200022288) | German Law Journal | — | 25 |
| S. Kulk | [Privacy, Freedom of Expression, and the Right to Be Forgotten in Europe](https://doi.org/10.2139/ssrn.2923722) | SSRN Electronic Journal | — | 24 |
| Eric Tjong Tjin Tai | [The Right to Be Forgotten - Private Law Enforcement](https://doi.org/10.2139/ssrn.2958145) | SSRN Electronic Journal | — | 21 |
| Eric W. K. Tsang | [Stop eulogizing, complicating or straitjacketing the concept of organizational unlearning, please](https://doi.org/10.1108/tlo-11-2016-0084) | The Learning Organization | — | 21 |
| Ricardo Gonçalves et al. | [When you must forget: Beyond strong persistence when forgetting in answer set programming](https://doi.org/10.1017/s1471068417000382) | Theory and Practice of Logic Programming | — | 19 |
| Junliang Shu et al. | [Why Data Deletion Fails? A Study on Deletion Flaws and Data Remanence in Android Systems](https://doi.org/10.1145/3007211) | ACM Transactions on Embedded Computing Systems | — | 16 |
| Richard G. Kyle et al. | [Learning and unlearning dignity in care: Experiential and experimental educational approaches](https://doi.org/10.1016/j.nepr.2017.05.001) | Nurse Education in Practice | — | 16 |
| Krzysztof Garstka, David Erdos | [Hiding in Plain Sight? The 'Right to Be Forgotten' and Search Engines in the Context of International Data Protection Frameworks](https://doi.org/10.2139/ssrn.3043870) | SSRN Electronic Journal | — | 16 |
| Marina Santín | [The problem of the right to be forgotten from the perspective of self-regulation in journalism](https://doi.org/10.3145/epi.2017.mar.17) | El Profesional de la Informacion | — | 15 |
| Melisa Akan, Lili Sahakyan | [Repeated failures to obtain selective directed forgetting in lab and online samples and variations in stimuli](https://doi.org/10.1080/09658211.2017.1327600) | Memory | — | 15 |
| Oliver Kliegl, Lisa Wallner, Karl‐Heinz T. Bäuml | [Selective directed forgetting in children](https://doi.org/10.1016/j.jecp.2017.11.002) | Journal of Experimental Child Psychology | — | 14 |
| Leticia Bode, Meg Leta Jones | [Ready to forget: American attitudes toward the right to be forgotten](https://doi.org/10.1080/01972243.2016.1271071) | The Information Society | — | 14 |
| Paul John Steinbart, Mark Keith, Jeffry Babb | [Measuring Privacy Concern and the Right to Be Forgotten](https://doi.org/10.24251/hicss.2017.603) | HICSS | — | 12 |
| Martha García‐Murillo, Ian MacInnes | [Così fan tutte: A better approach than the right to be forgotten](https://doi.org/10.1016/j.telpol.2017.12.003) | Telecommunications Policy | — | 11 |
| Judith Townend | [Data Protection and the ‘Right to be Forgotten’ in Practice: A UK Perspective](https://doi.org/10.1017/jli.2017.2) | International Journal of Legal Information | — | 10 |
| Amy Gajda | [Privacy, Press, and the Right to Be Forgotten in the United States](https://openalex.org/W2620779592) | SSRN Electronic Journal | — | 10 |
| Ruth Glynn, Karen Salmon, Jason Low | [It’s in the details: The role of selective discussion in forgetting of children’s autobiographical memories](https://doi.org/10.1016/j.jecp.2017.10.009) | Journal of Experimental Child Psychology | — | 9 |
| Charles B. Stone, Theofilos Gkinopoulos, William Hirst | [Forgetting history: The mnemonic consequences of listening to selective recountings of history](https://doi.org/10.1177/1750698017701610) | Memory Studies | — | 9 |
| Stefania Alessi | [Eternal Sunshine: The Right to Be Forgotten in the European Union after the 2016 General Data Protection Regulation](https://openalex.org/W3127149325) | eYLS (Yale Law School) | — | 9 |
| Chanhee Kwak et al. | [Let Machines Unlearn – Machine Unlearning and the Right to be Forgotten](https://openalex.org/W2617274374) | Journal of the Association for Information Systems | — | 7 |
| Mélanie Dulong de Rosnay, Andrés Guadamuz | [Memory Hole or Right to Delist? Implications of the Right to Be Forgotten for Web Archiving](https://openalex.org/W3153307287) | SSRN Electronic Journal | — | 6 |
| Byung-Cheol Kim, Jin Yeub Kim | [The Economics of the Right to Be Forgotten](https://doi.org/10.1086/694254) | The Journal of Law and Economics | — | 6 |
| John W. Dowdell | [An American Right to Be Forgotten](https://openalex.org/W2613207772) |  | — | 5 |
| McKay Cunningham | [Privacy Law That Does Not Protect Privacy, Forgetting the Right to Be Forgotten](https://openalex.org/W2605293135) | eYLS (Yale Law School) | — | 5 |
| Ben Medeiros | [The reputation-management industry and the prospects for a “right to be forgotten” in the US](https://doi.org/10.1080/21689725.2017.1308262) | First Amendment Studies | — | 3 |
| Cherie Noteboom, Julee Hafner, Abdullah Wahbeh | [Characteristics of Complete and Incomplete Physicians’ Unlearning with Electronic Medical Record](https://doi.org/10.17705/3jmwa.00031) | Journal of the Midwest Association for Information Systems | — | 3 |
| Eli Edwards | [Libraries and the Right to be Forgotten: a Conflict in the Making?](https://doi.org/10.5860/jifp.v2i1.6249) | Journal of Intellectual Freedom and Privacy | — | 2 |
| Brandon D. Chalifoux et al. | [ThermoYield actuators: nano-adjustable set-and-forget optics mounts](https://doi.org/10.1117/12.2273049) | Optical Engineering + Applications | — | 1 |

## 2016

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Maxwell B. Merkow et al. | [Stimulation of the human medial temporal lobe between learning and recall selectively enhances forgetting](https://doi.org/10.1016/j.brs.2016.12.011) | Brain stimulation | — | 86 |
| Mohammad Hosein Rezazade Mehrizi, Mojtaba Lashkarbolouki | [Unlearning Troubled Business Models: From Realization to Marginalization](https://doi.org/10.1016/j.lrp.2015.12.005) | Long Range Planning | — | 63 |
| Mary Lawhon et al. | [Unlearning (Un)Located Ideas in the Provincialization of Urban Theory](https://doi.org/10.1080/00343404.2016.1162288) | Regional Studies | — | 61 |
| John Howells, Joachim Scholderer | [Forget unlearning? How an empirically unwarranted concept from psychology was imported to flourish in management and organisation studies](https://doi.org/10.1177/1350507615624079) | Management Learning | — | 59 |
| Noam Tirosh | [Reconsidering the ‘Right to be Forgotten’ – memory rights and the right to memory in the new media era](https://doi.org/10.1177/0163443716674361) | Media Culture & Society | — | 51 |
| Minhui Xue et al. | [The Right to be Forgotten in the Media: A Data-Driven Study](https://doi.org/10.1515/popets-2016-0046) | PoPETs | — | 50 |
| María Dolores Aledo Ruiz et al. | [Linking an unlearning context with firm performance through human capital](https://doi.org/10.1016/j.iedeen.2016.07.001) | European Research on Management and Business Economics | — | 44 |
| Cesare Bartolini, Lawrence Siry | [The right to be forgotten in the light of the consent of the data subject](https://doi.org/10.1016/j.clsr.2016.01.005) | Computer law & security review | — | 39 |
| Daniel A. Friess, Tariq Jazeel | [Unlearning “Landscape”](https://doi.org/10.1080/24694452.2016.1230414) | Annals of the American Association of Geographers | — | 38 |
| T.F.E. Tjong Tjin Tai | [The right to be forgotten – private law enforcement](https://doi.org/10.1080/13600869.2016.1138628) | International Review of Law Computers & Technology | — | 38 |
| Ricardo Gonçalves, Matthias Knorr, João Leite | [The ultimate guide to forgetting in answer set programming](https://openalex.org/W2573779957) | Principles of Knowledge Representation and Reasoning | — | 33 |
| Kieron O’Hara, Nigel Shadbolt, Wendy Hall | [A pragmatic approach to the right to be forgotten](https://openalex.org/W2297895487) | ePrints Soton (University of Southampton) | — | 32 |
| Saif Shahin | [Right to Be Forgotten](https://doi.org/10.1177/1077699016638835) | Journalism & Mass Communication Quarterly | — | 29 |
| Antoon de Baets | [A historian's view on the right to be forgotten](https://doi.org/10.1080/13600869.2015.1125155) | International Review of Law Computers & Technology | — | 28 |
| Kyu Ho Youm, Ahran Park | [The “Right to Be Forgotten” in European Union Law](https://doi.org/10.1177/1077699016628824) | Journalism & Mass Communication Quarterly | — | 22 |
|  | [The Ethics of Memory in a Digital Age — Interrogating the Right to be Forgotten](https://doi.org/10.1108/rmj-11-2015-0040) | Records Management Journal | — | 21 |
| Ann L. Edwards, Jacqueline S. Hebert, Patrick M. Pilarski | [Machine learning and unlearning to autonomously switch between the functions of a myoelectric arm](https://doi.org/10.1109/biorob.2016.7523678) | International Conference on Biomedical Robotics and Biomechatronics | — | 18 |
| Frederik Zuiderveen Borgesius | [Het ‘right to be forgotten’ en bijzondere persoonsgegevens](https://openalex.org/W2763326251) | Computerrecht | — | 17 |
| Chen Liu, Hoda Aghaei Khouzani, Chengmo Yang | [ErasuCrypto: A Light-weight Secure Data Deletion Scheme for Solid State Drives](https://doi.org/10.1515/popets-2017-0009) | PoPETs | — | 17 |
| Ivor Shapiro, Brian MacLeod Rogers | [How the “Right to be Forgotten” Challenges Journalistic Principles](https://doi.org/10.1080/21670811.2016.1239545) | Digital Journalism | — | 16 |
| Kristie Byrum | [The European right to be forgotten: A challenge to the United States Constitution’s First Amendment and to professional public relations ethics](https://doi.org/10.1016/j.pubrev.2016.10.010) | Public Relations Review | — | 16 |
| Mike Schraeder et al. | [Unlearning cynicism](https://doi.org/10.1108/ijoa-05-2013-0674) | International journal of organizational analysis | — | 13 |
| Tzu‐Ling Liu, Nai-Feng Chen, Shih-kuen Cheng | [Selective rehearsal is affected by the emotionality of the encoding context in item-method directed forgetting: An event-related potential study](https://doi.org/10.1016/j.biopsycho.2016.11.012) | Biological Psychology | — | 12 |
| Claudia Kodde | [Germany's ‘Right to be forgotten’ – between the freedom of expression and the right to informational self-determination](https://doi.org/10.1080/13600869.2015.1125154) | International Review of Law Computers & Technology | — | 12 |
| Cayce Myers | [Digital Immortality vs. “The Right to be Forgotten”: A Comparison of U.S. and E.U. Laws Concerning Social Media Privacy](https://doi.org/10.21018/rjcpr.2014.3.175) | Romanian Journal of Communication and Public Relations | — | 10 |
| Mário Viola de Azevedo Cunha, Gabriel Itagiba | [Between privacy, freedom of information and freedom of expression: Is there a right to be forgotten in Brazil?](https://doi.org/10.1016/j.clsr.2016.05.009) | Computer law & security review | — | 8 |
| Bernd Malle et al. | [Privacy Aware Machine Learning and the "Right to be Forgotten".](https://openalex.org/W2576375469) | ERCIM News | — | 8 |
| Albert Verheij | [The right to be forgotten – a Dutch perspective](https://doi.org/10.1080/13600869.2015.1125156) | International Review of Law Computers & Technology | — | 8 |
| Michael Rosenstock | [Is there a ‘right to be forgotten’ in Canada’s Personal Information Protection and Electronic Documents Act (PIPEDA)?](https://openalex.org/W2555352372) | eYLS (Yale Law School) | — | 8 |
| Bambang Pratama | [Prinsip Moral Sebagai Klaim Pada Hak Cipta Dan Hak Untuk Dilupakan (Right To Be Forgotten)](https://doi.org/10.25123/vej.2270) | Veritas et Justitia | — | 7 |
| Julia Kerr | [What is a Search Engine? The Simple Question the Court of Justice of the European Union Forgot to Ask and What It Means for the Future of the Right to be Forgotten](https://openalex.org/W2533832859) | Chicago journal of international law | — | 6 |
| Erica Lenton, Carolyn Dineen | [Set it and Forget it (Almost): How We Make DIY 3D Printing Work in Our Library](https://doi.org/10.1080/15228959.2016.1168725) | Public & Access Services Quarterly | — | 6 |
| Sherry L. Xie | [Retention in “the right to be forgotten” scenario: a records management examination](https://doi.org/10.1108/rmj-11-2015-0038) | Records Management Journal | — | 6 |
| Duryana Mohamed | [The Privacy Right and Right to be Forgotten: the Malaysian Perspectives](https://doi.org/10.17485/ijst/2016/v9is1/106854) | Indian Journal of Science and Technology | — | 5 |
| Aline Klingenberg | [Catches to the right to be forgotten, looking from an administrative law perspective to data processing by public authorities](https://doi.org/10.1080/13600869.2015.1125161) | International Review of Law Computers & Technology | — | 5 |
| Amotz Bar-Noy, Benjamin S. Baumer, Dror Rawitz | [Set It and Forget It: Approximating the Set Once Strip Cover Problem](https://doi.org/10.1007/s00453-016-0198-8) | Algorithmica | — | 4 |
| Hugh J. McCarthy | [<i>All the World's a Stage</i>: The European right to be forgotten revisited from a US perspective](https://doi.org/10.1093/jiplp/jpw026) | Journal of Intellectual Property Law & Practice | — | 4 |
| Susanna Lindroos‐Hovinheimo | [Legal Subjectivity and the ‘Right to be Forgotten’: A Rancièrean Analysis of Google](https://doi.org/10.1007/s10978-016-9185-0) | Law and Critique | — | 4 |
| Jongwon Lee | [What the Right to be Forgotten Means to Companies: Threat or Opportunity?](https://doi.org/10.1016/j.procs.2016.07.138) | Procedia Computer Science | — | 3 |
| Jordan Levesque | [The right to be forgotten : no solution to the challenges of the digital environment](https://doi.org/10.14288/1.0308713) | cIRcle (University of British Columbia) | — | 3 |
| Ekaterina Andryushchenko | [Right to be forgotten on the internet in Europe and Russia](https://doi.org/10.18316/2237-8049-2016.2) | Conhecimento & Diversidade | — | 2 |
| Robin Trines et al. | [A cryogenic 'set-and-forget' deformable mirror](https://doi.org/10.1117/12.2231402) | SPIE, the International Society for Optical Engineering/ SPIE | — | 2 |
| Benjamin John Keele | [Privacy by Deletion: The Need for a Global Data Deletion Principle](https://doi.org/10.31228/osf.io/96f9k) | Indiana Journal of Global Legal Studies | — | 1 |

## 2015

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Yinzhi Cao, Junfeng Yang | [Towards Making Systems Forget with Machine Unlearning](https://doi.org/10.1109/SP.2015.35) | IEEE S&P | [GitHub](https://github.com/TouchSky-Lab/Awesome-Memorization-Elimination) | 1030 |
| Yinzhi Cao, Junfeng Yang | [Towards Making Systems Forget with Machine Unlearning](https://doi.org/10.1109/sp.2015.35) | IEEE S&P | [GitHub](https://github.com/TouchSky-Lab/Awesome-Memorization-Elimination) | 508 |
| Kai Olav Ellefsen, Jean-Baptiste Mouret, Jeff Clune | [Neural Modularity Helps Organisms Evolve to Learn New Skills without Forgetting Old Skills](https://doi.org/10.1371/journal.pcbi.1004128) | PLoS Computational Biology | [GitHub](https://github.com/OptimusLime/GPU-CPPN) | 157 |
| Nicole Lee, Matthew S. VanDyke | [Set It and Forget It](https://doi.org/10.1177/1075547015588600) | Science Communication | — | 114 |
| Cheryl Brook et al. | [On stopping doing those things that are not getting us to where we want to be: Unlearning, wicked problems and critical action learning](https://doi.org/10.1177/0018726715586243) | Human Relations | — | 110 |
| Pamela R. Haunschild, Francisco Polidoro, David P. Chandler | [Organizational Oscillation Between Learning and Forgetting: The Dual Role of Serious Errors](https://doi.org/10.1287/orsc.2015.1010) | Organization Science | — | 104 |
| Xiaoqing Hu et al. | [Unlearning implicit social biases during sleep](https://doi.org/10.1126/science.aaa3841) | Science | — | 104 |
| Alin Coman, William Hirst | [Social identity and socially shared retrieval-induced forgetting: The effects of group membership.](https://doi.org/10.1037/xge0000077) | Journal of Experimental Psychology General | — | 98 |
| Yichun Shuai et al. | [Dissecting neural pathways for forgetting in <i>Drosophila</i> olfactory aversive memory](https://doi.org/10.1073/pnas.1512792112) | National Academy of Sciences | — | 73 |
| Abraham L. Newman | [What the “right to be forgotten” means for privacy in a digital age](https://doi.org/10.1126/science.aaa4603) | Science | — | 57 |
| Michael L. Rustad, Sanna Kulevska | [Reconceptualizing the Right to Be Forgotten to Enable Transatlantic Data Flow](https://openalex.org/W2194561098) |  | — | 56 |
| Oleksandr V. Popovych, Markos Xenakis, Peter A. Tass | [The Spacing Principle for Unlearning Abnormal Neuronal Synchrony](https://doi.org/10.1371/journal.pone.0117205) | PLoS ONE | — | 49 |
| Anthony Wensley, Juan Gabriel Cegarra Navarro | [Overcoming knowledge loss through the utilization of an unlearning context](https://doi.org/10.1016/j.jbusres.2015.01.052) | Journal of Business Research | — | 46 |
| Julia Powles, Enrique Chaparro | [How Google Determined Our Right to be Forgotten](https://openalex.org/W3117577258) |  | — | 39 |
| Kieron O’Hara | [The Right to Be Forgotten: The Good, the Bad, and the Ugly](https://doi.org/10.1109/mic.2015.88) | IEEE Internet Computing | — | 36 |
| Dan Jerker B. Svantesson | [Limitless Borderless Forgetfulness? Limiting the Geographical Reach of the ‘Right to be Forgotten’](https://doi.org/10.5617/oslaw2567) | Oslo Law Review | — | 35 |
| Kieron O’Hara, Nigel Shadbolt | [The Right to be Forgotten: Its Potential Role in a Coherent Privacy Regime](https://doi.org/10.21552/edpl/2015/3/5) | European Data Protection Law Review | — | 33 |
| Christian W. Scheiner et al. | [ORGANISATIONAL AND INDIVIDUAL UNLEARNING IN IDENTIFICATION AND EVALUATION OF TECHNOLOGIES](https://doi.org/10.1142/s1363919616500171) | International Journal of Innovation Management | — | 33 |
| James P. Delgrande, Kewen Wang | [A Syntax-Independent Approach to Forgetting in Disjunctive Logic Programs](https://doi.org/10.1609/aaai.v29i1.9402) | AAAI | — | 28 |
| Luciano Floridi | [Should You Have The Right To Be Forgotten On Google? Nationally, Yes. Globally, No.](https://doi.org/10.1111/npqu.11510) | New Perspectives Quarterly | — | 28 |
| Ashleigh M. Maxcey | [Recognition-induced forgetting is not due to category-based set size](https://doi.org/10.3758/s13414-015-1007-1) | Attention Perception & Psychophysics | — | 22 |
| Anna Bunn | [The curious case of the right to be forgotten](https://doi.org/10.1016/j.clsr.2015.03.006) | Computer law & security review | — | 22 |
| Dan Jerker B. Svantesson | [Limitless Borderless Forgetfulness? Limiting the Geographical Reach of the 'Right to Be Forgotten'](https://doi.org/10.2139/ssrn.2659982) | SSRN Electronic Journal | — | 22 |
| Miquel Peguera | [In the Aftermath of Google Spain: How the ‘Right to Be Forgotten’ is Being Shaped in Spain by Courts and the Data Protection Authority](https://openalex.org/W3121555900) | Int. J. Law Inf. Technol | — | 21 |
| Vincent Charles, Madjid Tavana, Tatiana Gherman | [The right to be forgotten - is privacy sold out in the big data age?](https://doi.org/10.1504/ijsss.2015.073225) | International Journal of Society Systems Science | — | 21 |
| Giovanni Sartor | [The right to be forgotten: balancing interests in the flux of time](https://doi.org/10.1093/ijlit/eav017) | International Journal of Law and Information Technology | — | 17 |
| S. Kulk, Frederik Zuiderveen Borgesius | [Freedom of Expression and ‘Right to Be Forgotten’ Cases in the Netherlands After Google Spain](https://doi.org/10.21552/edpl/2015/2/5) | European Data Protection Law Review | — | 16 |
| Luciano Floridi | ['The Right to be Forgotten': A Philosophical View](https://doi.org/10.2139/ssrn.3853478) | SSRN Electronic Journal | — | 12 |
| Lyndsay Cook | [The Right to Be Forgotten: A Step in the Right Direction for Cyberspace Law and Policy](https://openalex.org/W2529311003) | eYLS (Yale Law School) | — | 12 |
| D. Payne | [Google, doctors, and the "right to be forgotten"](https://doi.org/10.1136/bmj.h27) | BMJ | — | 11 |
| Julee Hafner | [Computer System Unlearning in Individuals](https://doi.org/10.1109/hicss.2015.463) | HICSS | — | 11 |
| Herke Kranenborg | [Google and the Right to Be Forgotten (Case C-131/12, Google Spain)](https://doi.org/10.21552/edpl/2015/1/13) | European Data Protection Law Review | — | 10 |
| Edward Lee | [Recognizing Rights in Real Time: The Role of Google in the EU Right to Be Forgotten](https://openalex.org/W1023331947) |  | — | 9 |
| Seungwoo Jeon, Bonghee Hong, Joonho Kwon | [Redundant Data Removal Technique for Efficient Big Data Search Processing](https://openalex.org/W2188458595) |  | — | 7 |
| Brendan Van Alsenoy, Marieke Koekkoek | [The Extra-Territorial Reach of the EU's “Right to Be Forgotten”](https://openalex.org/W181648292) | International Data Privacy Law | — | 5 |
| R. George Wright | [The Right to Be Forgotten: Issuing a Voluntary Recall](https://doi.org/10.2139/ssrn.2569237) | SSRN Electronic Journal | — | 5 |
| Ravi Antani | [The Resistance of Memory: Could the European Union�s Right to be Forgotten Exist in the United States?](https://doi.org/10.15779/z387w09) | Berkeley technology law journal | — | 4 |
| Jianmin Ji, Jia-Huai You, Yisong Wang | [On forgetting postulates in answer set programming](https://openalex.org/W2406651931) | IJCAI | — | 4 |
| Shazmin Aniza Abdul Shukor, Emma Rushforth | [Adapting histogram for automatic noise data removal in building interior point cloud data](https://doi.org/10.1063/1.4915792) | AIP conference proceedings | — | 3 |
| Augusto Sebastio | [Online Right to be Forgotten in the European Justice Evolution](https://openalex.org/W2593266578) | RePEc: Research Papers in Economics | — | 3 |
| Geert Van Calster | [Regulating the Internet. Prescriptive and Jurisdictional Boundaries to the EU's 'Right to Be Forgotten'](https://doi.org/10.2139/ssrn.2686111) | SSRN Electronic Journal | — | 3 |
| Edward Lee | [The Right to Be Forgotten v. Free Speech](https://openalex.org/W2189603384) | The Knowledge Bank (The Ohio State University) | — | 3 |
| Byung‐Cheol Kim, Jin Yeub Kim | [The Economics of the Right to Be Forgotten](https://doi.org/10.2139/ssrn.2672007) | SSRN Electronic Journal | — | 2 |
| Meg Leta Jones et al. | [The right to be forgotten](https://doi.org/10.1002/pra2.2015.145052010010) | Association for Information Science and Technology | — | 1 |
| Yun Yang | [Active Data Deletion of Cloud Computing based on Hadoop](https://openalex.org/W2389150672) | Journal of Chengdu University of Information Technology | — | 1 |
| Reena Kumari Behera, Smita K. Nair, Vinay G. Vaidya | [Redundant Data Removal from Images](https://doi.org/10.4271/2015-01-0215) | SAE technical papers on CD-ROM/SAE technical paper series | — | 1 |

## 2014

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Antonio L. Leal‐Rodríguez et al. | [Organizational unlearning, innovation outcomes, and performance: The moderating effect of firm size](https://doi.org/10.1016/j.jbusres.2014.11.032) | Journal of Business Research | — | 218 |
| Angela Scarino | [Situating the challenges in current languages education policy in Australia – unlearning monolingualism](https://doi.org/10.1080/14790718.2014.921176) | International Journal of Multilingualism | — | 125 |
| Lucy Vanes et al. | [Contingency Learning in Alcohol Dependence and Pathological Gambling: Learning and Unlearning Reward Contingencies](https://doi.org/10.1111/acer.12393) | Alcoholism Clinical and Experimental Research | — | 103 |
| Kuo‐Pin Yang, Christine Chou, Yu-Jen Chiu | [How unlearning affects radical innovation: The dynamics of social capital and slack resources](https://doi.org/10.1016/j.techfore.2013.12.014) | Technological Forecasting and Social Change | — | 92 |
| Yangang Wang et al. | [Knowledge Forgetting in Answer Set Programming](https://doi.org/10.1613/jair.4297) | Journal of Artificial Intelligence Research | — | 41 |
|  | [Unlearning with Hannah Arendt](https://doi.org/10.5860/choice.186342) | Choice Reviews Online | — | 37 |
| Giovanni Sartor | [The right to be forgotten in the Draft Data Protection Regulation](https://doi.org/10.1093/idpl/ipu030) | International Data Privacy Law | — | 37 |
| Eleni Frantziou | [Further Developments in the Right to be Forgotten: The European Court of Justice's Judgment in Case C-131/12, Google Spain, SL, Google Inc v Agencia Espanola de Proteccion de Datos](https://doi.org/10.1093/hrlr/ngu033) | Human Rights Law Review | — | 36 |
| David Lindsay | [The ‘Right to be Forgotten’ by Search Engines under Data Privacy Law: A Legal Analysis of the <i>Costeja</i> Ruling](https://doi.org/10.5235/17577632.6.2.159) | Journal of Media Law | — | 24 |
| Carmen Aguirre et al. | [Selective voluntary forgetting in young and older adults.](https://doi.org/10.1037/a0035598) | Psychology and Aging | — | 24 |
| Meg Leta Ambrose | [Speaking of forgetting: Analysis of possible non-EU responses to the right to be forgotten and speech exception](https://doi.org/10.1016/j.telpol.2014.05.002) | Telecommunications Policy | — | 20 |
| Jade Q. Wu et al. | [The hippocampus, medial prefrontal cortex, and selective memory retrieval: Evidence from a rodent model of the retrieval‐induced forgetting effect](https://doi.org/10.1002/hipo.22291) | Hippocampus | — | 19 |
| Christopher Rees, Debbie Heywood | [The ‘right to be forgotten’ or the ‘principle that has been remembered’](https://doi.org/10.1016/j.clsr.2014.07.002) | Computer law & security review | — | 16 |
| Maya Parmar | [Memorialising 40 years since Idi Amin's expulsion: Digital ‘memory mania’ to the ‘right to be forgotten’](https://doi.org/10.1080/14746689.2014.879420) | South Asian Popular Culture | — | 16 |
| Robert Bolton | [The Right to Be Forgotten: Forced Amnesia in a Technological Age](https://openalex.org/W1516753457) | SSRN Electronic Journal | — | 10 |
| Lee A. Bygrave | [A right to be forgotten?](https://doi.org/10.1145/2688491) | Communications of the ACM | — | 9 |
| Ioannis Iglezakis | [The Right to Be Forgotten in the Google Spain Case (Case C-131/12): A Clear Victory for Data Protection or an Obstacle for the Internet?](https://doi.org/10.2139/ssrn.2472323) | SSRN Electronic Journal | — | 8 |
| Paulan Korenhof et al. | [Timing the Right to Be Forgotten: A Study into 'Time' as a Factor in Deciding About Retention or Erasure of Data](https://doi.org/10.2139/ssrn.2436436) | SSRN Electronic Journal | — | 7 |
| Julee Hafner, Timothy J. Ellis, William Hafner | [Error Occurrence: Successful versus Unsuccessful Unlearning in Individuals](https://doi.org/10.1109/hicss.2014.437) | HICSS | — | 5 |
| Younsung Choi et al. | [Password-based single-file encryption and secure data deletion for solid-state drive](https://doi.org/10.1145/2557977.2558072) | International Conference on Ubiquitous Information Management and Communication | — | 5 |
| Hannah Crowther | [Google v Spain: is there now a 'right to be forgotten'?](https://doi.org/10.1093/jiplp/jpu148) | Journal of Intellectual Property Law & Practice | — | 5 |
| Patricia Sánchez Abril, Jacqueline D. Lipton | [The Right to be Forgotten: Who Decides What the World Forgets?](https://openalex.org/W2797098220) | UKnowledge (University of Kentucky) | — | 5 |
| Julia Powles, Luciano Floridi | [A Manifesto For the Future of the ‘Right to be Forgotten’ Debate](https://openalex.org/W3000064506) |  | — | 3 |
| Zhiming Gui, Haipeng Yu | [Trip Travel Time Forecasting Based on Selective Forgetting Extreme Learning Machine](https://doi.org/10.1155/2014/829256) | Mathematical Problems in Engineering | — | 3 |
| Shayan Assadi, J. Maruniak, Jong‐Hyun Jung | [Bartold PM, Van Dyke TE. 2013. Periodontitis: a host-mediated disruption of microbial ho- meostasis. Unlearning learned concepts. Periodontology 2000, 62 (1): 203-217.](https://openalex.org/W2188496663) |  | — | 2 |
| Eric Lagu�, Khalil Rhaiem | [A PRACTICAL APPROACH TO ORGANIZATIONAL UNLEARNING](https://doi.org/10.18374/ijsm-14-1.3) | International Journal of Strategic Management | — | 2 |
| Martha García‐Murillo, Ian MacInnes | [The Right to Be Forgotten: Its Weaknesses and Alternatives](https://doi.org/10.2139/ssrn.2529396) | SSRN Electronic Journal | — | 2 |
| Pouria Sarhadi, Karim Salahshoor, Ali Khaki Sedigh | [Application of augmented UD identification with selective forgetting in an adaptive control loop](https://doi.org/10.1504/ijmic.2014.059393) | International Journal of Modelling Identification and Control | — | 1 |
| Peng Zhi-yua | [On the Right to Be Forgotten](https://openalex.org/W2350069090) | Journal of North University of China | [GitHub](https://github.com/rundimeco/right-to-be-forgotten) | 1 |

## 2013

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Donald Hislop et al. | [The process of individual unlearning: A neglected topic in an under-researched field](https://doi.org/10.1177/1350507613486423) | Management Learning | — | 173 |
| Andreas V. Kuhlmann et al. | [A dark-field microscope for background-free detection of resonance fluorescence from single semiconductor quantum dots operating in a set-and-forget mode](https://doi.org/10.1063/1.4813879) | Review of Scientific Instruments | — | 145 |
| Tomoko Kitago et al. | [Unlearning versus savings in visuomotor adaptation: comparing effects of washout, passage of time, and removal of errors on motor memory](https://doi.org/10.3389/fnhum.2013.00307) | Frontiers in Human Neuroscience | — | 140 |
| Joel Reardon, David Basin, Srđjan Čapkun | [SoK: Secure Data Deletion](https://doi.org/10.1109/sp.2013.28) | IEEE S&P | [GitHub](https://github.com/ATFWUS/holesecret) | 139 |
| Yingxin Zhao, Yanqiu Lü, Xiangyang Wang | [Organizational unlearning and organizational relearning: a dynamic process of knowledge management](https://doi.org/10.1108/jkm-06-2013-0242) | Journal of Knowledge Management | — | 134 |
| Meg Leta Ambrose, Jef Ausloos | [The Right to Be Forgotten Across the Pond](https://doi.org/10.5325/jinfopoli.3.2013.0001) | Journal of Information Policy | — | 69 |
| Güler Dunne, Chris Askew | [Vicarious learning and unlearning of fear in childhood via mother and stranger models.](https://doi.org/10.1037/a0032994) | Emotion | — | 54 |
| Alessandro Mantelero | [The EU Proposal for a General Data Protection Regulation and the roots of the ‘right to be forgotten’](https://doi.org/10.1016/j.clsr.2013.03.010) | Computer law & security review | — | 52 |
| Xiangyang Wang et al. | [Organisational unlearning, organisational flexibility and innovation capability: an empirical study of SMEs in China](https://doi.org/10.1504/ijtm.2013.052178) | International Journal of Technology Management | — | 52 |
| Karen R. Brandt, Maria Kragh Nielsen, Amanda Holmes | [Forgetting emotional and neutral words: An ERP study](https://doi.org/10.1016/j.brainres.2013.01.019) | Brain Research | — | 47 |
| Joel Reardon et al. | [Secure data deletion from persistent media](https://doi.org/10.1145/2508859.2516699) | CCS | — | 46 |
| Juan‐Gabriel Cegarra‐Navarro et al. | [Environmental knowledge, unlearning, and performance in hospitality companies](https://doi.org/10.1108/00251741311301858) | Management Decision | — | 46 |
| Peter Druschel, Michael Backes, R. Tirtea | [The right to be forgotten- between expectations and practice](https://openalex.org/W2242383803) | Dialnet (Universidad de la Rioja) | — | 41 |
| Joseph J. Mazzola, Jacqueline K. Deuling | [Forgetting What We Learned as Graduate Students: HARKing and Selective Outcome Reporting in I–O Journal Articles](https://doi.org/10.1111/iops.12049) | Industrial and Organizational Psychology | — | 41 |
| Dominic McGoldrick | [Developments in the Right to be Forgotten](https://doi.org/10.1093/hrlr/ngt035) | Human Rights Law Review | — | 36 |
| Jacob J. van den Berg et al. | [“Set it and Forget it”: Women’s Perceptions and Opinions of Long-Acting Topical Vaginal Gels](https://doi.org/10.1007/s10461-013-0652-4) | AIDS and Behavior | — | 32 |
| Meg Leta Jones | [Speaking of Forgetting: Analysis of Possible Non-EU Responses to the Right to Be Forgotten and Speech Exception](https://doi.org/10.2139/ssrn.2238602) | SSRN Electronic Journal | — | 31 |
| Yisong Wang, Kewen Wang, Mingyi Zhang | [Forgetting for answer set programs revisited](https://openalex.org/W2293185116) | Griffith Research Online (Griffith University, Queensland, Australia) | — | 30 |
| Anton O. Kris | [Unlearning and Learning Psychoanalysis](https://doi.org/10.1353/aim.2013.0018) | American imago | — | 25 |
| Muge Fazlioglu | [Forget me not: the clash of the right to be forgotten and freedom of expression on the Internet](https://doi.org/10.1093/idpl/ipt010) | International Data Privacy Law | — | 23 |
| Paulan Korenhof | [Forgetting Bits and Pieces: An Exploration of the 'Right to Be Forgotten' as Implementation of 'Forgetting' in Online Memory Processes](https://doi.org/10.2139/ssrn.2326475) | SSRN Electronic Journal | — | 21 |
| Charles B. Stone, Olivier Luminet, William Hirst | [Induced forgetting and reduced confidence in our personal past? The consequences of selectively retrieving emotional autobiographical memories](https://doi.org/10.1016/j.actpsy.2013.06.019) | Acta Psychologica | — | 20 |
| Robert G. Larson | [Forgetting the First Amendment: How Obscurity-Based Privacy and a Right to Be Forgotten Are Incompatible with Free Speech](https://doi.org/10.1080/10811680.2013.746140) | Communication Law and Policy | — | 20 |
| CR Coombs et al. | [Exploring types of individual unlearning by local health-care managers: an original empirical approach](https://doi.org/10.3310/hsdr01020) | Health Services and Delivery Research | — | 17 |
| Edward L. Carter | [Argentina's Right to Be Forgotten](https://openalex.org/W3126580280) | eYLS (Yale Law School) | — | 14 |
| Meg Leta Ambrose, Jef Ausloos | [The Right to Be Forgotten Across the Pond](https://doi.org/10.5325/jinfopoli.3.1.1) | Journal of Information Policy | — | 11 |
| Ashok K. Behuria, Mohammad Shehzad | [Partition of History in Textbooks in Pakistan: Implications of Selective Memory and Forgetting](https://doi.org/10.1080/09700161.2013.782664) | Strategic Analysis | — | 9 |
| Emily Adams Shoor | [Narrowing the Right to Be Forgotten: Why the European Union Needs to Amend the Proposed Data Protection Regulation](https://openalex.org/W1781514412) | Brooklyn journal of international law | — | 8 |
| Van Hoboken Joris V.j. | [The Proposed Right to be Forgotten Seen from the Perspective of Our Right to Remember Freedom of Expression Safeguards in a Converging Information Environment](https://doi.org/10.2788/51998) | Joint Research Centre (European Commission) | — | 8 |
| Yoan Hermstrüwer, Stephan Dickert | [Tearing the Veil of Privacy Law: An Experiment on Chilling Effects and the Right to Be Forgotten](https://doi.org/10.2139/ssrn.2311201) | SSRN Electronic Journal | — | 6 |
| Amotz Bar-Noy, Benjamin S. Baumer, Dror Rawitz | [Set it and forget it - approximating the set once strip cover problem](https://doi.org/10.1145/2486159.2486162) | arXiv | — | 6 |
| D. Preetha Evangeline et al. | [Feature subset selection for irrelevant data removal using Decision Tree Algorithm](https://doi.org/10.1109/icoac.2013.6921962) | International Conference on Advanced Computing | — | 4 |
| Sang-Ki Chung, Kyung-Yeol Kim | [Trend of Dispute on the Right to Be Forgotten and Acceptance Task of Internet Laws in Korea](https://doi.org/10.9716/kits.2013.12.1.131) | Journal of the Korea society of IT services | — | 3 |
| Eugen Chelaru, Chelaru Marius | [RIGHT TO BE FORGOTTEN](https://openalex.org/W2602421565) |  | — | 2 |

## 2012

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Roland G. Benoit, Michael C. Anderson | [Opposing Mechanisms Support the Voluntary Forgetting of Unwanted Memories](https://doi.org/10.1016/j.neuron.2012.07.025) | Neuron | — | 356 |
| Yoni Pertzov et al. | [Rapid forgetting prevented by retrospective attention cues.](https://doi.org/10.1037/a0030947) | Journal of Experimental Psychology Human Perception & Performance | — | 246 |
| Jeffrey Rosen | [The Right to Be Forgotten](https://openalex.org/W1841997604) |  | — | 177 |
| Melonie Williams, Geoffrey F. Woodman | [Directed forgetting and directed remembering in visual working memory.](https://doi.org/10.1037/a0027389) | Journal of Experimental Psychology Learning Memory and Cognition | — | 118 |
| Steven C. Bennett | ["The ""Right to Be Forgotten"": Reconciling EU and US Perspectives"](https://doi.org/10.15779/z38v08z) | Berkeley journal of international law | — | 103 |
| Peter A. Tass, Oleksandr V. Popovych | [Unlearning tinnitus-related cerebral synchrony with acoustic coordinated reset stimulation: theoretical concept and modelling](https://doi.org/10.1007/s00422-012-0479-5) | Biological Cybernetics | — | 95 |
| Charles B. Stone et al. | [Forgetting our personal past: Socially shared retrieval-induced forgetting of autobiographical memories.](https://doi.org/10.1037/a0030739) | Journal of Experimental Psychology General | — | 91 |
| Meg Leta Ambrose | [It's About Time: Privacy, Information Life Cycles, and the Right to be Forgotten](https://openalex.org/W2149624754) | SSRN Electronic Journal | — | 66 |
| Sarah J. Barber, Mara Mather | [Forgetting in context: The effects of age, emotion, and social factors on retrieval-induced forgetting](https://doi.org/10.3758/s13421-012-0202-8) | Memory & Cognition | — | 51 |
| Christine Bastin et al. | [The Neural Substrates of Memory Suppression: A fMRI Exploration of Directed Forgetting](https://doi.org/10.1371/journal.pone.0029905) | PLoS ONE | — | 51 |
| Jef Ausloos | [The ‘Right to be Forgotten’ – Worth remembering?](https://doi.org/10.1016/j.clsr.2012.01.006) | Computer law & security review | — | 41 |
| Robert Kramer | [Rank on Emotional Intelligence, Unlearning and Self-Leadership](https://doi.org/10.1057/ajp.2012.24) | The American Journal of Psychoanalysis | — | 40 |
| Norberto Nuno Gomes de Andrade | [Oblivion: The Right to Be Different … from Oneself. Reproposing the Right to Be Forgotten](https://doi.org/10.1057/9781137428455_5) | Palgrave Macmillan UK eBooks | — | 35 |
| Alun E. Joseph, Robin Kearns, Graham Moon | [Re-Imagining Psychiatric Asylum Spaces through Residential Redevelopment: Strategic Forgetting and Selective Remembrance](https://doi.org/10.1080/02673037.2013.729270) | Housing Studies | — | 34 |
| Hans Graux, Jef Ausloos, Peggy Valcke | [The Right to Be Forgotten in the Internet Era](https://doi.org/10.2139/ssrn.2174896) | SSRN Electronic Journal | — | 31 |
| Jasmine McNealy | [The Emerging Conflict between Newsworthiness and the Right to Be Forgotten](https://openalex.org/W2142547306) |  | — | 30 |
| Carlos J. Gómez‐Ariza et al. | [Selective intentional forgetting in adolescents with social anxiety disorder](https://doi.org/10.1016/j.psychres.2012.09.027) | Psychiatry Research | — | 30 |
| Matthew J. Crossley, F. Gregory Ashby, W. Todd Maddox | [Erasing the engram: The unlearning of procedural skills.](https://doi.org/10.1037/a0030059) | Journal of Experimental Psychology General | — | 29 |
| Cécile de Terwangne | [Internet Privacy and the Right to Be Forgotten/Right to Oblivion](https://doi.org/10.7238/idp.v0i13.1400) | IDP Revista de Internet Derecho y Política | — | 23 |
| Meg Leta Jones, Jef Ausloos | [The Right to Be Forgotten Across the Pond](https://doi.org/10.2139/ssrn.2032325) | SSRN Electronic Journal | — | 23 |
| Oliver Kliegl, Bernhard Pastötter, Karl‐Heinz T. Bäuml | [List-method directed forgetting can be selective: Evidence from the 3-list and the 2-list tasks](https://doi.org/10.3758/s13421-012-0264-7) | Memory & Cognition | — | 22 |
| Lilian Mitrou, Maria Karyda | [EU΄s Data Protection Reform and the right to be forgotten - A legal response to a technological challenge?](https://openalex.org/W2170690656) | SSRN Electronic Journal | — | 18 |
| Benjamin C. Storm, Rebecca H. Koppel, Brittany M. Wilson | [Rapid communication: Selective cues to forget can fail to cause forgetting](https://doi.org/10.1080/17470218.2012.753923) | Quarterly Journal of Experimental Psychology | — | 17 |
| Wasim Ahmad Bhat, S. M. K. Quadri | [restFS: Secure data deletion using reliable &amp;amp; efficient stackable file system](https://doi.org/10.1109/sami.2012.6209010) | International Symposium on Applied Machine Intelligence and Informatics | — | 16 |
| Jones, Meg Leta | [You are What Google Says You are: The Right to Be Forgotten and Information Stewardship](https://openalex.org/W1756473545) | SSRN Electronic Journal | — | 15 |
| Mega Leta Ambrose | [You Are What Google Says You Are: The Right to be Forgotten and Information Stewardship](https://doi.org/10.29173/irie212) | The International Review of Information Ethics | — | 15 |
| Gabriella Óturai et al. | [The role of object functions for deferred imitation – Do infants selectively retain and forget target actions?](https://doi.org/10.1016/j.infbeh.2012.01.004) | Infant Behavior and Development | — | 10 |
| R. M. Walker | [Forcing Forgetfulness: Data Privacy, Free Speech, and the 'Right to Be Forgotten'](https://doi.org/10.2139/ssrn.2017967) | SSRN Electronic Journal | — | 5 |
| Robert Kirk Walker | [Note – The Right to Be Forgotten](https://openalex.org/W2776521341) | Hastings law journal | — | 4 |
| Kieron O’Hara | [Can Semantic Web Technology Help Implement a Right to Be Forgotten](https://openalex.org/W111260239) | ePrints Soton (University of Southampton) | — | 4 |
| Lei Fan | [Approach into and prospect of the current organizational unlearning research](https://doi.org/10.1109/ismot.2012.6679520) | International Symposium on Management of Technology | — | 3 |
| Vanitha Muthusamy, C. Kavitha | [SECURED DATA DELETION IN CLOUD BASED MULTI-TENANT DATABASE ARCHITECTURE](https://doi.org/10.18000/ijisac.50125) | International Journal on Information Sciences and Computing | — | 2 |
| Glen McLaughlin, Mudassar Imran | [Set It and Forget It: Innovations in Implantable Medical Technology](https://doi.org/10.1109/mssc.2012.2193078) | IEEE Solid-State Circuits Magazine | — | 1 |

## 2011

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Jared Saletin, Andrea N. Goldstein, Matthew P. Walker | [The Role of Sleep in Directed Forgetting and Remembering of Human Memories](https://doi.org/10.1093/cercor/bhr034) | Cerebral Cortex | — | 155 |
| Bert‐Jaap Koops | [Forgetting Footprints, Shunning Shadows: A Critical Analysis of the 'Right to Be Forgotten' in Big Data Practice](https://doi.org/10.2139/ssrn.1986719) | SSRN Electronic Journal | — | 137 |
| Juan‐Gabriel Cegarra‐Navarro, María Eugenia Sánchez Vidal, David Cegarra‐Leiva | [Balancing exploration and exploitation of knowledge through an unlearning context](https://doi.org/10.1108/00251741111151163) | Management Decision | — | 135 |
| Shaker A. Zahra, Sondos Gamal Abdelgawad, Eric W. K. Tsang | [Emerging Multinationals Venturing Into Developed Economies: Implications for Learning, Unlearning, and Entrepreneurial Capability](https://doi.org/10.1177/1056492611408266) | Journal of Management Inquiry | — | 130 |
| Xiaosong Hu et al. | [Online estimation of an electric vehicle Lithium-Ion battery using recursive least squares with forgetting](https://doi.org/10.1109/acc.2011.5991260) | American Control Conference | — | 98 |
| Benjamin C. Storm, Genna Angello, Elizabeth Ligon Bjork | [Thinking can cause forgetting: Memory dynamics in creative problem solving.](https://doi.org/10.1037/a0023921) | Journal of Experimental Psychology Learning Memory and Cognition | — | 87 |
| Les Tien‐Shang Lee, Badri Munir Sukoco | [Reflexivity, stress, and unlearning in the new product development team: the moderating effect of procedural justice](https://doi.org/10.1111/j.1467-9310.2011.00645.x) | R and D Management | — | 77 |
| Alin Coman, William Hirst | [Cognition through a social network: The propagation of induced forgetting and practice effects.](https://doi.org/10.1037/a0025247) | Journal of Experimental Psychology General | — | 76 |
| Arabel Lim | [Unlearning the colonial cultures of planning](https://doi.org/10.1080/07293682.2010.517761) | Australian Planner | — | 75 |
| Rolf H. Weber | [The right to be forgotten: more than a pandora's box?](https://openalex.org/W2759501600) | Zurich Open Repository and Archive (University of Zurich) | — | 63 |
| Cheu-jey Lee | [Myths about Critical Literacy: What Teachers Need to Unlearn](https://openalex.org/W2138325854) | Opus: Research & Creativity (Indiana University – Purdue University Fort Wayne) | — | 59 |
| Ilke Öztekin | [Distributed patterns of brain activity that lead to forgetting](https://doi.org/10.3389/fnhum.2011.00086) | Frontiers in Human Neuroscience | — | 55 |
| Johanna C. van Hooff, Ruth M. Ford | [Remember to forget: ERP evidence for inhibition in an item-method directed forgetting paradigm](https://doi.org/10.1016/j.brainres.2011.04.004) | Brain Research | — | 53 |
| Peter S. P. Wong et al. | [The unlearning dimension of organizational learning in construction projects](https://doi.org/10.1016/j.ijproman.2011.04.001) | International Journal of Project Management | — | 53 |
| Pablo Martin de Holan | [Organizational Forgetting, Unlearning, and Memory Systems](https://doi.org/10.1177/1056492611409651) | Journal of Management Inquiry | — | 46 |
| Yiran Shen et al. | [Perfect set-and-forget alignment of silicon photonic resonators and interferometers](https://doi.org/10.1364/ofc.2011.pdpc3) | Optical Fiber Communication Conference and Exposition and the National Fiber Optic Engineers Conference | — | 46 |
| Bert‐Jaap Koops | [Forgetting footprints, shunning shadows: A critical analysis of the 'right to be forgotten' in big data practice](https://openalex.org/W3125386383) | DANS | — | 43 |
| Peter S. P. Wong, Ka Yin Lam | [Facing Turbulence: Driving Force for Construction Organizations to Regain Unlearning and Learning Traction](https://doi.org/10.1061/(asce)co.1943-7862.0000523) | Journal of Construction Engineering and Management | — | 24 |
| Byunghee Lee et al. | [Secure Data Deletion for USB Flash Memory](https://doi.org/10.6688/jise.2011.27.3.8) | Journal of information science and engineering | — | 24 |
| Zhang Xian, Wang Hong-Li | [Selective forgetting extreme learning machine and its application to time series prediction](https://doi.org/10.7498/aps.60.080504) | Acta Physica Sinica | — | 14 |
| Pere Simón Castellano | [The Right to Be Forgotten Under European Law: A Constitutional Debate](https://openalex.org/W1944856192) | Papyrus : Institutional Repository (Université de Montréal) | — | 13 |
| Maurizio Pighin, Anna Marzona | [Unlearning/Relearning in Processesof Business Information Systems Innovation](https://openalex.org/W224890477) | SHILAP Revista de lepidopterología | — | 12 |
| Pilar Andrés, Charlotte E. Howard | [Part set cuing in older adults: Further evidence of intact forgetting in aging](https://doi.org/10.1080/13825585.2010.542892) | Aging Neuropsychology and Cognition | — | 8 |
| Yiran Shen et al. | [Perfect set-and-forget alignment of silicon photonic resonators and interferometers](https://doi.org/10.1364/nfoec.2011.pdpc3) | Optical Fiber Communication Conference/National Fiber Optic Engineers Conference | — | 7 |
| Mei Yii Lim et al. | [Forgetting through generalisation: a companion with selective memory](https://doi.org/10.5555/2034396.2034447) | Adaptive Agents and Multi-Agents Systems | — | 3 |
| Liviu Ciortuz, Vlad Saveluc | [Learning to Unlearn in Lattices of Concepts: A Case Study in Fluid Construction Grammars](https://doi.org/10.1109/synasc.2011.27) | International Symposium on Symbolic and Numeric Algorithms for Scientific Computing | — | 3 |
| Whitney A. Hansen | [The Reality of Directed Forgetting in the Item-Method Paradigm: Suppression, not Selective Search or Decay.](https://openalex.org/W2123439137) |  | — | 2 |

## 2010

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Paul C. Gorski | [Unlearning Deficit Ideology and the Scornful Gaze: Thoughts on Authenticating the Class Discourse in Education](https://openalex.org/W2426726514) |  | — | 174 |
| Alp Aslan, Karl‐Heinz T. Bäuml | [Individual differences in working memory capacity predict retrieval-induced forgetting.](https://doi.org/10.1037/a0021324) | Journal of Experimental Psychology Learning Memory and Cognition | — | 119 |
| Darja Reuschke | [Unlearning the Colonial Cultures of Planning](https://doi.org/10.1080/02673037.2010.513841) | Housing Studies | — | 118 |
| Anne Hauswald et al. | [ERP dynamics underlying successful directed forgetting of neutral but not negative pictures](https://doi.org/10.1093/scan/nsq061) | Social Cognitive and Affective Neuroscience | — | 106 |
| Jerusha Conner | [Learning to unlearn: How a service-learning project can help teacher candidates to reframe urban students](https://doi.org/10.1016/j.tate.2010.02.001) | Teaching and Teacher Education | — | 87 |
| Alp Aslan, Karl‐Heinz T. Bäuml | [Retrieval-induced forgetting in young children](https://doi.org/10.3758/pbr.17.5.704) | Psychonomic Bulletin & Review | — | 72 |
| Benjamin C. Storm, Holly White | [ADHD and retrieval-induced forgetting: Evidence for a deficit in the inhibitory control of memory](https://doi.org/10.1080/09658210903547884) | Memory | — | 70 |
| James R. Schmidt, Jan De Houwer, Derek Besner | [Contingency learning and unlearning in the blink of an eye: A resource dependent process](https://doi.org/10.1016/j.concog.2009.12.016) | Consciousness and Cognition | — | 63 |
| H. Emre Yildiz, Carl F. Fey | [Compatibility and unlearning in knowledge transfer in mergers and acquisitions](https://doi.org/10.1016/j.scaman.2010.09.010) | Scandinavian Journal of Management | — | 62 |
| Jérôme Lang, Pierre Marquis | [Reasoning under inconsistency: A forgetting-based approach](https://doi.org/10.1016/j.artint.2010.04.023) | Artificial Intelligence | — | 60 |
| Alp Aslan, Martina Zellner, Karl‐Heinz T. Bäuml | [Working memory capacity predicts listwise directed forgetting in adults and children](https://doi.org/10.1080/09658211003742698) | Memory | — | 40 |
| Daniel Jiménez Jiménez, Gabriel Cepeda‐Carrión, Juan Gabriel Cegarra Navarro | [Linking unlearning with innovation through organizational memory and technology](https://openalex.org/W2611898197) |  | — | 23 |
| Juan‐Gabriel Cegarra‐Navarro, Anthony Wensley, Maria-Teresa Sánchez-Polo | [An Application of the Hospital-in-the-Home Unlearning Context](https://doi.org/10.1080/00981389.2010.506410) | Social Work in Health Care | — | 23 |

## 2009

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Elena P. Antonacopoulou | [Impact and Scholarship: Unlearning and Practising to Co-create Actionable Knowledge](https://doi.org/10.1177/1350507609336708) | Management Learning | — | 134 |
| Alin Coman, David Manier, William Hirst | [Forgetting the Unforgettable Through Conversation](https://doi.org/10.1111/j.1467-9280.2009.02343.x) | Psychological Science | — | 129 |
| Vicenç Fernández, Albert Suñe | [Organizational forgetting and its causes: an empirical research](https://doi.org/10.1108/09534810910997032) | Journal of Organizational Change Management | — | 99 |
| José Carlos Casillas Bueno, Francisco J. Acedo, José Luís Barbero | [Learning, unlearning and internationalisation: Evidence from the pre-export phase](https://doi.org/10.1016/j.ijinfomgt.2009.07.005) | International Journal of Information Management | — | 97 |
| Uri Ram | [Ways of Forgetting: Israel and the Obliterated Memory of the Palestinian Nakba](https://doi.org/10.1111/j.1467-6443.2009.01354.x) | Journal of Historical Sociology | — | 71 |
| Juan‐Gabriel Cegarra‐Navarro, Stephen Eldridge, Aurora Martínez‐Martínez | [Managing environmental knowledge through unlearning in Spanish hospitality companies](https://doi.org/10.1016/j.jenvp.2009.11.009) | Journal of Environmental Psychology | — | 52 |
| Jo Saunders, Marcelle Fernandes, Liv Kosnes | [Retrieval-induced forgetting and mental imagery](https://doi.org/10.3758/mc.37.6.819) | Memory & Cognition | — | 50 |
| Kathleen L. Hourihan, Jason D. Ozubko, Colin M. MacLeod | [Directed forgetting of visual symbols: Evidence for nonverbal selective rehearsal](https://doi.org/10.3758/mc.37.8.1059) | Memory & Cognition | — | 46 |
| Peter F. Delaney, Khanh Nghiem, Emily R. Waldum | [Short article: The selective directed forgetting effect: Can people forget only part of a text?](https://doi.org/10.1080/17470210902770049) | Quarterly Journal of Experimental Psychology | — | 41 |
| Benjamin John Keele | [Privacy by Deletion: The Need for a Global Data Deletion Principle](https://doi.org/10.2979/gls.2009.16.1.363) | Indiana Journal of Global Legal Studies | — | 2 |
| Eric Itzkin | [The Indian War Memorial: national memory and selective forgetting](https://openalex.org/W1815477673) |  | — | 1 |
| Eric Itzkin | [The Indian war memorial : national memory and selective forgetting : connecting public histories](https://openalex.org/W1943386537) |  | — | 1 |
| WU Hui-peng | [Forgetting process of the whole set of routine movement in competitive aerobics](https://openalex.org/W2347784885) | Journal of Shandong Institute of Physical Education and Sports | — | 1 |

## 2008

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Eric W. K. Tsang, Shaker A. Zahra | [Organizational unlearning](https://doi.org/10.1177/0018726708095710) | Human Relations | — | 396 |
| Jee Hyun Kim, Rick Richardson | [The Effect of Temporary Amygdala Inactivation on Extinction and Reextinction of Fear in the Developing Rat: Unlearning as a Potential Mechanism for Extinction Early in Development](https://doi.org/10.1523/jneurosci.4736-07.2008) | Journal of Neuroscience | — | 114 |
| Eric W. K. Tsang | [Transferring Knowledge to Acquisition Joint Ventures: An Organizational Unlearning Perspective](https://doi.org/10.1177/1350507607085169) | Management Learning | — | 106 |
| Thomas Eiter, Kewen Wang | [Semantic forgetting in answer set programming](https://doi.org/10.1016/j.artint.2008.05.002) | Artificial Intelligence | — | 94 |
| Feza Tabassum Azmi | [Mapping the learn‐unlearn‐relearn model](https://doi.org/10.1108/09555340810871437) | European Business Review | — | 58 |
| Anne Hauswald, Johanna Kißler | [Directed forgetting of complex pictures in an item method paradigm](https://doi.org/10.1080/09658210802169087) | Memory | — | 52 |
| E. Klein | [Learning, Unlearning, and Relearning: Lessons from One School's Approach to Creating and Sustaining Learning Communities.](https://openalex.org/W1859473071) | Teacher education quarterly (Claremont, Calif.) | — | 49 |
| Ryoichi Kimura, Alcino J. Silva, Masuo Ohno | [Autophosphorylation of αCaMKII is differentially involved in new learning and unlearning mechanisms of memory extinction](https://doi.org/10.1101/lm.1049608) | Learning & Memory | — | 47 |
| Deepak Nayyar | [Learning to Unlearn from Development](https://doi.org/10.1080/13600810802264407) | Oxford Development Studies | — | 41 |
| Karen Becker | [Unlearning as a driver of sustainable change and innovation: three Australian case studies](https://doi.org/10.1504/ijtm.2008.018062) | International Journal of Technology Management | — | 12 |

## 2007

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Ali E. Akgün et al. | [Organizational unlearning as changes in beliefs and routines in organizations](https://doi.org/10.1108/09534810710831028) | Journal of Organizational Change Management | — | 315 |
| Brice A. Kuhl et al. | [Decreased demands on cognitive control reveal the neural processing benefits of forgetting](https://doi.org/10.1038/nn1918) | Nature Neuroscience | — | 296 |
| Glenn R. Wylie, John J. Foxe, Tracy Taylor | [Forgetting as an Active Process: An fMRI Investigation of Item-Method-Directed Forgetting](https://doi.org/10.1093/cercor/bhm101) | Cerebral Cortex | — | 227 |
| Stefano Fusi et al. | [A Neural Circuit Model of Flexible Sensorimotor Mapping: Learning and Forgetting on Multiple Timescales](https://doi.org/10.1016/j.neuron.2007.03.017) | Neuron | — | 211 |
|  | [The infinite gift: how children learn and unlearn the languages of the world](https://doi.org/10.5860/choice.44-6080) | Choice Reviews Online | — | 108 |
| Miroslav Rebernik, Karin Širec | [Fostering innovation by unlearning tacit knowledge](https://doi.org/10.1108/03684920710747039) | Kybernetes | — | 106 |
| Marianna Fotaki | [PATIENT CHOICE IN HEALTHCARE IN ENGLAND AND SWEDEN: FROM QUASI‐MARKET AND BACK TO MARKET? A COMPARATIVE ANALYSIS OF FAILURE IN UNLEARNING](https://doi.org/10.1111/j.1467-9299.2007.00682.x) | Public Administration | — | 74 |
| Ganesh Baliga et al. | [When unlearning helps](https://doi.org/10.1016/j.ic.2007.10.005) | Information and Computation | — | 41 |
| A. Naskar et al. | [JU-CSE-NLP’25 at SemEval-2025 Task 4: Learning to Unlearn LLMs](https://www.semanticscholar.org/paper/1746a36f7b5419ba0ac9c4363e1ce8828861c935) | International Workshop on Semantic Evaluations - SemEval '07 | — | 0 |

## 2006

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| William H. Starbuck | [Unlearning Ineffective or Obsolete Technologies](https://doi.org/10.1093/oso/9780199288519.003.0017) | Organizational Realities | — | 112 |
| Mikael Johansson et al. | [When Remembering Causes Forgetting: Electrophysiological Correlates of Retrieval-Induced Forgetting](https://doi.org/10.1093/cercor/bhl044) | Cerebral Cortex | — | 111 |
| Juan‐Gabriel Cegarra‐Navarro, Frank W. Dewhurst | [Linking shared organisational context and relational capital through unlearning](https://doi.org/10.1108/09696470610639121) | The Learning Organization | — | 83 |
| Malen Migueles, Elvira García‐Bajos | [Selective retrieval and induced forgetting in eyewitness memory](https://doi.org/10.1002/acp.1323) | Applied Cognitive Psychology | — | 64 |
| Aaron S. Benjamin | [The effects of list-method directed forgetting on recognition memory](https://doi.org/10.3758/bf03194005) | Psychonomic Bulletin & Review | — | 51 |
| Karen Becker | [Unlearning: A people development issue for sustainable change and innovation](https://openalex.org/W1525528991) | CQUniversity | — | 3 |

## 2005

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| René Hurlemann et al. | [Noradrenergic Modulation of Emotion-Induced Forgetting and Remembering](https://doi.org/10.1523/jneurosci.0228-05.2005) | Journal of Neuroscience | — | 164 |
| Juan Gabriel Cegarra Navarro, Beatriz Rodrigo Moya | [Business performance management and unlearning process](https://doi.org/10.1002/kpm.233) | Knowledge and Process Management | — | 90 |
| Karen Becker | [Individual and organisational unlearning: directions for future research](https://openalex.org/W3004920430) | QUT ePrints (Queensland University of Technology) | — | 85 |
| Harry Purser, Christopher Jarrold | [Impaired verbal short-term memory in Down syndrome reflects a capacity limitation rather than atypically rapid forgetting](https://doi.org/10.1016/j.jecp.2005.01.002) | Journal of Experimental Child Psychology | — | 84 |
| Carlos J. Gómez‐Ariza et al. | [Retrieval-induced forgetting in recall and recognition of thematically related and unrelated sentences](https://doi.org/10.3758/bf03193376) | Memory & Cognition | — | 63 |
| Karl‐Heinz T. Bäuml, Martina Zellner, Roman Vilimek | [When Remembering Causes Forgetting: Retrieval-Induced Forgetting as Recovery Failure.](https://doi.org/10.1037/0278-7393.31.6.1221) | Journal of Experimental Psychology Learning Memory and Cognition | — | 45 |
| Erica McWilliam | [Unlearning pedagogy](https://doi.org/10.5204/jld.v1i1.2) | Journal of Learning Design | — | 44 |

## 2004

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Leela Fernandes | [The Politics of Forgetting: Class Politics, State Power and the Restructuring of Urban Space in India](https://doi.org/10.1080/00420980412331297609) | Urban Studies | — | 349 |
| Christopher Diehl, Gert Cauwenberghs | [Svm incremental learning, adaptation and optimization](https://doi.org/10.1109/ijcnn.2003.1223991) | IJCNN | [GitHub](https://github.com/diehl/Incremental-SVM-Learning-in-MATLAB) | 259 |
| Anne P. DePrince, Jennifer J. Freyd | [Forgetting Trauma Stimuli](https://doi.org/10.1111/j.0956-7976.2004.00706.x) | Psychological Science | — | 156 |
| Rosemary Rushmer | [Unlearning in health care](https://doi.org/10.1136/qshc.2003.009506) | BMJ Quality & Safety | — | 127 |
| Ruth M. Ford, Sam Keating, Rina Patel | [Retrieval‐induced forgetting: A developmental study](https://doi.org/10.1348/0261510042378272) | British Journal of Developmental Psychology | — | 59 |
| Lynn B. Myers, Nazanin Derakshan | [To forget or not to forget: What do repressors forget and when do they forget?](https://doi.org/10.1080/02699930341000419) | Cognition & Emotion | — | 58 |
| Sharon Mavin, Patricia Bryans, Teresa Waring | [Unlearning gender blindness: new directions in management education](https://doi.org/10.1108/00251740410522287) | Management Decision | — | 38 |
| R Rushmer | [Unlearning in health care](https://doi.org/10.1136/qhc.13.suppl_2.ii10) | BMJ Quality & Safety | — | 33 |
| Erja Mustonen‐Ollila | [IS Process Innovation Unlearning in Organizations](https://openalex.org/W2112540216) | Journal of the Association for Information Systems | — | 5 |
| George S. Ford, Lawrence J. Spiwak | [Set It and Forget It? Market Power and the Consequences of Premature Deregulation in Telecommunications Markets](https://doi.org/10.2139/ssrn.487464) | SSRN Electronic Journal | — | 5 |
| Karen Becker, Brian L. Delahaye | [A Model of Individual and Organisational Unlearning](https://openalex.org/W1560492106) | CQUniversity | — | 4 |

## 2003

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Marilyn Cochran‐Smith | [Learning and unlearning: the education of teacher educators](https://doi.org/10.1016/s0742-051x(02)00091-4) | Teaching and Teacher Education | — | 693 |
| Paula T. Hertel, Melissa Gerstle | [Depressive Deficits in Forgetting](https://doi.org/10.1046/j.0956-7976.2003.psci_1467.x) | Psychological Science | — | 182 |
| Beverly E. Cross | [Learning or Unlearning Racism: Transferring Teacher Education Curriculum to Classroom Practices](https://doi.org/10.1207/s15430421tip4203_6) | Theory Into Practice | — | 114 |
| Bernet M. Elzinga et al. | [Directed forgetting between, but not within, dissociative personality states.](https://doi.org/10.1037/0021-843x.112.2.237) | Journal of Abnormal Psychology | — | 81 |
| Brian Conway | [Active Remembering, Selective Forgetting, and Collective Identity: The Case of Bloody Sunday](https://doi.org/10.1207/s1532706xid0304_01) | Identity | — | 61 |
| Mark Easterby‐Smith, Marjorie A. Lyles | [Re-reading <i>Organizational Learning</i>: Selective memory, forgetting, and adaptation](https://doi.org/10.5465/ame.2003.10025192) | Academy of Management Perspectives | — | 56 |
| Marit Westergaard | [Unlearning V2](https://doi.org/10.1075/eurosla.3.07wes) | EUROSLA Yearbook | — | 53 |

## 2002

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| James M. Sinkula | [Market‐based success, organizational routines, and unlearning](https://doi.org/10.1108/08858620210431660) | Journal of Business and Industrial Marketing | — | 188 |
| Karl‐Heinz T. Bäuml | [Semantic Generation Can Cause Episodic Forgetting](https://doi.org/10.1111/1467-9280.00464) | Psychological Science | — | 152 |
| Mohamad Y. Jaber, Maurice Bonney | [Lot sizing with learning and forgetting in set-ups and in product quality](https://doi.org/10.1016/s0925-5273(02)00322-5) | International Journal of Production Economics | — | 126 |
| David A. Nembhard, Napassavong Osothsilp | [Task complexity effects on between-individual learning/forgetting variability](https://doi.org/10.1016/s0169-8141(01)00070-1) | International Journal of Industrial Ergonomics | — | 104 |
| Sverker Sikström | [Forgetting curves: implications for connectionist models](https://doi.org/10.1016/s0010-0285(02)00012-9) | Cognitive Psychology | — | 61 |
| S. Arimoto, T. Naniwa, Hisashi Suzuki | [Selective learning with a forgetting factor for robotic motion control](https://doi.org/10.1109/robot.1991.131671) | ICRA | — | 47 |
| Seongwook Song et al. | [Variable forgetting factor linear least squares algorithm for frequency selective fading channel estimation](https://doi.org/10.1109/tvt.2002.1002509) | IEEE Transactions on Vehicular Technology | — | 41 |
| Benjamin Baez | [Learning To Forget: Reflections on Identity and Language](https://doi.org/10.1207/s1532771xjle0102_4) | Journal of Latinos and Education | — | 35 |
| Seongwook Song et al. | [Variable forgetting factor linear least squares algorithm for a frequency selective fading channel estimation](https://doi.org/10.1109/icassp.2000.861030) | ICASSP | — | 4 |
| O.R. Manzano et al. | [Inhibitory unlearning: a mechanism for increasing the storage capacity in an attractor network](https://doi.org/10.1109/kes.2000.885786) | KES'. Fourth International Conference on Knowledge-Based Intelligent Engineering Systems and Allied Technologies. Proceedings (Cat. No.00TH8516) | — | 0 |

## 2001

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Laurie A. Rudman, Richard D. Ashmore, Melvin L. Gary | ["Unlearning" automatic biases: The malleability of implicit prejudice and stereotypes.](https://doi.org/10.1037/0022-3514.81.5.856) | Journal of Personality and Social Psychology | — | 482 |
| M. B. Plenio, V. Vitelli | [The physics of forgetting: Landauer's erasure principle and information theory](https://doi.org/10.1080/00107510010018916) | Contemporary Physics | — | 235 |
| Plenio, M B, Vitelli, V | [The physics of forgetting: Landauer's erasure principle and information theory](https://openalex.org/W3099249975) |  | — | 157 |
| Laurie A. Rudman, Richard D. Ashmore, Melvin L. Gary | ["Unlearning" automatic biases: The malleability of implicit prejudice and stereotypes.](https://doi.org/10.1037//0022-3514.81.5.856) | Journal of Personality and Social Psychology | — | 94 |
| Karin M. Butler et al. | [A limit on retrieval-induced forgetting.](https://doi.org/10.1037//0278-7393.27.5.1314) | Journal of Experimental Psychology Learning Memory and Cognition | — | 65 |
| Steven R. Bauer, Nissanka B. Priyantha | [Secure data deletion for Linux file systems](https://openalex.org/W150515408) | USENIX Security | — | 64 |
| Michael C. Anderson | [Active Forgetting](https://doi.org/10.1300/j146v04n02_09) | Journal of Aggression Maltreatment & Trauma | — | 59 |
| Inga Markovits | [Selective Memory: How the Law Affects What We Remember and Forget about the Past—The Case of East Germany](https://doi.org/10.2307/3185395) | Law & Society Review | — | 45 |
| Elyse Brauch Lehman et al. | [Item-Cued Directed Forgetting of Related Words and Pictures in Children and Adults: Selective Rehearsal Versus Cognitive Inhibition](https://doi.org/10.1080/00221300109598900) | The Journal of General Psychology | — | 32 |
| Greg Bankoff | [Selective memory and collective forgetting. Historiography and the Philippine centennial of 1898](https://doi.org/10.1163/22134379-90003801) | Bijdragen tot de taal- land- en volkenkunde / Journal of the Humanities and Social Sciences of Southeast Asia | — | 21 |

## 2000

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Marilyn Cochran‐Smith | [Blind Vision: Unlearning Racism in Teacher Education](https://doi.org/10.17763/haer.70.2.e77x215054558564) | Harvard Educational Review | — | 364 |
| Audrey M. Kleinsasser | [Researchers, Reflexivity, and Good Data: Writing to Unlearn](https://doi.org/10.1207/s15430421tip3903_6) | Theory Into Practice | — | 168 |
| Rebekah E. Smith, R. Reed Hunt | [The influence of distinctive processing on retrieval-induced forgetting](https://doi.org/10.3758/bf03201240) | Memory & Cognition | — | 77 |
| Melvyn Coles, Adrian Masters | [Retraining and long-term unemployment in a model of unlearning by not doing](https://doi.org/10.1016/s0014-2921(99)00005-7) | European Economic Review | — | 57 |
| Dennis Sherwood | [The Unlearning Organisation](https://doi.org/10.1111/1467-8616.00146) | Business Strategy Review | — | 37 |
| John R Riesenberg | [CATASTROPHIC FORGETTING IN NEURAL NETWORKS](https://openalex.org/W2245036985) | OhioLink ETD Center (Ohio Library and Information Network) | [GitHub](https://github.com/ariseff/overcoming-catastrophic) | 4 |

## 1999

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| R. French | [Catastrophic forgetting in connectionist networks.](https://doi.org/10.1016/S1364-6613(99)01294-2) | Trends in Cognitive Sciences | — | 2771 |
| David Lei, John W. Slocum, Robert A. Pitts | [Designing organizations for competitive advantage: The power of unlearning and learning](https://doi.org/10.1016/s0090-2616(99)90019-0) | Organizational Dynamics | — | 363 |
| Michael A. Ciranni, Arthur P. Shimamura | [Retrieval-induced forgetting in episodic memory.](https://doi.org/10.1037//0278-7393.25.6.1403) | Journal of Experimental Psychology Learning Memory and Cognition | — | 214 |
| Kim S. Graham et al. | [Relearning and subsequent forgetting of semantic category exemplars in a case of semantic dementia.](https://doi.org/10.1037/0894-4105.13.3.359) | Neuropsychology | — | 117 |
| Ivo H. Daalder, Michael O’Hanlon | [Unlearning the Lessons of Kosovo](https://doi.org/10.2307/1149651) | Foreign Policy | — | 44 |
| Anthony Robins, Simon McCallum | [The consolidation of learning during sleep: comparing the pseudorehearsal and unlearning accounts](https://doi.org/10.1016/s0893-6080(99)00056-8) | Neural Networks | — | 42 |
| Fran�ois-Regis Chalaoux, Se�n I. O'Donoghue, Michaël Nilges | [Molecular dynamics and accuracy of NMR structures: Effects of error bounds and data removal](https://doi.org/10.1002/(sici)1097-0134(19990301)34:4<453::aid-prot5>3.0.co;2-7) | Proteins Structure Function and Bioinformatics | — | 18 |
| Carlos Pereira et al. | [Real-time Adaptive Training of RBFNN using a Selective Forgetting Algorithm](https://openalex.org/W1505122576) |  | — | 1 |

## 1998

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Steffen Wilson, Katherine Kipp | [The Development of Efficient Inhibition: Evidence from Directed-Forgetting Tasks](https://doi.org/10.1006/drev.1997.0445) | Developmental Review | — | 148 |
| Lynn B. Myers, Chris R. Brewin, Mick Power | [Repressive coping and the directed forgetting of emotional material.](https://doi.org/10.1037//0021-843x.107.1.141) | Journal of Abnormal Psychology | — | 94 |
| Anthony Robins, Simon McCallum | [Catastrophic Forgetting and the Pseudorehearsal Solution in Hopfield-type Networks](https://doi.org/10.1080/095400998116530) | Connection Science | — | 48 |

## 1997

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Philipp J. Kraemer, Jonathan M. Golding | [Adaptive forgetting in animals](https://doi.org/10.3758/bf03214337) | Psychonomic Bulletin & Review | — | 143 |
| Michael G. Pratt, Carole K. Barnett | [Emotions and Unlearning in Amway Recruiting Techniques](https://doi.org/10.1177/1350507697281005) | Management Learning | — | 77 |
| J. Leo van Hemmen | [Hebbian learning, its correlation catastrophe, and unlearning](https://doi.org/10.1088/0954-898x_8_3_001) | Network Computation in Neural Systems | — | 25 |

## 1996

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Marylène Cloître et al. | [Memory performance among women with parental abuse histories: Enhanced directed forgetting or directed remembering?](https://doi.org/10.1037//0021-843x.105.2.204) | Journal of Abnormal Psychology | — | 70 |
| Lars Kai Hansen, Jan Larsen | [Linear unlearning for cross-validation](https://doi.org/10.1007/bf02124747) | Advances in Computational Mathematics | — | 46 |
| Margaret Simons | [Selective amnesia [Review of Manne, Robert. The Culture of Forgetting ( 1996 ).]](https://openalex.org/W2549763809) | Eureka street | — | 1 |

## 1994

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| S. Wimbauer, Nikolaus Klemmer, J. Leo van Hemmen | [Universality of unlearning](https://doi.org/10.1016/0893-6080(94)90020-5) | Neural Networks | — | 24 |
| Jon‐Arild Johannessen, Arnulf Hauan | [Organizational Unlearning](https://doi.org/10.1111/j.1467-8691.1994.tb00115.x) | Creativity and Innovation Management | — | 8 |

## 1993

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Michael E. McGill, John W. Slocum | [Unlearning the organization](https://doi.org/10.1016/0090-2616(93)90054-5) | Organizational Dynamics | — | 393 |
| David Gaffan | [Additive effects of forgetting and fornix transection in the temporal gradient of retrograde amnesia](https://doi.org/10.1016/0028-3932(93)90032-u) | Neuropsychologia | — | 65 |
| Donald E. Trahan, Glenn J. Larrabee | [Clinical and methodological issues in measuring rate of forgetting with the verbal selective reminding test.](https://doi.org/10.1037//1040-3590.5.1.67) | Psychological Assessment | — | 7 |
| Donald E. Trahan, Glenn J. Larrabee | [Clinical and methodological issues in measuring rate of forgetting with the verbal selective reminding test.](https://doi.org/10.1037/1040-3590.5.1.67) | Psychological Assessment | — | 5 |

## 1992

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Bonnie D. Schwartz, Magda Gubala-Ryzak | [Learnability and grammar reorganization in L2A: against negative evidence causing the unlearning of verb movement](https://doi.org/10.1177/026765839200800102) | Utrecht | — | 169 |
| Jens Parkum, Niels Kjølstad Poulsen, J. HOLST | [Recursive forgetting algorithms](https://doi.org/10.1080/00207179208934228) | International Journal of Control | — | 111 |

## 1991

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Thomas M. Davidson, Kenneth S. Bowers | [Selective hypnotic amnesia: Is it a successful attempt to forget or an unsuccessful attempt to remember?](https://doi.org/10.1037//0021-843x.100.2.133) | Journal of Abnormal Psychology | — | 9 |
| Thomas M. Davidson, Kenneth S. Bowers | [Selective hypnotic amnesia: Is it a successful attempt to forget or an unsuccessful attempt to remember?](https://doi.org/10.1037/0021-843x.100.2.133) | Journal of Abnormal Psychology | — | 6 |

## 1990

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| J. Leo van Hemmen et al. | [Increasing the efficiency of a neural network through unlearning](https://doi.org/10.1016/0378-4371(90)90345-s) | Physica A Statistical Mechanics and its Applications | — | 41 |
| Jens Parkum, Niels Kjølstad Poulsen, Jan Holst | [Selective Forgetting in Adaptive Procedures](https://doi.org/10.1016/s1474-6670(17)51997-7) | IFAC Proceedings Volumes | — | 26 |
| Uri Fidelman | [Hemispheric competition learning and unlearning concepts of infinity](https://doi.org/10.1007/bf01207335) | Bioscience Reports | — | 5 |

## 1989

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Jonathan I. Klein | [Parenthetic Learning in Organizations: Toward the Unlearning of the Unlearning Model](https://doi.org/10.1111/j.1467-6486.1989.tb00729.x) | Journal of Management Studies | — | 132 |

## 1988

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Deborah Loewenberg Ball | [Unlearning to Teach Mathematics.](https://openalex.org/W1578973251) |  | — | 352 |
| John Robinson | [Unlearning and backcasting: Rethinking some of the questions we ask about the future](https://doi.org/10.1016/0040-1625(88)90029-7) | Technological Forecasting and Social Change | — | 161 |
| Natalie Walker, Judith Reitman Olson | [Designing keybindings to be easy to learn and resistant to forgetting even when the set of commands is large](https://doi.org/10.1145/57167.57201) | CHI | — | 8 |

## 1987

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Soura Dasgupta, Yih-Fang Huang | [Asymptotically convergent modified recursive least-squares with data-dependent updating and forgetting factor for systems with bounded noise](https://doi.org/10.1109/tit.1987.1057307) | IEEE T-IT | — | 227 |
| Fulin Zhuang, R. Balasubramanian | [Bad Data Processing in Power System State Estimation by Direct Data Deletion and Hypothesis Tests](https://doi.org/10.1109/tpwrs.1987.4335126) | IEEE Transactions on Power Systems | — | 21 |
| Fulin Zhuang, R. Balasubramanian | [Bad Data Processing in Power System State Estimation by Direct Data Deletion and Hypothesis Tests](https://doi.org/10.1109/mper.1987.5527244) | IEEE Power Engineering Review | — | 2 |

## 1985

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Kenichi Imai, Ikujiro Nonaka, Hirotaka Takeuchi | [Managing the New Product Development Process: How Japanese Companies Learn and Unlearn](https://openalex.org/W1515564696) | Medical Entomology and Zoology | — | 503 |
| Rudolf Kulhavý | [Restricted Exponential Forgetting in Real-Time Identification](https://doi.org/10.1016/s1474-6670(17)60716-x) | IFAC Proceedings Volumes | — | 39 |

## 1984

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Paul C. Nystrom, William H. Starbuck | [To avoid organizational crises, unlearn](https://doi.org/10.1016/0090-2616(84)90011-1) | Organizational Dynamics | — | 819 |
| Irene Mazurkewich | [The acquisition of the dative alternation: Unlearning overgeneralizations](https://doi.org/10.1016/0010-0277(84)90030-1) | Cognition | — | 221 |
| Herbert F. Crovitz, Walter F. Daniel | [Measurements of everyday memory: Toward the prevention of forgetting](https://doi.org/10.3758/bf03333861) | Bulletin of the Psychonomic Society | — | 135 |
| David G. Martin et al. | [Selective Forgetting of Aversive Memories Cued in the Right Hemisphere](https://doi.org/10.3109/00207458408985360) | International Journal of Neuroscience | — | 1 |

## 1983

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| J. J. Hopfield, David I. Feinstein, R. G. Palmer | [‘Unlearning’ has a stabilizing effect in collective memories](https://doi.org/10.1038/304158a0) | Nature | — | 430 |
| R. Edward Geiselman, Robert A. Bjork, Deborah L. Fishman | [Disrupted retrieval in directed forgetting: A link with posthypnotic amnesia.](https://doi.org/10.1037//0096-3445.112.1.58) | Journal of Experimental Psychology General | — | 309 |
| John W. Newstrom | [The Management of Unlearning: Exploding the 'Clean Slate' Fallacy](https://openalex.org/W2342425186) | Training and development journal | — | 67 |
| John F. Kihlstrom | [Instructed forgetting: Hypnotic and nonhypnotic.](https://doi.org/10.1037//0096-3445.112.1.73) | Journal of Experimental Psychology General | — | 50 |

## 1982

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Andrea A. diSessa | [Unlearning Aristotelian Physics: A Study of Knowledge‐Based Learning*](https://doi.org/10.1207/s15516709cog0601_2) | Cognitive Science | — | 477 |
| A DISESSA | [Unlearning Aristotelian physics: a study of knowledge-based learning](https://doi.org/10.1016/s0364-0213(82)80005-0) | Cognitive Science | — | 60 |

## 1981

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Bo Hedberg | [How Organizations Learn and Unlearn](https://openalex.org/W170821833) |  | — | 1836 |

## 1980

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Keith D. Horton, Randy Petruk | [Set differentiation and depth of processing in the directed forgetting paradigm.](https://doi.org/10.1037/0278-7393.6.5.599) | Journal of Experimental Psychology Human Learning & Memory | — | 34 |
| Keith D. Horton, Randy Petruk | [Set differentiation and depth of processing in the directed forgetting paradigm.](https://doi.org/10.1037//0278-7393.6.5.599) | Journal of Experimental Psychology Human Learning & Memory | — | 4 |

## 1976

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Carla J. Posnansky | [Directed forgetting among third and seventh graders](https://doi.org/10.1016/0361-476x(76)90031-x) | Contemporary Educational Psychology | — | 12 |

## 1975

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Colin M. MacLeod | [Long-term recognition and recall following directed forgetting.](https://doi.org/10.1037/0278-7393.1.3.271) | Journal of Experimental Psychology Human Learning & Memory | — | 120 |

## 1974

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Donald Homa, Susan J. Spieker | [Assessment of selective search as an explanation for intentional forgetting.](https://doi.org/10.1037/h0036831) | Journal of Experimental Psychology | — | 6 |

## 1973

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Walter Reitman et al. | [Strategy control and directed forgetting](https://doi.org/10.1016/s0022-5371(73)80003-9) | Journal of Verbal Learning and Verbal Behavior | — | 51 |
| Wayne L. Shebilske, William Epstein | [Effect of forget instructions with and without the conditions for selective search*](https://doi.org/10.3758/bf03198107) | Memory & Cognition | — | 8 |
| G Benneche | [[From the patient's point of view: The data-brain might harm the B-set, it does not forget my foolish youth].](https://openalex.org/W2470603314) | PubMed | — | 1 |

## 1972

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| William Epstein, Dominc W. Massaro, Lucinda Wilder | [Selective search in directed forgetting.](https://doi.org/10.1037/h0032791) | Journal of Experimental Psychology | — | 27 |

## 1971

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Wayne L. Shebilske, Lucinda Wilder, William Epstein | [Forget instructions: Effect of selective rehearsal and categorical distinctiveness.](https://doi.org/10.1037/h0031186) | Journal of Experimental Psychology | — | 27 |

## 1970

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Robert A. Bjork | [Positive forgetting: The noninterference of Items intentionally forgotten](https://doi.org/10.1016/s0022-5371(70)80059-7) | Journal of Verbal Learning and Verbal Behavior | — | 352 |
| Alan E. Gross, John Barresi, Edward E. Smith | [Voluntary forgetting of a shared memory load](https://doi.org/10.3758/bf03335607) | Psychonomic Science | — | 10 |

## 1969

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Bernard Weiner, Henry Reed | [Effects of the instructional sets to remember and to forget on short-term retention: Studies of rehearsal control and retrieval inhibition (repression).](https://doi.org/10.1037/h0026951) | Journal of Experimental Psychology | — | 71 |
| Leo Postman, Karen Stark, Diane Henschel | [Conditions of recovery after unlearning.](https://doi.org/10.1037/h0028036) | Journal of Experimental Psychology | — | 40 |

## 1966

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Norman J. Slamecka | [Differentiation versus unlearning of verbal associations.](https://doi.org/10.1037/h0023223) | Journal of Experimental Psychology | — | 48 |

## 1965

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Leo Postman, Geoffrey Keppel, Karen Stark | [Unlearning as a function of the relationship between successive response classes.](https://doi.org/10.1037/h0021585) | Journal of Experimental Psychology | — | 96 |
| Leo Postman | [Unlearning under conditions of successive interpolation.](https://doi.org/10.1037/h0022266) | Journal of Experimental Psychology | — | 48 |

## 1964

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Benton J. Underwood | [Degree of learning and the measurement of forgetting](https://doi.org/10.1016/s0022-5371(64)80028-1) | Journal of Verbal Learning and Verbal Behavior | — | 242 |

## 1961

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Harold R. Lindman, Ward Edwards | [Supplementary report: Unlearning the gambler's fallacy.](https://doi.org/10.1037/h0046635) | Journal of Experimental Psychology | — | 63 |
| David Stephenson Greiner | [Selective Forgetting in Alcoholics](https://doi.org/10.15288/qjsa.1961.22.580) | Quarterly Journal of Studies on Alcohol | — | 0 |

## 1952

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| John Daniel O'Malley | [Sex Differences in Selective Forgetting](https://openalex.org/W346967091) | Loyola eCommons (Loyola University Chicago) | — | 0 |

## 1945

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Franklin J. Shaw, Andy Spooner | [Selective forgetting when the subject is not 'ego-involved.'](https://doi.org/10.1037/h0059509) | Journal of Experimental Psychology | — | 11 |

## 1944

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Franklin J. Shaw | [Two determinants of selective forgetting.](https://doi.org/10.1037/h0059768) | Journal of Abnormal & Social Psychology | — | 12 |

## 1942

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Richard Wallen | [Ego-involvement as a determinant of selective forgetting.](https://doi.org/10.1037/h0060255) | Journal of Abnormal & Social Psychology | — | 35 |

## Undated

| Authors | Title | Venue | Code | Citations |
|---|---|---|---|---:|
| Yang Chen, Zheyan Luo, Zhiwen Tang | [YNU at SemEval-2025 Task 4: Synthetic Token Alternative Training for LLM Unlearning](https://www.semanticscholar.org/paper/ca7a477a4665e5eba24a021e24bb1e767bf55279) |  | — | 2 |
| Varshita Kolipaka et al. | [S ANITY C HECKS FOR E VALUATING G RAPH U NLEARNING](https://www.semanticscholar.org/paper/190d81153f41f84e45061d67d10e2df386f307c7) |  | — | 0 |
| Chi-Ming Kuan, Yifei Chen | [NEKO at SemEval-2025 Task 4: A Gradient Ascent Based Machine Unlearning Strategy](https://www.semanticscholar.org/paper/bef5c81b6acd580305ea7846d63d70a991ef3a1e) |  | — | 0 |
| Hoorieh Sabzevari et al. | [NLPART at SemEval-2025 Task 4: Forgetting is harder than Learning](https://www.semanticscholar.org/paper/035f0c64d8fdd3ad544eb23dc669bd5949e64e5b) |  | — | 0 |
| A. Balordi | [A Principled Framework for Parameter Estimation in Federated Unlearning](https://www.semanticscholar.org/paper/6f8f992638559787c91d2ea89433c0bbcbe99822) |  | — | 0 |
| Olivier Capp´e | [Methods and Algorithms for Approximate Machine Unlearning](https://www.semanticscholar.org/paper/7834ed0c597a2cfa83ac602ffe9c36f56cdd03ae) |  | — | 0 |
| Hongyin Shi et al. | [Machine Unlearning Challenge](https://www.semanticscholar.org/paper/7e233b84f51a0356668273d42f6498ab191c4313) |  | [GitHub](https://github.com/unlearning-challenge/starting-kit) | 0 |
| A. Pesudo, Pce | [ESC: Erasing Space Concept for Knowledge Deletion Supplementary Material](https://www.semanticscholar.org/paper/b5c5d40a3055ae8ed233ffbe781ec386fc8e1844) |  | — | 0 |
| Adam Ge, Aadya Goel | [Unlearning Mechanisms in Graph Models and Document Classification](https://www.semanticscholar.org/paper/b2f8df0d12d0575335e0b9201b907a0192f93e4a) |  | — | 0 |
