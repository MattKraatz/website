# Website Refresh Plan

## Goals

- Create a personal site that feels professional but not corporate.
- Emphasize skillset, technical judgment, and domain expertise more than a large portfolio.
- Use a brutalist-inspired visual style without sacrificing readability or credibility.
- Keep deployment simple on GitHub Pages.
- Fix the broken custom-domain HTTPS setup.

## What the current site gets wrong

- It is visually dated and tied to an old Bootstrap template.
- It leans on a portfolio model that no longer fits the owner well.
- It includes stale content, old job context, and projects that feel more like archive material than current positioning.
- It includes a contact form that adds maintenance and spam surface area without being necessary.
- It does not establish a strong present-day technical point of view.

## Recommended direction

### Positioning
A concise, resume-ish personal site for a senior-ish software engineer: confident, direct, technically credible, lightly opinionated, and human.

### Tone
- Clear and smart
- Friendly but not chatty
- Slightly opinionated
- Avoid buzzword soup and exaggerated self-branding

### Visual direction
Brutalist-inspired, not chaotic:
- Strong typography
- High contrast
- Sharp borders, boxes, and grid structure
- Minimal palette
- Sparse but deliberate accent color
- No glossy gradients or template-y hero imagery
- Generous whitespace so it still feels professional

## Information architecture

### 1. Hero
Purpose: establish identity immediately.

Suggested content:
- Name
- Short title line
- 1–2 sentence positioning statement
- Primary links: GitHub, LinkedIn
- Optional CTA: "See what I build" / "What I’m good at"

Example direction:
- Matt Kraatz
- Software engineer building practical systems, internal tools, and product-minded web software.
- I work across backend, frontend, and the messy middle where software has to be useful, maintainable, and shipped.

### 2. Expertise / What I do
Purpose: communicate capability more clearly than a skills icon grid.

Organize by capability, not brand logos alone:
- Application development
- Frontend systems
- Backend/API design
- Developer experience / maintainability
- Product-minded delivery

Keep a smaller "Tech I work with" list underneath.

### 3. Professional profile
Purpose: a compact narrative instead of a traditional resume dump.

Possible framing:
- Software developer based in Nashville
- Experience building business software, internal tools, and user-facing products
- Stronger emphasis on solving practical problems, shipping maintainable systems, and working effectively across the stack

### 4. Selected work / proof points
Because the public portfolio is limited, avoid pretending otherwise.
Use 3–5 compact proof points:
- A current or most representative project
- One or two older/public projects with clear summaries
- A note that more work is visible through GitHub

For each item:
- Name
- One-line summary
- Stack or technical angle
- Link(s)

### 5. Technical perspective / principles
This is the differentiator.
A short section such as:
- I like software that is understandable before it is clever.
- I care about maintainability, pragmatic architecture, and reducing friction for users and developers.
- I’m most interested in systems that solve real business problems.

This makes the site feel like expertise, not just a link hub.

### 6. Contact / links
Keep this simple:
- GitHub
- LinkedIn
- Optional email link

Recommendation: remove the form.

## What to keep from the current site

- Basic identity: Matt Kraatz, Nashville, software developer
- GitHub and LinkedIn links
- Potentially one or two older projects as proof points

## What to remove

- Old Bootstrap navigation/sidebar pattern
- Technology icon circles
- Modal-heavy portfolio gallery
- Outdated employer/project wording
- Twitter link unless it is still actively useful professionally
- Contact form
- Background hero image and template-driven styling

## Recommended tech approach

Use a modern static site with no framework requirement unless later complexity justifies it.

Why:
- Fastest path to a strong result
- Easiest GitHub Pages deployment
- Easiest future maintenance
- Best for straightforward PR review
- No need to introduce framework complexity for a small personal site

If desired, we can still structure it cleanly with semantic HTML, a single stylesheet, and optional tiny JS only for niceties.

## Proposed implementation plan

1. Fix GitHub Pages custom domain / HTTPS issue
2. Replace old template with a clean single-page layout
3. Write fresh copy oriented around expertise and working style
4. Add selected proof points and external links
5. Refine typography and brutalist visual system
6. Validate deployment on GitHub Pages
7. Open PR for review

## DNS / HTTPS note

Current checks suggest the site is configured in GitHub Pages, but the custom-domain certificate is not valid for mattkraatz.com yet. That usually points to domain/DNS alignment problems or Pages needing the domain configuration refreshed and revalidated before HTTPS can be enforced.

## Draft homepage copy example

### Hero
Matt Kraatz

Software engineer building practical, maintainable web software.

I work across frontend, backend, and product-shaped problem solving — with a bias toward clarity, usefulness, and systems that hold up over time.

[GitHub] [LinkedIn]

### Expertise
What I’m good at

- Building full-stack applications that solve actual business problems
- Designing APIs and backend systems that stay understandable
- Shipping frontend experiences that are fast, clear, and maintainable
- Working across legacy code, greenfield builds, and the in-between
- Turning vague requirements into software that people can use

### Profile
I’m a software developer in Nashville with experience building internal tools, business software, and side projects on the web. I care less about chasing novelty for its own sake and more about making useful things that are cleanly built and easy to evolve.

### Selected work
Use 3–4 concise cards here.

### Principles
- Clarity beats cleverness.
- Good software should help both users and future developers.
- Shipping matters, but so does leaving the codebase in better shape.
