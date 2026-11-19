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

## Publishing with GitHub Pages

This repo includes a workflow that publishes the tool with GitHub Pages every time you push changes to `main`. GitHub Pages must be turned on for the repo before it works. Check with the Product Manager before turning it on.

To turn on GitHub Pages:

1. In this repo on GitHub, click **Settings**.
2. In the left-hand menu, click **Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push a change to `main`, or go to the **Actions** tab, select **Deploy to GitHub Pages** and click **Run workflow**.
5. When the workflow has finished (a green tick in the **Actions** tab), your tool's address appears at the top of the **Pages** settings. It will look like `https://<organisation>.github.io/<repo-name>/`.

If the workflow fails with a Pages error, check that step 3 is done and that the repo's visibility allows GitHub Pages.

## Before you submit to Ember Labs

1. Fill in `METHODOLOGY.md` and `data/README.md`.
2. Check the tool works on a phone and inside the Ember Labs page.
3. Turn on GitHub Pages (see above) and check the published version works.
4. Run the AI policy skill and fix anything marked "must fix".
5. Ask the Product Manager to review.

## Rules worth remembering

- Never put passwords, API keys or tokens in this repo. Store them as GitHub repository secrets.
- Don't collect personal information in the tool.
- Don't make analytical claims (findings or conclusions presented as Ember's view). Publish analysis through Ember's main website instead.
