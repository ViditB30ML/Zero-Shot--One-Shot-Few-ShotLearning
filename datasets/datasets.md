Certainly. Based on the 20 references you selected, four strong dataset/benchmark resources are PubMedQA, RAGTruth, KILT, and Evidence Inference 2.0. I verified their official repositories and dataset descriptions. 
G
GitHub
+3

Here is a polished, GitHub-ready datasets.md file:

📊 Datasets & Benchmarks

A curated collection of datasets and benchmarks relevant to evidence traceability, scientific literature synthesis, retrieval-augmented generation (RAG), factual consistency, provenance, and evidence-grounded question answering.

These resources can support the development and evaluation of metrics for agentic literature synthesis pipelines.

📚 Dataset Overview
Dataset / Benchmark	Domain	Primary Focus	Relevance
PubMedQA	Biomedical	Research QA	Evidence-grounded scientific reasoning
RAGTruth	RAG / NLP	Hallucination detection	Unsupported and contradictory claims
KILT	Knowledge-intensive NLP	Provenance	Evidence and source attribution
Evidence Inference 2.0	Biomedical	Evidence extraction	Claim–evidence alignment
1. 🧬 PubMedQA
Name

PubMedQA: A Dataset for Biomedical Research Question Answering

Source

Official GitHub Repository: pubmedqa/pubmedqa

The dataset is maintained through the official PubMedQA project and provides data and evaluation code for biomedical research question answering. 
G
GitHub
+1

Description

PubMedQA is a biomedical question-answering dataset designed to evaluate whether systems can answer research questions using evidence contained in biomedical article abstracts.

Questions are answered using three possible labels:

Yes
No
Maybe

The dataset contains approximately:

1,000 expert-labeled instances
61.2K unlabeled instances
211.3K artificially generated instances

The official repository provides the dataset, preprocessing scripts, and evaluation utilities. 
P
pubmedqa.github.io
+1

Application

PubMedQA can be used for:

Biomedical question answering
Evidence-grounded reasoning
Scientific literature understanding
Evaluation of LLMs on research questions
Claim–evidence reasoning
Testing scientific RAG systems
Evaluating whether generated answers are supported by scientific literature
Relevance to Evidence Traceability

PubMedQA is particularly useful for evaluating whether an AI system can derive an answer from scientific evidence rather than relying solely on parametric knowledge.

Links
🔗 Official GitHub Repository
🌐 Official Project Website
📄 Research Paper — ACL Anthology
Citation

Jin, Q., Dhingra, B., Liu, Z., Cohen, W. W., & Lu, X. (2019). PubMedQA: A Dataset for Biomedical Research Question Answering. Proceedings of EMNLP-IJCNLP 2019, 2567–2577.

2. 🚨 RAGTruth
Name

RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models

Source

Official GitHub Repository: ParticleMedia/RAGTruth

RAGTruth provides a corpus and accompanying code for studying hallucinations in retrieval-augmented generation systems. 
G
GitHub

Description

RAGTruth is a word-level hallucination corpus for Retrieval-Augmented Generation (RAG).

It contains nearly 18,000 naturally generated responses produced by multiple language models in RAG settings.

The responses have been manually annotated at:

Case level
Word level
Hallucination-span level

The annotations identify unsupported or contradictory content and provide additional information about hallucination characteristics. 
G
GitHub

Application

RAGTruth can be applied to:

Hallucination detection
RAG evaluation
Faithfulness evaluation
Unsupported-claim detection
Contradiction detection
Fine-grained factuality analysis
Training hallucination-detection models
Evaluating evidence-grounded generation
Relevance to Evidence Traceability

RAGTruth is highly relevant because evidence traceability requires determining whether generated claims are actually supported by retrieved evidence.

Its fine-grained hallucination annotations can therefore support metrics such as:

Unsupported Claim Rate
Evidence Contradiction Rate
Claim-Level Faithfulness
Evidence-Supported Token Ratio
Links
🔗 Official GitHub Repository
📄 arXiv Paper
📄 ACL Anthology — ACL 2024
Citation

Niu, C., Wu, Y., Zhu, J., Xu, S., Shum, K., Zhong, R., Song, J., & Zhang, T. (2024). RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models. Proceedings of ACL 2024, 10862–10878.

3. 🔗 KILT
Name

KILT: A Benchmark for Knowledge Intensive Language Tasks

Source

Official GitHub Repository: facebookresearch/KILT

KILT is an open benchmark and framework for knowledge-intensive NLP tasks with explicit provenance information. The official repository contains the benchmark data, knowledge source, evaluation framework, and data-processing utilities. 
G
GitHub
+1

Repository status: The original Facebook Research repository was archived in October 2023 and is now read-only. 
G
GitHub

Description

KILT brings together multiple knowledge-intensive NLP tasks under a common framework and knowledge source.

Its data format explicitly represents:

Input questions or claims
Generated answers
Supporting evidence
Wikipedia identifiers
Titles
Sections
Paragraph locations
Character spans
Provenance information

This makes provenance a first-class component of the benchmark. 
G
GitHub

KILT includes tasks such as:

Fact checking
Entity linking
Open-domain question answering
Slot filling
Dialogue
Knowledge-intensive language tasks
Application

KILT can be used for:

Provenance-aware question answering
Retrieval evaluation
Evidence retrieval
Knowledge-intensive NLP
Source attribution
Evidence localization
Retrieval-grounded generation
Benchmarking provenance-aware systems
Relevance to Evidence Traceability

KILT is one of the most directly relevant resources for this research because its evaluation framework explicitly connects answers with supporting provenance.

Its evidence-location representation provides a useful conceptual model for designing:

Provenance Completeness
Evidence Coverage
Evidence Localization Accuracy
Retrieval Recall
Claim–Evidence Alignment
Links
🔗 Official GitHub Repository
🌐 KILT Benchmark
📄 ACL Anthology — NAACL 2021
📄 arXiv
Citation

Petroni, F., Piktus, A., Fan, A., Lewis, P., Yazdani, M., De Cao, N., Thorne, J., Jernite, Y., Karpukhin, V., Maillard, J., Plachouras, V., Rocktäschel, T., & Riedel, S. (2021). KILT: A Benchmark for Knowledge Intensive Language Tasks. Proceedings of NAACL-HLT 2021, 2523–2544. DOI: 10.18653/v1/2021.naacl-main.200.

4. 🧪 Evidence Inference 2.0
Name

Evidence Inference 2.0: More Data, Better Models

Source

Official GitHub Repository: jayded/evidence-inference

The repository provides the dataset, annotations, preprocessing resources, and code associated with Evidence Inference research. 
G
GitHub

Description

Evidence Inference is a biomedical evidence-extraction and inference dataset based on reports of randomized controlled trials.

The task asks systems to determine the relationship between:

Intervention
     +
Comparator
     +
Outcome
     ↓
Evidence-supported conclusion


For example, a system may need to determine whether an intervention significantly increased, decreased, or had no significant effect on a particular outcome compared with a comparator.

The dataset also provides supporting evidence spans, making it particularly valuable for claim–evidence evaluation. 
G
GitHub

Evidence Inference 2.0 expanded the original dataset with additional annotations and introduced stronger baseline models and an abstract-only version for rapid experimentation. 
G
GitHub

Application

Evidence Inference 2.0 can be used for:

Biomedical evidence extraction
Clinical-trial analysis
Evidence span identification
Claim–evidence linking
Scientific information extraction
Evidence-grounded QA
Medical literature synthesis
Evaluating scientific reasoning systems
Relevance to Evidence Traceability

This dataset is particularly valuable for claim–evidence alignment metrics because systems are expected not only to infer a conclusion but also to identify evidence supporting that conclusion.

It can therefore help evaluate:

Evidence Span Recall
Evidence Span Precision
Claim–Evidence Alignment
Supporting Evidence Coverage
Evidence Selection Accuracy
Links
🔗 Official GitHub Repository
🌐 Dataset Website
📄 arXiv — Evidence Inference 2.0
📄 ACL Anthology
Citation

DeYoung, J., Lehman, E., Nye, B., Marshall, I., & Wallace, B. C. (2020). Evidence Inference 2.0: More Data, Better Models. Proceedings of the 19th SIGBioMed Workshop on Biomedical Language Processing, 123–132. DOI: 10.18653/v1/2020.bionlp-1.13.

📊 Comparison
Resource	Evidence	Provenance	Hallucination	Scientific Literature	Claim–Evidence Linking
PubMedQA	✅	◐	◐	✅	✅
RAGTruth	✅	◐	✅	◐	✅
KILT	✅	✅	◐	◐	✅
Evidence Inference 2.0	✅	◐	◐	✅	✅

Legend:
✅ Strong support · ◐ Partial/indirect support

🎯 Recommended Use in This Research

For Designing Evidence-Traceability Metrics for Agentic Literature Synthesis Pipelines, the four resources can be mapped to different evaluation dimensions:

                    Evidence Traceability
                            │
       ┌────────────────────┼────────────────────┐
       │                    │                    │
       ▼                    ▼                    ▼
   PubMedQA             RAGTruth              KILT
       │                    │                    │
       ▼                    ▼                    ▼
Scientific QA        Hallucination         Provenance
Evidence Reasoning   Faithfulness           Retrieval
       │                    │                    │
       └────────────────────┼────────────────────┘
                            │
                            ▼
                  Evidence Inference 2.0
                            │
                            ▼
                  Claim–Evidence Alignment

Suggested Metric Mapping
Metric	Recommended Resource
Retrieval Coverage	KILT
Evidence Relevance	KILT / PubMedQA
Claim–Evidence Alignment	Evidence Inference 2.0
Evidence Span Accuracy	Evidence Inference 2.0
Citation / Evidence Support	KILT / Evidence Inference 2.0
Hallucination Rate	RAGTruth
Faithfulness	RAGTruth
Scientific Reasoning	PubMedQA
Provenance Completeness	KILT
Evidence Traceability	KILT + Evidence Inference 2.0 + RAGTruth
📌 Notes

These resources originate from the scholarly literature included in this repository's selected reference set. They are not all designed specifically for agentic literature synthesis; rather, they provide complementary components that can be combined to evaluate different dimensions of an agentic research pipeline.

In particular:

PubMedQA → scientific evidence-based reasoning
RAGTruth → groundedness and hallucination
KILT → provenance and evidence localization
Evidence Inference 2.0 → explicit claim–evidence relationships

Together, they provide a useful experimental foundation for developing multidimensional evidence-traceability metrics.

📚 Related Files
📄 Research Paper
📚 References
🔍 Citation Integrity Audit
🏠 Repository README
<p align="center">

Evidence → Attribution → Provenance → Verification → Trust

</p> :::
G
P
Sources
