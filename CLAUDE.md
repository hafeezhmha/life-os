# Claude entry point

This file exists so Claude Code discovers the Life OS instructions
automatically. The system is agent-agnostic: read [AGENTS.md](AGENTS.md) and
follow it, starting with its "Session start protocol".

If `.life/SETUP_NEEDED` exists, this Life OS has not been set up yet. Greet the
person, explain in two lines what this is, and offer to run the
`life-architect` skill. Do nothing else first.
