# TechAdemy Agentic AI Course

A hands-on course that builds from Python and machine-learning foundations to the design, evaluation, and production-minded development of AI agents and retrieval-augmented systems. This workspace contains weekly learning materials, notebooks, exercises, case-study documents, and the capstone specification.

## What You Will Learn

- Use Python, pandas, and Matplotlib to inspect and analyze data.
- Build statistical intuition and understand core machine-learning and deep-learning concepts.
- Write effective prompts, manage context, and recognize prompt-injection risks.
- Distinguish reactive LLM applications from goal-oriented agents.
- Orchestrate chains and agent workflows with frameworks such as LangChain, LangGraph, and CrewAI.
- Design and improve retrieval-augmented generation (RAG) systems, including hybrid and graph-based retrieval.
- Evaluate LLM applications for quality, safety, latency, and cost.
- Apply guardrails and responsible-AI practices across an application's lifecycle.
- Translate a real-world brief into requirements, architecture, phased implementation, and acceptance checks.

## Course Roadmap

| Module | Topics | Materials |
| --- | --- | --- |
| 1. Python Basics | Data types, control flow, collections, and an introductory pandas/Matplotlib customer-data lab | `Week - 1 Python Basics/` |
| 2. Statistics for AI and ML | Descriptive statistics, distributions, outliers, correlation, and regression foundations | `Week 2 Stats & ML/` |
| 3. Machine Learning, Deep Learning, and SQL | Learning setups, training and generalization, and querying structured data | `Week 3 ML & DL/` |
| 4. Prompt Engineering and Agentic AI | Prompt design, few-shot examples, context budgets, prompt injection, reactive chatbots, and goal-oriented agents | `Week 4- Prompt-engineering-AI-Agents/` |
| 5. Agent Frameworks and Orchestration | Chains, LangChain composition, LangGraph state and control flow, CrewAI, and framework selection | `Week 5- Frameworks-RAG/` |
| 6. Retrieval-Augmented Generation | Indexing, retrieval, augmentation, common RAG failure modes, query transformation, and reranking | `Week 6- RAG/` |
| 7. Graph RAG | Knowledge graphs, entity and relationship construction, graph retrieval, and hybrid Graph RAG | `Week 7- Graph RAG/` |
| 8. LLM Evaluation and Production | Evaluation dimensions, rubrics, datasets, regression testing, deployment, cost, and latency | `Week 8- LLm Evaluation/` |
| 9. Guardrails and Responsible AI | Lifecycle risk, input controls, PII handling, output validation, and end-to-end testing | `Week 9- Guardrails/` |
| 10. Capstone | Plan and build an Enterprise Knowledge Assistant with retrieval, agents, guardrails, observability, and evaluation | `Week 10- Capstone Project/` |

## Applied Work

### Enterprise Knowledge Assistant Capstone

The capstone brief is an AI-powered assistant for enterprise knowledge. It brings together hybrid vector and graph retrieval, reranking and citations, a LangGraph workflow, layered guardrails, API delivery, observability, and evaluation. The project is organized into gated phases so each part can be implemented and verified incrementally.

Start with [`Week 10- Capstone Project/capstonespec.MD`](Week%2010-%20Capstone%20Project/capstonespec.MD), which contains the scope, architecture, decisions, and phase acceptance gates.

### FreshKart AI Support Triage Case Study

The FreshKart case study explores a different design problem: support-ticket classification and data lookup followed by deterministic, explainable business rules. Its requirements explicitly exclude RAG, vector databases, and application-level agents; the LLM classifies a ticket and drafts a reply, while Python rules control the outcome and mandatory human review.

See [`Freshkart-case Study/requirements.md`](Freshkart-case%20Study/requirements.md) and [`Freshkart-case Study/FreshKart_OpenCode_VSCode_Implementation_Playbook.md`](Freshkart-case%20Study/FreshKart_OpenCode_VSCode_Implementation_Playbook.md).

## Repository Guide

- `Week - 1 Python Basics/` through `Week 9- Guardrails/`: weekly transcripts, notebooks, and supporting exercises.
- Week 1 teaching pack: [session slides and revision](Week%20-%201%20Python%20Basics/Week%201%20-%20Session%20Slides%20and%20Revision.md), [session transcripts](Week%20-%201%20Python%20Basics/Week%201%20-%20Instructor%20Transcripts.md), [topic-wise instructor transcripts](Week%20-%201%20Python%20Basics/Week%201%20-%20Topic-wise%20Instructor%20Transcripts.md), and [assignment](Week%20-%201%20Python%20Basics/Week%201%20-%20Assignment.md).
- Week 1 notebooks: [Pandas and Matplotlib customer-data lab](Week%20-%201%20Python%20Basics/5_Pandas_Matplotlib_Customer_Data.ipynb), [customer assignment](Week%20-%201%20Python%20Basics/Week%201%20-%20Customer%20Assignment.ipynb), and [instructor answers](Week%20-%201%20Python%20Basics/Week%201%20-%20Customer%20Assignment%20Answers.ipynb). The lab uses the existing `customer_details.csv` file.
- Week 1 functions slides: [PowerPoint deck](Week%20-%201%20Python%20Basics/Week1_Functions.pptx) and [slide-ready outline](Week%20-%201%20Python%20Basics/Week%201%20-%20Functions%20Slides.md); all Week 1 decks are in the same folder.
- `Week 10- Capstone Project/`: the capstone specification and planning transcript.
- `Freshkart-case Study/`: requirements and an implementation playbook for the support-triage scenario.
- `Github Repo /`: course-related repository materials.
- `Agentoc AI Schduele.xlsx`: course schedule.
- `AI_Homework_LangChain_CrewAI_Streamlit.pdf`: supplementary homework material.

## Suggested Learning Path

1. Work through the modules in order; the early Python, statistics, ML, and SQL concepts support the later application work.
2. Follow along with the notebooks and exercises where provided, and keep the weekly transcripts as reference material.
3. Compare the two applied scenarios: FreshKart emphasizes deterministic decisions and operational safeguards, while the Enterprise Knowledge Assistant capstone emphasizes retrieval, graph data, and agent orchestration.
4. For the capstone, follow its phase prerequisites and acceptance gates rather than attempting the full system at once.

## Getting Started

Open this folder as a workspace in VS Code. Begin with the Week 1 materials and progress through the numbered modules. Notebooks may require a Python environment with the packages used in their cells; install dependencies in that environment as needed. Review each project's own requirements and instructions before running its code.
