<p align="center">
  <img src="https://raw.githubusercontent.com/dchrnv/dchrnv/main/assets/header.svg" alt="Denys Chernov — Systems &amp; Memory Architect" width="880"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/dchrnv/dchrnv/main/assets/now.svg" alt="now" width="720"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Rust-DEA584?style=flat&amp;logo=rust&amp;logoColor=black" height="22"/>
  <img src="https://img.shields.io/badge/Merkle_DAG-SHA256-58a6ff?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/redb-ACID_Store-green?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/Docker_OCI-2496ED?style=flat&amp;logo=docker&amp;logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/Deterministic-100%25-fc6d26?style=flat" height="22"/>
</p>

---

Systems engineer and memory architecture researcher. I design deterministic, low-level associative memory engines in Rust that turn raw byte streams into cryptographic Merkle DAGs, and I have a strong preference for mathematical invariants over opaque neural black boxes.

Most modern cognitive systems rely on multi-gigabyte vector databases, floating-point embeddings that drift with every checkpoint, and fragile prompt scaffolding. I build zero-vocabulary state machines where memory is byte-exact, compression is calculated online, and active working memory is bounded by provable temporal reachability.

### Stack

Day to day:

- **Rust (2024 Edition)** — memory arenas, zero-copy byte streams, lock-free concurrency, deterministic data structures
- **Merkle DAGs & Cryptographic Interning** — SHA-256, BLAKE2, bottom-up concept emergence from raw factory bytes
- **ACID Embedded Storage** — single-transaction durability via `redb`, memory mapping via `memmap2`
- **Information Theory & Surprise** — online surprise calculation ($S_{\text{static}}, S_{\text{growth}}$), streaming greedy folding $O(N)$
- **Graph & Co-occurrence** — sparse PPMI matrices, associative recall, biased random walks

Opinions I hold quietly:

- If a system cannot explain its internal state without querying another LLM, it is not a memory engine—it is a cache with opinions
- Vector databases are often an expensive workaround for the lack of a proper emergent grammar
- Generational GC without sweep ($K=3$ temporal root reachability) is all the forgetting an agent needs
- 100 passing deterministic tests beats a 1,000-line prompt every single day
- If state is not byte-exact and reproducible, debugging it is just guesswork

### Projects

**[axmg](https://github.com/dchrnv/axmg)** — Universal Merkle DAG Associative Memory Engine for Rust. Embedded, deterministic, zero-vocabulary associative memory engine. Replaces heavyweight vector databases with an online cryptographic DAG, dynamic working memory ($K=3$), online surprise metric, and sub-graph PPMI recall. Published on [crates.io/crates/axmg](https://crates.io/crates/axmg) and [GitHub Packages](https://github.com/dchrnv/axmg/pkgs/container/axmg).

**[axiom](https://github.com/dchrnv/axiom)** — Foundations of associative cognitive structures, byte-level tokenization, and emergent linguistic topologies.

**[axmv2](https://github.com/dchrnv/axmv2)** — Explorations in multi-agent memory synchronization and temporal graph evolution.

### What I am exploring right now

Currently formalizing Model Context Protocol (MCP) bridges so autonomous agents can plug directly into deterministic associative memory without middleware overhead, and exploring zero-alloc arena compaction for long-running streaming daemons.

### 📊 Activity

<p align="center">
  <img height="160" src="https://gh-profile-stats.zli39uclan.workers.dev/stats?username=dchrnv&amp;accent=fc6d26&amp;cell=sharp&amp;hide_border=true"/>
  <img height="160" src="https://gh-profile-stats.zli39uclan.workers.dev/top-langs?username=dchrnv&amp;accent=fc6d26&amp;cell=sharp&amp;hide_border=true"/>
</p>
<p align="center">
  <img width="720" src="https://gh-profile-stats.zli39uclan.workers.dev/activity?username=dchrnv&amp;accent=fc6d26&amp;cell=sharp&amp;hide_border=true"/>
</p>

### Contact

Open an issue or start a discussion on any of the repositories above. For architectural inquiries or collaboration on deterministic memory engines, reach out via GitHub or email.

---

Deterministic · Byte-exact · Built with Rust
