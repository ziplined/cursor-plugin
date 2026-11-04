# Ziplined for Cursor

Ziplined is engagement intelligence for LinkedIn. It shows who engages with your posts and with the posts of your competitors, tells you which of those people match your ideal client, and sends them to Slack, Google Sheets, Clay or your outreach tool.

This plugin connects Cursor to the Ziplined MCP server, so you can ask the agent questions like:

- "Who engaged with my posts this week, and who of them fits my ideal client?"
- "Which people from companies in my ideal client definition commented on my competitor's last post?"
- "Send the new people in my Founders view to Google Sheets."

## What is included

- `mcp.json`: the Ziplined MCP server at `https://mcp.ziplined.io/mcp`.
- `rules/ziplined.mdc`: a short rule that tells the agent when to use the Ziplined tools and to ask before it spends credits or sends people anywhere.

## Install

From the Cursor Marketplace: search for **Ziplined** and click **Install**.

To install by hand:

1. Clone this repository into `~/.cursor/plugins/local/ziplined`.
2. Restart Cursor, or run **Developer: Reload Window**.
3. Open **Customize** and check that the **ziplined** MCP server and rule appear.

## Sign in

The server uses OAuth. The first time Cursor connects, a browser window opens and asks you to sign in to your Ziplined account. There are no API keys to copy and nothing to configure in the plugin. You need a Ziplined account: sign up at [ziplined.io](https://ziplined.io).

## Configuration

None. Your sources, ideal client definition, views and destinations live in your Ziplined account and the tools read them from there.

## Learn more

- Documentation: [docs.ziplined.io](https://docs.ziplined.io)
- Privacy policy: [ziplined.io/privacy](https://ziplined.io/privacy)
- Support: [support@ziplined.io](mailto:support@ziplined.io)

## License

MIT. See [LICENSE](LICENSE).
