# AI Plugin Tracker

Search a catalog of ChatGPT apps and Claude connectors by name, task, category, publisher, platform or recorded Claude directory tier. Inspect listing details, available tools and original store links. Track captured rankings, tier changes and catalog history.

The plugin points Cursor at the hosted AI Plugin Tracker MCP server.

## Install

Install `AI Plugin Tracker` from the Cursor Marketplace once the listing is approved. To try it locally, copy this folder to `~/.cursor/plugins/local/ai-plugin-tracker`.

## Tools

All tools are read-only.

- `search_apps` - find apps and connectors by name, task, category, publisher, platform or tier
- `get_app` - listing details, available tools and original store link
- `list_rankings` - captured popular, new and trending lists
- `app_history` - daily rank history and recorded scores for one app
- `recent_changes` - tier changes, newly observed and delisted entries
- `market_overview` - catalog totals

Each result includes its snapshot date. History may be incomplete; "newly observed" means first seen in this catalog. Rankings and scores are captured directory data, not installation or user counts. User counts, revenue and reviews are unavailable.

## Hosted MCP Server

`https://mcp-app-store-chatgpt.keenethics-labs.com/mcp` (streamable HTTP, OAuth).

Google sign-in is required. Access is limited to 30 tool calls per minute and 500 per UTC day per account. The catalog cannot install apps, connect other services, access your workspaces or change listings.

## Example prompts

- Is there a Claude connector for Notion?
- Show the five most popular Claude connectors.
- Which Claude connector tiers changed in the last seven days?

## Support And Policies

- Support: `labs@keenethics.com`
- Privacy Policy: https://mcp-app-store-chatgpt.keenethics-labs.com/privacy
- Terms of Service: https://mcp-app-store-chatgpt.keenethics-labs.com/terms

## Repository

https://github.com/keen-mcp/ai-plugin-tracker-cursor-plugin

Provided by Keenethics, independently of OpenAI, Anthropic and listed publishers.
