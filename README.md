# Movavi Video Hub — Global

Independent affiliate SEO site for Movavi video editing software. 4,000+ pages in 9 languages.

**Live site:** https://brightlane.github.io/movavi.com/

## Setup

1. Upload `build.py` to repo root
2. Create `.github/workflows/deploy.yml` from `movavi_global_deploy.yml`
3. Go to **Settings → Pages → Source → GitHub Actions**
4. Go to **Settings → Secrets → Actions**
   - `ANTHROPIC_API_KEY` → your key (enables daily AI blog)
5. Push to `main` to trigger first build

## What It Builds

| Category | Pages |
|---|---|
| English core/how-to/task/platform | ~540 |
| English US geo (50 states × 12) | 600 |
| English US cities (200 cities × 12) | 2,400 |
| Spanish | ~102 |
| Portuguese | ~87 |
| French | ~90 |
| German | ~90 |
| Polish | ~78 |
| Dutch | ~72 |
| Italian | ~78 |
| Japanese | ~52 |
| Blog + Essential | ~44 |
| **Total** | **~4,200+** |

## Languages

| Language | URL Path |
|---|---|
| English | /guides/ |
| Spanish | /es/guias/ |
| Portuguese | /pt/guias/ |
| French | /fr/guides/ |
| German | /de/anleitungen/ |
| Polish | /pl/poradniki/ |
| Dutch | /nl/gidsen/ |
| Italian | /it/guide/ |
| Japanese | /ja/guides/ |

## Key Features

- **Hreflang tags** on every page for international SEO
- **Google + Bing verification** on every page
- **Daily AI blog** via Claude API (claude-sonnet-4-6)
- **Task-specific bodies** for 25 editing tasks × 8 aspects
- **Platform specs** for YouTube, Instagram, TikTok, Facebook, etc.
- **Rich schemas**: Article, FAQPage, HowTo, SoftwareApplication, BreadcrumbList
- **400+ US cities** with geo-targeted content

## Affiliate

All CTAs: `https://www.linkconnector.com/ta.php?lc=007949109434006513&atid=MovaviWebs`

## Verification Tags (on every page)

```html
<meta name="google-site-verification" content="eWVDN3vbam9nnaZQu7wAQKyfmJJdM7zjI80l4DGeUrQ">
<meta name="msvalidate.01" content="574044E39556B8B8DAAF1D1F233C87B0">
```
