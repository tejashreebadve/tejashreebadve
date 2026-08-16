<div align="center">

<img src="./assets/hero-banner.svg" width="800" alt="Tejashree Badve, Data and AI Engineer" />

<br><br>

<img src="https://img.shields.io/badge/DATA_ENGINEER-0D1117?style=for-the-badge&labelColor=0D1117&color=22D3EE" />
<img src="https://img.shields.io/badge/AI_ENGINEER-0D1117?style=for-the-badge&labelColor=0D1117&color=C084FC" />
<img src="https://img.shields.io/badge/ANALYTICS_ENGINEER-0D1117?style=for-the-badge&labelColor=0D1117&color=56D4DD" />

<a href="https://www.linkedin.com/in/tejashree-badve/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=22D3EE" /></a>
<a href="mailto:tejashreekishorbadve@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=maildotru&logoColor=C084FC" /></a>
<img src="https://komarev.com/ghpvc/?username=tejashreebadve&style=for-the-badge&color=22D3EE&labelColor=0D1117&label=VISITORS" />

<img src="./assets/divider.svg" width="800" alt="" />

</div>

Data and AI Engineer. Six years across banking, insurance, and healthcare. Currently working where data meets LLMs: retrieval, agent orchestration, and the schema discipline both depend on. Databricks and Snowflake for the platform, LangGraph and QLoRA for the layer above it.

| | |
|:--|:--|
| **Building** | Multi-agent, AI-native systems that hold up in production, not just in a demo |
| **Learning** | LLM evaluation frameworks, agent tracing, governance for systems on production data |
| **Ask me about** | Spark architecture, when RAG is the wrong answer, fine-tuning vs prompting |
| **Based in** | San Jose, CA |

<div align="center"><img src="./assets/divider.svg" width="800" alt="" /></div>

## Selected Work

> [!IMPORTANT]
> ### Hiring Agents That Read Between the Lines
> **A multi-agent recruiting system covering resume screening, structured extraction, and natural-language querying over candidate data.**
>
> Four open-weight models (Gemma 2, Llama 3.1, Qwen 2.5, Mistral) fine-tuned with QLoRA on 4-bit NF4 quantization and benchmarked head to head, then served through vLLM with paged attention. Retrieval runs on Qdrant with hybrid search. State moves between agents as a typed graph, so a failure traces to a node rather than to a prompt.
>
> `99% shortlisting accuracy` `73% NL-to-SQL exact match` `sub-4s p95`
>
> `LangGraph` `QLoRA` `vLLM` `Qdrant` `FastAPI` `Supabase`

> [!TIP]
> ### Retrieval That Survives Bad Questions
> **A multimodal RAG pipeline for macroeconomics QA, where the answer often lives in a chart rather than the surrounding text.**
>
> Dense FAISS vectors fused with BM25 lexical scores to catch the exact-figure queries embeddings miss, CLIP embeddings to bring chart images into the same retrieval space, and a cross-encoder reranking pass over the top-k before generation. LLaMA 3 on Groq keeps the reranking budget affordable.
>
> `benchmark score 0.28 to 0.42`
>
> `FAISS` `BM25` `CLIP` `Cross-Encoder` `LLaMA 3` `Groq`

> [!NOTE]
> ### Eight Hours to Under Three
> **Risk and liquidity reporting for a derivatives book, rebuilt around how Spark actually moves data rather than how the DAG looked on paper.**
>
> Diagnosed skew from the physical plan, repartitioned on a salted join key, replaced wide shuffles with broadcast joins where cardinality allowed, and cached the reused intermediate frames. Paired with a Snowflake migration of 70M+ records and Autosys orchestration for the nightly window.
>
> `batch runtime 8h to under 3h` `70M+ records migrated`
>
> `PySpark` `Databricks` `Delta Lake` `Snowflake` `Autosys`

> [!WARNING]
> ### A Lakehouse Fluent in Healthcare
> **A Medallion-architecture platform for pharmacy benefit and claims data, built so clinical coding stays queryable instead of collapsing into strings.**
>
> Bronze ingestion from PBM APIs, silver standardization of 835/837 EDI alongside SNOMED CT, CPT, LOINC, and ICD-10 vocabularies, gold star schemas modeled in dbt and orchestrated by Airflow. Power BI semantic models sit on top in Direct Lake mode, with a Microsoft Fabric Copilot agent for self-serve questions.
>
> `HIPAA-aligned` `oncology and RLT domain`
>
> `Snowflake` `dbt` `Airflow` `Microsoft Fabric` `Power BI`

<div align="center"><img src="./assets/divider.svg" width="800" alt="" /></div>

<div align="center">

## Stack

<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=22D3EE" />
<img src="https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=22D3EE" />
<img src="https://img.shields.io/badge/Scala-0D1117?style=for-the-badge&logo=scala&logoColor=22D3EE" />
<img src="https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk&logoColor=22D3EE" />

<img src="https://img.shields.io/badge/Databricks-0D1117?style=for-the-badge&logo=databricks&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Snowflake-0D1117?style=for-the-badge&logo=snowflake&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Spark-0D1117?style=for-the-badge&logo=apachespark&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Delta_Lake-0D1117?style=for-the-badge&logo=delta&logoColor=C084FC" />
<img src="https://img.shields.io/badge/dbt-0D1117?style=for-the-badge&logo=dbt&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Airflow-0D1117?style=for-the-badge&logo=apacheairflow&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Kafka-0D1117?style=for-the-badge&logo=apachekafka&logoColor=C084FC" />
<img src="https://img.shields.io/badge/Fabric-0D1117?style=for-the-badge&logo=microsoft&logoColor=C084FC" />

<img src="https://img.shields.io/badge/PyTorch-0D1117?style=for-the-badge&logo=pytorch&logoColor=56D4DD" />
<img src="https://img.shields.io/badge/LangGraph-0D1117?style=for-the-badge&logo=langchain&logoColor=56D4DD" />
<img src="https://img.shields.io/badge/Hugging_Face-0D1117?style=for-the-badge&logo=huggingface&logoColor=56D4DD" />
<img src="https://img.shields.io/badge/vLLM-0D1117?style=for-the-badge&logo=lightning&logoColor=56D4DD" />
<img src="https://img.shields.io/badge/Qdrant-0D1117?style=for-the-badge&logo=qdrant&logoColor=56D4DD" />
<img src="https://img.shields.io/badge/FAISS-0D1117?style=for-the-badge&logo=meta&logoColor=56D4DD" />

<img src="https://img.shields.io/badge/Azure-0D1117?style=for-the-badge&logo=microsoftazure&logoColor=8B949E" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonwebservices&logoColor=8B949E" />
<img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=8B949E" />
<img src="https://img.shields.io/badge/Kubernetes-0D1117?style=for-the-badge&logo=kubernetes&logoColor=8B949E" />
<img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=8B949E" />
<img src="https://img.shields.io/badge/Power_BI-0D1117?style=for-the-badge&logo=powerbi&logoColor=8B949E" />

<img src="./assets/divider.svg" width="800" alt="" />

## Analytics

<img src="https://github-readme-activity-graph.vercel.app/graph?username=tejashreebadve&theme=react-dark&bg_color=0d1117&color=58a6ff&line=22d3ee&point=bc8cff&area=true&hide_border=true" width="800" alt="Activity graph" />

<br>

<img src="https://ghchart.rshah.org/22d3ee/tejashreebadve" width="800" alt="Contribution grid" />

<br><br>

<table border="0">
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=tejashreebadve&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0d1117&title_color=c084fc&icon_color=22d3ee&text_color=8b949e&include_all_commits=true" alt="GitHub stats" />
</td>
<td>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejashreebadve&layout=compact&hide_border=true&theme=tokyonight&bg_color=0d1117&title_color=c084fc&text_color=8b949e&langs_count=8" alt="Top languages" />
</td>
</tr>
</table>

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=tejashreebadve&theme=tokyonight&hide_border=true&background=0d1117&ring=c084fc&fire=22d3ee&currStreakLabel=c084fc" alt="Streak stats" />

<img src="./assets/divider.svg" width="800" alt="" />

</div>

<!-- START_SECTION:activity -->
<!-- END_SECTION:activity -->

<!-- START_SECTION:content -->
<!-- END_SECTION:content -->

<div align="center">
<sub><code>SYSTEM.READY // tejashreebadve</code></sub>
</div>
