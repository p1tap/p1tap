<div align="center">

# Peerapat Thubthimthong

### AI Platform / LLMOps Engineer

Building evaluation-gated LLM systems, reliable inference infrastructure, and multimodal AI applications.

[LinkedIn](https://www.linkedin.com/in/peerapat-t) · [Email](mailto:peepzprtz@gmail.com) · Bangkok, Thailand

</div>

## Focus

- **Evaluation-driven AI:** versioned baselines, frozen test suites, LLM-as-judge evaluation, and policy-gated model promotion.
- **Reliable AI platforms:** Kubernetes, GitOps, failover, spend controls, and observability for LLM workloads.
- **Efficient multimodal systems:** PyTorch/CUDA, TTS/STT, runtime instrumentation, and consumer-GPU optimization.

## Selected work

- **[Vbot Model Gateway](https://github.com/p1tap/vbot-model-gateway)** - OpenAI-compatible, multi-provider LLM gateway on k3s with model fallback, Redis-backed circuit breaking, budget-capped virtual keys, and Prometheus/Grafana observability. Argo CD, Terraform, and an eval gate make a merged change deployable in roughly three minutes.

- **[Vbot RAG Evaluation Harness](https://github.com/p1tap/vbot-rag-eval/tree/main)** - Eval-gated RAG built with local E5 embeddings and a frozen 49-question golden set. Retrieval metrics, cross-family LLM judging, abstention checks, and CI reproducibility checks guard every promoted change.

- **Backbone fine-tuning system** *(private)* - Fine-tuned, evaluated, policy-gated, and GitOps-deployed a Qwen2.5-1.5B QLoRA model. Frozen behavioral probes, rather than training loss alone, determine whether a candidate is promoted.

- **[Vbot](https://github.com/NU8B/Vbot)** - Technical lead for a three-person team building a multimodal desktop AI character system with LLM, TTS, STT, emotion-aware avatar animation, and evaluation workflows. Reduced the full runtime's VRAM use from 16 GB to 6 GB.

- **[ToolShare on AWS](https://github.com/p1tap/toolshare-aws)** - Serverless marketplace API using API Gateway, Lambda, DynamoDB, Cognito, Step Functions, and SNS/SQS. Delivery is gated through GitHub Actions OIDC, staging smoke tests, approval, and canary rollback.

## Core toolkit

- **AI & evaluation:** Python, PyTorch, QLoRA/PEFT, vLLM, RAG, E5, LLM-as-judge
- **Platform & delivery:** Docker, Kubernetes (k3s), Argo CD, Terraform, GitHub Actions, Prometheus, Grafana, k6
- **Backend & cloud:** AWS serverless, PostgreSQL, Redis, Next.js, TypeScript

## Earlier highlight

Led a three-person team to **2nd place** in the UniversaAI AI Hackathon. Our agent-routing system reached **95.7% accuracy (66/69)** using vector search, lexical similarity, metadata caching, and weighted scoring. [Project](https://github.com/NU8B/agent_select_nono)

[Browse all repositories →](https://github.com/p1tap?tab=repositories)
