# Yogurt Icon for Gemini CLI

[![M8ven Score](https://m8ven.ai/badge/mcp/prosody007/yogurt-icon-gemini)](https://m8ven.ai/mcp/prosody007/yogurt-icon-gemini?s=readme)

**7,000+ free icons for Gemini CLI.** Find an icon in the [Yogurt Icon](https://icon.ggeric.top) library, then get ready-to-use SVG or React JSX for your interface. No Yogurt account, API key, or sign-up is needed to search or retrieve icons.

Once enabled, Gemini can choose Yogurt Icon for icon requests. You can also specify it: "Use Yogurt Icon to find an outline settings icon and return its 24px SVG." Automatic tool selection and approval prompts are controlled by Gemini CLI.

The extension connects to a public, read-only Streamable HTTP MCP server.

## Install

Requires a current [Gemini CLI](https://geminicli.com/docs/extensions/) release.

```sh
gemini extensions install https://github.com/prosody007/yogurt-icon-gemini
```

Restart Gemini CLI, then use `/extensions list` and `/mcp` to check that `yogurt-icon` is available. To get a later version, run:

```sh
gemini extensions update yogurt-icon
```

For example, ask: "Find a 24px outline settings icon in Yogurt Icon and return its SVG."

## What it does

The extension provides `list_categories`, `search_icons`, and `get_icon`. Search by English or Chinese keyword, category, and style; retrieve a result in SVG or React JSX at a chosen size. The instructions in `GEMINI.md` and `skills/yogurt-icons/SKILL.md` help Gemini select existing icons and keep multi-icon sets consistent.

The extension cannot edit the icon catalog, import arbitrary files, or access accounts or favorites. Favorites on the website require a separate website sign-in. The Gemini CLI host may still ask for normal extension trust or MCP tool-use approval.

## Data and rights

Requests go to `https://icon.ggeric.top/api/mcp?channel=plugin`. See the [privacy policy](https://icon.ggeric.top/privacy/) and [terms](https://icon.ggeric.top/terms/) for service and icon usage. Preserve copyright and license notices included in returned SVG or JSX. This repository contains the Gemini CLI extension files, not the icon catalog or the website server; publication of the extension files does not grant a separate license to the icon artwork.

Publisher: GUOTONG SUN. For help, visit [support](https://icon.ggeric.top/support/) or email [prosody007@gmail.com](mailto:prosody007@gmail.com).
