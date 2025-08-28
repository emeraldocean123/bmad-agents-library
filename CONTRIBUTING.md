# Contributing

Thanks for your interest in contributing to the BMAD Agents Library!

## Scope
This repository is a documentation library of BMAD agent prompts and usage guides. There is no executable code here.

## How to Add or Update Agents
- Structure: Place project-specific agents under their project folder (e.g., `bookmark-cleaner/`), and general-purpose agents under `general/`.
- Format: Prefer Markdown (`.md`) for rich rendering on GitHub. Use `.txt` only for very large prompt bundles that benefit from plain text.
- Required sections for agent docs:
  - Identity: Name, Role, Domain
  - Mission: What the agent is meant to achieve
  - Inputs/Assumptions: What context it expects
  - Operations/Commands: How to run or apply the agent in practice
  - Deliverables/Outputs: What artifacts or outcomes to expect
  - Limits/Notes: Boundaries and caveats
  
See `templates/agent.md` for a ready-to-copy template.

## Documentation Quality
- Keep language concise, actionable, and task-focused.
- Use consistent headings and section order across agents.
- Include a short “Quick Start” block if applicable.

## Folder READMEs
When adding a new folder or set of agents, add a `README.md` that:
- Summarizes the purpose of the folder
- Lists included agents with one-line descriptions
- Links to each document

## Link, Style, and Spellcheck
This repo uses Markdown linting, link checking, and spellcheck in CI. Please ensure:
- Links are valid and use HTTPS where possible
- Headings are properly nested and unique
- Lines are reasonably wrapped for readability
 - Spelling is correct; add domain terms to the ignore list when appropriate

## Issues and Discussions
- Use GitHub Issues for bugs, requests, or proposals.
- For security-related concerns, see `SECURITY.md`.

## Community Standards
- All contributors are expected to follow the `CODE_OF_CONDUCT.md`.

## License
If you intend to change or add licensing terms, please open an Issue first to discuss. Avoid adding license text to individual files.
