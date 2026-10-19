# Enterprise Learning Notes

A static educational website with learning notes for ServiceNow and Workday.

## Current content

- Homepage with topic paths, featured articles, learning approach, and contextual further-learning resources.
- ServiceNow category: `/servicenow/`
- Workday category: `/workday/`
- Four initial technical articles under `/blog/servicenow/` and `/blog/workday/`
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
5. Deploy and copy the exact assigned `https://<site-name>.netlify.app` address.

## SEO finalization after deployment

Do not guess the Netlify hostname. Once the actual production URL is known:
1. Add self-referencing canonical URLs to every indexable HTML page.
2. Create `sitemap.xml` with the exact absolute URLs for the live, canonical pages.
3. Add the sitemap location to `robots.txt`.
4. Verify page responses, internal links, canonical targets, mobile rendering, and indexability.
5. Verify the site in Google Search Console and submit the sitemap.
6. Inspect representative URLs and monitor the Pages report. Sitemap submission and indexing requests do not guarantee indexing.

## Editorial and link policy

Pages should answer a real learning question, provide original explanatory value, and link to relevant further reading only when useful. Avoid publishing repetitive or thin articles purely to place links. External training links are contextual resources; readers should verify current course information directly with the provider.

Product-specific behavior may vary by release, license, security role, and tenant design. Confirm technical instructions against current official documentation. This independent site is not affiliated with ServiceNow or Workday.
