# Matt Kraatz — Website Specification

## Purpose and audience

A concise professional site for prospective collaborators, hiring teams, and technical peers to understand Matt's work, judgment, and business impact. Position Matt as a product engineer who connects business needs, architecture, full-stack implementation, and AI-assisted delivery.

The site should feel confident, direct, technically credible, and human. Favor concrete work and outcomes over buzzwords, exaggerated branding, or a large gallery of archived side projects.

## Content direction

The current homepage is the baseline for published copy. Its narrative has two complementary themes: building useful products and building the engineering environment that helps teams deliver them reliably.

Maintain these sections:

1. **Identity:** Matt Kraatz, Product Engineer, Nashville; a concise positioning statement, the staff-engineer tarot portrait, and GitHub and LinkedIn links.
2. **Capabilities:** product discovery, tradeoffs, planning, implementation, testing, rollout, and training; paired with architecture, engineering standards, agent workflows, automation, and CI/CD.
3. **Selected work:** a small set of concrete case studies explaining the problem, Matt's contribution, and the outcome. Current examples cover agent-driven legacy modernization, claim repricing, distributed-system simplification, and AI-assisted medical bill entry. Link to public work where an appropriate public link exists.
4. **Delivery practice:** specification, technical planning, review, implementation, verification, and deployment, supported by tests and durable documentation.
5. **Industry experience:** healthcare, medical billing, cost containment, and workers' compensation, with the business and sales-operations background that informs product decisions.
6. **Engineering principles:** own outcomes, address root causes, reduce the cost of future changes, and justify complexity.
7. **Contact:** direct GitHub and LinkedIn links; email may be added if requested.

Technical detail should support the work described. Relevant experience includes .NET/C#, React/TypeScript, cloud and DevOps, SQL/data systems, and practical AI workflows. Avoid replacing the narrative with technology logos or an exhaustive skills inventory.

Employment details and quantified outcomes must remain grounded in information supplied by Matt. Preserve the distinction between measured results and estimates, and between potential and realized business impact. Do not add confidential client or implementation details.

## Visual direction

Use a restrained brutalist-inspired style: strong typography, dark borders, sharp offset shadows, a structured grid, generous spacing, and a limited palette. The current design uses warm off-white surfaces, dark text, and an orange accent, with Space Grotesk for primary text and IBM Plex Mono for labels and supporting details.

Keep the tarot portrait as the intentional personal element in the hero. The desktop hero pairs the portrait and identity text; narrow layouts stack them. Selected-work cards and other grids collapse to one column as space becomes limited.

Readability and accessibility take priority over visual effects. Maintain semantic landmarks, logical headings, descriptive alt text, visible keyboard focus, readable contrast, and layouts without horizontal overflow.

## Technical and maintenance requirements

- Serve a single static page with HTML, CSS, and only the images it uses.
- Keep GitHub Pages deployment simple, with the site served from the repository root and `CNAME` set to `mattkraatz.com`.
- Require no build step or dependency installation for local preview or publishing the static files.
- Add JavaScript only for a specific user need.
- Maintain useful page metadata and lightweight assets. Provide font fallbacks when Google Fonts is unavailable.
- Keep project documentation focused on this specification and contributor guidance in `AGENTS.md`.

## Outside the current scope

A contact form, Bootstrap sidebar navigation, project modals, legacy technology icon grids, and an archive-style portfolio are not part of the intended experience. A framework, CMS, blog, or backend should be introduced only for a new requirement.

The earlier refresh notes mentioned a custom-domain HTTPS problem. That historical observation is not evidence of a current issue; check live configuration if deployment or domain work is requested.

## Acceptance criteria

- A visitor can quickly understand Matt's positioning and find professional links.
- Case studies substantiate the positioning with clear contributions and appropriately qualified outcomes.
- The site remains readable and usable on desktop and mobile, including keyboard access to links.
- All local assets resolve and the page can be previewed with a basic static server.
- Repository guidance describes the maintained site rather than the retired template or past tasks.
