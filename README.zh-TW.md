<div align="center">

<a href="https://phison.ai">
  <img src="docs/phison-aidp.svg" width="300" alt="Phison AI Data Platform" />
</a>

# AI Data Platform

### 企業級 AI 基礎平台 — 從原型到量產

*加速部署 · 提升 GPU 利用率 · 降低大規模 AI 的成本與複雜度*

<a href="README.md">English</a> · <strong>繁體中文</strong>

[官方網站](https://phison.ai) · [生態系](https://phison.ai/ecosystem/) · [AISO](https://phison.ai/aiso/) · [聯絡我們](https://phison.ai/contact/) · [社群討論](https://github.com/AIDataPlatform/Community/discussions) 

[![GPU Server](https://img.shields.io/badge/GPU_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/gpu-server/)
[![Cache Server](https://img.shields.io/badge/Cache_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/cache-server/)
[![Storage Server](https://img.shields.io/badge/Storage_Server-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/storage-server/)
[![HCI](https://img.shields.io/badge/HCI-F7941D?style=for-the-badge&logoColor=white)](https://phison.ai/hci/)
[![Made by Phison](https://img.shields.io/badge/Made_by-Phison-f7941d?style=flat-square)](https://www.phison.com)

</div>

<p align="center">
  大多數組織都能建構 AI 原型，但遠少數能夠在生產環境中高效部署、運行並擴展 AI。<br><br>
  Phison AI Data Platform 將基礎設施、資源管理、AI 中介軟體和應用服務整合為單一平台，<br>
  協助組織加快部署速度、提升 GPU 利用率，並降低大規模運行 AI 的成本與複雜度。
</p>


<br>

<table>
<tr>
<td align="center" width="33%">
  <h2><strong>Day 1</strong></h2>
  <h3>開機即用</h3>
  <p>不只是一台伺服器，更是開箱即用的完整 AI 部門。從基礎架構到應用程式皆可無縫擴充，省去數月繁雜的系統整合。</p>
</td>
<td align="center" width="33%">
  <h2><strong>1/5</strong></h2>
  <h3>硬體預算</h3>
  <p>群聯獨創 Pascari aiDAPTIV™ 技術，以 1/5 的硬體成本提供安全、企業級的 LLM 微調與推理，讓各規模企業皆能輕鬆擁抱 AI。</p>
</td>
<td align="center" width="33%">
  <h2><strong>Anywhere</strong></h2>
  <h3>詢問 AI</h3>
  <p>數據原地不動，安全無虞。零遷移架構支援以自然語言直接查詢分散數據，無需搬移即可即時獲取商業洞察。</p>
</td>
</tr>
</table>

---

## 群聯提供哪些解決方案？

<table>
<tr>
<td width="55%">
  <h4>一站式 AI 解決方案</h4>
  <p>硬體、平台、AI 模組與應用服務透過單一平台整合，避免企業自行串接多家供應商與複雜技術堆疊。</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-one-stop.svg" alt="一站式 AI 解決方案" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>GPU 算力統一管理</h4>
  <p>集中管理不同品牌與世代的 GPU／XPU，提升整體資源利用率與可擴充性。</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-gpu.svg" alt="GPU 算力統一管理" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>降低部署成本</h4>
  <p>以預整合私有 AI 平台交付，協助企業更快從 PoC 走向量產。</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-deployment.svg" alt="降低部署成本" width="480" />
</td>
</tr>
</table>

---

## AI Data Platform 架構

企業可依據自身 AI 應用需求、既有 IT 環境與預算規模，彈性選擇最適合的硬體設備、AI 模組與應用服務。無論是 GPU / CPU Server、Cache / Storage 架構，或 AI 視覺、語音、推理等模組，皆可自由組合與擴充，協助企業以最合適的成本快速打造可持續成長的可擴充、可管理、可商業化的地端 AI 基礎平台。

<p align="center">
  <img src="docs/architecture-zh.svg" alt="AI Data Platform 架構圖" width="720" />
</p>

### 從邊緣到資料中心彈性部署

同一平台可從邊緣站點延伸至中央資料中心一致部署。依序擴充下方四層的運算骨幹、統一管控、開源元件與 AI 模組，無需重新設計整體架構。

<table>
<tr>
<td width="55%">
  <h4>L1 — 基礎設施層</h4>
  <p>透過高速互連整合 GPU、CPU、快取與儲存，構成運算與資料骨幹。</p>
  <p>
    <a href="https://phison.ai/gpu-server/"><img src="https://img.shields.io/badge/GPU_Server-F7941D?style=for-the-badge&logo=server&logoColor=white" alt="GPU Server" /></a>
    <a href="https://phison.ai/cache-server/"><img src="https://img.shields.io/badge/Cache_Server-F7941D?style=for-the-badge&logo=database&logoColor=white" alt="Cache Server" /></a>
    <a href="https://phison.ai/storage-server/"><img src="https://img.shields.io/badge/Storage_Server-F7941D?style=for-the-badge&logo=hard-drive&logoColor=white" alt="Storage Server" /></a>
  </p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l1.svg" alt="L1 基礎設施層" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L2 — 超融合基礎架構軟體層</h4>
  <p>超融合控制面統管異質 GPU/XPU、儲存與虛擬機，混品牌與世代設備集中池化。</p>
  <p>
    <a href="https://phison.ai/hci/"><img src="https://img.shields.io/badge/Phison_HCI-F7941D?style=for-the-badge&logo=cloud&logoColor=white" alt="Phison HCI" /></a>
  </p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l2.svg" alt="L2 超融合基礎架構軟體層" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L3 — 可複用開源元件層</h4>
  <p>精選並強化適用 AI 的開源元件（框架、佇列、資料庫與工具），作為可組合的工作流基礎。</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l3.svg" alt="L3 可複用開源元件層" width="480" />
</td>
</tr>
<tr>
<td width="55%">
  <h4>L4 — 可複用 AI 模組層</h4>
  <p>可投產的視覺、語音、推理與模型生命週期模組，涵蓋訓練、優化至部署與維運。</p>
</td>
<td align="center" width="45%">
  <img src="docs/svg-arch-l4.svg" alt="L4 可複用 AI 模組層" width="480" />
</td>
</tr>
</table>

---

## 生態系與應用服務

群聯 AI Data Platform 支援多種 AI 軟體平台與 SaaS 服務，並包含群聯與客戶共同開發的客製化 AI 應用與行業解決方案。

---

## 技術焦點 — Pascari aiDAPTIV™

> **分層 AI 記憶體 · 省 VRAM · 推論更快**

aiDAPTIV Cache Memory 將 AI 有效記憶體擴展到 GPU 記憶體、系統記憶體和快閃記憶體中，以支援更大的模型、更長的上下文窗口、KV 快取重用以及記憶體密集型 AI 工作負載。

<p align="center">
  <img src="docs/svg-training-compare-zh.svg" alt="Traditional vs Phison aiDAPTIV training architecture" width="800" />
</p>

<table>
<tr>
<td width="33%" valign="top">
  <h4>解耦式 AI 基礎設施</h4>
  <p>解耦式架構提升 AI 系統的可擴充性與資源利用率。</p>
</td>
<td width="33%" valign="top">
  <h4>一站式 AI 部署平台</h4>
  <p>從硬體、平台、aiDAPTIV、AI 模組到 SaaS 應用，提供完整一站式 AI 解決方案，大幅縮短 AI 導入週期。</p>
</td>
<td width="33%" valign="top">
  <h4>AI 軟體生態系整合</h4>
  <p>整合 ISV、SI、開源元件與 AI 生態系夥伴，加速企業 AI 商業化與落地實踐。</p>
</td>
</tr>
</table>

---

## 以存代算 — 大量節省 GPU 算力

KV cache 一旦產生，就在整個 Cluster 內可共用。長 prompt、多輪對話、Agent workflow、RAG 的 prefix 不必再每次從零跑起，Time-to-First-Token 立刻下降。

<p align="center">
  <img src="docs/svg-cache-cluster-en.svg" alt="GPU 叢集透過高速互連共享一個 KV cache pool" width="800" />
</p>

<table>
<tr>
<td align="center" width="33%">
  <h2><strong>200% UP</strong></h2>
  <h3>並行使用者</h3>
  <p>同樣的 GPU 叢集，翻倍以上的併發。Prefill 不再佔滿 GPU。</p>
  <img src="docs/svg-concurrency.svg" alt="GPU 併發" width="220" />
</td>
<td align="center" width="33%">
  <h2><strong>50% DOWN</strong></h2>
  <h3>GPU 運算需求</h3>
  <p>透過 KV cache 重用，GPU 算力節省一半以上。</p>
  <img src="docs/svg-decoupled-cost.svg" alt="解耦成本" width="220" />
</td>
<td align="center" width="33%">
  <h2><strong>500% UP</strong></h2>
  <h3>首字時間加速</h3>
  <p>命中即返取代重算，首字延遲快 5 倍以上。</p>
  <img src="docs/svg-hit-rate.svg" alt="共享快取命中" width="220" />
</td>
</tr>
</table>

> 來自正式部署系統的真實效能提升。

<table>
<tr>
<td width="50%">
  <h4>更高投資報酬</h4>
  <p>aiDAPTIV 降低對高階 GPU 的依賴與 VRAM 浪費，在維持吞吐的前提下削減成本。需求成長時，平台可橫向擴展、無需重新設計架構——讓您的初期投資持續發揮價值。</p>
</td>
<td width="50%">
  <h4>快速部署</h4>
  <p>將傳統 AI 平台導入從數月壓縮至數天，預整合模組縮短 PoC 至正式部署的距離。</p>
</td>
</tr>
</table>

<p align="center">
  <img src="docs/svg-inference-capacity-zh.svg" alt="推論容量探索器" width="800" />
</p>

---

## GPU Server 效益

> **同樣 GPU 硬體 — 並行使用者提升 500%**

在相同 GPU Server 基礎設施上比較有無 aiDAPTIV 的並行使用者容量與推論指標。aiDAPTIV 以軟體擴展有效 AI 記憶體，無需額外 GPU。同樣硬體，最高 **500% 並行使用者**，並有餘裕訓練與服務高達 **800B 參數**的模型。

<p align="center">
  <img src="docs/svg-gpu-results-en.svg" alt="GPU Server 有無 aiDAPTIV 並行使用者對比" width="800" />
</p>

> **推論速度 — Multi-GPU DAS 基準測試**

| GPU | 模型 | aiDAPTIV Cache | 使用者 (無 → 有) | TTFT (無 → 有) | TPS (無 → 有) |
| --- | --- | --- | --- | --- | --- |
| RTX 6000 Ada ×8 | GPT-OSS-120B | AI100 ×2 | 10 → **40** | 6.7s → **2.3s** | 28.3 → 28.0 |
| RTX PRO 6000 ×8 | GPT-OSS-120B | AI100 ×2 | 20 → **60** | 10.1s → **2.6s** | 18.8 → **21.3** |
| H200 ×8 | Llama 3.3 70B | AI200 ×4 | 20 → **100** | 7.4s → 8.3s | 21.7 → **22.2** |
| B300 ×8 | Llama 3.3 70B | AI200 ×8 | 60 → **180** | 9.4s → 9.9s | 16.5 → **17.7** |

> 基準條件：TTFT < 10 s · TPS > 20 tokens/sec · input token length = 16K。

---

## Storage Server 效益

> **三種存取模式，一個統一儲存平台**

Storage Server 將 Block、File、Object 儲存整合至單一叢集，消除孤島而不犧牲效能或協定保真度。一組 NVMe 叢集同時服務 Kubernetes CSI、NFS/SMB 和 S3 工作負載，並提供每磁碟區的 IOPS 限制、快照排程與複寫目標原則控制。

<p align="center">
  <img src="docs/svg-storage-access-en.svg" alt="三種存取模式匯聚至統一儲存平台" width="800" />
</p>

---

