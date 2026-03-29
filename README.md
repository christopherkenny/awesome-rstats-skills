# Awesome R Stats Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent skills for R programming and statistics.

AI agent skills are reusable prompt files (typically `SKILL.md`) that extend coding assistants like [Claude Code](https://claude.ai/code) with specialized, domain-specific workflows.
This list focuses on skills useful for R users.

## Contents

- [R Code Reviewers](#r-code-reviewers)
- [General Data Analysis](#general-data-analysis)
- [Tidyverse](#tidyverse)
- [Package Development](#package-development)
- [CRAN Submission Help](#cran-submission-help)
- [Performance](#performance)
- [Skill Collections](#skill-collections)
- [Tutorials and Blogs](#tutorials-and-blogs)

## Skills

### R Code Reviewers

Skills for auditing and reviewing R code quality, style, and correctness.

- [review-r](https://github.com/pedrohcgs/claude-code-my-workflow/tree/main/.claude/skills/review-r) by [@pedrohcgs](https://github.com/pedrohcgs) - Comprehensive review of R scripts across code quality, reproducibility, domain correctness, and professional standards. Generates detailed reports without modifying source files.

### General data analysis

General skills for programming patterns.

- [r-analyst](https://github.com/nealcaren/social-data-analysis/tree/main/plugins/r-analyst/skills/r-analyst) by [@nealcaren](https://github.com/nealcaren) - Guides a systematic, phased workflow for conducting publication-ready statistical analysis in R, emphasizing research design before estimation and robust sensitivity testing.
- [ds-assistant](https://github.com/chendakeng/claude-code-skill-ds-assistant/tree/main/skills/ds-assistant) by [@chendakeng](https://github.com/chendakeng) - Tools for general purpose data science assistant with instructions for Shiny and Quarto.
- [event-studies](https://github.com/dariia-m/my_claude_skills/tree/main/event-studies) by [@dariia-m](https://github.com/dariia-m) - Covers many differences-in-differences methods from classic fixed effect regressions to modern staggered adoption methods

### Tidyverse

Skills for writing idiomatic tidyverse code.

- [tidyverse-patterns](https://github.com/ab604/claude-code-r-skills/tree/main/.claude/skills/tidyverse-patterns) by [@ab604](https://github.com/ab604) - Modern `tidyverse` patterns covering pipes, joins, grouping, `purrr`, and `stringr` for writing current best-practice R code.
- 

### Package development

Skills for package development workflows.

- [r-package-development](https://github.com/ab604/claude-code-r-skills/tree/main/.claude/skills/r-package-development) by [@ab604](https://github.com/ab604) - Guides R package creation covering dependencies, API design, testing, documentation, and release workflows.
- [testing-r-packages](https://github.com/posit-dev/skills/blob/main/r-lib/testing-r-packages/SKILL.md) by [@posit-dev](https://github.com/posit-dev) - Guides test suite development for R packages using `testthat` 3+, covering test structure, expectations, fixtures, snapshots, and mocking.

### CRAN submission help

Skills for checking and submitting R packages to CRAN.

- [cran-submit](https://github.com/CoryMcCartan/agent-skills/tree/main/cran-submit) by [@CoryMcCartan](https://github.com/CoryMcCartan) - Runs automated checks, fixes issues, conducts adversarial review, and guides packages through a six-phase submission process to minimize resubmission cycles.
- [cran-extrachecks](https://github.com/posit-dev/skills/blob/main/r-lib/cran-extrachecks/SKILL.md) by [@posit-dev](https://github.com/posit-dev) - Checks for common CRAN requirements that standard development tools miss, including documentation completeness, DESCRIPTION formatting, URL validation, and administrative compliance.

### Performance

Skills for profiling, benchmarking, and optimizing R code.

- [r-performance](https://github.com/ab604/claude-code-r-skills/tree/main/.claude/skills/r-performance) by [@ab604](https://github.com/ab604) - Teaches R performance optimization through profiling and benchmarking with `profvis`, `bench::mark`, `vctrs`, and parallel processing, including decision guidance on `data.table` vs `dplyr` trade-offs.

## Skill collections

Full repositories of R-focused skills worth browsing.

- [skills](https://github.com/posit-dev/skills) by [@posit-dev](https://github.com/posit-dev) - Collection of skills from Posit covering R package development, Shiny, Quarto, and developer workflows.
- [claude-code-r-skills](https://github.com/ab604/claude-code-r-skills) by [@ab604](https://github.com/ab604) - Comprehensive Claude Code configuration for R development with 8 skills spanning tidyverse, performance, OOP, Bayesian methods, package development, and TDD.
- [claude-skills](https://github.com/jeremy-allen/claude-skills/) by [@jeremy-allen](https://github.com/jeremy-allen/) - Claude agent skills for using R's tidyverse. Mostly Derived from [Sarah Johnson's stellar CLAUDE.md](https://gist.github.com/sj-io/3828d64d0969f2a0f05297e59e6c15ad).
- [pkgskills](https://github.com/api2r/pkgskills/) by [@jonthegeek](https://github.com/jonthegeek) - A collection of curated, opinionated skills and agent instructions to improve agentic coding of R packages.

## Tutorials and blogs

Posts and guides on using AI agent skills for R.

- [A Few Claude Skills for R Users](https://rworks.dev/posts/claude-skills-for-r-users/) by [@ivelasq](https://github.com/ivelasq) - Roundup of community-built Claude skills for R developers covering `tidyverse` practices, package development, Quarto authoring, and brand consistency.

---

## License

This list is licensed under CC0.

## Contributing

Contributions welcome! Please read the [contribution guidelines](contributing.md) first.
