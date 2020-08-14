---
title: "Enable citation of the software"
teaching: 0
exercises: 0
questions:
- "Why explicitly enable software citation?"
- "How to make a software citable?"
objectives:
- "Create a citation.cff file"
- "Publish software on Zenodo"
keypoints:
- "We can publish software without publishing research results."
---

> ## [Recommendation 4](https://fair-software.eu/recommendations/citation)
>
> Enable citation of the software
{: .callout}
![recommendation4]({{ page.root }}/fig/recommendation4.png)

## Why making a software citable is important

Citation helps software developers be recognized for their work.
Additionally, a citation is an integral part of scientific accountability and reproducibility.

However, citing software is inherently more difficult than citing a paper.
To an outsider especially, even seemingly trivial things such as identifying
who should be recognized as an author can be difficult. It is therefore convenient
when software developers themselves provide the information necessary to cite.

## A citation file

By adding a machine-readable citation file ``CITATION.cff`` to your code base,
you can define how the software should be cited.

The [CodeMeta](https://codemeta.github.io/) metadata schema and the
[Citation File Format](https://citation-file-format.github.io/) are specifically
designed to enable citation. For either one, you write a plain text file with
citation metadata, which you then distribute with your software.

> ## Initialize your citation file
>
> We can use the tool [cffinit](https://citation-file-format.github.io/cff-initializer-javascript/)
> to initialize the ``CITATION.cff``.
{: .callout}

> ## Publish your code in zenodo
>
> Browse to [Zenodo](https://sandbox.zenodo.org/) and archive a snapshot of
> your repository created in the lesson
> [Use a publicly accessible repository with version control]({{ page.root }}{% link _episodes/01-version-control.md %}).
>
> > ## Solution
> >
> > Follow the instructions
> > on the [GitHub guides page](https://guides.github.com/activities/citable-code/#repository).
> {: .solution}
{: .challenge}

## A persistent identifier

Software is continuously evolving, and ideally when someone uses your software,
they cite the exact version of the software they use. To facilitate that,
you can make a **persistent identifier** (DOI, URN, ARK, etc) for a snapshot of
your software, so that the identifier will continue to resolve to exactly
that version for the foreseeable future.

> ## Archiving services
>
> There are several archiving services that help you create such an identifier,
> either using the push of a button, or automatically, for example each time
> you make a new release of your software:
>
> - [Zenodo](https://zenodo.org/)
> - [FigShare](https://figshare.com/)
> - [Software Heritage Archive](https://softwareheritage.org/)
{: .callout}

> ## Adding a DOI to your repository
>
> Browse to your repository created in the lesson
> [Use a publicly accessible repository with version control]({{ page.root }}{% link _episodes/01-version-control.md %}).
> Add the DOI generated in the previous exercise
> ([Publish your code in zenodo](#publish-your-code-in-zenodo))
> to the ``README.md`` file in your repository.
>
> > ## Solution
> >
> > Follow the instructions
> > on the [GitHub guides page](https://guides.github.com/activities/citable-code/#finishing).
> {: .solution}
{: .challenge}

{% include links.md %}
