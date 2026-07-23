# jeanpaul-topics: Topic modeling the correspondence of Jean Paul’s surroundings

## Context

This repository contains data and results that were obtained from topic modeling the letters from Jean Paul's surroundings, i. e. of family, friends and colleagues of the German author. It complements the following article available in open access, which in turn goes back to a presentation at the University of Rostock in 2022: 

* Article: Ulrike Henny-Krahmer and Frederike Neuber. 2026. Topic Modeling in Digital Scholarly Editions, in: Machine Learning and Data Mining for Digital Scholarly Editions (ed. by Ulrike Henny-Krahmer, Martina Scholger, Bernhard Geiger, Fabian Kaßner and Marc Lemke). Schriften des Instituts für Dokumentologie und Editorik 18. Norderstedt: Books on Demand. [[to be published in 2026](https://www.i-d-e.de/publikationen/schriften/)] 

* Conference Paper: Ulrike Henny-Krahmer and Frederike Neuber. 2022. Topic Modeling in Digital Scholarly Editions. Machine Learning and Data Mining for Digital Scholarly Editions, Universität Rostock, 10. Juni 2022. [[program](https://www.i-d-e.de/aktivitaeten/veranstaltungen/machine-learning-and-data-mining-for-digital-scholarly-editions/)]

The letters from Jean Paul's surroundings are published as [digital edition](jeanpaul-edition.de/) at the Berlin-Brandenburg Academy of Sciences and Humanities since 2019. The TEI datasets of the edition which are availiable on [GitHub](https://github.com/telota/jean_paul_briefe) and [Zenodo (v.5.0)](https://zenodo.org/record/6322839) were preprocessed and analyzed in different ways. The tools used include [CAB](https://kaskade.dwds.de/~moocow/software/DTA-CAB/), [Mallet](https://mimno.github.io/Mallet/index), and [TMW](https://github.com/cligs/tmw). For more detailed information on how we prepared, preprocessed and analyzed the data as well as how we interpreted the results, please consult the article mentioned above. 

Since 2025, this work has been continued within the framework of the DFG-funded project [_Jean Paul – Sämtliche Briefe digital: Einbindung der IV. Abteilung – Briefe an Jean Paul_](https://gepris.dfg.de/project/537078797), led by Markus Bernauer and Frederike Neuber. Within this project, the proof of concept presented here is being transferred into editorial practice and further developed through the implementation of a topic browser for the digital edition.

## Content

* **data/preprocessing**: datasets with various preprocessing parameters applied (see topic-modeling-overview.csv); all data sets are plain text version of the TEI source files including normalization of historical orthographic variants to "canonical" modern forms
  * **stopwords.txt**: list of stopwords (will be added soon)
* **data/tm**: results of the topic modeling; for the correlation of input and output data see topic-modeling-overview.csv
* **topic-models-overview.csv**: overview of applied topic models
* **letters-context-metadata.csv**: table with metadata to the single letters such as sender, receiver and date


## Citation and license

Neuber, Frederike and Ulrike Henny-Krahmer. 2026. “Topic modeling the correspondence of Jean Paul’s surroundings” (v.1.0). Zenodo. https://doi.org/#####, GitHub: https://github.com/FrederikeNeuber/jeanpaul-topics.

The content of the repository is published unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
