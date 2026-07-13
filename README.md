# burgholzer.me

Source for [burgholzer.me](https://burgholzer.me), built with Hugo and Hugo Blox.

## Prerequisites

- Hugo 0.164.0
- Go 1.19 or later (for Hugo modules)
- Node.js 22 or later

## Local development

```sh
npm ci
hugo server --disableFastRender
```

## Production build

```sh
npm ci
hugo --gc --minify
```

Netlify runs the same build command and deploys `public/`.
