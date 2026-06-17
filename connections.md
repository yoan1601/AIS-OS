# Connections

Registry of every system your AIOS can reach. Filled by `/onboard` from Q4-Q7 answers; expanded over time as you wire new tools. `/audit` checks this file for domain coverage and freshness.

| # | Domain | Tool | Mechanism | Auth | Last checked |
|---|---|---|---|---|---|
| 1 | Revenue / Financials | Orange Money + BMOI (clients internationaux TBD) | not yet connected | — | — |
| 2 | Customer interactions | WhatsApp, LinkedIn DMs, Messenger | not yet connected | — | — |
| 3 | Calendar | Google Calendar (inferred from Gmail) | not yet connected | — | — |
| 4 | Communication | Gmail (yoan.rab@gmail.com), WhatsApp, LinkedIn DMs, Messenger | not yet connected | — | — |
| 5 | Project / task tracking | Notion (workspace "Business" à créer) | mcp | — | — |
| 6 | Meeting intelligence | Notion, Google Drive | not yet connected | — | — |
| 7 | Knowledge / files | Google Drive, Notion, fichiers en local | not yet connected | — | — |

**Notion note:** tous les workspaces business doivent être sous une page "Business" dans Notion. Le workspace pour L'Activation AIOS est à créer. Un espace suivi financier est également à créer.

**Mechanism options:** `mcp` (MCP server), `script` (Python/Bash hitting an API, in `scripts/`), `export` (CSV/JSON dump pipeline), `key+ref` (`.env` key + `references/{tool}-api.md` guide), `not yet connected`.

When you wire a new tool, also save `references/{tool}-api.md` capturing endpoints, auth flow, and common queries — researched-once-saved-forever.
