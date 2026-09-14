# thewardogsguide.com

Static WARDOGS Steam Early Access guide site for [thewardogsguide.com](https://thewardogsguide.com).

## Cloudflare Pages (Git auto-deploy)

1. Cloudflare → Workers & Pages → Create → Connect to Git → this repository.
2. **Production branch:** `main`
3. **Build command:** leave empty
4. **Build output directory:** `/` (repo root is the publish root)
5. Add custom domain `thewardogsguide.com` (www → apex recommended).

Every push to `main` redeploys automatically once Git is connected.

## Local preview

Serve this folder with any static server, e.g. `python -m http.server 8080`.
