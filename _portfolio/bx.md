---
title: "Bidirectional Model Transformations"
excerpt: "This project is concerned with bidirectional model transformations for round-trip engineering"
collection: portfolio
---

Description
-----

Model transformations constitute a key technology for model-driven software engineering. Languages for model transformations rely on different computational paradigms, support batch or incremental, in-place or out-place transformations, etc. Model transformations may also be classified with respect to their direction. A *unidirectional transformation* receives a source model as input and returns a target model. In contrast, a *bidirectional transformation* may be executed in both directions.

In software engineering, a strict forward engineering process requires a chain of unidirectional transformations, which transform requirements eventually into code. In contrast, *roundtrip engineering* calls for bidirectional transformations that propagate changes back and forth. Bidirectional transformations have been studied also in a wide range of other application domains, including e.g. view-update problems in databases or bidirectional data exchange.

Developing bidirectional transformations in a conventional programming language is awkward and error-prone: Both transformation directions have to be programmed explicitly at a low level of abstraction, taking algorithmic details of change propagation into account. Therefore, *domain-specific languages (DSLs)* and *theoretical approaches* tailored towards bidirectional transformations have been developed.

Research on bidirectional transformations has often focused on the development of declarative approaches that guarantee consistent behavior of forward and backward transformations. Consistency has been formalized by a number of *bidirectional transformation laws* of different kinds.

However, these approaches have a major drawback which is shared by all of them: While they guarantee certain bidirectional transformation laws, they lack expressiveness: Certain bidirectional transformation problems cannot be solved at all, or they can be solved only partially, or they can be solved but with a considerably higher specification effort than expected. In previous work, this claim was substantiated by a number of benchmarks and case studies (see publications below).

The results from our case studies motivated us to set up a project dedicated to creating a light-weight framework for assisting developers in programming bidirectional transformations using an imperative programming language: [BXtend](https://tbuchmann.github.io/portfolio/BXtend).

In a later project, we added a declarative language on top of the BXtend framework, to support the declarative specification of model correspondences and automatic code generation for transformation code from this declarative specification: [BXtendDSL](https://tbuchmann.github.io/portfolio/BXtendDSL)

Publications
-----

- [Benchmarx 2.0: A Benchmark for Concurrent Model Synchronisation Approaches](https://tbuchmann.github.io/publication/2024-Anjorin2024)
- [Prompting Bidirectional Model Transformations - The Good, The Bad and The Ugly](https://tbuchmann.github.io/publication/2024-Buchmann2024)
- [Benchmarking bidirectional transformations: theory, implementation, application, and assessment](https://tbuchmann.github.io/publication/2020-AnjorinBWDKEHSZ20)
- [The Families to Persons Case](https://tbuchmann.github.io/publication/2017-AnjorinBW17)
- [Bidirectional Transformations with QVT-R: A Case Study in Round-trip Engineering UML Class Models and Java Source Code](https://tbuchmann.github.io/publication/2016-GreinerBW16)
- [Round-trip Engineering UML Class Models and Java Models: A Real-world Use Case for Bidirectional Transformations with QVT-R](https://tbuchmann.github.io/publication/2016-GreinerB16)
- [Using triple graph grammars to realise incremental round-trip engineering](https://tbuchmann.github.io/publication/2016-BuchmannW16)
- [Towards Incremental Round-Trip Engineering Using Model Transformations](https://tbuchmann.github.io/publication/2013-BuchmannW13)




