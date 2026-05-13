---
pagetitle: Home
---

# Starsim

Starsim is an open-source disease modeling framework used to answer real-world public health questions — including how to roll out HPV vaccination, scale up HIV prevention, target tuberculosis programs, and expand access to family planning. It is designed to give analysts and program teams trustworthy, locally relevant evidence to support decisions about which interventions to fund, where to deploy them, and how to measure impact.

Starsim is freely available for both Python and R under the MIT license. For policy applications, case studies, and team information, see [starsim.org](https://starsim.org).

## Why Starsim?

<div class="grid cards" markdown>

-   :material-check-decagram:{ .lg .middle } __Used in real programs__

    ---

    Starsim models have informed program decisions on HPV vaccination, HIV and STI services, tuberculosis, and family planning in partnership with ministries of health, NGOs, and global funders.

-   :material-eye-outline:{ .lg .middle } __Open and transparent__

    ---

    Starsim is fully open-source under the MIT license, with peer-reviewed publications documenting its methods and applications. Assumptions, code, and data flows are inspectable end-to-end.

-   :material-earth:{ .lg .middle } __Broad applicability__

    ---

    A single framework covers a wide range of diseases — HIV, HPV, TB, STIs, family planning, and more — making it easier to compare interventions and combine evidence across programs.

-   :material-rocket-launch:{ .lg .middle } __Fast and flexible__

    ---

    Starsim runs on a laptop, not a supercomputer, and its modular structure lets diseases, networks, demographics, and interventions be reused, adapted, or replaced without rewriting the core framework.

</div>

For representative work, see for example *[HPVsim: An agent-based model of HPV transmission and cervical disease](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012181)* (Stuart et al., PLOS Computational Biology, 2024) and *[The role of HPV single-dose vaccination in expanding access in GAVI-supported countries](https://www.sciencedirect.com/science/article/abs/pii/S0264410X25014859)* (Stuart et al., Vaccine, 2026).

## Models

The Starsim ecosystem includes a growing set of disease-specific models. A more detailed list is available in the [Starsim documentation](https://docs.starsim.org/user_guide/intro_models.html).

<div class="grid cards" markdown>

-   :material-virus:{ .lg .middle } __STIsim__

    ---

    Sexually transmitted infections, including HIV.

    [:octicons-arrow-right-24: STIsim](https://stisim.org)

-   :material-dna:{ .lg .middle } __HPVsim__

    ---

    Human papillomavirus transmission and cervical disease.

    [:octicons-arrow-right-24: HPVsim](https://hpvsim.org)

-   :material-human-pregnant:{ .lg .middle } __FPsim__

    ---

    Family planning and reproductive health.

    [:octicons-arrow-right-24: FPsim](https://fpsim.org)

-   :material-lungs:{ .lg .middle } __TBsim__

    ---

    Tuberculosis transmission and progression.

    [:octicons-arrow-right-24: TBsim](https://starsim.org/tbsim)

</div>

## Get started

If you build, calibrate, or extend Starsim models, these are the entry points:

<div class="grid cards" markdown>

-   :material-book-open-variant:{ .lg .middle } __Documentation__

    ---

    Full Starsim documentation, including API reference.

    [:octicons-arrow-right-24: Docs](https://docs.starsim.org)

-   :material-school:{ .lg .middle } __Tutorials__

    ---

    Step-by-step tutorials for getting started with Starsim.

    [:octicons-arrow-right-24: Tutorials](https://docs.idmod.org/projects/starsim/en/latest/tutorials.html)

-   :material-github:{ .lg .middle } __Source code__

    ---

    The Starsim source code on GitHub.

    [:octicons-arrow-right-24: Code](https://github.com/starsimhub/starsim)

-   :material-language-r:{ .lg .middle } __R interface__

    ---

    Run Starsim from R via the rstarsim package.

    [:octicons-arrow-right-24: R Docs](https://r.starsim.org)

</div>

## Installation

Install from Python:

```bash
pip install starsim
```

Or from R:

```r
devtools::install_github("starsimhub/rstarsim")
library(starsim)
init_starsim()
```

## AI-accelerated development

For technical contributors, [Starsim-AI](https://github.com/starsimhub/starsim_ai) provides MCP servers, skills, and plugins that integrate Starsim with modern code editors to speed up model development.
