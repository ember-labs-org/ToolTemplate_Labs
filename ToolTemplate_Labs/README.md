# {{TOOL_NAME}}

{{ONE_LINE_DESCRIPTION}}

An [Ember Labs](https://ember-labs.org/) prototype. Ember Labs tools are experimental and are not Ember's main data products.

## Owner

| Role | Person |
| :-- | :-- |
| Owner | {{OWNER_NAME}} ({{OWNER_EMAIL}}) |
| Backup | {{BACKUP_NAME}} ({{BACKUP_EMAIL}}) |
| Team | {{TEAM}} |

## What's in this repo

| Folder or file | What goes there |
| :-- | :-- |
| `index.html` | The tool itself |
| `data/` | Pre-built data files the tool reads, plus `data/README.md` listing each source and its licence |
| `scripts/` | Any scripts that fetch or process data |
| `METHODOLOGY.md` | Sources, method, assumptions and the AI disclosure. Linked from inside the tool |

## Updating the data

{{HOW_TO_UPDATE_DATA}}

## Before you submit to Ember Labs

1. Fill in `METHODOLOGY.md` and `data/README.md`.
2. Check the tool works on a phone and inside the Ember Labs page.
3. Run the AI policy skill and fix anything marked "must fix".
4. Ask the Product Manager to review.

## Rules worth remembering

- Never put passwords, API keys or tokens in this repo. Store them as GitHub repository secrets.
- Don't collect personal information in the tool.
- Don't make analytical claims (findings or conclusions presented as Ember's view). Publish analysis through Ember's main website instead.
