# All Weather Roofing Systems — Website Deployment Guide
Generated: June 24, 2026 | Core 30 Local SEO Platform (Caleb Ulku Methodology)

## What's in This ZIP

| File | Purpose |
|------|---------|
| `index.html` | Homepage |
| `[page]/index.html` | Each inner page (94 pages) |
| `sitemap.xml` | Submit to Google Search Console |
| `robots.txt` | Search engine crawl rules |
| `404.html` | Custom not-found page |
| `vercel.json` | Vercel deployment config |
| `_redirects` | Netlify deployment config |
| `.htaccess` | Apache/cPanel hosting config |
| `DEPLOY.md` | This file |
| `_seo-data/` | Reference data (not served publicly) |

## Pages Included (95 total)

```
  /roofing-contractor-st-louis-mo          Home
  /services                                Services
  /about                                   About Us
  /contact                                 Contact
  /locations                               Locations
  /roof-repair-service-st-louis-mo         Roof Repair Service
  /roof-leak-repair-st-louis-mo            Roof Leak Repair
  /metal-roofing-company-st-louis-mo       Metal Roofing Company
  /commercial-roofing-contractor-st-louis-mo Commercial Roofing Contractor
  /industrial-roofing-st-louis-mo          Industrial Roofing
  /residential-roof-replacement-st-louis-mo Residential Roof Replacement
  /new-roof-installation-st-louis-mo       New Roof Installation
  /storm-and-hail-damage-restoration-st-louis-mo Storm & Hail Damage Restoration
  /emergency-roofing-24-7-st-louis-mo      Emergency Roofing (24/7)
  /roof-inspection-st-louis-mo             Roof Inspection
  /free-roof-estimate-st-louis-mo          Free Roof Estimate
  /service-areas/st-louis-county           St. Louis County (county hub)
  /service-areas/st-charles-county         St. Charles County (county hub)
  /service-areas/jefferson-county          Jefferson County (county hub)
  /service-areas/madison-county            Madison County (county hub)
  /service-areas/st-clair-county           St. Clair County (county hub)
  /service-areas/clayton-mo                Clayton
  /roof-replacement-clayton                Roof Replacement in Clayton
  /roof-repair-clayton                     Roof Repair in Clayton
  /storm-damage-clayton                    Storm Damage in Clayton
  /service-areas/ladue-mo                  Ladue
  /roof-replacement-ladue                  Roof Replacement in Ladue
  /roof-repair-ladue                       Roof Repair in Ladue
  /storm-damage-ladue                      Storm Damage in Ladue
  /service-areas/frontenac-mo              Frontenac
  /service-areas/town-and-country-mo       Town and Country
  /service-areas/chesterfield-mo           Chesterfield
  /roof-replacement-chesterfield           Roof Replacement in Chesterfield
  /roof-repair-chesterfield                Roof Repair in Chesterfield
  /storm-damage-chesterfield               Storm Damage in Chesterfield
  /service-areas/creve-coeur-mo            Creve Coeur
  /roof-replacement-creve-coeur            Roof Replacement in Creve Coeur
  /roof-repair-creve-coeur                 Roof Repair in Creve Coeur
  /storm-damage-creve-coeur                Storm Damage in Creve Coeur
  /service-areas/kirkwood-mo               Kirkwood
  /roof-replacement-kirkwood               Roof Replacement in Kirkwood
  /roof-repair-kirkwood                    Roof Repair in Kirkwood
  /storm-damage-kirkwood                   Storm Damage in Kirkwood
  /service-areas/webster-groves-mo         Webster Groves
  /service-areas/ballwin-mo                Ballwin
  /service-areas/wildwood-mo               Wildwood
  /service-areas/st-charles-mo             St. Charles
  /roof-replacement-st-charles             Roof Replacement in St. Charles
  /roof-repair-st-charles                  Roof Repair in St. Charles
  /storm-damage-st-charles                 Storm Damage in St. Charles
  /service-areas/ofallon-mo                O'Fallon
  /roof-replacement-ofallon                Roof Replacement Ofallon in O'Fallon
  /roof-repair-ofallon                     Roof Repair Ofallon in O'Fallon
  /storm-damage-ofallon                    Storm Damage Ofallon in O'Fallon
  /service-areas/st-peters-mo              St. Peters
  /roof-replacement-st-peters              Roof Replacement in St. Peters
  /roof-repair-st-peters                   Roof Repair in St. Peters
  /storm-damage-st-peters                  Storm Damage in St. Peters
  /service-areas/wentzville-mo             Wentzville
  /roof-replacement-wentzville             Roof Replacement in Wentzville
  /roof-repair-wentzville                  Roof Repair in Wentzville
  /storm-damage-wentzville                 Storm Damage in Wentzville
  /service-areas/lake-saint-louis-mo       Lake Saint Louis
  /service-areas/cottleville-mo            Cottleville
  /service-areas/arnold-mo                 Arnold
  /roof-replacement-arnold                 Roof Replacement in Arnold
  /roof-repair-arnold                      Roof Repair in Arnold
  /storm-damage-arnold                     Storm Damage in Arnold
  /service-areas/imperial-mo               Imperial
  /service-areas/festus-mo                 Festus
  /service-areas/edwardsville-il           Edwardsville
  /roof-replacement-edwardsville           Roof Replacement in Edwardsville
  /roof-repair-edwardsville                Roof Repair in Edwardsville
  /storm-damage-edwardsville               Storm Damage in Edwardsville
  /service-areas/glen-carbon-il            Glen Carbon
  /roof-replacement-glen-carbon            Roof Replacement in Glen Carbon
  /roof-repair-glen-carbon                 Roof Repair in Glen Carbon
  /storm-damage-glen-carbon                Storm Damage in Glen Carbon
  /service-areas/collinsville-il           Collinsville
  /roof-replacement-collinsville           Roof Replacement in Collinsville
  /roof-repair-collinsville                Roof Repair in Collinsville
  /storm-damage-collinsville               Storm Damage in Collinsville
  /service-areas/troy-il                   Troy
  /service-areas/maryville-il              Maryville
  /service-areas/ofallon-il                O'Fallon
  /roof-replacement-ofallon-il             Roof Replacement Ofallon in O'Fallon
  /roof-repair-ofallon-il                  Roof Repair Ofallon in O'Fallon
  /storm-damage-ofallon-il                 Storm Damage Ofallon in O'Fallon
  /service-areas/belleville-il             Belleville
  /roof-replacement-belleville             Roof Replacement in Belleville
  /roof-repair-belleville                  Roof Repair in Belleville
  /storm-damage-belleville                 Storm Damage in Belleville
  /service-areas/shiloh-il                 Shiloh
  /service-areas/swansea-il                Swansea
  /service-areas/mascoutah-il              Mascoutah
```

---

## Option 1: Deploy to Vercel (Recommended — Free, Fast, CDN)

Use **Deploy GitHub + Vercel** in the platform. It creates or updates the GitHub repository, creates the Vercel production deployment, waits for it to become ready, and returns the live URL automatically.

For a manual fallback:
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new and import the repo
3. Framework: **Other** (static)
4. Build command: leave empty
5. Output directory: leave as root `./`
6. Click Deploy

**Domain setup:** In your DNS, add a CNAME record pointing `www` to `cname.vercel-dns.com`

---

## Option 2: Deploy to Netlify (Free, also great)

1. Go to https://netlify.com → "Deploy manually"
2. Drag and drop this entire folder
3. Site goes live instantly on a netlify.app subdomain
4. Add custom domain in Site Settings → Domain Management

---

## Option 3: Traditional Hosting (cPanel, Bluehost, SiteGround, etc.)

1. Open File Manager or connect via FTP (FileZilla)
2. Navigate to `public_html` folder
3. Upload ALL files from this ZIP maintaining folder structure
4. The `.htaccess` file handles clean URLs automatically
5. Test: visit `https://www.allweatherroofingsystems.com/drain-cleaning-gary-in` (or any inner page) to confirm routing works

---

## After Deployment

### Required (Day 1)
- [ ] Visit every page, confirm it loads correctly
- [ ] Update `sitemap.xml` base URL from `https://www.allweatherroofingsystems.com` to your live domain (if different)
- [ ] Submit `sitemap.xml` to Google Search Console
- [ ] Add Google Analytics tag to each page (or use Tag Manager)
- [ ] Test contact form (if applicable)
- [ ] Set up Google Search Console property

### GBP & Citations (Week 1)
- [ ] Update GBP website URL to live site
- [ ] Update GBP description with final copy
- [ ] Upload 10+ geotagged project photos to GBP
- [ ] Verify NAP consistency across all citations

### NAP (use EXACTLY everywhere — copy-paste to avoid typos)
```
Name:    All Weather Roofing Systems
Phone:   (314) 834-6556
Address: 701 Market St, St. Louis, MO 63101
Website: https://www.allweatherroofingsystems.com
```

---

## Ongoing SEO (Caleb's Methodology)
- Post weekly to GBP (use the 52-Week Post Generator in the platform)
- Publish 2-4 blog posts per month targeting informational keywords
- Respond to every Google review within 24 hours
- Build citations: Google, Yelp, BBB, Angi, HomeAdvisor, Houzz, Thumbtack
- Track keyword rankings monthly (use the Rank Tracker in the platform)
