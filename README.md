# TechAdemy Agentic AI Engineering Program

A hands-on program that builds from Python foundations to practical AI application development. Learners progress from writing and debugging Python to calling language models, composing agent workflows, building retrieval-augmented generation (RAG) applications, and evaluating and safeguarding AI systems.

This repository contains the course schedule, released teaching materials, Python notebooks, exercises, and course artifacts. Additional module materials will be added as they are prepared.

## Program at a Glance

- **20 technical sessions** across **10 weekends**
- **3 hours per technical session**
- Starts with Python; no prior agent framework experience is assumed
- A practical progression through LLM APIs, LangChain, LangGraph, CrewAI, RAG, evaluation, guardrails, and MCP
- Final two sessions reserved for a focused capstone; the cohort will select the final problem later in the program

## Learning Outcomes

By the end of the program, learners will be able to:

- Use core Python constructs, collections, functions, files, modules, packages, and JSON in AI application code.
- Set up a Python environment and run, inspect, and debug Jupyter notebooks in VS Code.
- Explain key LLM concepts, including tokens, context windows, embeddings, and prompting.
- Call model APIs, manage credentials safely, tune request parameters, handle errors, and consume streamed responses.
- Compose model, prompt, parser, tool, and agent workflows with LangChain.
- Model multi-step workflows with LangGraph state, nodes, edges, routing, checkpoints, and human approval.
- Build and compare multi-agent workflows with CrewAI.
- Implement a RAG flow from document ingestion and chunking through embeddings, indexing, retrieval, and answer generation.
- Recognize when advanced patterns such as Self-RAG, Corrective RAG, or Graph RAG may help.
- Test AI application quality with curated datasets, LLM-as-judge, RAGAS measures, tracing, and regression checks.
- Apply input and output validation, prompt-injection defenses, privacy and safety filters, and fallbacks.
- Use AI coding assistants and connect tools through skills and MCP.
- Scope, build, test, and present a small AI application as a team capstone.

## Curriculum Roadmap

| Module | Sessions | Schedule | Focus |
| --- | ---: | --- | --- |
| Python for AI | 1–3 | Nov 21, 22, 28, 2026 | Setup, variables, data types, strings, operators, conditions, loops, functions, collections, comprehensions, files, OOP basics, modules, packages, error handling, virtual environments, pip, and JSON |
| LLM Foundations, API Calling, and VS Code | 4–6 | Nov 29, Dec 5–6, 2026 | LLMs, tokens, context windows, conceptual embeddings, model families, prompting, REST and SDK calls, API keys and `.env`, parameters, streaming, errors, Jupyter, kernels, and debugging |
| LangChain | 7–8 | Dec 12–13, 2026 | Models, prompt templates, output parsers, chains, LCEL, runnables, tools, agents, memory, document loaders, text splitters, and tracing basics |
| LangGraph and Pydantic | 9–10 | Dec 19–20, 2026 | Graphs, nodes, edges, state, conditional routing, typed state and outputs, tool-calling agents, checkpoints, memory, human-in-the-loop, multi-step workflows, and streaming |
| CrewAI | 11 | Jan 9, 2027 | Agents, tasks, crews, roles, goals, sequential and hierarchical processes, tools, collaboration, and framework comparison |
| RAG and Advanced RAG | 12–14 | Jan 10, 16–17, 2027 | Ingestion, chunking, embeddings, FAISS/ChromaDB, indexing, similarity search, metadata filters, prompt augmentation, end-to-end RAG, basic reranking, Self-RAG, Corrective RAG, and Graph RAG |
| Evals and Guardrails | 15–16 | Jan 23–24, 2027 | LLM-as-judge, RAGAS, test sets, regression testing, tracing, validation, prompt-injection defense, PII and safety filters, guardrail frameworks, and fallbacks |
| Efficient Coding, Skills, Connections, and MCP | 17–18 | Jan 30–31, 2027 | AI coding assistants in VS Code, Claude Code workflow, project context, prompts and commands, skills, tool connections, MCP servers and clients, and a custom integration |
| Capstone | 19–20 | Feb 6–7, 2027 | Scope and requirements, architecture, core implementation, integration, evaluation, guardrails, demo, and feedback |

The complete session-by-session schedule, including the detailed topic descriptions, is in [`0_NonTeaching_Artifacts/Agentic_AI_Schedule_Nov2026.xlsx`](0_NonTeaching_Artifacts/Agentic_AI_Schedule_Nov2026.xlsx).

## Class Format

Each technical session is three hours. The planned teaching rhythm is a short concept segment followed by a dedicated doubt-clearing break, repeated through the class and paired with notebook or lab practice. The schedule describes roughly 20–25 minutes of topic delivery followed by 10–15 minutes for questions. The balance of explanation and hands-on work varies by module.

Learning materials include revision slides, Python notebooks, assignments, and capstone work. Use the notebooks to rerun examples, vary inputs, and inspect how the result changes.

## Capstone

The final project is intentionally open for now. The cohort will choose a problem later, after exploring the course topics and identifying useful applications. One candidate is a focused policy and SOP question-answering assistant that retrieves from a small document set, cites sources, and is tested with a compact evaluation set and basic guardrails. The final scope should fit the two scheduled capstone sessions; a production deployment is out of scope.


## Getting Started

1. Clone or download this repository and open it in VS Code.
2. Set up a Python environment and install the dependencies needed for the notebook or module you are working on. The root `requirements.txt` lists packages used across the program; some later modules may require only a subset.
3. Start with the Python notebooks in `1_PythonBasics/NBs/` and use the matching slides and assignment as companion material.
4. Refer to the schedule for the planned sequence and dates. Check each module's instructions before running its code, especially where API keys or external services are involved.

## Course Links

- [GitHub repository](https://github.com/capchitts/agentic_ai_Nov_2026)
- [Shared Google Drive folder](https://drive.google.com/drive/folders/1k5R297oLmtIeWfTkQrueE72qwd5ku4XC?usp=drive_link)
