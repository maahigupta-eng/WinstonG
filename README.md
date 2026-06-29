# WinstonGod

Winston is an interactive sovereignty analysis project built around *Disciplining God: The Meaning of Sovereignty*.

## Structure

- `index.html` — main Winston frontend
- `netlify.toml` — Netlify configuration
- `netlify/functions/chat.js` — Anthropic API proxy function

## Deployment

This repository is designed to deploy on Netlify.

The Netlify environment variable required for the chat function is:

```text
ANTHROPIC_API_KEY
```
