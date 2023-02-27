---
title: "Incremental Bidirectional Transformations: Evaluating Declarative and Imperative Approaches using the AST2Dag Benchmark"
author: "Matthias Bank and Sebastian Kaske and Thomas Buchmann and Bernhard Westfechtel"
collection: publications
permalink: /publication/2020-BankKBW20
excerpt: 'This paper is about '
year: 2020
venue: 'Proceedings of the 15th International Conference on Evaluation of Novel Approaches to Software Engineering, ENASE 2020, Prague, Czech Republic, May 5-6, 2020'
paperurl: ''
---

Published in *Proceedings of the 15th International Conference on Evaluation of Novel Approaches to Software Engineering, ENASE 2020, Prague, Czech Republic, May 5-6, 2020*, 2020

DOI: [10.5220/0009206602490260](https://doi.org/10.5220/0009206602490260)

[Download .bib-File](http://tbuchmann.github.io/files/BankKBW20.bib)
Abstract
=====

Model transformation are the core of model-driven software engineering. Typically an initial model is refined throughout the development process using model transformations to derive subsequent models until eventually code is generated. In round-trip engineering processes, these model transformations are performed not only in forward, but also in backward direction. To this end, bidirectional transformation languages provide a single transformation definition for both directions. This paper evaluates the transformation languages QVT Relations (QVT-R) which allows to specify incremental bidirectional transformations declaratively at a high level of abstraction and BXtend - a framework for procedural specification of both forward and backward transformation in a single rule set. Both languages have been used to implement the AST2Dag transformation example. The benchmarx framework was used for a quantitative and qualitative evaluation of the obtained results.