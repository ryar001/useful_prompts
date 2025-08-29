## 2025-08-29

### Documentation Update

#### `code_assistant/commands/ai-tracker.md`

- Updated command prefix from `--ai-tracker` to `//ai-tracker`.
- Updated command execution example to `//ai-tracker --update`.

### Feature

#### `code_assistant/commands/ai-tracker.md`

- Added new rules for commit messages regarding substitutions.
- Added sections for comparing against specific commits/branches and `UPDATES.md` format with an example.

## 2025-08-29

### What's New

#### `code_assistant/GEMINI.md`

- Overhauled and expanded the AI Coding Assistant Instructions, reorganizing existing guidelines and adding new sections on project context, code structure, data handling, quality, error handling, API development, testing, documentation, and AI guardrails. A new "Special Commands" section details how to invoke internal commands.

#### `code_assistant/commands/ai-tracker.md`

- Introduced a new command (`--ai-tracker update`) to monitor, summarize, and document project changes. This utility analyzes staged `git diff` output, generates AI-summarized updates, prepends them to `UPDATES.md`, and creates Conventional Commits.

#### `code_assistant/commands/execute-prp.md`

- Introduced a new command (`--execute-prp`) for executing Prompt Response Protocols, outlining a structured process for loading, planning, implementing, and validating features based on PRP files.

#### `code_assistant/commands/generate-prp.md`

- Introduced a new command (`--generate-prp`) for generating comprehensive Prompt Response Protocols, including guidelines for codebase analysis, external research, context inclusion, implementation blueprints, and validation gates.

# Project Updates

## 2025-08-24

### What's New

#### `code_assistant/AI_TRACKER_GENIE.md`

- Added a new markdown file detailing the AI Changes Tracker, including its overview, features, how it works, usage instructions, and file format for `UPDATES.md`.

#### `code_assistant/GEMINI.md`

- Added a new markdown file outlining core project workflow, code quality and consistency guidelines, API and package development practices, testing and reliability standards, documentation and explainability requirements, and AI guardrails.

#### `code_assistant/for_shopify_mcp.md`

- Added a new markdown file providing instructions for the Shopify API MCP Tool, including startup procedures and descriptions of `learn_shopify_api`, `search_docs_chunks`, and `fetch_full_docs`.