# Majico — Cursor plugin

Official [Majico.xyz](https://majico.xyz) MCP server for Cursor. Gives Agent access to your project's brand guidelines, design tokens, logos, Studio canvas, and export manifest.

**Requires:** Majico Pro or Creator plan.

## Setup after install

1. Open **Cursor → Settings → Features → Model Context Protocol**
2. Enable the **Majico** server
3. Click **Connect** — Cursor opens your browser to sign in to Majico
4. If you have multiple brand projects, pick which one to connect

No API keys or project IDs to copy. Cursor stores the OAuth token and binds it to your chosen Majico project.

## Tools

- `get_brand_profile`, `get_design_tokens`, `get_logo_svg`, `get_guidelines`, `get_design_md`
- `get_studio_canvas`, `get_export_manifest`, `update_studio_html_frame`

## Links

- [Majico](https://majico.xyz)
- [API docs](https://majico.xyz/docs/api-reference)
- [Support](mailto:support@majico.xyz)
