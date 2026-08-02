# Mina Gayid portfolio

Static GitHub Pages portfolio for Mina Maged Zekry Gayid.

## Chatbot

The portfolio assistant uses Puter.js to call the hosted `openai/gpt-oss-20b` open-weight model. It does not put an API key in this public repository, and it no longer downloads a large model into the visitor's browser. If hosted inference is unavailable, it immediately falls back to a small, grounded portfolio guide so the chatbot still responds quickly.

Puter's user-pays model keeps the integration free for the site owner; visitors may be asked to use Puter's own access flow. The assistant only answers from Mina's published portfolio facts and is not a medical, dental, legal, or financial advisor.

## Local preview

Open `index.html` directly or serve this folder with any static HTTP server. No build step or secret is required.
