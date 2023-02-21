# Corpora for Germanic low-resource languages and dialects

You can read more about this corpus collection here: *(link TBD)*.
If you find this overview useful for your research, please cite:
```
citation TBD
```

Table of contents:
- [Faroese](#faroese--fao--fao1244)
- [Norwegian](#norwegian--nor--norw1258)
- [Elfdalian](#elfdalianövdalian--ovd--elfd1234)
- [Swedish](#swedish--swe--swe1254)
- [Scots](#scots--sco--scot1243)
- [English](#english--eng--stan1293)
- [West Frisian](#western-frisian--fry--west2354)
- [North Frisian](#northern-frisian--frr--north2626)

## Faroese · fao · [fao1244](https://glottolog.org/resource/languoid/id/faro1244)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [UD Faroese OFT](https://github.com/UniversalDependencies/UD_Faroese-OFT) ([Tyers ea 2018](https://aclanthology.org/W18-6017/)) | POS (UPOS, Giellatekno-FAO), dependencies (UD), morpho (UD), lemmas | 1.2k sents | Faroese ortho |
| [FarPaHC](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92) ([Ingason ea 2012](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92), [Rögnvalsson ea 2012](https://aclanthology.org/L12-1228/)) | POS (mod. [Penn-historical](https://www.ling.upenn.edu/hist-corpora/annotation/index.html), phrase structure (mod. Penn-historical) | 53k toks | Faroese ortho |
| [UD Faroese FarPaHC](https://github.com/UniversalDependencies/UD_Faroese-FarPaHC) ([Ingason ea 2012](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92), [Rögnvalsson ea 2012](https://aclanthology.org/L12-1228/)) | POS (UPOS), dependencies (UD), morpho (UD) | 40k toks | Faroese ortho |
| [Føroyskur talumálsbanki](https://clarino.uib.no/corpuscle-classic/corpus-list) ([Jacobsen 2022](https://septentrio.uit.no/index.php/nordlyd/article/view/6440)) | | 599.9k toks | Faroese ortho |
| [BLARK 1.0](https://maltokni.fo/en/resources) (background corpus) ([Simonsen ea 2022](https://aclanthology.org/2022.lrec-1.495/)) | | 25M toks | Faroese ortho |
| [Faroese text collection (FTS)](https://spraakbanken.gu.se/en/resources/fts) | in BLARK 1.0 background corpus | 1.1M toks | Faroese ortho |
| [BLARK 1.0](https://maltokni.fo/en/resources) (audio) ([Simonsen ea 2022](https://aclanthology.org/2022.lrec-1.495/)) | locations | 100 hrs | audio, Faroese ortho, some phono |
| [Faroese Danish Corpus Hamburg (FADAC Hamburg)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:fadac-0.2.dan) (subset) ([Debess 2019](https://macau.uni-kiel.de/receive/publ_mods_00002318)) | locations | 31 hrs | audio, Faroese ortho |
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 417 sents | Faroese ortho |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated; *not* in [CC-100](https://data.statmt.org/cc-100/) or [OSCAR 22.01](https://oscar-project.org/post/oscar-v22-01/) | 102 MB | Faroese ortho |
| [Wikipedia](https://dumps.wikimedia.org/) ([fo](https://fo.wikipedia.org/) subset) | uncurated | 14k articles | Faroese ortho |

## Norwegian · nor · [norw1258](https://glottolog.org/resource/languoid/id/norw1258)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [LIA Treebank](https://github.com/textlab/spoken_norwegian_resources/tree/master/treebanks/Norwegian-NynorskLIA) ([+transcriptions](https://tekstlab.uio.no/LIA/norsk/index_english.html)) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710/)) | POS ([mod](https://tekstlab.uio.no/LIA/pdf/parseretningslinjer-lia12042019.pdf). [NDT](https://tekstlab.uio.no/LIA/pdf/retningslinjer_NDT_norsk.pdf)), dependencies (mod. NDT), morpho (mod. NDT), lemmas, locations | 7.5k speech segments / 78k toks | [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) |
| [UD Norwegian Nynorsk LIA](https://github.com/UniversalDependencies/UD_Norwegian-NynorskLIA) ([+transcriptions](https://tekstlab.uio.no/LIA/norsk/index_english.html)) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710/)) | POS (UPOS), dependencies (UD), morpho (UD), lemmas, locations | 5.3k speech segments / 55k toks |  [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) |
| [NDC Treebank](https://github.com/textlab/spoken_norwegian_resources/tree/master/treebanks/Norwegian-BokmaalNDC) (+[transcriptions](http://tekstlab.uio.no/scandiasyn/download.html); [website](http://www.tekstlab.uio.no/nota/scandiasyn/treebank.html)) ([Kåsen ea 2022](https://aclanthology.org/2022.lrec-1.516/), [Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | POS ([mod](https://tekstlab.uio.no/LIA/pdf/parseretningslinjer-lia12042019.pdf). [NDT](https://tekstlab.uio.no/LIA/pdf/retningslinjer_NDT_norsk.pdf)), dependencies (mod. NDT), morpho (mod. NDT), lemmas, locations | 4.6k speech segments / 66k toks | Bokmål ortho, [phono](http://www.tekstlab.uio.no/scandiasyn/Transkripsjonsrettleiing%20for%20ScanDiaSyn.pdf) |
| NorDial (subset) ([Mæhlum ea 2022](https://aclanthology.org/2022.vardial-1.7/) – contact authors) | POS (UPOS) | 35+ tweets | ad-hoc spelling |
| [Nordic Dialect Corpus](http://tekstlab.uio.no/nota/scandiasyn/) (subset) ([Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | locations | 1.9M toks | Bokmål ortho, [phono](http://www.tekstlab.uio.no/scandiasyn/Transkripsjonsrettleiing%20for%20ScanDiaSyn.pdf) |
| [The spoken language investigation in Oslo (TAUS)](http://www.tekstlab.uio.no/nota/taus/english.html) | locations (East vs. West Oslo) | 387k toks | [Bokmål ortho, phono](http://www.tekstlab.uio.no/nota/oslo/transkripsjon/NoTa-transkripsjonsveil7.pdf) |
| [NorDial](https://github.com/jerbarnes/nordial) (subset) ([Barnes ea 2021](https://aclanthology.org/2021.nodalida-main.51/)) | | 348 tweets | ad-hoc spelling |
| [American Nordic Speech Corpus (CANS)](https://tekstlab.uio.no/norskiamerika/korpus.html) (subset) ([Johannessen ea 2015](https://aclanthology.org/W15-1840/)) | locations (USA/Canada) | 773k toks | Bokmål ortho, [phono](https://tekstlab.uio.no/norskiamerika/Transkripsjons-translittereringsveiledning-norskiamerika.pdf) |
| [Speech Database for Norwegian (NB Tale)](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-31/) | locations | 365 × 2 mins (spontaneous speech), 7.6k sents (reading) | audio, Bokmål ortho, mod. X-SAMPA |
| [Norwegian Parliamentary Speech Corpus (NPSC)](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-58/) | locations | 140 hrs / 65k sents / 1.2M toks | audio, Bokmål/​Nynorsk ortho |

## Elfdalian/Övdalian · ovd · [elfd1234](https://glottolog.org/resource/languoid/id/elfd1234)

Glottolog 4.7 categorizes Elfdalian as a dialect of Dalecarlian/[dale1238](https://glottolog.org/resource/languoid/id/dale1238).

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Nordic Dialect Corpus](http://tekstlab.uio.no/nota/scandiasyn/) (subset) ([Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | locations | 15.7k toks | Elfdalian ortho (Råðdjärum's orthography), Swedish ortho |

## Swedish · swe · [swe1254](https://glottolog.org/resource/languoid/id/swed1254)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [American Nordic Speech Corpus (CANS)](https://tekstlab.uio.no/norskiamerika/korpus.html) (subset) ([Johannessen ea 2015](https://aclanthology.org/W15-1840/)) | locations (USA) | 46k toks | Swedish ortho, [phono](https://tekstlab.uio.no/norskiamerika/CANS-f%C3%B6r-svensk.pdf) |

## Scots · sco · [scot1243](https://glottolog.org/resource/languoid/id/scot1243)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Scottish Corpus of Texts & Speech (SCOTS)](https://scottishcorpus.ac.uk/) (subset) ([Anderson ea 2007](https://link.springer.com/chapter/10.1057/9780230223936_2)) | | ? | mix of ad-hoc spelling and English ortho |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated; *not* in [CC-100](https://data.statmt.org/cc-100/) or [OSCAR 22.01](https://oscar-project.org/post/oscar-v22-01/) | 35 MB | ? |
| [Wikipedia](https://dumps.wikimedia.org/) ([sco](https://sco.wikipedia.org/) subset) | uncurated, see also [here](https://www.theguardian.com/uk-news/2020/aug/26/shock-an-aw-us-teenager-wrote-huge-slice-of-scots-wikipedia) and [here](https://slate.com/technology/2020/09/scots-wikipedia-language-american-teenager.html) | 39k articles | [Scots ortho](https://sco.wikipedia.org/wiki/Wikipedia:Spellin_an_grammar) |

## English · eng · [stan1293](https://glottolog.org/resource/languoid/id/stan1293)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [TwitterAAE-UD](https://slanglab.cs.umass.edu/TwitterAAE/) ([Blodgett ea 2016](https://slanglab.cs.umass.edu/TwitterAAE/)) | POS (UPOS). AAVE | 250 tweets | ad-hoc spelling |
| [Diachronic Electronic Corpus of Tyneside English (DECTE)](https://research.ncl.ac.uk/decte/index.htm) ([Corrigan ea 2012](https://research.ncl.ac.uk/decte/index.htm) | Tyneside (UK) | 72 hrs / 804k toks | audio, English ortho, partially: [phono](https://research.ncl.ac.uk/decte/representation.htm) |
| [Intonational Variation in English (IViE)](http://www.phon.ox.ac.uk/files/apps/IViE/) ([Nolan & Post 2013](https://research.ncl.ac.uk/decte/representation.htm)) | locations (British Isles) | 36 hrs | audio, English ortho |
| [Crowdsourced high-quality UK and Ireland English Dialect speech data set](https://openslr.org/83) ([Demirsahin ea 2020](https://aclanthology.org/2020.lrec-1.804/)) | locations (British Isles) | locations (British Isles) | 31 hrs | audio, English ortho |
| [Helsinki Corpus of British English Dialects](https://varieng.helsinki.fi/CoRD/corpora/Dialects/) | locations (UK: East Anglia, South-West England, Lancashire) | 1M toks | audio, English ortho |
| [Nationwide Speech Project (NSP)](https://u.osu.edu/nspcorpus/) ([Clopper & Pisoni 2006](https://www.sciencedirect.com/science/article/abs/pii/S0167639305002232)) | locations (USA) | 60 × 1 hr | audio, partially: English ortho |

## West(ern) Frisian · fry · [west2354](https://glottolog.org/resource/languoid/id/west2354)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [UD Frisian/Dutch Fame](https://github.com/UniversalDependencies/UD_Frisian_Dutch-Fame) ([Braggar & van der Goot 2021](https://aclanthology.org/2021.adaptnlp-1.6/), [Yılmaz ea 2016](https://aclanthology.org/L16-1739/)) | POS (UPOS), dependencies (UD), code-switching. Code-mixed Frisian and Dutch | 400 sents | Frisian​(/Dutch) ortho |
| [Common Voice](https://commonvoice.mozilla.org/en/datasets) (subset) ([Ardila ea 2020](https://aclanthology.org/2020.lrec-1.520/)) | | 150 hrs | audio, Frisian ortho |
| [Frisian AudioMining Enterprise (FAME)](https://www.ru.nl/clst/tools-demos/datasets/) ([Yılmaz ea 2016](https://aclanthology.org/L16-1739/)) | partially: location | 18.5 hrs | audio, Frisian ortho |
| [Recordings of Dutch-Frisian council meetings](https://frisian.eu/dutchfrisiancouncilmeetings/) ([Bentum ea 2022](https://aclanthology.org/2022.lrec-1.107/)) || 26 hrs / 281k toks | audio, Frisian ortho |
| [Corpus Spoken Frisian (KSF)](https://www1.fa.knaw.nl/ksf.html) | | 200 hrs (65 hrs thereof transcribed) | audio, partially: Frisian ortho |
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 641 sents | Frisian ortho |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 72 MB | Frisian ortho |
| [CC-100](https://data.statmt.org/cc-100/) (subset) ([Wenzek ea 2020](https://aclanthology.org/2020.lrec-1.494/)) | uncurated | 174 MB | Frisian ortho |
| [OSCAR](https://oscar-project.org/post/oscar-v22-01/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 75.3 MB / 6.4M toks | Frisian ortho |
| [Wikipedia](https://dumps.wikimedia.org/) ([fy](https://fy.wikipedia.org/wiki/) subset)| uncurated | 50k articles | Frisian ortho |

*UD Frisian/Dutch Fame* is an annotated subset of *FAME.*

## North(ern) Frisian · frr · [north2626](https://glottolog.org/resource/languoid/id/nort2626)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 2.9k sents | ? |
| [Wikipedia](https://dumps.wikimedia.org/) ([frr](https://frr.wikipedia.org/wiki/) subset)| uncurated, partially [tagged with dialect information](https://frr.wikipedia.org/wiki/Kategorie:Spriakwiisen) | 17k articles | [different dialect-based (ad-hoc?) orthographies](https://frr.wikipedia.org/wiki/Wikipedia:Spr%C3%A4kekoordinasjoon) |

## Saterland Frisian/Saterfrisian · stq · [sate1242](https://glottolog.org/resource/languoid/id/sate1242)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) ([stq](https://stq.wikipedia.org/) subset)| uncurated | 4k articles | [revised Kramer orthography for Saterfrisian](https://stq.wikipedia.org/wiki/Wikipedia:H%C3%A4lpe_bie_ju_seelter_Sproake) (unclear if example, recommendation or rule for this wiki) |

## Low Saxon/Low German · nds · [lowg1239](https://glottolog.org/resource/languoid/id/lowg1239)

(The relationship between the ISO 639-3 code and the Glottocode is [complicated](https://github.com/glottolog/glottolog/issues/845).)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [UD Low Saxon LSDC](https://github.com/UniversalDependencies/UD_Low_Saxon-LSDC) ([Siewert ea 2021](https://aclanthology.org/2021.konvens-1.25/)) | POS (UPOS), dependencies (UD), morphological features (UD), glosses (Middle Low Saxon), lemmas, locations | 95 sents | ad-hoc spelling, Nysassiske Sryvwyse |
| [TaPaCo](https://zenodo.org/record/3707949) (subset) [Scherrer 2020](https://aclanthology.org/2020.lrec-1.848/) | paraphrases | 1107 sents | ? |
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | location | 88.9k sents | ad-hoc spelling |
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) (Low German subset) | varieties of Low Saxon, East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio |
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 18.1k sents | ? |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 24 MB | ? |
| [OSCAR](https://oscar-project.org/post/oscar-v22-01/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 9 MB / 1M toks | ? |
| [Wikipedia](https://dumps.wikimedia.org/) ([nds](https://nds.wikipedia.org/) subset)| uncurated partially [tagged with dialect information](https://nds.wikipedia.org/wiki/Kategorie:Artikels_na_Dialekt) | 84k articles | [Sass'sche Schrievwies](https://nds.wikipedia.org/wiki/Wikipedia:Sass) |
| [Wikipedia](https://dumps.wikimedia.org/) ([nds-nl](https://nds-nl.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://nds-nl.wikipedia.org/wiki/Kategorie:Nedersaksies_artikel) | 8k articles | [Nysassiske Skryvwyse (preferred) and Algemene Nedersaksische Schriefwieze (older articles)](https://nds-nl.wikipedia.org/wiki/Wikipedia:Spelling) |


*UD Low Saxon LSDC* is an annotated subset of *LSDC.*
*TaPaCO* is an annotated subset of *Tatoeba.*

## East Frisian Low Saxon · frs · [east2288](https://glottolog.org/resource/languoid/id/east2288)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) (East Frisian Low Saxon subset) | varieties of Low Saxon, East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio |

## Gronings · gos · [gron1242](https://glottolog.org/resource/languoid/id/gron1242)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [TaPaCo](https://zenodo.org/record/3707949) (subset) [Scherrer 2020](https://aclanthology.org/2020.lrec-1.848/) | paraphrases | 122 sents | ? |
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 5.7k sents | ? |

*TaPaCO* is an annotated subset of *Tatoeba.*

## West(ern) Flemish · vls · [vlaa1240](https://glottolog.org/resource/languoid/id/vlaa1240)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Stemmen uit het verleden (annotated subset)](https://dataverse.no/dataset.xhtml?persistentId=doi:10.18710/NSFN2B) ([Lybaert ea 2019](https://www.cambridge.org/core/journals/journal-of-germanic-linguistics/article/corpusbased-analysis-of-v2-variation-in-west-flemish-and-french-flemish-dialects/EAA18DFD4B507EECCAEF90395B60DD95), [Van Keymeulen ea 2019](https://biblio.ugent.be/publication/8629057)) | V2 variation, location | 1.4k sents | phono |
| [Wikipedia](https://dumps.wikimedia.org/) ([vls](https://vls.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://vls.wikipedia.org/wiki/Categorie:Wikipedia:Artikels_noar_dialect) | 8k articles | [Standoardvlams](https://vls.wikipedia.org/wiki/Wikipedia:Gebruuk_van_streektoaln) (orthography developped by vls.wikipedia.org editors) |

## Zeelandic/Zeeuws · zea · [zeeu1238](https://glottolog.org/resource/languoid/id/zeeu1238)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) ([zea](https://zea.wikipedia.org/) subset)| uncurated | 6k articles | ? |

## Moselle Franconian · [luxe1241](https://glottolog.org/resource/languoid/id/luxe1241)

### Luxembourgish · ltz · [luxe1243](https://glottolog.org/resource/languoid/id/luxe1243)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [LuxId](lrec2014.lrec-conf.org/en/shared-lrs/current-list-shared-lrs) ([Lavergne ea 2014](https://aclanthology.org/L14-1573/)) | code-switching (LTZ, DEU, FRA) | 924 sentences (most with LTZ content) | Luxembourgish​(/German/​French) ortho |
| [Tatoeba](https://tatoeba.org/en/downloads) (subset) | some translations into other languages | 884 sents | Luxembourgish ortho |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 81 MB | ? |
| [OSCAR](https://oscar-project.org/post/oscar-v22-01/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 15.8 MB / 1.5M toks | ? |
| [Wikipedia](https://dumps.wikimedia.org/) ([lb](https://lb.wikipedia.org/) subset)| uncurated | 61k articles | Luxembourgish ortho |

### Transylvanian Saxon · [tran1294](https://glottolog.org/resource/languoid/id/tran1294)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Audioatlas siebenbürgisch-sächsischer Dialekte (ASD)](https://clarin.phonetik.uni-muenchen.de/BASRepository/index.php?target=Public/Corpora/ASD/ASD.1.php)) ([University of Munich](http://www.asd.gwi.uni-muenchen.de/index.php)) | 360 hrs / 450k tokens | audio, German ortho, partially phono |

## Colognian · ksh · [kols1241](https://glottolog.org/resource/languoid/id/kols1241)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) ([ksh](https://ksh.wikipedia.org/) subset)| uncurated, Colognian and other varieties of Ripuarian, partially [tagged with dialect and/or orthography information](https://ksh.wikipedia.org/wiki/Saachjrupp:Wikipedia:Atikkel_ier_Shprooche) | 3k articles | [ad-hoc spelling, some articles according to various Ripuarian orthographies](https://ksh.wikipedia.org/wiki/Wikipedia:Schrievwies) |

## Limburgish/Limburgan · lim · [lim1263](https://glottolog.org/resource/languoid/id/limb1263)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) ([li](https://li.wikipedia.org/) subset)| uncurated, partially [tagged with dialect and/or orthography information](https://li.wikipedia.org/wiki/Categorie:Wikipedia:Artikele_nao_dialek) | 14k articles | [Veldeke-sjpelling, Algemein Gesjreve Limburgs](https://li.wikipedia.org/wiki/Wikipedia:Wie_sjrief_ich_Limburgs) |

## Palatine German · pfl · [pala1330](https://glottolog.org/resource/languoid/id/pala1330)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) ([pfl](https://pfl.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://pfl.wikipedia.org/wiki/Sachgrubb:Adiggel_noch_em_Dialegd) | 3k articles | [ad-hoc spelling](https://pfl.wikipedia.org/wiki/Wikipedia_Dischbediere:Schdammdisch) |

## Pennsylvania Dutch · pdc · [penn1240](https://glottolog.org/resource/languoid/id/penn1240)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Wikipedia](https://dumps.wikimedia.org/) (subset)| uncurated | 2k articles | ? |

## Yiddish · yid · west2361[https://glottolog.org/resource/languoid/id/west2361]/[east2295](https://glottolog.org/resource/languoid/id/east2295)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Penn Parsed Corpus of Historical Yiddish](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish) (Santorini 2021) | POS ([Penn-historical](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish/blob/main/doc/annotation-yiddish/annotation.html), phrase structure (Penn-historical) | 200k toks | [partially YIVO transliteration, partially YIVO-inspired ad-hoc transliteration](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish/blob/main/doc/annotation-yiddish/transliteration.html) | New York | 1 hr | audio, transcriptions (partially IPA, partially orthography-based (YIVO-transliteration-based?)) |
| [CABank Yiddish Corpus](https://ca.talkbank.org/access/Yiddish.html) ([Newman 2015](https://benjamins.com/catalog/silv.18.08kah)) | 
| [Wikipedia](https://dumps.wikimedia.org/) (subset)| uncurated | 15k articles | Yiddish ortho |

## German · deu · [stan1295](https://glottolog.org/resource/languoid/id/stan1295)

| Corpus | Notes | Size | Representation |
|--------|-------|------|----------------|
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) (German subset) | varieties of Low Saxon, East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio |
| [Regional Variants of German 1 (RVG1)](https://www.bas.uni-muenchen.de/forschung/Bas/BasRVG1eng.html) ([link2](https://clarin.phonetik.uni-muenchen.de/BASRepository/index.php?target=Public/Corpora/RVG1_CLARIN/RVG1_CLARIN.3.php)) ([Burger & Schiel 1998](https://www.phonetik.uni-muenchen.de/forschung/publikationen/Burger-98-RVG1.pdf)) | unclear whether all of the recordings are in regionally accented (Standard) German or some are in Low Saxon/Bavarian/Colognian/etc. instead | 500 × 1 min spontaneous speech | audio, SAMPA, German ortho |
| Texas German Sample Corpus (TGSC) ([Blevins 2022](https://dataverse.tdl.org/dataset.xhtml?persistentId=doi:10.18738/T8/IOX9ZA)) | | 13.5 hrs / 75k tokens | audio, German ortho |


## Bavarian

https://bar.wikipedia.org/wiki/Kategorie:Artikel_nach_Dialekt

https://bar.wikipedia.org/wiki/Wikipedia:Boarische_Umschrift

## Cimbrian

## Swabian

## Alemannic

https://als.wikipedia.org/wiki/Kategorie:Wikipedia:Dialekt

https://als.wikipedia.org/wiki/Hilfe:Schrybig

## Walser















