<div align="center">

<a href="https://phison.ai">
  <img src="docs/phison-aidp.svg" width="260" alt="Phison" />
</a>

# AI Data Platform

### Enterprise AI infrastructure — from prototype to production

*Deploy faster · Raise GPU utilization · Cut the cost and complexity of running AI at scale*

<strong>English</strong> · <a href="README.zh-TW.md">繁體中文</a>

[Website](https://phison.ai) · [Ecosystem](https://phison.ai/ecosystem/) · [AISO](https://phison.ai/aiso/) · [Contact](https://phison.ai/contact/) · [Discussions](https://github.com/AIDataPlatform/Community/discussions)

[![GPU Server](https://img.shields.io/badge/GPU_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/gpu-server/)
[![Cache Server](https://img.shields.io/badge/Cache_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/cache-server/)
[![Storage Server](https://img.shields.io/badge/Storage_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/storage-server/)
[![HCI](https://img.shields.io/badge/HCI-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/hci/)

[![Made by Phison](https://img.shields.io/badge/Made_by-Phison-f7941d?style=flat-square)](https://www.phison.com)

</div>

<p align="center">
  Most organizations can build an AI prototype, but far fewer can efficiently deploy, run, and scale AI in production.<br><br>
  Phison AI Data Platform unifies infrastructure, resource management, AI middleware, and application services into a single platform,<br>
  helping organizations deploy faster, raise GPU utilization, and lower the cost and complexity of running AI at scale.
</p>

<!-- TODO: add homepage hero screenshot or GIF -->

<br>

<table>
<tr>
<td align="center" width="33%">
  <h2><strong>Day 1</strong></h2>
  <h3>Ready to Run</h3>
  <p>More than a server — a turnkey AI department, ready out of the box. Scale seamlessly from infrastructure to applications, skipping months of complex system integration.</p>
</td>
<td align="center" width="33%">
  <h2><strong>1/5</strong></h2>
  <h3>Hardware Budget</h3>
  <p>Phison's pioneering Pascari aiDAPTIV™ technology delivers secure, enterprise-grade LLM fine-tuning and inference at one-fifth the hardware cost, putting AI within reach of every organization.</p>
</td>
<td align="center" width="33%">
  <h2><strong>Anywhere</strong></h2>
  <h3>Ask AI</h3>
  <p>Your data stays in place, secure. A zero-migration architecture lets you query distributed data directly in natural language — real-time business insight with nothing to move.</p>
</td>
</tr>
</table>

---

## What solutions does Phison provide?

<table>
<tr>
<td width="55%">
  <h4>One-Stop AI Solution</h4>
  <p>Hardware, platform, AI modules, and application services unified in a single platform — no need to stitch together multiple vendors and complex technology stacks.</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-one-stop.svg" alt="One-Stop AI Solution" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>Unified GPU Management</h4>
  <p>Centrally manage GPUs/XPUs across brands and generations to raise overall resource utilization and scalability.</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-gpu.svg" alt="Unified GPU Management" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>Lower Deployment Cost</h4>
  <p>Delivered as a pre-integrated private AI platform, helping enterprises move from PoC to production faster.</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-deployment.svg" alt="Lower Deployment Cost" width="480" />
</td>
</tr>
</table>

---

## AI Data Platform Architecture

Enterprises can flexibly choose the hardware, AI modules, and application services that best fit their AI use cases, existing IT environment, and budget. Whether GPU/CPU servers, Cache/Storage architecture, or AI vision, speech, and inference modules — all can be freely combined and scaled, helping enterprises build a scalable, manageable, and commercially viable on-premise AI foundation at the most appropriate cost.

<p align="center">
  <img src="docs/architecture-en.svg" alt="AI Data Platform architecture" width="720" />
</p>


### Flexible Deployment from Edge to Data Center

The same platform deploys consistently from edge sites to the central data center. Scale the four layers below — compute backbone, unified control, open-source components, and AI modules — in sequence, with no need to redesign the overall architecture.

<table>
<tr>
<td width="55%">
  <h4>L4 — Reusable AI Module Layer</h4>
  <p>Production-ready vision, speech, inference, and model-lifecycle modules, spanning training and optimization through deployment and operations.</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l4.svg" alt="L4 — Reusable AI Module Layer" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L3 — Reusable Open-Source Component Layer</h4>
  <p>Curated, AI-ready open-source components (frameworks, queues, databases, and tools), hardened as a composable workflow foundation.</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l3.svg" alt="L3 — Reusable Open-Source Component Layer" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L2 — Hyper-Converged Infrastructure Software Layer</h4>
  <p>A hyper-converged control plane managing heterogeneous GPU/XPU, storage, and VMs — pooling mixed-brand, mixed-generation hardware centrally.</p>
  <p>
    <a href="https://phison.ai/hci/"><img src="https://img.shields.io/badge/Phison_HCI-F7941D?style=for-the-badge&logo=cloud&logoColor=white" alt="Phison HCI" /></a>
  </p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l2.svg" alt="L2 — Hyper-Converged Infrastructure Software Layer" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L1 — Infrastructure Layer</h4>
  <p>Integrates GPU, CPU, cache, and storage over high-speed interconnects to form the compute and data backbone.</p>
  <p>
    <a href="https://phison.ai/gpu-server/"><img src="https://img.shields.io/badge/GPU_Server-F7941D?style=for-the-badge&logo=server&logoColor=white" alt="GPU Server" /></a>
    <a href="https://phison.ai/cache-server/"><img src="https://img.shields.io/badge/Cache_Server-F7941D?style=for-the-badge&logo=database&logoColor=white" alt="Cache Server" /></a>
    <a href="https://phison.ai/storage-server/"><img src="https://img.shields.io/badge/Storage_Server-F7941D?style=for-the-badge&logo=hard-drive&logoColor=white" alt="Storage Server" /></a>
  </p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l1.svg" alt="L1 — Infrastructure Layer" width="480" />
</td>
</tr>
</table>

---

## Ecosystem & Application Services

Phison AI Data Platform supports various AI software platforms and SaaS services, including customized AI applications and industry solutions co-developed with customers.

---

## Technology Spotlight — Pascari aiDAPTIV™

> **Tiered AI memory · Save VRAM · Faster inference**

aiDAPTIV Cache Memory extends effective AI memory across GPU memory, system memory, and flash storage to support larger models, longer context windows, KV cache reuse, and memory-intensive AI workloads.

<p align="center">
  <img src="docs/svg-training-compare-en.svg" alt="Traditional vs Phison aiDAPTIV training architecture" width="800" />
</p>

<table>
<tr>
<td width="33%" valign="top">
  <h4>Disaggregated AI Infrastructure</h4>
  <p>Disaggregated architecture raises the scalability and resource utilization of AI systems.</p>
</td>
<td width="33%" valign="top">
  <h4>One-Stop AI Deployment Platform</h4>
  <p>Provides a complete one-stop AI solution spanning hardware, platform, aiDAPTIV, AI modules, and SaaS applications to significantly shorten the AI adoption lifecycle.</p>
</td>
<td width="33%" valign="top">
  <h4>AI Software Ecosystem Integration</h4>
  <p>Integrates ISVs, SIs, open-source components, and AI ecosystem partners to accelerate enterprise AI commercialization and deployment.</p>
</td>
</tr>
</table>

---

## Cache Server Benefits

> **Storage in Place of Compute — Save Massive GPU Compute**

Once produced, KV cache is shared across the entire cluster. Long prompts, multi-turn dialogue, agent workflows, and RAG prefixes don't have to run from scratch every time — Time-to-First-Token drops immediately.

<p align="center">
  <img src="docs/svg-cache-cluster-en.svg" alt="GPU cluster sharing one KV cache pool over high-speed interconnect" width="800" />
</p>

<table>
<tr>
<td align="center" width="33%">
  <h2><strong>200% UP</strong></h2>
  <h3>Concurrent Users</h3>
  <p>Same GPU cluster, more than 2× concurrency. Prefill no longer hogs the GPU.</p>
  <img src="docs/svg-concurrency.svg" alt="GPU concurrency" width="220" />
</td>
<td align="center" width="33%">
  <h2><strong>50% DOWN</strong></h2>
  <h3>GPU Compute Required</h3>
  <p>With KV cache reuse, GPU compute drops by more than half.</p>
  <img src="docs/svg-decoupled-cost.svg" alt="Decoupled cost" width="220" />
</td>
<td align="center" width="33%">
  <h2><strong>500% UP</strong></h2>
  <h3>Faster TTFT</h3>
  <p>Hit-and-return replaces recompute — 5× faster time-to-first-token.</p>
  <img src="docs/svg-hit-rate.svg" alt="Shared cache hit" width="220" />
</td>
</tr>
</table>

> Real performance gains from production deployments.

<table>
<tr>
<td width="50%">
  <h4>Higher Return on Investment</h4>
  <p>aiDAPTIV reduces dependence on high-end GPUs and VRAM waste, cutting cost while maintaining throughput. As demand grows, the platform scales horizontally — no architecture redesign needed — so your initial investment keeps delivering value.</p>
</td>
<td width="50%">
  <h4>Rapid Deployment</h4>
  <p>Compress traditional AI platform adoption from months to days. Pre-integrated modules shorten the distance from PoC to production.</p>
</td>
</tr>
</table>

<p align="center">
  <img src="docs/svg-inference-capacity-en.svg" alt="Inference Capacity Explorer" width="800" />
</p>

---

## GPU Server Benefits

> **500% More Concurrent Users — Same GPU Hardware**

Compare concurrent user capacity and inference metrics with and without aiDAPTIV on the same GPU server infrastructure. aiDAPTIV expands effective AI memory in software — no extra GPUs required. Same hardware, up to **500% more concurrent users**, and the headroom to train and serve LLMs up to **800B parameters**.

<p align="center">
  <img src="docs/svg-gpu-results-en.svg" alt="GPU Server concurrent users with and without aiDAPTIV" width="800" />
</p>

> **Inference Speed — Multi-GPU DAS Benchmark**

| GPU | Model | aiDAPTIV Cache | Users (w/o → w/) | TTFT (w/o → w/) | TPS (w/o → w/) |
| --- | --- | --- | --- | --- | --- |
| RTX 6000 Ada ×8 | GPT-OSS-120B | AI100 ×2 | 10 → **40** | 6.7s → **2.3s** | 28.3 → 28.0 |
| RTX PRO 6000 ×8 | GPT-OSS-120B | AI100 ×2 | 20 → **60** | 10.1s → **2.6s** | 18.8 → **21.3** |
| H200 ×8 | Llama 3.3 70B | AI200 ×4 | 20 → **100** | 7.4s → 8.3s | 21.7 → **22.2** |
| B300 ×8 | Llama 3.3 70B | AI200 ×8 | 60 → **180** | 9.4s → 9.9s | 16.5 → **17.7** |

> Benchmark: TTFT < 10 s · TPS > 20 tokens/sec · input token length = 16K.

---

## Storage Server Benefits

> **Three Access Modes, One Unified Storage Platform**

Storage Server converges Block, File, and Object storage onto a single cluster — eliminating silos without sacrificing performance or protocol fidelity. One NVMe cluster serves Kubernetes CSI, NFS/SMB, and S3 workloads simultaneously, with per-volume policy controls for IOPS limits, snapshot schedules, and replication targets.

<p align="center">
  <img src="docs/svg-storage-access-en.svg" alt="Three access modes converging on one unified storage platform" width="800" />
</p>

---
