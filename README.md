# Enterprise Learning Notes

Independent technical learning guides for ServiceNow and Workday.

## Project structure

- `index.html`: homepage
- `servicenow/index.html`: ServiceNow category
- `workday/index.html`: Workday category
- `blog/servicenow/`: ServiceNow articles
- `blog/workday/`: Workday articles
- `style.css`: responsive styles
- `robots.txt`: allows crawling of public pages
- `netlify.toml`: static publishing configuration
- `sitemap.xml`: add after Netlify assigns the final URL

## Deploy on Netlify

1. Import this repository into Netlify.
2. Set the production branch to `main`.
3. Leave the build command empty.
4. Set the publish directory to `.`.
5. Deploy and note the exact assigned `https://<site-name>.netlify.app` URL.

## Required post-deployment SEO step

Do not guess the Netlify subdomain. Once the real site URL is assigned, add absolute canonical URLs to every indexable HTML page, create `sitemap.xml` with those exact live URLs, and add the sitemap URL to `robots.txt`. Test every URL and submit the sitemap in Google Search Console.

## Editorial standard

Keep pages original, accurate, useful, and maintained. Verify release-specific product instructions against current official vendor documentation. This independent site is not affiliated with ServiceNow or Workday.
