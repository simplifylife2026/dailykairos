# Daily Kairos — Help & Setup Guide

This repository hosts the **Daily Kairos** help website, published via GitHub Pages at [simplifylife2026.github.io/dailykairos](https://simplifylife2026.github.io/dailykairos/).

## About Daily Kairos

Daily Kairos is a personal Bible study companion for iPhone and iPad. It pairs any Scripture passage with AI-generated reflections — context, applications, historical background, cross-references, and more — so every reading becomes a richer, deeper encounter with the text.

The app uses your own API keys to fetch Bible text and generate reflections. Nothing is stored on external servers; all requests go directly from your device to the providers you configure.

## Help pages

| Page | Description |
|---|---|
| [What is Daily Kairos?](docs/index.html) | Overview and getting-started guide |
| [ESV Bible API](docs/setup-esv.html) | Required — how to get a free Crossway API key |
| [Apple Intelligence](docs/setup-apple-intelligence.html) | On-device AI (no API key needed on supported devices) |
| [OpenAI](docs/setup-openai.html) | GPT-4o and other OpenAI models |
| [Anthropic (Claude)](docs/setup-anthropic.html) | Claude Sonnet, Haiku, Opus |
| [Google Gemini](docs/setup-gemini.html) | Gemini 1.5 and Gemini 2.0 |
| [Custom Provider](docs/setup-custom.html) | Groq, OpenRouter, or any OpenAI-compatible endpoint |
| [Privacy Policy](docs/privacy-policy.html) | How the app handles your data |
| [Contact](docs/contact.html) | Get in touch |

## Repository structure

```
docs/          GitHub Pages source
  css/         Shared stylesheet
  img/         Screenshots used in setup guides
  index.html   Overview / landing page
  setup-*.html Per-provider setup guides
  *.html       Other help pages
```

## Development

The site is plain HTML/CSS — no build step required. Edit files in `docs/` and push; GitHub Pages deploys automatically from the `main` branch.
