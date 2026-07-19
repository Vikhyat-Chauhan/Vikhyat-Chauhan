## Vikhyat Chauhan — Applied AI & Software Engineer

I build production AI systems and the software they run on — RAG, agents, and the backend
microservices behind them. M.S. Computer Engineering, Virginia Tech.

### What I've shipped (live)

- **[specced](https://github.com/Vikhyat-Chauhan/specced)** — local-first clinical-notes → **FHIR** pipeline: a QLoRA-fine-tuned Qwen2.5-Coder-7B running a LangGraph `plan → retrieve → act → evaluate` loop, with HIPAA-safe de-identification and SNOMED/RxNorm/ICD-10/LOINC terminology RAG. Fine-tuning took held-out pass rate **0/20 → 20/20** (resource-F1 0.42 → 0.99); every output is schema-validated and field-scored against gold. *Local-first by design — no hosted demo (PHI never leaves the box).*
- **[ProfessionalRAG](https://github.com/Vikhyat-Chauhan/ProfessionalRAG)** — production RAG service: two-stage retrieval (BGE embeddings → cross-encoder rerank over Pinecone), Claude generation, LLM-as-judge evals (Hit@K, MRR), and per-query cost/latency telemetry. Built from scratch, no LangChain. → **[live demo](https://vikhyatchauhan.com)**
- **[Hearth](https://github.com/Vikhyat-Chauhan/Hearth)** — full-stack shared-household app: Next.js/TypeScript, React, Supabase/Postgres, Drizzle ORM, two-way Google Calendar sync, deployed on Vercel. → **[live](https://hearth.tnmlabs.com)**

### Before that

- **GE HealthCare** — led a legacy C++ monolith → Kubernetes / Spring Boot microservices migration (~80% faster deployments) and CI/CD quality gates (−60% release defects) in an FDA-regulated (IEC 62304) environment. *GE Impact Award.*
- **Founder, 0→1** — bootstrapped a hardware startup: patented a microcontroller communication protocol, built an AWS/MQTT backend scaling 0 → 1,000+ devices at 99.9% uptime, shipped to 100+ homes.
- **M.S. thesis (NSF-funded)** — brain-inspired autonomous-navigation framework: 34.6% compute-energy reduction with zero deadline violations across 1,000 runs (p < 0.0001).

`Python` · `RAG` · `LLMs` · `LangGraph` · `Fine-tuning (QLoRA)` · `FHIR` · `FastAPI` · `Pinecone` · `TypeScript` · `Next.js` · `Microservices` · `Docker` · `Kubernetes` · `AWS`

✉️ vikhyat.chauhan@gmail.com · 🔗 [vikhyatchauhan.com](https://www.vikhyatchauhan.com) · [LinkedIn](https://www.linkedin.com/in/vikhyat-chauhan)
