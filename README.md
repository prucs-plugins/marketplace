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
| [reddit-business-research](#reddit-business-research) | Research what Reddit says about your business, competitors, and market | [prucs-plugins/reddit-business-research](https://github.com/prucs-plugins/reddit-business-research) |
| [idea-research](#idea-research) | Business research, market analysis, and idea validation | [prucs-plugins/claude-code-plugins](https://github.com/prucs-plugins/claude-code-plugins) |
| [project-optimizer](#project-optimizer) | Generate project.md, brand.md, and CLAUDE.md for any project | [prucs-plugins/claude-code-plugins](https://github.com/prucs-plugins/claude-code-plugins) |

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

---

## Attribution

The `idea-research` and `project-optimizer` plugins under [prucs-plugins/claude-code-plugins](https://github.com/prucs-plugins/claude-code-plugins) are forked from the original work by **[Anilcan Cakir](https://github.com/anilcancakir)** ([anilcancakir/claude-code-plugins](https://github.com/anilcancakir/claude-code-plugins)). Full credit goes to the original author. If you find these plugins useful, please consider starring the original repo.

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

---

### reddit-business-research

Find out what Reddit really thinks about your business, your competitors, and your market. No API keys required.

```
/plugin install reddit-business-research
```

---

### idea-research

Comprehensive business research, market analysis, competitor intelligence, and idea validation with TAM/SAM/SOM, Porter's Five Forces, and SWOT analysis.

> Originally by [Anilcan Cakir](https://github.com/anilcancakir)

```
/plugin install idea-research
```

---

### project-optimizer

Create project.md (PRD), brand.md (brand guidelines), and CLAUDE.md (technical config) for any project. Interactive workflow with archetype-based branding.

> Originally by [Anilcan Cakir](https://github.com/anilcancakir)

```
/plugin install project-optimizer
```
