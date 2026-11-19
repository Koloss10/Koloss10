# Project instructions

Shared rules adapted from [everything-claude-code](https://github.com/affaan-m/everything-claude-code) (MIT, see `.claude/ECC-LICENSE`).
Stack: Python + HTML/CSS/JS (web).

@.claude/rules/common/code-review.md
@.claude/rules/common/coding-style.md
@.claude/rules/common/development-workflow.md
@.claude/rules/common/git-workflow.md
@.claude/rules/common/patterns.md
@.claude/rules/common/performance.md
@.claude/rules/common/security.md
@.claude/rules/common/testing.md
@.claude/rules/python/coding-style.md
@.claude/rules/python/patterns.md
@.claude/rules/python/security.md
@.claude/rules/python/testing.md
@.claude/rules/web/coding-style.md
@.claude/rules/web/design-quality.md
@.claude/rules/web/patterns.md
@.claude/rules/web/performance.md
@.claude/rules/web/security.md
@.claude/rules/web/testing.md

## Available subagents (`.claude/agents/`)
planner, architect, code-reviewer, python-reviewer, security-reviewer, tdd-guide, build-error-resolver,
refactor-cleaner, doc-updater, silent-failure-hunter, performance-optimizer.

## Slash commands (`.claude/commands/`)
/plan, /code-review, /python-review, /build-fix, /refactor-clean, /test-coverage, /update-docs, /feature-dev

## Skills (`.claude/skills/`)
python-patterns, python-testing
