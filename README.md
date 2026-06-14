# Austin Varnon

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-austinvarnon-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/austinvarnon/)

  I build tools to solve problems I'm facing, or because something seems interesting enough to apply a concept I'm working through — sometimes both.

  Professional background in Java, Spring Boot, and enterprise backend systems at a large bank — containerization, OpenShift/K8s operations, CI/CD automation, and security remediation at
  compliance scale. Outside of work I run a two-node homelab for end-to-end project ownership: building, shipping, and operating software I actually use. Currently focused on Rust systems
  programming and local AI infrastructure.

  ---

  ## 📌 Featured Projects

  <table>
  <tr>
  <td width="50%" valign="top">

  ### [`homelab-rs`](https://github.com/asvarnon/homelab-rs)
  **Homelab MCP server**

  A Rust workspace that exposes homelab infrastructure (Proxmox, OPNsense) as AI-callable MCP tools — node/cluster status, DHCP leases, and more. Deployed behind Cloudflare Zero Trust
  with atomic CI/CD deploy and automatic rollback. Split into `homelab-core` (HTTP client, config, tool logic) and `homelab-mcp` (thin `rmcp` adapter).

  ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
  ![MCP](https://img.shields.io/badge/MCP_Protocol-000000?style=flat-square)
  ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

  </td>
  <td width="50%" valign="top">

  ### [`Husk`](https://github.com/asvarnon/Husk)
  **Self-hosted local LLM Discord bot**

  A persona-agnostic Discord bot backed by a local Ollama model. Threaded conversations, optional SearXNG web search, and two-tier memory — hot per-thread history in Redis, durable
  cross-thread recall via `context-forge`. Everything runs on your own infrastructure, no third-party API.

  ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
  ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
  ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

  </td>
  </tr>
  <tr>
  <td colspan="2" valign="top">

  ### [`context-forge`](https://github.com/asvarnon/context-forge)
  **Local-first memory library for LLM apps**

  A Rust crate providing persistent memory for LLM applications — SQLite + FTS5 BM25 retrieval, recency-decay scoring, and token-budget-aware context assembly. No network calls, no
  async runtime, no cloud dependency. Powers `Husk`'s long-term memory.

  ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
  ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
  ![crates.io](https://img.shields.io/badge/crates.io-context--forge-orange?style=flat-square&logo=rust&logoColor=white)

  </td>
  </tr>
  </table>

  ---

  ## 🛠 Tech & Tools

  **Professional**

  ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
  ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
  ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
  ![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
  ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
  ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
  ![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)

  **Homelab & Personal**

  ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
  ![MCP](https://img.shields.io/badge/MCP_Protocol-000000?style=flat-square)
  ![Tokio](https://img.shields.io/badge/Tokio-async-000000?style=flat-square)
  ![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat-square)
  ![cuda-oxide](https://img.shields.io/badge/cuda--oxide-76B900?style=flat-square)
  ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
  ![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
  ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
  ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
  ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
  ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

  ---

  ## 💡 Philosophy

  I learn by building. Applying a concept until it becomes a skill is the only path that actually sticks. Most of what's here is that process made visible.

  ---

  ## 🔭 Currently

  - Rust systems programming — shipping production tooling in the homelab
  - Local LLM inference and AI-augmented infrastructure (Ollama, llama.cpp, MCP)
  - GPU compute fundamentals (cuda-oxide, Rust + CUDA)
  - Security tooling and compliance engineering (professional focus)
