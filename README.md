# Heritage x Supernal 2027 (hosted copy)

Live for Heritage at https://2027-heritage.links.getsupernal.ai/ (Supernal link router, entry "2027" under client "heritage", URL mode, created 2026-10-13 by Sven's account).
The router forwards the request path to the target host, so this page must sit at a host ROOT: this repo is therefore the account root site `svenboettger-supernal.github.io` (GitHub Pages, branch main, path /). Project sites like heritage-ai-roadmap keep working under their own paths.

Source of truth is the claude.ai client artifact CzHR75GQLotQP3s4VD1Qfc. Rebuild: wrap the artifact source (see ~/Desktop/session-handoffs/heritage-2027-order-form/) in the doctype/head skeleton used in index.html, commit, push. GitHub Pages autoships in about a minute, the router proxies live.
Alternative: upload index.html directly in https://links.getsupernal.ai (File mode, same client + subdomain replaces the entry). The uploader flags the page's script and meta tags, so the "Upload as-is" confirmation has to be clicked by a person.
