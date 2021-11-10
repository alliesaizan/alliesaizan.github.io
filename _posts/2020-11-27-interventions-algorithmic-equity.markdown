---
layout: post
title:  Interventions for Algorithmic Equity
date:   2020-11-27 00:00:00
categories: ai-ethics research-review
---

# Toward Situated Interventions for Algorithmic Equity: Lessons from the Field

**Technical interventions to reduce algorithmic bias are incomplete without community-based interventions that focus on the socio-political context of technical systems.**

Publisher: Katell, M. et al. Toward Situated Interventions for Algorithmic Equity: Lessons from the Field. FAT '20, January 27–30, 2020, Barcelona, Spain.


## Summary

I haven’t read much on non-technical means of assuring algorithmic fairness, so on first blush I think this will be an interesting contribution to the field. This work is intended to fill the gap in algorithmic bias research surrounding social-context-based means of reducing harms from algorithmic systems. The authors use the framework of situated knowledge to study technical systems. Situated knowledge refers to the "product of embodied vantage points, located historically."<sup>1</sup> The authors also incorporate elements of the human-computer interaction field to contextualize their participatory discourse, and draw on their experiences
developing the [Algorithmic Equity Toolkit](https://www.aclu-wa.org/AEKit). The authors document their development of the Algorithmic Equity Toolkit as a response to the lack of safeguards against algorithmic bias in the 2017 Seattle Surveillance Ordinance. Participatory design methods such as contextual inquiry were used to center affected populations in the development of the toolkit. Throughout the process, the authors partnered with community-based civil rights organizations and data science institutes for their input. The toolkit, which was designed to assess the impact of particular technologies in public settings, has three tenets: (1) Determine whether a system is AI, (2) Ask tough questions, (3) Better learn how ML works and when it fails. Stakeholder-provided input facilitated continuous integration / continuous development creation  of the toolkit. Among other takeaways, the authors found that non-technical measures can meaningfully impact
algorithmic accountability. Stakeholders don’t need to have a technical background to assess outcome(s) of and identify alternatives to technical systems. The authors conclude that future automated decision system interventions should consider the framework of situated context.

## My Takeaways

The authors believe that participatory methods that center those most disparately affected by algorithmic systems should be integrated in the practice of data science. And I agree, I think it’s crucial for data scientists to recognize that the tools they build, even seemingly divorced from any social context, can prop up social inequities. On the toolkit itself, tenets (2) and (3) seem duplicative, and tenet (3) might be better listed as "understand how **this particular** ML system works." Another important takeaway is that it’s not enough to identify the risks associated with automated decision systems. Even if the system works as intended without any disparate impacts, it may still produce undesirable results (e.g., facial recognition surveillance systems).

Overall, this research provides a blueprint for the “interpretative data scientist”, that is, a data scientist who is deeply ingrained with community organizations, is attuned to the needs of vulnerable populations and the potentially negative impacts of the technical systems being developed, and is an expert communicator of not just technical topics, but also understanding how those topics are situated within a socio-political context. I am hopeful that these skills increasingly become part of data science training.

## Notable Quotes

1. "A more inclusive data science practice will result in novel conventions of work which attend to fairness, accountability, transparency, and equity as an explicit part of research method and practice– rather than as topic alone."
2. "...such efforts emphasize the importance of equitable processes determinative of equitable outcomes."
3. "...the most meaningful measures towards fairness, accountability, and transparency are not necessarily technical but are instead informed through contextualized understanding about how a given tool or technology is implemented and contested in practice."

## Citations

1. Donna Haraway. 1988. Situated knowledges: The science question in feminism and the privilege of partial perspective. *Feminist studies* 14, 3 (1988), 575–599.