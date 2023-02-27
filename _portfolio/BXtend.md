---
title: "BXtend"
excerpt: "A light-weight framework for programming bidirectional transformations"
collection: portfolio
---

Description
-----

Model transformations constitute the core essence of model-driven software development (MDSD) – a software engineering discipline, which gained more and more attention during the last decade. While technology for unidirectional batch transformations seems to be fairly well developed, tool support for bidirectional and incremental transformations is still restricted. Results obtained with case studies carried out with popular bidirectional approaches motivated us to set up our own light-weight framework for bidirectional and incremental model transformations based on the Xtend programming language. Our approach provides several advantages, as it reduces the cognitive complexity for transformation developers, and allows for a greater flexibility in transformation specifications by providing procedural language constructs. In addition, it provides a higher expressive power and allows for compact specifications at the same time.
BXtend ist ein Projekt im Bereich bidirektionaler und inkrementeller Modell-zu-Modell Transformationen. Umfangreiche Fallstudien auf diesem Gebiet haben zu der Erkenntnis geführt, dass existierende Ansätze für in der Praxis auftretende Transformationsprobleme zu starr und unflexibel sind, da sie auf einem vorgegebenen Paradigma aufsetzen und dieses strikt verfolgen (z. B. regel-basierte Sprachen, constraint-basierte Sprachen). Oftmals lassen sich die Transformationsregeln aber rein deklarativ nur sehr schwer und unter großen Mühen ausdrücken. Hier wären imperative Sprachkonstrukte hilfreich, vor allem bei Regeln, deren rechte Seiten Variabilität enthalten. BXtend ist ein Lösungsansatz hierfür: Das Framework bietet ein generisches Korrespondenzmodell mit zugehöriger Infrastruktur. Es werden Regelklassen generiert, in die der Transformationsentwickler lediglich die Transformationsvorschriften für Vorwärts- und Rückwärtsrichtung mit Hilfe der Programmiersprache Xtend eintragen muss. Im Vergleich mit herkömmlichen Ansätzen zeigt sich auch der Mehrwert von BXtend

Publications
-----

- [Incremental Bidirectional Transformations: Evaluating Declarative and Imperative Approaches using the AST2Dag Benchmark](https://tbuchmann.github.io/publication/2020-BankKBW20)
- [Incremental Bidirectional Transformations: Comparing Declarative and Procedural Approaches Using the Families to Persons Benchmark](https://tbuchmann.github.io/publication/2018-WestfechtelB18)
- [BXtend - A Framework for (Bidirectional) Incremental Model Transformations](https://tbuchmann.github.io/publication/2018-Buchmann18)
- [Bidirectional Model Transformations Using a Handcrafted Triple Graph Transformation System](https://tbuchmann.github.io/publication/2016-BuchmannG16a)
- [Handcrafting a Triple Graph Transformation System to Realize Round-trip Engineering Between UML Class Models and Java Source Code](https://tbuchmann.github.io/publication/2016-BuchmannG16)

Eclipse Update Site
-----

[BXtend Update Site](https://tbuchmann.github.io/bxtendUpdateSite/)

