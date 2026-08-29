# 🛠️ Tools & Libraries

> **A curated collection of tools, libraries, frameworks, APIs, and standards for designing, implementing, tracing, and evaluating evidence-traceable agentic literature synthesis pipelines.**

[![Research](https://img.shields.io/badge/Research-Evidence%20Traceability-blue)](#)
[![RAG](https://img.shields.io/badge/RAG-Retrieval--Augmented%20Generation-green)](#)
[![Agents](https://img.shields.io/badge/AI-Agentic%20Systems-purple)](#)
[![Evaluation](https://img.shields.io/badge/LLM-Evaluation-orange)](#)
[![Provenance](https://img.shields.io/badge/Provenance-Tracking-red)](#)

This collection focuses on the technical infrastructure required to build **auditable, evidence-grounded, and reproducible agentic literature synthesis systems**.

---

## 📑 Contents

- [🔎 Retrieval & Literature Search](#-retrieval--literature-search)
- [📚 RAG & Knowledge Pipelines](#-rag--knowledge-pipelines)
- [🤖 Agentic Orchestration](#-agentic-orchestration)
- [🔗 Evidence & Citation Evaluation](#-evidence--citation-evaluation)
- [🔬 LLM Evaluation Frameworks](#-llm-evaluation-frameworks)
- [🧭 Tracing & Observability](#-tracing--observability)
- [📊 Experiment Tracking & Evaluation](#-experiment-tracking--evaluation)
- [🗂️ Document Processing](#-document-processing)
- [🧮 Vector Databases & Retrieval Infrastructure](#-vector-databases--retrieval-infrastructure)
- [🧾 Provenance & Traceability Standards](#-provenance--traceability-standards)
- [🎯 Recommended Research Stack](#-recommended-research-stack)
- [📊 Tool-to-Metric Mapping](#-tool-to-metric-mapping)
- [🔬 Research Use Cases](#-research-use-cases)
- [🧠 Proposed Metric Layers](#-proposed-metric-layers)
- [⭐ Recommended Core Toolkit](#-recommended-core-toolkit)
- [🔬 End-to-End Research Architecture](#-end-to-end-research-architecture)
- [📚 Selection Principles](#-selection-principles)
- [🔬 Research Objective](#-research-objective)

---

# 📖 Overview

Evidence-traceable literature synthesis requires more than retrieving documents and generating text.

A robust research pipeline should preserve the relationship between:

```text
Research Question
       ↓
Search Query
       ↓
Retrieved Paper
       ↓
Evidence Passage
       ↓
Generated Claim
       ↓
Citation
       ↓
Verification
       ↓
Provenance


The tools in this document support different stages of this process, from scholarly discovery and document processing to agent orchestration, tracing, evaluation, and provenance management.

🔎 Retrieval & Literature Search

Tools in this category support discovery and retrieval of scholarly literature.

Tool	Type	Primary Use	Traceability
Semantic Scholar	Scholarly API	Academic literature discovery	⭐⭐⭐⭐⭐
OpenAlex	Scholarly API	Open scholarly metadata	⭐⭐⭐⭐⭐
Crossref	Metadata API	DOI & bibliographic metadata	⭐⭐⭐⭐⭐
PubMed / NCBI	Scholarly API	Biomedical literature	⭐⭐⭐⭐⭐
Europe PMC	Scholarly API	Biomedical literature & full text	⭐⭐⭐⭐
arXiv API	Scholarly API	Scientific preprints	⭐⭐⭐⭐
🔗 Semantic Scholar

Semantic Scholar provides scholarly search and metadata services useful for literature discovery and citation-network analysis.

Key Applications
 Literature discovery
 Citation graph construction
 Related-paper retrieval
 Author metadata
 Research-source identification
Resources
🌐 Semantic Scholar
🔌 Semantic Scholar API
🔗 OpenAlex

OpenAlex provides an open catalog of scholarly works, authors, institutions, concepts, and citations.

Key Applications
 Literature corpus construction
 Citation-network analysis
 Bibliographic enrichment
 Research trend analysis
 Source metadata verification
Resources
🌐 OpenAlex
🔌 OpenAlex API
🔗 Crossref

Crossref is particularly useful for persistent identifiers and bibliographic metadata verification.

Key Applications
DOI verification
Reference normalization
Publication identification
Citation integrity auditing
Bibliographic metadata enrichment
Resources
🌐 Crossref
🔌 Crossref REST API
🔗 PubMed / NCBI

PubMed provides access to biomedical and life-science literature.

Key Applications
Biomedical literature retrieval
Evidence discovery
PMID verification
Citation metadata
Clinical literature synthesis
Resources
🌐 PubMed
🔌 NCBI E-utilities
📚 RAG & Knowledge Pipelines

Retrieval-Augmented Generation frameworks provide infrastructure for connecting language models to external scientific knowledge.

Tool	Primary Function	Agentic RAG	Evaluation	Traceability
LangChain	LLM application framework	✅	◐	⭐⭐⭐⭐
LlamaIndex	Data & RAG framework	✅	◐	⭐⭐⭐⭐⭐
Haystack	Search/RAG framework	✅	◐	⭐⭐⭐⭐
RAGAS	RAG evaluation	—	✅	⭐⭐⭐⭐⭐
DeepEval	LLM/RAG evaluation	✅	✅	⭐⭐⭐⭐⭐
🦜 LangChain

LangChain provides components for retrieval, tool use, agents, document processing, and RAG architectures.

Applications
Agentic literature search
Retrieval pipelines
Tool calling
Multi-step research workflows
Citation-aware generation
Agent trajectory logging
Resources
📚 Documentation
💻 GitHub Repository
🦙 LlamaIndex

LlamaIndex is designed for connecting LLM applications with external data sources.

Applications
Scientific-document indexing
RAG
Agentic retrieval
Document parsing
Citation-aware synthesis
Knowledge-base construction
Resources
📚 Documentation
💻 GitHub Repository
🧪 Haystack

Haystack is an open-source framework for search, RAG, question answering, and agentic pipelines.

Applications
Literature retrieval
Semantic search
RAG
Document processing
Agent pipelines
Evaluation workflows
Resources
📚 Documentation
💻 GitHub Repository
🤖 Agentic Orchestration

Agentic literature synthesis requires explicit representation of actions, tool calls, retrieval decisions, intermediate evidence, and verification steps.

Framework	Primary Strength	Traceability Potential
LangGraph	Stateful agent workflows	⭐⭐⭐⭐⭐
AutoGen	Multi-agent systems	⭐⭐⭐⭐
CrewAI	Role-based agents	⭐⭐⭐⭐
DSPy	Programmatic LLM pipelines	⭐⭐⭐⭐
🔗 LangGraph

LangGraph is suitable for stateful and multi-step research workflows.

Search
  ↓
Retrieve
  ↓
Read
  ↓
Extract Evidence
  ↓
Assess Evidence
  ↓
Synthesize
  ↓
Verify

Resources
📚 LangGraph Documentation
💻 GitHub Repository
🤝 AutoGen

AutoGen supports LLM-based agents and multi-agent interactions.

Applications
Multi-agent research workflows
Research planning
Agent collaboration
Tool use
Iterative synthesis
Resources
📚 Documentation
💻 GitHub Repository
👥 CrewAI

CrewAI supports role-based multi-agent workflows.

Applications
Research-agent teams
Task delegation
Multi-stage synthesis
Agent collaboration
Workflow automation
Resources
📚 Documentation
💻 GitHub Repository
🔗 Evidence & Citation Evaluation

Evidence-traceability systems need to determine whether generated claims are actually supported by retrieved evidence.

Tool / Method	Main Function	Relevance
RAGAS	RAG evaluation	⭐⭐⭐⭐⭐
DeepEval	Faithfulness & RAG evaluation	⭐⭐⭐⭐⭐
ARES	RAG evaluation	⭐⭐⭐⭐⭐
FActScore	Atomic factuality	⭐⭐⭐⭐⭐
ALCE	Citation correctness	⭐⭐⭐⭐⭐
TRUE	Factual consistency	⭐⭐⭐⭐

Research note: ARES, FActScore, ALCE, and TRUE are primarily research methods or benchmarks rather than general-purpose software libraries. They are included because they provide methodological foundations for evidence-traceability metrics.

📏 RAGAS

RAGAS provides reference-free evaluation methods for RAG systems.

Evaluation Dimensions
Context relevance
Context recall
Context precision
Answer relevance
Faithfulness
Resources
📚 Documentation
💻 GitHub Repository
🧪 DeepEval

DeepEval is an evaluation framework for LLM, RAG, and agentic applications.

Applications
Retrieval evaluation
Faithfulness evaluation
Hallucination detection
Agent evaluation
Trajectory evaluation
Custom metrics
Regression testing
Resources
📚 Documentation
💻 GitHub Repository
🔬 LLM Evaluation Frameworks
Framework	RAG	Agents	Custom Metrics	Trace Evaluation
DeepEval	✅	✅	✅	✅
RAGAS	✅	◐	✅	◐
Phoenix	✅	✅	✅	✅
MLflow	✅	✅	✅	✅
W&B Weave	✅	✅	✅	✅
Legend
✅ = Strong support
◐ = Partial / indirect support
❌ = Not a primary capability
🧭 Tracing & Observability

Evidence traceability requires access to the execution trace, rather than only the final generated report.

A useful trace representation is:

Research Task
     │
     ├── Query Generation
     │
     ├── Search Call
     │      ├── Source A
     │      ├── Source B
     │      └── Source C
     │
     ├── Retrieval
     │
     ├── Evidence Extraction
     │
     ├── Claim Generation
     │
     ├── Citation Assignment
     │
     ├── Verification
     │
     └── Final Synthesis

🔥 Arize Phoenix

Phoenix is an open-source observability and evaluation platform for AI/LLM applications.

Applications
Agent trace collection
Retrieval tracing
Tool-call tracing
Evaluation
RAG debugging
Failure analysis
Resources
📚 Documentation
💻 GitHub Repository
📈 MLflow

MLflow provides experiment tracking and tracing capabilities for ML and GenAI applications.

Applications
Experiment tracking
Trace storage
Evaluation
Custom scoring
Regression analysis
Model comparison
Reproducibility
Resources
📚 Documentation
💻 GitHub Repository
🧵 OpenTelemetry & OpenInference

OpenTelemetry provides a general observability framework, while OpenInference provides conventions and instrumentation for AI/LLM applications.

A research trace can be represented as:

Agent
 ├── LLM Call
 ├── Retriever
 ├── Tool
 ├── Document
 ├── Evidence
 ├── Citation
 └── Evaluation

Resources
🌐 OpenTelemetry
💻 OpenInference
📊 Experiment Tracking & Evaluation

Evidence-traceability research requires repeated experiments across:

Different LLMs
Retrieval strategies
Prompts
Datasets
Agent configurations
Evaluation metrics
Recommended Workflow
Dataset
   ↓
Agent Configuration
   ↓
Experiment Run
   ↓
Execution Trace
   ↓
Evidence Graph
   ↓
Metrics
   ↓
Statistical Analysis
   ↓
Research Report

Tool	Primary Purpose
MLflow	Experiment and trace tracking
Weights & Biases	Experiment tracking
W&B Weave	LLM tracing and evaluation
Phoenix	AI observability and evaluation
TensorBoard	Experiment visualization
🗂️ Document Processing

Scientific literature is commonly distributed as:

PDF
HTML
XML
Structured metadata
Supplementary files
Tool	Function	Research Use
GROBID	Scientific PDF → structured XML/TEI	⭐⭐⭐⭐⭐
PyMuPDF	PDF extraction	⭐⭐⭐⭐
Unstructured	Document parsing	⭐⭐⭐⭐
Apache Tika	Content extraction	⭐⭐⭐
BeautifulSoup	HTML parsing	⭐⭐⭐
📄 GROBID

GROBID extracts structured information from scientific documents.

Applications
Title extraction
Author extraction
Abstract extraction
Section detection
Reference extraction
Citation parsing
Scientific document structuring
Resource
💻 GROBID GitHub
📑 PyMuPDF

PyMuPDF supports extraction of text, metadata, images, and structural information from PDFs.

Applications
PDF ingestion
Page-level evidence extraction
Citation localization
Text extraction
Document preprocessing
Resource
📚 PyMuPDF Documentation
🧩 Unstructured

Unstructured provides document-processing functionality for LLM and RAG workflows.

Applications
PDF processing
HTML processing
Document chunking
Metadata extraction
RAG preprocessing
Resources
📚 Documentation
💻 GitHub Repository
🧮 Vector Databases & Retrieval Infrastructure

Evidence traceability depends on preserving the relationship between a retrieved passage and its originating document.

Tool	Type	Main Use
FAISS	Vector library	Similarity search
Qdrant	Vector database	Metadata-aware retrieval
Milvus	Vector database	Large-scale retrieval
Weaviate	Vector database	Semantic search
Chroma	Vector database	Local RAG development
🧾 Recommended Evidence Metadata

When storing scientific evidence, preserve metadata such as:

{
  "document_id": "doi:10.xxxx/xxxxx",
  "title": "Research Paper",
  "authors": [
    "Author A",
    "Author B"
  ],
  "year": 2026,
  "page": 7,
  "section": "Results",
  "chunk_id": "paper_001_chunk_042",
  "retrieval_score": 0.91,
  "doi": "10.xxxx/xxxxx"
}


This information makes it possible to reconstruct the evidence lineage of generated claims.

🧾 Provenance & Traceability Standards
Standard / Technology	Purpose	Relevance
W3C PROV	Provenance representation	⭐⭐⭐⭐⭐
OpenTelemetry	Distributed tracing	⭐⭐⭐⭐⭐
OpenInference	AI/LLM instrumentation	⭐⭐⭐⭐⭐
RO-Crate	Research object packaging	⭐⭐⭐⭐
DataCite	Persistent identifiers	⭐⭐⭐⭐
Crossref	Scholarly metadata	⭐⭐⭐⭐⭐
🔗 W3C PROV

The W3C PROV family of specifications provides a framework for representing provenance.

A literature synthesis pipeline can be represented conceptually as:

Entity
  │
  │ wasDerivedFrom
  ▼
Entity
  │
  │ wasGeneratedBy
  ▼
Activity
  │
  │ wasAssociatedWith
  ▼
Agent


For literature synthesis:

Research Paper
      ↓
Evidence Passage
      ↓
Generated Claim
      ↓
Citation
      ↓
Research Report

Resource
🌐 W3C PROV Overview
🎯 Recommended Research Stack

For an academic research prototype, the following stack provides broad coverage across the evidence-traceability lifecycle.

Layer	Recommended Tool
📚 Literature Discovery	OpenAlex + Semantic Scholar
🧾 Metadata Verification	Crossref
🔬 Biomedical Retrieval	PubMed / Europe PMC
📄 PDF Processing	GROBID + PyMuPDF
🧮 Vector Retrieval	Qdrant / FAISS
📚 RAG Framework	LlamaIndex / LangChain
🤖 Agent Orchestration	LangGraph
🧭 Trace Instrumentation	OpenTelemetry + OpenInference
🧭 Observability	Phoenix
📏 RAG Evaluation	RAGAS + DeepEval
📊 Experiment Tracking	MLflow
🧾 Provenance Model	W3C PROV
📊 Tool-to-Metric Mapping
Metric Dimension	Recommended Tools
🔎 Retrieval Recall	OpenAlex, Semantic Scholar, RAGAS
🎯 Retrieval Precision	RAGAS, DeepEval
📚 Source Coverage	OpenAlex, Crossref
🔗 Claim–Evidence Alignment	DeepEval, custom evaluators
📍 Evidence Localization	GROBID, PyMuPDF
🧾 Citation Correctness	Crossref, custom citation evaluator
🧠 Faithfulness	RAGAS, DeepEval
🚨 Hallucination Rate	DeepEval, RAGTruth
🔄 Agent Trajectory Quality	DeepEval, Phoenix
🧭 Provenance Completeness	W3C PROV, OpenTelemetry
🧩 Trace Completeness	Phoenix, OpenTelemetry
⏱️ Workflow Efficiency	Phoenix, MLflow
♻️ Reproducibility	MLflow, W&B
📊 Experiment Consistency	MLflow, Phoenix
🧪 Regression Testing	DeepEval, MLflow
🔬 Research Use Cases
1. Evidence Retrieval Evaluation
Research Question
       ↓
Literature Search
       ↓
Candidate Papers
       ↓
Retrieved Evidence
       ↓
Precision / Recall / Relevance


Recommended tools: OpenAlex + Semantic Scholar + RAGAS + DeepEval

2. Claim–Evidence Traceability
Generated Claim
       ↓
Supporting Citation
       ↓
Evidence Passage
       ↓
Original Paper
       ↓
Persistent Identifier


Recommended tools: GROBID + Crossref + W3C PROV + custom evaluator

3. Agent Workflow Traceability
Agent
 │
 ├── Search
 ├── Retrieve
 ├── Read
 ├── Extract
 ├── Synthesize
 ├── Cite
 └── Verify


Recommended tools: LangGraph + OpenTelemetry + Phoenix

4. Citation Integrity

A citation can be evaluated across several dimensions:

Citation
   │
   ├── Correct Source?
   │
   ├── Correct Paper?
   │
   ├── Supports Claim?
   │
   ├── Evidence Actually Present?
   │
   └── Citation Location Correct?


Recommended tools: Crossref + GROBID + DeepEval + custom citation metrics

🧠 Proposed Metric Layers

The tools above can support a hierarchical evidence-traceability framework:

                    Evidence Traceability
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
     Retrieval          Evidence          Generation
      Layer              Layer               Layer
          │                 │                 │
          ▼                 ▼                 ▼
    Recall /           Relevance /        Faithfulness /
    Precision          Coverage           Hallucination
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                     Citation Layer
                            │
                            ▼
                    Provenance Layer
                            │
                            ▼
                      Agent Trace
                            │
                            ▼
                  Workflow Traceability

⭐ Recommended Core Toolkit

If the objective is to build a research prototype, the following compact stack is recommended.

<details> <summary><strong>📚 Discovery & Corpus</strong></summary>
OpenAlex — Scholarly corpus and metadata
Semantic Scholar — Literature discovery and citation networks
Crossref — DOI and metadata verification
PubMed — Biomedical literature
</details> <details> <summary><strong>📄 Processing & Retrieval</strong></summary>
GROBID — Scientific PDF parsing
PyMuPDF — PDF extraction
Qdrant / FAISS — Vector retrieval
LlamaIndex / LangChain — RAG pipelines
</details> <details> <summary><strong>🤖 Agent Layer</strong></summary>
LangGraph — Stateful agent orchestration
AutoGen — Multi-agent workflows
CrewAI — Role-based agent workflows
</details> <details> <summary><strong>🧭 Traceability Layer</strong></summary>
OpenTelemetry — Distributed tracing
OpenInference — AI/LLM instrumentation
Phoenix — AI observability and evaluation
</details> <details> <summary><strong>📏 Evaluation Layer</strong></summary>
RAGAS — RAG evaluation
DeepEval — LLM, RAG, and agent evaluation
</details> <details> <summary><strong>📊 Experiment Layer</strong></summary>
MLflow — Experiment tracking and evaluation
Weights & Biases — Experiment management
</details> <details> <summary><strong>🧾 Provenance Layer</strong></summary>
W3C PROV — Provenance representation
OpenTelemetry — Execution trace representation
</details>
🔬 End-to-End Research Architecture
                    ┌──────────────────────┐
                    │  Scholarly Sources   │
                    │ OpenAlex / PubMed /  │
                    │ Semantic Scholar     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Document Processing  │
                    │ GROBID / PyMuPDF     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Retrieval Layer      │
                    │ Qdrant / FAISS       │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ RAG / Knowledge      │
                    │ LlamaIndex /         │
                    │ LangChain            │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Agent Orchestration  │
                    │ LangGraph             │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Trace Instrumentation│
                    │ OpenTelemetry /      │
                    │ OpenInference        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Observability        │
                    │ Phoenix              │
                    └──────────┬───────────┘
                               │
                    ┌──────────┴───────────┐
                    ▼                      ▼
             ┌──────────────┐       ┌──────────────┐
             │    RAGAS     │       │  DeepEval    │
             │ RAG Metrics  │       │ Agent Metrics│
             └──────┬───────┘       └──────┬───────┘
                    │                      │
                    └──────────┬───────────┘
                               ▼
                       ┌──────────────┐
                       │    MLflow    │
                       │ Experiments  │
                       └──────┬───────┘
                              │
                              ▼
                  ┌────────────────────────┐
                  │ Evidence-Traceability  │
                  │       Metrics          │
                  └────────────────────────┘

🧾 Example Evidence-Traceability Record

A trace record for experimental evaluation could be represented as:

{
  "claim_id": "claim_017",
  "claim_text": "The retrieval method improves evidence coverage.",
  "source_document": {
    "title": "Example Research Paper",
    "doi": "10.xxxx/example"
  },
  "evidence": {
    "page": 6,
    "section": "Results",
    "chunk_id": "chunk_042"
  },
  "retrieval": {
    "method": "hybrid",
    "rank": 2,
    "score": 0.91
  },
  "citation": {
    "citation_id": "cite_017",
    "verified": true
  },
  "evaluation": {
    "evidence_relevance": 0.94,
    "claim_support": 0.89,
    "citation_correctness": 1.0
  }
}


This structure allows metrics to be calculated at multiple levels:

 Claim level
 Evidence level
 Citation level
 Document level
 Agent-step level
 Workflow level
📚 Selection Principles

Tools included in this collection should ideally satisfy one or more of the following criteria:

 Support scholarly literature retrieval
 Preserve document-level metadata
 Preserve passage-level evidence
 Support agent execution tracing
 Enable retrieval evaluation
 Enable faithfulness evaluation
 Support citation/provenance tracking
 Provide reproducible experiments
 Support custom research metrics
 Integrate with open standards
🔬 Research Objective

The objective is not simply to build another RAG system.

The central research goal is to make the complete evidence chain observable, measurable, and auditable:

Question → Search → Source → Evidence → Claim → Citation → Verification → Provenance

A successful evidence-traceability system should allow researchers to move backward from any generated claim to the precise evidence and source that support it, while also reconstructing the agent's retrieval and synthesis trajectory.

🌟 Final Perspective

A trustworthy agentic literature-synthesis system should not be evaluated solely on the fluency or apparent correctness of its final answer.

It should also be evaluated on its ability to:

🔎 Retrieve relevant evidence
📌 Select appropriate sources
🔗 Connect claims to evidence
🧾 Preserve provenance
📚 Produce accurate citations
🚨 Avoid unsupported claims
♻️ Enable reconstruction of its research process
📊 Produce reproducible evaluation results

Together, these tools provide a practical foundation for developing a multidimensional evidence-traceability evaluation framework.

🔬 Evidence-Traceability Pipeline
┌───────────────────────────────────────────────────────────────┐
│                    AGENTIC RESEARCH PIPELINE                  │
└───────────────────────────────────────────────────────────────┘
                              │
                              ▼
                    🔎 Literature Discovery
                              │
                              ▼
                    📚 Document Retrieval
                              │
                              ▼
                    📄 Evidence Extraction
                              │
                              ▼
                    🤖 Agentic Reasoning
                              │
                              ▼
                    🔗 Claim–Evidence Linking
                              │
                              ▼
                    🧾 Citation Assignment
                              │
                              ▼
                    🧭 Provenance Tracking
                              │
                              ▼
                    📊 Metric Computation
                              │
                              ▼
                    ✅ Verification & Audit

📁 Suggested Repository Structure
.
├── README.md
│
├── paper/
│   └── AI_Assisted_Research_Paper.pdf
│
├── references/
│   └── references.md
│
├── datasets/
│   └── datasets.md
│
├── tools/
│   └── tools.md
│
├── implementations/
│   └── implementations.md
│
├── tutorials/
│   └── tutorials.md
│
└── citation-audit/
    └── Citation_Integrity_Audit.pdf

<p align="center">
🔎 Retrieve → 📚 Evidence → 🔗 Attribute → 🧾 Cite → 🧭 Trace → ✅ Verify

Building trustworthy, transparent, reproducible, and auditable agentic literature synthesis systems.

⭐ If this resource is useful for your research, consider starring the repository!

</p> ```
GitHub rendering features included

This version uses GitHub Flavored Markdown features such as:

# / ## / ### headings
GitHub-compatible tables
[x] task/check lists
<details> / <summary> collapsible sections
Fenced text and json code blocks
Blockquotes using >
Emoji-based visual navigation
Repository directory trees
GitHub-compatible badges
Internal anchor links
Consistent alignment syntax such as :---: and :---|
<p align="center"> for a GitHub-friendly footer

Suggested filename: tools/tools.md
