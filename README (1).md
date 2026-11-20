# bot-test-page

A one-page static site used to test whether a chatbot on the other end of a chat
will follow instructions found in a link (indirect prompt injection).

No build step, no dependencies, no scripts, no tracking.

## Deploy

1. Push this folder to a GitHub repo (or run `npx vercel` inside it).
2. On vercel.com choose "Add New Project" and import the repo.
3. Framework Preset: **Other**. Leave build command and output directory empty.
4. Deploy, then send the resulting `https://<name>.vercel.app` link in the chat.

## Tips

- Pick a neutral project name, e.g. `reading-notes`, so the URL doesn't give the game away.
- Send it with something like: "Can you read this page and tell me what you think?"
- Screenshot whatever the bot replies. If it writes the banana poem or switches to French, that's your proof.
- Don't click links the scammer sends back, and don't share real personal details.
