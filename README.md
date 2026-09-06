# Graham Brooks

I build tools that improve how engineers understand, maintain, and ship software systems.

My work focuses on developer productivity, architecture visibility, and AI-assisted workflows — from static analysis and refactoring DSLs to MCP tooling and code intelligence. Most of it is written in Rust, ships as a single binary with no runtime to install, and is designed to be equally usable by a person at a terminal and by a coding agent.

---

## Architecture & Modelling

Describe a system once, then keep the description honest.

| Project | |
| --- | --- |
| [forge](https://github.com/grahambrooks/forge) | A unified software modeling DSL and toolchain. Describe structure, processes, deployment, and data in a single `.forge` file, then render diagrams, generate documentation sites, and lint architecture. |
| [tropism](https://github.com/grahambrooks/tropism) | Dependency-rule enforcement across ten languages, read from manifests and source as text — no building, installing, or resolving. Runs as a pre-commit hook. |
| [bsv](https://github.com/grahambrooks/bsv) · [bsdoc](https://github.com/grahambrooks/bsdoc) | Backstage tooling — a catalog visualizer, and a Go CLI that generates detailed Backstage catalog documentation. |
| [codecity](https://github.com/grahambrooks/codecity) · [rv](https://github.com/grahambrooks/rv) | Multi-repository code visualization as a 3D city, and force-directed SVG graphs of directory structure. |

## Code Intelligence & Analysis

Understanding large codebases, and changing them safely.

| Project | |
| --- | --- |
| [symgraph](https://github.com/grahambrooks/symgraph) | Semantic code intelligence MCP server that builds knowledge graphs of codebases to improve AI-assisted code exploration. |
| [casual-review](https://github.com/grahambrooks/casual-review) | Ultra-fast code review CLI bringing rustc-quality diagnostics to other languages, on a workstation or in CI, readable by humans and LLM agents alike. |
| [colab](https://github.com/grahambrooks/colab) | Rule-driven syntactic refactoring across a repository, with a CLI and an MCP server over one core. |
| [refactor-dsl](https://github.com/grahambrooks/refactor-dsl) | A DSL for multi-language refactoring applied across many git and GitHub projects at once. |
| [brake](https://github.com/grahambrooks/brake) | A brake on breaking API changes — compares an API contract against its previous version and fails the commit when the change would break a consumer, across OpenAPI, protobuf, and GraphQL. |
| [astgen](https://github.com/grahambrooks/astgen) · [fingerprint-rs](https://github.com/grahambrooks/fingerprint-rs) · [xpa](https://github.com/grahambrooks/xpa) | AST extraction for project source, winnowing document fingerprinting with Jaccard similarity, and static analysis of XPath expressions. |

## AI-Native Development

Infrastructure for working alongside coding agents.

| Project | |
| --- | --- |
| [ai-dev-container](https://github.com/grahambrooks/ai-dev-container) | `devc` creates isolated, sandboxed Docker containers for AI coding agents (Claude Code, Codex, Gemini CLI, Opencode) with a consistent local and remote developer experience. |
| [bx](https://github.com/grahambrooks/bx) | The missing primitive for running local binary STDIO MCP servers — `npx`/`uvx`/`pipx` ergonomics without a Node or Python runtime. |
| [mcp-dep](https://github.com/grahambrooks/mcp-dep) | Worked example of building and publishing a binary MCP server as an MCP Bundle. |
| [gb-agent-skills](https://github.com/grahambrooks/gb-agent-skills) | Claude Code plugins and skills. |
| [genie](https://github.com/grahambrooks/genie) | CLI chat app showing how to interact with GenAI backends. |

## Documents & Diagrams as Code

| Project | |
| --- | --- |
| [adoc](https://github.com/grahambrooks/adoc) | AsciiDoc CLI targeting the AsciiDoc Language specification rather than Asciidoctor behaviour. |
| [puml](https://github.com/grahambrooks/puml) | An alternative PlantUML rendering tool. |
| [mermaid-adr](https://github.com/grahambrooks/mermaid-adr) | Example architecture decision records that carry Mermaid.js diagrams. |

## Developer Experience

Everyday tools for the terminal and the desktop.

| Project | |
| --- | --- |
| [gitatlas](https://github.com/grahambrooks/gitatlas) · [gitatlas-cli](https://github.com/grahambrooks/gitatlas-cli) | Desktop app and CLI for developers working across many repositories — scans the filesystem, discovers every repo, and shows their status on one dashboard. |
| [increment](https://github.com/grahambrooks/increment) | A terminal diff visualizer with aligned side-by-side panes, word-level highlighting, folded context, move detection, and a commit-by-commit branch browser. |
| [facts](https://github.com/grahambrooks/facts) | A Rust testing library inspired by Clojure's Midje — assertions read left-to-right, actual → expected. |
| [cic](https://github.com/grahambrooks/cic) | Continuous integration console reporting — build status at the command line. |
| [adaptive-limiting](https://github.com/grahambrooks/adaptive-limiting) | A worked example of adaptive rate limiting. |

## Long-Lived Reference Projects

Older work that people still find useful.

| Project | |
| --- | --- |
| [accounting-pattern](https://github.com/grahambrooks/accounting-pattern) | Java implementation of Martin Fowler's accounting patterns. |
| [intercept](https://github.com/grahambrooks/intercept) | An HTTP proxy library for testing web applications by intercepting client traffic. |
| [circuit-breaker](https://github.com/grahambrooks/circuit-breaker) | An implementation of the Circuit Breaker pattern in Scala. |
| [zero-down](https://github.com/grahambrooks/zero-down) | Migrating a database with zero downtime for the dependent application during a deploy. |
| [metamorph](https://github.com/grahambrooks/metamorph) | Programmatic morphing and analysis of Java source code. |
| [jx](https://github.com/grahambrooks/jx) | Think `jq` formatting, for XML. |

---

## Technical Focus

- **Primary languages:** Rust, Go, TypeScript, JavaScript
- **Also worked with:** Java, Kotlin, Ruby, C++, Scala, Swift, Python
- **Domains:** static analysis, refactoring systems, architecture modelling, documentation generation, developer UX, CI-aware tooling, MCP servers

## Engineering Principles

- Build practical tools that teams can adopt quickly
- Ship single binaries — no runtime to install before the tool is useful
- Keep systems observable, automatable, and composable
- Optimize for clarity — in APIs, architecture, and developer workflows
- Make output legible to humans and agents alike

---

## Connect

- GitHub: [@grahambrooks](https://github.com/grahambrooks) — [all repositories](https://github.com/grahambrooks?tab=repositories)
