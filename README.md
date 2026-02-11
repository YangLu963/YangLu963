# 👋 Hi, I'm Yang Lu
<p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&width=550&lines=Distributed+Systems+Architect;AI+%26+Robotics+Researcher;LLM+Agent+Architect;On-Device+AI+Expert" alt="Typing SVG" /> </p>

### 📖 About Me
> 🚀 **Cross-domain Developer & Researcher** specializing in the synergy between **High-Performance Distributed Systems** and **Frontier AI**. 
> Experienced in the full-stack lifecycle: from high-concurrency backend scaling to the deployment of lightweight AI models on edge devices.

---

### 🏆 Flagship Project: Distributed E-Commerce Platform & Real-time Recommendation

#### [📂 Repository: Distributed E-Commerce System](https://github.com/YourUsername/ecommerce-repo)
**Description**: A robust distributed e-commerce ecosystem designed to support millions of concurrent users, featuring an integrated real-time user behavior analysis and recommendation engine.

* **Core Features:**
    * **High-Concurrency Architecture**: Built on **Spring Cloud Alibaba** for microservices governance. Implemented a **Redis 3-level caching strategy** (Local-Distributed-Persistent), reducing hot-spot API latency to **< 50ms**.
    * **Real-time Recommendation**: Leveraged **Spark Streaming** to consume **Kafka** user-click streams, utilizing **ALS + DNN** hybrid models for minute-level profile updates, achieving a **22%** increase in CTR.
    * **High Availability**: Engineered a full-link circuit breaking and throttling solution with **Sentinel**, integrated with **Kubernetes HPA** (Horizontal Pod Autoscaling) to ensure **99.99%** availability during peak traffic events.
* **Tech Stack:** `Java 21`, `Spring Cloud`, `Kafka`, `Spark`, `Redis`, `MySQL`, `Kubernetes`, `Docker`, `Prometheus`.

---

### 🧠 LLM & Agent Research

#### [📂 Repository: P-E-S Agent Mechanism](https://github.com/YourUsername/pes-agent)
**Description**: Proposed and implemented the **P-E-S (Python-Evaluation-Structure)** abstraction mechanism to solve compositional generalization challenges in LLM Agents for complex, long-chain tasks.

* **Core Features:**
    * **Python Abstraction Layer**: Maps LLM reasoning outputs directly into executable Python code snippets, significantly enhancing task execution determinism.
    * **Auto-Evaluation Loop**: Established a multi-dimensional evaluation mechanism to auto-correct logical errors, boosting **Zero-shot success rate to 66.4%**.
    * **Cost Optimization**: Utilized **Structured Prompting** and Chain-of-Thought (CoT) pruning to reduce expensive LLM API calls by **61.5%**.
* **Tech Stack:** `Python`, `LangChain`, `GPT-4/Llama-3`, `Pytest (Unit Test Strategy)`, `JSON Schema`.

#### [📂 Repository: Enterprise Q&A Engine (RAG)](https://github.com/YourUsername/rag-engine)
**Description**: A production-grade RAG engine designed to eliminate hallucinations and solve scalability issues within enterprise private knowledge bases.

* **Core Features:**
    * **Advanced Retrieval Pipeline**: Integrated **HyDE (Hypothetical Document Embeddings)** and multi-scale **Sentence-Transformers**, improving factual accuracy to **92%**.
    * **Industrial Deployment**: Orchestrated on **Kubernetes** via **Istio** for fine-grained traffic management and canary releases, improving environment setup efficiency by **80%**.
    * **Closed-loop Monitoring**: Leveraged **Prometheus/Grafana** to track token consumption, inference latency, and hallucination rates.
* **Tech Stack:** `Llama-3`, `Milvus (Vector DB)`, `Istio`, `LoRA`, `Kafka`, `Prometheus`.

---

### 📱 Edge AI & Robotics

#### [📂 Repository: On-Device Multimodal Inference](https://github.com/YourUsername/mobile-ai)
**Description**: A high-performance solution for 4-model parallel inference on mobile devices, enabling localized real-time AI interaction.

* **Core Features:**
    * **Extreme Edge Optimization**: Achieved end-to-end latency **< 200ms** through **INT8 Quantization** and the **ExecuTorch** framework utilizing **ARM NEON** instruction set parallelism.
    * **Heterogeneous Pipeline**: Engineered a hybrid inference pipeline for ARM CPUs, achieving a **3.2x speedup**.
    * **Memory Pool Management**: Designed a dynamic memory scheduler to handle multi-model context switching under a strict **6GB RAM** constraint.
* **Tech Stack:** `C++`, `Python`, `ExecuTorch`, `PyTorch`, `ARM NEON`, `OpenCL`.

#### [📂 Repository: Multimodal HRL Robotic Planning](https://github.com/YourUsername/hrl-robotics)
**Description**: Combines Hierarchical Reinforcement Learning (HRL) with multimodal perception to solve long-horizon robotic task planning in simulation.

* **Core Features:**
    * **Sub-task Decomposition**: Utilized Transformer encoders for vision-language feature extraction, increasing task success rate by **25%** through a High-level Policy & Low-level Action hierarchy.
    * **Sample Efficient Learning**: Implemented **Reward Shaping** algorithms to reduce required training samples by **80%**.
* **Tech Stack:** `PyTorch`, `Gym/Isaac Gym`, `Transformer`, `SAC`, `HRL`.

---

### 🛠 Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Backend** | Java 21, Spring Cloud, Go, MySQL, Redis, Kafka |
| **AI / ML** | PyTorch, Transformer, LangChain, RAG, Reinforcement Learning |
| **Cloud Native** | Kubernetes, Docker, Istio, Prometheus, Grafana |
| **Edge / Optim** | ExecuTorch, INT8 Quantization, ARM NEON, C++ |

---

### 📊 Engineering Contributions
![Metrics](https://metrics.lecoq.io/你的用户名?template=classic&base=header%2C%20activity%2C%20community%2C%20repositories&config.timezone=Asia%2FShanghai)

---

### 🤝 Connect with Me
<p align="left">
  <a href="mailto:luyang96377@gmail.com">
    <img src="https://img.shields.io/badge/Email-luyang96377@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
