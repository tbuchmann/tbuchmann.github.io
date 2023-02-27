---
title: "BXtendDSL: A layered framework for bidirectional model transformations combining a declarative and an imperative language (Summary)"
author: "Thomas Buchmann, Matthias Bank, Bernhard Westfechtel"
collection: publications
permalink: /publication/2023-BuchmannBW23a
excerpt: 'This paper is about '
year: 2023
venue: 'Software Engineering 2023, Fachtagung des GI-Fachbereichs Softwaretechnik, 20.-24. Februar 2023, Paderborn'
paperurl: ''
---

Published in *Software Engineering 2023, Fachtagung des GI-Fachbereichs Softwaretechnik, 20.-24. Februar 2023, Paderborn*, 2023

Download: [Paper](https://dl.gi.de/20.500.12116/40072)

[Download .bib-File](https://tbuchmann.github.io/files/BuchmannBW23a.bib)

Abstract
=====

This summary is based on an article which appeared in 2022 in The Journal of Systems and Software. Bidirectional transformations have been studied in a wide range of application domains. In model-driven software engineering, they are required for roundtrip engineering processes. Programming bidirectional transformations in a conventional programming language is both laborious and error-prone: Both transformation directions have to be programmed separately, and consistency of forward and backward transformations has to be checked by testing. In response to these problems, a wide variety of bx approaches (functional, relational, or grammar-based) have been developed in research. However, empirical evaluations demonstrate limitations of bx approaches with respect to expressiveness, conciseness, and scalability. These observations motivated the development of BXtendDSL, a framework for engineering bidirectional model transformations. BXtendDSL combines domain-specific languages (DSL) for bidirectional model transformations that are located at different levels of abstractions. A declarative language serves to specify a bidirectional transformation concisely. Round-trip properties are guaranteed as long as the transformation specification conforms to well-behavedness conditions. Intentionally, the declarative language is computationally incomplete, i.e., it is usually not possible to completely specify a bidirectional transformation at the declarative level. Therefore, the declarative language provides extension points for adding imperative code, which is written in an internal DSL.