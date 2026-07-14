# GD Outdoor Services — Fredericton Expansion Playbook
_Created 2026-07-02. Note: this file lives in the deploy repo — delete or .gitignore it before pushing if you don't want it public._

## What's already done (this session)
Five new pages, all wired into the site, sitemap (31 URLs), and lead plumbing (Web3Forms + n8n webhook → Sheet + email Greg + SMS):

- /excavation-fredericton.html
- /retaining-walls-fredericton.html
- /landscaping-fredericton.html
- /carpentry-fredericton.html
- /snowplowing-fredericton.html

Internal links added: all 4 service hubs + retaining-walls hub + homepage (service-area section, footers, meta/OG). Copy uses the existing "vetted network of local contractors" positioning — accurate for the subcontracting model, no false "based in Fredericton" claims.

## Step 1 — Deploy (you, ~2 min)
From your Mac terminal in this folder:

```
git add -A
git commit -m "Add Fredericton location pages + internal links + sitemap"
git push
```

Cloudflare Pages auto-deploys from main. Verify live at gdoutdoorservices.ca/excavation-fredericton (CF redirects .html → extensionless).

## Step 2 — GSC (you, ~5 min, after deploy)
1. Search Console → Sitemaps → resubmit sitemap.xml (should show 31 discovered).
2. URL Inspection → Request Indexing for each of the 5 new URLs (excavation and retaining-walls first — highest value).

## Step 3 — Google Business Profile (when your partner's address lands)
**Do NOT change the existing GBP's location** — that kills the Saint John map pack presence that's currently producing leads.

Instead, create a SECOND profile:
1. business.google.com → Add business → "GD Outdoor Services – Fredericton" (keep the brand name; the suffix is fine since it's a distinct location).
2. Address: the partner's real Fredericton street address. Google requires a real, staffed location OR you verify there and then hide the address (service-area business). For a contractor, hide-address SAB mode is correct: verify at the address, then set "Service area" to Fredericton, New Maryland, Hanwell, Lincoln, Oromocto and hide the street address.
3. Category primary: **Excavating contractor**. Secondary: Landscaper, Deck builder, Snow removal service, Retaining wall supplier (if offered).
4. Website field: link to https://gdoutdoorservices.ca/excavation-fredericton (NOT the homepage — the homepage is Saint John-targeted).
5. Phone: ideally a distinct Fredericton-local number that forwards (matters for NAP consistency + call tracking; a second Retell/Twilio 506 number works). Same number as Saint John is acceptable but weaker.
6. Verification is usually video (walk-through showing signage/vehicle/tools at the address). Have the partner ready to help.
7. After verification: 10+ photos (crew, equipment, completed Fredericton-area jobs as they happen), business hours, services list, and start collecting reviews from the very first Fredericton jobs — reviews mentioning "Fredericton" are the strongest map-pack signal.

## Step 4 — Citations (after GBP exists, ~1 hr)
Add the Fredericton location (same NAP as the GBP) to: Bing Places, 411.ca, YellowPages.ca, Facebook page (add service area). Consistency matters more than volume.

## Honest expectations
- Organic: new city pages on an already-indexed domain typically start showing impressions in 1–3 weeks, meaningful clicks in 4–8. Fredericton competition for excavation/landscaping is similar to Saint John — winnable.
- Map pack: won't happen from the website alone. It requires the Fredericton GBP (Step 3). That's the single highest-leverage item on this list.
- The "leads are busy" problem in Saint John is a demand-capacity mismatch; in Fredericton the partner's contractor network is the capacity, so speed-to-lead matters — the existing SMS/email/Sheet plumbing already covers Fredericton leads (forms tag source_page, and city defaults to "Fredericton, NB").

## Optional next moves (not done, tell me if you want them)
- Oromocto + New Maryland dedicated pages (thin market, do after Fredericton indexes).
- Fredericton-specific photos on the pages once first jobs complete (currently the pages have no project photos — real ones beat stock).
- Add Fredericton footer links to the 17 existing city pages (minor crawl benefit).
- A second Retell receptionist number with a Fredericton identity.
