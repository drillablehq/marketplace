# drillable marketplace

The Claude Code plugin marketplace for [drillable](https://drillable.com) — ground your coding agent
in cited sources instead of letting it guess.

```
/plugin marketplace add drillablehq/marketplace
/plugin install drillable@drillable
```

The **drillable** plugin grounds your agent's reference claims against the 100+ domain corpus, and
optionally your project's own docs too. A companion tool, **[Drillable Check](https://github.com/drillablehq/check)**,
grounds your **dependencies** against the live registry + OSV — it's a GitHub Action / CLI, not a
plugin: `npx drillable-check` or `uses: drillablehq/check@v1`.

| Tool | Grounds your… | Against | Form |
|---|---|---|---|
| **drillable** | reference claims (+ optionally your project's docs) | the 100+ domain corpus (and your repo's docs/decisions) | CC plugin (MCP) |
| **check** | dependencies | the live package registry + OSV | Action / CLI |

Operated by Drillable LLC.
