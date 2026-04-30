SEO Diagnosis & Indexing Troubleshooting

Scenario:
A newly launched Worknoon website is not indexing on Google even after submitting the sitemap in Google Search Console.

Objective:
To systematically diagnose and resolve indexing issues by identifying technical, structural, and performance-related blockers affecting search engine crawlability and indexation.

Step-by-Step Diagnosis Process:

1. Verify Indexing Status
   - Perform a site search:
     site:example.com
   - Use URL Inspection Tool in Google Search Console (GSC)
   - Check:
   - “URL is not on Google”
   - Crawl status
   - Last crawl date

2. Robots.txt Audit

Check:
https://henry.breatha.org/robots.txt (not set)

Issues to look for: - Disallowed important pages:
Disallow: / - Blocking critical resources (CSS, JS)

Fix: - Ensure essential pages are crawlable - Allow search engines access to required assets

3. No-Index Tag Check
Inspect page source or use SEO plugin:
html
<meta name="robots" content="noindex" />

Common Causes: - SEO plugin misconfiguration - “Discourage search engines” enabled in WordPress

Fix: - Remove `noindex` - Disable:
Settings → Reading → “Discourage search engines from indexing this site”

4. XML Sitemap Issues
   Validate sitemap: https://henry.breatha.org/sitemap.xml (not set)

Check for: - Broken URLs - Missing pages - Incorrect canonical links

Fix: - Regenerate sitemap via SEO plugin - Resubmit in Google Search Console

5. Crawlability & Internal Linking
   Problems: - Orphan pages (no internal links) - Poor navigation structure
   Fix: - Link homepage → services → contact - Ensure logical site hierarchy

6. Canonical Tag Issues
Check:
html
<link rel="canonical" href="..." />

Issues: - Canonical pointing to wrong URL - Duplicate content confusion

Fix: - Set correct canonical to preferred page version

7. Page Speed & Performance Blockers
   Impact: Slow pages may delay or reduce crawl frequency.

Tools: - Google PageSpeed Insights - Lighthouse
Fix: - Optimize images (WebP) - Minify CSS/JS - Enable caching (LiteSpeed)

8. Server & Response Issues
   Check: - HTTP status codes (200, 404, 500) - Server downtime

Fix: - Ensure pages return **200 OK** - Resolve server errors promptly

9.  Google Search Console Debugging
    Use: - Coverage Report - URL Inspection Tool - Page Experience Report

Actions: - Request indexing manually - Identify crawl errors - Monitor improvements

10. Domain & Authority Signals
    Problem: New domains may take time to gain trust.

Fix: - Build backlinks - Share on social platforms - Submit to directories

Root Cause Summary
Common reasons a new site may not index: - Robots.txt blocking crawlers - Noindex meta tags - Poor internal linking - Weak domain authority - Technical errors (server, canonical, sitemap)

Recommended Action Plan

1. Remove all crawl/indexing restrictions
2. Validate sitemap and resubmit
3. Improve internal linking structure
4. Optimize page performance
5. Use GSC to request indexing
6. Build initial authority signals

Conclusion

Indexing issues are typically caused by a combination of technical misconfigurations and lack of authority signals. A structured debugging approach ensures that all potential blockers are identified and resolved efficiently, improving crawlability, indexation, and overall search visibility.
