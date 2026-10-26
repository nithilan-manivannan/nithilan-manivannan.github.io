# nithilan-manivannan.github.io

**The user site repository behind <https://nithilan-manivannan.github.io/>**

GitHub serves whatever lands in the root of this repository at the account's Pages URL. Because the repo is called `nithilan-manivannan.github.io`, it is special: it is the site root for the account rather than the sub path of a project.

## Current contents

At the moment this repository is deliberately tiny:

- `home.md` renders as a page on the site through GitHub's Jekyll processing.
- No theme bundle, no framework, no pipeline. Plain markdown becomes HTML.

This is the starting point of the user site. Small personal pages, notes, and link collections belong here, kept as plain text at heart so that any future styling layers on top of content that already works.

## Nearby sites on this account

| Repository | Live at |
|---|---|
| [photography](https://github.com/nithilan-manivannan/photography) | shots.nithilan portfolio, deployed through its own Actions workflow |
| [nps-ai-assistant](https://github.com/nithilan-manivannan/nps-ai-assistant) | school briefing app, data synced by GitHub Actions |

## Working with the repo

1. Edit `home.md` on the main branch, or add another `.md` file.
2. Give any new file Jekyll front matter so GitHub renders it:

```markdown
---
layout: page
title: Whatever this page is
---
```

3. GitHub Pages rebuilds on push. The latest status is visible under the repository's Pages settings or the Actions tab.

The build type here is the legacy builder, which renders markdown straight from the main branch root, so there is no build script or artifact step to maintain.
