# Gabriel Lima

**Systems & low-level engineer — I build things from scratch.**

Compilers, GPU kernels, deep-learning internals, distributed systems. I reach for a
first-principles implementation when it teaches more than a framework would. Every
project below is built from the ground up and ships with **tests, benchmarks, and
bilingual (EN/PT) docs**.

---

### 🧠 Languages & Compilers

| Project | What it is |
|---|---|
| **[tired](https://github.com/Tech-GabrielLima/tired)** · `Rust` | A **compiled DSL for consuming HTTP APIs**: compile-time error handling, automatic request parallelization, and dead-request elimination. A real compiler — lexer → parser → type-checker → IR → optimizer → concurrent runtime. |

### ⚙️ Systems & Distributed Backends

| Project | What it is |
|---|---|
| **[raft-kv-store](https://github.com/Tech-GabrielLima/raft-kv-store)** · `Java 21` | **Raft consensus from scratch** (all 7 phases) + a network-fault simulator and a Wing–Gong–Lowe linearizability checker, behind a linearizable key-value store. Zero dependencies. |
| **[lowlatency-matching-engine](https://github.com/Tech-GabrielLima/lowlatency-matching-engine)** · `WebFlux + LMAX Disruptor` | A single-writer **limit-order-book matching engine**. ~3.6M orders/s, p99 ≈ 60µs. |
| **[event-sourced-ledger](https://github.com/Tech-GabrielLima/event-sourced-ledger)** · `Spring Boot` | A distributed **double-entry financial ledger**: event sourcing, CQRS, saga + transactional outbox, idempotent money movement. |

### 🤖 ML & GPU — from scratch

| Project | What it is |
|---|---|
| **[nabla-autograd](https://github.com/Tech-GabrielLima/nabla-autograd)** · `Python / CUDA` | A **micro-PyTorch**: reverse-mode autograd with CPU & GPU backends — gradients matching PyTorch to ~1e-7. |
| **[nano-llm-inference](https://github.com/Tech-GabrielLima/nano-llm-inference)** · `NumPy + Triton` | A **GPT-2 inference engine**: KV-cache, INT8 quantization and FlashAttention. |
| **[cuda-kernels-from-scratch](https://github.com/Tech-GabrielLima/cuda-kernels-from-scratch)** · `CUDA` | GEMM from naive to **Tensor Cores**, plus reduce / softmax / layernorm / conv2d — benchmarked against cuBLAS. |

---

**Stack:** Rust · CUDA / C++ · Python (NumPy, Triton) · Java 21 / Spring Boot · Elixir · SQL (PostgreSQL, MySQL) · NoSQL · Distributed Systems · Compilers · GPU Computing


📫 **port.gabriellima@gmail.com**
