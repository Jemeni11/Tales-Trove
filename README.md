<div align="center">
  <a href="https://github.com/Jemeni11/Tales-Trove">
    <img src="assets/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">TalesTrove</h3>

  <p align="center">
    TalesTrove is a browser extension that allows users to easily save links to their favorite fictional stories and series from various platforms.
    <br />
    <br />
    <a href="https://github.com/Jemeni11/Tales-Trove"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>

## Supported Sites

- FanFiction.net
  - Favorites
  - Following
- Archive Of Our Own
  - Work Subscriptions
  - Series Subscriptions
  - Author Subscriptions

## Sites Planned for Support

- SpaceBattles
  - Following Threads
- QuestionableQuesting
  - Following Threads

## Features

- Save favorites and followed stories from various websites.
- Export saved links in various formats (JSON, TXT, CSV, HTML).

## Installation

[Instructions for installing the browser extension - to be added]

## Usage

1. Click on the TalesTrove icon in your browser's extension area.
2. Configure your preferences for each supported website.
3. Use the "Download Links" section to export your saved links.

## Development

This project was built using the [Plasmo](https://docs.plasmo.com/) framework.

### Getting Started

Clone the repository and install the dependencies:

```bash
git clone https://www.github.com/Jemeni11/Tales-Trove.git Tales-Trove
cd Tales-Trove
pnpm install
```

First, run the development server:

```bash
pnpm dev
```

Open your browser and load the appropriate development build. For example, if you are developing for the chrome browser, using manifest v3, use: `build/chrome-mv3-dev`.

You can start editing the popup by modifying `popup.tsx`. It should auto-update as you make changes.

For further guidance, [visit Plasmo's Documentation](https://docs.plasmo.com/)

### Making production build

Run the following:

```bash
pnpm build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

## Contributing

[Guidelines for contributing to the project - to be added]

## License

[GPL-3.0 license](/LICENSE)

## Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!
