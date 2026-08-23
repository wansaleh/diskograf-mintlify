# Documentation project instructions

## About this project

- This is `diskograf-next`'s public docs site, built on [Mintlify](https://mintlify.com).
  It replaces the retired Fumadocs Worker at `fumadocs.diskograf.com`. It was
  briefly moved into the `diskograf-next` monorepo as `apps/docs/` and moved
  back out to this standalone repo on 2026-08-23.
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- `openapi.json` is a **committed copy** of `diskograf-next`'s
  `apps/api/openapi.json`, not a symlink — Mintlify's dashboard only fetches
  this repo, so a path pointing outside it fails to resolve on their end
  ("Failed to fetch OpenAPI file for anchor or tab"). Whenever
  `apps/api/openapi.json` changes in `diskograf-next`, re-copy it here in a
  separate commit: `cp ../diskograf-next/apps/api/openapi.json openapi.json`.
  Never hand-edit this file directly — edit the source in `diskograf-next`
  and re-copy.
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP
- Run `mint dev --port 3010` to preview locally. There's no build/lint/typecheck
  step — Mintlify's own dashboard builds and hosts the site from this repo.

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
