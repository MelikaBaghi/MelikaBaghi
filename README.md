## Melika Baghi

**Ph.D. Candidate in Industrial & Systems Engineering at Georgia Tech**, working at the
intersection of machine learning, statistics, and data-driven decision making. I develop
methods for high-dimensional, structured and incomplete data, with applications spanning
healthcare, scientific computing, and sequential decision problems.

`Python` · `PyTorch` · `scikit-learn` · `XGBoost` · `SQL` · `Statistical ML`

I also hold an M.S. in Statistics (Georgia Tech) and an M.S. in Industrial Engineering
with a focus on Healthcare Systems. Advised by Kamran Paynabar and Xiao Liu.

**[melikabaghi.github.io](https://melikabaghi.github.io)** ·
[Google Scholar](https://scholar.google.com/citations?user=UNGLFyUAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/melika-baghi) ·
mbaghi3@gatech.edu

---

### [Selected projects](https://melikabaghi.github.io/projects.html)

| Project | What it does | Links |
|---|---|---|
| **Medical tourism hospital simulation** | Hybrid agent-based + discrete-event model of a multi-specialty international-patient department, with channel choice, physician switching, abandonment and deterioration modeled explicitly. A 256-run factorial screen finds **bed capacity** the most consistent driver of waiting; against an otherwise identical discrete-event-only model, the hybrid model's mean inpatient admission wait is **42% lower** (14.8 vs 25.8 days, *p* < 0.001). | [code](https://github.com/MelikaBaghi/IPD-medical-tourism-simulation) · [paper](https://arxiv.org/abs/2605.19139) · [DOI](https://doi.org/10.5281/zenodo.22646799) |
| **RouteCert** | Certifies a prediction when the evidence already collected determines the decision, and otherwise abstains and says which modality to acquire next, with finite-sample guarantees conditional on the modality pattern. Evaluated on four datasets spanning ECG, speech and wearable sensing. | [code](https://github.com/MelikaBaghi/RouteCert) · [paper](https://arxiv.org/abs/2608.15520) |
| **cXGBoost** | Constrained gradient boosting that enforces the manifold-chart bound inside every leaf, so predicted reduced-order bases are valid by construction. On four parametric problems (cylinder wake, Kolmogorov flow, the Kuramoto–Sivashinsky equation, a forced beam) it has lower mean reconstruction error than the projected Gaussian process and Grassmann interpolation. | [code](https://github.com/MelikaBaghi/cXGBoost) · [paper](https://arxiv.org/abs/2605.04130) |
| **State-EXP3** | Delayed bandits with drifting state losses: one delayed outcome is charged to every action that could have produced that state, at a cost set by an effective dimension. Reduces regret up to **79%** against action-level weighting and **32–68%** against a rate-optimal delayed-bandit baseline. | [code](https://github.com/MelikaBaghi/State-exp3) · [paper](https://arxiv.org/abs/2609.01761) |
| **Tensor-structured surrogates** | Keeps the multiway structure of simulation output instead of flattening it: every mode gets its own subspace, interpolated on its own manifold, with cores aligned before one low-rank surrogate is fitted. Across five PDE benchmarks in 2D and 3D, the interpolation size is **13× to 482× smaller** and cached queries run 3.3× to 8.5× faster than a single-subspace surrogate, with mean errors within 0.22 percentage points. | [paper](https://arxiv.org/abs/2610.34559) |
| **LLM agents as simulated users** | Three dated OpenAI model snapshots, with a fixed prompt, strict JSON schema and cached replies, acted as 36 synthetic patient profiles inside a queueing simulation of eight capacity policies (120 paired seeds). Matched on baseline rates, they **disagreed on the best policy** under a demand surge; simple behavioral rules picked the same policy, so the study stopped at its go/no-go gate. | [details](https://melikabaghi.github.io/projects.html) |
| **Retrieval-augmented claim verification** | Local RAG over 5,183 SciFact abstracts: BM25, two dense retrievers, rank fusion and reranking, with an open 1.5B LLM returning JSON verdicts with citations. Hybrid retrieval raised nDCG@10 from **0.678 to 0.724** over BM25 (*p* = 0.0008); one distractor abstract cut faithful rationales from 0.251 to 0.142. | [details](https://melikabaghi.github.io/projects.html) |

### [Publications & preprints](https://melikabaghi.github.io/publications.html)

| | Status |
|---|---|
| [A Product-Grassmann Tucker Surrogate for Parametric Field Prediction](https://arxiv.org/abs/2610.34559) | Submitted, *Journal of Computational Physics* |
| [Constrained Extreme Gradient Boosting for Parametric Proper Orthogonal Decomposition Subspace Prediction](https://arxiv.org/abs/2605.04130) | Under review |
| [Managing Shared Hospital Capacity for Medical Tourism: Patient Behavior and Hybrid Simulation](https://arxiv.org/abs/2605.19139) | Under review, *Health Care Management Science* |
| [Conditional Validity for Adaptive Modality Acquisition: When the Policy Chooses Its Own Calibration Group](https://arxiv.org/abs/2608.15520) | Under review |
| [Pooling and Drift in Delayed Bandits](https://arxiv.org/abs/2609.01761) | Under review |
| Supervised Active-Subspace Input Reduction and Risk-Controlled Field Uncertainty | Completed manuscript |

Full list on [Google Scholar](https://scholar.google.com/citations?user=UNGLFyUAAAAJ&hl=en) ·
[CV](https://melikabaghi.github.io/assets/Melika_Baghi_CV.pdf) ·
[Resume](https://melikabaghi.github.io/assets/Melika_Baghi_Resume.pdf)

### Interests

High-dimensional statistical learning · Uncertainty quantification and conformal prediction ·
Multimodal learning and missing data · Sequential decision making and bandits ·
Reduced-order and surrogate modeling · Tensor and geometry-aware learning · Scientific machine learning ·
Evaluation of LLMs and AI agents
