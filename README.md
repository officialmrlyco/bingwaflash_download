# Bingwa Flash Download Page

This repository publishes the direct installer page for `download.bingwaflash.co.ke`.

The page intentionally uses `noindex` meta tags instead of a blocking `robots.txt` rule. Search crawlers must be able to fetch the page before they can remove it from search results.

Cloudflare DNS should contain this record:

```text
Type: CNAME
Name: download
Target: officialmrlyco.github.io
Proxy status: DNS only
```
