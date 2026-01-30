# Custom Claude Code Plugins

A collection of Claude Code plugins for enhanced AI-assisted development workflows.

## The Deep Trilogy

A three-plugin pipeline for turning vague ideas into production code:

```
/deep-project (decompose) → /deep-plan (plan) → /deep-implement (build)
```

| Plugin | Purpose | Input | Output |
|--------|---------|-------|--------|
| [deep-project](https://github.com/piercelamb/deep-project) | Decompose | Vague requirements | Focused spec files |
| [deep-plan](https://github.com/piercelamb/deep-plan) | Plan | Spec file | Section files with TDD |
| [deep-implement](https://github.com/piercelamb/deep-implement) | Build | Section files | Production code |

### Where to start?

- **Vague multi-component project?** Start with [/deep-project](https://github.com/piercelamb/deep-project)
- **Single focused feature?** Start with [/deep-plan](https://github.com/piercelamb/deep-plan)
- **Already have section files?** Skip to [/deep-implement](https://github.com/piercelamb/deep-implement)

## All Plugins

| Plugin | Description | Status |
|--------|-------------|--------|
| [deep-project](https://github.com/piercelamb/deep-project) | Decomposes broad, vague requirements into focused, plannable spec files | Available |
| [deep-plan](https://github.com/piercelamb/deep-plan) | Transforms feature requests into detailed, TDD-oriented implementation plans through research, interviews, and multi-LLM review | Available |
| [deep-implement](https://github.com/piercelamb/deep-implement) | Implements section files with TDD methodology, integrated code review, and structured git workflow | Available |

## Installation

Add the marketplace once (using any plugin repo), then install whichever plugins you need:

```
/plugin marketplace add piercelamb/deep-plan
/plugin install deep-project
/plugin install deep-plan
/plugin install deep-implement
```

Or install individually via clone:

```bash
git clone https://github.com/piercelamb/<plugin-name> ~/.claude/plugins/<plugin-name>
```

## Author

Pierce Lamb - [GitHub](https://github.com/piercelamb)
