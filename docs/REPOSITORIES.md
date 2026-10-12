# GitHub repository map and consolidation decision

| Repo | Visibility / purpose | Maintenance decision |
| --- | --- | --- |
| [influencer-os-startup-dynv6](https://github.com/tswetc/influencer-os-startup-dynv6) | PUBLIC. **Canonical startup dossier + active Anthropic applicant site**. | One main public source of startup docs and status. Root GitHub Pages publishing remains unchanged. |
| [influencer-os-startup-domain](https://github.com/tswetc/influencer-os-startup-domain) | PUBLIC. Still serves working `influenceros.mooo.com`. | Keep until alternate domain migration/redirect is planned and approved. |
| [influencer-os-startup-site](https://github.com/tswetc/influencer-os-startup-site) | PUBLIC. Older relative-path visual site `tswetc.github.io/influencer-os-startup-site/`. | Keep as historical, externally reachable page while links may exist in applications. Archive only after redirect/link dependency checks. |
| `tswetc/influencer-os` | **PRIVATE** full commercial app source. | Do NOT merge into this public repo. |
| [tswetc/runs-at.dev](https://github.com/tswetc/runs-at.dev) | PUBLIC fork of third-party registry; supports an [OPEN claim PR](https://github.com/preetmendpara/runs-at.dev/pull/11). | External fork stays separate until upstream resolves the request. |

**One-repository interpretation:** maintain all NEW PUBLIC startup documents here; the other site repositories are preserved **only as serving endpoints / historical URLs**, not new sources of truth. This is not yet a literal one-repo GitHub account because deleting/archiving currently deployed sites or an active third-party fork could disrupt existing URLs.

The project-wide archival backup and founder's business docs live in private Google Drive, not in GitHub. Local working sources are on the external SSD pending independent Step 4. No directories from the paid app, old stage histories or private receipts are copied into the public website repo.

GitHub Pages is configured to publish from `main:/`; `website/README.md` is a pointer, not a relocation. Site copy and static assets at root must remain byte-identical in this documentary consolidation.
