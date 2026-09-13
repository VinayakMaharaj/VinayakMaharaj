<div align="center">

# Vinayak Maharaj

**Software Engineer · AI Systems · Full-Stack**

[![Portfolio](https://img.shields.io/badge/Portfolio-vinayakmaharaj.dev-5b9cf6?style=flat-square&logoColor=white)](https://vinayakmaharaj.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vinayak--maharaj-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinayak-maharaj/)
[![Goodreads](https://img.shields.io/badge/Goodreads-460%20books-F4A460?style=flat-square&logo=goodreads&logoColor=white)](https://www.goodreads.com/user/show/165139028-vinayak)
[![Email](https://img.shields.io/badge/Email-vinayakcpa@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vinayakcpa@gmail.com)

</div>

---

B.Sc. Computer Science & Statistics, University of Toronto (Mathematics minor, 2025). I build AI systems that run in production — LLM pipelines, RAG architectures, anomaly detection, full-stack SaaS. Recently completed research with Prof. Patrick Hosein at TTLab on zero-shot LLM reasoning in long-horizon decision environments, submitted to IEEE ICTMOD 2026.

From Trinidad and Tobago. Based in Toronto.

---

## What I'm Working On

- **Maritime KYC/AML Platform** — building a custom compliance platform for a financial services firm, replacing a legacy World-Check integration. Entity resolution over sanctions/PEP data using pgvector + LLMs, projected to save ~$200k/year and manage 300k+ client records
- **"Can an LLM Play Balatro Without Ever Practicing?"** — submitted to IEEE ICTMOD 2026. Compared heuristic, zero-shot LLM, and RAG agents on long-horizon decision-making under uncertainty, using Balatro as a controlled testbed
- **Applied AI systems** — production RAG pipelines, agentic workflows, LLM-powered SaaS

---

## Selected Work

**Maritime Financial Group** *(Software Engineer, Contract — Sep 2025 to present)*
- Building a metadata-driven KYC/AML compliance platform replacing Refinitiv World-Check — sanctions/PEP screening with LLM-based entity resolution over pgvector, projected to save ~$200k/year and handle 300k+ client records
- Built an end-to-end firewall and VPN anomaly detection pipeline ingesting 100k+ log events per week — automated risk scoring reduced manual analysis time by 70%
- Designed a hybrid detection system combining a rules engine, Isolation Forest, and autoencoder over 5-minute windows, targeting login bursts and multi-region access anomalies with explainable per-alert scoring
- Shipped a Next.js monitoring dashboard with grouped alerts, drill-down views, and trend analytics — cut average analyst investigation time per incident by 40% and reduced repeated false-positive escalations

**["Can an LLM Play Balatro Without Ever Practicing?"](https://github.com/VinayakMaharaj/balatro_research)** *(IEEE ICTMOD 2026, submitted)*
- Compared five agents — a floor baseline, a hand-coded heuristic, a zero-shot LLM, and two RAG variants — on long-horizon strategic decision-making in Balatro
- Found zero-shot LLM reasoning matches a hand-coded heuristic outright, and that LLM reasoning *over* expert strategy knowledge beats deterministic execution of that same knowledge
- Also trained a MaskablePPO RL agent to ~310M timesteps; documented its failure to learn long-horizon strategy as a finding on architectural insufficiency, not just an abandoned attempt

**[Inbox Copilot](https://github.com/VinayakMaharaj/Inbox-Copilot)**
- Built a production AI email client where reply drafts are grounded in real Gmail/Outlook history via LangChain + Pinecone RAG, with real-time inbox sync via Aurinko webhooks and multi-account support
- Shipped as full SaaS with Stripe subscription billing, free/pro feature gating, and end-to-end type safety via tRPC

**[AI Developer Collaboration Platform](https://github.com/VinayakMaharaj/AI-Developer-Collaboration-Platform)**
- Built a RAG platform that ingests GitHub repositories via the GitHub API, indexes source files and commits into pgvector, and answers natural-language questions about any codebase with exact source-file citations
- Added AssemblyAI meeting transcription indexed alongside code context; shipped credit-based SaaS billing with Stripe, deployed via Docker on Fly.io

**[Prepwise](https://github.com/VinayakMaharaj/jsm_mock_interview_platform)**
- AI mock interview platform where a Vapi voice agent conducts real-time interviews, generates role-specific questions via Google Gemini, and scores answers across 5 structured criteria
- Validated across 100+ sessions with Firebase Auth and Firestore persistence

**[F1 Lap Time Predictor](https://github.com/VinayakMaharaj/F1-2025-Predictions)**
- Trained an LSTM on Monaco GP 2023 telemetry via FastF1 to predict next-lap time from a 10-lap rolling window; compared against an XGBoost baseline with SHAP explainability
- Tyre degradation and sector consistency were stronger signals than raw top speed — the data made this project inevitable

**[NBA Hot Hand Bayesian Analysis](https://github.com/VinayakMaharaj/nba-hot-hand-bayesian-analysis)**
- Tested the Hot Hand Fallacy across 15 NBA players using Bayesian regression in PyMC; compared Multivariate Normal, Horseshoe, and Spike-and-Slab priors — reduced model divergences by 20% via Metropolis-Hastings tuning
- Presented model selection rationale, posterior diagnostics, and sports analytics implications to the UofT Statistics department head

**[CommerceCore](https://github.com/VinayakMaharaj/CommerceCore)**
- Production-style e-commerce REST API in Java with JWT authentication, role-based access control, and full cart/order/product management
- Clean layered architecture: Controller → Service → Repository → DTO

**[Algorithmic Trading Backtest](https://github.com/VinayakMaharaj/Algorithmic-Trading-Project)**
- Backtested a Twitter engagement-ratio signal against NASDAQ across 2022 — portfolio outperformed benchmark by up to 25%
- Built full signal generation, portfolio simulation, and performance attribution pipeline from scratch

---

## Tech

| | |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · Java · SQL · R |
| **AI / LLM** | LangChain · LLM APIs · RAG · Pinecone · pgvector · sentence-transformers · PyTorch · HuggingFace · scikit-learn · stable-baselines3 · Vapi |
| **Frontend** | Next.js · React · tRPC · GraphQL · Tailwind |
| **Backend** | Node.js · Express · Prisma · NextAuth · Spring Boot · Flask |
| **Infrastructure** | Docker · AWS (S3, SES) · Vercel · Railway · Supabase · PostgreSQL · MongoDB · Firebase · Upstash Redis · BullMQ · Stripe · Fly.io · Sentry · Weights & Biases · Git |
---

## Certifications

- **[IBM RAG and Agentic AI](https://coursera.org/verify/professional-cert/1X3A3XVN39GM)** — Professional Certificate, 8 courses (LangChain, LangGraph, CrewAI, AutoGen) · Oct 2025
- **[Generative AI with LLMs](https://coursera.org/verify/8DDJjX7DYO0A)** — AWS + DeepLearning.AI · Jun 2025
- **[Machine Learning Specialization](https://coursera.org/verify/specialization/AD3DUHHMV4F3)** — DeepLearning.AI + Stanford, Andrew Ng · Jan 2024

---

## GitHub Activity

![](https://github-profile-summary-cards-three.vercel.app/api/cards/profile-details?username=VinayakMaharaj&theme=nord_dark)

<div align="center">

![](https://github-profile-summary-cards-three.vercel.app/api/cards/repos-per-language?username=VinayakMaharaj&theme=nord_dark)
![](https://github-profile-summary-cards-three.vercel.app/api/cards/most-commit-language?username=VinayakMaharaj&theme=nord_dark)
![](https://github-profile-summary-cards-three.vercel.app/api/cards/stats?username=VinayakMaharaj&theme=nord_dark)
![](https://github-profile-summary-cards-three.vercel.app/api/cards/productive-time?username=VinayakMaharaj&theme=nord_dark&utcOffset=-4)

</div>

---

## Open To

Software Engineering and ML/AI Engineering roles in Toronto — backend-leaning, full-stack, or anything at the intersection of AI and practical software. Especially interested in roles where I can own systems end-to-end.

`vinayakcpa@gmail.com` · [vinayakmaharaj.dev](https://vinayakmaharaj.dev)


<div align="center">
  <a href="https://commit-history.com/VinayakMaharaj">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/VinayakMaharaj?theme=dark" />
      <img alt="VinayakMaharaj's commit history" src="https://commit-history.com/embed/VinayakMaharaj" />
    </picture>
  </a>
</div>
