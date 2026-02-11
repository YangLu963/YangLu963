# 👋 你好，我是Yang Lu

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&width=550&lines=Java+Backend+Expert;AI+&amp;+Robotics+Researcher;LLM+Agent+Architect;On-Device+AI+Engineer" alt="Typing SVG" /></a>
</p>

### 📖 关于我 (About Me)
> 🚀 跨界开发者与研究者，擅长在**高性能分布式架构**与**前沿人工智能**之间寻找平衡。
> 具备从后端大并发处理到端侧模型轻量化部署的全链路实战经验。

---

### 🏆 旗舰项目：分布式电商平台与实时推荐系统

#### [📂 仓库地址：Distributed E-Commerce System](https://github.com/你的用户名/ecommerce-repo)
**项目描述**：构建了一个能够支撑百万级并发的分布式电商生态系统，集成实时用户行为分析与精准推荐。

* **核心功能：**
    * **高并发架构**：基于 **Spring Cloud Alibaba** 实现微服务治理，利用 **Redis** 三级缓存策略（本地-分布式-持久化）将系统热点接口延迟压测至 **< 50ms**。
    * **实时推荐引擎**：利用 **Spark Streaming** 消费 **Kafka** 中的用户点击流，结合 **ALS + DNN** 混合模型实现分钟级画像更新，CTR 提升 **22%**。
    * **高可用保障**：设计了基于 **Sentinel** 的全链路熔断限流方案，配合 **Kubernetes** 的 HPA（自动水平扩容）确保在大促峰值期间 99.99% 的可用性。
* **技术栈：** `Java 21`, `Spring Cloud`, `Kafka`, `Spark`, `Redis`, `MySQL`, `Kubernetes`, `Docker`, `Prometheus`.



---

### 🧠 大模型与智能体研究 (LLM & Agent Research)

#### [📂 仓库地址：P-E-S Agent Mechanism](https://github.com/你的用户名/pes-agent)
**项目描述**：提出并实现了一种 **P-E-S (Python-Evaluation-Structure)** 抽象机制，解决了 LLM Agent 在处理复杂、长链路任务时的泛化能力不足问题。

* **核心功能：**
    * **Python 抽象层**：将 LLM 的输出直接映射为可执行的 Python 代码片段，增强了任务执行的确定性。
    * **自动评价循环**：建立了一套多维评估机制，自动纠正逻辑错误，使 Zero-shot 任务成功率提升至 **66.4%**。
    * **成本优化**：通过结构化提示词（Structured Prompting）和思维链剪枝，将昂贵的 LLM 调用次数降低了 **61.5%**。
* **技术栈：** `Python`, `LangChain`, `GPT-4/Llama-3`, `Pytest (Unit Test Strategy)`, `JSON Schema`.



#### [📂 仓库地址：Enterprise Q&A Engine](https://github.com/你的用户名/rag-engine)
**项目描述**：生产级的 RAG（检索增强生成）引擎，专为解决企业私有知识库中的幻觉问题和可扩展性设计。

* **核心功能：**
    * **高级检索流水线**：集成 **Hyde (假设性文档嵌入)** 与多尺度 **Sentence-Transformers**，将复杂语义查询的事实准确率提升至 **92%**。
    * **工业级部署治理**：在 **Kubernetes** 上通过 **Istio** 实现流量精细化管理和灰度发布，环境搭建与实验编排提效 **80%**。
    * **闭环监控**：利用 **Prometheus/Grafana** 监控 Token 消耗、推理延迟及模型幻觉率。
* **技术栈：** `Llama-3`, `Milvus (Vector DB)`, `Istio`, `LoRA`, `Kafka`, `Prometheus`.

---

### 📱 移动端 AI 与机器人 (Edge AI & Robotics)

#### [📂 仓库地址：On-Device Multimodal Inference](https://github.com/你的用户名/mobile-ai)
**项目描述**：在移动端实现 4 模型并行推理的高性能方案，专注于在资源极度受限的设备上实现实时交互。

* **核心功能：**
    * **极致端侧优化**：通过 **INT8 量化** 和 **ExecuTorch** 框架，利用 **ARM NEON** 指令集并行化，实现端到端延迟 **< 200ms**。
    * **异构流水线**：设计了针对 ARM CPU 的混合推理流水线，实现 **3.2倍** 的推理提速。
    * **内存池管理**：针对 6GB 显存上限，设计了动态内存调度器，支持多模态模型的高效上下文切换。
* **技术栈：** `C++`, `Python`, `ExecuTorch`, `PyTorch`, `ARM NEON`, `OpenCL`.



#### [📂 仓库地址：Multimodal HRL Robotic Planning](https://github.com/你的用户名/hrl-robotics)
**项目描述**：结合层级强化学习 (HRL) 与多模态感知，解决复杂模拟环境中的长距离机器人任务规划。

* **核心功能：**
    * **子任务分解机制**：利用 Transformer 编码器提取视觉-语言特征，通过层级结构（High-level Policy & Low-level Action）将任务成功率提升 **25%**。
    * **样本高效学习**：引入奖励塑形（Reward Shaping）算法，将训练所需的交互样本数量降低了 **80%**。
* **技术栈：** `PyTorch`, `Gym/Isaac Gym`, `Transformer`, `SAC`, `HRL`.

---

### 🛠 核心技术栈 (Tech Stack)

| 类别 | 技术工具 |
| :--- | :--- |
| **Backend** | Java 21, Spring Cloud, Go, MySQL, Redis, Kafka |
| **AI / ML** | PyTorch, Transformer, LangChain, RAG, Reinforcement Learning |
| **Cloud Native** | Kubernetes, Docker, Istio, Prometheus, Grafana |
| **Edge / Optim** | ExecuTorch, INT8 Quantization, ARM NEON, C++ |

---

### 📊 工程贡献
![Metrics](https://metrics.lecoq.io/你的用户名?template=classic&base=header%2C%20activity%2C%20community%2C%20repositories&config.timezone=Asia%2FShanghai)

---

<p align="left">
  <a href="mailto:luyang96377@gmail.com">
    <img src="https://img.shields.io/badge/Email-luyang96377@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
