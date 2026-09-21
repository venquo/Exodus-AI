<div align="center">

# ⚡ Exodus-AI: Dedicated Uncensored LLM Infrastructure

**High-performance, single-tenant private AI servers powered by abliterated models.  
Zero logging. Zero guardrails. Pure crypto checkout.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Docker Support](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](docker-compose.yml)
[![Inference Engine](https://img.shields.io/badge/Engine-vLLM-00E5FF)](https://github.com/vllm-project/vllm)
[![UI](https://img.shields.io/badge/Frontend-OpenWebUI-purple)](https://github.com/open-webui/open-webui)
[![Payment](https://img.shields.io/badge/Billing-Crypto%20%7C%20No%20KYC-F7931A)](https://t.me/ExodusAISupport)

[Quickstart (Self-Hosted)](#-option-1-diy-self-host-free) • [Order Dedicated Node](#-option-2-order-a-managed-exodus-node-250mo) • [Architecture](#-architecture) • [Security & Privacy](#-privacy--zero-logging-guarantee)

</div>

---

## ⚡ Overview

Exodus-AI provides an unthrottled, single-tenant AI environment designed for developers, red-teamers, and creators who require unfiltered inference without telemetry, corporate logging, or preachy safety refusals.

You can use the open-source configuration in this repository to run the stack on your own hardware for free, or order a turnkey, fully-managed 24GB VRAM node provisioned within minutes.

---

## ⚖️ Deployment Comparison

| Feature | Self-Hosted (DIY) | Exodus-AI Managed Node |
| :--- | :--- | :--- |
| **Cost** | Free (MIT License) | **$250 / month (Paid in Crypto)** |
| **Hardware** | Your local PC / GPU | **Dedicated 24GB RTX 4090 / A6000** |
| **Setup Time** | 30–60 mins (Manual drivers/CUDA) | **Ready in 10 minutes** |
| **Power & Heat** | 450W+ continuous home draw | **Hosted in tier-3 datacenter** |
| **Networking** | Manual port forwarding & DDNS | **Dedicated HTTPS Cloudflare Tunnel** |
| **Model Preloading**| Slow download speeds | **Preloaded & warmed up** |
| **API Endpoints** | `localhost:8000` | **Public `/v1` endpoint (Claude Code/Cursor ready)** |
| **Payment / KYC** | N/A | **USDT / USDC / BTC / Monero (No KYC)** |

---

## 🚀 Option 1: DIY Self-Host (Free)

If you already have a 24GB+ NVIDIA GPU (RTX 3090, 4090, or professional series) running Ubuntu with the NVIDIA Container Toolkit installed:

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/Exodus-AI.git](https://github.com/your-username/Exodus-AI.git)
cd Exodus-AI
