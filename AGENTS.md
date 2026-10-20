# RAHNAM — Codex Project Instructions

## Project

RAHNAM is a premium strategy, digital growth, ecommerce and transformation consultancy website.

The website is being built with:
- Astro
- HTML
- CSS
- JavaScript
- GitHub
- AWS Amplify
- Route 53

The current work is local/repository-first.

## Brand Positioning

RAHNAM must feel like a premium consulting and digital strategy firm.

It must NOT feel like:
- a generic digital agency
- a freelancer portfolio
- a template website
- an AI-generated website
- a flashy luxury brand

The design direction is:

Deep Navy Editorial + Quiet Motion

Use:
- deep navy / charcoal
- warm off-white / neutral light sections
- muted greys
- strong typography
- generous but controlled spacing
- thin dividers
- restrained motion
- editorial composition
- clear hierarchy

Avoid:
- pure black everywhere
- excessive gradients
- gold/luxury clichés
- glassmorphism
- excessive rounded cards
- excessive animation
- stock imagery unless explicitly requested
- unnecessary decorative elements

## Critical Design Rule

Preserve the existing RAHNAM visual language.

Do not redesign completed sections simply because another design might look different.

Reuse existing:
- CSS variables
- typography
- spacing system
- container widths
- buttons
- section labels
- dividers
- reveal/motion patterns
- responsive conventions

Do not introduce a new design system unless explicitly instructed.

## LOCKED HOMEPAGE SECTIONS

The following homepage sections have already been reviewed and approved:

1. Hero
2. Positioning / Problem
3. Services

These sections are LOCKED.

Do not redesign, restructure or rewrite them unless:
- there is a functional bug
- there is a responsive/accessibility problem
- there is an obvious implementation error

Minor bug fixes are allowed.

Do not change their visual direction merely for stylistic preference.

## Homepage Remaining Work

Continue from the existing implementation.

Remaining homepage work should focus on:
- Selected Impact / Case Studies
- About
- Insights
- Contact
- final integration
- responsive/mobile QA
- accessibility
- basic SEO
- production build verification

## Existing Pages

The site currently contains:

/
/services
/case-studies
/about
/insights
/contact

Treat the existing page structures and copy as the foundation.

Do not replace the pages with completely new concepts.

Improve them consistently with the established RAHNAM design.

## Content Rules

Use existing approved RAHNAM content wherever possible.

Do not invent:
- clients
- testimonials
- revenue claims
- business metrics
- awards
- partnerships
- case-study results
- credentials
- fabricated business outcomes

If information is missing, flag it rather than inventing it.

## Case Studies

Case studies should feel credible, strategic and consulting-grade.

Do not manufacture proof points.

Where evidence is unavailable, use qualitative language or clearly mark content as requiring confirmation.

## Insights

Review the existing Insights implementation before changing it.

Do not automatically create a complex CMS or article architecture.

Prefer the simplest maintainable solution that fits the current site.

## Contact

The Contact page should remain visually complete even if the backend submission system is not yet implemented.

Do not implement AWS Lambda, SES, API Gateway or other production infrastructure unless explicitly instructed.

Do not modify Route 53, AWS Amplify, CloudFront, Lambda or SES as part of normal frontend work.

## Motion

Use CSS and lightweight JavaScript first.

Prefer:
- CSS transitions
- IntersectionObserver
- subtle hover movement
- restrained scroll reveals

Respect:
prefers-reduced-motion

Do not add GSAP or another animation framework unless there is a clear requirement.

Motion should support the design rather than become the design.

## Responsive Design

Every section must work properly at:
- desktop
- tablet
- mobile

Pay particular attention to:
- navigation
- typography
- spacing
- grids
- buttons
- horizontal overflow
- long headings
- forms
- touch targets

Do not fix mobile by simply hiding important content.

## Accessibility

Maintain:
- semantic HTML
- keyboard accessibility
- visible focus states
- meaningful link text
- appropriate button states
- accessible navigation
- sensible heading hierarchy
- reduced-motion support
- form labels and accessible error/success states

## Code Quality

Prefer simple, maintainable Astro/CSS/JS.

Do not add dependencies unless genuinely necessary.

Reuse components instead of duplicating code.

Do not perform large unrelated refactors while completing the website.

Keep changes focused.

## Validation

Before considering work complete:

1. Run the development site where appropriate.
2. Run:

npm run build

3. Check for build errors.
4. Check browser console errors where possible.
5. Check internal links.
6. Check desktop and mobile layouts.
7. Check accessibility basics.
8. Check that existing approved sections have not been unintentionally changed.

## Working Method

Before making substantial changes:
- inspect the existing implementation
- understand the surrounding components
- identify the smallest appropriate change
- preserve existing patterns

For larger tasks:
- break the work into logical steps
- complete and validate one area before moving to the next
- avoid changing many unrelated files simultaneously

When finished, report:
- files changed
- what was implemented
- issues fixed
- validation/build result
- anything that still requires human decision

## Important

The goal is to FINISH AND POLISH THE EXISTING RAHNAM WEBSITE.

Do not redesign the project from scratch.

Do not make changes merely because you personally prefer another visual direction.

When uncertain about a business/content decision, flag it for human review rather than inventing an answer.
