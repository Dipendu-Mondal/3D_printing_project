# Optimization of 3D Printing Technologies for Application-Specific Manufacturing

## 📌 Overview
Analyzed and optimized multiple additive manufacturing (AM) processes to select the best technology for fabricating a **customized simple generator** across different application scenarios. Work included research, a decision matrix, cost–performance trade-offs, and client-ready recommendations.

## 🎯 Objectives
- Compare leading AM technologies (e.g., FDM, SLA, SLS, DMLS/SLM, MJF).
- Evaluate material compatibility, mechanical performance, surface finish, accuracy, build size, and cost.
- Recommend one or two optimal processes per application scenario.
- Document assumptions, trade-offs, and risks.

## 🔬 Methodology
1. **Requirements capture:** Functional loads, tolerances, environment, budget, lead time.
2. **Process shortlist:** Screened by available materials and part geometry constraints.
3. **Scoring model:** Normalized scores (0–10) for Strength, Accuracy, Surface Finish, Cost/Part, Lead Time, Post-Processing.
4. **Weighted decision matrix:** Weights set by scenario (e.g., prototype vs. end-use).
5. **Sensitivity analysis:** Tested robustness of the recommendation to weight changes.

## 🧮 Decision Matrix (example)
| Process | Materials | Strength | Accuracy | Finish | Cost | Lead Time | Overall* |
|---|---|---:|---:|---:|---:|---:|---:|
| FDM | PLA/ABS/PA-CF | 6 | 6 | 5 | 9 | 8 | 7.1 |
| SLA | Photopolymer | 5 | 9 | 9 | 7 | 7 | 7.8 |
| SLS | Nylon/PA12 | 8 | 7 | 7 | 6 | 7 | 7.4 |
| MJF | PA12/PA12GB | 8 | 7 | 7 | 6 | 8 | 7.7 |
| DMLS/SLM | Al/SS/Ti | 10 | 8 | 6 | 3 | 5 | 7.1 |

\* Overall = weighted sum (weights tuned per scenario). Replace with your actual scores.

## 📊 Key Outcomes
- Compared **5+ AM processes** against **6 evaluation criteria**.
- Recommended **2 optimal processes** tailored to prototyping vs. end-use.
- Achieved **~25–30% cost efficiency** (prototype scenario) while meeting performance targets.
- Delivered a concise recommendation report and presentation for the client.

## 🛠️ Tools & Skills
Additive Manufacturing • DfAM • Trade-off & Multi-criteria Decision Making • Cost Modeling • Technical Writing & Presentation

## 📂 Repository Structure
