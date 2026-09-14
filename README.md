# Hi, I'm Harry Nguyen <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

<p align="center">
  <a href="https://www.linkedin.com/in/harrynguyen26/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:nguyenharry2662@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://nexteasystep.com/" target="_blank">
    <img src="https://img.shields.io/badge/NextStep-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="NextStep"/>
  </a>
  <a href="https://github.com/HarryNguyen2662" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

## 👨‍💻 About Me

I'm a CS undergrad at **Georgia State University** (May 2027), building **applied AI systems and production infrastructure**: agents that act on real systems, retrieval that has to be accurate, and inference that has to stay up.

## 🚀 Experience

<div align="center">

| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" width="46"/><br/>**Google**<br/>*SWE Intern*<br/>Chrome Browser | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" width="46"/><br/>**TiMoto AI**<br/>*Software Engineer*<br/>Backend · Infra · AI | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="46"/><br/>**Develop for Good**<br/>*SWE Intern*<br/>Backend |
|:---:|:---:|:---:|

</div>

### <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" width="20"/> TiMoto AI · Software Engineer · Sep 2025 to present

Primary engineer for backend, cloud infrastructure, and AI systems on a 3-person team.

- 🤖 Built an **agentic tool-calling system** that fixes bugs from PR diffs and logs, gated by pre-deploy tests and auto-rollback. MTTR from **45 min to under 8 min** across 150+ issues, **30-35%** of bugs auto-resolved.
- 🔍 Raised **retrieval Precision@5 from 68% to 91%** with hybrid BM25/vector search over engineering docs, and cut data-access latency **70%** with an **MCP server** routing AI tools to cached read-replicas.
- ⚡ Increased **LLM serving throughput 3.2x** (14 to 45 req/sec) with a **vLLM/PagedAttention** engine, cutting KV cache fragmentation from 65% to under 4%.
- ☁️ Migrated EKS to multi-AZ **ECS Fargate** under **Terraform**: infra cost down **44%**, **99.9% uptime**, observability built from zero on Prometheus/Grafana.

### <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" width="20"/> Google · SWE Intern, Chrome Browser · Summer 2025

- 🧩 Rebuilt `chrome://privacy-sandbox-internals` with a **C++** interface exposing browser config over IPC, used by **200+ engineers**, cutting per-case debug data collection from 2-3 hours to **under 5 min**.
- 🔗 Merged a **C++ Mojo IPC** interface into Chrome passing Protobuf-serialized state, benchmarked at **sub-50ms p99** and **10K+ req/sec**.
- 🌲 Cut settings search p99 from **1,200ms to sub-50ms** by replacing a linear scan with a self-implemented **lock-free concurrent trie**.

### <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="20"/> Develop for Good · SWE Intern · Summer 2024

- 🌍 Moved CW3, a global Web3 community, off Airtable as primary backend engineer on a 12-person team, serving **500+ concurrent sessions**.
- 🏎️ Cut user list load time from 3+ seconds to **sub-100ms** on 10,000+ records by replacing an N+1 query pattern with batched queries and PostgreSQL indexing.

---

## 🛠️ Projects

### [NextStep](https://nexteasystep.com/) · Founder

AI copilot that tracks deadlines and obligations in household documents, live for **~100 users**.

- Cut per-field extraction error from **37% to 9%** with deterministic schema validation and multi-pass repair, routing the remaining 7% to manual review instead of shipping bad output silently.
- Built an **LLM router** with automatic failover across Gemini, OpenAI, OpenRouter, and NVIDIA NIM: request completion **92-94% to 99.7%**, malformed structured output reaching the client from 12-15% to **under 0.3%**.
- Resumable upload pipeline handling files up to **500 MiB** in 8 MiB chunks, surviving network drops and client restarts, under a **302-test** suite.

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
</p>

### [Pulumi](https://github.com/pulumi/pulumi) · Open Source Contributor

Go CLI features and fixes for multi-cloud (AWS/Azure/GCP) provisioning, plus **Raft/Paxos consensus** test cases verifying correctness under concurrent operations and partial failures.

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/IaC-844FBA?style=flat-square&logo=pulumi&logoColor=white"/>
</p>

---

## 💻 Skills & Technologies <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="30px">

### Languages

<table>
<tr>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="42"/><br/>Python</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="42"/><br/>C++</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" width="42"/><br/>Go</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="42"/><br/>TypeScript</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="42"/><br/>Java</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="42"/><br/>JavaScript</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" width="42"/><br/>Rust</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="42"/><br/>Bash</td>
</tr>
</table>

### AI & Agent Systems

<p>
  <img src="https://img.shields.io/badge/LLM_Agents-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tool_Calling-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG_·_Hybrid_Retrieval-1A7F64?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/vLLM-FD4B4B?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PagedAttention-2E6FDB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Evals-6E40C9?style=for-the-badge"/>
</p>

### Backend & Frameworks

<table>
<tr>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="42"/><br/>Node.js</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="42"/><br/>React</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" width="42"/><br/>Django</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="42"/><br/>FastAPI</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="42"/><br/>PostgreSQL</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="42"/><br/>Redis</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="42"/><br/>MongoDB</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg" width="42"/><br/>Supabase</td>
</tr>
</table>

### Cloud, Infra & DevOps

<table>
<tr>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="42"/><br/>AWS</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="42"/><br/>Terraform</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" width="42"/><br/>Kubernetes</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="42"/><br/>Docker</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" width="42"/><br/>Actions</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg" width="42"/><br/>Prometheus</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" width="42"/><br/>Grafana</td>
<td align="center" width="80"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="42"/><br/>Linux</td>
</tr>
</table>

### AI Dev Tools

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white"/>
  <img src="https://img.shields.io/badge/Codex-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GitHub_Copilot-181717?style=for-the-badge&logo=githubcopilot&logoColor=white"/>
</p>

---

## 📊 GitHub

<p align="center">
  <img width="47%" src="https://github-readme-stats.vercel.app/api?username=HarryNguyen2662&show_icons=true&locale=en&theme=tokyonight&hide_border=true" alt="stats"/>
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=HarryNguyen2662&show_icons=true&locale=en&layout=compact&theme=tokyonight&hide_border=true" alt="top langs"/>
</p>

<p align="center">
  <i>Open to New Grad SWE roles starting 2027: backend, distributed systems, ML infrastructure, SRE.</i>
</p>
