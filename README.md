### Victor Adegbe Daniel

Compliance specialist turned AI engineer — building evaluated, human-in-the-loop AI for financial crime compliance.

4+ years in AML, KYC, EDD, sanctions compliance and fraud investigation across fintech, crypto and telecoms — Wise (customer support → due diligence → Enhanced Due Diligence Quality Specialist), CoinMetro (AML compliance) and Bella Mobile (fraud consulting). At Wise I built a root cause analysis framework for AI conversation failures that cut investigation time by 35% and fed the golden dataset used for model retraining.

CFCS certified (ACFCS) · CGSS in progress · Tallinn, Estonia · [LinkedIn](https://www.linkedin.com/in/victor-daniel-cfcs-453983191/)

#### What I build

AI systems for high-stakes domains — where being wrong has consequences.

The through-line is evaluation: measuring what a system actually does, not what it is supposed to do. Hallucination rates. Faithfulness scores. Retrieval precision. Refusal correctness. Bootstrap confidence intervals on every aggregate.

#### Shipped projects

**[Compliance Monitoring Agent](https://github.com/Vickkywhyte/compliance-monitoring-agent)** — autonomous EU regulatory change monitor (sanctions lists, EUR-Lex, EBA). The agent proposes; a human always decides. 39 security controls, 20 evaluation metrics across six pipeline stages, 211 tests, $0 runtime with a local Ollama fallback.

**[Document Intelligence Platform](https://github.com/Vickkywhyte/doc-intelligence-platform)** — RAG with first-class evaluation. 3 chunkers × 2 embedders on a 75-question golden set, 15 of them deliberately unanswerable. Best config 0.933 answer accuracy; lowest hallucination rate 3.1%; full matrix for $0.46. 378 tests.

**[Multi-Model Router](https://github.com/Vickkywhyte/Multi-Model-Router)** — cost-aware LLM gateway that classifies prompt complexity and routes each request to the cheapest capable Gemini tier, logging cost, latency and human quality feedback per request.

**[Agentic RAG Assistant](https://github.com/Vickkywhyte/agentic_rag_project)** — multi-hop reasoning with autonomous planning and a search / calculate / verify tool loop, returning execution traces and source verification.

**[Sanctions CGSS RAG](https://github.com/Vickkywhyte/sanctions-cgss-rag)** — ACAMS CGSS exam prep across OFAC, UN and EU frameworks, with retrieval surfaced next to every answer.

**[Competitive Intelligence Council](https://wise-competitive-intelligence.vercel.app)** (live demo) — four analysts on four different LLMs, anonymised peer review, and an executive synthesis that separates agreement from uncertainty.

Open source; the flagship repos are MIT licensed and documented in depth.
