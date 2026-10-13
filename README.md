# AI Product Management Portfolio

This repository is the working foundation for an AI Product Manager portfolio. It brings together product discovery, strategy, execution, analytics, go-to-market, and AI/LLM product work. The goal is to turn learning and project artifacts into concise case studies that show product judgment and measurable outcomes.

## Portfolio themes

- **Discovery:** interviews, personas, journeys, usability, and concept validation
- **Strategy:** market and competitor analysis, opportunity framing, positioning, and roadmaps
- **Execution:** PRDs, user stories, sprint planning, prioritization, and stakeholder alignment
- **Measurement:** funnels, product metrics, experimentation, and growth
- **AI product management:** AI use cases, LLM capabilities, prompt design, responsible AI, and model/product trade-offs
- **Business:** pricing, business models, GTM, and lifecycle planning

## Repository contents

- [`context.md`](./context.md) — portfolio positioning, case-study directions, and suggested structure
- [`read.me`](./read.me) — the original portfolio setup notes

The original course/workshop bundle is kept locally and excluded from Git by default. It contains third-party learning materials and examples that are not yet cleared for redistribution. Select work you created or have permission to share, rewrite it as a case study, and add only the reviewed artifacts to the portfolio repository.

## Suggested case studies

1. Product analytics and funnel analysis
2. Competitor teardown and opportunity assessment
3. A PRD, roadmap, and sprint-planning example
4. An AI product concept with trust and responsible-AI considerations
5. User research and usability validation
6. GTM or pricing strategy

## Git setup and workflow

Initialize this folder locally when ready:

```powershell
git init -b main
```

The local source bundle is ignored, so the initial repository contains only the portfolio setup documents and any files you explicitly add outside that bundle. Review what Git will track:

```powershell
git status --short
```

When the portfolio content and publishing rights are ready, stage only the files you intend to publish, review the staged changes, then commit:

```powershell
git add <files-you-own-and-want-to-publish>
git diff --cached
git commit -m "Prepare AI PM portfolio"
```

To publish later, create an empty repository on your chosen Git host and add its URL as the `origin` remote. No remote or push is configured by this setup.

## Privacy and publishing checklist

- Do not commit raw customer, user, candidate, or event-level records.
- Review filenames, document contents, comments, hidden sheets, and file metadata before publishing.
- Include only work you created or are authorized to share.
- Course handouts, workshop materials, third-party examples, logos, and candidate-assignment data may have redistribution restrictions. Confirm the applicable permissions before making the repository public.
- Replace placeholders with reviewed portfolio content; do not include personal contact details unless you explicitly want them public.

## Next steps

1. Create a `case-studies/` folder for your original, reviewed work.
2. Write a short profile and link a current resume.
3. Select three to five projects and create polished case studies.
4. Add sanitized visuals and artifacts that you have permission to publish.
5. Review the complete staged diff and GitHub's repository visibility before pushing.
6. Continue refining the portfolio based on feedback and new work.
