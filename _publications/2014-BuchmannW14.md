---
title: "Mapping feature models onto domain models: ensuring consistency of configured domain models"
author: "Thomas Buchmann and Bernhard Westfechtel"
collection: publications
permalink: /publication/2014-BuchmannW14
excerpt: 'This paper is about '
year: 2014
venue: 'Software and Systems Modeling (SoSym)'
paperurl: ''
---

Published in *Software and Systems Modeling (SoSym)*, 2014

DOI: [10.1007/s10270-012-0305-5](https://doi.org/10.1007/s10270-012-0305-5)

Abstract
=====

We present an approach to model-driven software product line engineering which is based on feature models and domain models. A feature model describes both common and varying properties of the instances of a software product line. The domain model is composed of a structural model (package and class diagrams) and a behavioral model (story diagrams). Features are mapped onto the domain model by annotating elements of the domain model with features. An element of a domain model is specific to the features included in its feature annotation. An instance of the product line is defined by a set of selected features (a feature configuration). A configuration of the domain model is built by excluding all elements whose feature set is not included in the feature configuration. To ensure consistency of the configured domain model, we define constraints on the annotations of inter-dependent domain model elements. These constraints guarantee that a model element may be selected only when the model elements are also included on which it depends. Violations of dependency constraints may be removed automatically with the help of an error repair tool which propagates features to dependent model elements.