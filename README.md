# Summary

This is the first Cypriot-Greek treebank. Cypriot Greek is a living dialect of the South-Eastern Greek dialect group and is spoken by more than 700,000 people on Cyprus and Cypriot communities in the UK, USA, Australia, Canada and South Africa.

The treebank contains material from transcribed authentic speech,  texts scrapedand from the Web *****theatrical plays*******. 


# About Cypriot-Greek

The long time of isolation from other Greek-speaking areas led to substantial differences between Cypriot-Greek and Standard Modern Greek, occasionally rendering the two mutually unintelligible due to a host of phonological, morphological, lexical and syntactic differences. 

On Cyprus, Cypriot-Greek is used in oral communication, while Standard Modern Greek functions in formal contexts and is the instructional language in public primary and secondary education. So far, Cypriot-Greek has no standardized writing system.  The alphabet of Standard Modern Greek is formally used but it does not represent the distinctive sounds of Cypriot-Greek; the treebank adopts the alphabet and the orthography of Cypriot-Greek proposed in Armostis et al. (2014). 

# About the treebank 

The current version of the Cypriot-Greek treebank contains 100 sentences that function as the test set: length in words ***average length +/- yy***, number of tokens: ***Y***. The final version of the treebank will contain 500 sentences. <!---it will be informed with the final figures for length and tokens--->


Texts were drawn from authentic spontaneous Cypriot-Greek oral data: [Mozilla Data Collective/Common Voice Spontaneous Speech 5.0 - Cypriot Greek]( https://mozilladatacollective.com/datasets/cmu5n1iaw00tjmi07dcx96c1m) ***(XX%)***, text data scraped from the Web: [GRDD+ dialectal dataset]( https://arxiv.org/pdf/2511.03772) ***(YY%)*** and ****texts contributed by Spyros Armostis******  ***(ZZ%)*** (the percentages refer to the final treebank, not the 100 examples version).   To homogenise the data by making them adapt to the orthography proposed by Armostis et al. (2014), the following pipeline has been applied: first automatic editing with ****Spyros’ tool**** and then manual editing.

Active annotation is  used for knowledge transfer from GUD, a UD treebank of Standard Modern Greek, and the results are edited manually by the annotators group. The 100 sentences of the test set have been annotated with a  model trained on GUD and then edited manually by S. Markantonatou and S. Bompolas ******(inter annotator agreement before adjudication XXXX, and after adjudication 1)*****. 

The data will be split into  training (70%),  dev (10%) and  test (20%) sets.



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
Contributors: Markantonatou, Stella; Armostis, Spyros; Bompolas, Stavros; Stamou, Vivian; Apostolidou, Maria; Chalkia, Eirini; Raftis, Konstantinos; Petropoulou, Christina-Athanasia; Piskopos, Dionisis
Contributing: here
Contact: stiliani.markantonatou@gmail.com
===============================================================================
</pre>
