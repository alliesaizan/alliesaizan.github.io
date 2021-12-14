---
layout: post
title:  Mitigating Dataset Harms Requires Stewardship
date:   2021-12-14 00:00:00
categories: ai-ethics research-review
---

# Mitigating Dataset Harms Requires Stewardship: Lessons from 1000 Papers

**Advocating for a distributed approach to dataset harms mitigation**

Publisher: Kenny Peng, Arunesh Mathur, and Arvind Narayanan. “Mitigating Dataset Harms Requires Stewardship: Lessons from 1000 Papers.” 35th Conference on Neural Information Processing Systems (NeurIPS 2021) Track on Datasets and Benchmarks (2021).

## Summary
The author’s approach is to evaluate the life cycles of three datasets that have recently faced ethical scrutiny: Labeled Faces in the Wild (LFW), MS-Celeb-1M, and
DukeMTMC. These datasets are used for face/person recognition tasks. After analyzing nearly 1,000 papers that cite using one or more of these datasets, the authors made the following findings:
1. Dataset retraction has a limited effect on mitigating harms
2. Licenses can be ineffective at restraining production use of datasets
3. Social and technological change can change the ethical concerns associated with a dataset
4. Current dataset management and citation practices have shortcomings that means they are sometimes ineffective at ensuring ethical use.

Dataset retractions work on limiting the use of datasets by both making it unavailable and setting normative expectations around use. However, in the case of the datasets the author studied, formal retraction did not make much of a difference because the dataset was also available in other, informal places. Another way others can learn about retracted datasets is through the citation of retracted papers, which the authors note is a problem in the machine learning field. Derivatives of datasets, which are used for purposes outside the intentions of the dataset creators, can also raise concerns. Derivatives can include updates with relabeled features, models trained on those datasets, and other post-processing modifications meant to improve performance on the original task.

The authors also found that non-commercial dataset licenses, like those used by the datasets analyzed, are sometimes ignored in practice. The licenses either do not prohibit distribution or are no longer available. The authors note that ethical norms have shifted between when many popular datasets were first published and the current day. Most egregiously, in the case of ImageNet, researchers discovered misogynistic and racist slurs in image labels nearly a decade after the dataset’s release, prompting the dataset maintainers to remove those images. Finally, the authors find that none of the datasets they studied were centrally managed or have stable identifiers for tracking purposes.

The authors put forward a number of recommendations for dataset creators to mitigate potential harms:
1. Make licenses and dataset documentation clear and easily accessible
2. Maintain active stewardship over datasets to address ethical concerns as they arise
3. Conferences should take an active role in encouraging responsible dataset use, advocating for dataset management and citation practices, and incentivizing responsible dataset creation through new publishing avenues


## My Takeaways

My main takeaway is that I am not surprised the authors found such glaring issues with popular benchmarking datasets. They note at one point that “creating datasets is already an undervalued activity”, so why would dataset creators feel incentivized to be better stewards of their data? I recently wrote a blog post about the significant fairness issues associated with another non-image recognition benchmarking dataset (Boston Housing), and many of the same problems abounded (included unclear documentation, no licenses, shifting ethical norms, etc). That dataset was prolific in machine learning benchmarking, and often in applications that stray far from the original intended use of the data. I think ultimately this phenomenon is a consequence of the academic publish-or-perish cycle. This cycle has created an environment where cutting edge machine learning algorithms (or slight improvements on them) are needed to pass publisher muster, and simultaneously there are no official datasets allocated for machine learning testing. So popular datasets become the norm for benchmarking with little attention paid to the potential impacts of using a given algorithm on those data. 

I think the authors’ recommendations are good first steps, and chief among them should be restructuring the publishing incentive structure (as noted by their recommendations around conferences). If dataset evaluation research is rewarded, people will do it! I consider the second-most important recommendation to be the establishment of a centralized data management structure/review body. As the authors note, Institutional Review Boards may be insufficient for this new class of ethical concerns, and, not to be too cliche, modern problems require modern solutions. I think back to an article I read some time ago about dataset archives as a possible centralized data management option - it’s interesting that the authors did not review that suggestion in their analysis. Overall, I have been seeing more field surveys out of arXiv, and I think that’s good! More holistic reviews of datasets in particular will only further the development and adoption of new ethical behavior norms.
