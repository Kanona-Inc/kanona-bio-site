# Kanona Bio

Static local recapitulation of the existing Squarespace homepage. No framework or build dependencies; deployable files are in `public/`.

## Local preview

```sh
python3 -m http.server 8080 --bind 127.0.0.1 --directory public
```

Open http://127.0.0.1:8080/ . The server binds to this Mac only. Python’s basic server does not apply Cloudflare `_headers`, `_redirects` or custom unknown-route handling; verify those behaviors on the approved hosting preview.

## Contact

The recipient is `hello@kanona.bio`, verified on 2026-09-15 as an alias of Jonathan’s active Google Workspace account. One central Get in touch link scrolls to the contact section. Its clickable email address prepares a draft via `mailto:`. Jonathan confirmed receiving a test message at the alias on 2026-09-15. The site uses no JavaScript and sends no messages itself.

Source text and logo provenance, reference views, contact verification and review notes are in the relaunch work order at `../kanona-agent-ops/work-orders/2026-09-15-kanona-bio-site-relaunch/`.

## Publication

Published with Jonathan’s approval on 2026-09-15 at https://kanona-bio.pages.dev/ using Cloudflare Pages dashboard Direct Upload. Deployment: d922d531-799b-498c-be07-d2fd6053cc09. The ten-file ZIP and release manifest are in the work order’s `review/` directory.

Public homepage/assets, HTTPS, security headers and custom 404 handling pass verification; served bytes match the release manifest. Hosted visual/CSP-console verification remains pending because dedicated Chrome navigation returned ERR_ABORTED. Local desktop/mobile checks passed.

Canonical site remains `https://kanona.bio/` in metadata; the domain has not been connected. Custom-domain redirects, zone creation, DNSSEC and nameserver transition remain subject to the work-order migration plan and Jonathan’s separate approval. Email DNS must remain unchanged. No API token, git commit or paid service was used for this deployment.
