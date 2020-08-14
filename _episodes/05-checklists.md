---
title: "Use a software quality checklist"
teaching: 0
exercises: 0
questions:
- "What is a software checklist?"
- "Why is a software checklist important?"
- "What is a Software Management plan?"
- "What is a Software Sustainability plan?"
objectives:
- "Understand a software checklist"
- "Choose a relevant software checklist"
keypoints:
- "Checklists help you write good quality software."
---

> ## [Recommendation 5](https://fair-software.eu/recommendations/checklist)
>
> Use a software quality checklist
{: .callout}
![recommendation5]({{ page.root }}/fig/recommendation5.png)

## Why software checklists are important

Checklists help you write good quality software. What exactly
**good quality** means depends on the specific application of the software,
but typically covers things like documenting the source code,
using continuous testing, and following standardized code patterns.

## Using a checklist

There are many checklists available. We find that the most useful checklist are those that:

- allow for a granular evaluation of a software package, as opposed to just pass or fail.
- explain the rationale behind each item in the checklist.
- explain how to get started with implementing each item in the checklist.

We recommend that you include the checklist as part of the ``README``, for example as
a badge or by including the checklist as a
[MarkDown table](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables).
The point is decidedly not to show perfect compliance, but rather to be transparent about
the state of the code while providing the necessary guidance on which aspects could be improved.

Here is a list of some candidate checklists:

- [Core Infrastructures Initiative](https://bestpractices.coreinfrastructure.org/en) (online, interactive).
- Deutsches Zentrum für Luft- und Raumfahrt
[Class 1](https://rse.dlr.de/download/checklist_applicationclass_1-markdown_v1.0.md),
[Class 2](https://rse.dlr.de/download/checklist_applicationclass_2-markdown_v1.0.md),
[Class 3](https://rse.dlr.de/download/checklist_applicationclass_3-markdown_v1.0.md) (MarkDown).
- Software Sustainability Institute’s software evaluation checklist ([Google form](https://docs.google.com/forms/d/e/1FAIpQLSf0ccsVdN-nXJCHLluJ-hANZlp8rDKgprJa0oTYiLZSDxh3DA/viewform)).
- CLARIAH checklist ([PDF page 38-42](https://github.com/CLARIAH/software-quality-guidelines/blob/v1.0/softwareguidelines.pdf)).
- EURISE ([MarkDown](https://github.com/eurise-network/technical-reference/blob/v0.1/quality/software-checklist.rst)).

> ## Choose a checklist
>
> Have a look at the checklists above and pick two checklists.
>
> - What are the differences?
> - What do you think about the questions on the checklist?
> - Which checklist seems most relevant for your code?
>
{: .discussion}

{% include links.md %}
