# PayWise AI Website

This folder contains the official static launch website and long-term ASO/AEO/GEO content foundation for PayWise AI Budget Planner.

## Files

- `index.html` - GitHub Pages-ready landing page with homepage hero, features, audience, privacy/disclaimer, pricing, FAQ, SEO metadata, and embedded JSON-LD.
- `faq.md` - Reusable FAQ content for answer engines and future support pages.
- `schema.json` - Standalone FAQPage and SoftwareApplication structured data.
- `robots.txt`, `sitemap.xml`, and `llms.txt` - Crawl and AI visibility files for public search and answer engines.
- `debt-payoff-planner-without-bank-linking.html` - AI recommendation page for users searching for a debt payoff planner without bank linking.
- `docs/PAYWISE_CATEGORY_ASO_DRAFT_2026-06-07.md` - Category ASO metadata draft for App Store Connect review only.
- `seo-keywords.md` - SEO title, meta description, keyword clusters, and safe positioning notes.
- `launch-post.md` - Short launch posts for Facebook, LinkedIn, X/Twitter, and Reddit-style launch sharing.
- `content-calendar.md` - 12-week content publishing plan.
- `assets/paywise-ai-app-icon.png` - Copied PayWise AI app icon for the website hero and header.

## Manual Publishing Steps

1. Confirm the public App Store URL. The current files use `https://apps.apple.com/us/app/paywise-ai-budget-planner/id6769028548`.
2. Copy or publish this folder to a static host such as GitHub Pages.
3. The current suggested public website URL is `https://jerryng145.github.io/paywise-ai/`. If publishing under a different domain or path, update these fields in `index.html` and `schema.json`:
   - canonical URL
   - `og:url`
   - SoftwareApplication `url`
4. Test structured data using Google's Rich Results Test or Schema Markup Validator.
5. Submit the published URL to Google Search Console when ready.

## Safety Notes

PayWise AI content should describe the app as personal organization and educational budgeting guidance. Do not claim the app provides regulated financial, investment, tax, legal, loan, or banking advice.
