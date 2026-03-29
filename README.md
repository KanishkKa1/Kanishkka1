# 👋 Kanishk Agarwal  

### ⚡ C++ Systems Engineer | Concurrency | AI Infrastructure  

I build **high-performance backend systems** with strict invariants, controlled concurrency, and predictable failure modes — extending into **agentic AI infrastructure and LLM orchestration systems**.

---

## 🚀 Flagship Systems  

### ⚡ Multithreaded Task Scheduler  
🔗 https://github.com/KanishkKa1/cpp_TaskScheduler  

- Bounded thread pool with **backpressure-aware queue**  
- Producer–consumer model using `condition_variable` with predicates  
- Deterministic shutdown → no lost tasks, no dangling threads  
- Explored **throughput vs fairness trade-offs**  
- Designed under **high contention (multi-producer / multi-worker)**  

---

### 🔧 Custom STL-like `vector<T>`  

- Manual memory management (**Rule of Five**)  
- Amortized O(1) growth via geometric resizing  
- Improved **cache locality** in sequential workloads  
- Reduced allocation overhead with optimized growth strategy  
- Benchmarked behavior vs `std::vector`  

---

### 🔥 Custom Redis (Systems Build Phase)  

- In-memory key-value store focused on **latency + memory layout**  
- Designing **Write-Ahead Logging (WAL)** for durability  
- Exploring **LRU/LFU eviction strategies**  
- Planning **replication + concurrency control**  
- Goal: understand real-world datastore trade-offs  

---

## 📈 Experience  

### 🏢 Associate Software Engineer — Harman International  
**Jan 2025 – Present**

- Enforced **invariants at API boundaries** → prevented invalid state propagation  
- Reduced latency from **~6s → 0.8s** via system-level optimizations  
- Improved reliability by eliminating async state corruption  
- Debugged concurrency + memory issues using **gdb + profilers**  

---

### 🤖 ML Engineer Intern — Assisto Technologies  
**Jan 2024 – May 2024**

- Reduced inference latency by **~30%**  
- Built RAG pipelines and CV systems  
- Focused on deployment-ready ML systems  

---

## ⚙️ Tech Stack  

**Systems:**  
C++ (17/20), Multithreading, Concurrency Design, Memory Management  

**AI Infra:**  
LangGraph, MCP, PyTorch, ONNX  

**Ops:**  
SQL, Docker, Git, MLOps  

---

## 🧠 Engineering Signals  

- Designed systems with **explicit invariants**  
- Built under **real contention scenarios**  
- Prefer **predictable failures over silent corruption**  
- Debugging-first approach → isolate → reproduce → fix  

---

## 🧠 How I Think  

1. Define invariants first  
2. Identify failure modes early  
3. Prefer **bounded systems**  
4. Separate control vs execution planes  
5. Optimize after measurement  

---

## 📊 GitHub Activity  

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kanishkka1&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=1800" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kanishkka1&theme=tokyonight&hide_border=true" />
</p>

---

## 🧩 Problem Solving  

<p align="center">
  <a href="https://leetcode.com/u/agarkanishk/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-orange?style=for-the-badge&logo=leetcode">
  </a>
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/agarkanishk?theme=dark&font=baloo&ext=heatmap" />
</p>

---

## 🤝 Connect  

<p align="center">
  <a href="https://www.linkedin.com/in/kanishkaga/">
    <img src="https://img.shields.io/badge/LinkedIn-Kanishk%20Agarwal-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="mailto:agarwalkanishk12345@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail">
  </a>
  <a href="https://github.com/KanishkKa1/Portfolio">
    <img src="https://img.shields.io/badge/Portfolio-View-black?style=for-the-badge&logo=vercel">
  </a>
</p>
