# Sajad

Python, ML, some TypeScript. I fine-tune small models, build RAG systems, and ship production ML. Code is mostly Python; the frontends and the TypeScript I touch come from LLMs doing the typing.

## Projects

- [BlitzKode](https://github.com/neuralbroker/blitzkode): 4-stage fine-tuning (SFT, reward SFT, DPO, LoRA) on Qwen2.5-Coder-1.5B. GGUF Q8_0 + LoRA adapter. 510+ HF downloads. [HF](https://huggingface.co/neuralbroker/blitzkode)
- [EsenceLab](https://github.com/neuralbroker/esencelab): AI hiring platform, 3-service monorepo. Gemini resume parsing cut shortlisting by 60% across 200+ resumes. JWT + Supabase RLS auth. 2nd at Innovision (30+ teams).
- [Lexora AI](https://github.com/neuralbroker/lexora-ai): RAG document Q&A. Per-user FAISS, LangChain + OpenAI, sub-2s on 100k-token corpora. JWT refresh, Redis revocation.
- [SentinelML](https://github.com/neuralbroker/sentinel-ml): credit-card fraud detection. SMOTE + RandomForest, 0.94 ROC-AUC. Redis cache, MLflow, docker-compose. Drift detection, weekly retrain.
