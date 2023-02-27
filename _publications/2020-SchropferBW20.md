---
title: "A Generic Projectional Editor for EMF Models"
author: "Johannes Schröpfer, Thomas Buchmann, Bernhard Westfechtel"
collection: publications
permalink: /publication/2020-SchropferBW20
excerpt: 'This paper is about '
year: 2020
venue: 'Proceedings of the 8th International Conference on Model-Driven Engineering and Software Development, MODELSWARD 2020, Valletta, Malta, February 25-27, 2020'
paperurl: ''
---

Published in *Proceedings of the 8th International Conference on Model-Driven Engineering and Software Development, MODELSWARD 2020, Valletta, Malta, February 25-27, 2020*, 2020

DOI: [10.5220/0008971003810392](https://doi.org/10.5220/0008971003810392)

[Download .bib-File](https://tbuchmann.github.io/files/SchropferBW20.bib)

Abstract
=====

The Eclipse Modeling Framework (EMF) constitutes a popular ecosystem for model-driven development. In the technological space of EMF, a wide variety of model-based tools have been developed, including tools for transforming and editing models. Model editors may display models in different representations such as diagrams, trees, or tables. Due to the increasing popularity of human-readable textual syntax, there is a growing demand for textual model editors. In EMF, this demand is currently satisfied by syntax-based editors which persist models as text files. In contrast, we propose a projectional editor that persists models natively as EMF models; the textual representation constitutes a projection of the underlying EMF model. Projectional editing does not only exclude syntactic errors; in addition, maintaining the underlying model persistently facilitates tool integration. The projectional editor is generic; it may be instantiated for different modeling languages by declarative definitions of their concrete syntax. So far, model editors for subsets of Java and ALF (Action Language for Foundational UML) have been built to demonstrate the feasibility of the generic approach.