# rags-to-agents

Learning journal for an AI engineering course — covers RAG (Retrieval-Augmented Generation) through to building agents. Contains follow-along notebooks, personal notes, and homework assignments.

## Project structure

```
lectures/       # Follow-along notebooks from course lessons
notes/          # Personal notes and summaries
assignments/    # Homework and projects
```

## Setup

Requires Python 3.10+ and [uv](https://github.com/astral-sh/uv).

```bash
# Install dependencies
uv sync

# Launch Jupyter
uv run jupyter lab
```

Copy `.env.example` to `.env` and add your API keys:

```
OPENAI_API_KEY=your-key-here
```
