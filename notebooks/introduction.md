# Introduction

In today's scientific and engineering research, software plays a critical role to collect, process, analyze, and visualize data or simulate complex physical systems [@Storer2017].
Whenever existing software does not meet the specific research needs, adaption or new development is often required.
The researchers (referred to as "Domain Experts" or "DE" in this paper) will either have to tread the unfamiliar water of software engineering, or collaborate with developers who likely possess different knowledge-sets and expectations [@HannayEtAl2009] [@KillcoyneEtAl2009].

The main motivation behind our work is to move research software away from being a disposable tool for a single paper/project, to a sustainable product that can be maintained, reused and adapted for more works in the future.
We argue that software should meet the same rigorous standards, such as peer review and reproducibility, as the research itself.

Our work presents a framework to help developers effectively collaborate with domain experts to produce high-quality, sustainable research software.
It comes in the form of a GitHub repository template, around which we will also discuss our [Proposed Practices](./practices.md).

## Pain Points
Our literature review has identified several prominent pain points in research software development.
Some of these are also corroborated by our own experience as discussed in the [Background](./background.md) section.
- Lack of software engineering knowledge by the domain experts [@HannayEtAl2009] [@PintoEtAl2018].
    -  Particularly lacking the know-how to conduct testing [@HannayEtAl2009]
- Domain experts have limited time to work on the software, and do not think they get enough recognition and feedback for the software [@PintoEtAl2018]. Which could be the underlying reason for:
    - Poor documentation [@PintoEtAl2018]
    - Not considering long-term maintainability important [@HannayEtAl2009].
- Feature creep and hard to nail down requirements at the beginning of the project due to the ever-changing nature of research [@PintoEtAl2018] [@SegalEtAl2008] [@KillcoyneEtAl2009].
- Developers having a hard time understanding the domain knowledge and research needs, especially at the beginning of the project [@SegalEtAl2008].
- Special considerations needed for less tech-savvy users to use the software [@WieseEtAl2020] and the developers can become frustrated when they are stuck providing IT support [@KillcoyneEtAl2009].

```{bibliography}
```