# CLAUDE.md

## About This Repo

SciWrite is a single Agent Skill that reviews scientific and engineering manuscripts for writing quality, based on Dr. Kristin Sainani's *Writing in the Sciences* course. The repo is four Markdown/text files; there is no code, build, or test suite.

## Files

- `SKILL.md` - the skill itself (name: `manuscript-writing-review`). YAML frontmatter, then four review modes, five audit passes, the report format, severity levels, and constraints.
- `README.md` - what the skill does, how it was made, and install steps for Claude.ai, Claude Code, Cowork, ChatGPT, and Gemini.
- `HOW-TO-USE.md` - Claude Code setup and example prompts.
- `LICENSE` - CC BY 4.0.

## Working Here

- `SKILL.md` must stay a valid Agent Skill: keep the YAML frontmatter (`name`, `description`) at the top. The `description` controls when the skill triggers, so edit its trigger phrases and "Do NOT use for" clause deliberately.
- `README.md` and `HOW-TO-USE.md` describe the skill's five passes, four modes, and output format. When changing any of these in `SKILL.md`, update both documents to match.
- Keep the attribution to Sainani's course and the CC-BY notices intact.
- Users install by zipping or copying this repo, so keep `SKILL.md` at the repo root and don't add files the skill doesn't need.

## Reviewing a Manuscript in This Repo

If asked to review writing while working here, follow `SKILL.md`. Its constraints apply: never alter scientific content, and show the original text with a concrete revision for every finding.
