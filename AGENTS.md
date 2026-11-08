# AGENTS.md

## Marketing agents

A team of 19 AI marketing agents lives in [`agents/`](agents/) (source: https://github.com/dottaap-star/AI_Marketing_Agents). Each agent is a plain markdown file.

- Start with `agents/README.md` and `agents/GUIDE.md`; agent-specific rules are in `agents/AGENTS.md` and `agents/CLAUDE.md`.
- Invoke an agent by typing `use <agent-name>`. Begin with `use brand-strategist`, which writes the campaign brief all other agents read.
- Suggested order: `brand-strategist`, `campaign-builder`, `landing-page`, `meta-ads`, `buyer-panel`.
- `agents/` is an independent git clone; update it with `git -C agents pull`.
