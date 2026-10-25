# Human voice module (agent skill)

This repository packages the **human voice** optional module as an agent skill. Use it on top of the human-centered language standard when you want drafts to read less like generic machine output.

## What you get

- `SKILL.md`: entry point the agent reads first.
- `module.md`: full module text.
- `SOURCES.md`: upstream attribution for cited organizations.
- `PROVENANCE`: which commit of the upstream monorepo produced this export.

## Install

1. Download or clone this repository.
2. **Claude (Skills):** zip `SKILL.md` and `module.md` together (or upload this folder) under Settings → Customize → Skills.
3. Load the human-centered language skill first if you use both; this module adds style constraints only.

Upstream monorepo: https://github.com/GoldenDoodleAI/trauma-informed-language (`packaging/claude-skill/human-voice/`).

## License

See `LICENSE`.

## Updates

Re-exports track commits of `GoldenDoodleAI/trauma-informed-language`. Compare `PROVENANCE` with the monorepo commit you intend to match.
