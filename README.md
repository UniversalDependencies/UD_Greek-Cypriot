# Summary

This is the first Cypriot-Greek treebank. Cypriot Greek is a living dialect of the South-Eastern Greek dialect group and is spoken by more than 700,000 people on Cyprus and Cypriot communities in the UK, USA, Australia, Canada and South Africa.

The treebank contains material from transcribed authentic speech,  texts scraped from the Web and scripts from CyBC series. 


# About Cypriot-Greek

The long time of isolation from other Greek-speaking areas led to substantial differences between Cypriot-Greek and Standard Modern Greek, occasionally rendering the two mutually unintelligible due to a host of phonological, morphological, lexical and syntactic differences. 

On Cyprus, Cypriot-Greek is used in oral communication, while Standard Modern Greek functions in formal contexts and is the instructional language in public primary and secondary education. So far, Cypriot-Greek has no standardized alphabet and orthography.  The alphabet and he orthographic conventions  of Standard Modern Greek are formally used but they fail to represent the distinctive sounds and morphology of Cypriot-Greek; the treebank adopts the alphabet and the orthography of Cypriot-Greek proposed in Armostis et al. (2014). 

# About the treebank 

The current version of the Cypriot-Greek treebank contains the 100 sentences of the test set:  average length in words 17,8 (range: 7-30), number of tokens: 1782. The development of the treebank is ongoing work and we expect that new, enriched versions will be uploaded in due time.


The final version of the treebank will contain 500 sentences, as follows:

- 54% (270) transcribed oral data from authentic spontaneous speech [Mozilla Data Collective/Common Voice Spontaneous Speech 5.0 - Cypriot Greek]( https://mozilladatacollective.com/datasets/cmu5n1iaw00tjmi07dcx96c1m)

- 22,8% (114) from scripts of the Cyprus Broadcasting Corporation-CyBC
 
- 20% (100) from texts scrapped from the WEB [GRDD+ dialectal dataset]( https://arxiv.org/pdf/2511.03772)

- 3,2% (16) from texts collected by Spyros Armostis

To homogenise the data by making them adapt to the orthography proposed by Armostis et al. (2014), the following pipeline has been applied: first automatic editing with an orthographic normaliser tool provided by Spyros Armostis and then manual editing.

Active annotation is  used for knowledge transfer from GUD, a UD treebank of Standard Modern Greek, and the results are edited manually by the annotators group. The 100 sentences of the test set have been annotated with a  model trained on GUD and then edited manually by S. Markantonatou and S. Bompolas ******(inter annotator agreement before adjudication XXXX, and after adjudication 1)*****. 

The final version of the data will be split into  training (70%),  dev (10%) and  test (20%) sets.



# Acknowledgments

For the development of the treebank worked: Stavros Bompolas and Stella Markantonatou,  [Institute for Language and Speech Processing (ILSP)/Athena Research Centre](http://www.ilsp.gr/), Spyros Armostis [Department of English Studies/University of Cyprus](https://www.ucy.ac.cy/eng/?lang=en), Antonis Dimakis, PhD student [NKUA](https://en.uoa.gr/)  and [Archimedes Unit/Athena Research Center](https://archimedesai.gr/en/),  and Maria Apostolidou, Eirini Chalkia, Christina Petropoulou, Dionysis Piskopos and,  Konstantinos Raftis, MSc students/[Language Technology](https://www.di.uoa.gr/en/lt). 

# Bibliography 

Spyros Armostis, Kyriaki Christodoulou, Marianna Katsoyannou, and Charalambos Themistocleous. 2014. Addressing writing system issues in dialectal lexicography: The case of cypriot greek. In Carrie Dyck, Tania Granadillo, Keren Rice, and Jorge Emilio Rosés Labrada, editors, Dialogue on Dialect Standardization, pages 23–38. Cambridge Scholars Publishing, Cambridge.

## References

* (citation)


# Changelog

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: TO-BE-SPECIFIED
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Markantonatou, Stella; Armostis, Spyros; Bompolas, Stavros; Dimakis, Antonis; Apostolidou, Maria; Chalkia, Eirini; Raftis, Konstantinos; Petropoulou, Christina-Athanasia; Piskopos, Dionisis
Contributing: here
Contact: stiliani.markantonatou@gmail.com
===============================================================================
</pre>
