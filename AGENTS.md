# GraftForge Games privacy site — agent instructions

1. At session start, read `.ai-memory/context.yaml` and this file on remote `main`; inspect the current privacy HTML and repository state.
2. This repository is authoritative for the published privacy-policy source text, navigation and presentation. The game implementation and SDK behavior must be verified in their respective game repositories; do not invent compliance claims.
3. Central AI-Memory repository: `GraftJ80/AI-Memory`, project scope `graftforge-games-privacy`. Follow its `docs/agent-gateway.md` and `docs/authority.md`; this YAML is discovery metadata only.
4. Use operator-authorized gateway context/record/sync operations where available. There is no automatic session capture or CLI continuity command. Verify canonical events on central remote `main` before claiming continuity persistence.
5. Persist governed active tasks, unresolved legal/SDK disclosures, blockers and session handovers with source revisions and explicit epistemic status. Respect ownership and authority validation; do not silently turn proposals into accepted decisions.
6. Approved AI-Memory configuration and continuity updates go directly to `main` and must be verified remotely. Normal policy-text/application changes still follow project approvals.
7. Related website staging source is `GraftJ80/GraftForge-website-staging`; website and privacy deployments are separate.
