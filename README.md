<div align="center">

<img src="./assets/hero.gif" alt="Raj Bhoyar — Backend & AI Systems Engineer" width="100%" />

<br />

<a href="https://bitwizard.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=00F5FF&center=true&vCenter=true&width=720&lines=Backend+%26+AI+Systems+Engineer;Go+streaming+pipelines+%E2%80%A2+agent+memory+research;Shipping+fixes+to+Gemini+CLI+%26+LangGraph" alt="Typing intro" />
</a>

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-bitwizard.vercel.app-0B1120?style=for-the-badge&logo=vercel&logoColor=00F5FF)](https://bitwizard.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Raj_Bhoyar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-bhoyar-b597b416a)
[![Zenodo](https://img.shields.io/badge/Preprint-Zenodo_DOI-024DAD?style=for-the-badge&logo=zenodo&logoColor=white)](https://zenodo.org/records/24387983)
[![Kaggle](https://img.shields.io/badge/Kaggle-45--Run_Ablation-20BEFF?style=for-the-badge&logo=kaggle&logoColor=black)](https://www.kaggle.com/code/rajbhoyar/neuroresearch)
[![LeetCode](https://img.shields.io/badge/LeetCode-raj729-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/raj729/)
[![Email](https://img.shields.io/badge/Email-rbhoyar729@gmail.com-10B981?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rbhoyar729@gmail.com)

</div>

<br />

### `$ whoami`

```yaml
name:      Raj Bhoyar
role:      Backend & AI Systems Engineer
builds:    [low-latency Go services, voice/LLM pipelines, agent memory]
ships_to:  [google-gemini/gemini-cli, langchain-ai/langgraph]
research:  "Bounded episodic memory for LLM agents (Zenodo DOI)"
motto:     "Measure it, then ship it."
```

<br />

### 🔧 Open-Source Contributions

* **[`google-gemini/gemini-cli#30473`](https://github.com/google-gemini/gemini-cli/pull/30473)** *(fixes [#30446](https://github.com/google-gemini/gemini-cli/issues/30446))* — Fixed context collapse in `collapseOlderFunctionResponses` by adding `calculateRetainedTurnByteSize` so evicted base64 image payloads no longer exhaust the 64 KB exempt retrieval budget and collapse earlier `read_file`/`grep` outputs. Backed by parameterized Vitest regression tests (`nested`, `sibling`, absent-response).
* **[`langchain-ai/langgraph#9802`](https://github.com/langchain-ai/langgraph/pull/9802)** *(fixes [#9791](https://github.com/langchain-ai/langgraph/issues/9791))* — Aligned `InMemoryStore.search(filter=...)` with PostgreSQL JSONB by requiring key existence (stopping missing keys from matching `None`) and guarding `$gt`/`$gte`/`$lt`/`$lte` against `ValueError`/`TypeError` crashes on heterogeneous types.
* **[`langchain-ai/langgraph#9803`](https://github.com/langchain-ai/langgraph/pull/9803)** *(fixes [#9792](https://github.com/langchain-ai/langgraph/issues/9792))* — Eliminated `bool` vs `int`/`float` filter conflation (`0`/`False`, `1`/`True`) across `InMemorySaver`, `SqliteSaver`/`AsyncSqliteSaver` (via SQLite `json_type`), and `InMemoryStore` with sync & async regression coverage.

<br />

### ⚡ Live Systems Architecture

<div align="center">
  <a href="https://github.com/bitwizard25/Shiksh_AI">
    <img src="./assets/pipeline.gif" alt="Shiksh_AI Go Streaming Voice Pipeline" width="100%" />
  </a>
</div>

* **[Shiksh_AI](https://github.com/bitwizard25/Shiksh_AI)** — Open-source Go multilingual voice tutor streaming ASR → Gemini LLM → parallel Bhashini TTS with circuit breakers, failover, and Dockerized deployment.
* **[DevPulse-AI](https://github.com/bitwizard25/DevPulse-AI)** & **[inventory_management_system](https://github.com/bitwizard25/inventory_management_system)** — Full-stack Python/TypeScript analytics and modular SaaS backend systems.

<br />

### 🧠 Independent AI Memory Research

<div align="center">
  <a href="https://zenodo.org/records/24387983">
    <img src="./assets/ablation.gif" alt="Bounded Episodic Agent Memory 45-Run Ablation" width="100%" />
  </a>
</div>

Published on **[Zenodo (DOI: 10.5281/zenodo.24387983)](https://zenodo.org/records/24387983)** with full reproducible experiments on **[Kaggle](https://www.kaggle.com/code/rajbhoyar/neuroresearch)** — demonstrating that selective write gating into 24 bounded slots achieves **`0.93 ± 0.03`** held-out 1–3 day recall vs. **`0.51`** for write-all and **`0.17`** for unlimited RAG.

<br />

### 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,py,ts,cpp,nodejs,fastapi,postgres,mongodb,redis,kafka,rabbitmq,nextjs,react,docker,aws&perline=8&theme=dark" alt="Tech Stack" />
</div>

<br />

<div align="center">

**Open to backend, infra and applied-AI roles — let's talk.**

[![Hire me](https://img.shields.io/badge/Say_hello-rbhoyar729@gmail.com-00F5FF?style=flat-square&logo=gmail&logoColor=black)](mailto:rbhoyar729@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=bitwizard25&color=0B1120&style=flat-square&label=profile+views)

</div>
