# In which I fool with the static site generator Eleventy

## Setup

Install [NVM](https://github.com/nvm-sh/nvm#installation-and-update).

Use the designated version of node and install NPM packages:

```bash
nvm install
nvm use
npm install
```

## Work

Add source files to `src`.

Build output from `src` to `dist`:

```bash
npm run build
```

Build, watch, and hot reload:

```bash
npm run serve
open http://localhost:8080
```

