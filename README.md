# maw.sh — marketing site

Source for the **[maw.sh](https://maw.sh)** marketing site: a static Astro page.

Project repo: <https://github.com/maw-sh/maw>

## Develop

```sh
bun install       # install dependencies
bun run dev       # start local dev server at localhost:4321
bun run build     # build static output → dist/
```

## Deploy

Auto-deployed to **Cloudflare Pages** on push to `main`.

- Build command: `bunx astro build`
- Output directory: `dist/`

## License

[Apache-2.0](LICENSE)
