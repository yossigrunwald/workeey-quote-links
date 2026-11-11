# Workeey Quote Links

Quote Links is a free tool from [Workeey](https://www.workeey.com/) that turns a quote into a link the
customer approves online. Nobody needs an account.

Quote Links is separate from the Workeey app: it is not the estimates inside the app.

- The **customer link** opens a page where the customer sees the quote, picks an option and any add-ons, types their
  name, and approves, declines or asks for changes.
- The **private link** shows the business that answer and lets them revise or cancel the quote.

This repository holds one file: [`server.json`](server.json), the description of the tool's MCP server, for AI
assistants and the directories that list such tools.

## For AI assistants and developers

Everything an assistant needs is on one page:

**https://www.workeey.com/quote-links/for-ai/**

It covers the ready-made link (no connection needed: the link opens a filled-in draft on the user's own screen, and
nothing is published until they check it and press Create approval link themselves), and the MCP server.

- MCP server (streamable HTTP, no sign-in): `https://www.workeey.com/api/mcp`
- Try the tool yourself: https://www.workeey.com/quote-links/

## Questions

support@workeey.com
