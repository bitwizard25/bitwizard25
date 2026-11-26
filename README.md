<div align="center">

<img src="./assets/header.svg" alt="Raj Bhoyar — Backend & AI Systems Engineer" width="100%" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-bitwizard.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=00F5FF)](https://bitwizard.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Raj_Bhoyar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-bhoyar-b597b416a)
[![Zenodo](https://img.shields.io/badge/Research_Preprint-Zenodo_DOI-024DAD?style=for-the-badge&logo=zenodo&logoColor=white)](https://zenodo.org/records/24387983)
[![LeetCode](https://img.shields.io/badge/LeetCode-raj729-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/raj729/)
[![Medium](https://img.shields.io/badge/Medium-@rbhoyar729-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rbhoyar729)
[![Email](https://img.shields.io/badge/Email-rbhoyar729@gmail.com-10B981?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rbhoyar729@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=bitwizard25&label=PROFILE+VIEWS&color=00f5ff&style=for-the-badge" alt="Profile Views" />

</div>

---

## `$ cat /etc/raj.conf`

```yaml
name       : Raj Bhoyar
location   : India
role       : Backend & AI Systems Engineer
languages  : Go · Python · TypeScript · C++
focus      : AI agent runtimes · persistence & retrieval parity · Go microservices · streaming pipelines
research   : Bounded episodic agent memory & selective write gating (Zenodo DOI: 10.5281/zenodo.24387983)
motto      : "Ship clean, testable systems that hold up past the demo."
```

---

## `$ git log --author="bitwizard25" --oss`

Recent open-source engineering contributions focused on AI agent context management and cross-backend persistence parity:

| Repository | Pull Request | Problem Solved | Verification |
| :--- | :--- | :--- | :--- |
| **[google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)** | **[#30473](https://github.com/google-gemini/gemini-cli/pull/30473)** *(fixes [#30446](https://github.com/google-gemini/gemini-cli/issues/30446))* | Prevented evicted base64 image payloads from exhausting the 64 KB exempt retrieval budget and collapsing earlier `read_file`/`grep` context | Parameterized Vitest regression suite (`nested`, `sibling`, absent-response) |
| **[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)** | **[#9802](https://github.com/langchain-ai/langgraph/pull/9802)** *(fixes [#9791](https://github.com/langchain-ai/langgraph/issues/9791))* | Separated missing keys from explicit `None` in `InMemoryStore` filters and guarded `$gt`/`$gte`/`$lt`/`$lte` against heterogeneous type crashes | Pytest regression suite (`119/119` passing) + `ruff` |
| **[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)** | **[#9803](https://github.com/langchain-ai/langgraph/pull/9803)** *(fixes [#9792](https://github.com/langchain-ai/langgraph/issues/9792))* | Fixed `bool` vs `int`/`float` filter conflation across `InMemorySaver`, `SqliteSaver`/`AsyncSqliteSaver` (via SQLite `json_type`), and `InMemoryStore` | Sync & async Pytest suites across checkpoint & SQLite (`150/150` passing) |

---

## `$ cat research/preprint.md`

### [Selective Write Gating vs. Neuromodulation in Bounded Episodic Agent Memory](https://zenodo.org/records/24387983)
> **Zenodo Preprint** · DOI [`10.5281/zenodo.24387983`](https://zenodo.org/records/24387983) · [45-Run Kaggle Ablation Notebook](https://www.kaggle.com/code/rajbhoyar/neuroresearch)

* Controlled **45-run ablation** (9 memory variants × 5 seeds, 4,000 simulated days/run, 24 bounded memory slots) evaluating what actually drives multi-day episodic recall in LLM agents.
* Demonstrated that **selective write gating** into 24 bounded slots achieves **`0.93 ± 0.03`** held-out 1–3 day recall vs. **`0.51`** for write-all and **`0.17`** for unlimited RAG retrieval.

---

## `$ ls -la ~/featured-systems`

### 1. [Shiksh_AI](https://github.com/bitwizard25/Shiksh_AI) — Multilingual Voice AI Tutor *(Go · Streaming · Docker)*
Open-source Go-based voice tutor for Indian languages engineered for low-latency streaming and fault tolerance.

<details>
<summary><b>Inspect streaming pipeline architecture</b></summary>

```text
[User Audio] ──▶ [ASR] ──▶ [Gemini LLM Stream] ──▶ [Parallel Bhashini TTS] ──▶ [Audio Stream]
                                  │                          │
                          Circuit Breakers            Failover & Retries
```

</details>

### 2. [DevPulse-AI](https://github.com/bitwizard25/DevPulse-AI) & [inventory_management_system](https://github.com/bitwizard25/inventory_management_system)
Full-stack developer analytics and production SaaS backend/UI systems built with **Python**, **TypeScript**, **Node.js**, **PostgreSQL**, and **Next.js**.

---

## `$ env | grep STACK`

<div align="center">

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend, Data & Messaging**

![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_&_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**AI, Frontend & Cloud**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

</div>

---

## `$ top --github-telemetry`

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=bitwizard25&show_icons=true&bg_color=0D1424&title_color=00F5FF&icon_color=10B981&text_color=E2E8F0&border_color=1E293B&hide_border=false" alt="GitHub Stats" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bitwizard25&layout=compact&bg_color=0D1424&title_color=00F5FF&text_color=E2E8F0&border_color=1E293B&hide_border=false" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=bitwizard25&background=0D1424&border=1E293B&ring=00F5FF&fire=10B981&currStreakLabel=00F5FF&sideLabels=E2E8F0&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=94A3B8" alt="GitHub Streak" />

</div>

---

<div align="center">
  <code>raj@bitwizard25:~$ echo "Always down to talk distributed systems, agent memory, or open source."</code>
</div>
