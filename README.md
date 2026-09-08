# Mina Gayid portfolio

Personal portfolio for [Mina Maged Zekry Gayid](https://minagayid.github.io/): an Applied AI Intern, dentist, clinic owner, and healthcare MBA candidate based in Aswan, Egypt.

## What the site presents

- Applied AI and Claude workflow experience from FlyRank AI and Anthropic Academy coursework
- Healthcare, clinic-operations, and public primary-care experience
- Education, selected credentials, technical skills, and collaboration contact links
- A grounded portfolio guide that answers from Mina's published profile facts

## Chatbot

The portfolio assistant is a compact chat UI. When the protected bridge URL is configured, it sends only the visitor's question and short chat history to the private Oracle Qwen model through the server-side gateway; no API key or model is exposed in GitHub Pages. If the bridge is unavailable, it fails closed to a small grounded portfolio guide.

The assistant only answers from Mina's published portfolio facts and is not a medical, dental, legal, or financial advisor.

## Local preview

Open `index.html` directly or serve this folder with any static HTTP server. No build step or secret is required.
