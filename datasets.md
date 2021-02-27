---
layout: default
title: "List of datasets used for training SocialMediaIE"
description: "List of datasets used for training SocialMediaIE"
permalink: /datasets/
---

# List of datasets used for training SocialMediaIE 

- [Dataset referencs](#dataset-referencs)
  * [Tagging datasets](#tagging-datasets)
- [Dataset statistics](#dataset-statistics)
  * [Sentiment](#sentiment)
  * [Abusive](#abusive)
  * [Uncertainity](#uncertainity)
  * [Part of Speech Tagging](#part-of-speech-tagging)
  * [Named Entity Recognition](#named-entity-recognition)
  * [Chunking](#chunking)
  * [Supersense Tagging](#supersense-tagging)
- [Dataset references](#dataset-references)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>



## Dataset referencs

### Tagging datasets

* **POS tagging:** [17,18] (OW), [7] (TIE), [20] (RT), [15](TB), [22] (DS), [12] (FS), and [12,13] (LW). 
* **NER:** [20] (RT), [23] (W16), [6] (W17), [9] (FN), [10] (HG),and [4] (BR), [24] (MM), [11] (YD), [21] (we do not evaluate on this) and [1] (MSM). 
* **Chunking:** [20] (RT) dataset. 
* **Supersense tagging:** [20] (RT) dataset, the [14] (JH) dataset.



## Dataset statistics

### Sentiment

|            	|       	| tokens 	| tweets 	| vocab 	|
|------------	|-------	|--------	|--------	|-------	|
| data       	| split 	|        	|        	|       	|
| Airline    	| dev   	| 20079  	| 981    	| 3273  	|
|            	| test  	| 50777  	| 2452   	| 5630  	|
|            	| train 	| 182040 	| 8825   	| 11697 	|
| Clarin     	| dev   	| 80672  	| 4934   	| 15387 	|
|            	| test  	| 205126 	| 12334  	| 31373 	|
|            	| train 	| 732743 	| 44399  	| 84279 	|
| GOP        	| dev   	| 16339  	| 803    	| 3610  	|
|            	| test  	| 41226  	| 2006   	| 6541  	|
|            	| train 	| 148358 	| 7221   	| 14342 	|
| Healthcare 	| dev   	| 15797  	| 724    	| 3304  	|
|            	| test  	| 16022  	| 717    	| 3471  	|
|            	| train 	| 14923  	| 690    	| 3511  	|
| Obama      	| dev   	| 3472   	| 209    	| 1118  	|
|            	| test  	| 8816   	| 522    	| 2043  	|
|            	| train 	| 31074  	| 1877   	| 4349  	|
| SemEval    	| dev   	| 105108 	| 4583   	| 14468 	|
|            	| test  	| 528234 	| 23103  	| 43812 	|
|            	| train 	| 281468 	| 12245  	| 29673 	|


### Abusive

|           	|       	| tokens 	| tweets 	| vocab  	|
|-----------	|-------	|--------	|--------	|--------	|
| data      	| split 	|        	|        	|        	|
| Founta    	| dev   	| 102534 	| 4663   	| 22529  	|
|           	| test  	| 256569 	| 11657  	| 44540  	|
|           	| train 	| 922028 	| 41961  	| 118349 	|
| WaseemSRW 	| dev   	| 25588  	| 1464   	| 5907   	|
|           	| test  	| 64893  	| 3659   	| 10646  	|
|           	| train 	| 234550 	| 13172  	| 23042  	|


### Uncertainity

|        	|       	| tokens 	| tweets 	| vocab 	|
|--------	|-------	|--------	|--------	|-------	|
| data   	| split 	|        	|        	|       	|
| Riloff 	| dev   	| 2126   	| 145    	| 1002  	|
|        	| test  	| 5576   	| 362    	| 1986  	|
|        	| train 	| 19652  	| 1301   	| 5090  	|
| Swamy  	| dev   	| 1597   	| 73     	| 738   	|
|        	| test  	| 3909   	| 183    	| 1259  	|
|        	| train 	| 14026  	| 655    	| 2921  	|


### Part of Speech Tagging

|             	|                                                                                                                                                                            	| labels                                                                                                                                                                                                 	| labels_unique 	| sequences 	| tokens_unique 	| total_tokens 	|
|-------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------	|-----------	|---------------	|--------------	|
| data_key    	| split_prefix                                                                                                                                                               	|                                                                                                                                                                                                        	|               	|           	|               	|              	|
| Owoputi     	| train                                                                                                                                                                      	| [!, #, $, &, ,, @, A, D, E, G, L, M, N, O, P, R, S, T, U, V, X, Y, Z, ^, ~]                                                                                                                            	| 25            	| 1547      	| 6572          	| 22326        	|
|             	| dev                                                                                                                                                                        	| [!, #, $, &, ,, @, A, D, E, G, L, N, O, P, R, S, T, U, V, X, Z, ^, ~]                                                                                                                                  	| 23            	| 327       	| 2036          	| 4823         	|
|             	| test                                                                                                                                                                       	| [!, #, $, &, ,, @, A, D, E, G, L, N, O, P, R, S, T, U, V, X, Z, ^, ~]                                                                                                                                  	| 23            	| 500       	| 2754          	| 7152         	|
| Foster      	| test                                                                                                                                                                       	| [ADJ, ADP, ADV, CCONJ, DET, NOUN, NUM, PART, PRON, PUNCT, VERB, X]                                                                                                                                     	| 12            	| 250       	| 1068          	| 2841         	|
| TwitIE      	| dev                                                                                                                                                                        	| ['', (, ), ,, :, CC, CD, DT, FW, HT, IN, JJ, JJR, JJS, MD, NN, NNP, NNPS, NNS, PDT, POS, PRP, PRP$, PUNCT, RB, RBR, RBS, RP, RT, SYM, TO, UH, URL, USR, VB, VBD, VBG, VBN, VBP, VBZ, WDT, WP, WRB]     	| 43            	| 269       	| 1229          	| 2998         	|
|             	| test                                                                                                                                                                       	| ['', (, ), ,, :, CC, CD, DT, EX, FW, HT, IN, JJ, JJR, JJS, MD, NN, NNP, NNPS, NNS, PDT, POS, PRP, PRP#, PUNCT, RB, RBR, RBS, RP, RT, SYM, TO, UH, URL, USR, VB, VBD, VBG, VBN, VBP, VBZ, WDT, WP, WRB] 	| 45            	| 632       	| 3539          	| 12196        	|
| dev         	| ['', (, ), ,, :, CC, CD, DT, HT, IN, JJ, JJR, JJS, MD, NN, NNP, NNS, POS, PRP, PRP#, PUNCT, RB, RBR, RP, RT, SYM, TO, UH, URL, USR, VB, VBD, VBG, VBN, VBP, VBZ, WDT, WRB] 	| 41                                                                                                                                                                                                     	| 84            	| 735       	| 1627          	|              	|
| lowlands    	| test                                                                                                                                                                       	| [ADJ, ADP, ADV, CCONJ, DET, NOUN, NUM, PART, PRON, PUNCT, VERB, X]                                                                                                                                     	| 12            	| 1318      	| 4805          	| 19794        	|
| Tweetbankv2 	| dev                                                                                                                                                                        	| [ADJ, ADP, ADV, AUX, CCONJ, DET, INTJ, NOUN, NUM, PART, PRON, PROPN, PUNCT, SCONJ, SYM, VERB, X]                                                                                                       	| 17            	| 710       	| 3271          	| 11759        	|
|             	| train                                                                                                                                                                      	| [ADJ, ADP, ADV, AUX, CCONJ, DET, INTJ, NOUN, NUM, PART, PRON, PROPN, PUNCT, SCONJ, SYM, VERB, X]                                                                                                       	| 17            	| 1639      	| 5632          	| 24753        	|
|             	| test                                                                                                                                                                       	| [ADJ, ADP, ADV, AUX, CCONJ, DET, INTJ, NOUN, NUM, PART, PRON, PROPN, PUNCT, SCONJ, SYM, VERB, X]                                                                                                       	| 17            	| 1201      	| 4699          	| 19095        	|
| DiMSUM2016  	| train                                                                                                                                                                      	| [ADJ, ADP, ADV, AUX, CCONJ, DET, INTJ, NOUN, NUM, PART, PRON, PROPN, PUNCT, SCONJ, SYM, VERB, X]                                                                                                       	| 17            	| 4799      	| 9113          	| 73826        	|
|             	| test                                                                                                                                                                       	| [ADJ, ADP, ADV, AUX, CCONJ, DET, INTJ, NOUN, NUM, PART, PRON, PROPN, PUNCT, SCONJ, SYM, VERB, X]                                                                                                       	| 17            	| 1000      	| 4010          	| 16500        	|


### Named Entity Recognition

|            	|              	| boundaries 	| labels                                                                                                                    	| labels_unique 	| sequences 	| tokens_unique 	| total_tokens 	|
|------------	|--------------	|------------	|---------------------------------------------------------------------------------------------------------------------------	|---------------	|-----------	|---------------	|--------------	|
| data_key   	| split_prefix 	|            	|                                                                                                                           	|               	|           	|               	|              	|
| Finin      	| train        	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 10000     	| 19663         	| 172188       	|
|            	| test         	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 5369      	| 13027         	| 97525        	|
| Hege       	| test         	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 1545      	| 4552          	| 20664        	|
| Ritter     	| train        	| [I, B, O]  	| [COMPANY, OTHER, FACILITY, PERSON, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 1900      	| 7695          	| 36936        	|
|            	| dev          	| [I, B, O]  	| [COMPANY, OTHER, PERSON, FACILITY, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 240       	| 1731          	| 4612         	|
|            	| test         	| [I, B, O]  	| [COMPANY, OTHER, PERSON, FACILITY, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 254       	| 1776          	| 4921         	|
| YODIE      	| train        	| [I, B, O]  	| [COMPANY, OTHER, PERSON, LOCATION, FACILITY, MOVIE, MUSICARTIST, GEO-LOC, UNK, TVSHOW, PRODUCT, SPORTSTEAM, ORGANIZATION] 	| 13            	| 396       	| 2554          	| 7905         	|
|            	| test         	| [I, B, O]  	| [COMPANY, OTHER, FACILITY, LOCATION, PERSON, MOVIE, MUSICARTIST, GEO-LOC, UNK, TVSHOW, PRODUCT, SPORTSTEAM, ORGANIZATION] 	| 13            	| 397       	| 2578          	| 8032         	|
| WNUT2016   	| train        	| [I, B, O]  	| [COMPANY, OTHER, FACILITY, PERSON, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 2394      	| 9068          	| 46469        	|
|            	| test         	| [I, B, O]  	| [COMPANY, OTHER, PERSON, FACILITY, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 3850      	| 16012         	| 61908        	|
|            	| dev          	| [I, B, O]  	| [COMPANY, OTHER, FACILITY, PERSON, MOVIE, MUSICARTIST, GEO-LOC, TVSHOW, PRODUCT, SPORTSTEAM]                              	| 10            	| 1000      	| 5563          	| 16261        	|
| WNUT2017   	| train        	| [I, B, O]  	| [GROUP, CORPORATION, PERSON, LOCATION, PRODUCT, CREATIVE-WORK]                                                            	| 6             	| 3394      	| 12840         	| 62730        	|
|            	| dev          	| [I, B, O]  	| [GROUP, CORPORATION, PERSON, LOCATION, PRODUCT, CREATIVE-WORK]                                                            	| 6             	| 1009      	| 3538          	| 15733        	|
|            	| test         	| [I, B, O]  	| [GROUP, CORPORATION, PERSON, LOCATION, PRODUCT, CREATIVE-WORK]                                                            	| 6             	| 1287      	| 5759          	| 23394        	|
| MSM2013    	| train        	| [I, B, O]  	| [LOC, MISC, PER, ORG]                                                                                                     	| 4             	| 2815      	| 8514          	| 51521        	|
|            	| test         	| [I, B, O]  	| [LOC, PER, ORG, MISC]                                                                                                     	| 4             	| 1450      	| 5701          	| 29089        	|
| NEEL2016   	| train        	| [I, B, O]  	| [PERSON, THING, LOCATION, EVENT, PRODUCT, ORGANIZATION, CHARACTER]                                                        	| 7             	| 2588      	| 9731          	| 51669        	|
|            	| dev          	| [I, B, O]  	| [PERSON, LOCATION, THING, EVENT, PRODUCT, ORGANIZATION, CHARACTER]                                                        	| 7             	| 88        	| 762           	| 1647         	|
|            	| test         	| [I, B, O]  	| [PERSON, THING, LOCATION, EVENT, PRODUCT, ORGANIZATION, CHARACTER]                                                        	| 7             	| 2663      	| 9894          	| 47488        	|
| BROAD      	| train        	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 5605      	| 19523         	| 90060        	|
|            	| dev          	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 933       	| 5312          	| 15169        	|
|            	| test         	| [I, B, O]  	| [LOC, PER, ORG]                                                                                                           	| 3             	| 2802      	| 11772         	| 45159        	|
| MultiModal 	| train        	| [I, B, O]  	| [LOC, PER, ORG, MISC]                                                                                                     	| 4             	| 4000      	| 20221         	| 64439        	|
|            	| dev          	| [I, B, O]  	| [LOC, MISC, PER, ORG]                                                                                                     	| 4             	| 1000      	| 6832          	| 16178        	|
|            	| test         	| [I, B, O]  	| [LOC, PER, ORG, MISC]                                                                                                     	| 4             	| 3257      	| 17381         	| 52822        	|


### Chunking

|          	|              	| boundaries 	| labels                                           	| labels_unique 	| sequences 	| tokens_unique 	| total_tokens 	|
|----------	|--------------	|------------	|--------------------------------------------------	|---------------	|-----------	|---------------	|--------------	|
| data_key 	| split_prefix 	|            	|                                                  	|               	|           	|               	|              	|
| Ritter   	| train        	| [I, B, O]  	| [ADJP, PP, INTJ, ADVP, PRT, NP, SBAR, VP, CONJP] 	| 9             	| 551       	| 3158          	| 10584        	|
|          	| dev          	| [I, B, O]  	| [ADJP, PP, INTJ, ADVP, PRT, NP, SBAR, VP]        	| 8             	| 118       	| 994           	| 2317         	|
|          	| test         	| [I, B, O]  	| [ADJP, PP, INTJ, ADVP, PRT, NP, SBAR, VP]        	| 8             	| 119       	| 988           	| 2310         	|


### Supersense Tagging

|               	|              	| boundaries 	| labels                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      	| labels_unique 	| sequences 	| tokens_unique 	| total_tokens 	|
|---------------	|--------------	|------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------	|-----------	|---------------	|--------------	|
| data_key      	| split_prefix 	|            	|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             	|               	|           	|               	|              	|
| Ritter        	| train        	| [I, B, O]  	| [NOUN.BODY, NOUN.STATE, NOUN.ARTIFACT, NOUN.ATTRIBUTE, NOUN.FOOD, NOUN.TOPS, NOUN.COGNITION, NOUN.EVENT, NOUN.OBJECT, NOUN.MOTIVE, NOUN.GROUP, VERB.COMMUNICATION, NOUN.PHENOMENON, VERB.POSSESSION, VERB.COMPETITION, NOUN.POSSESSION, NOUN.FEELING, VERB.SOCIAL, NOUN.ANIMAL, VERB.CREATION, VERB.CONSUMPTION, VERB.PERCEPTION, VERB.CONTACT, VERB.WEATHER, VERB.BODY, NOUN.LOCATION, NOUN.QUANTITY, NOUN.SUBSTANCE, NOUN.RELATION, NOUN.TIME, NOUN.PERSON, VERB.COGNITION, VERB.EMOTION, NOUN.PLANT, VERB.STATIVE, VERB.MOTION, NOUN.COMMUNICATION, NOUN.PROCESS, NOUN.ACT, VERB.CHANGE] 	| 40            	| 551       	| 3174          	| 10652        	|
|               	| dev          	| [I, B, O]  	| [NOUN.BODY, NOUN.STATE, NOUN.ARTIFACT, NOUN.ATTRIBUTE, NOUN.FOOD, NOUN.COGNITION, NOUN.EVENT, NOUN.OBJECT, NOUN.MOTIVE, NOUN.GROUP, VERB.COMMUNICATION, NOUN.PHENOMENON, VERB.COMPETITION, VERB.POSSESSION, NOUN.POSSESSION, NOUN.FEELING, VERB.SOCIAL, NOUN.ANIMAL, VERB.CREATION, VERB.CONSUMPTION, VERB.PERCEPTION, VERB.CONTACT, VERB.BODY, NOUN.LOCATION, NOUN.QUANTITY, NOUN.SUBSTANCE, NOUN.RELATION, NOUN.TIME, VERB.COGNITION, NOUN.PERSON, VERB.EMOTION, NOUN.PLANT, VERB.STATIVE, VERB.MOTION, NOUN.COMMUNICATION, NOUN.ACT, VERB.CHANGE]                                        	| 37            	| 118       	| 1014          	| 2242         	|
|               	| test         	| [I, B, O]  	| [NOUN.BODY, NOUN.STATE, NOUN.ARTIFACT, NOUN.ATTRIBUTE, NOUN.FOOD, NOUN.TOPS, NOUN.COGNITION, NOUN.EVENT, NOUN.OBJECT, NOUN.MOTIVE, NOUN.SHAPE, NOUN.GROUP, VERB.COMMUNICATION, NOUN.PHENOMENON, VERB.POSSESSION, NOUN.FEELING, NOUN.POSSESSION, VERB.COMPETITION, VERB.SOCIAL, NOUN.ANIMAL, VERB.CREATION, VERB.CONSUMPTION, VERB.PERCEPTION, VERB.CONTACT, VERB.WEATHER, VERB.BODY, NOUN.LOCATION, NOUN.QUANTITY, NOUN.SUBSTANCE, NOUN.RELATION, NOUN.TIME, NOUN.PERSON, VERB.COGNITION, VERB.EMOTION, VERB.STATIVE, VERB.MOTION, NOUN.COMMUNICATION, NOUN.PROCESS, NOUN.ACT, VERB.CHANGE] 	| 40            	| 118       	| 1011          	| 2291         	|
| Johannsen2014 	| test         	| [I, B, O]  	| [NOUN.BODY, NOUN.STATE, NOUN.ARTIFACT, NOUN.ATTRIBUTE, NOUN.FOOD, NOUN.COGNITION, NOUN.EVENT, NOUN.OBJECT, NOUN.SHAPE, NOUN.GROUP, VERB.COMMUNICATION, NOUN.PHENOMENON, VERB.COMPETITION, VERB.POSSESSION, NOUN.FEELING, NOUN.POSSESSION, VERB.SOCIAL, NOUN.ANIMAL, VERB.CREATION, VERB.CONSUMPTION, VERB.PERCEPTION, VERB.CONTACT, VERB.BODY, NOUN.LOCATION, NOUN.QUANTITY, NOUN.SUBSTANCE, NOUN.RELATION, NOUN.TIME, NOUN.PERSON, VERB.COGNITION, VERB.EMOTION, VERB.STATIVE, VERB.MOTION, NOUN.COMMUNICATION, NOUN.PROCESS, NOUN.ACT, VERB.CHANGE]                                       	| 37            	| 200       	| 1249          	| 3064         	|


## Dataset references

* [1] Amparo Elizabeth Cano, Andrea Varga, Matthew Rowe, Milan Stankovic, and Aba-Sah Dadzie. 2013. Making Sense of Microposts (#MSM2013) Concept ExtractionChallenge. In#MSM.
* [2] Richard A. Caruana. 1993.  Multitask Learning: A Knowledge-Based Source ofInductive Bias.  InMachine Learning Proceedings 1993. Elsevier, 41–48.   https://doi.org/10.1016/b978-1-55860-307-3.50012-5
* [3] Ronan Collbert, Jason Weston, LÃľon Bottou, Michael Karlen, Koray Kavukcuoglu,and Pavel Kuksa. 2011.  Natural Language Processing (Almost) from Scratch.Journal ofMachine Learning Research12 (2 2011), 2493–2537.   http://dl.acm.org/citation.cfm?id=2078186
* [4] Leon  Derczynski,  Kalina  Bontcheva,  and  Ian  Roberts.  2016.Broad  Twit-ter  Corpus:  A  Diverse  Named  Entity  Recognition  Resource.Proceedings ofCOLING 2016, the 26th International Conference on Computational Linguis-tics: Technical Papers(2016),  1169–1179.http://aclanthology.info/papers/broad-twitter-corpus-a-diverse-named-entity-recognition-resource
* [5] Leon Derczynski, Diana Maynard, Niraj Aswani, and Kalina Bontcheva. 2013.Microblog-genre Noise and Impact on Semantic Annotation Accuracy. InPro-ceedings of the 24th ACM Conference on Hypertext and Social Media (HT ’13). ACM,New York, NY, USA, 21–30.   https://doi.org/10.1145/2481492.2481495
* [6] Leon Derczynski, Eric Nichols, Marieke van Erp, and Nut Limsopatham. 2017.Results of the WNUT2017 Shared Task on Novel and Emerging Entity Recognition.InProceedings of the 3rd Workshop on Noisy User-generated Text. Association forComputational Linguistics, Copenhagen, Denmark, 140–147.  https://doi.org/10.18653/v1/W17-4418
* [7] Leon Derczynski, Alan Ritter, Sam Clark, and Kalina Bontcheva. 2013.  Twit-ter Part-of-Speech Tagging for All: Overcoming Sparse and Noisy Data.Pro-ceedings of the International Conference Recent Advances in Natural LanguageProcessing RANLP 2013(2013),  198–206.http://aclanthology.info/papers/twitter-part-of-speech-tagging-for-all-overcoming-sparse-and-noisy-data
* [8] Jacob Eisenstein. 2013.   What to do about bad language on the internet. InProceedings of the 2013 Conference of the North American Chapter of the Associationfor Computational Linguistics: Human Language Technologies. Association forComputational Linguistics, Atlanta, Georgia, 359–369.   https://www.aclweb.org/anthology/N13-1037
* [9] Tim Finin, William Murnane, Anand Karandikar, Nicholas Keller, Justin Mar-tineau, and Mark Dredze. 2010. Annotating Named Entities in Twitter Data withCrowdsourcing.Proceedings of the NAACL HLT 2010 Workshop on Creating Speechand Language Data with Amazon’s Mechanical Turk2010, January, 80–88.
* [10] Hege Fromreide, Dirk Hovy, and Anders Søgaard. 2014. Crowdsourcing and anno-tating NER for Twitter #drift. InProceedings of the Ninth International Conferenceon Language Resources and Evaluation (LREC’14). European language resourcesdistribution agency, 2544–2547.   http://www.lrec-conf.org/proceedings/lrec2014/pdf/421_Paper.pdf
* [11] Genevieve Gorrell, Johann Petrak, and Kalina Bontcheva. 2015. Using @TwitterConventions to Improve #LOD-Based Named Entity Disambiguation. Springer,Cham, 171–186.  https://doi.org/10.1007/978-3-319-18818-8{_}11
* [12] Dirk Hovy, Barbara Plank, and Anders Søgaard. 2014. Experiments with crowd-sourced re-annotation of a POS tagging data set. InProceedings of the 52ndAnnual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers). Association for Computational Linguistics, Baltimore, Maryland, 377–382.https://doi.org/10.3115/v1/P14-2062
* [13] Dirk Hovy, Barbara Plank, and Anders Søgaard. 2014.   When POS data setsdon’t add up: Combatting sample bias.Proceedings of the Ninth InternationalConference on Language Resources and Evaluation (LREC-2014)(2014).   https://aclanthology.coli.uni-saarland.de/papers/L14-1402/l14-1402
* [14] Anders Johannsen, Dirk Hovy, HÃľctor Martínez Alonso, Barbara Plank, andAnders Søgaard. 2014.  More or less supervised supersense tagging of Twitter.InProceedings of the Third Joint Conference on Lexical and Computational Se-mantics (*SEM 2014). Association for Computational Linguistics and Dublin CityUniversity, Stroudsburg, PA, USA, 1–11.  https://doi.org/10.3115/v1/S14-1001
* [15] Yijia Liu, Yi Zhu, Wanxiang Che, Bing Qin, Nathan Schneider, and Noah A. Smith.2018.  Parsing Tweets into Universal Dependencies. InProceedings of the 2018Conference of the North American Chapter of the Association for ComputationalLinguistics: Human Language Technologies, Volume 1 (Long Papers). Associationfor Computational Linguistics, New Orleans, Louisiana, 965–975.   https://doi.org/10.18653/v1/N18-1088
* [16] Héctor Martínez Alonso and Barbara Plank. 2017. When is multitask learningeffective? Semantic sequence prediction under varying data conditions. InPro-ceedings of the 15th Conference of the European Chapter of the Association forComputational Linguistics: Volume 1, Long Papers. Association for ComputationalLinguistics, Valencia, Spain, 44–53.  https://www.aclweb.org/anthology/E17-1005
* [17] Olutobi Owoputi, Brendan O’Connor, Chris Dyer, Kevin Gimpel, and NathanSchneider. 2012. Part-of-Speech Tagging for Twitter: Word Clusters and OtherAdvances.Cmu-Ml-12-107(2012).
* [18] Olutobi Owoputi, Brendan O’Connor, Chris Dyer, Kevin Gimpel, Nathan Schnei-der, and Noah a Smith. 2013.   Improved Part-of-Speech Tagging for OnlineConversational Text with Word Clusters.Proceedings of NAACL-HLT 2013June(2013), 380–390.   https://doi.org/10.1.1.343.3572
* [19] Matthew Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark,Kenton Lee, and Luke Zettlemoyer. 2018.  Deep Contextualized Word Repre-sentations. InProceedings of the 2018 Conference of the North American Chapterof the Association for Computational Linguistics: Human Language Technologies,Volume 1 (Long Papers). Association for Computational Linguistics, New Orleans,Louisiana, 2227–2237.  https://doi.org/10.18653/v1/N18-1202
* [20] Alan Ritter, Sam Clark, and Oren Etzioni. 2011.  Named entity recognition intweets: an experimental study. InProceedings of Emperical Methods for NaturalLangauge Processing. 1524–1534.   https://doi.org/10.1075/li.30.1.03nad
* [21] Giuseppe Rizzo, Marieke van Erp, Julien Plu, and RaphaÃńl Troncy. 2016. MakingSense of Microposts (#Microposts2016) Named Entity rEcognition and Linking(NEEL) Challenge. InWorkshop on Making Sense of Microposts (#Microposts2016).Montréal.   http://ceur-ws.org/Vol-1691/microposts2016_neel-challenge-report/http://ceur-ws.org/Vol-1691/microposts2016_neel-challenge-report/microposts2016_neel-challenge-report.pdfhttp://microposts2016.seas.upenn.edu/challenge.htmlhttp://ceur-ws.org/Vol-1691/mic
* [22] Nathan Schneider and Noah A. Smith. 2015.  A Corpus and Model IntegratingMultiword Expressions and Supersenses. InProceedings of the 2015 Conference ofthe North American Chapter of the Association for Computational Linguistics: Hu-man Language Technologies. Association for Computational Linguistics, Denver,Colorado, 1537–1547.  https://doi.org/10.3115/v1/N15-1177
* [23] Benjamin  Strauss,  Bethany  Toma,  Alan  Ritter,  Marie-Catherine  de  Marn-effe,  and  Wei  Xu.  2016.Results  of  the  WNUT16  Named  Entity  Recog-nition  Shared  Task.Proceedings of the 2nd Workshop on Noisy User-generated Text (WNUT)(2016),  138–144.http://aclanthology.info/papers/results-of-the-wnut16-named-entity-recognition-shared-task
* [24] Qi Zhang, Jinlan Fu, Xiaoyu Liu, and Xuanjing Huang. 2018.   Adaptive Co-attention Network for Named Entity Recognition in Tweets.   https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16432
