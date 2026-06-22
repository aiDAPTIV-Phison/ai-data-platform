<div align="center">

<a href="https://phison.ai">
  <img src="docs/phison-aidp.svg" width="480" alt="Phison AI Data Platform" />
</a>

#### Enterprise AI infrastructure

*Deploy faster · Raise GPU utilization · Cut the cost and complexity of running AI at scale*

<strong>English</strong> · <a href="README.zh-TW.md">繁體中文</a>

[Website](https://phison.ai) · [Ecosystem](https://phison.ai/ecosystem/) · [AISO](https://phison.ai/aiso/) · [Contact](https://phison.ai/contact/) · [Discussions](https://github.com/AIDataPlatform/Community/discussions) · [Phison](https://www.phison.com)

[![GPU Server](https://img.shields.io/badge/GPU_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/gpu-server/)
[![Cache Server](https://img.shields.io/badge/Cache_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/cache-server/)
[![Storage Server](https://img.shields.io/badge/Storage_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/storage-server/)
[![HCI](https://img.shields.io/badge/HCI-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/hci/)

</div>

<p align="center">
  Most organizations can build an AI prototype, but far fewer can efficiently deploy, run, and scale AI in production. Phison AI Data Platform unifies infrastructure, resource management, AI middleware, and application services into a single platform, helping organizations deploy faster, raise GPU utilization, and lower the cost and complexity of running AI at scale.
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

---

## GPU Server Benefits

> **500% More Concurrent Users — Same GPU Hardware**

Compare concurrent user capacity and inference metrics with and without aiDAPTIV on the same GPU server infrastructure. aiDAPTIV expands effective AI memory in software — no extra GPUs required. Same hardware, up to **500% more concurrent users**, and the headroom to train and serve LLMs up to **800B parameters**.

<p align="center">
  <img src="docs/svg-gpu-results-en.svg" alt="GPU Server concurrent users with and without aiDAPTIV" width="800" />
</p>

---

## Storage Server Benefits

> **Three Access Modes, One Unified Storage Platform**

Storage Server converges Block, File, and Object storage onto a single cluster — eliminating silos without sacrificing performance or protocol fidelity. One NVMe cluster serves Kubernetes CSI, NFS/SMB, and S3 workloads simultaneously, with per-volume policy controls for IOPS limits, snapshot schedules, and replication targets.

<p align="center">
  <img src="docs/svg-storage-access-en.svg" alt="Three access modes converging on one unified storage platform" width="800" />
</p>

---

## HCI Benefits

> **Maximize GPU Usage Rate — One Unified Control Plane**

Phison HCI unifies heterogeneous GPU/XPU, storage, and VM resources under a single control plane. Proprietary vGPU partitioning, distributed KV cache sharing, and automatic failover deliver measurable performance and efficiency gains across the cluster.

<table>
<tr>
<td align="center" width="33%">
  <h3>Lower Inference Cost</h3>
  <p>Reduce idle resources and directly lower the per-token inference cost.</p>
  <img src="docs/svg-cost.svg" alt="Lower inference cost" width="220" />
</td>
<td align="center" width="33%">
  <h3>Linear Scale-Out</h3>
  <p>Add new nodes to linearly increase throughput without redeploying the model.</p>
  <img src="docs/svg-scale-out.svg" alt="Linear scale-out" width="220" />
</td>
<td align="center" width="33%">
  <h3>Higher Concurrency</h3>
  <p>Combined with vGPU partitioning, a single host serves more concurrent requests simultaneously.</p>
  <img src="docs/svg-vgpu-concurrency.svg" alt="Higher concurrency" width="220" />
</td>
</tr>
</table>

---
