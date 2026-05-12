---
pagetitle: Home
---

# Starsim

Starsim is a fast, flexible framework for agent-based modeling of health and disease. It supports co-transmission of multiple diseases, non-infectious conditions, detailed mother-child relationships, multiple network types, flexible interventions, automated calibration, and varying levels of detail from agent-based to compartmental.

Starsim is available for both Python and R, and is fully open-source under the MIT license. For more information, see <a href="https://starsim.org">starsim.org</a>.

## Getting started

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

## Why Starsim?

Starsim achieves C++ speeds from pure Python via array computations and just-in-time compilation, so simulations run on laptops rather than supercomputers. Its modular design lets you reuse or adapt disease models, transmission networks, and demographics — mix, match, and modify any module. Starsim is a community, not a product: we believe diversity, transparency, and collaboration are essential for real-world health outcomes.

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

## AI-accelerated development

Starsim includes [Starsim-AI](https://github.com/starsimhub/starsim_ai): MCP servers, skills, and plugins you can use with your favorite code editor to accelerate model development.
