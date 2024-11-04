---
title: "White-box LLM-supported Low-code Engineering: A Vision and First Insights"
author: "Buchmann, Thomas, Peinl, René, Schwägerl, Felix"
collection: publications
permalink: /publication/2024-Buchmann2024a
excerpt: 'This paper is about '
year: 2024
venue: 'Proceedings of the ACM/IEEE 27th International Conference on Model Driven Engineering Languages and Systems'
paperurl: ''
---

Published in *Proceedings of the ACM/IEEE 27th International Conference on Model Driven Engineering Languages and Systems*, 2024

DOI: [10.1145/3652620.3687803](https://doi.org/10.1145/3652620.3687803)

[Download .bib-File](https://tbuchmann.github.io/files/Buchmann2024a.bib)

Abstract
=====

Low-code development (LCD) platforms promise to empower citizen developers to define core domain models and rules for business applications. However, as domain rules grow complex, LCD platforms may fail to do so effectively. Generative AI, driven by large language models (LLMs), offers source code generation from natural language but suffers from its non-deterministic black-box nature and limited explainability. Therefore, rather than having LLMs generate entire applications from single prompts, we advocate for a white-box approach allowing citizen developers to specify domain models semi-formally, attaching constraints and operations as natural language annotations. These annotations are fed incrementally into an LLM contextualized with the generated application stub. This results in deterministic and better explainable generation of static application components, while offering citizen developers an appropriate level of abstraction. We report on a case study in manufacturing execution systems, where the implementation of the approach provides first insights.