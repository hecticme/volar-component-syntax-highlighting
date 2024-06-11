## Vue - Official v2.0.20 extension broke component syntax highlighting

Syntax highlighting for components is broken with the following conditions:

- Nuxt version is prior to `v3.12.0`.
- Nuxt auto-import for components is disabled (https://nuxt.com/docs/guide/concepts/auto-imports#auto-imported-components).
- Vue - Official extension's version is either `2.0.20` or `2.0.21`.

This repository is scaffolded with `nuxi@latest`.
