# Direct Task: Resume-Style Brutalist Site Refresh

## 1. Recommended Site Structure (Brutalist, Resume-ish)
- **Hero / Identity Block**: Name, title, 1-2 sentence positioning statement, city, GitHub + LinkedIn links, primary CTA.
- **Core Expertise**: Capability-first sections (Full-Stack Delivery, Frontend Systems, Backend/API Design, Cloud & DevOps, AI Engineering).
- **Professional Experience Snapshot**: Recent roles and impact bullets, emphasizing outcomes over long narrative.
- **Domain Experience**: Healthcare, medical billing, cost containment, and workers comp context with concise business-impact notes.
- **Selected Work / Proof**: 3-5 compact case studies (problem, stack, result, link).
- **Technical Principles**: Short opinionated statements on maintainability, delivery, and pragmatic architecture.
- **Contact**: Direct links only (email optional), no form.

## 2. Content to Remove from Current Site
- Outdated Bootstrap template patterns (sidebar toggle nav, modal-heavy portfolio flow, hero background image treatment).
- Stale copy and old employer/project framing (e.g., dated "currently" statements and 2017-era positioning).
- Legacy tech emphasis that no longer matches target narrative (AngularJS/Xamarin-forward icon grid).
- Low-value or high-maintenance elements (Formspree contact form, Twitter link if not actively professional).
- Long project modals that read as archive material rather than current senior-level positioning.

## 3. Technologies/Experience to Emphasize for Matt Kraatz
- .NET and modern C# backend engineering
- React + TypeScript frontend architecture
- Full-stack product and internal-tool delivery
- Cloud architecture (especially Azure-oriented patterns)
- DevOps and CI/CD implementation
- SQL Server and Postgres data design/performance
- AI engineering and practical ML-enabled workflows
- Healthcare domain depth: medical billing, cost containment, workers comp

## 4. Five-Step Implementation Plan
1. Replace the current single-page template with a clean semantic layout and brutalist visual system (typography, high contrast, sharp grid).
2. Rewrite all core copy to present current positioning, capability-based expertise, and domain credibility.
3. Rebuild "Selected Work" into concise proof cards (no modals), focused on impact, stack, and links.
4. Remove deprecated sections/components (icon grid, legacy contact form, stale social links, dated project narrative).
5. Finalize responsive polish, accessibility pass, and deploy-ready content validation for GitHub Pages.

## Implementation Note (First Reviewable Pass)
- Replaced the legacy Bootstrap-template homepage with a custom single-page layout centered on Matt Kraatz's current positioning: full-stack/product-minded engineering, .NET/React/TypeScript, cloud + DevOps/CI/CD, SQL Server/Postgres, and AI workflows.
- Removed stale UI/content patterns: sidebar toggle nav, technology icon grid, modal-heavy portfolio flow, and contact form.
- Rebuilt the page as a resume-ish professional narrative with sections for current focus, domain depth (healthcare/medical billing/cost containment/workers comp), selected work patterns, and concise working principles.
- Heavily rewrote `css/stylish-portfolio.css` to deliver a brutalist-inspired visual system (bold borders, sharp shadows, high-contrast typography, responsive grid) without adding any framework.
- Cleared old template JS behaviors in `js/stylish-portfolio.js` to keep the refreshed static site lightweight for GitHub Pages.
