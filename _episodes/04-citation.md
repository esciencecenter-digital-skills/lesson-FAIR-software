---
title: "Enable citation of the software"
teaching: 0
exercises: 0
questions:
- "Why explicitly enable software citation?"
- "How to make your software citable?"
objectives:
- "Publish software on Zenodo"
- "Create citation.cff file"
keypoints:
- "You can publish software without publishing research results."
---
The [fourth principle](https://fair-software.eu/recommendations/citation) states:
> ## Principle 4
> Enable citation of the software
{: .callout}

## Why make your software citable?
Citation helps software developers be recognized for their work. Additionally, citation is an integral part of scientific accountability and reproducibility, but accurately citing software is inherently more difficult than citing a paper. To an outsider especially, even seemingly trivial things such as identifying who should be recognized as an author can be difficult. It is therefore convenient when software developers themselves provide the information necessary to enable citation.

## Getting started
### Adding a citation file to your code
By adding a machine readable citation file to your code base, you can define how the software should be cited.

The [CodeMeta](https://codemeta.github.io/) standard and the [Citation File Format](https://citation-file-format.github.io/) were specifically designed to enable citation. For either one, you write a plain text file with citation metadata, which you then distribute with your software.

The easiest way to initialize your CITATION.cff files is [with this tool].

### Create a persistent identifier
Software is continiously involving, and ideally when someone uses your software, they cite the exact version of the software they use. To facilitate that, you can make a *persistent identifier* (DOI, URN, ARK, etc) for a snapshot of your software, so that the identifier will continue to resolve to exactly that version for the foreseeable future.

There are several archiving services that help you create such a identifier, either at the push of a button, or automatically, for example each time you make a new release of your software:

- [Zenodo](https://zenodo.org/)
- [FigShare](https://figshare.com/)
- [Software Heritage Archive](https://softwareheritage.org/)

> ## Exercise
>
> Take the GitHub repository that you created in episode 1 (version control).
> Browse to [Zenodo](https://sandbox.zenodo.org/) and archive a snapshot of the repository
>
{: .challenge}

{% include links.md %}
