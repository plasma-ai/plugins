# plugins

[![license](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)

Plugin marketplaces for [Plasma AI](https://github.com/plasma-ai). Agent skills
for Claude Code and Codex with CLIs published to PyPI.

| Plugin    | Package          | Description                                                 |
| --------- | ---------------- | ----------------------------------------------------------- |
| `wiki`    | `plasma-wiki`    | Indexed knowledge bases with command-line tools for agents. |
| `fractal` | `plasma-fractal` | Hierarchical agent loops with recursive self-organization.  |

## Claude Code

```bash
/plugin marketplace add plasma-ai/plugins
/plugin install wiki@plasma
/plugin install fractal@plasma
```

## Codex

```bash
codex plugin marketplace add plasma-ai/plugins
codex plugin add wiki@plasma
codex plugin add fractal@plasma
```

## Without a marketplace

The skills can also be installed from their CLIs, which copy them into
`~/.claude/skills` and `~/.agents/skills`:

```bash
pipx install plasma-wiki && wiki install
pipx install plasma-fractal && fractal install
```

Or if `uv` is installed:

```bash
uv tool install plasma-wiki && wiki install
uv tool install plasma-fractal && fractal install
```

## License

Licensed under the Apache License 2.0 — see [LICENSE](LICENSE).

Copyright © 2026 Plasma AI
