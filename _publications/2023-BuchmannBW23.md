---
title: "BXtendDSL at Work: Combining Declarative and Imperative Programming of Bidirectional Model Transformations"
author: "Thomas Buchmann, Matthias Bank, Bernhard Westfechtel"
collection: publications
permalink: /publication/2023-BuchmannBW23
excerpt: 'This paper is about '
year: 2023
venue: 'SN Computer Science'
paperurl: ''
---

Published in *SN Computer Science*, 2023

DOI: [10.1007/s42979-022-01448-8](https://doi.org/10.1007/s42979-022-01448-8)

[Download .bib-File](https://tbuchmann.github.io/files/BuchmannBW23.bib)

Abstract
=====

Model transformations are a major driving force behind model-driven software development (MDSD), when typically an initial model is refined throughout the development process over several steps until eventually code is generated. Strict forward engineering processes require uni-directional model transformations, where an initial requirements model is refined through various model transformation steps. Roundtrip engineering on the other hand calls for bidirectional and incremental model transformations instead, where changes may be propagated back and forth while retaining manual modifications to the models involved. In this paper, we present BXtendDSL, a framework for bidirectional incremental model transformations. BXtendDSL combines two languages: a light-weight declarative language for defining correspondences between model elements, and an imperative language that allows to implement behavior that cannot be specified in the declarative language. We demonstrate our approach by a case study. We also include an evaluation of this case study that demonstrates conciseness, expressiveness, and scalability of our hybrid approach.