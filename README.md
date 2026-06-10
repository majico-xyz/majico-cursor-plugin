# Majico — Cursor plugin

Official [Majico.xyz](https://majico.xyz) MCP server for Cursor. Gives Agent access to your project's brand guidelines, design tokens, logos, Studio canvas, and export manifest.

**Requires:** Majico Pro or Creator plan and a [project API key](https://majico.xyz/account/integrations).

## Setup after install

Set these environment variables (system or in your MCP config):

| Variable            | Description                                     |
| ------------------- | ----------------------------------------------- |
| `MAJICO_PROJECT_ID` | Project UUID from Majico                        |
| `MAJICO_API_KEY`    | Project API key                                 |
| `MAJICO_API_URL`    | Optional — defaults to `https://api.majico.xyz` |

Get credentials from [Account → Integrations](https://majico.xyz/account/integrations) (one-click Cursor install with prefilled values).

## Tools

- `get_brand_profile`, `get_design_tokens`, `get_logo_svg`, `get_guidelines`, `get_design_md`
- `get_studio_canvas`, `get_export_manifest`, `update_studio_html_frame`

## npm package

This plugin runs [`user-majico-mcp`](https://www.npmjs.com/package/user-majico-mcp) via `npx`.

## Links

- [Majico](https://majico.xyz)
- [API docs](https://majico.xyz/docs/api-reference)
- [Support](mailto:support@majico.xyz)
