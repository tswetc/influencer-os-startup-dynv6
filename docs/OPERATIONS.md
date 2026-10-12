# Public-site operations and safe rollback

## Canonical deployment

1. Only modify `main` in `tswetc/influencer-os-startup-dynv6` after reviewing the change for secrets, PII and product-claim accuracy.
2. GitHub Pages publishes from **main / root** to `https://influenceros.dynv6.net/`; the root `CNAME` must remain unchanged while applications are pending.
3. Check GitHub Pages `built` state and live HTTPS 200 after each update; confirm at least `/`, `/about/`, `/ru/about/`, `/claude/`, and video URLs.
4. Protect working mail: do not overwrite DNS MX/TXT or company contact email when changing site docs.
5. Rollback by reverting the specific bad commit on `main` (do not erase history or force-push), then recheck the published domain.

## Historical domains and GitHub repos

Three public Pages deployments were independently responding as of 2026-10-12. **Do not archive/delete/redirect them until** checking external backlinks, existing application form URLs, GitHub Pages custom domains and any future domain redirects. The user wants low clutter, not broken inbound verification.

The `runs-at.dev` fork cannot be folded into a product repo while upstream claim #11 is under review.

## Confidentiality

Public GitHub is not a substitute for private Google Drive. Do not commit API keys, authentication cookies, DNS forwarding TXT targets, IDs and tax records, CV PDFs, full submitted forms, personal email, unlicensed source assets, unreleased application builds, or media whose public-rights status is unknown. Avoid publishing the Drive's internal sharing URL in public docs.

## Archiving and SSD cleanup

Cloud archives and their restored hashes were checked separately during Stage 2. That does NOT grant deletion authority for the SSD. Clean outdated local build stages only in a **separate Step 4** after generating a named deletion list and getting the owner's approval. Preserve private original software and unrelated Mac/SSD projects entirely.
