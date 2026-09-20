# life-reel.app

Landing page for **Life Reel: Photo & Video Diary** (iOS).

## Deploy

Hosted on [GitHub Pages](https://pages.github.com/) with custom domain `life-reel.app`.

```bash
git push origin main
```

## GitHub Pages setup

1. Create repo `lifereel` on GitHub (public)
2. Push this folder
3. **Settings → Pages →** deploy from `main` branch, root `/`
4. Set custom domain: `life-reel.app`
5. Enable **Enforce HTTPS** after DNS check passes

## Cloudflare DNS

For apex domain `life-reel.app`:

| Type | Name | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `moonmoonnotsun.github.io` |

Use DNS only (grey cloud). Set SSL mode to **Full** in Cloudflare.

## Meta ads

Use Traffic → Link clicks → `https://life-reel.app/get/`

## Links

- App Store: https://apps.apple.com/app/id6760628421
- Privacy: https://mpc-app-c2e7a.web.app/moments-privacy.html
- Terms: https://mpc-app-c2e7a.web.app/moments-terms.html

## Images

Replace placeholders under `assets/images/life-reel/optimized/` when ready:

- `logo.png` — app icon
- `hero.png` — phone / hero screenshot
- `01-…jpg` etc. — screenshot carousel (optional)
