My practical test for worknoon WordPress Developer role
Worknoon WordPress Assessment

Project Overview

This project is a responsive, SEO-optimized WordPress landing page built as part of the Worknoon WordPress Developer (SEO + Systems Specialist) assessment.

The goal was not just to design a page, but to architect a "scalable, performance-focused WordPress system" that supports structured content, strong SEO foundations, and future extensibility.

Objectives

- Build a responsive landing page using Elementor
- Implement structured, reusable content using ACF
- Apply technical SEO best practices (schema, crawlability, performance)
- Demonstrate system thinking and scalability
- Integrate analytics tracking
- Maintain clean Git workflow and documentation

System Architecture Overview

Frontend (Presentation Layer)

- Elementor used for layout and UI design
- Mobile-first responsive design approach
- Reusable sections for scalability

Content Layer (Structured Data)

- Advanced Custom Fields (ACF) used to manage:
  - Services
  - Testimonials
- Enables non-technical users to update content easily
- Avoids hardcoding content inside Elementor

SEO Layer:
Google Search Console is configured for indexing monitoring, sitemap submission, and crawl diagnostics

- Schema markup (JSON-LD)
- Proper heading hierarchy (H1–H3)
- Meta tags and indexing control via SEO plugin
- Sitemap integration

Performance Layer

- LiteSpeed Cache for optimization
- Image optimization (WebP + lazy loading)
- CSS/JS minification and defer loading

Analytics Layer

- Plausible/Google Analytics (GA4) integrated
- Tracks user behavior and engagement

Tools & Technologies Used

- WordPress
- Elementor (Page Builder)
- Advanced Custom Fields (ACF)
- LiteSpeed Cache
- SiteSEO (or RankMath)
- Plausible
- Google Analytics (GA4)
- Git & GitHub

Features Implemented

1. Hero Section

- Clear value proposition
- Call-to-action (CTA)
- Optimized for Largest Contentful Paint (LCP)

2. Services Section

- Dynamically managed using ACF
- Structured for scalability

3. Testimonials Section

- Custom fields for easy updates
- Designed for trust and conversion

4. Contact Form

- Implemented using a lightweight plugin
- Basic validation and submission handling

Performance Optimization
The site was optimized for speed and Core Web Vitals:

- Lazy loading for images
- Preloading critical assets (hero section)
- Minified CSS and JavaScript
- Reduced render-blocking resources
- Optimized image formats (WebP)

SEO Implementation
On-Page SEO

- Proper heading structure (single H1, logical hierarchy)
- Keyword-friendly content structure
- Optimized meta titles and descriptions

Technical SEO

- XML sitemap configured
- Robots.txt reviewed
- Canonical URLs applied
- Mobile responsiveness ensured

Schema Markup

- Organization schema
- Person schema (Founder)
- Website schema
- sameAs linking to social profiles

(See `schema.json` file for implementation)

Analytics Integration

- Google Analytics (GA4) added via script
- Tracks:
  - Page views
  - User engagement
  - Traffic sources

Setup Instructions

1. Clone the repository:

   git clone [https://github.com/rextechits/worknoon-wordpress-assessment]

2. Move files into your WordPress environment:
   - Place theme/plugin files in `/wp-content/`and db
   - Also use the live url to view the practical test [https://henry.breatha.org]

3. Import database (if applicable) - database attached

4. Install required plugins:
   - Elementor/Elementor Pro
   - ACF
   - LiteSpeed Cache
   - SiteSEO

5. Configure:
   - Permalinks
   - SEO plugin
   - Analytics tracking ID

6. Launch site locally or on staging

Key Decisions & Rationale

- Why ACF instead of static Elementor content?

To ensure scalability and structured content management. This allows easy updates without modifying layout design.

- Why LiteSpeed Cache?

It provides advanced optimization (caching, minification, image optimization) with minimal configuration.

- Why structured schema?

To improve search engine understanding and support Knowledge Graph inclusion.

Challenges & Solutions

- Challenge 1: Mobile responsiveness issues
- Solution: Used custom breakpoints and optimized spacing per device

Challenge 2: Page speed optimization

- Solution: Deferred JavaScript and optimized images

Challenge 3: Avoiding content duplication in Elementor

- Solution: Leveraged ACF for dynamic content

Tradeoffs Considered

- Elementor flexibility vs performance → mitigated using caching and optimization
- Plugin usage vs custom code → prioritized speed and maintainability
- Design richness vs loading speed → optimized assets to balance both

Future Improvements

- Convert sections into reusable Gutenberg blocks
- Implement server-side rendering improvements
- Add CDN integration
- Enhance schema with more entity relationships
- Implement advanced event tracking

Demo Video:
Complete Loom video URLs -

[https://www.loom.com/share/70a14e614e7143d4acb36e72340cc53a] - First half

[https://www.loom.com/share/dcfc76e49263458ca172642668f5a300] - Concluding Video

Submission

GitHub Repository:
GitHub Repo Link - [https://github.com/rextechits/worknoon-wordpress-assessment]

Live Practical Test URL [https://henry.breatha.org]

Author:
Henry Nwobodo (Co-Founder DragsDev)
WordPress Developer | Frontend | SEO Systems
