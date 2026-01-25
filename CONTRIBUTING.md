# Contributing to PGP – Applied AI & Agentic AI (IIITB)

This repo hosts **course projects** from the [IIIT Bangalore × upGrad Executive PGP in Applied AI and Agentic AI](https://www.upgrad.com/applied-ai-and-agentic-ai-executive-pgp-certification-iiitb/).

---

## Adding a New Project

1. Create a folder under `projects/`, e.g.:
   - `projects/module-rag-retrieval/`
   - `projects/capstone-a-ml-system/`
   - `projects/capstone-b-agentic-assistant/`
2. Inside that folder, add:
   - **`README.md`** – What the project does, how to run it, dependencies, and (optional) links to course module.
   - **`requirements.txt`** – Python dependencies.
   - Your code (notebooks, scripts, app, etc.).
3. Optionally add a short entry in `projects/README.md` (project index).

---

## Running a Project

- Each project has its own `README.md` and `requirements.txt`.
- Typical setup:
  ```bash
  cd projects/<project-name>
  python -m venv venv
  source venv/bin/activate   # Windows: venv\Scripts\activate
  pip install -r requirements.txt
  ```
- Follow the project-specific README for data, API keys, and run instructions.

---

## Course Context

- **Program:** [Executive PGP in Applied AI and Agentic AI (upGrad × IIITB)](https://www.upgrad.com/applied-ai-and-agentic-ai-executive-pgp-certification-iiitb/)
- **Focus:** Applied AI (ML, MLOps) + Agentic AI (LLMs, RAG, multi-agent systems, LangChain, CrewAI, etc.).

---

## Questions

Open a [GitHub Issue](https://github.com/ananttripathi/PGP-Applied-AI-Agentic-AI-IIITB/issues).
