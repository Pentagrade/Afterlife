<p align="center">
  <img src="/docs/public/afterlife.svg" width="360">
</p>

# Afterlife

This repo contains the code and pages for the Afterlife Guides Website, powered by [VitePress](https://vitepress.dev)

Come chat with us on [Fluxer](https://fluxer.gg/afterlife)

## Development

### Requirements
1. Node.js (v20+)
    - [Download Node.js](https://nodejs.org/en/download)
    - Consider using NVM if you use different versions of Node
      - [NVM (Linux/Mac)](https://github.com/nvm-sh/nvm)
      - [NVM (Windows)](https://github.com/coreybutler/nvm-windows)
2. Bun
    - [Full Installation Instructions](https://bun.com/docs/installation)
    - Or just use npm: `npm install -g bun`

### Steps

1. Clone the repo with `git clone https://github.com/Afterlife-Fluxer/Afterlife.git && cd Afterlife`
3. Install the dependencies with `bun install`
4. Run the Dev Server with `bun run docs:dev`

## Deployment

Any changes are automatically built and deployed to GitHub Pages.

The workflow is defined in `.github/workflows/deploy.yml`
