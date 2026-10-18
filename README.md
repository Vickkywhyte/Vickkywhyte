### Victor Adegbe Daniel

Compliance specialist turned AI engineer — building evaluated, human-in-the-loop AI for financial crime compliance.

4 years in financial crime compliance at Wise, moving from customer support through verification and due diligence to Enhanced Due Diligence Quality Specialist. I have reviewed more than 10,000 consumer and business profiles across EDD, AML, sanctions and fraud controls. At Wise I built a root cause analysis framework for AI conversation failures that cut investigation time by 35% and fed the golden dataset used for model retraining.

CFCS certified (ACFCS) · CGSS in progress · Tallinn, Estonia · [LinkedIn](https://www.linkedin.com/in/victor-daniel-cfcs-453983191/)

#### What I build

AI systems for high-stakes domains — where being wrong has consequences.

The through-line is evaluation: measuring what a system actually does, not what it is supposed to do. Hallucination rates. Faithfulness scores. Retrieval precision. Refusal correctness. Bootstrap confidence intervals on every aggregate.

#### Shipped projects

**[Compliance Runtime](https://github.com/Vickkywhyte/compliance-runtime)** — open-source runtime that sits between an AI agent and its tools. Rule-based policies allow, deny or escalate every tool call before it executes, with no LLM in the decision path; high-stakes actions wait for human approval; every decision lands in a SHA-256 hash chain with Ed25519 signatures, exportable as a PDF dossier mapped to EU AI Act Article 12. 46 security controls, 17 evaluation metrics with bootstrap CIs, 369 tests, $0 runtime.

**[Compliance Monitoring Agent](https://github.com/Vickkywhyte/compliance-monitoring-agent)** — autonomous EU regulatory change monitor (sanctions lists, EUR-Lex, EBA). The agent proposes; a human always decides. 39 security controls, 20 evaluation metrics across six pipeline stages, 211 tests, $0 runtime with a local Ollama fallback.

**[Document Intelligence Platform](https://github.com/Vickkywhyte/doc-intelligence-platform)** — RAG with first-class evaluation. 3 chunkers × 2 embedders on a 75-question golden set, 15 of them deliberately unanswerable. Best config 0.933 answer accuracy; lowest hallucination rate 3.1%; full matrix for $0.46. 378 tests.

**[Multi-Model Router](https://github.com/Vickkywhyte/Multi-Model-Router)** — cost-aware LLM gateway that classifies prompt complexity and routes each request to the cheapest capable Gemini tier, logging cost, latency and human quality feedback per request.

Earlier builds, kept private: an agentic RAG assistant with planning and verification loops, a sanctions research assistant, and a multi-model analyst council with anonymised peer review.

#### How I build

I write the specs, threat models and evaluation designs with Claude as a drafting partner, then use Claude Code to implement them phase by phase. Each flagship README has a "How this was built" section, and the design documents live in the repo next to the code. The flagship repos are MIT licensed.
