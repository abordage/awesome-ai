# Awesome AI

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-ai?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-92-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-668,968-gold)
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
- [Generators](#generators)
  - [App](#app)
  - [UI](#ui)
  - [Documentation](#documentation)
- [IDE & Editor](#ide--editor)
  - [Extensions](#extensions)
  - [Neovim](#neovim)
  - [Emacs](#emacs)
- [SDKs & Libraries](#sdks--libraries)
  - [Go](#go)
  - [PHP & Laravel](#php--laravel)


## AI Coding Agents

### General Purpose

- [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) — Run local LLMs on any device ☆`77,137`
- [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) — Chat with documents using LLMs ☆`57,116`
- [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer) — CLI platform to experiment with codegen ☆`55,217`
- [Aider-AI/aider](https://github.com/Aider-AI/aider) — aider is AI pair programming in your terminal ☆`40,551`
- [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr) — RAG for GenAI in apps ☆`38,930`
- [mckaywrigley/chatbot-ui](https://github.com/mckaywrigley/chatbot-ui) — AI chat for any model. ☆`33,024`
- [plandex-ai/plandex](https://github.com/plandex-ai/plandex) — AI coding agent for large projects ☆`14,986`
- [smol-ai/developer](https://github.com/smol-ai/developer) — Embed a developer agent in apps ☆`12,205`
- [joshpxyne/gpt-migrate](https://github.com/joshpxyne/gpt-migrate) — Migrate codebase between frameworks ☆`6,997`
- [kuafuai/DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — Multi-agent AI-driven development ☆`5,967`
- [stravu/crystal](https://github.com/stravu/crystal) — Run multiple AI sessions in parallel ☆`2,904`
- [melih-unsal/DemoGPT](https://github.com/melih-unsal/DemoGPT) — Create LLM agents with tools ☆`1,888`
- [splx-ai/agentic-radar](https://github.com/splx-ai/agentic-radar) — A security scanner for your LLM agentic workflows ☆`908`
- [Nayjest/Gito](https://github.com/Nayjest/Gito) — AI-powered GitHub code review ☆`166`
- [pmusolino/AI-Git-Narrator](https://github.com/pmusolino/AI-Git-Narrator) — AI-generated Git commit messages ☆`116`
- [closedloop-technologies/autocomplete-sh](https://github.com/closedloop-technologies/autocomplete-sh) — LLM autocomplete in terminal ☆`128`
- [seahyinghang8/blinky](https://github.com/seahyinghang8/blinky) — An open-source debugging agent in VSCode ☆`89`
- [Strawberry-Computer/vibe-compiler](https://github.com/Strawberry-Computer/vibe-compiler) — RAG for integrating GenAI in apps ☆`59`
- [beyimjan/shell-whiz](https://github.com/beyimjan/shell-whiz) — AI assistant for the command line ☆`60`
- [Strawberry-Computer/poorcoder](https://github.com/Strawberry-Computer/poorcoder) — DIY Poor Man's AI Coder ☆`53`
- [BrodaNoel/cmd-ai](https://github.com/BrodaNoel/cmd-ai) — Natural language shell command generator and executor powered by AI ☆`38`
### Claude Code

- [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) — Configuration framework for Claude Code ☆`20,759`
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) — CLI tool for configuring and monitoring Claude Code ☆`20,138`
- [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts) — Quick start projects for Claude ☆`13,909`
- [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow) — Agent orchestration for Claude ☆`13,976`
- [slopus/happy](https://github.com/slopus/happy) — Mobile/Web client for Codex and Claude ☆`11,472`
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) — Analyze Claude Code usage stats ☆`10,597`
- [automazeio/ccpm](https://github.com/automazeio/ccpm) — Project management for Claude Code ☆`7,194`
- [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) — Claude Code usage monitor ☆`6,514`
- [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) — Manage multiple AI terminal agents ☆`5,976`
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) — Claude Code action for GitHub PRs ☆`5,629`
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) — Custom statusline for Claude Code ☆`3,705`
- [OneRedOak/claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows) — Best workflows for Claude Code ☆`3,607`
- [nizos/tdd-guard](https://github.com/nizos/tdd-guard) — Automated TDD enforcement for Claude Code ☆`1,750`
- [parruda/swarm](https://github.com/parruda/swarm) — Ruby gems for AI agent systems ☆`1,623`
- [pchalasani/claude-code-tools](https://github.com/pchalasani/claude-code-tools) — Productivity tools for Claude Code ☆`1,416`
- [Piebald-AI/tweakcc](https://github.com/Piebald-AI/tweakcc) — Customize Claude Code prompts ☆`1,064`
- [Owloops/claude-powerline](https://github.com/Owloops/claude-powerline) — Beautiful vim-style powerline statusline for Claude Code ☆`767`
- [carlrannaberg/claudekit](https://github.com/carlrannaberg/claudekit) — Custom commands and hooks for Claude ☆`587`
- [Helmi/claude-simone](https://github.com/Helmi/claude-simone) — Project management for AI dev ☆`544`
- [claude-did-this/claude-hub](https://github.com/claude-did-this/claude-hub) — Webhook service for Claude + GitHub ☆`346`
- [johnlindquist/claude-hooks](https://github.com/johnlindquist/claude-hooks) — TypeScript hook system for Claude Code with type safety ☆`294`
- [nyatinte/ccexp](https://github.com/nyatinte/ccexp) — Terminal interface for Claude extensions ☆`249`
- [JSONbored/claudepro-directory](https://github.com/JSONbored/claudepro-directory) — Searchable Claude Pro project collection ☆`181`
- [bartolli/claude-code-typescript-hooks](https://github.com/bartolli/claude-code-typescript-hooks) — Quality check hooks for Claude Code projects ☆`168`
- [dazuiba/CCNotify](https://github.com/dazuiba/CCNotify) — Desktop notifications for Claude Code ☆`152`
- [dtormoen/tsk](https://github.com/dtormoen/tsk) — Task manager and sandbox for coding agents ☆`132`
- [ayoubben18/ab-method](https://github.com/ayoubben18/ab-method) — AI-powered software development ☆`139`
- [GowayLee/cchooks](https://github.com/GowayLee/cchooks) — A Python SDK for claude-code hooks ☆`116`
- [eckardt/cchistory](https://github.com/eckardt/cchistory) — Like the shell history command but for your Claude Code sessions. ☆`100`
- [sculptdotfun/viberank](https://github.com/sculptdotfun/viberank) — claude code leaderboard ☆`86`
- [beyondcode/claude-hooks-sdk](https://github.com/beyondcode/claude-hooks-sdk) — A PHP SDK for building Claude Code hooks ☆`60`
- [icanhasjonas/run-claude-docker](https://github.com/icanhasjonas/run-claude-docker) — Run claude code in somewhat safe and isolated yolo mode ☆`68`
- [Veraticus/cc-tools](https://github.com/Veraticus/cc-tools) — Claude Code tools ☆`47`
- [Brads3290/cclogviewer](https://github.com/Brads3290/cclogviewer) — Review Claude Code .jsonl files with a nice HTML UI ☆`66`
- [viveknair/ccoutputstyles](https://github.com/viveknair/ccoutputstyles) — Customize Claude Code output styles ☆`49`
### Gemini CLI

- [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) — AI agent with Gemini in terminal ☆`94,298`
- [google-gemini/cookbook](https://github.com/google-gemini/cookbook) — Examples and guides for using the Gemini API ☆`16,430`
- [google-github-actions/run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli) — A GitHub Action invoking the Gemini CLI. ☆`1,749`
- [GewoonJaap/gemini-cli-openai](https://github.com/GewoonJaap/gemini-cli-openai) — Gemini CLI as OpenAI API endpoint ☆`839`
- [gzzhongqi/geminicli2api](https://github.com/gzzhongqi/geminicli2api) — Proxy converting Gemini CLI to OpenAI-compatible API ☆`491`
- [Piebald-AI/gemini-cli-desktop](https://github.com/Piebald-AI/gemini-cli-desktop) — Desktop UI for Gemini CLI ☆`251`
- [amitkmaraj/gemini-cli-custom-slash-commands](https://github.com/amitkmaraj/gemini-cli-custom-slash-commands) — Custom slash commands for Gemini CLI ☆`152`
- [Theopsguide/gemini-code-flow](https://github.com/Theopsguide/gemini-code-flow) — AI dev orchestration for Gemini CLI ☆`139`
- [nettee/gemini-cli-proxy](https://github.com/nettee/gemini-cli-proxy) — Gemini CLI as OpenAI-compatible API ☆`131`
- [openmule/gacua](https://github.com/openmule/gacua) — Out-of-the-box computer use agent ☆`113`
- [Brioch/gemini-openai-proxy](https://github.com/Brioch/gemini-openai-proxy) — Serve Gemini models via OpenAI API ☆`51`
- [automateyournetwork/GeminiCLI_Slash_Listen](https://github.com/automateyournetwork/GeminiCLI_Slash_Listen) — A /listen feature for Gemini CLI ☆`19`
- [Jasonzhangf/gemini-cli-router](https://github.com/Jasonzhangf/gemini-cli-router) — routing your gemini-cli to openai 3rd party providers ☆`21`
### PR & Review

- [qodo-ai/pr-agent](https://github.com/qodo-ai/pr-agent) — AI-powered PR reviewer ☆`10,128`
- [sweepai/sweep](https://github.com/sweepai/sweep) — Sweep: AI coding assistant for JetBrains ☆`7,636`
- [mattzcarey/shippie](https://github.com/mattzcarey/shippie) — extendable code review and QA agent ☆`2,327`
- [Yuyz0112/dewhale](https://github.com/Yuyz0112/dewhale) — GitHub-powered AI development ☆`1,549`
- [codeintegrity-ai/mutahunter](https://github.com/codeintegrity-ai/mutahunter) — Open Source, Language Agnostic Mutation Testing ☆`286`
## Generators

### App

- [stackblitz-labs/bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Prompt and deploy full-stack web apps ☆`18,999`
- [srcbookdev/srcbook](https://github.com/srcbookdev/srcbook) — TypeScript app development platform ☆`3,438`
### UI

- [rapidpages/rapidpages](https://github.com/rapidpages/rapidpages) — Generate React and Tailwind components using AI ☆`1,235`
### Documentation

- [eli64s/readme-ai](https://github.com/eli64s/readme-ai) — README file generator, powered by AI. ☆`2,863`
## IDE & Editor

### Extensions

- [codota/TabNine](https://github.com/codota/TabNine) — AI Code Completions ☆`10,810`
- [smallcloudai/refact](https://github.com/smallcloudai/refact) — AI agent for engineering tasks ☆`3,474`
- [lgrammel/rubberduck-vscode](https://github.com/lgrammel/rubberduck-vscode) — AI-powered code edits in VS Code ☆`631`
- [kesor/chatgpt-code-plugin](https://github.com/kesor/chatgpt-code-plugin) — Code ChatGPT Plugin is a TypeScript Code Analyzer that enables ChatGPT to "talk" with YOUR code ☆`240`
### Neovim

- [greggh/claude-code.nvim](https://github.com/greggh/claude-code.nvim) — Claude Code integration for Neovim ☆`1,814`
### Emacs

- [manzaltu/claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) — Claude Code IDE integration for Emacs ☆`1,331`
- [stevemolitor/claude-code.el](https://github.com/stevemolitor/claude-code.el) — Claude Code Emacs integration ☆`612`
## SDKs & Libraries

- [av/harbor](https://github.com/av/harbor) — Run LLM backends and APIs easily ☆`2,421`
### Go

- [googleapis/go-genai](https://github.com/googleapis/go-genai) — Google Gen AI SDK for Go ☆`1,026`
### PHP & Laravel

- [google-gemini-php/laravel](https://github.com/google-gemini-php/laravel) — Gemini PHP API for Laravel ☆`600`
- [halilcosdu/laravel-slower](https://github.com/halilcosdu/laravel-slower) — Laravel Slower - Optimize Your DB Queries with AI ☆`398`
- [kargnas/laravel-ai-translator](https://github.com/kargnas/laravel-ai-translator) — Auto-translate Laravel language files ☆`247`
- [grok-php/laravel](https://github.com/grok-php/laravel) — Grok AI integration for Laravel ☆`162`
- [tott/laravel-tall-claude-ai-configs](https://github.com/tott/laravel-tall-claude-ai-configs) — Laravel TALL stack AI configs ☆`38`




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
