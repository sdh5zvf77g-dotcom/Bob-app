# Bob — Personal AI Assistant

Bob is a single-page browser AI assistant designed to run on GitHub Pages.

## GitHub Pages setup

1. Upload **all files in this folder** to the root of a GitHub repository.
2. Make sure the main file is named **`index.html`**.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and open the generated `https://YOUR-USER.github.io/YOUR-REPO/` address.

Do **not** open the GitHub `blob` page or a `raw.githubusercontent.com` URL as the app URL.

## AI backend

Bob can connect to an OpenAI-compatible AI endpoint from Settings. API keys entered in a static GitHub Pages site are stored in the browser and are visible to the browser/network request. Do not use a secret production key in a public client. For a production deployment, put the AI key behind your own server-side proxy.

## Included

- Local memory and conversation history
- Tasks, goals, habits and notes
- AI agent tool loop
- Research tools
- AI learning/evaluation lab
- Agent telemetry
- Today dashboard
- Internet radio discovery
- Optional voice, camera and image features
- GitHub Pages environment guidance
