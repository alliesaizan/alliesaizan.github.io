---
layout: post
title:  From What to How
date:   2020-12-28 00:00:00
categories: ai-ethics research-review
---

# From What to How: An Initial Review of Publicly Available AI Ethics Tools, Methods and Research to Translate Principles into Practices

**A 2019 review of AI ethics tools and methods**

Publisher: Morley, J., Floridi, L., Kinsey, L. et al. From What to How: An Initial Review of Publicly Available AI Ethics Tools, Methods and Research to Translate Principles into Practices. Sci Eng Ethics 26, 2141–2168 (2020). https://doi.org/10.1007/s11948-019-00165-5

## Summary
The authors begin by asserting that code, and particularly code that facilitates machine learning, is both our greatest threat and our greatest promise. Citing a review of AI ethics principles, the argues note that ethically-aligned machine learning is typically defined as having the following properties: beneficence, non-maleficence, autonomy, justice, and explainability. This consensus on the definition of AI creates a foundation upon which technologists can "communicate expectations and evaluate deliverables". However, very few of these guidelines set technical expectations. The authors note that the next step in defining ethical machine learning guidelines is to translate the **what** outlined in the principles to **how**.

To bridge this gap, the authors define a typology that maps the foundational principles above to each stage of the machine learning algorithm design process. They identified 425 papers which ostensibly answer the question of "how to develop an ethical algorithmic system". The typology developed is intended to show machine learning developers what ethical ML tools are already available. The authors find that not all principles have tools for each stage of the algorithm design process. Explainability, which is more easily implemented than the other principles, is overrepresented in the toolset. Unlike beneficence, non-maleficence, autonomy, and justice, explainability is not a moral principle, so tools that enable transparency like LIME and SHAP are insufficient alone. Instead of ensuring explainability at the back end, the authors propose that transparency is prioritized at the beginning of the design process.

The authors also note that few of the tools provide ways to assess the impact of an ML algorithm on an individual in a dataset. The <em>deployment</em> column of the typology is blank, highlighting the need for "pro- ethically designed human-computer interaction (at an individual level) or networks of ML systems (at a group level)". The authors assert that not enough research has been done in the field of translating predictions to decisions in the context of algorithmic systems. Finally, the tools in the typology are generally not usable, as they are either not easily applicable in practice or too complex for a wide set of users, as in the case of open source code libraries.

ML researchers from all disciplines will need to accept that: (1) AI is built on assumptions; (2) human behaviour is complex; (3) algorithms can have unfair consequences; (4) algorithmic predictions can be hard to interpret (Vaughan & Wallach, 2016); (5) trade-offs are usually inevitable; and (6) positive, ethical features are open to progressive increase. Ethical principles should not be applied once or not, but should be regularly re-applied or applied differently, depending on changing needs throughout the ML development process.

## My Takeaways

I don’t think this article provided me with anything I didn’t already know. Through my (albeit limited) review of AI ethics principles, it’s evident that a wide gap exists between framework and technical practice. The guidelines I tend to see fall on one of two extremes: high-level principles that outline the values algorithmic systems should embed, or low-level technical implementations of those values (such as transparency as in SHAP, or fairness as in fairlearn) without explicating a context for prioritizing those results within organizational and/or project goals. I appreciated that the authors' literature review and typology reflected this sentiment, and that they provided a thorough synthesis of the existing ML ethics conversation.

I think one of my most important takeaways is at the end of the article, where the authors describe what topics the ML research community prioritize. They put the most important topic at the bottom of the list: **the evaluation and creation of pro-ethical business models and incentive structures that balance the costs and rewards of investing in ethical AI across society**. I firmly believe that none of the other topics can be on the table, not a commitment to reproducibility and openness, not evaluation of currently implemented tools, not the development of a common language, etc. until ML developers have organizational buy-in. Organizational buy-in only occurs when ethical priorities align with financial priorities, and in some cases the only way to facilitate that alignment may be a fundamental restructuring of financial priorities.

The authors note that they eventually hope to create a searchable database with AI ethics tools and methods, and I think that would be particularly helpful to practitioners. The authors note an urgent need to progress research in the AI for Social Good field, and having a comprehensive database of tools (with a common/standardized language to discuss concepts) would be a good first step to making that research feasible.

## Notable Quotes



## Citations

