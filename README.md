# Create Nuxtus

NPX package for creating a new ResultCrafter Nuxtus site. A boilerplate based on [Directus](https://directus.io) and [Nuxt](https://nuxtjs.org) (with [Tailwind CSS](https://tailwindcss.nuxtjs.org/) included).

## Usage

```bash
npx create-nuxtus@latest app-name
```

> Replace `app-name` with the name of your project.

### Premium Template

Use the `--template premium` flag to use the premium template with AI skills, layout system, and documentation:

```bash
npx create-nuxtus@latest app-name --template premium
```

Available templates:
- `default` (default) — Free boilerplate with @nuxtus packages
- `premium` — Paid template with layout, AI skills (init-general-site, init-blog, add-collection), Directus MCP config, and docs

## Developing/Debugging

You can modify the branch the script uses by supplying an environment variable `NUXTUS_BRANCH` when executing the script:

```bash
$ NUXTUS_BRANCH=develop ./build/src/main.js app-name
```
