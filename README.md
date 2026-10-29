# Persistent Agents on Claude Code

A working note on running always-on personal agents with Claude Code alone: nine named agents,
each an ordinary `claude --agent` session in a tmux window, kept alive by systemd and reachable
through its own Telegram bot. There is no agent framework between the person and Claude Code.

**Read it:** [web](https://daveremy.github.io/persistent-agents/) · [PDF](docs/persistent-agents.pdf) · [source](docs/index.html)
· 30 October 2026

## What it covers

Why build it; the hardware; each of the nine agents (chief of staff, health, finance,
communications, engineering, operations, customer support, research, marketing); the
infrastructure we had to add (session continuity across restarts, scheduled jobs, routing between
agents, memory, models and budget, safety gates); Telegram and remote work; what went wrong; and
how it compares with the hosted persistent agents released in the second half of 2026.

## What this is, and is not

A description of one working system, offered so other engineers who already use Claude Code can
try the approach. It is not a product or a framework, and there is nothing to install. Questions,
corrections and accounts of your own setup are welcome as issues.

Companion paper: [Agent Scrum](https://daveremy.github.io/agent-scrum/), on how the engineering
agents run two-hour sprints.

## License

Text and figures: [CC BY 4.0](LICENSE). Written by Dave Remy, in collaboration with AI.
