# Summary

UD Cuicatec-MesoTree consists of sentences in Tepeuxila Cuicatec annotated as part of the
NSF-funded project "Syntactically-annotated corpora for endangered languages in areal contact"
(MesoTree).

# Introduction

Cuicatec (_dibaku_, _dbaku_, _dubaku_) is a Oto-Manguean language of the Mixtecan
branch, spoken in the southern Cañada region of Oaxaca, Mexico. The treebank is of Tepeuxila Cuicatec
(_dbaku_), spoken in the communities around San Juan Tepeuxila.

The pre-existing dictionary example sentences initially contemplated for annotation are in a variety of 
Tepeuxila Cuicatec different from that of the collaborators, so the treebank was instead created by:

* translating the elicitation sentences from the _Archivo de lenguas indígenas de México_ (ALIMG) (sentence IDs beginning wtih `alimg`);
* asking our collaborators to produce word lists and coming up with a sentence for each (sentence IDs beginning with `ejemplos`).

The sentences are written following the collaborators' own orthographic norms for their language variety. 
The original text is given in `text[orig]`, a normalised version in `text` (affecting apostrophes and capitalisation), and a Spanish
translation in `text[spa]`. Non-standard spellings are marked `Typo=Yes`, usually with the standard
form in the MISC attribute `Normal`. The MISC column also contains morpheme glosses (`Gloss`) and Spanish word
translations (`Trad`) for some of the words. 

The sentences were annotated in a web interface combining UD Annotatrix and Arborator-Grew, with final annotations decided by group 
consensus. Lemmas and morphological features are not yet annotated for the whole corpus.

# Citation

If you use this treebank in your research, please cite:

```
@inproceedings{pugh-etal-2026-mesotree,
    title = "{M}eso{T}ree: Annotated Linguistic Resources for Quantitative Comparative Linguistic Analysis and {NLP} in Mesoamerica",
    author = "Pugh, Robert  and
      Tyers, Francis  and
      Henderson, Robert",
    editor = {{\c{C}}{\"o}ltekin, {\c{C}}a{\u{g}}r{\i}  and
      Dobrovoljc, Kaja},
    booktitle = "Proceedings of the Ninth Workshop on {U}niversal {D}ependencies ({UDW} 2026)",
    month = may,
    year = "2026",
    address = "Palma de Mallorca, Spain",
    publisher = "ELRA Language Resources Association (ELRA)",
    url = "https://aclanthology.org/2026.udw-1.17/",
    doi = "10.63317/2xvtti733shi",
    pages = "197--207"
}
```

# Acknowledgments

We would like to thank our Cuicatec collaborators who wrote, translated and annotated these
sentences. This work was supported by NSF grant 2319246/2319247, "Collaborative Research:
Syntactically-annotated corpora for endangered languages in areal contact".

## References

* Pugh, R., Tyers, F., & Henderson, R. (2026, May). MesoTree: Annotated Linguistic Resources for Quantitative Comparative Linguistic Analysis and NLP in Mesoamerica. In The Ninth Workshop on Universal Dependencies (UDW 2026), (pp. 197–207).


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Pugh, Robert; Tyers, Francis
Contributing: elsewhere
Contact: ftyers@iu.edu
===============================================================================
</pre>
