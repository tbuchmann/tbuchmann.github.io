---
title: "FAMILE - Features And Models In Lucid Evoluation"
excerpt: "The FAMILE project is dedicated to the model-driven development of software product lines"
collection: portfolio
---

The FAMILE project is dedicated to the model-driven development of software product lines. The toolchain comprises tools supporting the creation of feature models and feature configurations (capturing the variability within a software product line) and to map those features to arbitrary Ecore based domain models. It provides extensive support for (co-) evolution of feature, mapping and domain models respectively. Furthermore, it comprises mechanisms, which ensure the well-formedness of configured domain models.

The main component of FAMILE is the F2DMM (feature to domain mapping model) editor, which provides advanced mapping concepts. On the one hand, mappings can be defined in a user-friendly way by means of drag-and-drop or by manually entering feature expressions which refer to features defined in the feature model. On the other hand, this editor supports cardinality-based feature modeling by providing adequate mapping techniques such as attribute mappings and/or cardinality constraints.

Although our approach is basically dedicated to negative variability (i.e., artifacts unused in a specific feature configuration are filtered), variability constraints imposed by the meta-model can be mitigated by means of alternative mappings. For example, an alternative name can be specified for a UML class, depending on the respective feature configuration. This way, the advantages of positive variability are adopted to a certain extent.

For consistency purposes, we provide the textual language SDIRL (structural dependency identification and repair language) that allows to define not only dependencies at meta-model level, but also provides the basis for the automatic derivation of repair actions that restore product consistency before derivation. The concept of propagation strategies ensures that mappings are mutually consistent, while the number of necessary feature annotation is reduced significantly.