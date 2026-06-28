I write code. I make it work. I make it stay working.

```bash
$ whoami
> software engineer & applied ai.
> stack: python, fastapi, pytorch, next.js, postgres.
> focus: llm fine-tuning (lora/dpo), rag, mlops.
```

**find me:** [github](https://github.com/neuralbroker) · [huggingface](https://huggingface.co/neuralbroker) · [linkedin](https://linkedin.com/in/abdullasajad) · [email](mailto:abdullasajad01@gmail.com)

---

### what i've shipped

### [BlitzKode](https://github.com/neuralbroker/blitzkode) | *Open Source LLM*
4-stage fine-tuning pipeline (SFT → Reward-SFT → DPO → LoRA) on Qwen2.5-1.5B-Instruct. 
VRAM from 24GB to 8GB via LoRA, gradient checkpointing, bfloat16. Exported to GGUF Q8_0 (1.53GB) for CPU-only inference via llama.cpp. Deployed as FastAPI server with SSE streaming. 
**510+ downloads on HuggingFace.**
`[PyTorch]` `[PEFT]` `[TRL]` `[llama.cpp]` `[FastAPI]` `[Docker]`

### [EsenceLab](https://github.com/neuralbroker/esencelab) | *AI Hiring Platform*
Full-stack AI hiring platform (student, recruiter, admin) as a 3-service monorepo. 
Groq-powered resume parsing cuts manual shortlisting by 60% across 200+ resumes. JWT + Supabase RLS auth, GitHub Actions CI with RBAC smoke tests. Deployed on Vercel + Render with zero downtime. 
Won 2nd prize at Innovision (out of 30+ teams) and offered pre-seed funding.
`[Next.js 15]` `[Express]` `[FastAPI]` `[Supabase]` `[Docker]`

### [Lexora AI](https://github.com/neuralbroker/lexora-ai) | *Multi-Tenant RAG*
Document Q&A with per-user FAISS index isolation and Celery for background chunking. 
Sub-2s retrieval latency on 100k+ token corpora. JWT refresh-token rotation with Redis-backed revocation. 
`[LangChain]` `[FAISS]` `[OpenAI]` `[Celery]` `[Redis]`

### [SentinelML](https://github.com/neuralbroker/sentinel-ml) | *Fraud Detection API*
RandomForest with SMOTE oversampling and 25 engineered features. ROC-AUC 0.94. 
Redis prediction cache, MLflow experiment tracking, drift detection, and weekly retrain logic. Full stack via docker-compose. 
`[Scikit-Learn]` `[MLflow]` `[PostgreSQL]` `[Redis]` `[Docker]`

### [AI Resume Screener](https://github.com/neuralbroker/ai-resume-screener) | *Resume–JD Matcher*
FastAPI-based resume screener using Groq (llama-3.1-8b-instant). 
JWT auth, per-user screening history, admin role, statistics dashboard. SQLite + SQLAlchemy. 
`[FastAPI]` `[Groq]` `[SQLAlchemy]` `[JWT]`

### [SpeakSwap](https://github.com/neuralbroker/speakswap) | *Translation App*
Next.js 15 + React 19 web app for text + speech translation between languages. 
Uses free endpoints (MyMemory, LibreTranslate, Lingva) with fallback, voice input/output, dark mode, and translation history in localStorage. 
`[Next.js]` `[React]` `[TypeScript]` `[Tailwind]`
```
