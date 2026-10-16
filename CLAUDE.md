# Cloudflare Pages deployment — 回路くるり

This repository contains the static browser puzzle at `kairo-kururi/index.html`.

Cloudflare MCP is configured in `.mcp.json` (OAuth authorization by the account owner is required).

When asked to deploy 回路くるり:
1. Use the configured official Cloudflare API MCP and verify the authenticated Cloudflare account.
2. Create or update a **Cloudflare Pages** project named `kairo-kururi` (if available).
3. Prefer GitHub integration with repository `matsuishogo/matsuishogo.github.io`, production branch `main`, output directory `kairo-kururi`, no framework and no build step.
4. Do not change the existing GitHub Pages home page or the contents of other subdirectories.
5. Verify a real successful production deployment and the exact `*.pages.dev` URL; never assume availability or success.
6. Ask the account owner to complete any Cloudflare / GitHub OAuth authorization in their own browser. Never request that API tokens be pasted into a chat.
