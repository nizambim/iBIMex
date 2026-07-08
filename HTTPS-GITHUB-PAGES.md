# HTTPS setup for www.i-bimex.com

The website files are prepared for HTTPS:

- `CNAME` is set to `www.i-bimex.com`.
- All local assets use relative paths.
- External links use `https://`.
- The page redirects `http://www.i-bimex.com` to `https://www.i-bimex.com`.

In GitHub Pages:

1. Go to repository `Settings > Pages`.
2. Confirm the custom domain is `www.i-bimex.com`.
3. Wait until the certificate is issued.
4. Tick `Enforce HTTPS`.
5. Save and test `https://www.i-bimex.com`.

If `Enforce HTTPS` is disabled or greyed out, wait a few minutes after DNS check succeeds, then refresh the GitHub Pages settings page.
