# Brian Munene Mwirigi

I build developer tools. Five CLI packages on npm, each solving a specific problem I hit while writing code.

CS undergrad at Strathmore University, Nairobi. Interested in developer tooling, AI infrastructure, and systems programming.

[brianmunene.me](https://brianmunene.me) · [LinkedIn](https://www.linkedin.com/in/brian-munene-mwirigi) · [npm](https://www.npmjs.com/~brian-mwirigi)

---

### Shipped

| | What it does | Why it exists |
|:--|:--|:--|
| [**codesession-cli**](https://github.com/brian-mwirigi/codesession-cli) | Tracks AI-assisted coding sessions — time, files changed, git diffs, token costs across providers. Uses file system watchers and git process spawning to capture everything automatically. | I was losing track of how much AI-assisted coding actually cost per session. No tool existed to measure it end-to-end. |
| [**aitoken-cli**](https://github.com/brian-mwirigi/aitoken-cli) | Unified dashboard for AI API token usage and costs. Normalizes pricing across OpenAI, Anthropic, and Google (per-1K vs per-1M, input/output rate splits). | Every provider reports costs differently. I needed one view across all of them. |
| [**apisnap-cli**](https://github.com/brian-mwirigi/apisnap-cli) | HTTP proxy that captures live API traffic and auto-generates Jest tests and MSW mock handlers from recorded requests. | Writing mocks by hand for integration tests is tedious and error-prone. This records real traffic and produces ready-to-use test code. |
| [**devmem-cli**](https://github.com/brian-mwirigi/devmem-cli) | Persistent cross-project code memory for AI coding assistants. Extracts and indexes code patterns so AI tools have context beyond the current file. | AI assistants forget everything between sessions. This gives them long-term memory across your entire codebase. |
| [**runbook-cli**](https://github.com/brian-mwirigi/runbook-cli) | Global command registry — save project-specific commands once, execute from any directory with correct working-directory context. | I was tired of `cd`-ing into projects just to remember and run their specific build/deploy commands. |

### Other work

[**Jarvis**](https://github.com/brian-mwirigi/Jarvis) — Voice-controlled AI assistant (Python). NLP pipeline, task automation, smart home integration.

[**brianmunene.me**](https://brianmunene.me) — Portfolio and blog. Next.js 14, TypeScript, MDX, Tailwind CSS. Statically generated, deployed on Vercel.

### Stack

```
Languages    TypeScript · Python · JavaScript
Frontend     React · Next.js · Tailwind CSS
Backend      Node.js · Flask · Express
Data         PostgreSQL · SQLite
Infra        Docker · Git · Vercel · GitHub Actions
```

---

<sub>Open to opportunities in developer tooling, AI infrastructure, and systems engineering. Reach me at brian@brianmunene.me</sub>
