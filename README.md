# CoNLL-U_Manzoni

This repository contains the output of an ongoing work aimed at creating a new dataset of the Alessandro Manzoni's novel "I Promessi Sposi" (The Betrothed, 1840) annotated with morpho-grammatical information.

Currently, the repository gives access to:
- chapters I, VIII and XXIII annotated with lemmas, part-of-speech tags and features following the Italian guidelines of [Universal Dependencies](https://universaldependencies.org/). The annotation was carried out by Flavio Massimiliano Cecchini under the supervision of Rachele Sprugnoli. The dataset is split into training, development, and test sets with an 80/10/10 ratio, with the division based on syntactic words as units, in accordance with the guidelines of the UD framework. The number of syntactic words was taken proportionally equally from the three chapters. Following this approach, the partitions are the following:
  - training set: 615 sentences, 20,806 syntactic words;
  - development set: 101 sentences, 2,670 syntactic words;
  - test set: 75 sentences, 2,457 syntactic words.

