# CoNLL-U_Manzoni

This repository contains the output of an ongoing work aimed at creating a new dataset of the Alessandro Manzoni's novel "I Promessi Sposi" (The Betrothed, 1840) annotated with morpho-grammatical information.

Currently, the repository gives access to:
- Folder **UD_Italian-Manzoni**: chapters I, VIII and XXIII annotated with lemmas, part-of-speech tags and features following the Italian guidelines of [Universal Dependencies](https://universaldependencies.org/). The annotation was carried out by Flavio Massimiliano Cecchini under the supervision of Rachele Sprugnoli. The dataset is split into training, development, and test sets with an 80/10/10 ratio, with the division based on syntactic words as units, in accordance with the guidelines of the UD framework. The number of syntactic words was taken proportionally equally from the three chapters. Following this approach, the partitions are the following:
  - training set: 615 sentences, 20,806 syntactic words;
  - development set: 101 sentences, 2,670 syntactic words;
  - test set: 75 sentences, 2,457 syntactic words.
- Folder **CoNLL-U_Plus**: chapters I, VIII and XXII of _Ventisettana_ and _Quarantana_ annotated with an additional column that contains a different lemmatization following a conservative approach. For example, an altered form is lemmatized with its non-altered lemma in the third field (*coltellacci* --> *coltello*) and with its altered lemma in the eleventh field (*coltellacci* --> *coltello*). Similarly, an archaic form is lemmatize with its normalized lemma in the third field (*edifizi* --> *edificio*) and with its archaic lemma in the eleventh field (*edifizi* --> *edifizio*).
- Annotation **guidelines**.
- **variant_apoc_crf_model.joblib**: CFR sequence tagger developed to identify apocopated forms in the novel.
