# Starting a New Project

New projects start from the family pattern, not from zero:

- **Follow the standard.** The published
  [engineering standard](https://github.com/cuesoftinc/oss-engineering-standards)
  sets the baseline for structure, testing and review on every new repo.
- **Copy a sibling, not a boilerplate.** Our repos are maintained as one
  system — tooling, CI, config and folder structure stay identical across
  siblings, and only the product code differs. Start a new project by
  mirroring the closest existing repo in the
  [cuesoftinc](https://github.com/cuesoftinc) org, and keep the parity: if
  you improve one repo's tooling, improve its siblings' in the same
  session.
- **Wire the guardrails on day one.** Linting, type checks, tests and CI
  come with the first commit — retrofitting them later never happens.
- **Ask before creating.** New repositories are created by the CTO so
  naming, access and infrastructure wiring stay consistent.
