---
title: "BXtendDSL"
excerpt: "BXtendDSL: A layered framework for bidirectional model transformations combining a declarative and an imperative language"
collection: portfolio
---

Description
-----

Our research in the context of bidirectional model transformations follows a more pragmatic approach. Our primary 
focus lies on *expressiveness*, *conciseness*, and *scalability*. To this end, we combine a *declarative DSL* with 
an *imperative DSL*, the latter of which allows to specify all parts of the transformation that may not be addressed 
by the declarative DSL.  

**BXtendDSL** is a framework for the definition and execution of bidirectional incremental model transformations. 
The framework is based on EMF and has been implemented in [Xtend](https://www.eclipse.org/xtend/), an expressive 
dialect of the programming language Java. The models to be transformed are assumed to be instances of metamodels, 
which in turn are defined with the help of Ecore, the metametamodel provided by EMF. A transformation is specified 
in a small and light-weight external DSL called \emph{BXtendDSL Declarative}, which essentially serves to define 
correspondences between model elements with the help of transformation rules. From a declarative specification, 
code is generated against the libraries of the BXtendDSL framework. The application programming interfaces of 
these libraries constitute an internal, imperative DSL called \emph{BXtendDSL Imperative}. The generated code 
is extended with handwritten code that is written in the internal DSL. In this way, the transformation developer 
may take care of operational details that go beyond the capabilities of the declarative language. Altogether, 
BXtendDSL allows to write concise transformation definitions and at the same time provides the expressiveness 
required for solving a wide range of bidirectional transformation problems. Furthermore, execution of BXtendDSL 
transformations proves scalable to large model sizes.


Publications
-----

- [BXtendDSL: A layered framework for bidirectional model transformations combining a declarative and an imperative language (Summary)](https://tbuchmann.github.io/publication/2023-BuchmannBW23a)
- [BXtendDSL at Work: Combining Declarative and Imperative Programming of Bidirectional Model Transformations](https://tbuchmann.github.io/publication/2023-BuchmannBW23)
- [Engineering Bidirectional Model Transformations (Short Paper)](https://tbuchmann.github.io/publication/2022-BuchmannW22)
- [BXtendDSL: A layered framework for bidirectional model transformations combining a declarative and an imperative language](https://tbuchmann.github.io/publication/2022-BuchmannBW22)
- [Combining a Declarative Language and an Imperative Language for Bidirectional Incremental Model Transformations](https://tbuchmann.github.io/publication/2021-BankBW21)

Eclipse Update Site
-----

[BXtendDSL Update Site](https://tbuchmann.github.io/bxtendDSLUpdateSite/)

