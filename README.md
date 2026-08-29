# 🎯 Designing Evidence - Traceability Metrics for Agentic Literature Synthesis Pipelines

Welcome to the ultimate resource hub for researchers and practitioners dedicated to advancing **evidence-traceability metrics** in **agentic literature synthesis pipelines**. This curated collection brings together cutting-edge papers, datasets, tools, implementations, and tutorials to foster transparency, reproducibility, and accountability in automated literature synthesis.

---
## 🚀 What’s Inside
- 🔎[Overview](#-overview)
- 📄[AI-Assisted Research Paper](#ai-assisted-research-paper)
- 📚 [Curated Research Papers](#-curated-research-papers)
  - [Survey and Review](#-survey-papers)
  - [Foundational Papers](#-foundational-papers)
  - [Recent Research](#-recent-research-papers)
- 📊[Datasets](#-datasets)
- 🛠️[Tools and Libraries](#tools-and-libraries)
- 💻[GitHub Implementations](#-github-implementations)
- 🎓[Tutorials & Guides](#-tutorials--guides)
- 🔍[Citation Integrity Audit](#-citation-integrity-audit)
- 📜[License](#-license)
---

## 🔬 Overview

**Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines** focuses on developing systematic methods for measuring how reliably AI agents retrieve, interpret, synthesize, and cite scientific evidence. As large language models and agentic systems increasingly support literature reviews and research discovery, evaluating the quality of the final generated text alone is insufficient. A trustworthy literature-synthesis pipeline must also make the underlying evidence chain transparent, verifiable, and reproducible.

Evidence traceability refers to the ability to follow a generated claim back through its supporting evidence, source document, retrieval process, citation, and relevant agent actions. This research area therefore connects **Retrieval-Augmented Generation (RAG), scientific information retrieval, citation evaluation, factuality assessment, provenance tracking, agent observability, and reproducible research**.

The central objective is to develop **quantitative and interpretable metrics** that evaluate different stages of an agentic research workflow. Potential dimensions include retrieval coverage, evidence relevance, claim–evidence alignment, citation correctness, evidence completeness, factual faithfulness, provenance completeness, hallucination rate, and workflow traceability.

A multidimensional evaluation framework can help researchers identify where an agentic literature-synthesis system succeeds or fails—from finding appropriate scientific sources to producing claims that are accurately supported by those sources. Ultimately, evidence-traceability metrics can contribute to the development of **transparent, auditable, reproducible, and trustworthy AI-assisted research systems**.

> **Research principle:**  
> **Question → Retrieval → Evidence → Claim → Citation → Provenance → Verification → Trust**
---
## 📃AI-Assisted Research Paper

This repository includes the AI-assisted research paper prepared for the research topic:

### ⓘ Paper Information

- **Topic:** Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines
- **Purpose:** Study the relationship between prompt variations and the stability of LLM-generated research conclusions.
- **AI Tool Used:** ChatGPT/Claude
- **Research Type:** Literature-based research
- **Paper Format:** PDF

**[View the AI-Assisted Research Paper](Paper/AI_Assisted_Research_Paper.pdf)**

---


## 📚 Curated Research Papers

A curated selection of scholarly works supporting the research theme **“Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines.”**

The papers are organized into three categories:

- 📖 **Survey Papers** — synthesize existing research and establish the broader technical landscape.
- 🏛️ **Foundational Papers** — introduce core methods, benchmarks, evaluation paradigms, or provenance concepts.
- 🚀 **Recent Research Papers** — address contemporary RAG, citation evaluation, agentic research, and scientific literature synthesis.

---

## 📖 Survey Papers

1. Retrieval-Augmented Generation for Large Language Models: A Survey
   [arXiv:2312.10997](https://arxiv.org/abs/2312.10997)
 
2. TRUE: Re-evaluating Factual Consistency Evaluation
   [ACL Anthology](https://aclanthology.org/2022.naacl-main.287/)
---
## 🏛️ Foundational Papers
3. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks
   [arXiv:2005.11401](https://arxiv.org/abs/2005.11401)

4. Provenance in Collection-Oriented Scientific Workflows
   [10.1002/cpe.1226](https://doi.org/10.1002/cpe.1226)

5. KILT: A Benchmark for Knowledge Intensive Language Tasks
   [ACL Anthology](https://aclanthology.org/2021.naacl-main.200/)

6. Evidence Inference 2.0: More Data, Better Models
   [ACL Anthology](https://aclanthology.org/2020.bionlp-1.13/)

7. Enabling Large Language Models to Generate Text with Citations
   [ACL Anthology](https://aclanthology.org/2023.emnlp-main.398/)

8. FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation
   [ACL Anthology](https://aclanthology.org/2023.emnlp-main.741/)

9. PubMedQA: A Dataset for Biomedical Research Question Answering
   [ACL Anthology](https://aclanthology.org/D19-1259/)

10. RAGAs: Automated Evaluation of Retrieval Augmented Generation
    [ACL Anthology](https://aclanthology.org/2024.eacl-demo.16/)

11. ARES: An Automated Evaluation Framework for Retrieval-Augmented Generation Systems
    [ACL Anthology](https://aclanthology.org/2024.naacl-long.20/)
---
## 🚀 Recent Research Papers
12. Synthesizing Scientific Literature with Retrieval-Augmented Language Models
    [10.1038/s41586-025-10072-4](https://doi.org/10.1038/s41586-025-10072-4)

13. DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents
    [arXiv:2506.11763](https://arxiv.org/abs/2506.11763)

14. Agent Laboratory: Using LLM Agents as Research Assistants
    [arXiv:2501.04227](https://arxiv.org/abs/2501.04227)
    
15. Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection
    [arXiv:2310.11511](https://arxiv.org/abs/2310.11511)

16. RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models
    [ACL Anthology](https://aclanthology.org/2024.acl-long.585/)

17. Towards Fine-Grained Citation Evaluation in Generated Text: A Comparative Analysis of Faithfulness Metrics
    [ACL Anthology](https://aclanthology.org/2024.inlg-main.35/)

18. Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models
    [ACL Anthology](https://aclanthology.org/2024.naacl-long.347/)

19. PaperQA: Retrieval-Augmented Generative Agent for Scientific Research
    [arXiv:2312.07559](https://arxiv.org/abs/2312.07559)

20. FAIR Data Pipeline: Provenance-Driven Data Management for Traceable Scientific Workflows
    [10.1098/rsta.2021.0300](https://doi.org/10.1098/rsta.2021.0300)
---

## 📊 Category Summary

| Category | Number of Papers | Primary Contribution |
|---|---:|---|
| 📖 **Survey Papers** | 2 | RAG and factual-consistency landscape |
| 🏛️ **Foundational Papers** | 9 | RAG, provenance, evidence, citation and evaluation foundations |
| 🚀 **Recent Research Papers** | 9 | Agentic research, citation evaluation, hallucination and scientific synthesis |
| **Total** | **20** | Multidimensional evidence-traceability research base |

  See the complete metadata, links, and relevance notes in **[references/references.md](references/references.md)**.
---

## 📊 Datasets

The assignment requires at least three relevant datasets/benchmarks. This repository includes five.

**[Open the complete dataset/benchmark list](datasets/datasets.md)**

---

## 🛠️ Tools & Libraries

A curated collection of tools and libraries supporting **scholarly retrieval, scientific document processing, Retrieval-Augmented Generation (RAG), agent orchestration, evidence evaluation, citation verification, provenance tracking, and experiment monitoring**.

---

### 📚 1. Scholarly Literature Retrieval

| Tool / Library | Purpose | Application to Evidence Traceability |
|---|---|---|
| 🔎 [OpenAlex](https://openalex.org/) | Scholarly metadata and literature discovery | Source identification, citation networks, bibliographic metadata |
| 🔎 [Semantic Scholar](https://www.semanticscholar.org/) | Academic search and citation discovery | Literature retrieval and citation relationship analysis |
| 🧾 [Crossref](https://www.crossref.org/) | DOI and publication metadata | Citation and DOI verification |
| 🧬 [PubMed](https://pubmed.ncbi.nlm.nih.gov/) | Biomedical literature retrieval | Scientific evidence discovery |
| 📚 [Europe PMC](https://europepmc.org/) | Biomedical literature and full-text search | Evidence retrieval and source identification |
| 📄 [arXiv](https://arxiv.org/) | Scientific preprints | Retrieval of recent research literature |

---

### 📄 2. Scientific Document Processing

| Tool / Library | Purpose | Traceability Application |
|---|---|---|
| 📑 [GROBID](https://github.com/kermitt2/grobid) | Scientific PDF parsing | Metadata, citations, sections and evidence extraction |
| 📄 [PyMuPDF](https://pymupdf.readthedocs.io/) | PDF text and metadata extraction | Page- and passage-level evidence localization |
| 🧩 [Unstructured](https://github.com/Unstructured-IO/unstructured) | Document preprocessing | PDF/HTML processing for RAG |
| 📦 [Apache Tika](https://tika.apache.org/) | Document content extraction | Large-scale heterogeneous document processing |

> **Why GROBID?**  
> GROBID is specifically designed for extracting and restructuring scientific publications into machine-readable TEI/XML. It can extract bibliographic metadata, references, citation contexts, full-text structures, and PDF coordinates, making it particularly useful for evidence localization and citation traceability. Ggrobid.readthedocs.io+1


---

### 🧠 3. RAG & Knowledge Pipelines

| Tool / Library | Purpose | Evidence-Traceability Application |
|---|---|---|
| 🦙 [LlamaIndex](https://www.llamaindex.ai/) | Data ingestion, indexing and RAG | Scientific literature indexing and evidence retrieval |
| 🦜 [LangChain](https://www.langchain.com/) | LLM and RAG applications | Retrieval, tools, agents and synthesis |
| 🌾 [Haystack](https://haystack.deepset.ai/) | Search and RAG pipelines | Evidence retrieval and grounded generation |
| 🧮 [FAISS](https://github.com/facebookresearch/faiss) | Vector similarity search | Passage-level evidence retrieval |
| 🗃️ [Qdrant](https://qdrant.tech/) | Vector database | Metadata-aware evidence storage and retrieval |
| 🗄️ [Weaviate](https://weaviate.io/) | Vector database | Semantic search and retrieval |

---

### 🤖 4. Agentic Research & Workflow Orchestration

| Tool / Library | Purpose | Research Application |
|---|---|---|
| 🔗 [LangGraph](https://www.langchain.com/langgraph) | Stateful agent workflows | Multi-step literature research agents |
| 🤝 [AutoGen](https://github.com/microsoft/autogen) | Multi-agent orchestration | Collaborative research agents |
| 👥 [CrewAI](https://github.com/crewAIInc/crewAI) | Role-based agents | Research task decomposition |
| 🧪 [DSPy](https://github.com/stanfordnlp/dspy) | Programmatic LLM pipelines | Optimizable research workflows |

---

### 📊 5. Evidence & RAG Evaluation

| Tool / Library | Main Focus | Potential Metric |
|---|---|---|
| 📏 [Ragas](https://docs.ragas.io/) | RAG and agent evaluation | Faithfulness, relevance, retrieval quality |
| 🧪 [DeepEval](https://github.com/confident-ai/deepeval) | LLM/RAG evaluation | Faithfulness, hallucination, relevance |
| 🔬 [ARES](https://github.com/stanford-futuredata/ARES) | RAG evaluation | Context relevance, faithfulness, answer relevance |
| 📌 [FActScore](https://github.com/shmsw25/FActScore) | Atomic factuality | Claim-level factual precision |
| ✅ [TRUE](https://github.com/google/TRUE) | Factual consistency | Source-grounded factuality |

---

### 🧭 6. Tracing & Observability

| Tool / Library | Purpose | Evidence-Traceability Use |
|---|---|---|
| 🔥 [Arize Phoenix](https://phoenix.arize.com/) | LLM observability | Agent, retrieval and tool-call tracing |
| 📡 [OpenTelemetry](https://opentelemetry.io/) | Distributed tracing | Standardized workflow execution traces |
| 🔬 [OpenInference](https://github.com/Arize-ai/openinference) | AI/LLM instrumentation | Semantic tracing of LLM applications |
| 🧵 [LangSmith](https://smith.langchain.com/) | LLM observability | Agent trajectory and retrieval inspection |

---

### 🧪 7. Experiment Tracking & Reproducibility

| Tool / Library | Purpose | Research Application |
|---|---|---|
| 📈 [MLflow](https://mlflow.org/) | Experiment tracking | Compare models, prompts and metrics |
| 📊 [Weights & Biases](https://wandb.ai/) | Experiment management | Track evaluation experiments |
| 🗂️ [DVC](https://dvc.org/) | Dataset/version control | Reproducible research datasets |
| 🌳 [Git](https://git-scm.com/) | Version control | Version code, metrics and configurations |

---

### 🔗 8. Provenance & Citation Infrastructure

| Standard / Tool | Purpose | Application |
|---|---|---|
| 🧾 [W3C PROV](https://www.w3.org/TR/prov-overview/) | Provenance modelling | Represent evidence lineage |
| 🔗 [Crossref](https://www.crossref.org/) | Persistent scholarly metadata | DOI and citation verification |
| 🆔 [DataCite](https://datacite.org/) | Persistent identifiers | Dataset and research-object identification |
| 👤 [ORCID](https://orcid.org/) | Researcher identification | Author disambiguation |

---

## 🎯 Tool-to-Metric Mapping

The following mapping connects tools with the major dimensions of an evidence-traceability framework.

| Evidence-Traceability Dimension | Recommended Tools |
|---|---|
| 🔎 **Retrieval Coverage** | OpenAlex, Semantic Scholar, Ragas |
| 🎯 **Retrieval Precision** | Ragas, DeepEval |
| 📚 **Evidence Relevance** | Ragas, DeepEval |
| 📍 **Evidence Localization** | GROBID, PyMuPDF |
| 🔗 **Claim–Evidence Alignment** | Ragas, DeepEval, custom evaluators |
| 🧾 **Citation Correctness** | Crossref, GROBID |
| 📑 **Citation Completeness** | Crossref, OpenAlex |
| 🧠 **Faithfulness** | Ragas, DeepEval |
| 🚨 **Hallucination Rate** | DeepEval, FActScore |
| 🤖 **Agent Trajectory** | LangGraph, Phoenix, OpenTelemetry |
| 🧭 **Provenance Completeness** | W3C PROV, OpenTelemetry |
| 📊 **Experiment Reproducibility** | MLflow, DVC, Git |
| 🔬 **Workflow Traceability** | LangGraph, Phoenix |
| ✅ **Overall Evidence Traceability** | Combined evaluation framework |

---

## 🏗️ Recommended Research Stack

For a practical prototype of an **agentic literature synthesis pipeline**, the following stack is recommended:

| Pipeline Layer | Recommended Tool |
|---|---|
| 🔎 Literature Discovery | **OpenAlex + Semantic Scholar** |
| 🧾 Metadata Verification | **Crossref** |
| 📄 Scientific PDF Processing | **GROBID + PyMuPDF** |
| 🧮 Vector Retrieval | **Qdrant / FAISS** |
| 📚 RAG | **LlamaIndex / LangChain** |
| 🤖 Agent Orchestration | **LangGraph** |
| 🧭 Trace Collection | **OpenTelemetry + OpenInference** |
| 🔬 Observability | **Phoenix** |
| 📏 RAG Evaluation | **Ragas** |
| 🧪 LLM Evaluation | **DeepEval** |
| 📈 Experiment Tracking | **MLflow** |
| 🧾 Provenance | **W3C PROV** |

---

## 💻 GitHub Implementations
The implementations section considers documentation, source availability, maintenance/activity, reproducibility, licensing, and connection to research—not popularity alone.

**[Open the complete implementation list](implementations/github-repositories.md)**

---

## 🎓 Tutorials & Guides

- [How to Evaluate Traceability Metrics](tutorials/evaluate_metrics.md)
- [Building an Agentic Literature Pipeline](tutorials/build_pipeline.md)

---

## 🔍 Citation Integrity Audit

A citation/resource audit was prepared to verify the references appearing in the supplied paper and to document the verification rules used for the curated collection.

**[View the Citation Integrity Audit PDF](citation-audit/Citation_Integrity_Audit.pdf)** ·

---

## 📜 License

This repository is licensed under the MIT License.  
See the **[LICENSE](LICENSE)** file for details.

---
