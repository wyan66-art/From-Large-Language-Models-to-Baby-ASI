# From Large Language Models to Baby ASI


**A Developmental Framework for Persistent, Embodied, Continually Learning Artificial Agents**


Author: Winston Y Yan


Live site: https://wyan66-art.github.io/From-Large-Language-Models-to-Baby-ASI/


## What this is


This project treats artificial superintelligence as a developmental process, not a scaled-up static model. It proposes a "Baby ASI" that grows through stages — from a dependent, embodied learner into a mature agent — with persistent identity, memory, and world models, and with safety gates at each stage.


The site presents the framework in English and Chinese (toggle in the header), with the seven falsifiable predictions (P1–P7), the seven-stage research plan, the formal model, and a discussion section.


## Papers


| Version | File | Date | Pages |
|---|---|---|---|
| **Revised V1 (current formal baseline)** | `Baby_ASI_Revised_V1_Nov_2026.pdf` | Nov 2026 | 12 |
| V1 (original) | `Baby_ASI_Research_Paper.pdf` | Aug 2026 | 9 |


The Revised V1 paper is the formal paper. It carries the new title, the formal model (§6), the predictions with metrics, baselines, and failure conditions (§9), and the safety gates (§11), with 24 references.


An honest note, stated in the paper itself: the formal model in §6 is a **specification**, not an implemented algorithm. The predictions are falsifiable claims, each with a metric, a baseline, and a failure condition — not established results.


## Version history


- **V1** (23 Aug 2026, 9 pp): the original paper — ASI as a developmental process; Baby ASI → Developing ASI → Mature ASI; seven-stage program.
- **Revised V1 / V1.5** (23 Nov 2026, 12 pp): revised after review. New title, expanded formal model, predictions, and safety sections. This is the current formal baseline. It is deliberately **not** called V2.
- **V2.1** (in preparation): centered on **AI Identity Continuity** — model and parameter transition, memory migration, AI forking and branch identity, and validated continuation vs. successor agent. It will also add 2025–2026 references (continual learning, agent memory, world models, model migration, multi-agent research); the current 24 references run through 2024.


## Repository contents


- `index.html` — the whole website (single file; bilingual, interactive).
- `Baby_ASI_Revised_V1_Nov_2026.pdf` — the Revised V1 paper (standalone file; the site links to it, it is not embedded in the HTML).
- `Baby_ASI_Research_Paper.pdf` — the original V1 paper, kept for the record.
- `README.md` — this file.


## Deployment


The site is published with GitHub Pages from the `main` branch root. To update it:


1. Edit the site in Muse (the "Baby ASI" Space), then export `index.html`.
2. Upload the new `index.html` to the repository root, replacing the old one.
3. If the paper changes, upload the new PDF as a standalone file and update the download link in the site — do not embed the PDF in the HTML again.
4. GitHub Pages rebuilds automatically (about a minute). If the live page still shows the old version, it is CDN cache; check with `?v=N` appended to the URL.


## Discussion and contact


- Discussion: the site has a discussion section (Giscus, backed by GitHub Discussions in this repository), or open a discussion directly at https://github.com/wyan66-art/From-Large-Language-Models-to-Baby-ASI/discussions
- Website correspondence: yan415822@gmail.com
- Paper correspondence: wyan66@gmail.com


## 中文简介


本项目把人工超级智能看作一个发育过程，而非放大后的静态模型：从依赖性的具身学习者（Baby ASI）逐步成长为成熟智能体，全程保持持续身份、记忆与世界模型，每一阶段设有安全门。当前正式版本为 Revised V1（2026 年 11 月，17 页）；V2.1 正在筹备中，核心是 AI 身份连续性（AI Identity Continuity）。网站提供中英文切换、七项可证伪预测（P1–P7）、七阶段研究计划与讨论区。
