# Transdisciplinary Engineering — Literature Evaluation Results Summary

*English version of [02_evaluation_results.md](./02_evaluation_results.md).*

Scope: 122 papers evaluated per the [evaluation rubric](../evaluation/rubric_en.md) (102 from ISTE/ISPE Transdisciplinary Engineering international conference proceedings, 2016–2025; 20 from related journals).
Data: [Evaluated dataset (CSV)](../evaluation/te_papers_evaluated.csv) / [Interactive mapping](./te_mapping.html)

## 1. Overall Trends

| Indicator | Average | Min | Max |
|---|---|---|---|
| G (Goal Orientation) | 2.93 | 1 | 5 |
| C (Collaboration Breadth) | 3.20 | 1 | 5 |
| I (Integration Depth) | 2.93 | 1 | 4 |
| **TE-Index (composite)** | **3.01 / 5** | **1.0** | **4.7** |
| M (Methodological Contribution) | 2.97 | 1 | 5 |
| V (Validation Level) | 2.21 | 1 | 4 |

- **V (Validation Level) has the lowest average**, indicating that much of the research claiming to be "TE" remains at the level of conceptual proposals or single illustrative cases, with relatively few studies backed by multiple cases or quantitative impact measurement.
- Among G, C, and I, **C (Collaboration Breadth) is the highest**, but at only ~3.2 out of 5, genuine co-creation involving society, industry, and citizens (level 5) is actually a minority — most collaboration remains within engineering or between engineering and management (see the disciplinary pairing distribution below).

## 2. Papers with High vs. Low "TE-ness"

**Top-scoring papers (TE-Index ≥ 4.3)** all share the trait of addressing real-world wicked problems (regional energy policy, systemic risk, water resource management, prosthetics engineering, regulatory-change response, community development) through co-creation with diverse stakeholders and longer-term validation.

**Bottom-scoring papers (TE-Index ≤ 2.0)** fall into one of two categories: (1) papers that include "transdisciplinary" in the title but are in substance single-discipline technical papers (information/mechanical engineering), or (2) literature reviews / bibliometric analyses of existing research. **A gap between the label "transdisciplinary" and actual TE practice** is one of the key findings of this evaluation (the "TREND" research group led by Lattanzio et al. 2020 reports a consistent concern, finding that none of 41 existing design tools they examined could genuinely be called TD).

## 3. Categorical Distribution

- **Domain**: Research 67 / Practice 34 / Multiple 14 / Education 7 — research on education (TDEE) is relatively scarce, suggesting the thinness of the education area flagged in the research agenda of Wognum et al. (2019) may still persist.
- **Application Theme**: Design Methodology (25) > Other (19) > Industry 4.0 (15) ≈ Sustainability/Resilience (15) > PLM (12) ≈ Systems Engineering (12) > Education (11) > Social Innovation (8) > Digital Twin (5)
- **Disciplinary Pairing**: Engineering×Management (38) ≈ Engineering×Social Science (38) > Engineering×Engineering (25) > Engineering×Data Science (12) > Other (9) — collaboration centers on engineering with management and social science, while integration with data science is still emerging.

## 4. Year-over-Year Trend (ISTE/ISPE TE Conference, 2016–2025)

The average TE-Index rose gradually from 2.75 in 2016 to 3.23 in 2025, suggesting a deepening of practice (particularly in Collaboration and Integration) since the conference series was renamed "Transdisciplinary Engineering" in 2016. That said, there is year-to-year variation rather than a strictly monotonic improvement.

## 5. Implications

1. **Quality assurance for research claiming to be "TE" requires raising V (Validation Level).** Many papers remain at the conceptual-proposal stage; accumulating research with multiple cases and quantitative evaluation is needed going forward.
2. **The Engineering×Social Science pairing accounts for over 30% of the corpus**, suggesting TE's definitional emphasis (integrating natural science and social science) is reflected in practice to some degree. However, many papers still label purely intra-engineering integration (Engineering×Engineering) as "TE," leaving the boundary with Multidisciplinary/Interdisciplinary work ambiguous in practice.
3. **The interactive mapping artifact** allows filtering by Domain and inspecting individual papers' scoring rationale, which can support extracting best practices from high-TE-Index cases in specific application areas (e.g., Sustainability/Resilience).

## 6. Analysis of Disciplinary Span (Author / Method / Objective)

Based on the [rubric's add-on metric](../evaluation/rubric_en.md#add-on-metric-disciplinary-span-author--method--objective), each paper's Author, Method, and Objective were evaluated for how far they cross the 8-category discipline taxonomy (see the "Disciplinary Span" card in the [mapping artifact](./te_mapping.html) for an interactive visualization).

| Axis | Average span | Breakdown (1 discipline / 2 disciplines / 3+ disciplines) |
|---|---|---|
| Author | 1.52 | 59 / 62 / 1 |
| Method | 1.81 | 34 / 77 / 11 |
| Objective | 1.86 | 33 / 74 / 15 |

**Average DSI (Disciplinary Span Index) = 1.73** (theoretical max ≈ 2.67, i.e., 8/3)

- A clear asymmetry emerges: **Objective crosses disciplines most readily, while Author crosses disciplines the least.** Many papers have authorship confined to Engineering alone while their stated Objective spans Engineering plus Social Science/Management — suggesting **the interdisciplinarity of author teams has not kept pace with the interdisciplinarity of the stated objectives.**
- Discipline frequency by role (Author / Method / Objective): Engineering dominates overwhelmingly across all three axes (119 / 98 / 115 papers). By contrast, **Social Science appears as an Author discipline in only 14 papers, yet appears as a Method in 38 and as an Objective in 40** — indicating that a large share of TE papers attempt to address social-scientific perspectives and methods using engineering researchers alone, without social scientists as co-authors.
- DSI correlates positively with TE-Index (the existing core composite): papers with DSI≈1 average a TE-Index of 2.51, while papers with DSI≈2 average 3.17 — confirming that higher disciplinary span aligns with stronger "TE-ness" as measured by the original G/C/I framework. This cross-validation, from two independently constructed metrics, strengthens confidence that both are capturing a real underlying phenomenon.
- The highest DSI value (2.67) is shared by C2-025 ("Towards a Transdisciplinary Approach to Systemic Risk Detection") and J-017 ("Editorial: Transdisciplinary engineering for sustainability decisions"), both of which span multiple disciplines on all three of the Author/Method/Objective axes.

## 7. Limitations and Caveats

- Collection was limited to what is accessible via web search (IOS Press ebooks / publicly available information via Google Scholar). This is not an exhaustive systematic review but a trend analysis based on a medium-sized sample (122 papers).
- Paywalled papers (19 of the 20 journal articles) were evaluated from abstract only, which may be less accurate than an evaluation based on full-text review.
- Scoring was performed by four evaluators (LLM agents) working on separate batches. While the rubric was shared, no rigorous inter-rater calibration (agreement-rate verification) was performed. Borderline judgment calls (the "ambiguous cases" each batch's agent reported) can be reviewed individually in the source evaluation logs.
- The `rationale` field in the underlying dataset remains in Japanese even in this English-language report set, since re-scoring all 122 papers in English was out of scope for this pass.
