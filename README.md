# Influence of AI on Stack Overflow Users (2017–2025)

*A reproducible analysis of how AI appears in the Stack Overflow Developer Survey—its rising prominence, adoption, sentiment, trust, and usage patterns.*

---

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code can be run using the standard distribution of Python versions 3.*. Necessary libraries for producing the plots are matplotlib and seaborn.

## Project Motivation<a name="motivation"></a>

The goal of this project is to analyze Stack Overflow’s annual Developer Survey (2017–2025) to answer four questions:
- **How** did AI-related content in the survey evolve over time?
- **How** have developers’ perceptions of AI changed (adoption, sentiment, trust)?
- **What** are the most common **use cases** for AI among developers?
- **What data quality considerations** (schema changes, non-response) affect interpretation?

This project harmonizes survey schemas across years, quantifies the rise of AI-related items, and tracks perception and usage trends with appropriate caveats.

## File Descriptions <a name="files"></a>

- `Project.ipynb` — Main notebook: data ingestion, schema harmonization (2017–2025), analysis, and figures.
- `README.md` — This file.
- `docs` - Files necessary for the blogpost for this analysis.

## Results<a name="results"></a>

- **AI’s growing prominence**: AI-related items increased markedly; by 2025 they account for a significant share of the survey instrument.
- **Adoption**: A clear majority report using AI by 2024; in 2025, most “Yes” users indicate daily use.
- **Attitude**: Still predominantly favorable, but softening into 2025 (rise in “very unfavorable”).
- **Trust**: Net trust remains positive, yet declines by 2025 (increase in “highly distrust” responses).
- **Usage patterns**: Writing code and search for answers lead; code review, deployment/monitoring, and project planning remain less AI-driven.
- **Data quality notes**: Yearly schema changes and high non-response (particularly for usage blocks) require cautious interpretation.

The main findings of the code can be found at the post available [here](https://uuji17d.github.io/StackoverflowSurvey_UpskillingProject/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

- Stack Overflow for the Developer Survey and documentation which can be found [here](https://survey.stackoverflow.co/).
- Open-source libraries and their maintainers (pandas, numpy, matplotlib, seaborn, jupyter, etc.).
- Udacity for motivating this analysis during a data science course.