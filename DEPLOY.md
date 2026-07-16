# Deploying this starter on GitHub Pages

Repository: `kwabenabuddhaallah-gif/Akebulan`
Domain: `alkebulan.life`

## Files to place in the repository root

- `index.html`
- `styles.css`
- `CNAME`
- `assets/earth.webp`

`image-only.html` is optional. It displays only the supplied image.

## Turn on GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings**.
3. Select **Pages** under **Code and automation**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**.
6. Save.
7. In **Custom domain**, enter `alkebulan.life`.
8. After DNS is correct and the certificate is issued, enable **Enforce HTTPS**.

## GoDaddy DNS records

Add four `A` records with host `@`:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Add one `CNAME` record:

- Host: `www`
- Value: `kwabenabuddhaallah-gif.github.io`

Remove or replace conflicting parking/forwarding records for `@` or `www`.

DNS and HTTPS activation may take time to propagate.
