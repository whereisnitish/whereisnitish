<div align="center">

# Hi 👋, I'm Nitish Kumar

### 🐍 Python Backend Developer &nbsp;|&nbsp; 🤖 AI & Agentic Systems Developer

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Python+Backend+Developer;AI+%26+Agentic+Systems+Developer;Building+LLM-Powered+Applications;Designing+Scalable+Backend+Systems" alt="Python Backend Developer · AI and Agentic Systems Developer" />

<p>
I build backend systems and AI agents meant to run in production —
tested, containerised and guard-railed, not demo scripts.
</p>

<p>
<a href="https://github.com/whereisnitish?tab=repositories"><img src="https://img.shields.io/badge/Projects-View%20Repos-00D9FF?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
<!-- TODO: point these two at your real profile/inbox, or delete them -->
<a href="https://linkedin.com/in/your-handle"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://komarev.com/ghpvc/?username=whereisnitish&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" alt="Profile views" />
</p>

</div>

---

## 🧠 About Me

```python
class NitishKumar:
    """Python backend developer who ships AI agents that survive production."""

    def __init__(self) -> None:
        self.roles = ["Python Backend Developer", "AI & Agentic Systems Developer"]
        self.focus = "AI 🤖 × Backend Engineering ⚡ × Automation ⚙️"

    def stack(self) -> dict[str, list[str]]:
        return {
            "backend": ["Python", "FastAPI", "Django", "REST", "asyncio"],
            "ai":      ["LangGraph", "CrewAI", "MCP", "RAG", "tool calling"],
            "data":    ["PostgreSQL", "pgvector", "SQLite", "Alembic"],
            "ops":     ["Docker", "pytest", "Ruff", "GitHub Actions"],
        }

    def currently_building(self):
        yield "AI agents with human-in-the-loop guardrails"
        yield "LangGraph workflows that are tested, not just prompted"
        yield "MCP servers that expose real business tools to LLMs"

    def open_to(self, opportunity: str) -> bool:
        return opportunity in {"backend roles", "AI agent projects", "collaboration"}


if __name__ == "__main__":
    me = NitishKumar()
    print(me.focus)  # AI 🤖 × Backend Engineering ⚡ × Automation ⚙️
```

My work sits where **reliable backend engineering** meets **modern LLM capability**: agents that
call real tools against real data, validate what they produce, and refuse to act when they
shouldn't.

---

## 🚀 Featured Projects

| Project | What it does | Built with |
| :--- | :--- | :--- |
| **[AI Customer Support Agent](https://github.com/whereisnitish/AI-customer-support-agent)** | A tool-using support agent for e-commerce: retrieves policy from a vector-indexed knowledge base, remembers each customer, and validates every answer against the evidence that produced it before replying. Runs offline, no API key. | `FastAPI` `LangGraph` `RAG` `PostgreSQL + pgvector`<br/>191 tests · 91% coverage |
| **[ChatFlow AI](https://github.com/whereisnitish/chatflow-ai)** | An embeddable support widget that answers **only** from your own docs — refusal is a code path, not a prompt instruction. Live-preview dashboard, one-line install. | `FastAPI` `Next.js 15` `TypeScript` `pgvector`<br/>160 tests |
| **[MCP Business Assistant](https://github.com/whereisnitish/mcp-business-assistant)** | An agent with **no hard-coded tool list** — it discovers what it can do at runtime from five MCP servers, and can't take an irreversible action without explicit human approval. | `MCP` `LangGraph` `FastAPI` `Docker`<br/>258 tests · 84% coverage |

---

## ⚡ Tech Stack

<div align="center">

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=python,fastapi,django,docker" alt="Python, FastAPI, Django, Docker" />

`Python` · `FastAPI` · `Django` · `REST APIs` · `Async / asyncio` · `Pydantic`

**AI & Agentic Systems**

<img src="https://img.shields.io/badge/LangGraph-Agent%20Workflows-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/CrewAI-Multi--Agent-FF5A1F?style=for-the-badge" alt="CrewAI" />
<img src="https://img.shields.io/badge/MCP-Tool%20Protocol-8A2BE2?style=for-the-badge" alt="MCP" />
<img src="https://img.shields.io/badge/RAG-Retrieval-00ADD8?style=for-the-badge" alt="RAG" />

`AI Agents` · `Multi-Agent Systems` · `LangGraph` · `CrewAI` · `MCP`

`RAG` · `Prompt Engineering` · `Structured Outputs` · `Tool Calling` · `Evals`

**Data & Infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,sqlite,redis,git,github,linux" alt="PostgreSQL, SQLite, Redis, Git, GitHub, Linux" />

`PostgreSQL` · `pgvector` · `SQLite` · `Alembic` · `Docker` · `pytest` · `Ruff` · `CI/CD`

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind" alt="React, Next.js, TypeScript, Tailwind CSS" />

`React` · `Next.js` · `TypeScript` · `Tailwind CSS`

</div>

---

## 🛠️ What I Build

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AI Agent Systems

Agents that do work, not just chat.

- Agent orchestration & state machines
- Multi-agent collaboration
- Tool calling and MCP integrations
- Human-in-the-loop approval gates
- Structured, validated outputs

</td>
<td width="50%" valign="top">

### ⚡ Backend Systems

Scalable Python services with clean boundaries.

- Django & FastAPI applications
- REST API design & versioning
- Authentication and authorisation
- Async workflows and background jobs
- Third-party API integrations

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 LLM Applications

Retrieval and reasoning that hold up on real inputs.

- RAG pipelines and vector search
- Prompt engineering & context management
- Grounding, citations, refusal paths
- Cost and latency tuning
- Evaluation harnesses

</td>
<td width="50%" valign="top">

### 🚀 Production Readiness

Getting it from `localhost` to live.

- Docker & docker-compose
- Database migrations (Alembic)
- Test suites and coverage gates
- Stripe, Cloudflare, analytics
- Deployment & monitoring

</td>
</tr>
</table>

---

## 📈 GitHub Activity

<div align="center">

<!--
  WHY THESE CARDS (this is the fix for the wrong / missing stats):

  1. The old *.herokuapp.com hosts died when Heroku removed free dynos. They render
     blank or serve stale numbers. Never use them again.
  2. github-readme-stats.vercel.app — the shared public instance is rate-limited by
     GitHub and frequently returns 503, which is what makes stats "disappear" or go
     stale. If you want that card, deploy your OWN copy (free, ~5 min):
        https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance
     Then swap the host below and add &include_all_commits=true&count_private=true
     (without include_all_commits it only counts the CURRENT year — the usual reason
     the commit total looks far too low).
  3. The cards below are on hosts verified to respond, and read GitHub's own
     contribution calendar — so they only count work GitHub counts: commits on a
     repo's default branch, authored with an email verified on your account.
     If your numbers look low, check `git config user.email` matches a verified
     email in https://github.com/settings/emails.
  4. "Top Languages by Repo" is used instead of "by commit" on purpose: the by-commit
     version is byte-weighted, so one Jupyter notebook (outputs and all) outranks
     every Python service you own.
  5. utcOffset=5.5 -> IST. Change it if you move.
-->

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=whereisnitish&theme=tokyonight" alt="GitHub profile summary" />

<br/>

<img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=whereisnitish&theme=tokyonight" alt="Top languages by repository" />
<img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=whereisnitish&theme=tokyonight&utcOffset=5.5" alt="Most productive hours" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=whereisnitish&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&card_width=495" alt="GitHub streak" />

</div>

> **On the numbers:** language cards measure **code volume**, not time or skill — generated
> files and notebooks skew them. Treat these as a pulse, and the
> [projects above](#-featured-projects) as the actual work.

---

## 🤝 Let's Connect

I'm always up for talking to:

- 🚀 **Founders building AI products**
- 🤖 **Teams working on agentic AI systems**
- 🐍 **Python & backend developers**
- 🧠 **Anyone building something genuinely interesting with LLMs**

**Easiest way to reach me:** open an issue on any repo, or use the links at the top.

---

<div align="center">

### 💬 Let's build something intelligent.

**Python 🐍 · AI 🤖 · Agents ⚙️ · Backend 🚀**

⭐ If something here is useful to you, a star helps other people find it.

</div>
