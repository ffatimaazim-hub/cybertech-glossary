# CyberTech Glossary (AI-Powered)

AI-powered real-time cybersecurity terms & tools search — type any security
term or tool and get an instant, AI-generated explanation, powered by the
Google Gemini API.

🔗 **Live site:** https://ffatimaazim-hub.github.io/cybertech-glossary/

## Created and maintained by

**ffatimaazim-hub** — https://github.com/ffatimaazim-hub

## How it works

- Users enter their own Google Gemini API key (stored only in their own
  browser's local storage — never sent anywhere except directly to Google).
- The app automatically detects which Gemini models are available for that
  key and tries them in order, retrying on temporary overload, until it gets
  a result.
- The AI's Markdown-formatted response is rendered safely (escaped first,
  then formatted) to prevent script injection.

## License

This project is licensed under the [MIT License](./LICENSE) — see the
LICENSE file for details.

**If you fork, copy, or reuse this code, please keep the original copyright
notice and a credit/link back to this repository.** Removing attribution
while redistributing the code is a violation of the license terms.

## Tech stack

- Plain HTML / CSS / JavaScript (no build step, no framework)
- Google Gemini API (`generativelanguage.googleapis.com`)
- Hosted via GitHub Pages
