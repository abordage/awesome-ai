# Awesome AI

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-ai?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-ai)](LICENSE)

**Automated. Curated. Ranked.**

AI and machine learning projects hosted on GitHub. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

> Looking for MCP servers? Check out [Awesome MCP](https://github.com/abordage/awesome-mcp) — a curated list of Model Context Protocol servers, clients, and frameworks.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI Coding Agents](#ai-coding-agents)
  - [General Purpose](#general-purpose)
  - [Claude Code](#claude-code)
  - [Gemini CLI](#gemini-cli)
  - [PR & Review](#pr--review)
- [IDE & Editor](#ide--editor)
  - [Extensions](#extensions)
  - [Neovim](#neovim)
  - [Emacs](#emacs)
- [CLI Assistants](#cli-assistants)
- [Generators](#generators)
  - [App](#app)
  - [UI](#ui)
- [SDKs & Libraries](#sdks--libraries)
  - [Go](#go)
  - [PHP & Laravel](#php--laravel)
- [Documentation](#documentation)
- [Testing](#testing)
- [Other](#other)


## AI Coding Agents

### General Purpose

- [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) — Run local LLMs on any device ☆`76,986`
- [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) — Chat with documents using LLMs ☆`56,925`
- [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer) — CLI platform to experiment with codegen ☆`55,143`
- [Aider-AI/aider](https://github.com/Aider-AI/aider) — aider is AI pair programming in your terminal ☆`39,181`
- [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr) — RAG for GenAI in apps ☆`38,711`
- [mckaywrigley/chatbot-ui](https://github.com/mckaywrigley/chatbot-ui) — AI chat for any model. ☆`32,858`
- [plandex-ai/plandex](https://github.com/plandex-ai/plandex) — AI coding agent for large projects ☆`14,784`
- [smol-ai/developer](https://github.com/smol-ai/developer) — Embed a developer agent in apps ☆`12,195`
- [joshpxyne/gpt-migrate](https://github.com/joshpxyne/gpt-migrate) — Migrate codebase between frameworks ☆`6,995`
- [kuafuai/DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — Multi-agent AI-driven development ☆`5,966`
- [stravu/crystal](https://github.com/stravu/crystal) — Run multiple AI sessions in parallel ☆`2,629`
- [melih-unsal/DemoGPT](https://github.com/melih-unsal/DemoGPT) — Create LLM agents with tools ☆`1,881`
- [splx-ai/agentic-radar](https://github.com/splx-ai/agentic-radar) — A security scanner for your LLM agentic workflows ☆`849`
- [Nayjest/Gito](https://github.com/Nayjest/Gito) — AI-powered GitHub code review ☆`81`
- [seahyinghang8/blinky](https://github.com/seahyinghang8/blinky) — An open-source debugging agent in VSCode ☆`81`
- [Strawberry-Computer/vibe-compiler](https://github.com/Strawberry-Computer/vibe-compiler) — RAG for integrating GenAI in apps ☆`52`
### Claude Code

- [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) — Configuration framework for Claude Code ☆`19,452`
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) — CLI tool for configuring and monitoring Claude Code ☆`13,671`
- [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts) — Quick start projects for Claude ☆`12,787`
- [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow) — Agent orchestration for Claude ☆`10,851`
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) — Analyze Claude Code usage stats ☆`9,386`
- [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) — Claude Code usage monitor ☆`5,982`
- [automazeio/ccpm](https://github.com/automazeio/ccpm) — Project management for Claude Code ☆`5,712`
- [slopus/happy](https://github.com/slopus/happy) — Mobile/Web client for Codex and Claude ☆`5,635`
- [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) — Manage multiple AI terminal agents ☆`5,396`
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) — Claude Code action for GitHub PRs ☆`4,436`
- [OneRedOak/claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows) — Best workflows for Claude Code ☆`3,326`
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) — Custom statusline for Claude Code ☆`2,463`
- [nizos/tdd-guard](https://github.com/nizos/tdd-guard) — Automated TDD enforcement for Claude Code ☆`1,617`
- [parruda/swarm](https://github.com/parruda/swarm) — Ruby gems for general-purpose AI agent systems: automation, research, data processing, customer support, content creation. SwarmSDK provides single-process orchestration, persistent memory with semantic search, node workflows, and hooks. SwarmMemory/SwarmCLI included. Claude Swarm v1 for dev teams. ☆`1,542`
- [Piebald-AI/tweakcc](https://github.com/Piebald-AI/tweakcc) — Customize Claude Code prompts ☆`643`
- [Owloops/claude-powerline](https://github.com/Owloops/claude-powerline) — Beautiful vim-style powerline statusline for Claude Code ☆`623`
- [pchalasani/claude-code-tools](https://github.com/pchalasani/claude-code-tools) — Productivity tools for Claude Code ☆`584`
- [Helmi/claude-simone](https://github.com/Helmi/claude-simone) — Project management for AI dev ☆`521`
- [carlrannaberg/claudekit](https://github.com/carlrannaberg/claudekit) — Custom commands and hooks for Claude ☆`498`
- [claude-did-this/claude-hub](https://github.com/claude-did-this/claude-hub) — Webhook service for Claude + GitHub ☆`311`
- [johnlindquist/claude-hooks](https://github.com/johnlindquist/claude-hooks) —  ☆`249`
- [nyatinte/ccexp](https://github.com/nyatinte/ccexp) — Terminal interface for Claude extensions ☆`228`
- [JSONbored/claudepro-directory](https://github.com/JSONbored/claudepro-directory) — Searchable Claude Pro project collection ☆`151`
- [bartolli/claude-code-typescript-hooks](https://github.com/bartolli/claude-code-typescript-hooks) —  ☆`149`
- [dazuiba/CCNotify](https://github.com/dazuiba/CCNotify) — Desktop notifications for Claude Code ☆`131`
- [dtormoen/tsk](https://github.com/dtormoen/tsk) — Task manager and sandbox for coding agents ☆`111`
- [ayoubben18/ab-method](https://github.com/ayoubben18/ab-method) — AI-powered software development ☆`111`
- [GowayLee/cchooks](https://github.com/GowayLee/cchooks) — A Python SDK for claude-code hooks ☆`101`
- [eckardt/cchistory](https://github.com/eckardt/cchistory) — Like the shell history command but for your Claude Code sessions. ☆`85`
- [sculptdotfun/viberank](https://github.com/sculptdotfun/viberank) — claude code leaderboard ☆`80`
- [beyondcode/claude-hooks-sdk](https://github.com/beyondcode/claude-hooks-sdk) — A PHP SDK for building Claude Code hooks ☆`57`
- [icanhasjonas/run-claude-docker](https://github.com/icanhasjonas/run-claude-docker) — Run claude code in somewhat safe and isolated yolo mode ☆`54`
- [Brads3290/cclogviewer](https://github.com/Brads3290/cclogviewer) — Review Claude Code .jsonl files with a nice HTML UI ☆`55`
- [Veraticus/cc-tools](https://github.com/Veraticus/cc-tools) — Claude Code tools ☆`38`
- [viveknair/ccoutputstyles](https://github.com/viveknair/ccoutputstyles) — Customize Claude Code output styles ☆`50`
### Gemini CLI

- [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) — AI agent with Gemini in terminal ☆`88,571`
- [google-gemini/cookbook](https://github.com/google-gemini/cookbook) — Examples and guides for using the Gemini API ☆`15,966`
- [google-github-actions/run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli) — A GitHub Action invoking the Gemini CLI. ☆`1,628`
- [GewoonJaap/gemini-cli-openai](https://github.com/GewoonJaap/gemini-cli-openai) — Gemini CLI as OpenAI API endpoint ☆`780`
- [gzzhongqi/geminicli2api](https://github.com/gzzhongqi/geminicli2api) —  ☆`432`
- [clduab11/gemini-flow](https://github.com/clduab11/gemini-flow) — Claude-Flow for Gemini CLI ☆`280`
- [Piebald-AI/gemini-cli-desktop](https://github.com/Piebald-AI/gemini-cli-desktop) — Web/desktop UI for Gemini CLI/Qwen Code. Manage projects, switch between tools, search across past conversations, and manage MCP servers, all from one multilingual interface, locally or remotely. ☆`130`
- [Theopsguide/gemini-code-flow](https://github.com/Theopsguide/gemini-code-flow) — AI dev orchestration for Gemini CLI ☆`134`
- [amitkmaraj/gemini-cli-custom-slash-commands](https://github.com/amitkmaraj/gemini-cli-custom-slash-commands) — Custom slash commands for Gemini CLI ☆`130`
- [nettee/gemini-cli-proxy](https://github.com/nettee/gemini-cli-proxy) — Gemini CLI as OpenAI-compatible API ☆`127`
- [openmule/gacua](https://github.com/openmule/gacua) — Out-of-the-box computer use agent ☆`111`
- [Brioch/gemini-openai-proxy](https://github.com/Brioch/gemini-openai-proxy) — Serve Gemini models via OpenAI API ☆`44`
- [Jasonzhangf/gemini-cli-router](https://github.com/Jasonzhangf/gemini-cli-router) — routing your gemini-cli to openai 3rd party providers ☆`19`
- [automateyournetwork/GeminiCLI_Slash_Listen](https://github.com/automateyournetwork/GeminiCLI_Slash_Listen) — A /listen feature for Gemini CLI ☆`16`
### PR & Review

- [qodo-ai/pr-agent](https://github.com/qodo-ai/pr-agent) — AI-powered PR reviewer ☆`9,685`
- [sweepai/sweep](https://github.com/sweepai/sweep) — Sweep: AI coding assistant for JetBrains ☆`7,622`
- [mattzcarey/shippie](https://github.com/mattzcarey/shippie) — extendable code review and QA agent ☆`2,311`
- [Yuyz0112/dewhale](https://github.com/Yuyz0112/dewhale) — GitHub-powered AI development ☆`1,545`
## IDE & Editor

### Extensions

- [codota/TabNine](https://github.com/codota/TabNine) — AI Code Completions ☆`10,814`
- [smallcloudai/refact](https://github.com/smallcloudai/refact) — AI agent for engineering tasks ☆`3,420`
- [lgrammel/rubberduck-vscode](https://github.com/lgrammel/rubberduck-vscode) — Use AI-powered code edits, explanations, code generation, error diagnosis, and chat in Visual Studio Code with the official OpenAI API. ☆`630`
### Neovim

- [greggh/claude-code.nvim](https://github.com/greggh/claude-code.nvim) — Claude Code integration for Neovim ☆`1,646`
### Emacs

- [manzaltu/claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) — Claude Code IDE integration for Emacs ☆`1,200`
- [stevemolitor/claude-code.el](https://github.com/stevemolitor/claude-code.el) — Claude Code Emacs integration ☆`555`
## CLI Assistants

- [closedloop-technologies/autocomplete-sh](https://github.com/closedloop-technologies/autocomplete-sh) — Large language model in the terminal! Less `--help` and `man` and more getting stuff done ☆`120`
- [pmusolino/AI-Git-Narrator](https://github.com/pmusolino/AI-Git-Narrator) — AI-generated Git commit messages ☆`115`
- [beyimjan/shell-whiz](https://github.com/beyimjan/shell-whiz) — AI assistant for the command line ☆`57`
- [Strawberry-Computer/poorcoder](https://github.com/Strawberry-Computer/poorcoder) — DIY Poor Man's AI Coder ☆`49`
- [BrodaNoel/cmd-ai](https://github.com/BrodaNoel/cmd-ai) — Natural language shell command generator and executor powered by AI ☆`33`
## Generators

### App

- [stackblitz-labs/bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Prompt and deploy full-stack web apps ☆`18,721`
- [srcbookdev/srcbook](https://github.com/srcbookdev/srcbook) — TypeScript app development platform ☆`3,428`
### UI

- [rapidpages/rapidpages](https://github.com/rapidpages/rapidpages) — Generate React and Tailwind components using AI ☆`1,235`
## SDKs & Libraries

### Go

- [googleapis/go-genai](https://github.com/googleapis/go-genai) — Google Gen AI SDK for Go ☆`943`
### PHP & Laravel

- [google-gemini-php/laravel](https://github.com/google-gemini-php/laravel) — Gemini PHP API for Laravel ☆`569`
- [halilcosdu/laravel-slower](https://github.com/halilcosdu/laravel-slower) — Laravel Slower - Optimize Your DB Queries with AI ☆`395`
- [kargnas/laravel-ai-translator](https://github.com/kargnas/laravel-ai-translator) — Auto-translate Laravel language files ☆`241`
- [grok-php/laravel](https://github.com/grok-php/laravel) — Grok AI integration for Laravel ☆`162`
- [tott/laravel-tall-claude-ai-configs](https://github.com/tott/laravel-tall-claude-ai-configs) — Laravel TALL stack AI configs ☆`35`
## Documentation

- [eli64s/readme-ai](https://github.com/eli64s/readme-ai) — README file generator, powered by AI. ☆`2,828`
## Testing

- [codeintegrity-ai/mutahunter](https://github.com/codeintegrity-ai/mutahunter) — Open Source, Language Agnostic Mutation Testing ☆`286`
## Other

- [clidey/whodb](https://github.com/clidey/whodb) — Lightweight next-gen data explorer ☆`4,410`
- [av/harbor](https://github.com/av/harbor) — Run LLM backends and APIs easily ☆`2,209`


## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

- [jamesmurdza/awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools)
- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)
- [Piebald-AI/awesome-gemini-cli](https://github.com/Piebald-AI/awesome-gemini-cli)
- [All Contributors](https://github.com/abordage/awesome-ai/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
