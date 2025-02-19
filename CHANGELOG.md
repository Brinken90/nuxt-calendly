# Changelog

## v0.1.13


### 🩹 Fixes

  - Reverse checks (242088a)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.12


### 🩹 Fixes

  - Switch to pnpm" (daa3563)
  - Type improvements" (37888e2)
  - Use `typeof window` instead of `process` (ebcf5a6)

### 🏡 Chore

  - **release:** V0.1.11" (3199679)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.11


### 🩹 Fixes

  - Switch to pnpm" (daa3563)
  - Type improvements" (37888e2)

### 🏡 Chore

  - **release:** V0.1.11" (3199679)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.10


### 🩹 Fixes

  - Don't add supabase types to nuxt.d.ts (5142317)

### 📖 Documentation

  - Readme update url (8d12047)

### ❤️  Contributors

- Daniel Roe <daniel@roe.dev>
- Madebyfabian <hello@madebyfabian.com>

## v0.1.9


### 🩹 Fixes

  - Use correct types for `CalendlyInlineWidgetOptions` (d9cf00f)
  - Remove uneeded `Partial<>` (0ced639)

### 📖 Documentation

  - Updated readme according nuxt-calendly-docs (e5e3979)
  - Improve playground usability (4b23b77)
  - Fix namings and urls (41fb543)
  - Updated wording (d284aa9)

### 🏡 Chore

  - Remove unneeded imports (c054e93)
  - Fix docs playground example loaded twice (286dd0d)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.8


### 🩹 Fixes

  - Always use dynamic path (a78c846)
  - Attempt to fix vercel prod path issues (8ac784d)
  - Removed `loadWidgetJS` option and load script from calendly directly due to vercel issues (20722b3)

### 🏡 Chore

  - Remove debug (e3c5cf6)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.7


### 🩹 Fixes

  - Use different paths for `nuxt generate` and `nuxt build` (d192e5b)
  - Ignorefile add (1be7de6)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.6


### 🩹 Fixes

  - Change email in changelog (93d98dc)
  - Use static build dir instead of nuxt config (8a9728b)
  - Improve types, remove compiler warning (39adce1)
  - Improve generated path for `nuxt generate`. The svg file is now inlined (you can delete the generated `close-icon.svg`) (237247b)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.5


### 🩹 Fixes

  - Remove non-setup scripts  to fix`[@vue/compiler-sfc]` error (d4d4b50)

### 🏡 Chore

  - Change email in changelog (d530dfc)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.4


### 🩹 Fixes

  - Wip: change order of `<script>` props, attempt to fix `[@vue/compiler-sfc]` error (5036508)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.3


### 🩹 Fixes

  - Adding generated files to ignores (bcb7124)
  - Remove unneeded import (4922c44)
  - Dependencies and release command (19b79cd)
  - Add `dev:generate` (1836f8c)
  - Adding build config (4aa5f77)
  - Remove empty script in test folder (f9204f2)
  - Remove config file (f6558b6)

### 📖 Documentation

  - Adding docs repo (d825931)
  - Add playground link seperately, move ignore files (1f127c5)
  - Move to seperate repo (c2b761f)
  - Improve link (4f14f4f)

### 🏡 Chore

  - Cleanup (3fad548)
  - **release:** V0.1.1 (765127c)
  - **release:** V0.1.2 (aa86490)
  - Add changelog for first version (8912c53)
  - **release:** V0.1.1 (8ab0c1a)
  - Added package.json info (7a20a7d)
  - **release:** V0.1.2 (ab1dd27)

### ❤️  Contributors

- Madebyfabian <beer.fabian@mail.de>

## v0.1.2


### 🩹 Fixes

  - Adding generated files to ignores (bcb7124)
  - Remove unneeded import (4922c44)
  - Dependencies and release command (19b79cd)
  - Add `dev:generate` (1836f8c)
  - Adding build config (4aa5f77)

### 📖 Documentation

  - Adding docs repo (d825931)
  - Add playground link seperately, move ignore files (1f127c5)
  - Move to seperate repo (c2b761f)
  - Improve link (4f14f4f)

### 🏡 Chore

  - Cleanup (3fad548)
  - **release:** V0.1.1 (765127c)
  - **release:** V0.1.2 (aa86490)
  - Add changelog for first version (8912c53)
  - **release:** V0.1.1 (8ab0c1a)
  - Added package.json info (7a20a7d)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.com>

## v0.1.1


### 🩹 Fixes

  - Adding generated files to ignores (bcb7124)
  - Remove unneeded import (4922c44)
  - Dependencies and release command (19b79cd)

### 🏡 Chore

  - Cleanup (3fad548)
  - **release:** V0.1.1 (765127c)
  - **release:** V0.1.2 (aa86490)
  - Add changelog for first version (8912c53)

### ❤️  Contributors

- Madebyfabian <hello@madebyfabian.come>

## v0.1.0

### 🚀 Enhancements

- Implement components, types, module options (0c1814b)
- Implementing the `useCalendly` composable, implement widget locally (5ad8ec3)
- Adding `useCalendlyEventListener`, page titles (bb87281)

### 🩹 Fixes

- Tweak editor config (93c153e)
- Remove volar settings (d255183)
- Syntax (89e7374)
- Updated dev command (abf5bde)
- Updated readme (d7748a9)
- Updated package version (6b79f28)
- Remove empty plugin file (71b214b)
- Add `config` global (4da1282)

### 📖 Documentation

- Improvements (dfdb60b)
- Improve readme (b72fa0d)
- Improvements to readme (f15622f)
- Spacings (a10e118)

### 🏡 Chore

- Init (89781c1)
- Eslint ignore static assets (a1e8fcf)
- Cleanup (3fad548)

### ❤️ Contributors

- Madebyfabian <hello@madebyfabian.com>
