<!--
These instructions help AI coding assistants become immediately productive in this repository.
Only include facts that are discoverable in the workspace and short, actionable guidance.
-->

# Copilot instructions for ai-avatar (repository)

This repository is currently minimal — it contains only a top-level `README.md` and a `.git` history. There is no source, tests, or CI configuration present.

Use the guidance below when working in this repo:

- ✅ First step: Ask the user for goals and preferred language/framework before making any non-trivial changes. The repo doesn't show an existing stack — do not assume one.

- 🔎 Where to look: the only authoritative file present is `README.md`. Check for hidden files and branches before scaffolding (e.g. `.github/`, `main` branch, remote history).

- 🛠 Safe scaffolding pattern: when the user requests implementation, propose a minimal scaffold and get confirmation. For example, suggest a layout like:

  - `src/` — source code
  - `tests/` — unit/integration tests
  - `README.md` — usage and commands
  - `LICENSE` and `pyproject.toml` or `package.json` depending on language

- 💬 Communication: explain any assumptions clearly in your commit message and PR description; include quick run or test commands in the README.

- 🔁 When updating this file: merge any existing content and preserve user-provided notes. If `.github/copilot-instructions.md` already exists, keep user text and append missing, correct facts only.

- 📌 Examples of safe, small actions an AI assistant can take without extra permission:

  - Add a descriptive README section that asks the user about intended language/tooling.
  - Create a tiny example scaffold and corresponding tests (but confirm before expanding into a full feature).

- ⚠️ What NOT to do without confirmation:
  - Pick a language, runtime, or framework and commit a full project scaffolding without explicit user approval.
  - Delete or rewrite top-level files or important git history.

If you're unsure what to do next, ask one concise question to the repo owner describing your options and the minimal change you plan to make.

---

If this file is merged or updated later, keep instructions short and fact-based — reflect only what is discoverable in the repo at merge time.
