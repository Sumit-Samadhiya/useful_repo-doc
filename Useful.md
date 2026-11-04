# Essential Production Checklist & Curated Developer Resources

A structured, clean collection of production readiness requirements, tools, workflows, and developer resources.

---

## 🚀 Web & App Launch Checklist

Ensure these foundational security, compliance, performance, and SEO items are verified before pushing to production:

### 🔒 Security & Compliance
- [ ] **Enforce HTTPS**: Redirect all HTTP traffic and configure proper SSL/TLS certificates.
- [ ] **Remove Frontend Secrets**: Audit client-side builds to ensure no private API keys or environment variables are exposed.
- [ ] **Privacy Policy & Terms**: Clear, accessible legal documentation tailored to your product.
- [ ] **Cookie Consent Banner**: Compliant user consent for tracking and analytics cookies (GDPR/CCPA).
- [ ] **Form Validation & Spam Protection**: Client/server input sanitation alongside CAPTCHA or Honeypot mechanisms.

### 🔍 SEO & Social Discovery
- [ ] **Meta Titles & Descriptions**: Unique, concise tags customized for every primary route.
- [ ] **Social Preview (OpenGraph / Twitter Cards)**: Dedicated `og:image` and metadata optimized for cross-platform sharing.
- [ ] **Favicon Package**: High-resolution favicons covering multiple resolutions (`.ico`, `.png`, and SVG vectors).
- [ ] **Sitemap & Robots.txt**: Configured `sitemap.xml` dynamically generated alongside a clean `robots.txt` policy.
- [ ] **Image Alt Text**: Semantic `alt` tags on all informational images for indexing and accessibility.

### ⚡ Performance & Core Web Vitals
- [ ] **Image Compression & Formats**: Modern formats (AVIF/WebP) with responsive `srcset` and lazy loading.
- [ ] **Page Load Speed Check**: Benchmark Lighthouse scores and optimize LCP, FID/INP, and CLS.
- [ ] **Color Contrast Fixes**: WCAG AA/AAA-compliant foreground-to-background contrast ratios.
- [ ] **Mobile Responsiveness**: Thorough cross-device testing across portrait, landscape, and multiple viewport breakpoints.

### 🎯 UX & Conversion
- [ ] **Single Clear CTA**: Focused, unambiguous call-to-action on landing and conversion screens.
- [ ] **Custom 404 Page**: User-friendly fallback with links redirecting back to home/core features.
- [ ] **Broken Link Audit**: Scan and eliminate internal and external 404/broken links.
- [ ] **Analytics Setup**: Production event tracking, user flows, and error monitoring (e.g., PostHog, GA4, Sentry).

---

## 🛠️ Curated Developer Resources & Repositories

### 🤖 AI, Agents & Video
* **[Hermes Agent](https://github.com/NousResearch/hermes-agent)** — Framework and implementation for autonomous Hermes-powered AI agents.
* **[MoCha (Video Character Replacement)](https://github.com/Orange-3DV-Team/MoCha)** — End-to-end framework for video character replacement.
* **[Vibe-Coding Guide](https://docs.google.com/document/d/12u0wXE0u0o5FNGj2sGy8OvOPHEtPSwD8ltwN0UcvqH4/edit?tab=t.0#heading=h.vjg4nn1gdwsm)** — Workflow documentation and notes for AI-assisted development.
* **[Animated Mascot Asset](https://drive.google.com/file/d/1baIvyMNRjLSvkUGPg4Wcsss2oBLxC5cU/view)** — Project files and walkthrough for creating an animated mascot.

### 🌐 Frontend & 3D Web
* **[Anatomy 3D Explainer](https://github.com/wheresryan22/anatomy)** — Interactive 3D visualization and explanatory components for modern web apps.

### 🔌 APIs & Infrastructure
* **[Public APIs Directory](https://github.com/public-apis/public-apis)** — Collective list of free, public APIs for web development across categories.
* **[Free Domain Service](https://accounts.northwestregisteredagent.com/#/web-services/domains/22c1e3fb-3447-4264-88a9-ddcddaca2679)** — Free domain registration service for 1 year.

### 🔍 Security & Research
* **[Reverse Engineering Skills (REA)](https://github.com/morluto/rea)** — Practical guides, roadmaps, and skills for reverse engineering and binary analysis.

### 🎬 Media & Downloads
* **MKVBase** — `mkvbase.site`
