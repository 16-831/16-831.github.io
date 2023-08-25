# 6.884 Computational Sensorimotor Learning

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

## Installation

Install Node.js
```bash

## Install nvm: https://github.com/nvm-sh/nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash


## Install Node.js
nvm install node

# =================
# Other packages
npm i -g yarn
npm i -g npx
```


## Running the deveopment server (Preview the website)
```bash
cd <root dir of the website>
npm run start
```

## Build (To put it on a web server)
```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

After this, you can run `npm run serve` to preview the website locally.

## Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```
If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.