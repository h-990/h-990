<div align="center">

<!-- ═══════════ 3D ISOMETRIC ANIMATED HERO ═══════════ -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/h-990/h-990/main/assets/hero-3d.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/h-990/h-990/main/assets/hero-3d.svg">
  <img src="https://raw.githubusercontent.com/h-990/h-990/main/assets/hero-3d.svg" alt="Harsh Kumar 3D Animated Hero" width="100%" />
</picture>

<br>

<!-- ═══════════ TYPING SVG ANIMATION ═══════════ -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&multiline=true&repeat=true&width=840&height=100&lines=%E2%88%B4+Systems+Architect%3A+C11+storage+engines%2C+custom+allocators+%26+WALs;%E2%88%B4+Pure+Math+%26+Logic%3A+abstract+algebra%2C+category+theory+%26+formal+proofs;%E2%88%B4+Information+Theory%3A+probing+the+theoretical+limits+of+modern+computing;%E2%88%B4+AI+Architectures%3A+neuro-symbolic%2C+bio-inspired+%26+deterministic+systems;%E2%88%B4+Common+Lisp+macro+sorcery+%C2%B7+Bare-metal+C+substrate+%C2%B7+Python+glue" alt="Typing SVG" />
</a>

<br>

<!-- ═══════════ DOMAIN BADGES ═══════════ -->
<p align="center">
  <img src="https://img.shields.io/badge/Systems-C11_Storage_Engines_%26_WAL-161b22?style=for-the-badge&logo=c&logoColor=00ff41&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Theory-Pure_Mathematics_%26_Logic-161b22?style=for-the-badge&logo=wolframmathematica&logoColor=ff6600&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Inquiry-Information_Theory-161b22?style=for-the-badge&logo=scikitlearn&logoColor=00e5ff&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/AI-Neuro--Symbolic_%26_Bio--Inspired-161b22?style=for-the-badge&logo=openai&logoColor=a78bfa&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Craft-Common_Lisp_%C2%B7_C_%C2%B7_Python-161b22?style=for-the-badge&logo=commonlisp&logoColor=00ff41&labelColor=0d1117"/>
</p>

</div>

---

<h2 align="center">🧠 <code>(defun who-am-i () ...)</code></h2>

<div align="center">
<table>
<tr><td>
<pre lang="lisp">
(defparameter *harsh*
  (make-instance 'multidisciplinary-builder
    :identity     "Independent researcher, systems builder & deconstructor of machines"
    :doctrine     "Rather than just assembling black-box applications, I deconstruct
                   them to understand the underlying cache lines, axioms, and entropy."
    :obsessions   '(:low-level-storage-engines
                    :pure-mathematics-and-formal-logic
                    :information-theory-limits
                    :neuro-symbolic-ai-architectures
                    :lisp-metaprogramming-and-c-ffi)
    :toolbox      '(:common-lisp "For homoiconicity, macros & symbolic manipulation"
                    :pure-c      "The universal lingua franca; bare-metal denominator"
                    :pure-math   "Abstract algebra, category theory, mathematical logic"
                    :python      "Rapid prototyping, exploratory data science & glue"
                    :rust-cpp    "High-throughput native concurrency & desktop GUIs")
    :humour-log   "Why write 50 lines of Python when you can write a 5,000-line C11
                   storage engine with custom WAL ring buffers just to understand how a page faults?"))
</pre>
</td></tr>
</table>
</div>

---

<h2 align="center">🔭 Core Inquiries & Research Pillars</h2>

<div align="center">
<i>Exploring the computational continuum: from silicon cache lines to mathematical logic.</i>
</div>

<br>

<table>
<tr>
<td width="50%" valign="top">
<h3>⚙️ 1. Low-Level Systems & Storage Engines</h3>
<b>"Primitives over dependencies."</b><br><br>
Deep fascination with memory layout, hardware mechanics, and zero-overhead data structures:
<ul>
  <li><b>Cache-Line Addressing:</b> Aligning object headers strictly to 64 bytes for single L1 fetches.</li>
  <li><b>Deterministic Durability:</b> Implementing Write-Ahead Log (WAL) ring buffers with group commit and CRC32C Castagnoli hardware acceleration.</li>
  <li><b>Explicit Buffer Pools:</b> Rejecting <code>mmap</code> unpredictability in favor of bounded user-space caches with LRU eviction and pin/lease semantics.</li>
  <li><b>Custom Memory Allocators:</b> Power-of-2 slab allocators with deferred reuse to eliminate ABA pointer hazards.</li>
</ul>
</td>
<td width="50%" valign="top">
<h3>∫ 2. Pure Mathematics & Formal Logic</h3>
<b>"If it can't be formalized, it's just a conjecture."</b><br><br>
Applying mathematical rigor to software design and computation theory:
<ul>
  <li><b>Abstract Algebra & Category Theory:</b> Modeling software components as algebraic structures, monads, and morphisms.</li>
  <li><b>Formal Logic & Proof Systems:</b> Deconstructing algorithms into verifiable axioms rather than relying on empirical trial-and-error.</li>
  <li><b>Graph & Containment Topology:</b> Designing lexicographically ordered prefix-length varint tree codecs for hierarchical graph navigation.</li>
  <li><b>Mathematical Modeling:</b> Exploring deterministic state spaces where invariants are guaranteed by construction.</li>
</ul>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>📐 3. Information Theory & Limits of Computing</h3>
<b>"Information is conserved. Where do the missing bits come from?"</b><br><br>
Looking at software and artificial intelligence through an information-theoretic lens:
<ul>
  <li><b>Information Conservation in Compilers:</b> In a rule-based specification (like a WYSIWYG or DSL compiler), information is conserved: $\Delta I = 0$.</li>
  <li><b>Statistical Gap-Filling in AI:</b> In underspecified natural language prompts, the input information $I_{in}$ is sparse; modern LLMs statistically supply the missing bits from prior weights.</li>
  <li><b>The Constraint Collapse Principle:</b>
    $$\lim_{\text{constraints} \to \text{complete}} |\Omega_{\text{solution}}| = 1 \implies \text{Utility}(\text{Stochastic Guessing}) = 0$$
  </li>
  <li>Investigating how explicit constraints shrink state spaces to eliminate non-deterministic hallucinations.</li>
</ul>
</td>
<td width="50%" valign="top">
<h3>🧠 4. Neuro-Symbolic & AI Architectures</h3>
<b>"Beyond pure statistical curve-fitting."</b><br><br>
Exploring architectures that bridge statistical learning and symbolic reasoning:
<ul>
  <li><b>Neuro-Symbolic Hybridization:</b> Pairing neural networks (for perception & soft heuristics) with symbolic knowledge graphs (for deterministic reasoning & verification).</li>
  <li><b>Reviving GOFAI:</b> Resurrecting Good Old-Fashioned AI, rule engines, and explicit knowledge representations for safety-critical domains.</li>
  <li><b>Bio-Inspired Distributed Systems:</b> Designing multi-agent ecosystems with decoupled brains (Cortex), hands (Executors), and message buses (ZeroMQ).</li>
  <li><b>Inference Auditing:</b> Building native C++ tools to benchmark and stress-test LLM APIs across multiple providers.</li>
</ul>
</td>
</tr>
</table>

---

<h2 align="center">🛠️ <code>ls -la ~/arsenal/</code></h2>

<div align="center">

| Domain | Tools & Languages | Rationale & Practical Use |
|:---|:---|:---|
| **Low-Level Systems** | <img src="https://img.shields.io/badge/C11-00599C?style=flat-square&logo=c&logoColor=ffffff"/> <img src="https://img.shields.io/badge/POSIX-Direct_I/O-161b22?style=flat-square&logo=linux&logoColor=00ff41"/> | The universal substrate. Zero-overhead abstractions, cache-line alignment (64B), and custom memory allocators. Easily exposed via C-ABI to other runtimes. |
| **Pure Mathematics** | <img src="https://img.shields.io/badge/Abstract_Algebra-Formal_Logic-ff6600?style=flat-square&logo=wolfram&logoColor=ffffff"/> | Category Theory, Information Theory (Shannon Entropy), and Topology. The foundational compass behind system architecture. |
| **Symbolic & Metaprogramming** | <img src="https://img.shields.io/badge/Common_Lisp-000000?style=flat-square&logo=commonlisp&logoColor=00ff41"/> | Homoiconicity and syntactic macros. Treating code as data; the ultimate vehicle for symbolic AI, DSLs, and exploratory computing. |
| **High-Throughput Systems** | <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=ff6600"/> <img src="https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=cplusplus&logoColor=ffffff"/> | Zero-cost memory safety, distributed message buses (ZeroMQ), and native desktop GUI tooling (raylib, egui). |
| **Prototyping & Glue** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=ffffff"/> | Rapid mathematical experimentation, exploratory data science, OS-level accessibility scripting, and pipeline integration. |

</div>

---

<h2 align="center">⚡ Featured Architectural Creations</h2>

<div align="center">
<table>
<tr>
<td align="center" width="50%">
<h3><a href="https://github.com/h-990/kb-core">🏛️ kb-core</a></h3>
<code>C11</code> <code>Storage Engine</code> <code>Zero-mmap</code> <code>WAL</code><br><br>
<b>Low-Level Systems:</b> Ultra-high-performance single-file embedded storage engine for hierarchical knowledge graphs. 64-byte immovable cache-line headers, prefix-length varint path codec, slab allocators with deferred reuse, and a crash-resilient WAL ring buffer. (48,700+ assertions passing).
</td>
<td align="center" width="50%">
<h3><a href="https://github.com/h-990/system_synapse">🧠 system_synapse</a></h3>
<code>Rust</code> <code>ZeroMQ</code> <code>egui</code> <code>tokio</code><br><br>
<b>Bio-Inspired AI:</b> Artificial intelligence ecosystem mimicking mammalian neurological signal flow — Cortex Citadel (brain), Executor (hand), and Nervous System (ZeroMQ bus) with real-time telemetry.
</td>
</tr>
<tr>
<td align="center" width="50%">
<h3><a href="https://github.com/h-990/API-Tester">🔬 API-Tester</a></h3>
<code>C++20</code> <code>raylib</code> <code>CMake</code> <code>curl</code><br><br>
<b>Developer Tooling & Auditing:</b> Native cross-platform desktop suite for stress-testing, latency profiling, and auditing LLM inference APIs across 9+ providers (Google AI, OpenRouter, Mistral, Groq).
</td>
<td align="center" width="50%">
<h3><a href="https://github.com/h-990/z-automation">⚡ z-automation</a></h3>
<code>Python</code> <code>macOS AXUI</code><br><br>
<b>OS Automation:</b> System-level agent automation — training agents to control, inspect, and automate complex workflows via native macOS Accessibility UI hierarchy trees.
</td>
</tr>
</table>
</div>

---

<h2 align="center">📊 <code>git telemetry --realtime</code></h2>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=h-990&show_icons=true&theme=chartreuse-dark&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&icon_color=ff6600&border_color=30363d&hide_border=false&count_private=true"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=h-990&theme=chartreuse-dark&background=0D1117&border=30363D&stroke=00ff41&ring=ff6600&fire=ff6600&currStreakLabel=00ff41&sideLabels=c9d1d9&currStreakNum=00ff41&dates=586069&sideNums=00ff41"/>

<br><br>

<img width="55%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=h-990&layout=compact&theme=chartreuse-dark&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&border_color=30363d&langs_count=8"/>

<br><br>

<!-- Animated Git Snake -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/h-990/h-990/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/h-990/h-990/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/h-990/h-990/output/github-snake-dark.svg" />
</picture>

</div>

---

<h2 align="center">📡 <code>ping -c 1 harsh.network</code></h2>

<p align="center">
Always excited to collaborate with systems hackers, mathematicians, Lisp explorers, and builders interested in the foundational mechanics of computing.
</p>

<div align="center">

<a href="https://www.linkedin.com/in/harsh-kumar-206b023b3/">
  <img src="https://img.shields.io/badge/LinkedIn-Harsh_Kumar-0d1117?style=for-the-badge&logo=linkedin&logoColor=00ff41&labelColor=161b22"/>
</a>
<a href="https://github.com/h-990">
  <img src="https://img.shields.io/badge/GitHub-h--990-0d1117?style=for-the-badge&logo=github&logoColor=ff6600&labelColor=161b22"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=h-990&color=00ff41&style=for-the-badge&label=COMPUTATIONAL+STATES"/>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:ff6600,50:00ff41,100:0d1117&height=100&section=footer" width="100%"/>

<i>"From bare-metal cache lines to pure mathematical abstractions."</i>

</div>
