# AI Agents: Zero to Production

An interactive, single-page guide to building AI agents — from first principles to production deployment. Built as a self-contained HTML site with a chapter sidebar, progress tracker, and full code examples throughout.

**[Live demo →](https://ai-agent-web-xi.vercel.app)**

## What's covered

15 chapters across 5 sections:

**Foundations**
- What is an AI Agent?
- The Agent Loop
- LLMs as the Brain

**Core Capabilities**
- Tools & Function Calling
- Memory Systems
- Planning & Reasoning

**Architecture**
- Agent Patterns
- Multi-Agent Systems
- RAG & Knowledge

**Building**
- Build from Scratch
- Frameworks Deep Dive (LangChain, LangGraph, CrewAI)
- Evaluation & Testing

**Production**
- Reliability & Safety
- Observability
- Cost & Scaling

Each chapter includes working code examples (mostly Python, using the Anthropic API), architecture diagrams, and comparison tables — not just theory.

## Tech

Pure HTML/CSS/JS — no build step, no framework, no dependencies. One `index.html` file. Deployed on Vercel.

## Running locally

Clone the repo and open `index.html` in a browser. That's it.

```bash
git clone https://github.com/tathagat-git/ai-agent-web.git
cd ai-agent-web
open index.html
```

## Why this exists

Most agent tutorials are scattered across blog posts and docs. This pulls the full picture — loop design, memory, RAG, multi-agent orchestration, framework tradeoffs, and what actually breaks in production — into one structured, readable reference.
