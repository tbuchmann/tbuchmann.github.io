---
title: "BXtendDSL: A layered framework for bidirectional model transformations combining a declarative and an imperative language"
author: "Thomas Buchmann and Matthias Bank and Bernhard Westfechtel"
collection: publications
permalink: /publication/2022-BuchmannBW22
excerpt: 'This paper is about '
year: 2022
venue: 'Journal of Systems and Software'
paperurl: ''
---

Published in *Journal of Systems and Software*, 2022

DOI: [10.1016/j.jss.2022.111288](https://doi.org/10.1016/j.jss.2022.111288)

[Download .bib-File](http://tbuchmann.github.io/files/BuchmannBW22.bib)
Abstract
=====

Model-driven software development (MDSD) heavily relies on model transformations. While in a strict forward engineering process unidirectional transformations are used, bidirectional transformations are crucial as soon as roundtrip engineering comes into play. In this paper, we present a hybrid language specifically designed to describe bidirectional model transformations. From a declarative transformation specification code is generated which uses our framework for bidirectional and incremental model transformations. A sophisticated code generation mechanism allows for hooking into the generated transformation code at the imperative level to supply behavior that can not be expressed declaratively. A thorough evaluation demonstrates conciseness, expressiveness, and scalability of our approach.