# One More Zero 00.01.04 — privacy release validation (4 November 2026)

This is an **engineering/release checklist**, not part of the player-facing privacy policy. Keep it alongside the relevant release gate in `GraftJ80/OneMoreZero` before publicly promoting 00.01.04.

- [ ] Confirm public 00.01.03 still uses AdMob; compare the actual 00.01.04 Play-delivered Android artifact with the stated Unity LevelPlay + Unity Ads configuration and UMP consent management. Do not treat a branch source check as a signed-binary inventory.
- [ ] Verify Unity Ads and any additional enabled network partners against LevelPlay dashboard assignments and publisher-approved consent messages.
- [ ] Confirm the consent form is presented where required, can reopen, and supports withdrawing choices on a **physical Android device**, including after restart. Previously observed `OMZ-C104` remains a meaningful regression gate.
- [ ] Check ad-request eligibility is not interpreted as positive consent to personalised advertising, including on declines and UMP failures.
- [ ] Reconcile Google Play **Data safety** and **Target audience and content** declarations with all bundled SDKs, permissions and observed data transfers, including ad identifiers and third-party diagnostics.
- [ ] Confirm 13+ target audience statement matches Google Play settings and appropriate ad treatment.
- [ ] Confirm support-correspondence retention practices match the public policy's criteria. Decide and document actual deletion/archive workflow.
- [ ] Confirm international provider data flows and safeguards; do not assume a provider policy link by itself proves a compliant transfer.
- [ ] Confirm the published policy on `https://privacy.graftforge.games/one-more-zero/` matches `one-more-zero/index.html` and `one-more-zero/PRIVACY.md` on the exact deployed commit.

No EAS build, Google Play upload or privacy-site production deployment is authorised by this documentation change. References: OMZ `docs/37-v000104-unity-levelplay-migration.md`; ICO privacy-notice guidance; Google Play Data safety guidance.
