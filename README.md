# agentcowboy

Small tools and studies from running AI coding agents day to day, including OpenAI's Codex CLI.

- [agent-workbench](https://github.com/agentcowboy/agent-workbench): a checker that tells you when instruction text you've listed no longer appears in your files, a warning when one commit mixes changes from two writers' directories in a shared working tree, and the case study behind the checker.
- [codex-roles-study](https://github.com/agentcowboy/codex-roles-study): how one operator picked Codex model and effort settings for coding, fact-checking and code review, with the numbers and calculations to reproduce them.
- [evidence-facts](https://github.com/agentcowboy/evidence-facts): a plain-text format and Python linter for one-line claims about a system, each with an address, declared evidence and cross-references the linter checks.
- [codex-jobs](https://github.com/agentcowboy/codex-jobs): a small supervisor for Codex jobs, with saved outcomes, a live registry and a terminal viewer.
- [hook-route-parity](https://github.com/agentcowboy/hook-route-parity): a checker that compares the declared hook routes in two Claude Code settings or plugin hooks JSON files, exiting 0 when they match, 1 on drift and 2 on an input error, without printing commands or paths.
- [rule-roles](https://github.com/agentcowboy/rule-roles): a tool that checks every Markdown rule file in a folder is assigned to one or more agent roles and copies each role's files, unchanged, into its own folder, so different agents get different subsets of one rules folder; it exits 0 when complete, 1 on unassigned or missing files and 2 on an input error.

Each repo has a self-test: clone it, run `bash ACCEPTANCE`, and look for `ACCEPTANCE PASS` on the last line. Requirements are in each README; codex-jobs's self-test also needs Linux, tmux and the Rich Python package.
