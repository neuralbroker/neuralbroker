I write code. I make it work. I make it stay working.

```bash
$ whoami
> software engineer & applied ai.
> currently: shipping small models, building production systems.
> stack: python, fastapi, pytorch, next.js, postgres.
> learning: applied ai & llms.
```

**find me:** [github](https://github.com/neuralbroker) · [huggingface](https://huggingface.co/neuralbroker) · [linkedin](https://linkedin.com/in/abdullasajad) · [email](mailto:abdullasajad01@gmail.com)

### what i've shipped

**[BlitzKode](https://huggingface.co/neuralbroker/blitzkode)** | *Open Source LLM*
4-stage fine-tuning pipeline (SFT -> Reward-SFT -> DPO -> LoRA) on Qwen2.5-1.5B-Instruct. VRAM from 24GB to 8GB. PyTorch + PEFT training, exported to GGUF for CPU-only inference via llama.cpp. `510+ downloads on HuggingFace.`
`[PyTorch] [PEFT] [llama.cpp] [FastAPI]`

**[EsenceLab](https://github.com/neuralbroker/esencelab)** | *AI Hiring Platform*
3-service monorepo. Groq-powered parsing + Supabase RLS for strict row-level security. Won 2nd prize at Innovision (out of 30 teams). Zero downtime in production.
`[Next.js] [FastAPI] [Supabase] [Docker]`

**[Lexora AI](https://github.com/neuralbroker/lexora-ai)** | *Multi-Tenant RAG*
Document Q&A with per-user FAISS index isolation. Celery for background chunking and Redis for caching. Sub-2s latency on 100k+ token corpora.
`[LangChain] [FAISS] [Celery] [Redis]`

**[SentinelML](https://github.com/neuralbroker/sentinel-ml)** | *Fraud Detection API*
RandomForest with SMOTE oversampling. Redis prediction cache to handle repeated requests. Drift tracking with MLflow. `0.94 ROC-AUC.`
`[Scikit-Learn] [MLflow] [PostgreSQL]`

**[AI Resume Screener](https://github.com/neuralbroker/ai-resume-screener)** | *Resume-JD Matcher*
FastAPI-based resume screener using Groq (llama-3.1-8b-instant). JWT auth, screening history, admin role, statistics dashboard. SQLite + SQLAlchemy.
`[FastAPI] [Groq] [SQLAlchemy] [JWT]`

**[SpeakSwap](https://github.com/neuralbroker/speakswap)** | *Translation App*
Next.js 15 + React 19 web app. Text + speech translation between languages via free endpoints (MyMemory, LibreTranslate, Lingva) with fallback. Voice input/output, dark mode, translation history in localStorage.
`[Next.js] [React] [TypeScript] [Tailwind]`
