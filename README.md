# LangGraph-Learning 

This repo contains notebooks and Python scripts that explore LangGraph workflows such as simple LLM workflows, RAG, persistence, tools, chatbot implementations, and more as part of a structured learning journey.

##  What is LangGraph?

LangGraph is an open-source framework used to orchestrate long-running, stateful agent workflows and multi-actor systems for language model applications. It enables you to build:
- Stateful agents,
- Complex workflow graphs,
- Durable and restartable executions,
- Human-in-the-loop steps,
- Loops and branching logic in AI task automation.

LangGraph works alongside LangChain and gives developers the building blocks to compose powerful agent workflows in Python. :contentReference[oaicite:0]{index=0}

## 📂 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `0_test_installation.ipynb` | Test environment setup & installation checks |
| `1_bmi_workflow.ipynb` | Example of workflow with simple computations |
| `2_simple_llm_workflow.ipynb` | Workflow with an LLM integration |
| `3_prompt_chaining.ipynb` | Prompt chaining with LangGraph |
| `4_batsman_workflow.ipynb` | Example workflow logic demonstration |
| `5_UPSC_essay_workflow.ipynb` | Workflow demonstrating text generation |
| `6_quadratic_equation_workflow.ipynb` | LLM workflows for calculation logic |
| `7_review_reply_workflow.ipynb` | Building a review response agent |
| `8_X_post_generator.ipynb` | Example: Social post generation workflow |
| `9_basic_chatbot.ipynb` | Simple LangGraph chatbot |
| `10_persistence.ipynb` | Working with durable states and checkpoints |
| `11_tools.ipynb` | Integrating tools in LangGraph workflows |
| `12_mcp.py` | Python script example for MCP usage |
| `13_rag.ipynb` | Retrieval Augmented Generation within LangGraph |
| `14_hitl.ipynb` | Human-in-the-Loop agent demonstration |
| `15_subgraph_shared.ipynb` | Subgraph and shared state usage |
| `chatbot_with_hitl.py` | Chatbot with interactive HITL |
| `chatbot_without_hitl.py` | Chatbot without human-in-loop |
| `intro-to-ml.pdf` | Intro ML concepts used in workflows |
| `requirements.txt` | Project dependencies |

### 🛠 Prerequisites

1. **Python 3.11+**
2. Install dependencies:

```bash
pip install -r requirements.txt
