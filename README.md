# Mina Gayid portfolio

Personal portfolio for [Mina Maged Zekry Gayid](https://minagayid.github.io/): an Applied AI Intern, dentist, clinic owner, and healthcare MBA candidate based in Aswan, Egypt.

## What the site presents

- Applied AI and Claude workflow experience from FlyRank AI and Anthropic Academy coursework
- Healthcare, clinic-operations, and public primary-care experience
- Education, selected credentials, technical skills, and collaboration contact links
- A grounded portfolio guide that answers from Mina's published profile facts

## Chatbot

The portfolio assistant uses Puter.js to call the hosted `openai/gpt-oss-20b` open-weight model. It does not put an API key in this public repository or download a large model into a visitor's browser. If hosted inference is unavailable, it falls back to a small, grounded portfolio guide so the site remains useful and responsive.

The assistant only answers from Mina's published portfolio facts and is not a medical, dental, legal, or financial advisor.

## Local preview

Open `index.html` directly or serve this folder with any static HTTP server. No build step or secret is required.
