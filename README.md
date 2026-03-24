<div align="center">

![Eve Frontier App Directory](fab.webp)

# Eve Frontier App Directory

A community-maintained directory of third-party apps and tools for Eve Frontier.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Apps](https://img.shields.io/badge/dynamic/json?style=flat-square&label=apps&color=blueviolet&query=%24.length&url=https%3A%2F%2Fraw.githubusercontent.com%2FEconmartin%2Feve-frontier-apps%2Fmain%2Furls.json)](urls.json)

[View the Directory](https://evefrontier.space/directory) · [Submit your app](CONTRIBUTING.md) · [Report an issue](../../issues)

</div>

---

## What is this?

This repo is the data source for the [Eve Frontier App Directory](https://evefrontier.space/directory). Anyone can submit their app by opening a pull request — just add your URL to `urls.json`.

The directory site pulls app names, descriptions, and images automatically from each URL's og tags, so make sure your site has them set.

---

## Screenshot

<!-- Replace this with a real screenshot once the directory is live -->
![Directory preview](https://placehold.co/1200x600/0a0a0f/444444?text=Screenshot+coming+soon&font=montserrat)

---

## Submitting your app

1. Open `urls.json` in GitHub
2. Click the pencil ✏️ icon to edit
3. Add your entry to the array:

```json
{
  "url": "https://your-app.com",
  "tags": []
}
```

4. Scroll down and click **Propose changes**
5. Click **Create pull request**

That's it. Once reviewed and merged your app will appear in the directory automatically.

---

## Tags

Tags are optional. The only supported tag right now is `dapp` — use it if your app is a decentralised app running on the Eve Frontier smart contract layer and is accessible through a [Smart Assembly](https://docs.evefrontier.com/smart-assemblies/introduction) .

More tags will be added as the directory grows.

```json
{
  "url": "https://your-dapp.com",
  "tags": ["dapp"]
}
```

---

## og tags

The directory pulls your app's title, description, and image from your site's og tags. Make sure you have these in your `<head>`:

```html
<meta property="og:title" content="Your App Name" />
<meta property="og:description" content="A short description of your app" />
<meta property="og:image" content="https://your-app.com/preview.png" />
```

If these are missing your app will still appear in the directory but may look sparse.

---

## Rules

- The app must be accessible from within Eve Frontier's in-game browser
- No malicious or deceptive apps
- One entry per URL — don't submit duplicates

---

<div align="center">

Built with ❤️ by the Eve Frontier community

</div>
