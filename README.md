# Interesting Projects

Interesting tools, services, and projects worth exploring. 

## 🚀 Development Tools

### [zed.dev](https://zed.dev/)
**Minimalist Code Editor**
- Fast, lightweight code editor written in Rust
- Jupyter Notebooks not supported yet, but on the roadmap

### [z.ai](https://z.ai/subscribe)
**AI LAB**
- GLM 4.7 - Claude alternative, almost as good.
- asymmetrically cheaper pricing

### [linear.app](https://linear.app/)
**Modern Issue Tracking & Project Management**
- Fast, minimalist project management tool designed for software teams
- Keyboard-first navigation with real-time sync
- Integrates with GitHub, GitLab, Figma, and Slack
- Opinionated workflow reduces decision fatigue
- Popular among startups and high-performing engineering teams

### [cto.new](https://cto.new)
**Free Coding Agents**
- Read Terms of Use carefully before using it
- AI Agents for free

## 🤖 Inference Providers

### [groq.com](https://groq.com/)
**Ultra-Fast LLM Inference API**
- Lightning-fast AI inference with custom LPU (Language Processing Unit) hardware
- Up to 1,000+ tokens per second - significantly faster than GPU-based solutions
- Competitive pricing with transparent token-based billing
- Supports popular open-source models (Llama, Mistral, etc.)
- Simple REST API for real-time AI applications
- Ideal for chatbots, streaming applications, and low-latency AI services
- *For free inference with rate limits, also check out [OpenRouter](https://openrouter.ai) and [Hugging Face](https://huggingface.co/inference-api)*

### [runpod.io](https://www.runpod.io/)
**GPU Cloud Computing Platform**
- On-demand GPU access across 30+ global regions
- Both serverless and persistent pod options
- Wide range of GPUs: H100, A100, RTX series, and more
- Competitive per-second billing with no idle costs on serverless
- Pre-built templates for ML/AI workloads
- Instant clusters for multi-node training
- SOC 2 Type II compliant infrastructure
- Popular for inference, fine-tuning, and compute-heavy AI tasks

## ☁️ Cloud

### [cloudflare.com](https://www.cloudflare.com/)
**Global Cloud Platform & CDN**
- Fundamentally a Reverse proxy based global CDN,DDOS, WAF provide. Unlike say AWS Cloudfront which is basically a distributed file system. 
- **Storage Solutions**: R2 object storage (S3-compatible), Workers KV (key-value), Durable Objects (stateful storage)
- **Data Engineering**: D1 SQLite database, Analytics Engine (time-series), Vectorize (vector search), Pipelines (streaming ingestion)
- **Compute Solutions**: Cloudflare Workers (10ms CPU limit free, 50ms paid), Pages (static sites), Queues (background jobs), **Containers** (full Docker support, launched 2025)
- Global edge network with 300+ locations worldwide
- Competitive pricing with zero egress fees on storage
- Also checkout Akamai which is the same space but not as popular as Cloudflare.

### [fly.io](https://fly.io/)
**Edge Computing Platform**
- Deploy Docker containers globally across 35+ regions
- Built on Firecracker microVMs for fast boot times and security
- Managed databases: Postgres, Redis, and distributed systems
- GPU support for AI/ML workloads
- Simple deployment with `flyctl` CLI
- Pay-per-use pricing with generous free tier
- Focus on running applications close to users for low latency

### [oracle.com/cloud](https://www.oracle.com/cloud/)
**Oracle Cloud Infrastructure (OCI)**
- Competitive pricing in mostly everything.
- **Generous egress**: 10TB/month free data transfer (vs 100GB on AWS/GCP)
- **Always Free tier**: ARM instances,One tiny AMD x86 instance, Autonomous Database, block storage under always free tier
- Consistent global pricing across all regions
- **RDMA networking**: Remote Direct Memory Access for ultra-low latency cluster computing (bypasses CPU/OS for direct memory-to-memory transfers, critical for HPC/AI workloads - rare among major cloud providers)
- **Bare Metal Servers**: True bare metal instances with no hypervisor overhead (direct hardware access for maximum performance)
- **Shapes**: Granular CPU/memory scaling (adjust by single core/GB) vs fixed instance sizes on other clouds
- Strong enterprise features and database integration
- Major AI partnerships (OpenAI, NVIDIA Blackwell GPUs)
- **Cons**: Poor developer experience, confusing documentation, limited community adoption and ecosystem as of early 2026. Free tier instances can be preempted based on low usage. 

## 📝 Notes
 
 Tracking interesting projects, tools, and services across various domains. Each entry includes a brief description and key features or considerations.
