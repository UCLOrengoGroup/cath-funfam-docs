# FunFams (Functional Families) in CATH-Gene3D

In a nutshell...

 * A **FunFam** is a collection of protein structural domains that share a common function (read more)
 * **FunFams** can be used to predict the location of structural domains and provide clues about putative function in novel protein sequences (read more)
 * This site contains information, scripts and tutorials on how **FunFams** can be used to annotate your own protein sequences (see below)

## How do I scan my own protein sequences?

There are few different options depending on:

 1. how many sequences do you want to scan? (e.g. 1, 100, 100000+?)
 1. how comfortable you are working in a technical environment

### Manually scan individual sequences

The most simple way of predicting the location of FunFams on your protein sequence is to use the CATH web pages. Simply copy and paste your protein sequence into the sequence search and follow the instructions.

 * Difficulty: easy
 * Technical requirements: none
 * Expected time: < 1 minute

### Scan many sequences (e.g. 100s)

The FunFHMMER server provides a public API that allows users to submit their own sequence scans
through their own scripts. Note, queries are submitted to a queueing system and are subject to fair
use policy.

 * Difficulty: medium
 * Technical requirements: simple scripting
 * Expected time: < 10 mins

### Scan entire genomes (e.g. 10000s) (medium)

The FunFHMMER protocol can be used to scan your own sequence on your own server. This is the recommended
approach if you are trying to scan many thousands of protein sequences (e.g. entire genomes).

 * Difficulty: medium
 * Technical requirements: Linux terminal
 * Expected time: < 1 hour

## Help

The wiki area contains lots of information, please have a good look through that documentation. If you have a question that is not already answered then please help us improve the documentation by letting us know (by raising an issue or emailing us).

## Relevant Papers

1. [Functional classification of CATH superfamilies: a domain-based approach for protein function annotation](https://doi.org/10.1093/bioinformatics/btv398)
2. [CATH FunFHMMer web server: protein functional annotations using functional family assignments](https://doi.org/10.1093/nar/gkv488)
