Welcome !
Here we have various ML learning techniques from verified sources. This repository will help us to dive into core concepts of Machine Learning.

# Contents
* [Link Text](#contents)

## A second-level heading
### A third-level heading

# Source - https://stackoverflow.com/a/69921468


# Creating an example workflow

In this tutorial, you'll learn how to create a basic workflow that is triggered by a push event.

## Introduction

This guide shows you how to create a basic workflow that is triggered when code is pushed to your repository.

To get started with preconfigured workflows, browse through the list of templates in the [actions/starter-workflows](https://github.com/actions/starter-workflows) repository. For more information, see [Using workflow templates](/en/actions/how-tos/write-workflows/use-workflow-templates).

> This is a blockquote on GitHub.

> \[!IMPORTANT] For more information about best practices for securing your workflows and secure use of GitHub Actions features, see [Secure use reference](/en/actions/reference/security/secure-use#writing-workflows).
>

<details>
  <summary>Click here to expand</summary>

  This content is hidden by default. You can include paragraphs, images, or even code blocks here.
  
</details>

qwewqeqwewqe

[GitHub Pages](https://pages.github.com/).

## Code of conduct

This project has adopted a [Code of Conduct][code-of-conduct]. By participating, you agree to abide by its terms.

## Support

For help, questions, and how to file issues, see [`SUPPORT.md`][support].

Here is a sentence that requires a first reference[^1].
You can also add a completely different second reference later in the paragraph[^2].

Below is a polished, GitHub-ready README.md tailored to your research topic, “Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines.” I’ve kept the structure from your template while making the sections appropriate for the 20-paper collection you developed.

Writing
Awesome Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines

A curated collection of research papers, datasets, evaluation frameworks, tools, implementations, and learning resources related to evidence traceability, citation correctness, provenance, retrieval-augmented generation (RAG), agentic research systems, and automated scientific literature synthesis.

This repository supports research on designing and evaluating evidence-traceability metrics for agentic literature synthesis pipelines, with an emphasis on claim-level evidence grounding, citation faithfulness, provenance, retrieval quality, factual consistency, and reproducibility.

Contents
Overview
AI-Assisted Research Paper
Survey Papers
Foundational Papers
Recent Research Papers
Datasets
Tools and Libraries
GitHub Implementations
Tutorials
Citation Integrity Audit
License
Overview

Large Language Models (LLMs) and autonomous research agents are increasingly being used to retrieve scientific literature, identify relevant evidence, synthesize findings, and generate research reports.

However, conventional evaluation metrics often focus primarily on answer quality, factual correctness, or retrieval performance without fully measuring whether individual claims can be reliably traced back to the evidence that supports them.

This repository focuses on the emerging research problem of evidence traceability in agentic literature synthesis pipelines.

Key research dimensions include:

Evidence retrieval: Can the system retrieve relevant and authoritative scientific evidence?
Claim–evidence alignment: Can generated claims be mapped to the evidence supporting them?
Citation correctness: Does a citation actually support the associated claim?
Citation completeness: Are important claims adequately supported by citations?
Factual faithfulness: Does the generated synthesis remain consistent with retrieved evidence?
Provenance: Can the origin and transformation of evidence be reconstructed?
Evidence coverage: What proportion of substantive claims have traceable supporting evidence?
Source quality: Are authoritative and appropriate sources preferentially selected?
Workflow traceability: Can retrieval, reasoning, synthesis, and citation decisions be audited?
Reproducibility: Can another researcher reconstruct the evidence trail and synthesis process?

The collection is intended for researchers working in NLP, information retrieval, scientific AI, RAG, AI-assisted research, knowledge representation, provenance, and trustworthy AI.

AI-Assisted Research Paper
Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines

The repository's primary research paper investigates how evidence-traceability can be operationalized and evaluated within agentic literature synthesis systems.

The paper discusses:

Evidence-traceability dimensions
Claim-level citation analysis
Retrieval and evidence quality
Citation faithfulness
Provenance completeness
Factual consistency
Agent workflow traceability
Existing evaluation frameworks
Research gaps and future metric design

Paper:
View AI-Assisted Research Paper

Survey Papers

Survey papers provide an overview of the technical foundations surrounding retrieval-augmented generation, scientific literature synthesis, and evidence-grounded language generation.

Selected Surveys

Retrieval-Augmented Generation for Large Language Models: A Survey
Gao et al. (2023)
arXiv:2312.10997

Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks
Lewis et al. (2020)
arXiv:2005.11401

TRUE: Re-evaluating Factual Consistency Evaluation
Honovich et al. (2022)
ACL Anthology

These works establish important concepts for retrieval, grounding, factual consistency, and evaluation of knowledge-intensive language systems.

Foundational Papers

The following works provide important foundations for evidence-grounded generation, provenance, retrieval, and citation-aware NLP systems.

Retrieval-Augmented Generation
Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks
Lewis et al., 2020
Paper
Provenance and Scientific Workflows
Provenance in Collection-Oriented Scientific Workflows
Bowers, McPhillips & Ludäscher, 2008
DOI:10.1002/cpe.1226
Knowledge-Intensive Evaluation
KILT: a Benchmark for Knowledge Intensive Language Tasks
Petroni et al., 2021
ACL Anthology
Factuality Evaluation
FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation
Min et al., 2023
ACL Anthology
Citation-Aware Generation
Enabling Large Language Models to Generate Text with Citations
Gao et al., 2023
ACL Anthology
Recent Research Papers

Recent research has increasingly focused on autonomous research agents, scientific literature synthesis, citation evaluation, hallucination detection, and end-to-end research workflows.

Scientific Literature Synthesis
Synthesizing Scientific Literature with Retrieval-Augmented Language Models
Asai et al., 2026
Nature, 650, 857–863
DOI:10.1038/s41586-025-10072-4
Agentic Research Systems

Agent Laboratory: Using LLM Agents as Research Assistants
Schmidgall et al., 2025
arXiv:2501.04227

DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents
Du et al., 2025
arXiv:2506.11763

Self-Reflective Retrieval
Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection
Asai et al., 2024
arXiv:2310.11511
Scientific Research Agents
PaperQA: Retrieval-Augmented Generative Agent for Scientific Research
Lála et al., 2023
arXiv:2312.07559
Citation Evaluation
Towards Fine-Grained Citation Evaluation in Generated Text: A Comparative Analysis of Faithfulness Metrics
Zhang et al., 2024
ACL Anthology
Research and Article Generation
Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models
Shao et al., 2024
ACL Anthology
Datasets

Datasets and benchmarks are essential for developing and validating evidence-traceability metrics.

PubMedQA

A biomedical question-answering dataset requiring reasoning over scientific research evidence.

Jin et al., 2019
Proceedings of EMNLP-IJCNLP 2019
ACL Anthology
RAGTruth

A hallucination corpus designed for evaluating trustworthy retrieval-augmented language models, including fine-grained annotations of unsupported generated content.

Niu et al., 2024
Proceedings of ACL 2024
ACL Anthology
KILT

A benchmark for knowledge-intensive language tasks that incorporates provenance-aware evaluation.

Petroni et al., 2021
Proceedings of NAACL-HLT 2021
ACL Anthology
Evidence Inference

A biomedical evidence extraction and inference resource focused on identifying evidence supporting comparative conclusions from clinical trials.

DeYoung et al., 2020
Proceedings of the SIGBioMed Workshop on Biomedical Language Processing
ACL Anthology
Tools and Libraries

The following tools and frameworks are relevant to building or evaluating evidence-grounded and retrieval-augmented systems.

RAG Evaluation
RAGAS — Automated evaluation of retrieval-augmented generation systems.
Context relevance
Faithfulness
Answer relevance
Automated RAG Evaluation
ARES — Automated evaluation framework for RAG systems.
Context relevance
Answer faithfulness
Answer relevance
Citation Evaluation
ALCE — Automatic evaluation of citations generated by language models.
Citation correctness
Citation completeness
Citation quality
Factuality Evaluation
FActScore — Fine-grained evaluation of factual precision through atomic fact decomposition.
GitHub Implementations

This section collects open-source implementations and repositories relevant to the research topic.

Recommended categories include:

Retrieval-Augmented Generation
Scientific literature retrieval
Citation verification
Citation-aware generation
RAG evaluation
Hallucination detection
Provenance tracking
Research agents
Automated literature review
Evidence extraction
Example Projects

Self-RAG — Retrieval, generation, and self-reflection framework
GitHub

RAGAS — Evaluation framework for RAG applications
GitHub

KILT — Knowledge-intensive language task benchmark
GitHub

FActScore — Fine-grained factuality evaluation
GitHub

STORM — Multi-perspective research and article generation
GitHub

Tutorials

Recommended learning resources for understanding the technical foundations of evidence-traceable literature synthesis include:

Retrieval-Augmented Generation
Retrieval-Augmented Generation (RAG)
Dense passage retrieval
Hybrid retrieval
Query expansion
Reranking
Context selection
Evidence and Citation Evaluation
Citation correctness
Citation completeness
Claim-level attribution
Factual consistency
Hallucination detection
Evidence-grounded generation
Agentic Literature Research
Tool-using LLM agents
Multi-step retrieval
Self-reflection
Research planning
Scientific literature search
Automated literature review
Research report generation
Provenance
Data provenance
Workflow provenance
Evidence lineage
Reproducibility
FAIR data principles
Citation Integrity Audit

Citation integrity is a core component of evidence-traceable scientific synthesis.

The audit evaluates the selected references for:

Bibliographic correctness
Author accuracy
Publication year
Venue accuracy
DOI or persistent identifier
Citation accessibility
Claim–citation correspondence
Evidence relevance
Citation completeness
Potential unsupported claims

The complete audit is available here:

View Citation Integrity Audit

Repository Structure
.
├── README.md
│
├── paper/
│   └── AI_Assisted_Research_Paper.pdf
│
├── references/
│   └── references.md
│
├── citation-audit/
│   └── Citation_Integrity_Audit.pdf
│
├── datasets/
│   └── README.md
│
├── tools/
│   └── README.md
│
└── tutorials/
    └── README.md

Research Focus

The repository is particularly concerned with developing a multidimensional framework for evaluating evidence traceability.

A potential metric framework can be expressed as:

𝐸
𝑇
=
𝑓
(
𝐶
𝑆
,
𝐸
𝐴
,
𝐶
𝐶
,
𝐹
𝐶
,
𝑃
𝐶
,
𝑅
𝐶
,
𝑆
𝑄
)

where:

CS = Citation Support
EA = Evidence Alignment
CC = Citation Completeness
FC = Factual Consistency
PC = Provenance Completeness
RC = Retrieval Coverage
SQ = Source Quality

The goal is not to reduce evidence traceability to a single score, but to provide a transparent, interpretable, and auditable set of complementary metrics.

Contributing

Contributions are welcome.

When adding a paper, dataset, tool, or implementation, please provide:

Name and title
Authors or developers
Publication/release year
Venue or source
DOI, arXiv ID, PMID, or another persistent identifier where available
Official repository or project link
A short explanation of relevance
Verification of bibliographic information

Please prioritize peer-reviewed scholarly literature, established benchmarks, official repositories, and reproducible research resources.

License

This repository is intended for academic and educational purposes.

Unless otherwise specified, the original papers, datasets, software, and external resources remain under their respective licenses and copyrights. This repository does not redistribute copyrighted research papers; it provides bibliographic information, links, summaries, and research-oriented organization.

For repository-specific content, please see the applicable license included in the repository.

