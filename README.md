# Mays for Claude

Mays is operations software for restaurants and cafés. This plugin connects Claude to your Mays account so you can ask about your locations in plain words and get answers from your live Mays data: who is working and who is late, what is waiting for your approval, how the checklists are going, which fridges are out of range, sales and labor, timecards, tips, stock, orders and your knowledge base. In Claude on the web, desktop and mobile, many answers come with an interactive Mays card.

If your Mays admin allows actions from AI apps and you tick "make changes" when you connect, Claude can also change things for you, such as adding a shift, approving time off or sending a purchase order. Every change shows you a preview first and happens only after you say yes.

## What the plugin contains

- `.mcp.json`: the remote Mays MCP server, `https://go.mays.app/mcp` (the same server as the Mays connector in Claude's directory).
- `skills/get-started/SKILL.md`: how to use the Mays tools well: picking a location, reading times, the two-step confirmation for changes, and the pay opt-in.

The plugin runs no local code and installs no packages. It talks only to `https://go.mays.app`, Mays' own server.

## Connect

1. Install the plugin. Claude adds the Mays server.
2. When Claude asks you to sign in, Mays opens in your browser. Sign in to Mays (managers and admins can connect).
3. Review what Claude will be able to read, optionally tick "make changes" and "Include wages, labor cost and tips", and click **Allow**.

You need a Mays account with the manager or admin role. Step-by-step help, with pictures: [Connect Mays to ChatGPT, Claude or Grok](https://mays.app/help/ai-automation/connect-mays-to-chatgpt-or-claude).

## Privacy

Claude works in Mays as you, with exactly your access: your locations and your permissions. People appear as first name and last initial; phone numbers, email addresses and home addresses are never shared. Pay is included only if you can see pay in Mays and choose to include it. Mays keeps a record of each request for 180 days, which you can see under Settings → Connected AI apps, where you can also disconnect at any time. Full details: [Mays privacy policy](https://www.mays.app/privacy).

## Support

[mays.app/contact](https://www.mays.app/contact?topic=support), or open a ticket from **Help** in the Mays web app.

## License

The files in this folder are under the MIT License (see `LICENSE`). Mays itself is a commercial service; using it requires a Mays account and is governed by the [Mays terms of service](https://www.mays.app/terms).
