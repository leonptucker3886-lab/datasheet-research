# Proposal: Hyper-Local Affiliate CTA Sites

**Prepared by:** Sgt datasheet · **Date:** 26 Oct 2026 · **For:** Leon Tucker

## 1. Objective
Launch turnkey call-to-action (CTA) sites in U.S. hyper-local niches that are underrepresented in advertising and have active affiliate, CPL, or pay-per-call payouts.

## 2. Selected niches
| # | Niche | Locale | Why it's underserved | Revenue |
|---|---|---|---|---|
| 1 | Private well water testing | Rural NH & ME | Private wells aren't EPA-regulated; owners carry testing alone; few advertisers | Tap Score affiliate (AWIN) + WQA treatment referrals |
| 2 | Radon testing & mitigation | Iowa | Every county is EPA Zone 1 (highest risk); local search is thinly served | Radon test kits (Tap Score) + mitigation leads via CPL/pay-per-call |
| 3 | Septic pumping & inspection | Rural VT | Agency running real campaigns calls septic "very noncompetitive" | Pay-per-call septic offers + Cinch warranty septic/well-pump add-ons |

Full sourcing: `evidence.md` / `evidence.html`.

## 3. Deliverables (in this repo)
- `index.html` — landing hub linking all sites
- `well/index.html`, `radon/index.html`, `septic/index.html` — CTA sites (call button, lead form, affiliate link, FTC disclosure)
- `evidence.md`, `evidence.html` — evidence sheet
- Live preview: https://practice-niche-kit.vercel.app

## 4. Launch plan
1. **Week 1 — Approvals:** apply to AWIN (Tap Score) and one pay-per-call network; get Cinch affiliate access.
2. **Week 1 — Wire-up:** replace `AFFILIATE_LINK_HERE`, `TRACKING_NUMBER_HERE`, `FORM_ENDPOINT_HERE`.
3. **Week 2 — Validate:** run Google Keyword Planner per target ZIP/county; confirm low CPC and volume.
4. **Week 2–3 — Deploy:** connect this repo to Vercel, add custom domains, submit to Google Search Console.
5. **Week 3–6 — Expand:** add county/town pages; test small paid campaigns ($5–10/day per niche).
6. **Ongoing — Measure:** track calls, form leads, affiliate clicks; cut or scale per niche.

## 5. Success metrics
- Cost per call / lead below network payout
- Affiliate conversion rate per site
- Organic rankings for "[service] + [town]" terms

## 6. Risks & mitigations
| Risk | Mitigation |
|---|---|
| Commission terms vary | Confirm rates on approval before spending |
| Competition claims from industry sources | Keyword Planner check per ZIP before ads |
| Compliance (FTC, lead-gen rules) | Keep disclosures; don't impersonate local providers |
