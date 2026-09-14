<h1 align="center">Harry Nguyen</h1>

<p align="center">
  <b>Applied AI systems and production infrastructure.</b><br>
  CS @ Georgia State (May 2027) &nbsp;·&nbsp; SWE @ TiMoto AI &nbsp;·&nbsp; prev. SWE Intern @ Google Chrome
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harrynguyen26/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:nguyenharry2662@gmail.com">nguyenharry2662@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://nexteasystep.com/">nexteasystep.com</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" height="24" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" height="24" />
</p>

---

I work where AI systems meet production: agents that act on real systems, retrieval that has to be accurate, and inference that has to stay up.

### TiMoto AI &nbsp;·&nbsp; Software Engineer &nbsp;·&nbsp; Sep 2025 to present

Primary engineer for backend, cloud infrastructure, and AI systems on a 3-person team.

- Built an **agentic tool-calling system** that fixes bugs from PR diffs and logs, gated by pre-deploy tests and auto-rollback. MTTR from 45 min to under 8 min across 150+ issues, 30-35% of bugs auto-resolved.
- Raised **retrieval Precision@5 from 68% to 91%** with hybrid BM25/vector search over engineering docs, and cut data-access latency 70% with an **MCP server** routing AI tools to cached read-replicas.
- Increased **LLM serving throughput 3.2x** (14 to 45 req/sec) with a **vLLM/PagedAttention** engine, cutting KV cache fragmentation from 65% to under 4% and ending OOM failures at peak hours.
- Migrated EKS to multi-AZ **ECS Fargate** under **Terraform**, cutting infra cost 44% while holding 99.9% uptime, with observability built from zero on Prometheus/Grafana.

### Google &nbsp;·&nbsp; SWE Intern, Chrome Browser &nbsp;·&nbsp; Summer 2025

- Rebuilt `chrome://privacy-sandbox-internals` with a **C++** interface exposing browser config over IPC, used by **200+ engineers**, cutting per-case debug data collection from 2-3 hours to under 5 min.
- Merged a **C++ Mojo IPC** interface into Chrome passing Protobuf-serialized state, benchmarked at sub-50ms p99 and 10K+ req/sec.
- Cut settings search p99 from **1,200ms to sub-50ms** by replacing a linear scan with a self-implemented **lock-free concurrent trie**.

### Develop for Good &nbsp;·&nbsp; SWE Intern &nbsp;·&nbsp; Summer 2024

- Moved CW3, a global Web3 community, off Airtable as primary backend engineer on a 12-person team, serving 500+ concurrent sessions.
- Cut user list load time from 3+ seconds to sub-100ms on 10,000+ records by replacing an N+1 query pattern with batched queries and PostgreSQL indexing.

---

## Projects

**[NextStep](https://nexteasystep.com/)** &nbsp;·&nbsp; Founder &nbsp;·&nbsp; `TypeScript` `React` `Expo` `Supabase` `Terraform`

AI copilot that tracks deadlines and obligations in household documents, live for ~100 users.

- Cut per-field extraction error from **37% to 9%** with deterministic schema validation and multi-pass repair, routing the remaining 7% to manual review instead of shipping bad output silently.
- Built an **LLM router** with automatic failover across Gemini, OpenAI, OpenRouter, and NVIDIA NIM: request completion from 92-94% to **99.7%**, malformed structured output reaching the client from 12-15% to under 0.3%.
- Resumable upload pipeline handling files up to 500 MiB in 8 MiB chunks that survives network drops and client restarts, under a 302-test suite.

**[Pulumi](https://github.com/pulumi/pulumi)** &nbsp;·&nbsp; Open Source Contributor &nbsp;·&nbsp; `Go` `TypeScript` `IaC`

Go CLI features and fixes for multi-cloud (AWS/Azure/GCP) provisioning, plus Raft/Paxos consensus test cases verifying correctness under concurrent operations and partial failures.

---

## Stack

| | |
|---|---|
| **AI systems** | LLM agents, tool calling, MCP, hybrid retrieval (RAG), schema-constrained generation, evals, vLLM, PagedAttention |
| **Backend & infra** | AWS, Terraform, Kubernetes, Docker, gRPC, Protocol Buffers, CI/CD, Prometheus, Grafana |
| **Languages** | C++, Python, Go, TypeScript, Java, JavaScript, SQL, Rust, Bash |
| **Data** | PostgreSQL, pgvector, Redis, MongoDB |
| **Frameworks** | Django, FastAPI, Node.js, React |
| **AI dev tools** | Claude Code, Cursor, Codex, GitHub Copilot |

---

<p align="center">
  <i>Open to New Grad SWE roles starting 2027: backend, distributed systems, ML infrastructure, SRE.</i>
</p>
