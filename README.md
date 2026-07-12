<div align="center">

# Peerapat Thubthimthong

### AI Platform / LLMOps Engineer

Building evaluation-gated LLM systems, reliable inference infrastructure, and multimodal AI applications.

[LinkedIn](https://www.linkedin.com/in/peerapat-t) · [Email](mailto:peepzprtz@gmail.com) · Bangkok, Thailand

</div>

## What I work on

Making model changes provable before they ship — versioned baselines, frozen test suites, and LLM-as-judge gates that decide promotion by exit code. Around that sits the platform to run it (Kubernetes, GitOps, failover, spend caps, Prometheus/Grafana) and the systems it serves, from QLoRA fine-tunes to a multimodal desktop runtime squeezed onto a consumer GPU.

## Selected work

- **[Vbot Model Gateway](https://github.com/p1tap/vbot-model-gateway)** - OpenAI-compatible, multi-provider LLM gateway on k3s with model fallback, Redis-backed circuit breaking, budget-capped virtual keys, and Prometheus/Grafana observability. Argo CD, Terraform, and an eval gate make a merged change deployable in roughly three minutes.

- **[Vbot RAG Evaluation Harness](https://github.com/p1tap/vbot-rag-eval/tree/main)** - Eval-gated RAG built with local E5 embeddings and a frozen 49-question golden set. Retrieval metrics, cross-family LLM judging, abstention checks, and CI reproducibility checks guard every promoted change.

- **Backbone fine-tuning system** *(private)* - Fine-tuned, evaluated, policy-gated, and GitOps-deployed a Qwen2.5-1.5B QLoRA model. Frozen behavioral probes, rather than training loss alone, determine whether a candidate is promoted.

- **[Vbot](https://github.com/NU8B/Vbot)** - Multimodal desktop AI character system: LLM, TTS, STT, emotion-aware avatar animation, and an evaluation/promotion layer. Cut the full runtime's VRAM use from 16 GB to 6 GB.

- **[ToolShare on AWS](https://github.com/p1tap/toolshare-aws)** - Serverless marketplace API using API Gateway, Lambda, DynamoDB, Cognito, Step Functions, and SNS/SQS. Delivery is gated through GitHub Actions OIDC, staging smoke tests, approval, and canary rollback.

## Core toolkit

- **AI & evaluation:** Python, PyTorch, QLoRA/PEFT, vLLM, RAG, E5, LLM-as-judge
- **Platform & delivery:** Docker, Kubernetes (k3s), Argo CD, Terraform, GitHub Actions, Prometheus, Grafana, k6
- **Backend & cloud:** AWS serverless, PostgreSQL, Redis, Next.js, TypeScript

## Earlier highlight

**2nd place** in the UniversaAI AI Hackathon. An agent-routing system that reached **95.7% accuracy (66/69)** using vector search, lexical similarity, metadata caching, and weighted scoring. [Project](https://github.com/NU8B/agent_select_nono)

[Browse all repositories →](https://github.com/p1tap?tab=repositories)
