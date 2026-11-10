<h1 align="center">Alexander Kovel</h1>

<p align="center">
  <b>Senior MLOps Engineer</b> · ML Platform @ Wildberries<br/>
  LLM, speech &amp; vision inference at scale on GPU
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/--alexander-kovel--/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://t.me/xanderkov"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="mailto:xanderkovel@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/xanderkov/cv/releases/latest"><img src="https://img.shields.io/badge/CV-PDF-24292F?style=flat-square&logo=readthedocs&logoColor=white" alt="CV"/></a>
</p>

---

### Highlights

| | |
|---:|:---|
| **300 → 1,200 RPS** | scaled the ML inference platform for content moderation |
| **3–4×** | faster OCR on Triton — DALI preprocessing, TensorRT on H200 |
| **10+ LLMs** | in production (Qwen3, GLM 5 on 8×H200) behind a LiteLLM gateway with budgets and routing |
| **20 nodes** | A100 / H100 / H200 fleet — driver rollouts, NVIDIA MIG partitioning, HAMi GPU sharing |
| **LLMStore** | led the bank-wide LLM deployment platform at Alfa-Bank — KServe + Knative autoscaling, ArgoCD |

### Stack

**Model serving** &nbsp;
![Triton](https://img.shields.io/badge/Triton-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![SGLang](https://img.shields.io/badge/SGLang-6E40C9?style=flat-square)
![LiteLLM](https://img.shields.io/badge/LiteLLM-111111?style=flat-square)
![KServe](https://img.shields.io/badge/KServe-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**GPU &amp; platform** &nbsp;
![NVIDIA MIG](https://img.shields.io/badge/NVIDIA_MIG-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![KEDA](https://img.shields.io/badge/KEDA-0062B1?style=flat-square)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,go,cpp,pytorch,kubernetes,docker,ansible,prometheus,grafana,githubactions,fastapi,kafka,rabbitmq,postgres,redis,opencv,linux,arch,neovim&theme=dark&perline=10">
  <img src="https://skillicons.dev/icons?i=py,go,cpp,pytorch,kubernetes,docker,ansible,prometheus,grafana,githubactions,fastapi,kafka,rabbitmq,postgres,redis,opencv,linux,arch,neovim&theme=light&perline=10" alt="Python, Go, C++, PyTorch, Kubernetes, Docker, Ansible, Prometheus, Grafana, GitHub Actions, FastAPI, Kafka, RabbitMQ, PostgreSQL, Redis, OpenCV, Linux, Arch, Neovim"/>
</picture>

### Now

- Moving image moderation models to H200 and autoscaling Triton
- GPU economics for the ML platform — who uses what, and what it costs
- MCP servers and agents for day-to-day platform work
