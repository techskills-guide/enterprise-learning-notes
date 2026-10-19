# Enterprise Learning Notes

A small static educational website with two focused articles: one on evaluating ServiceNow training in Noida and one on Workday Finance training.

## Current content

- Homepage with two featured articles and relevant contextual course links.
- ServiceNow guide: `/blog/servicenow/servicenow-training-in-noida.html`
- Workday Finance guide: `/blog/workday/workday-finance-training.html`
- ServiceNow category: `/servicenow/`
- Workday category: `/workday/`
- About page: `/about.html`
- Editorial policy: `/editorial-policy.html`
- Custom 404 page: `/404.html`
- Responsive CSS: `/style.css`
- Crawl policy: `/robots.txt`
- Netlify configuration: `/netlify.toml`

## Deploy on Netlify

1. Import this repository into Netlify.
2. Set production branch to `main`.
3. Leave the build command empty.
4. Set publish directory to `.`.
5. Deploy and note the exact assigned `https://<site-name>.netlify.app` address.

## SEO finalization after deployment

Do not guess the Netlify hostname. Once the actual production URL is known:
1. Add self-referencing canonical URLs to each indexable HTML page.
2. Create `sitemap.xml` using exact absolute URLs for the live canonical pages.
3. Add the sitemap URL to `robots.txt`.
4. Check internal links, page responses, canonical targets, mobile rendering, and indexability.
5. Verify the site in Google Search Console and submit the sitemap.
6. Inspect representative URLs and monitor indexing reports. Sitemap submission does not guarantee indexing.

## Editorial and link policy

Publish only useful, original material that answers a genuine learning question. External course links should be relevant and clearly contextual; do not publish thin or repetitive pages purely to place links. Course details and availability can change, so readers should verify them directly with the provider.

Product-specific behavior varies by release, license, and implementation. Confirm technical instructions against current official documentation. This independent site is not affiliated with ServiceNow, Workday, or TechPratham.
