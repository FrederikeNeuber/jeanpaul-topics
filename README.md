# jeanpaul-topics: Topic modeling the correspondence of Jean Paul’s surroundings

## Context

This repository contains the data and results that were obtained from Topic Modeling the letters from Jean Paul's surroundings, i. e. of the family, friends and colleagues of the German author. It complements the following article available in open access, which in turn goes back to a presentation at the University of Rostock in 2022: 

* Article: Ulrike Henny-Krahmer and Frederike Neuber. 2023. Topic Modeling in Digital Scholarly Editions, in: Machine Learning and Data Mining for Digital Scholarly Editions (ed. by Geiger, Bernhard, Ulrike Henny-Krahmer, Fabian Kaßner, Marc Lemke und Martina Scholger). Schriften des Instituts für Dokumentologie und Editorik 18. Norderstedt: Books on Demand. [[published in 2023](https://www.i-d-e.de/publikationen/schriften/)] 

* Conference Paper: Ulrike Henny-Krahmer and Frederike Neuber. 2022. Topic Modeling in Digital Scholarly Editions. Machine Learning and Data Mining for Digital Scholarly Editions, Universität Rostock, 10. Juni 2022. [[program](https://www.i-d-e.de/aktivitaeten/veranstaltungen/machine-learning-and-data-mining-for-digital-scholarly-editions/)]

The Letters from Jean Paul's surroundings are published as [digital edition](jeanpaul-edition.de/) at the Berlin-Brandenburg Academy of Sciences and Humanities since 2019. The TEI datasets of the edition which are availiable on [GitHub](https://github.com/telota/jean_paul_briefe) and [Zenodo (v.5.0)](https://zenodo.org/record/6322839) were preprocessed and analyzed in different ways. The tools used include [CAB](https://kaskade.dwds.de/~moocow/software/DTA-CAB/), [Mallett](https://mimno.github.io/Mallet/index), and [TMW](https://github.com/cligs/tmw). For more detailed information on the preprocessing and analysis of the data, please consult the article mentioned above. 

## Content

* **data** (all data sets are plain text version of the TEI source files including normalization of historical orthographic variants to "canonical" modern forms)
  * **letters-context** / **letters_lemmata_N** / **letters_lemmata_NNE** / **letters_lemmata_NNEVA** / **letters_lemmata_NVA**: datasets with various preprocessing parameters (see topic-modeling-overview.csv)
  * **tm**: results of the topic modeling, generated with the TMW tool. For the correlation of output data to results, see topic-modeling-overview.csv
  * **topic-modeling-overview.csv**
* **letters-context-metadata.csv**


# stopwordliste fehlt
