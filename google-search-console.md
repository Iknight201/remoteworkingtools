# Google Search Console Setup

## Step 1: Add Your Site
1. Go to https://search.google.com/search-console
2. Enter: `remoteworkingtools.net`
3. Click "Continue"

## Step 2: Verify Ownership (Choose One)

### Option A: DNS Verification (Recommended)
1. In GSC, select "Domain" property type
2. It will show you a TXT record to add
3. Go to Cloudflare Dashboard → DNS → Add record
4. Add the TXT record they provide
5. Come back to GSC and click "Verify"

### Option B: HTML File Upload
1. Download the verification HTML file from GSC
2. I can upload it to the repo and it will deploy
3. Then click "Verify" in GSC

## Step 3: Submit Sitemap
Once verified, submit this sitemap URL:
```
https://remoteworkingtools.net/sitemap.xml
```

## Current Site Info
- **Sitemap URL:** https://remoteworkingtools.net/sitemap.xml
- **Robots.txt:** https://remoteworkingtools.net/robots.txt
- **Site verified:** Not yet - needs your action

---
## What I Can Do
If you choose Option B (HTML file), let me know and I'll:
1. Add the verification HTML file to the repo
2. Push to GitHub
3. Cloudflare will auto-deploy
4. Then you can verify in GSC