# Alex Efimik

**Pre-Sales Engineer / ML Platform — sovereign AI infrastructure, on-premises LLM serving, GPU orchestration.**

Dubai, UAE.

---

## Focus

- On-premises LLM serving on H100/H200 clusters: vLLM, SGLang, NVIDIA NIM, TensorRT-LLM, llm-d
- GPU orchestration: OpenShift AI, KubeRay, Run:ai / KAI Scheduler, fractional GPU and MIG
- Sovereign cloud architecture: DESC-aligned, air-gapped deployments, multi-tenant GenAI PaaS
- Retrieval and evaluation harnesses: hybrid retrieval, structured generation, citation-grounded RAG, confidence-routing patterns

---

## Selected projects

### [harness-eval](https://github.com/Alexey3250/harness-eval) — *the harness is the variable, the model is the constant*
Empirical comparison of prompt and retrieval harnesses around a fixed open-weight model on a UAE legal corpus. 477 articles across 12 laws, 20-question gold set, four harnesses (naked / minimal / constrained / few-shot), citation-accuracy and out-of-scope refusal scoring. Framed as a certification harness, not a chatbot.
**Stack:** Next.js · TypeScript · Cerebras Cloud · Python · BGE-M3 · Qdrant
**Live:** [harness-eval.vercel.app](https://harness-eval.vercel.app) · [findings](https://harness-eval.vercel.app/findings)

### [sovereignty-stress-test](https://github.com/Alexey3250/sovereignty-stress-test) — measurement framework for on-prem LLM stacks
Comparative serving harness for vLLM, TGI and llm-d on identical workloads — TTFT, TPOT, throughput, KV-cache behaviour. The kind of internal validation lab any sovereign-cloud NCP needs before refreshing its model catalogue.
**Live:** [sovereignty-stress-test.vercel.app](https://sovereignty-stress-test.vercel.app)

### [trustworthy-rag-demo](https://github.com/Alexey3250/trustworthy-rag-demo) — confidence-routing RAG pattern
Three-tier router (gold / amber / gray) that returns grounded answers when retrieval is confident, asks for clarification when ambiguous, and refuses without calling the LLM when out of scope. Jurisdiction-portable; demonstrated on the Service NSW open-data corpus, the same pattern wraps any government open-data source.
**Live:** [trustworthy-rag-demo.vercel.app](https://trustworthy-rag-demo.vercel.app)

---

## Stack

**Inference engines** vLLM · SGLang · TensorRT-LLM · NVIDIA NIM · llm-d
**Orchestration** Kubernetes · OpenShift AI · KubeRay · Run:ai / KAI Scheduler · LiteLLM
**GPU and systems** NVIDIA H100 / H200 · CUDA · DCGM · MIG · RTX 3090 (local)
**Retrieval** BGE-M3 · Qdrant · hybrid search · LangGraph
**Languages** Python · TypeScript · Bash
**Frontend** Next.js · React · Tailwind
**Inference cloud** Cerebras · Vercel

---

## Languages

English (working) · Russian (native) · Czech (working)

---

## Contact

📧 a.efimik@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/efimik/)
📱 [WhatsApp](https://wa.me/971527846185)
