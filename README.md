## Hi, I'm Tarun

I'm a product builder. I take a product from user research to a live, tested app on my own: the research, PRD, design, build and QA, with AI coding agents as my build team.

These days I mostly build **AI products**: retrieval-augmented answers, LLM grading against a rubric, and guardrails for when the model shouldn't answer.

### Things I've shipped

| Product | What it does | Proof |
|---|---|---|
| **[Playbook](https://product-bible.vercel.app)** · [code](https://github.com/TarunPur/product-bible) | Ask a product question and get an answer drawn from Lenny's Podcast, with every citation checked against the retrieved transcript before it's shown | RAG on pgvector, groundedness grading, golden-set evals |
| **[Clearline](https://traffic-congestion-tau.vercel.app)** · [code](https://github.com/TarunPur/traffic-congestion) | A Delhi NCR commute planner (Metro, bus, auto, walk) that tells you when to leave and how to go | 37 test files + Playwright E2E, CI on every push, RLS tests in SQL |
| **[NOD](https://learning-tech-ai.vercel.app)** · [code](https://github.com/TarunPur/learning-tech-ai) | AI coaching for non-technical professionals: you do one real task with it, and an expert rubric gives you feedback | Built on a 160-response user survey; rubric discrimination tests; PII auto-masking |
| **[WorkReview](https://workreview.vercel.app)** · [code](https://github.com/TarunPur/workreview) | Peer and manager reviews for professionals, with team import and email profile claiming | Next.js 16 + Supabase, API route tests |

### How I build

- **Research before scope.** I validate the problem before I write a PRD.
- **Every stage of the customer journey gets a decision**, from awareness to support, not only the product screens.
- **Quality gates before "done":** strict TypeScript (no `any`, enforced by lint), tests, CI, accessibility checks and a live click-through.

**Stack:** Next.js · TypeScript · Supabase (Postgres, RLS, pgvector) · Tailwind · Claude API · Vercel

[LinkedIn](https://www.linkedin.com/in/tarun-puri-product-manager)
