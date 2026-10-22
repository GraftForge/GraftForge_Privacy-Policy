# GraftForge Games privacy site — agent instructions

1. At session start, read `.ai-memory/context.yaml` and this file on remote `main`; inspect the current privacy HTML and repository state.
2. This repository is authoritative for the published privacy-policy source text, navigation and presentation. The game implementation and SDK behavior must be verified in their respective game repositories; do not invent compliance claims.
3. Central AI-Memory repository: `GraftJ80/AI-Memory`, project scope `graftforge-games-privacy`. Follow its `docs/trusted-github-sessions.md` and `docs/authority.md`; this YAML is discovery metadata only.
4. Read and write AI-Memory using existing GitHub repository access and SHA-checked commits; no deployed gateway, operator principal or special AI-Memory login is required. There is no automatic session capture. Verify canonical events on central remote `main` before claiming continuity persistence.
5. Persist governed active tasks, unresolved legal/SDK disclosures, blockers and session handovers with source revisions and explicit epistemic status. Respect declared work ownership and user approval boundaries; do not silently turn proposals into accepted decisions.
6. Approved AI-Memory configuration and continuity updates go directly to `main` and must be verified remotely. Normal policy-text/application changes still follow project approvals.
7. Related website staging source is `GraftJ80/GraftForge-website-staging`; website and privacy deployments are separate.
