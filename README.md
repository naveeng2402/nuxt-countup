<!--
Get your module up and running quickly.

Find and replace all on all files (CMD+SHIFT+F):
- Name: CountUp.js
- Package name: nuxt-countup
- Description: Nuxt wrapper for countup.js
-->

# CountUp.js

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

Nuxt 3 module for countup.js - A dependency-free, lightweight JavaScript class that can be used to quickly create animations that display numerical data in a more interesting way.

- [✨ &nbsp;Release Notes](/CHANGELOG.md)
<!-- - [🏀 Online playground](https://stackblitz.com/github/your-org/nuxt-countup?file=playground%2Fapp.vue) -->
<!-- - [📖 &nbsp;Documentation](https://example.com) -->

## Features

<!-- Highlight some of the features your module provide here -->
- To be updated

## Quick Setup

1. Add `nuxt-countup` dependency to your project

```bash
# Using pnpm
pnpm add -D nuxt-countup

# Using yarn
yarn add --dev nuxt-countup

# Using npm
npm install --save-dev nuxt-countup
```

2. Add `nuxt-countup` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    'nuxt-countup'
  ]
})
```

That's it! You can now use CountUp.js in your Nuxt app ✨

## Development

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-countup/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/nuxt-countup

[npm-downloads-src]: https://img.shields.io/npm/dm/nuxt-countup.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/nuxt-countup

[license-src]: https://img.shields.io/npm/l/nuxt-countup.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/nuxt-countup

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
