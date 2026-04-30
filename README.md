# GD Outdoor Services

Static marketing website for **GD Outdoor Services** (gdoutdoorservices.ca) — landscaping, snowplowing, excavation, and carpentry services.

## Stack

- **Hosting:** Cloudflare Pages (free, unlimited bandwidth)
- **Source:** Static HTML / CSS / MP4 — no build step
- **Forms:** [Web3Forms](https://web3forms.com/) → emails leads to greg@gdoutdoorservices.ca
- **Lead tracking:** n8n webhook → Google Sheet (commission tracking)
- **Lead notifications:** Monthly n8n scheduled workflow → SMS lead count on the 1st

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Home |
| `about.html` | About the company |
| `landscaping.html` | Landscaping service page |
| `snowplowing.html` | Snowplowing service page |
| `excavation.html` | Excavation service page |
| `carpentry.html` | Carpentry service page |
| `service-template.css` | Shared styles for service pages |

## Deploy

Push to `main` → Cloudflare Pages auto-deploys.

```bash
git add .
git commit -m "your message"
git push
```

## Client

GD Outdoor Services
greg@gdoutdoorservices.ca

## Managed by

[Win Big Marketing](https://winbigmarketing.com) / [Absolute Funnels](https://absolutefunnels.com)
