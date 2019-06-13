# create-snips-action
#### Generator for writing Snips action code in Javascript/Typescript.

## Purpose

Create a fully fledged Snips action in a single command.

## Usage

```bash
# Run this in your favourite terminal.
npm init snips-action
```

## Features

**📦Uses the [javascript-toolkit](https://github.com/snipsco/snips-javascript-toolkit) package under the hood.**

- 🐚 Action code template (folder structure & files) fully commented
- ⚚ Platform interactions going through [hermes-javascript](https://www.npmjs.com/package/hermes-javascript)
- 💬 Internationalization (i18n) using [i18next](https://www.i18next.com)
- 📞 Api calls using [wretch](https://github.com/elbywan/wretch) and [wretch-middlewares](https://github.com/elbywan/wretch-middlewares)
- ✍️ Logger with [debug](https://github.com/visionmedia/debug)
- ✔️ Flows testing using [jest](https://jestjs.io/) and [mqtt](https://github.com/mqttjs).
- ✅ Linter with [eslint](https://eslint.org/)
