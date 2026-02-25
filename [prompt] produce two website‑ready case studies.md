<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Hi, I'm Roma, a product designer. I want to update my personal website and add case studies to it so that the site can serve as a portfolio. Our initial goal is to add to the existing case study \#1 [Board Games Companion App (600K Installs)] and create a new case study \#2 [B2B ecosystem design system]. After that, we will start making stylistic changes.

For now, create the following prompt for the LLM agent to generate case \#1 and case \#2:

Important
– for case \#1, we must rely on content from my current website (https://raw.githubusercontent.com/n-apps/md-notes/refs/heads/main/[Roma% 20portfolio%5D%20Content%20of%20romamakescom.md) and social media posts (https://github.com/n-apps/md-notes/raw/refs/heads/main/[Social media posts] Score Counter- Count Anyth.md)
– recommendations from Fedor Shkliarau's book (https://raw.githubusercontent.com/n-apps/md-notes/refs/heads/main/[Recommendations] Case Study Recommendations for Product Designers.md)
– take into account references from similar sites (https://github.com/n-apps/md-notes/raw/refs/heads/main/[Case Example] Building a Scalable, Reusable Design System Template.md, [https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BCase%20Example%5D%20Design%20System.md](https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BCase%20Example%5D%20Design%20System.md), https://github.com/n-apps/md-notes/raw/refs/heads/main/[Case Example] Rember.md)
– Case \#2 [B2B ecosystem design system] involves creating a design system from scratch for Yesim's group of B2B products. The challenge was to ensure scalability and flexibility, as the components of the design system will be used in at least three products. The design system also had to provide the ability to customize the appearance for each product (an approach similar to working with sub-brands).

- for images use placeholders e.g. [image with the final result.jpg]

Copy‑paste the prompt below into your LLM agent. It’s designed to produce two website‑ready case studies, while keeping Case \#1 strictly grounded in your existing materials and making Case \#2 strong for hiring managers via clear context, decisions, and outcomes. Guidance like “capture decisions while the project is fresh” and “keep case studies visual and concise” is consistent with common portfolio advice from Fedor Shkliarau and hiring-manager heuristics (e.g., lead with visuals, show impact).[^1][^2]

```text
You are an expert product-design case-study writer + editor. You write in first person (“I”) as Roma, a product designer. Your job is to produce TWO case studies for my personal website portfolio.

NON‑NEGOTIABLES
1) Case #1 MUST be based ONLY on the provided sources (my current website content + my social posts). Do not invent facts. If something is missing, mark it as [TODO: ask Roma …] and continue without guessing.
2) Case #2 is a new case study. You may structure it like a real project, but you MUST avoid fabricating specific metrics, client-sensitive details, or internal names that were not provided. Use reasonable placeholders when needed (e.g., [metric TBD], [team size TBD]) and include a short list of questions for Roma to confirm.
3) Use the “case study recommendations” file as your writing checklist (structure, clarity, outcomes, storytelling). If recommendations conflict with this prompt, follow this prompt.
4) Use the provided “case example” references to emulate strong structure and pacing, but do NOT copy wording.
5) Images: do NOT embed real images. Use placeholders exactly like: [image with the final result.jpg]. Sprinkle them where visuals should appear.

SOURCE FILES (you must read and extract from these)
- Case #1 main content (current site):
  https://raw.githubusercontent.com/n-apps/md-notes/refs/heads/main/%5BRoma%20portfolio%5D%20Content%20of%20romamakescom.md
- Case #1 extra context (social posts):
  https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BSocial%20media%20posts%5D%20Score%20Counter-%20Count%20Anyth.md
- Recommendations checklist:
  https://raw.githubusercontent.com/n-apps/md-notes/refs/heads/main/%5BRecommendations%5D%20Case%20Study%20Recommendations%20for%20Product%20Designers.md
- Reference examples (structure inspiration only):
  https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BCase%20Example%5D%20Building%20a%20Scalable,%20Reusable%20Design%20System%20Template.md
  https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BCase%20Example%5D%20Design%20System.md
  https://github.com/n-apps/md-notes/raw/refs/heads/main/%5BCase%20Example%5D%20Rember.md

OUTPUT FORMAT
- Output Markdown for TWO separate pages: “case-1.md” and “case-2.md”.
- Keep each case study scannable: short paragraphs, meaningful headings, bullets for lists.
- Prefer concrete artifacts over vague process talk.
- Include at least 8 image placeholders per case (more if the story needs it).
- Avoid fluff. Avoid generic UX definitions. Assume the reader knows design basics.
- Tone: confident, calm, reflective, practical.
- Do not mention this prompt or the source files in the final case studies.

GLOBAL CASE STUDY TEMPLATE (use for both, adapt as needed)
1) Title (project + a crisp outcome hook)
2) One-line summary (who/what/impact)
3) Hero section
   - [image with the final result.jpg]
   - Role, timeframe, team, platforms
   - Confidentiality note if needed
4) Context
   - What the product/company is
   - Users/customers
   - Why it mattered (business + user stakes)
5) Problem & goals
   - The problem statement
   - Success metrics (if unknown: [metric TBD])
   - Constraints (tech, time, stakeholders, legacy)
6) My role & responsibilities
   - What I owned, what I influenced, what I didn’t do
7) Process (tell it like a story, decision-first)
   - Key moments, tradeoffs, constraints
   - Collaboration points (PM, engineers, marketing, etc.)
   - Show artifacts: flows, IA, wireframes, prototypes, iterations
   - [image …] placeholders near each artifact
8) Solution
   - What shipped (or what was delivered)
   - How it works (focus on the user journey + system logic)
   - Design rationale (why this, not that)
9) Outcome & impact
   - Quant + qual results (if unknown: [impact TBD])
   - What I learned
10) What I’d do differently
11) Next steps (if the project continued)
12) Links / credits (if allowed) + short CTA (e.g., “Want to see more? Contact me.”)

========================
CASE #1 REQUIREMENTS
========================
Case #1 name:
Board Games Companion App (600K Installs)

Rules for Case #1:
- Use ONLY the facts, numbers, features, dates, screenshots descriptions, and claims that appear in the two Case #1 sources.
- Extract any metrics (e.g., installs, retention, ratings, conversion, revenue, etc.) only if explicitly present.
- If the sources contain multiple apps/projects, make it unambiguous which one is the “Board Games Companion App (600K Installs)”.
- If “600K installs” is not in the sources, keep it as a headline claim BUT add: [TODO: confirm installs number + source].
- Include a clear “Before → After” narrative if supported by the sources; otherwise include “constraints + decisions + iterations” narrative.

Case #1 must include:
- A short “Product snapshot” block: platform, audience, key use cases, monetization (only if in sources).
- 3–5 “Key design decisions” with reasoning; for each decision, add an artifact placeholder.
- A section “What I’m proud of” with 3 bullets grounded in evidence.
- A section “How I worked” describing collaboration and iteration (only if supported; otherwise [TODO]).
- End with 5 questions you would ask Roma to strengthen the case study (only questions that emerged because info was missing).

Minimum images for Case #1 (placeholders; rename as needed):
- [image with the final result.jpg]
- [image with app store screenshots.jpg]
- [image with user flow diagram.jpg]
- [image with wireframes.jpg]
- [image with iteration comparison.jpg]
- [image with UI components.jpg]
- [image with edge cases.jpg]
- [image with learnings summary.jpg]

========================
CASE #2 REQUIREMENTS
========================
Case #2 name:
B2B ecosystem design system (Yesim)

Known project description (must be reflected accurately):
- I created a design system from scratch for Yesim’s group of B2B products.
- The challenge: scalability and flexibility, with components used in at least three products.
- The system must allow customizing appearance per product (similar to sub-brands).

Rules for Case #2:
- Do not fabricate confidential product details. Keep descriptions at a “portfolio safe” level.
- You MAY propose reasonable, standard design-system deliverables (tokens, components, guidelines, governance), but flag anything not confirmed as [assumption].
- Emphasize: scalability, cross-product consistency, theming/sub-branding, adoption, and governance.

Case #2 must include (specific sections):
A) “System goals & principles”
   - 5–7 principles (e.g., consistency vs flexibility tradeoffs, accessibility, composability), mark any uncertain ones as [assumption].
B) “Architecture”
   - Tokens strategy (color, typography, spacing, elevation), theming approach for sub-brands, component structure, naming conventions.
   - Include at least one small table: token layers or theming model (generic if needed).
C) “Component library”
   - Prioritize B2B patterns (tables, filters, forms, empty states, permissions, density), mark as [assumption] where needed.
D) “Documentation & governance”
   - Contribution model, review workflow, versioning, release notes, adoption plan, how requests are handled.
E) “Adoption across products”
   - How you ensured it works for 3+ products, migration strategy, how you measured adoption (if unknown: [metric TBD]).
F) “Tradeoffs & risks”
   - 5 bullets: what you deliberately didn’t solve, and why.
G) “Outcome”
   - What was delivered + how it changed the org/product velocity (keep metrics as [TBD] if not known).

Minimum images for Case #2 (placeholders; rename as needed):
- [image with design system overview.jpg]
- [image with tokens and theming model.jpg]
- [image with component anatomy.jpg]
- [image with table component spec.jpg]
- [image with form patterns.jpg]
- [image with sub-brand themes comparison.jpg]
- [image with documentation page example.jpg]
- [image with governance workflow diagram.jpg]
- [image with before-after UI consistency.jpg]

FINAL CHECKS BEFORE YOU OUTPUT
- Every major claim is either sourced (Case #1) or clearly labeled [assumption]/[TBD]/[TODO] (Case #2).
- Each case reads well when skimmed: headings tell the story.
- No generic filler like “I used Double Diamond”; focus on decisions + outcomes.
- Ensure both cases feel like they belong to the same designer and portfolio voice.

Now produce:
1) case-1.md
2) case-2.md
```

<span style="display:none">[^10][^11][^12][^13][^14][^15][^3][^4][^5][^6][^7][^8][^9]</span>

<div align="center">⁂</div>

[^1]: https://www.linkedin.com/posts/fedor_the-best-time-to-work-on-case-studies-for-activity-7274761813458616321-LOSS

[^2]: https://jlzych.com/2022/10/24/ingredients-for-a-great-product-design-case-study/

[^3]: https://gist.github.com/nnja/9136152c163091614e70defcf3753d06

[^4]: https://www.make.md

[^5]: https://www.docs-md.com

[^6]: https://raw.githubusercontent.com/google/gitiles/master/Documentation/markdown.md

[^7]: https://stories.hackmd.io

[^8]: https://apkcombo.com/file-converter/com.icecoldapps.fileconverter/

[^9]: https://romhandbook.com

[^10]: https://wise.readwise.io/issues/wisereads-vol-42/

[^11]: https://md.dhr.wtf

[^12]: https://www.scribd.com/document/774526099/Product-Design-Portfolio-Final-Final-Preview

[^13]: https://github.com/Make-md/makemd

[^14]: https://www.reddit.com/r/UXDesign/comments/1avrvpe/senior_product_designer_case_studies/

[^15]: https://md-notes-docs.netlify.app

