# StrategistKit — Free Skills for Claude Code

Free, production-ready [SKILL.md](https://www.agensi.io/learn/what-is-skill-md) skills for **Claude Code, Cursor, Codex CLI, Gemini CLI, OpenClaw** — and any AI coding agent that reads the open SKILL.md standard.

The three skills here are **free and MIT-licensed**. They're a taste of the full [**StrategistKit catalog**](https://strategistkit.com/?utm_source=github&utm_medium=repo&utm_campaign=free-skills) — 190+ skills for AI engineering, DevOps, testing, SEO, and consulting.

## The free skills

| Skill | What it does |
|---|---|
| [**Socratic Code Reviewer**](https://www.agensi.io/skills/socratic-code-reviewer) | Reviews your code or diff by interrogating intent, edge cases, and trade-offs — a senior reviewer's questions, not a checklist. |
| [**Systematic Bug Debugger**](https://www.agensi.io/skills/systematic-bug-debugger) | Root-cause debugging from symptoms + stack trace: reproduce, bisect, hypothesis-test — including heisenbugs and "works locally, fails in prod". |
| [**TDD Loop Master**](https://www.agensi.io/skills/tdd-loop-master) | Drives red-green-refactor: builds a test list, writes the tests first, and keeps the discipline tight. |

## Install

Each skill is a folder containing a `SKILL.md`. Drop it into `~/.claude/skills/` (personal) or your project's `.claude/skills/`:

```bash
git clone https://github.com/laki-arnsteinlarsen/strategistkit-skills.git
cp -r strategistkit-skills/systematic-bug-debugger ~/.claude/skills/
```

Your agent auto-discovers the skill from its `description` and loads it when relevant. No config required.

## More skills (190+)

- **Full catalog:** [strategistkit.com](https://strategistkit.com/?utm_source=github&utm_medium=repo&utm_campaign=free-skills)
- **On Agensi:** [agensi.io/creators/arnstein-larsen](https://www.agensi.io/creators/arnstein-larsen)
- **On PromptBase:** [promptbase.com/profile/strategistkit](https://promptbase.com/profile/strategistkit?via=strategistkit)

Highlights: RAG Failure Diagnostics & Architect, SAST Configuration Kit, API Contract Tester, AI Automation QA & UAT Pack, Local SEO Audit Pro, Multi-Agent Orchestration, and more.

## License

The three skills in this repository are released under the [MIT License](LICENSE) — use, modify, and share freely.
