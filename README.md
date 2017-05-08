# FunFams (Functional Families) in CATH-Gene3D

In a nutshell...

 * A **FunFam** is a collection of protein structural domains that share a common function (read more)
 * **FunFams** can be used to predict the location of structural domains and provide clues about putative function in novel protein sequences (read more)
 * This site contains information, scripts and tutorials on how **FunFams** can be used to annotate your own protein sequences (see below)

## How do I find **FunFams** in my own protein sequences?

There are few different options. The most suitable method will depend on:

 1. how many protein sequences do you want to scan? (1? 100? >100000?)
 1. how comfortable are you working in a technical environment? (Linux terminal? scripting?)

### Manually scan individual sequences

 * Difficulty: EASY
 * Expected time: < 1 minute
 * Technical requirements: none

The most simple way of predicting the location of FunFams on your protein sequence is to use the CATH web pages. Simply copy and paste your protein sequence into the sequence search and follow the instructions.

### Scan many sequences (e.g. 100s)

 * Difficulty: MEDIUM
 * Expected time: < 10 mins
 * Technical requirements: simple scripting (e.g. Perl, Python)

The FunFHMMER server provides a public API that allows users to submit their own sequence scans
through their own scripts. Note, queries are submitted to a queueing system and are subject to fair
use policy.

### Scan entire genomes (e.g. 10000s) (medium)

 * Difficulty: MEDIUM
 * Expected time: < 1 hour
 * Technical requirements: Linux terminal

The FunFHMMER protocol can be used to scan your own sequences on your own machines. This is the recommended
approach if you are trying to scan many thousands of protein sequences (e.g. entire genomes).

## Help

The wiki area contains lots of information, please have a good look through that documentation. If you have a question that is not already answered then please help us improve the documentation by letting us know (by raising an issue or emailing us).

## Relevant Papers

1. [Functional classification of CATH superfamilies: a domain-based approach for protein function annotation](https://doi.org/10.1093/bioinformatics/btv398)
2. [CATH FunFHMMer web server: protein functional annotations using functional family assignments](https://doi.org/10.1093/nar/gkv488)
