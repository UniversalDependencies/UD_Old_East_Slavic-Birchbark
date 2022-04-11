# Summary

UD Old\_East\_Slavic-Birchbark is based on the RNC Corpus of Birchbark Letters and includes
documents written in 1025-1500 in an East Slavic vernacular (letters, household and business records, 
records for church services, spell against diseases, and other short inscriptions). 
The treebank is manually syntactically annotated in the UD 2.0 scheme, 
morphological and lexical annotation is a conversion of the original RNC annotation.  

# Introduction

The treebank is based on the historical Corpus of Birchbark Letters written in 1025-1500. 
It is part of the Russian National Corpus and includes documents written in an East Slavic vernacular (letters, 
household and business records, records for church services, spell against diseases, and other short inscriptions). 
The birchbark letters were found during archaeological excavations in Novgorod the Great, Staraya Russa, and other East Slavic cites 
and provide rare evidence of everyday writing in pre-Mongol East Slavic dialects. 
The fact that many documents are damaged and/or fragmented, together with the diversity of the spelling traditions 
presented in them, makes them an interesting case for linguistic analysis and historical NLP research.

The digital copies of the letters are reproduced online in a database available at http://gramoty.ru, where the hypotheses on tokenisation 
are also provided. The morphological analysis was originally done under the Russian National Corpus scheme for the Corpus of Birchbark Letters, 
which is mostly compatible with the RNC Old Russian scheme. Lemmatization reflects the later Old Russian spelling tradition. 
The morphological and lexical annotation of the UD Old\_East\_Slavic-Birchbark treebank is a conversion of this annotation that follows the mapping 
in (Lyashevskaya 2019). The sentence segmentation and the dependency annotation is originally done in the UD 2.0 scheme.  

# Data collection  

The data includes 27k tokens. Documents created at different periods are evenly distributed across test, dev, and train parts.  

* 1025-1100 --  2.4%
* 1100-1200 -- 37.0%
* 1200-1300 -- 16.7%
* 1300-1400 -- 31.5%
* 1400-1500 -- 12.5%

The following genres are presented: 

* letters -- 61.7% 
* household and business records -- 21.6% 
* official and legal documents -- 6.8% 
* records for church services -- 3.4% 
* learner records -- 2.2%
* mixed genred, varia -- 4.3% 

# Conventions  

In the source documents, words are not delimited by spaces. In the treebank, however, they are represented as separate 
words, which is the result of linguistic interpretation. Many documents were found damaged and/or in fragments, so the following conventions 
for the reconstructed texts are used:

* [] -- reconstructed letters, partially preserved
* () -- completely lost letters (pure conjectures) 
* {} -- misspelled letters
* ... -- unknown number of missing letters
* --- known number of missing letters (each letter is represented by one -)
* <lb/> -- line breaks within words  

The birchbark document number and line of the word are given in the MISC field (e.g. `addr="431:1"|line_id=1`). 
Normalized word spellings (e.g. `wf="кѫна"` for `к[ѫ](на)`), grammar and meaning commentary provided in the RNC corpus can also be found in the MISC field.  

# Acknowledgments

Tokenisation, lexical and morphological analysis is primarily based on the study _Old Novgorod Dialect_ by Andrei Zalizniak as well as other studies by 
Valentin Yanin, Andrei Zalizniak, Alexey Gippius, Dmitri Sitchinava, and other researchers of East Slavic vernacular. 
We thank the developers and annotators of the RNC Corpus of Birchbark Letters.  

## References

* Lyashevskaya, Olga. Syntactic annotation of the Old Russian Birchbark Letters Corpus (submitted).

* Sitchinava Dmitri, Dyshkant Anton. Integration of the Old East Slavic Epigraphical Databases, Corpora and Indices. Scripta & E-Scripta, 2021, no. 21, pp. 95–108.


# Changelog

* 2022-05-15 v2.10
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.10
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction
Lemmas: converted from manual
UPOS: converted from manual
XPOS: not available
Features: converted from manual
Relations: manual native
Contributors: Lyashevskaya, Olga
Contributing: elsewhere
Contact: olesar@yandex.ru
===============================================================================
</pre>
