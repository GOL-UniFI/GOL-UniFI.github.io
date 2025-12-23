---
layout: page
title: AIMS
permalink: /pages/projects/aims/
---



# AIMS: Artificial Intelligence for the Management of Shifts

## Research Overview
The **AIMS project** (Artificial Intelligence for the Management of Shifts) was a research initiative funded by the **Tuscany Region** (POR CreO 2014-2020). The project focused on developing advanced **optimisation tools for personnel shift scheduling** based on real-world activity demands.

Our research unit, the **Global Optimization Laboratory (GOL)** at the University of Florence, in collaboration with **FirLab s.r.l.**, spearheaded the development of mathematical models to solve the **Integrated Task Scheduling and Personnel Rostering (TSPR)** problem.

## Our Scientific Contribution: Integrated TSPR
Historically, personnel management issues—**staff rostering** (defining shifts) and **activity assignment** (scheduling tasks)—have been treated separately and sequentially. Our research demonstrates that treating these as a single, integrated problem significantly increases solution quality.

### Key Innovation: Mixed-Integer Linear Programming (MILP)
We formalised the TSPR problem into a **Mixed-Integer Linear Programming (MILP)** model. This model simultaneously decides:
*   The activation of employees.
*   The definition of optimal shifts.
*   The assignment of specific tasks (e.g., check-in, cleaning, boarding) to those shifts.

### Mathematical Advancements for Tractability
To handle large-scale data from international airports, our unit introduced **clique-based valid inequalities**. 
*   **Clique Inequalities:** These mathematical constraints strengthen the model by cutting off "unfeasible" fractional solutions during computation, allowing for **near-optimal solutions in reasonable timeframes**.
*   **Constraint Management:** The model incorporates complex real-world requirements, including **heterogeneous workforce skills**, contractual limits on weekly hours, and mandatory **11-hour resting periods** between shifts.

## Validation: The Airport Case Study
The research was validated using real-world data from the **Bergamo Orio al Serio Airport**. Airport environments are uniquely challenging due to **24/7 operations** and highly time-varying demand.

**Results showed that our integrated model:**
*   Significantly **reduced idle time** compared to traditional sequential methods.
*   Lowered the total number of **active workers** needed to cover 100% of the demand.
*   Outperformed the meta-heuristic models currently used in production systems by ensuring higher efficiency and strict adherence to legal constraints.

## Official Project Partners
*   **Academic Partner:** [Global Optimization Laboratory (GOL)](https://webgol.dinfo.unifi.it/), University of Florence.
*   **Industrial Partner:** [FirLab s.r.l.](https://www.firlab.it/).
*   **Management Partner:** [Resolvo S.r.l.](https://www.resolvo.eu/case-studies/aims/).

## References
*   **Cappanera, P., Di Gangi, L., Lapucci, M., Pellegrini, G., Roma, M., Schoen, F., and Sortino, A. (2024).** *Integrated task scheduling and personnel rostering of airports ground staff: A case study*. **Expert Systems with Applications**, 238, 121953. [DOI: 10.1016/j.eswa.2023.121953](https://doi.org/10.1016/j.eswa.2023.121953).

## Project Funding and Logos
*This project was supported by the POR CreO FESR 2014-2020 funds of the Tuscany Region.*

| | | |
|:---:|:---:|:---:|
| ![POR CreO Toscana - Unione Europea - Repubblica Italiana - Regione Toscana](loghi.png?text=POR+CreO+Toscana) | ![Università di Firenze](unifi.png?text=UNIFI+GOL) | ![FirLab](firlab.png?text=FirLab) |

```

*** 
*   The **DOI link** provided in the references section leads directly to the published version of your paper in *Expert Systems with Applications*.
*   The analogy at the end is provided to help non-expert visitors quickly grasp the value of the "Integrated" approach described in the sources.
