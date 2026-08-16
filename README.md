<h1 align="center">Hello, I'm Tejashree</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=6D28D9&fontSize=40&height=80&width=700&text=Data%20and%20AI%20Engineer" alt="Data and AI Engineer" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1400&color=6D28D9&center=true&vCenter=true&width=700&height=40&lines=Pipelines+that+scale%2C+models+that+ship;Lakehouses+and+the+agents+that+query+them;Medallion+by+day%2C+multi-agent+by+night" alt="Typing headlines" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tejashree-badve/"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:tejashreekishorbadve@gmail.com"><img src="https://img.shields.io/badge/Email-0891B2?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=tejashreebadve&style=flat-square&color=6D28D9&label=Profile+Views" alt="Profile views" />
</p>

---

## 🧠 &nbsp;About Me

Data and AI Engineer. Six years across banking, insurance, and healthcare. Currently working where data meets LLMs: retrieval, agent orchestration, and the schema discipline both depend on. Databricks and Snowflake for the platform, LangGraph and QLoRA for the layer above it.

```yaml
currently_working_on: Multi-agent, AI-native systems that hold up in production, not just in a demo
currently_learning:   LLM evaluation frameworks, agent tracing, governance for systems on production data
ask_me_about:         Spark architecture, when RAG is the wrong answer, fine-tuning vs prompting
based_in:             San Jose, CA
```

> Every failed agent I have debugged failed at the data layer, not the model layer.

---

## 🧩 &nbsp;Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 &nbsp;Hiring Agents That Read Between the Lines

A LangGraph multi-agent system for end-to-end recruiting: resume screening, structured extraction, and natural-language querying over candidate data.

Four open-weight models (Gemma 2, Llama 3.1, Qwen 2.5, Mistral) fine-tuned with QLoRA on 4-bit NF4 quantization, benchmarked head to head, then served through vLLM with paged attention for throughput. Retrieval runs on Qdrant with hybrid search; state moves between agents as a typed graph so failures are traceable to a node instead of a prompt.

`LangGraph` `QLoRA` `vLLM` `Qdrant` `FastAPI` `Supabase`

**99%** shortlisting accuracy &nbsp;·&nbsp; **73%** NL-to-SQL exact match &nbsp;·&nbsp; **<4s** p95 latency

</td>
<td width="50%" valign="top">

### 🔍 &nbsp;Retrieval That Survives Bad Questions

A multimodal RAG pipeline for macroeconomics QA, where the answer often lives in a chart rather than the surrounding text.

Dense FAISS vectors fused with BM25 lexical scores to catch the exact-figure queries embeddings miss, CLIP embeddings to bring chart images into the same retrieval space, and a cross-encoder reranking pass over the top-k before generation. Inference served by LLaMA 3 on Groq to keep the reranking budget affordable.

`FAISS` `BM25` `CLIP` `Cross-Encoder` `LLaMA 3` `Groq`

Benchmark score lifted **0.28 → 0.42**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ &nbsp;Eight Hours to Under Three

Risk and liquidity reporting for a derivatives book, rebuilt around how Spark actually moves data rather than how the DAG looked on paper.

Diagnosed skew from the physical plan, repartitioned on a salted join key, replaced wide shuffles with broadcast joins where cardinality allowed, and cached the reused intermediate frames. Paired with a Snowflake migration of 70M+ records and Autosys orchestration for the nightly window.

`PySpark` `Databricks` `Delta Lake` `Snowflake` `Autosys`

Batch runtime **8h → <3h**

</td>
<td width="50%" valign="top">

### 🏥 &nbsp;A Lakehouse Fluent in Healthcare

A Medallion-architecture platform on Snowflake for pharmacy benefit and claims data, built so clinical coding stays queryable instead of collapsing into strings.

Bronze ingestion from PBM APIs, silver standardization of 835/837 EDI plus SNOMED CT, CPT, LOINC, and ICD-10 vocabularies, gold star schemas modeled in dbt and orchestrated by Airflow. Power BI semantic models sit on top in Direct Lake mode, with a Microsoft Fabric Copilot agent for self-serve questions.

`Snowflake` `dbt` `Airflow` `Microsoft Fabric` `Power BI`

HIPAA-aligned &nbsp;·&nbsp; oncology and RLT domain

</td>
</tr>
</table>

---

## 🛠️ &nbsp;Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" />
</p>

**Data Platforms and Processing**

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
</p>

**AI and ML**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/vLLM-6D28D9?style=flat-square&logo=lightning&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
</p>

**Cloud and Infrastructure**

<p>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
</p>

**Analytics and BI**

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" />
</p>

---

## 📊 &nbsp;GitHub Activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=tejashreebadve&show_icons=true&hide_border=true&bg_color=00000000&title_color=6D28D9&icon_color=0891B2&text_color=64748B&include_all_commits=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejashreebadve&layout=compact&hide_border=true&bg_color=00000000&title_color=6D28D9&text_color=64748B&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tejashreebadve&bg_color=00000000&color=64748B&line=6D28D9&point=0891B2&area=true&area_color=6D28D9&hide_border=true" alt="Contribution activity" />
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=6D28D9&height=4&section=footer" alt="footer" />
</p>
