# Profile publication checklist

The profile and Super Schema preview are published. The items below are the remaining inputs needed to replace planning placeholders with implementation evidence.

## Details to fill in

| Item | Fill in | Where to update |
| --- | --- | --- |
| **Super Schema repository** | Final owner and public repository URL. Temporary assumption: `github.com/jhsenjaliya/super-schema`. | Replace preview links in `README.md` with the repository URL; update `SUPER_SCHEMA.md`. |
| **Public demo** | Runnable example URL, recording/GIF URL, and exact command to reproduce it. | `SUPER_SCHEMA.md`; add a demo link beside Super Schema in `README.md`. |
| **MCP server** | Confirm that “MCV” in the brief meant **MCP (Model Context Protocol)**. Supply the actual package/command, transport, tools, client configuration, and one successful workflow. | `SUPER_SCHEMA.md` and the implementation repository's README. |
| **Implemented capabilities** | List what works today versus what is planned; document supported model features and tested emission targets. | Replace the proposed-target wording with a tested support matrix in the implementation repository. |
| **Release details** | License, installation prerequisites, initial version, and release status. | Standalone repository, once available. |
| **Engineering outcomes** | Two or three accurate, publicly shareable outcomes with their scope and measurement period. | Replace the hidden outcome TODO in `README.md`. |
| **Current-work updates** | Links and dates for substantive progress: a release, demo, proposal update, article, or talk. | Keep the Current work section concise and refresh it as work ships. |

## Outcome prompts

Fill only the metrics you can substantiate and share publicly. Leave the rest out.

| Outcome | Before | After | Scope / time period / evidence |
| --- | --- | --- | --- |
| Pipeline onboarding or developer setup time | TODO | TODO | TODO |
| Reliability, incident rate, or detection time | TODO | TODO | TODO |
| Platform adoption, operating cost, or processing efficiency | TODO | TODO | TODO |

Translate each completed row into one sentence describing your contribution and the resulting behavior or outcome. Do not use estimates as measured results.

## Super Schema demo acceptance checklist

- [ ] A fresh user can follow the documented installation steps.
- [ ] The example model and generated outputs are checked into the repository.
- [ ] The same entity is demonstrated across at least two implemented targets.
- [ ] Validation feedback is visible and explained.
- [ ] MCP setup works with at least one documented agent client.
- [ ] Limitations, target-specific semantics, and version requirements are stated.
- [ ] The demo makes clear whether it generates files, applies schemas, or performs migrations.

## Profile updates when the repository is public

- [ ] Replace the temporary project-preview links with the final repository and demo links.
- [ ] Pin Super Schema first and the data-product workshop second.
- [ ] Keep TypeSpec and selected active contribution repositories after original work.
- [ ] The archived Eagle project remains acknowledged in the community paragraph.
- [ ] Verify the links and generated README rendering.

The public profile uses coming-soon language for unreleased material; no implementation outcomes or benchmark numbers have been invented.
