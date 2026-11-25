# Kind Reply

Check a reply to a Google review before you post it.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://replies.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http kind-reply https://replies.rowhousesoftware.com/mcp
```

## Tools

- `check_reply`: Checks your reply for things that cause trouble, like promises or blame.
- `safe_reply`: Gives a short, safe reply. For health offices it's the safe choice.
- `pro_status`: Says what the plan on the site adds.

## Free and paid

Free here: check replies as often as you like. On the site, it's $12 a month per location, or $120 a year. It writes replies in your voice and sends a summary each Monday. Try it free for 14 days.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://replies.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
