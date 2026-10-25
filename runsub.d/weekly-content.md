# EXAMPLE PROMPT — fictional website project

This file is a **sample** long agent prompt for RunSub. It is referenced from
`runsub.example.yaml` via `prompt_file: runsub.d/weekly-content.md`.

Copy the pattern into your application repo: keep short prompts inline in
`runsub.yaml`, and put anything longer than about ten lines in `runsub.d/*.md`.

## Goal

Produce a brief weekly content outline for the fictional Example Website:
homepage hero angle, one supporting article idea, and one CTA tweak.

## Constraints

- Do not invent production metrics or customer data.
- Do not include secrets, tokens, hostnames used as credentials, or env values.
- Stay offline-friendly: work only from repository text the agent is mounted with.
- Output plain markdown suitable for an editor to review.

## Output shape

1. **Hero** — one sentence angle  
2. **Article** — title + three bullet points  
3. **CTA** — one suggested button label and destination path (path only)
