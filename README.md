# perplexity

Sharing files between Claude and Perplexity.

## Folder structure

| Folder | Purpose |
|---|---|
| `from-claude/` | Files produced by Claude for Perplexity to pick up (research briefs, drafts, code, summaries) |
| `from-perplexity/` | Files produced by Perplexity for Claude to pick up (search results, sources, exports) |
| `shared/` | Reference material both assistants use (context docs, prompts, glossaries) |
| `archive/` | Finished exchanges — move files here once they've been processed |

## Conventions

- **File naming:** `YYYY-MM-DD-short-topic.md` (e.g. `2026-09-04-tampa-market-research.md`) so files sort chronologically.
- **Formats:** prefer Markdown (`.md`) for text; use `.csv`/`.json` for data.
- **Lifecycle:** drop a file in `from-claude/` or `from-perplexity/`, the other side reads it, then move it to `archive/` to keep the inbox folders clean.
- **Sources:** when sharing research, include source URLs at the bottom of the file.
