# QR Code Generator & Small Utilities

This repository is a deliberate collection of **standalone static pages**, not a shared backend application.

| Tool | Source page | Local route |
| --- | --- | --- |
| QR Code Generator | `index.html` | `/` |
| House utility | `house/index.html` | `/house/` |
| Weather utility | `weather/index.html` | `/weather/` |
| Hockey utility | `hockey/index.html` | `/hockey/` |

Each page has its own existing assets where present. No Supabase project is required for these static pages.

## Organization rules

- Keep existing folder names and URLs stable so saved bookmarks and integrations do not break.
- Keep a tool in this repository only while it can be maintained and deployed as a static page.
- If a utility requires accounts, a database, its own domain, or independent deployment, move it into a **new repository only after** its replacement is deployed and verified.
- Do not add private tokens or API secrets to browser JavaScript or to Git history.

See [PROJECT-ORGANIZATION.md](PROJECT-ORGANIZATION.md) for the current portfolio classification.
