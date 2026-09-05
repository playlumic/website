# Lumic website

Phase 01 public home for Lumic.

## Cloudflare deployment

This repository deploys as a Cloudflare Worker with Static Assets.

- Production branch: `main`
- Deploy command: `npx wrangler deploy`
- Static asset directory: repository root (`.`)
- Custom domain: `playlumic.com`
- Custom 404 handling is configured in `wrangler.jsonc`
- Non-public repository/build files are excluded through `.assetsignore`

Every push to `main` should trigger a new production deployment through the connected Cloudflare project.

The site is static HTML. Buttondown signup forms are wired to the `playlumic` list.

## Current public social links

- X: https://x.com/playlumic
- Instagram: https://instagram.com/playlumic
- YouTube: https://youtube.com/@playlumic
- LinkedIn: https://linkedin.com/company/playlumic
- Discord: https://discord.gg/Y7VMJQQSV
