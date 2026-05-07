# Lincoln Ops Website

Static GitHub Pages site for Lincoln Ops.

## Pages

- Marketing: `https://lincolnops.com/bible-color-quest/`
- Support: `https://lincolnops.com/bible-color-quest/support/`
- Privacy: `https://lincolnops.com/bible-color-quest/privacy/`

## Publishing

Create a public GitHub repository named `lincolnops.github.io` under the `lincolnops` GitHub owner, then push this repository's `main` branch.

The included `CNAME` file sets the custom domain to `lincolnops.com`.

## DNS

Point the apex domain `lincolnops.com` to GitHub Pages:

```text
A @ 185.199.108.153
A @ 185.199.109.153
A @ 185.199.110.153
A @ 185.199.111.153
```

Optional IPv6 records:

```text
AAAA @ 2606:50c0:8000::153
AAAA @ 2606:50c0:8001::153
AAAA @ 2606:50c0:8002::153
AAAA @ 2606:50c0:8003::153
```

Optional `www` redirect:

```text
CNAME www lincolnops.github.io
```
