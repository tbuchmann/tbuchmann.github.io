---
title: "MOD2-SCM: A model-driven product line for software configuration management systems"
author: "Thomas Buchmann and Alexander Dotor and Bernhard Westfechtel"
collection: publications
permalink: /publication/2013-BuchmannDW13
excerpt: 'This paper is about '
year: 2013
venue: 'Information and Software Technology'
paperurl: ''
---

Published in *Information and Software Technology*, 2013

DOI: [10.1016/j.infsof.2012.07.010](https://doi.org/10.1016/j.infsof.2012.07.010)

[Download .bib-File](http://tbuchmann.github.io/files/BuchmannDW13.bib)
Abstract
=====

Context: Software configuration management (SCM) is the discipline of controlling the evolution of large and complex software systems.  Over the years many different SCM systems sharing similar concepts have been implemented from scratch. Since these concepts usually are hard-wired into the respective program code, reuse is hardly possible.\ Objective: Our objective is to create a model-driven product line for SCM systems. By explicitly describing the different concepts using models, reuse can be performed on the modeling level. Since models are executable, the need for manual programming is eliminated. Furthermore, by providing a library of loosely coupled modules, we intend to support flexible composition of SCM systems.\ Method: We developed a method and a tool set for model-driven software product line engineering which we applied to the SCM domain. For domain analysis, we applied the FORM method, resulting in a layered feature model for SCM systems. Furthermore, we developed an executable object-oriented domain model which was annotated with features from the feature model. A specific SCM system is configured by selecting features from the feature model and elements of the domain model realizing these features. \ Results:  Due to the orthogonality of both feature model and domain model, a very large number of SCM systems may be configured. We tested our approach by creating instances of the product line which mimic wide-spread systems such as CVS, GIT, Mercurial, and Subversion. \ Conclusion: The experiences gained from this project demonstrate the feasibility of our approach to model-driven software product line engineering. Furthermore, our work advances the state of the art in the domain of SCM systems since it support the modular composition of SCM systems at the model rather than the code level.