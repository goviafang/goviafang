Backend engineer and architect, 15+ years in PHP. I run Amoozie, my own software studio.

## What I'm working on

- **RECO Pass**, a study platform for Ontario's RECO real estate licensing exam. I'm the only engineer on it: Laravel API, Vue and Vite on the client, MeiliSearch for search, Sentry for errors. I also provision and maintain the GCP Compute Engine instances it runs on, including the IAM roles and firewall rules. Releases go out most days.
- The question bank comes out of an LLM pipeline I built. Source material is curated by hand, the model drafts questions, answers and explanations, then a human expert reviews everything before publication. Licensing exam content has to be correct, so every generated item gets read by a person first. The pipeline runs offline and users never touch it.
- A Claude Code agent-skills toolchain, used in every repository at Amoozie. I wrote the standards that go with it: anything a model writes goes through a named human reviewer before it can merge, skills live in version control and get reviewed like code, and output that can't be checked against a test or a spec doesn't go in.

## Before that

For eight years I ran the real estate platform at 51.CA, Canada's largest Chinese-language media company, leading a team of 15 across backend, frontend, mobile, server operations and QA. The MLS feeds ran around the clock and brought in millions of listing records a day, and the public site still had to stay fast while all of that was writing. So the read path went onto MySQL read/write splitting with a Redis cache in front of it, and ingestion and image processing moved onto Redis queues. Later we broke the content services into smaller services talking over internal REST APIs, with the request and response classes kept in shared Composer packages so each contract was versioned in one place. I also built the agent product: a WordPress site per agent fed from the shared listing pool, with buyer lead routing on top of it. On the process side I replaced FTP deployment with a Git branching workflow, mandatory code review and automated deploys, and moved core services off VPS onto AWS with Docker.

Earlier: a multi-tenant e-commerce platform at Wabow, and before that payment collection and financial reconciliation at ELTA, a national OTT operator in Taiwan, where I also delivered the broadcast technology for the Olympics and the FIFA World Cup.

## Skills

- **Backend:** PHP · Laravel · Python · REST API design · MySQL (read/write splitting, query optimization, schema design) · Redis (queues, caching)
- **Architecture:** microservices · shared contract packages · multi-tenant and white-label platforms · third-party data integration (MLS)
- **Full stack:** TypeScript · Vue.js · Flutter / Dart · Astro · Vitest
- **Infrastructure:** GCP (Compute Engine, IAM, firewall rules) · AWS · Docker · Nginx · Linux · Cloudflare · Supabase · MeiliSearch · Elasticsearch · Sentry
- **AI:** LLM pipelines in production with a human review step · Claude Code agent skills · team standards for AI-assisted development
- **Practice:** technical leadership (15 engineers) · CI/CD · code review · mentoring · remote async work

## Contact

Working languages: English · Mandarin (native)

[LinkedIn](https://www.linkedin.com/in/goviafang/)
