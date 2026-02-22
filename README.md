# Collabute Agent Skills

Skills for AI coding agents to use Collabute MCP correctly and safely.

## Available skills

### collabute-mcp

Use Collabute MCP for organization-specific retrieval and proposal-safe actions.

Covers:
- Meeting-first workflows (`meeting.list_recent -> meeting.get -> meeting.propose_task_from_meeting`)
- Transcript pagination behavior (`meeting.get_transcript`)
- Scope-aware tool selection and OAuth troubleshooting
- Proposal-only write safety patterns

## Install

```bash
npx skills add muperdev/collabute-agent-skills --skill collabute-mcp
```

## List skills in this repo

```bash
npx skills add muperdev/collabute-agent-skills --list
```

## Local development

```bash
npx skills add . --list
```

## License

MIT
