<p align="center">
  <img src="./assets/terminal.svg" width="900" alt="Terminal session: Tejashree Badve, Data and AI Engineer" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tejashree-badve/"><img src="https://img.shields.io/badge/LinkedIn-1E1B4B?style=flat-square&logo=linkedin&logoColor=F59E0B" alt="LinkedIn" /></a>
  <a href="mailto:tejashreekishorbadve@gmail.com"><img src="https://img.shields.io/badge/Email-1E1B4B?style=flat-square&logo=maildotru&logoColor=F59E0B" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=tejashreebadve&style=flat-square&color=1E1B4B&label=views" alt="Profile views" />
</p>

<br>

## About

Data and AI Engineer. Six years across banking, insurance, and healthcare. Currently working where data meets LLMs: retrieval, agent orchestration, and the schema discipline both depend on. Databricks and Snowflake for the platform, LangGraph and QLoRA for the layer above it.

| | |
|:--|:--|
| **Building** | Multi-agent, AI-native systems that hold up in production, not just in a demo |
| **Learning** | LLM evaluation frameworks, agent tracing, governance for systems on production data |
| **Ask me about** | Spark architecture, when RAG is the wrong answer, fine-tuning vs prompting |
| **Based in** | San Jose, CA |

> *Every failed agent I have debugged failed at the data layer, not the model layer.*

<br>

## Selected Work

<details>
<summary><b>Hiring Agents That Read Between the Lines</b> &nbsp;·&nbsp; <code>LangGraph</code> <code>QLoRA</code> <code>vLLM</code></summary>

<br>

A multi-agent recruiting system covering resume screening, structured extraction, and natural-language querying over candidate data.

Four open-weight models (Gemma 2, Llama 3.1, Qwen 2.5, Mistral) fine-tuned with QLoRA on 4-bit NF4 quantization and benchmarked head to head, then served through vLLM with paged attention for throughput. Retrieval runs on Qdrant with hybrid search. State moves between agents as a typed graph, so a failure traces to a node rather than to a prompt.

**99%** shortlisting accuracy &nbsp;·&nbsp; **73%** NL-to-SQL exact match &nbsp;·&nbsp; **under 4s** p95 latency

`LangGraph` `QLoRA` `vLLM` `Qdrant` `FastAPI` `Supabase`

</details>

<details>
<summary><b>Retrieval That Survives Bad Questions</b> &nbsp;·&nbsp; <code>FAISS</code> <code>CLIP</code> <code>Cross-Encoder</code></summary>

<br>

A multimodal RAG pipeline for macroeconomics QA, where the answer often lives in a chart rather than the surrounding text.

Dense FAISS vectors fused with BM25 lexical scores to catch the exact-figure queries embeddings miss, CLIP embeddings to bring chart images into the same retrieval space, and a cross-encoder reranking pass over the top-k before generation. LLaMA 3 on Groq keeps the reranking budget affordable.

Benchmark score lifted from **0.28 to 0.42**

`FAISS` `BM25` `CLIP` `Cross-Encoder` `LLaMA 3` `Groq`

</details>

<details>
<summary><b>Eight Hours to Under Three</b> &nbsp;·&nbsp; <code>PySpark</code> <code>Databricks</code> <code>Snowflake</code></summary>

<br>

Risk and liquidity reporting for a derivatives book, rebuilt around how Spark actually moves data rather than how the DAG looked on paper.

Diagnosed skew from the physical plan, repartitioned on a salted join key, replaced wide shuffles with broadcast joins where cardinality allowed, and cached the reused intermediate frames. Paired with a Snowflake migration of 70M+ records and Autosys orchestration for the nightly window.

Batch runtime cut from **8 hours to under 3**

`PySpark` `Databricks` `Delta Lake` `Snowflake` `Autosys`

</details>

<details>
<summary><b>A Lakehouse Fluent in Healthcare</b> &nbsp;·&nbsp; <code>Snowflake</code> <code>dbt</code> <code>Airflow</code></summary>

<br>

A Medallion-architecture platform for pharmacy benefit and claims data, built so clinical coding stays queryable instead of collapsing into strings.

Bronze ingestion from PBM APIs, silver standardization of 835/837 EDI alongside SNOMED CT, CPT, LOINC, and ICD-10 vocabularies, gold star schemas modeled in dbt and orchestrated by Airflow. Power BI semantic models sit on top in Direct Lake mode, with a Microsoft Fabric Copilot agent for self-serve questions.

HIPAA-aligned &nbsp;·&nbsp; oncology and RLT domain

`Snowflake` `dbt` `Airflow` `Microsoft Fabric` `Power BI`

</details>

<br>

## Stack

<details open>
<summary><b>Tools I reach for</b></summary>

<br>

**Languages** &nbsp;
<img src="https://img.shields.io/badge/Python-1E293B?style=flat-square&logo=python&logoColor=F59E0B" />
<img src="https://img.shields.io/badge/SQL-1E293B?style=flat-square&logo=postgresql&logoColor=F59E0B" />
<img src="https://img.shields.io/badge/Scala-1E293B?style=flat-square&logo=scala&logoColor=F59E0B" />
<img src="https://img.shields.io/badge/Java-1E293B?style=flat-square&logo=openjdk&logoColor=F59E0B" />

**Platform** &nbsp;
<img src="https://img.shields.io/badge/Databricks-1E293B?style=flat-square&logo=databricks&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Snowflake-1E293B?style=flat-square&logo=snowflake&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Spark-1E293B?style=flat-square&logo=apachespark&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Delta%20Lake-1E293B?style=flat-square&logo=delta&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Fabric-1E293B?style=flat-square&logo=microsoft&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/dbt-1E293B?style=flat-square&logo=dbt&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Airflow-1E293B?style=flat-square&logo=apacheairflow&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Kafka-1E293B?style=flat-square&logo=apachekafka&logoColor=38BDF8" />

**AI** &nbsp;
<img src="https://img.shields.io/badge/PyTorch-1E293B?style=flat-square&logo=pytorch&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/LangGraph-1E293B?style=flat-square&logo=langchain&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/Hugging%20Face-1E293B?style=flat-square&logo=huggingface&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/vLLM-1E293B?style=flat-square&logo=lightning&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/Qdrant-1E293B?style=flat-square&logo=qdrant&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/FAISS-1E293B?style=flat-square&logo=meta&logoColor=A78BFA" />

**Cloud** &nbsp;
<img src="https://img.shields.io/badge/Azure-1E293B?style=flat-square&logo=microsoftazure&logoColor=94A3B8" />
<img src="https://img.shields.io/badge/AWS-1E293B?style=flat-square&logo=amazonwebservices&logoColor=94A3B8" />
<img src="https://img.shields.io/badge/Docker-1E293B?style=flat-square&logo=docker&logoColor=94A3B8" />
<img src="https://img.shields.io/badge/Kubernetes-1E293B?style=flat-square&logo=kubernetes&logoColor=94A3B8" />
<img src="https://img.shields.io/badge/PostgreSQL-1E293B?style=flat-square&logo=postgresql&logoColor=94A3B8" />
<img src="https://img.shields.io/badge/FastAPI-1E293B?style=flat-square&logo=fastapi&logoColor=94A3B8" />

**Analytics** &nbsp;
<img src="https://img.shields.io/badge/Power%20BI-1E293B?style=flat-square&logo=powerbi&logoColor=F59E0B" />
<img src="https://img.shields.io/badge/Tableau-1E293B?style=flat-square&logo=tableau&logoColor=F59E0B" />

</details>

<br>

## Activity

<details>
<summary><b>GitHub stats</b></summary>

<br>

<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=tejashreebadve&show_icons=true&hide_border=true&bg_color=00000000&title_color=F59E0B&icon_color=38BDF8&text_color=64748B&include_all_commits=true" alt="GitHub stats" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejashreebadve&layout=compact&hide_border=true&bg_color=00000000&title_color=F59E0B&text_color=64748B&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tejashreebadve&bg_color=00000000&color=64748B&line=F59E0B&point=38BDF8&area=true&area_color=F59E0B&hide_border=true" alt="Contribution activity" />
</p>

</details>
