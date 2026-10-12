# Active domain inventory

Checked 2026-10-12. The term **active** means the site answered over HTTPS at the time tested, not that it is the registered company's own second-level domain.

| Host or address | Role | Website | Email / DNS | GitHub source |
| --- | --- | --- | --- | --- |
| `influenceros.dynv6.net` | **Canonical Anthropic applicant website** | HTTPS 200, GitHub Pages `main`, enforced HTTPS | MX routes to Forward Email; matching `founder@` previously received authentication email | [influencer-os-startup-dynv6](https://github.com/tswetc/influencer-os-startup-dynv6) |
| `influenceros.mooo.com` | Working alternate public page | HTTPS 200, distinct GitHub Pages repo | MX at this exact name absent in the 2026-10-12 DNS check; no company-mail claim | [influencer-os-startup-domain](https://github.com/tswetc/influencer-os-startup-domain) |
| `tswetc.github.io/influencer-os-startup-site/` | Older public presentation, preserved as historical reference | HTTPS 200; relative-path deployment | No matching company mailbox controlled at `tswetc.github.io` | [influencer-os-startup-site](https://github.com/tswetc/influencer-os-startup-site) |
| `v0-influenceros01.vercel.app` | Original licensed-app entry | HTTPS 200 | Not used as company-email identity | **Separate** app deployment, not a GitHub Pages repo here |

**DNS hygiene:** The exact root `CNAME` in this repository must continue to name `influenceros.dynv6.net`. Do not remove active MX while Anthropic might reply. An HTTP 200 or DNS MX lookup by itself does **not** prove current end-to-end email delivery; test it before changing application contacts.

Never copy publicly resolvable mail-routing TXT contents into this repository: they may reveal a private destination inbox.
