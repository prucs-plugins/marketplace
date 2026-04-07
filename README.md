# prucs-plugins Marketplace

Official Claude Code plugin marketplace for the [prucs-plugins](https://github.com/prucs-plugins) org.

## Install

```
/plugin marketplace add prucs-plugins/marketplace
```

Then install any plugin:

```
/plugin install <plugin-name>
```

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| [gameplay-editor](#gameplay-editor) | Transform gameplay recordings into highlight reels using AI audio analysis | [prucs-plugins/gameplay-editor](https://github.com/prucs-plugins/gameplay-editor) |
| [coconuti](#coconuti) | AI-powered investment research, prediction, and portfolio management | [prucs-plugins/claude-plugin-trader](https://github.com/prucs-plugins/claude-plugin-trader) |
| [research-mode](#research-mode) | Anti-hallucination toggle - enforces citation requirements and source grounding | [prucs-plugins/research-mode](https://github.com/prucs-plugins/research-mode) |

---

## My Active Plugins

Plugins I use daily, ranked by global install count.

| # | Plugin | Installs | Marketplace | What it does |
|---|--------|----------|-------------|--------------|
| 1 | **frontend-design** | 455,628 | official | Production-grade UI generation with high design quality |
| 2 | **superpowers** | 355,657 | official | Planning, TDD, debugging, brainstorming, code review workflows |
| 3 | **context7** | 231,346 | official | Live documentation lookup via MCP — prevents hallucinated APIs |
| 4 | **code-review** | 212,871 | official | Automated code review for bugs, style, and conventions |
| 5 | **code-simplifier** | 178,204 | official | Refactors code for clarity and maintainability |
| 6 | **feature-dev** | 155,235 | official | Guided feature development with codebase exploration |
| 7 | **playwright** | 150,132 | official | Browser automation and end-to-end testing via MCP |
| 8 | **skill-creator** | 131,592 | official | Create, modify, and benchmark custom skills |
| 9 | **claude-md-management** | 125,973 | official | Audit and improve CLAUDE.md files |
| 10 | **security-guidance** | 107,637 | official | Security best practices and vulnerability prevention |
| 11 | **commit-commands** | 102,020 | official | `/commit`, `/commit-push-pr`, branch cleanup |
| 12 | **pr-review-toolkit** | 68,342 | official | Deep PR analysis — silent failures, type design, test coverage |
| 13 | **claude-mem** | — | [thedotmack](https://github.com/thedotmack/claude-mem) | Cross-session persistent memory with timeline and plan execution |

## Other Tools

Non-plugin tools I use with Claude Code.

| Tool | Type | What it does | Source |
|------|------|--------------|--------|
| **ccstatusline** | npm package | Customizable status line formatter for the Claude Code CLI | [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) |

### ccstatusline config

Widgets: model, context length, context %, session cost, git repo, git modified lines.

```bash
npm install --prefix ~/.local ccstatusline
```

Add to `~/.claude/settings.json`:

```json
{
  "statusLine": {
    "type": "command",
    "command": "~/.local/node_modules/.bin/ccstatusline",
    "padding": 0
  }
}
```

`~/.config/ccstatusline/settings.json`:

```json
{
  "version": 3,
  "lines": [
    [
      { "id": "1", "type": "model", "color": "cyan" },
      { "id": "2", "type": "separator" },
      { "id": "3", "type": "context-length", "color": "brightBlack" },
      { "id": "4", "type": "separator" },
      { "id": "5", "type": "context-percent", "color": "brightBlack" },
      { "id": "6", "type": "separator" },
      { "id": "7", "type": "session-cost", "color": "green" },
      { "id": "8", "type": "separator" },
      { "id": "9", "type": "git-root-dir", "color": "magenta" },
      { "id": "10", "type": "separator" },
      { "id": "11", "type": "git-changes", "color": "yellow" }
    ]
  ],
  "flexMode": "full-minus-40",
  "colorLevel": 2
}
```

---

### gameplay-editor

Transform long gameplay recordings into highlight reels and short-form clips using AI-powered audio analysis and transcript understanding.

```
/plugin install gameplay-editor
```

---

### coconuti

AI-powered investment research, prediction, and portfolio management with multi-agent DAG pipeline architecture and intelligent delegation framework.

```
/plugin install coconuti
```

---

### research-mode

Anti-hallucination toggle for Claude Code. Activates constraints that force Claude to cite sources, say "I don't know" when unsure, and ground responses in direct quotes.

```
/plugin install research-mode
```
