# Hi, I'm Richard 👋

**Product Manager | Enterprise AI · Agent Evaluation · Human-Data Quality**

I build data and AI products that help teams make better decisions. My background spans enterprise data platforms, analytics, customer data, and AI workflows. I'm now focusing on a harder question: **how do we know an AI system is reliable enough to use?**

I work across product discovery, system design, evaluation, and launch judgment. I'm especially interested in the human-data infrastructure behind trustworthy AI: high-quality labels, reviewer disagreement, error analysis, and the feedback loops that turn evaluation findings into product improvements.

[Portfolio](https://aboutrichie.vercel.app) · [LinkedIn](https://www.linkedin.com/in/richieriri/) · [Email](mailto:richardconstantine67@gmail.com)

## 🚀 Featured projects

### 🧪 [Evalxiety — evidence before release](https://github.com/richardan01/evalxiety)

A working prototype for testing agents, reviewing outputs, comparing versions, and making explicit ship/no-ship decisions.

**A revealing result:** In a **20-case synthetic** merchant-pricing experiment, the candidate improved from **9/20 to 18/20** cases passing all four deterministic checks. **It still failed the release gate**: one case regressed on mandatory CFO approval, and another remained incorrect. A 90% aggregate pass rate wasn't enough to justify shipping.

**What this demonstrates:** release judgment, regression analysis, human review, and clearly bounded evaluation claims. The LLM judge is **not yet calibrated**; the demo is not evidence of production reliability.

[Explore Evalxiety →](https://github.com/richardan01/evalxiety)

### 🔬 [AI-Product-Lab — understanding agent failures](https://github.com/richardan01/AI-Product-Lab)

A public research-and-learning workspace for evaluating **agent trajectories**, not just final answers. It examines task success, tool choice, parameter grounding, error recovery, context retention, efficiency, and goal alignment.

The lab includes trace-based evaluations and an [evaluation integrity case study](https://github.com/richardan01/AI-Product-Lab/blob/main/evals/regeval/discovery-pass-2026-06-28.md) documenting how a contaminated held-out set invalidated an earlier claim.

**What this demonstrates:** reproducibility, failure analysis, evaluation provenance, and willingness to correct invalid measurement.

[Explore AI-Product-Lab →](https://github.com/richardan01/AI-Product-Lab)

### 📊 [Finance Bot — reviewable AI analysis](https://github.com/richardan01/Finance-bot)

A finance-analysis assistant **prototype** exploring structured answers, charting, uncertainty, and human oversight. Its finance data access is simulated; it is not a deployed, verified financial decision system.

[Explore Finance Bot →](https://github.com/richardan01/Finance-bot)

## 🧭 My product approach

```text
Understand the user problem
       ↓
Define the decision and risk
       ↓
Design the workflow and data
       ↓
Evaluate failures with people and code
       ↓
Make an evidence-backed release decision
       ↓
Observe outcomes and improve
```

I try to distinguish **what the product does**, **what experiments show**, and **what remains unproven**. A good demo is a starting point; it is not a reliability claim.

## 🎯 What I'm building toward

My focus is **human-data and evaluation platforms for frontier AI**—systems that help researchers, engineers, and product teams collect useful judgments and translate them into measurable improvements.

Current learning and build priorities:

- **Human-data workflows:** annotation instructions, independent labeling, adjudication, and label provenance.
- **Evaluation science:** representative sampling, held-out sets, judge calibration, failure slices, and confidence intervals.
- **Researcher experience:** trace review, debugging workflows, evaluation data discoverability, and feedback-to-fix cycles.
- **Platform outcomes:** reviewer throughput, label quality, evaluation cost, and time to validated product decisions.

These are focus areas and planned improvements, **not claims that I've shipped a research data platform at scale**.

---

🤝 **I'm interested in connecting with teams working on enterprise AI, agent reliability, evaluation infrastructure, and human-data quality.** [Connect on LinkedIn](https://www.linkedin.com/in/richieriri/) or explore my [portfolio](https://aboutrichie.vercel.app).
