# Website — actual location and deployment

**Published website source = the root of this repository** (`index.html`, `about/`, `ru/`, `assets/`, `claude/`, `system/`, `case/`, `guide/`, `changelog/`, `favicon.svg`, `CNAME`).

The `website/` folder contains *only this explanation*, not a second copy of the site. This is deliberate: copying the same website into several folders would re-create the duplication being removed.

- Canonical site: https://influenceros.dynv6.net/
- Pages source: `main` branch, `/` root, custom domain from root `CNAME`.
- HTTPS enforcement: enabled at the 2026-10-12 check.
- EN/RU routes use the same root asset paths; moving or renaming directories requires a coordinated deployment.
- Historical GitHub Pages presentation: https://tswetc.github.io/influencer-os-startup-site/ (still public, not the canonical source).
- FreeDNS alternate: https://influenceros.mooo.com/ (separate live Pages repo; do not disconnect without DNS/Pages dependency review).

For changes: see [operations and rollback](../docs/OPERATIONS.md). Do not place private work-in-progress media or legal records under the public website source.
