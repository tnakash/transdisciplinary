# Transdisciplinary Engineering — Evaluation Rubric

*English version of [rubric.md](./rubric.md).*

Based on the [definition and framework](../docs/01_definition_and_framework_en.md) (A. Goal / B. Collaboration / C. Integration / D. Application domain), the following metrics are defined for evaluating the collected papers. Each paper is judged from its Title/Abstract/Keywords (and full text where a PDF is available).

## Evaluation Policy

- The three core indicators (Goal / Collaboration / Integration) are each scored on a **1–5 ordinal scale**, measuring "how TE-like" the paper is (i.e., how much it practices transdisciplinarity).
- The two auxiliary indicators (methodological contribution, validation level) measure the **maturity/quality** of the work as research.
- Application domain is assigned as a categorical variable, used for color-coding etc. in the mapping.
- Rather than a single consensus "correct score," results are presented as a **multi-dimensional positioning (map)**, following the "landscape" concept of Lattanzio et al. (2021).

## Core Indicators (How TE-like)

### G. Goal Orientation — 1–5 points
Whether the problem framing is ill-defined/a wicked problem, and whether social relevance is made explicit.

| Score | Criterion |
|---|---|
| 1 | A clearly structured technical problem within a single discipline (no mention of social relevance) |
| 2 | Technical problem is central, with light mention of application context or social background |
| 3 | Industrial/social challenge is explicitly stated as background; partially addresses an ill-defined problem |
| 4 | Clearly defines a socially/industrially important challenge involving multiple stakeholders |
| 5 | Explicitly framed as a wicked/ill-defined problem, with impact on society, environment, and economy at its core |

### C. Collaboration Breadth — 1–5 points
Breadth of cross-disciplinarity and diversity of stakeholders.

| Score | Criterion |
|---|---|
| 1 | Research within a single engineering sub-discipline |
| 2 | Collaboration across multiple engineering sub-disciplines (e.g., mechanical × electrical) |
| 3 | Collaboration between engineering and an adjacent field (information science, management engineering, etc.) |
| 4 | Explicit collaboration between engineering and social science/humanities (management, psychology, policy science, etc.), or academia-industry collaboration |
| 5 | Includes a co-creation process among diverse stakeholders — academia, industry, government, citizens/end users |

### I. Integration Depth — 1–5 points
Depth of integration of knowledge, methodology, and process.

| Score | Criterion |
|---|---|
| 1 | Knowledge from each discipline is merely juxtaposed (no integration) |
| 2 | Cross-referencing/comparison between disciplines exists, but no methodological integration |
| 3 | A specific methodology/tool is applied across disciplines (e.g., partial adoption of mixed methods) |
| 4 | Proposes a framework that systematically integrates methodologies, data, and processes from multiple disciplines |
| 5 | Achieves/demonstrates true knowledge integration beyond ontological/epistemological boundaries (co-creation of academic × practical knowledge) |

**TE-Index (composite indicator)** = (G + C + I) / 3 (in 0.5 increments, max 5). An overall score of how well the paper aligns with the core concept of TE.

## Auxiliary Indicators (Research Maturity)

### M. Methodological Contribution — 1–5 points
| Score | Criterion |
|---|---|
| 1 | A review/explanation of existing methods only |
| 2 | A small-scale improvement or application of an existing method |
| 3 | Presents a new application case/case study |
| 4 | Proposes a new framework/method/tool |
| 5 | Proposes a new framework and discusses generalizability to other domains/cases |

### V. Validation Level — 1–5 points
| Score | Criterion |
|---|---|
| 1 | Conceptual discussion only (no validation) |
| 2 | A simple illustrative example |
| 3 | Validated through a single case study |
| 4 | Validated through multiple cases / real data |
| 5 | Validated through industrial implementation, long-term operation, or quantitative impact measurement |

## Add-on Metric: Disciplinary Span (Author / Method / Objective)

The existing Collaboration Breadth (C) captures "breadth of collaboration" as a single ordinal scale. This add-on metric independently visualizes **how far the Author(s), the Method, and the Objective of a paper each cross disciplinary boundaries**. It is assigned independently of G/C/I/M/V, and does not alter any existing field.

### Discipline Taxonomy (8 categories)

For each of a paper's Author / Method / Objective, applicable disciplines are assigned as a **multi-label selection** from the following 8 categories.

1. Engineering (mechanical, electrical, civil, aerospace, industrial engineering, etc.)
2. Natural Science (physics, chemistry, biology, materials science, etc.)
3. Social Science (sociology, economics, policy science, anthropology, etc.)
4. Management / Business (management, organizational theory, marketing, etc.)
5. Data Science / CS (information science, computer science, statistics, AI, etc.)
6. Humanities (philosophy, psychology, design theory, ethics, etc.)
7. Medicine / Health (medicine, public health, nursing, etc.)
8. Other (disciplines not covered above)

### Evaluation Axes

- **Author disciplines**: Disciplines inferable from the authors' affiliations/expertise (judged from departmental affiliations in the author list, co-authorship composition, and the paper's writing register).
- **Method disciplines**: Disciplines from which the adopted methodology/technique/tools originate (e.g., ethnography → Social Science, finite element analysis → Engineering, machine learning → Data Science / CS).
- **Objective disciplines**: Disciplines to which the research objective/problem framing belongs (e.g., improving manufacturing efficiency → Engineering, understanding user behavior → Social Science, elucidating material properties → Natural Science).

For each axis, applicable disciplines are listed, and the **number of disciplines (span)** is computed.

| Span value | Meaning |
|---|---|
| 1 | Single discipline (disciplinary) |
| 2 | Spans 2 disciplines (interdisciplinary-like) |
| 3+ | Spans 3 or more disciplines (transdisciplinary-like breadth) |

**Disciplinary Span Index (DSI)** = (author_span + method_span + objective_span) / 3. A composite indicator of how much a paper crosses disciplinary boundaries across the Author, Method, and Objective axes (reported alongside, and independent of, the existing TE-Index).

## Categorical Variables (Mapping Metadata)

- **Domain**: Research / Practice / Education / Multiple (the three domains of Wognum et al. 2019)
- **Application Theme**: e.g., Industry 4.0, Sustainability/Resilience, Social Innovation, Product Lifecycle/PLM, Systems Engineering, Design Methodology, Education, Digital Twin, Other
- **Disciplinary Pairing**: e.g., Engineering×Engineering, Engineering×Social Science, Engineering×Management, Engineering×Data Science, etc.

## Field Definitions (papers/metadata records)

| Field | Description |
|---|---|
| id | Paper ID (sequential) |
| title | Title |
| authors | Authors |
| year | Publication year |
| venue | Publication venue (conference or journal) |
| keywords | Keywords |
| abstract | Abstract |
| pdf_status | full_text / abstract_only |
| pdf_path | PDF file path (if obtained) |
| G, C, I, TE_index | Core indicator scores |
| M, V | Auxiliary indicator scores |
| domain | Application domain category |
| theme | Application theme category |
| pairing | Disciplinary pairing |
| rationale | Rationale for the scores (1–2 sentences, kept in Japanese in the underlying dataset) |
| author_disciplines, method_disciplines, objective_disciplines | Discipline list for each of Author/Method/Objective (multi-label from the 8-category taxonomy) |
| author_span, method_span, objective_span, DSI | Disciplinary span for each axis and the composite Disciplinary Span Index |
