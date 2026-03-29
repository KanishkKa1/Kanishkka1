# 👋 Kanishk Agarwal

## 🚀 C++ Systems Engineer | Concurrency | AI Infrastructure

I build **high-performance backend systems** with strict invariants, controlled concurrency, and predictable failure modes — extending into **agentic AI infrastructure and LLM orchestration systems**.

- 🏢 Associate Software Engineer @ Harman International  
- ⚡ Focus: C++ (17/20), Multithreading, System Design  
- 🤖 Working with: LangGraph, MCP, AI Agents  
- 🧠 Approach: Build systems from first principles — not just use abstractions  

---

## 🚀 Flagship Systems

### ⚡ Multithreaded Task Scheduler  
🔗 https://github.com/KanishkKa1/cpp_TaskScheduler

- Thread pool with **bounded task queue (backpressure-aware design)**  
- Producer–consumer model using `condition_variable` with predicate-based waiting  
- Deterministic shutdown (no lost tasks, no dangling threads)  
- Explored trade-offs: **throughput vs fairness**, blocking vs non-blocking APIs  
- Designed under **high contention scenarios (multiple producers / workers)**  

---

### 🔧 Custom STL-like `vector<T>`

- Manual memory management with full **Rule of Five compliance**  
- Geometric growth strategy → amortized O(1) push_back  
- Improved **cache locality in sequential access patterns**  
- Reduced allocation overhead via controlled resizing strategy  
- Compared behavior against `std::vector` for correctness + performance  

---

### 🔥 Custom Redis (In Progress — Systems Build Phase)

- In-memory key-value store with focus on **latency + memory layout**  
- Designing **write-ahead logging (WAL)** for durability  
- Exploring **eviction policies (LRU/LFU)** and memory constraints  
- Planning **replication + concurrency control mechanisms**  
- Goal: understand trade-offs behind real-world data stores  

---

## 📈 Experience

### 🏢 Associate Software Engineer — Harman International  
**Jan 2025 – Present**

- Enforced **system invariants at API boundaries**, preventing invalid state propagation  
- Reduced workflow latency from **~6s → 0.8s** via system-level optimizations  
- Improved reliability by eliminating state corruption across async flows  
- Debugged concurrency + memory issues using **gdb and profiling tools**  

---

### 🤖 ML Engineer Intern — Assisto Technologies  
**Jan 2024 – May 2024**

- Reduced inference latency by **~30%**  
- Built RAG pipelines and computer vision systems  
- Worked on deployment-oriented ML systems (not just models)  

---

## ⚙️ Technical Stack

### Systems
- C++ (17/20), Multithreading, Concurrency Design  
- Memory Management, Cache Locality, Performance Optimization  

### AI Infrastructure
- LangGraph, MCP (Model Context Protocol)  
- PyTorch, ONNX, YOLOv8  

### Data & Ops
- SQL, Docker, Git, MLOps Pipelines  

---

## 🧠 Engineering Signals

- Designed systems with **explicit invariants** to eliminate invalid states  
- Built concurrency-safe workflows under **real contention scenarios**  
- Focus on **predictable failure modes over silent corruption**  
- Debugging-first mindset: isolate → reproduce → fix → validate  

---

## 🧠 How I Think

When designing systems:

1. Define invariants first  
2. Identify failure modes early  
3. Prefer **bounded systems** over unbounded growth  
4. Separate **control plane vs execution plane**  
5. Optimize only after measurement  

---

## ⚡ Engineering Principles (Applied)

- **Correctness > Performance** → enforced via invariants  
- **Backpressure-aware design** → prevents system overload  
- **Observability-first systems** → logs, metrics, failure surfaces  
- Systems should fail **explicitly and predictably**, not silently  

---

## 🎯 Open To

- C++ Backend / Systems Engineering Roles  
- High-performance systems, infra, or platform teams  
- Work involving concurrency, distributed systems, or AI infrastructure  

---

## 🤝 Connect

- 💼 LinkedIn: https://www.linkedin.com/in/kanishkaga/  
- 📧 Email: agarwalkanishk12345@gmail.com  
- 🌐 Portfolio: https://github.com/KanishkKa1/Portfolio  
