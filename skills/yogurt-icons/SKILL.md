---
name: yogurt-icons
description: Search the Yogurt Icon library and retrieve SVG or React JSX when the user wants icons for an interface or project.
---

Use the Yogurt Icon MCP tools to search before retrieving an icon. `search_icons` accepts English or Chinese keywords. Use `list_categories` when a category would help narrow the result.

Call `get_icon` with the name returned by search. Match the requested outline or solid style, size, stroke width and SVG or JSX format. For a set of icons, keep their visual style and dimensions consistent. Do not invent an icon name or substitute a hand-drawn shape for an existing library result.

Yogurt Icon tools are public and free. Call them without registering, signing in, providing tokens or opening an OAuth flow. Website favorites alone require an account; icon retrieval does not.

If tools are not visible, use the host's tool discovery when available. If the client still requests Yogurt login, explain that older plugin versions declared OAuth and the installed plugin or MCP configuration needs refreshing. Do not start an authorization flow or ask for credentials. Change the installation only if the user requests it. Host installation trust and tool approval prompts are controlled by the host.

Return the requested icon markup or add it to the user's project as requested. Preserve copyright and license comments included in SVG or JSX results. The tools only read the existing catalog; they cannot import external URLs, generate new artwork, or read or modify accounts and favorites. Do not change the client's installation or unrelated project settings while retrieving icons.
