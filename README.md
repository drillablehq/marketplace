# drillable marketplace

The Claude Code plugin marketplace for [drillable](https://drillable.com)'s developer tools — each
grounds a different claim against a different source, instead of letting your agent guess.

```
/plugin marketplace add drillablehq/marketplace
/plugin install drillable@drillablehq
```

A third tool, **[Drillable Check](https://github.com/drillablehq/check)**, grounds your
**dependencies** against the live registry + OSV — it's a GitHub Action / CLI, not a plugin:
`npx drillable-check` or `uses: drillablehq/check@v1`.

| Tool | Grounds your… | Against | Form |
|---|---|---|---|
| **cite** | reference claims | the 100+ domain reference corpus | CC plugin (MCP) |
| **context** | project's own facts | your repo's docs/decisions | CC plugin (local MCP) |
| **check** | dependencies | the live package registry + OSV | Action / CLI |

Operated by Drillable LLC.
