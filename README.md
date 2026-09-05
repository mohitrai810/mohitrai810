<h1 align="center">Mohit Rai</h1>
<h3 align="center">AI/ML Engineer &nbsp;·&nbsp; Backend &amp; Systems Engineer</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=2EA3F7&center=true&vCenter=true&width=650&lines=Building+production+RAG+systems+from+scratch;Retrieval+%2B+Reranking+%2B+Evaluation+pipelines;Distributed+systems+%7C+Redis+%7C+FastAPI+%7C+Docker" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohit-rai-369595224/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://leetcode.com/u/mohitrai7676760/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" /></a>
  <a href="mailto:mohitrai22222@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

### About

I build retrieval systems, LLM pipelines, and the backend infrastructure that keeps them reliable in production. My background is in systems-level engineering — C, Linux, real-time signaling — which is why I care about making AI systems that hold up outside a notebook.

- Currently building: production-oriented RAG and retrieval pipelines
- Focus areas: RAG, retrieval evaluation, cross-encoder reranking, embeddings, distributed systems
- Background: Redis/Lua atomicity, BGE embeddings, Linux-level debugging
- Open to AI/ML Engineer and Backend Engineer roles

---

### Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

### Projects

<table>
<tr>
<td width="50%" valign="top">

**Production RAG &amp; Retrieval Engine**
Built from scratch, no high-level RAG framework. Document ingestion, recursive chunking, 768-dim BGE embeddings, PGVector storage, cross-encoder reranking, LLM generation.

- Retrieval eval pipeline (Hit@K, Precision@K, Recall@K, MRR) over a 40-query benchmark
- Applied to 5G troubleshooting: correlates network logs with 3GPP specs for citation-backed debugging

`Python` `PostgreSQL` `PGVector` `BGE Embeddings` `Docker`
[View Repo](https://github.com/mohitrai810/RAG)

</td>
<td width="50%" valign="top">

**DeepDub — AI Video Dubbing Pipeline**
End-to-end multilingual dubbing: WhisperX transcription, GPT-3.5 translation, Edge TTS synthesis, Demucs source separation, FFmpeg sync.

- 40% better audio-video sync via pitch-preserving time-stretching
- 2.5x lower latency via chunk-wise TTS processing
- Deployed on Hugging Face Spaces, 30s videos processed in under 90s

`Python` `WhisperX` `Demucs` `FFmpeg` `Gradio`
[Live Demo](https://huggingface.co/spaces) · [View Repo](https://github.com/mohitrai810/DeepDub-Samples)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Distributed Rate Limiter**
Token Bucket algorithm with Redis-backed shared state for consistent limits across multiple instances.

- Rate-check logic as an atomic Lua script, eliminates race conditions under concurrent load
- Exposed as reusable FastAPI middleware with per-endpoint policies and HTTP 429 handling

`Python` `FastAPI` `Redis` `Lua` `Docker`
[View Repo](https://github.com/mohitrai810/distributed-rate-limiter)

</td>
<td width="50%" valign="top">

**RAG Log Debugging Assistant**
Retrieval-based analysis tool correlating 5G RAN logs against 3GPP specifications for faster protocol-issue debugging.

`Python` `RAG` `3GPP` `Retrieval`

</td>
</tr>
</table>

---

### Open Source

- **[langgenius/dify-official-plugins](https://github.com/langgenius/dify-official-plugins)** — fixed a `ReadTimeout` streaming issue in the Tongyi TTS plugin via a new incremental PCM streaming class
- **[explodinggradients/ragas](https://github.com/explodinggradients/ragas)** — fixed a `None`-interpolation bug in `InstanceRubrics._ascore` and a `ChrfScore` reference-handling bug
- **[modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)** — contributing a fix for missing `cancel_requested` support on high-level `Context`

---

### Experience

**Software Engineer — 5G RAN Team, Capgemini** *(Sept 2025 – Present)*
Design and implement modules for real-time signaling and data-flow control in a large-scale C codebase on Linux. Optimize memory management and resource utilization for latency-sensitive, high-throughput systems.

`C` `Linux` `GDB` `Git` `Jenkins` `Shell Scripting`

---

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mohitrai810&show_icons=true&theme=default&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohitrai810&layout=compact&theme=default&hide_border=true" />
</p>
