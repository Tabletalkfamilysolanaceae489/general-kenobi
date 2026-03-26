# general-kenobi

An agent skill that responds to "Hello there" with "General Kenobi."

That's it. That's the skill.

Compatible with any agent that supports the [Agent Skills](https://agentskills.io) standard: Claude Code, Codex CLI, Gemini CLI, Cursor, and more.

## Installation

**Any agent (Claude Code, Codex, Cursor, Gemini CLI, and more):**
```bash
npx skills add antonkarliner/general-kenobi
```

**Claude Code plugin:**
```
/plugin marketplace add antonkarliner/general-kenobi
```

**Manual:**
```bash
cp -r general-kenobi ~/.claude/skills/
# or ~/.codex/skills/, ~/.gemini/skills/, etc.
```

## Usage

Say `Hello there` to your agent. Receive `General Kenobi.`

## License

MIT
