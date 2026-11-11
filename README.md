# Persistent Agents on Claude Code

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23787644.svg)](https://doi.org/10.5281/zenodo.23787644)

Part of **Working Agents**, a living series of working papers on operating AI agents and agent software development: [the plan and index](https://daveremy.github.io/working-agents/) · [all papers on Zenodo](https://zenodo.org/communities/working-agents).

A working note on running always-on personal agents with Claude Code alone: nine named agents,
each an ordinary `claude --agent` session in a tmux window, kept alive by systemd and reachable
through its own Telegram bot. There is no agent framework between the person and Claude Code.

**Read it:** [web](https://daveremy.github.io/persistent-agents/) · [PDF](docs/persistent-agents.pdf) · [source](docs/index.html)

**Short on time?** [Deck PDF, 14 slides](docs/persistent-agents-deck.pdf)
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
agents run sprints.

## Versions

- 1.3, 11 November 2026: the chief-of-staff agent runs Haiku 5.5; session transcripts were deleted after 30 days until 10 November 2026; counts of skills, hooks and login sites dated; other changed facts corrected (sprint length, tmux windows, job and timer count dates, in-session scheduled tasks, handoff documents, the cloud-credit grant, the Claude Duet entry); American spelling.
- 1.2, 30 October 2026: Claude Code Projects added to the comparison.
- 1.1, 30 October 2026: in-session scheduled tasks survive a resume; Claude Code's newer scheduling options covered.
- 1.0, 30 October 2026: first release.

## License

Text and figures: [CC BY 4.0](LICENSE). Written by Dave Remy, in collaboration with AI.
