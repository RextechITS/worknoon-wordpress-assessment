Short Answers – WordPress, SEO & Systems

1. Difference between Google Knowledge Graph and Google Knowledge Panel
   The **Google Knowledge Graph** is a structured database that stores information about entities (people, organizations, places) and their relationships.

The **Google Knowledge Panel** is the visual representation of that data shown in search results.

In simple terms:

- Knowledge Graph = data layer
- Knowledge Panel = display layer

2. How Google Determines Entity Identity
   Google determines entity identity using a combination of:

- Structured data (schema markup)
- Consistent brand information across platforms
- Authoritative mentions and backlinks
- Verified social media profiles
- External databases like Wikidata
  Consistency and credibility across these signals help Google confidently identify and validate an entity.

3. When to Create Custom Post Types Instead of Pages
   Custom Post Types (CPTs) should be used when content:

- Is repeatable and structured (e.g., services, testimonials, case studies)
- Requires its own archive page
- Needs custom taxonomies or categorization
- Will scale over time
  Pages are best for static content like Home, About, and Contact.

4. Recommended Plugins for Speed Optimization and Why
   LiteSpeed Cache

- Server-level caching
- CSS/JS minification and optimization
- Image optimization and lazy loading
- Excellent performance with minimal configuration

WP Rocket (Alternative)

- User-friendly interface
- Strong caching and performance features
- Works well across most hosting environments

Additional Tools

- Image optimization plugins (for WebP conversion)
- CDN integration (for global performance)

5. Robots.txt & No-Index Audit
   Robots.txt

- Ensure critical pages are not blocked
- Avoid:
  Disallow: /

No-Index Check

- Inspect meta tags:
  <meta name="robots" content="noindex">

- Ensure indexing is enabled in WordPress settings
  Misconfiguration in either can completely prevent indexing.

6. Sitemap Structure Issues
   Common sitemap problems include:

- Missing important pages
- Including non-indexable pages
- Broken or outdated URLs
- Incorrect canonical references

A clean sitemap should:

- Include only indexable pages
- Be automatically updated
- Be submitted to Google Search Console

7. Canonical Checks
   Canonical tags help prevent duplicate content issues.
   Key checks:

- Each page should have a self-referencing canonical
- Avoid pointing canonicals to unrelated pages
- Ensure consistency between HTTP/HTTPS and www/non-www
  Incorrect canonical setup can confuse search engines and affect rankings.

8. Crawlability Tests
   To ensure a site is crawlable:

- Check robots.txt for restrictions
- Use Google Search Console URL Inspection
- Verify internal linking structure
- Ensure CSS/JS are not blocked
  Poor crawlability leads to incomplete indexing.

9. Search Console Debugging Steps

- Use URL Inspection Tool to check indexing status
- Review Coverage Report for errors
- Identify excluded pages and reasons
- Request indexing after fixes
- Monitor performance and crawl stats

10. Page Speed Indexing Blockers
    Slow websites can negatively impact crawling and indexing.

Common issues:

- Large unoptimized images
- Render-blocking CSS/JS
- Excessive plugins
- Poor hosting performance

Solutions:

- Use caching (LiteSpeed)
- Optimize assets
- Lazy load non-critical resources
- Improve server response time

Conclusion

Strong SEO performance depends on a combination of technical accuracy, structured data, performance optimization, and proper system architecture. Addressing these areas ensures better crawlability, indexation, and long-term scalability.
