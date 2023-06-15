# A Survey of Corpora for Germanic Low-Resource Languages and Dialects

You can read more about this corpus collection [here](https://aclanthology.org/2023.nodalida-1.41/).
If you find this overview useful for your research, please cite:
```
@inproceedings{blaschke-etal-2023-survey,
  title = {A survey of corpora for {G}ermanic low-resource languages and dialects},
  author = {Blaschke, Verena and Sch{\"u}tze, Hinrich and Plank, Barbara},
  year = {2023},
  month = may,
  booktitle = {Proceedings of the 24th Nordic Conference on Computational Linguistics (NoDaLiDa)},
  address = {T{\'o}rshavn, Faroe Islands},
  publisher = {University of Tartu Library},
  url = {https://aclanthology.org/2023.nodalida-1.41},
  pages = {392--414},
}
```

Language varieties:
- [North Germanic](#north-germanic) ([Faroese](#faroese--fao--fao1244) · [(non-std.) Norwegian](#norwegian--nor--norw1258) · [Jutish](#jutish--juti1236) · [East Danish](#east-danish--scan1238) · [Elfdalian](#elfdalianövdalian--ovd--elfd1234) · [(non-std.) Swedish](#swedish--swe--swe1254))
- West Germanic
    - North Sea Germanic
        - [Anglo-Frisian](#anglo-frisian) ([Scots](#scots--sco--scot1243) · [(non-std.) English](#english--eng--stan1293) · [West Frisian](#western-frisian--fry--west2354) · [North Frisian](#northern-frisian--frr--north2626) · [Saterland Frisian](#saterland-frisiansaterfrisian--stq--sate1242))
        - [Low German](#low-german) ([Low Saxon](#low-saxonlow-german--nds--lowg1239) · [East Frisian Low Saxon](#east-frisian-low-saxon--frs--east2288) · [Gronings](#gronings--gos--gron1242) · [Twents](#twents--twd--twen1241) · [Achterhoeks](#achterhoeks--act--acht1238) · [Westphalian](#westphalicwestphalishwestphalian--wep--west2356))
    - [Macro-Dutch](#macro-dutch) ([Dutch](#dutch--nld--dutc1256) · [West Flemish](#western-flemish--vls--vlaa1240) · [Zeelandic](#zeelandiczeeuws--zea--zeeu1238))
    - High German
        - [Middle German](#middle-german) ([Upper Saxon](#upper-saxon--sxu--uppe1400) · [Moselle Franconian incl. Luxembourgish](#moselle-franconian--luxe1241) · [Colognian](#colognian--ksh--kols1241) · [Limburgish](#limburgishlimburgan--lim--lim1263) · [Rhine Franconian incl. Palatine German](#rhinerhenish-franconian--rhin1244) · [Pennsylvania Dutch](#pennsylvania-dutch--pdc--penn1240) · [Yiddish](#yiddish--yid--west2361east2295))
        - [Upper German](#upper-german) ([(non-std.) German](#german--deu--stan1295) · [Upper Franconian](#upperhigh-franconian--uppe1464) · [Bavarian](#bavarian--bar--bava1246) · [Cimbrian](#cimbrian--cim--cimb1238) · [Swabian](#swabian--swg--swab1242) · [Central Alemannic (Swiss German & Alsatian)](#central-alemannic-incl-swiss-german--alsatian--gsw--swis1247) · [Walser](#walser--wae--wals1238))

Inclusion criteria:
- Accessible to researchers
- Can be downloaded (easily)
- No extensive pre-processing required (appropriate file formats; no abundance of OCR errors)
- Full sentences/utterances rather than word lists
- Data are contemporaneous or from the past century
- If only a written version is available, it should be (manually) annotated and/or showcase variation through phone[t/m]ic transcriptions or orthographies used specifically for that language variety

We focus on manual or manually corrected annotations rather than fully automatically annotated data.

The license names link to where the license is mentioned on the corpus website, unless the license is mentioned on the site linked in the first column, in the article accompanying the dataset, or in the downloaded corpus files.

Did we forget a corpus for a Germanic low-resource language or dialect that fits these inclusion criteria? Please reach out to us via a GitHub issue or pull request or an email to `verena DOT blaschke ÄT cis.lmu.de`!

## North Germanic

### Faroese · fao · [fao1244](https://glottolog.org/resource/languoid/id/faro1244)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [UD Faroese OFT](https://github.com/UniversalDependencies/UD_Faroese-OFT) ([Tyers ea 2018](https://aclanthology.org/W18-6017/)) | POS (UPOS, Giellatekno-FAO), dependencies (UD), morpho (UD), lemmas. Contains material from Wikipedia | 1.2k sentences | Faroese ortho | [GNU GPL 2.0, GNU LGPL 2.1, Mozilla Public License 1.1](https://github.com/UniversalDependencies/UD_Faroese-OFT/blob/master/LICENSE.txt) |
| [FarPaHC](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92) ([Ingason ea 2012](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92), [Rögnvalsson ea 2012](https://aclanthology.org/L12-1228/)) | POS (mod. [Penn-historical](https://www.ling.upenn.edu/hist-corpora/annotation/index.html), phrase structure (mod. Penn-historical) | 53k tokens | Faroese ortho | CC BY 4.0 |
| [UD Faroese FarPaHC](https://github.com/UniversalDependencies/UD_Faroese-FarPaHC) ([Ingason ea 2012](https://repository.clarin.is/repository/xmlui/handle/20.500.12537/92), [Rögnvalsson ea 2012](https://aclanthology.org/L12-1228/)) | POS (UPOS), dependencies (UD), morpho (UD) | 40k tokens | Faroese ortho | [CC BY-SA 4.0](https://github.com/UniversalDependencies/UD_Faroese-FarPaHC/blob/master/LICENSE.txt) |
| [Føroyskur talumálsbanki](https://clarino.uib.no/corpuscle-classic/corpus-list) ([Jacobsen 2022](https://septentrio.uit.no/index.php/nordlyd/article/view/6440)) | | 599.9k tokens | Faroese ortho(, audio?) | CLARIN RES-PLAN-BY-PRIV-NORED |
| [FoNE](https://huggingface.co/datasets/vesteinn/sosialurin-faroese-ner) ([Snæbjarnarson ea 2023](https://aclanthology.org/2023.nodalida-1.74/)) | named entities (8 classes). The text overlaps with the BLARK background corpus (Sosialurin subcorpus) | 118k tokens | Faroese ortho | CC BY 4.0 |
| [Fo-STS](https://huggingface.co/datasets/vesteinn/faroese-sts) ([Snæbjarnarson ea 2023](https://aclanthology.org/2023.nodalida-1.74/)) | semantic text similarity (sentence-level), translated subset of the [English STS corpus](http://ixa2.si.ehu.eus/stswiki/index.php/STSbenchmark) ([Cer ea 2017](https://aclanthology.org/S17-2001/)) | 729 sentence pairs | Faroese ortho | CC BY 4.0 |
| [BLARK 1.0](https://maltokni.fo/en/resources) (background corpus) ([Simonsen ea 2022](https://aclanthology.org/2022.lrec-1.495/)) | | 25M tokens | Faroese ortho | CC BY 4.0 |
| [Sprotin translations](https://github.com/Sprotin/translations) | English–Faroese parallel sentences | 126k sentence pairs | Faroese ortho | MIT license |
| [Faroese text collection (FTS)](https://spraakbanken.gu.se/en/resources/fts) | in BLARK 1.0 background corpus | 1.1M tokens | Faroese ortho | CC BY 4.0 |
| [Korp](http://gtweb.uit.no/f_korp/?mode=fao#?lang=en) (Giellatekno) | in BLARK 1.0 background corpus (download via BLARK), contains Wikipedia articles | ? | Faroese ortho | CC BY 4.0 |
| [BLARK 1.0](https://maltokni.fo/en/resources) (audio) ([Simonsen ea 2022](https://aclanthology.org/2022.lrec-1.495/)) | locations (Suðuroy, Sandoy, Suðurstreymoy, Norðurstreymoy/​Eysturoy, Vágar, Norðuroyggjar) | 100 hrs | audio, Faroese ortho, some phono | CC BY 4.0 |
| [Faroese Danish Corpus Hamburg (FADAC Hamburg)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:fadac-0.2.dan) (subset) ([Debess 2019](https://macau.uni-kiel.de/receive/publ_mods_00002318)) | locations (Tórshavn, Vágar, Suðuroy, Eysturoy/​Norðuroyggjar) | 31 hrs | audio, Faroese ortho | [HZSK-RES](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:fadac-0.2.dan#corpus-metadata) |
| [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200) (subset) ([Goyal ea 2022](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00474/110993/The-Flores-101-Evaluation-Benchmark-for-Low), [NLLB Team 2022](https://arxiv.org/abs/2207.04672)) | parallel with ~200 languages | 2k sentences | Faroese ortho | [CC BY-SA 4.0](https://huggingface.co/datasets/facebook/flores) |
| [Tatoeba](https://tatoeba.org/en/downloads) ([fao](https://tatoeba.org/en/sentences/show_all_in/fao/none) subset) | translations into other languages | 417 sentences | Faroese ortho | CC BY 2.0 FR |
| [Ubuntu via OPUS](https://opus.nlpl.eu/Ubuntu.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 20.2k tokens | Faroese ortho | ? |
| [QED via OPUS](https://opus.nlpl.eu/QED.php) ([Abdelali ea 2014](http://www.lrec-conf.org/proceedings/lrec2014/pdf/877_Paper.pdf), [Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 6.4k tokens | Faroese ortho | ? |
| [FC3](https://huggingface.co/datasets/vesteinn/FC3) ([Snæbjarnarson ea 2023](https://aclanthology.org/2023.nodalida-1.74/)) | Faroese subset of CommonCrawl (uncurated) | 98k paragraphs / 9M tokens | Faroese ortho | unspecified CC license |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 102 MB | Faroese ortho | CC BY-SA 3.0 |
| [Wikipedia](https://dumps.wikimedia.org/) ([fo](https://fo.wikipedia.org/) subset) | uncurated | 14k articles | Faroese ortho | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Norwegian · nor · [norw1258](https://glottolog.org/resource/languoid/id/norw1258)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [LIA Treebank](https://github.com/textlab/spoken_norwegian_resources/tree/master/treebanks/Norwegian-NynorskLIA) ([+transcriptions](https://tekstlab.uio.no/LIA/norsk/index_english.html)) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710/)) | POS ([mod](https://tekstlab.uio.no/LIA/pdf/parseretningslinjer-lia12042019.pdf). [NDT](https://tekstlab.uio.no/LIA/pdf/retningslinjer_NDT_norsk.pdf)), dependencies (mod. NDT), morpho (mod. NDT), lemmas, locations (17 places in Norway). Annotated subset of *LIA Norsk* | 7.5k speech segments / 78k tokens | [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) | [CC BY-NC-SA 4.0](https://tekstlab.uio.no/LIA/norsk/index_english.html) |
| [UD Norwegian Nynorsk LIA](https://github.com/UniversalDependencies/UD_Norwegian-NynorskLIA) ([+transcriptions](https://tekstlab.uio.no/LIA/norsk/index_english.html)) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710/)) | POS (UPOS), dependencies (UD), morpho (UD), lemmas, locations (10 places in Norway). Annotated subset of *LIA Norsk* | 5.3k speech segments / 55k tokens | [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) | [treebank: CC BY-SA 4.0](https://github.com/UniversalDependencies/UD_Norwegian-NynorskLIA/blob/master/LICENSE.txt), [transcriptions: CC BY-NC-SA 4.0](https://tekstlab.uio.no/LIA/norsk/index_english.html) |
| [NDC Treebank](https://github.com/textlab/spoken_norwegian_resources/tree/master/treebanks/Norwegian-BokmaalNDC) (+[transcriptions](http://tekstlab.uio.no/scandiasyn/download.html); [website](http://www.tekstlab.uio.no/nota/scandiasyn/treebank.html)) ([Kåsen ea 2022](https://aclanthology.org/2022.lrec-1.516/), [Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | POS ([mod](https://tekstlab.uio.no/LIA/pdf/parseretningslinjer-lia12042019.pdf). [NDT](https://tekstlab.uio.no/LIA/pdf/retningslinjer_NDT_norsk.pdf)), dependencies (mod. NDT), morpho (mod. NDT), lemmas, locations (17 places)| 4.6k speech segments / 66k tokens | Bokmål ortho, [phono](http://www.tekstlab.uio.no/scandiasyn/Transkripsjonsrettleiing%20for%20ScanDiaSyn.pdf) | [treebank](http://www.tekstlab.uio.no/nota/scandiasyn/treebank.html) and [transcriptions](http://tekstlab.uio.no/scandiasyn/download.html): CC BY-NC-SA 4.0 |
| [NorDial](https://github.com/jerbarnes/nordial) (subset) ([Barnes ea 2021](https://aclanthology.org/2021.nodalida-main.51/)) | | 348 tweets | ad-hoc spelling | [CC0 1.0](https://github.com/jerbarnes/nordial/blob/main/LICENSE) |
| NorDial (POS-annotated subset) ([Mæhlum ea 2022](https://aclanthology.org/2022.vardial-1.7/) – contact authors) | POS (UPOS) | 35+ tweets | ad-hoc spelling |
| [Nordic Dialect Corpus](http://tekstlab.uio.no/nota/scandiasyn/) (subset) ([Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | locations (>100 places) | 1.9M tokens | Bokmål ortho, [phono](http://www.tekstlab.uio.no/scandiasyn/Transkripsjonsrettleiing%20for%20ScanDiaSyn.pdf) | [CC BY-NC-SA 4.0](http://www.tekstlab.uio.no/scandiasyn/download.html) |
| [LIA Norsk](https://tekstlab.uio.no/LIA/norsk/index_english.html) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710.pdf)) | locations (222 places) | 3.5M tokens | [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) | CC BY-NC-SA 4.0 |
| [LIA Norsk](https://tekstlab.uio.no/LIA/norsk/index_english.html) (downloadable audio subset) ([Øvrelid ea 2018](https://aclanthology.org/L18-1710.pdf)) | locations (178 places) | ? | audio, [Nynorsk ortho](https://tekstlab.uio.no/LIA/pdf/rettleiing-translitterator.pdf), [phono](https://tekstlab.uio.no/LIA/pdf/transkripsjonsrettleiing_lia.pdf) | CC BY-NC-SA 4.0 |
| [The spoken language investigation in Oslo (TAUS)](http://www.tekstlab.uio.no/nota/taus/english.html) | locations (East vs. West Oslo) | 387k tokens | [Bokmål ortho, phono](http://www.tekstlab.uio.no/nota/oslo/transkripsjon/NoTa-transkripsjonsveil7.pdf) | CC BY-NC-SA 4.0 |
| [American Nordic Speech Corpus (CANS)](https://tekstlab.uio.no/norskiamerika/korpus.html) (subset) ([Johannessen ea 2015](https://aclanthology.org/W15-1840/)) | locations (57 places in USA/Canada) | 773k tokens | Bokmål ortho, [phono](https://tekstlab.uio.no/norskiamerika/Transkripsjons-translittereringsveiledning-norskiamerika.pdf) | CC BY-NC-SA 4.0 |
| [Speech Database for Norwegian (NB Tale)](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-31/) | locations (24 areas) | 365 × 2 mins (spontaneous speech), 7.6k sentences (reading) | audio, Bokmål ortho, mod. X-SAMPA | CC0 |
| [Norwegian Parliamentary Speech Corpus (NPSC)](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-58/) | locations (5 dialect regions) | 140 hrs / 65k sentences / 1.2M tokens | audio, Bokmål/​Nynorsk ortho | CC0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Jutish · [juti1236](https://glottolog.org/resource/languoid/id/juti1236)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Danish Gigaword Corpus](https://gigaword.dk/) (*synne* subset) ([Derczynski ea 2021](https://aclanthology.org/2021.nodalida-main.46/)) | South Jutish | ca. 20k tokens | | CC BY 4.0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### East Danish · [scan1238](https://glottolog.org/resource/languoid/id/scan1238)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Danish Gigaword Corpus](https://gigaword.dk/) (*botxt* subset) ([Derczynski ea 2021](https://aclanthology.org/2021.nodalida-main.46/), [Kjeldsen 2019](https://målogmæle.dk/MoM-arkiv/MoM_40/MoM40_2.pdf#page=22)) | Bornholmsk | ca. 400k tokens | | CC BY 4.0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Elfdalian/Övdalian · ovd · [elfd1234](https://glottolog.org/resource/languoid/id/elfd1234)

Glottolog 4.7 categorizes Elfdalian as a dialect of Dalecarlian/[dale1238](https://glottolog.org/resource/languoid/id/dale1238).

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Nordic Dialect Corpus](http://tekstlab.uio.no/nota/scandiasyn/) (subset) ([Johannessen ea 2009](https://aclanthology.org/W09-4612/)) | locations (7 places) | 15.7k tokens | Elfdalian ortho (Råðdjärum's orthography), Swedish ortho | CC BY-NC-SA 4.0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Swedish · swe · [swe1254](https://glottolog.org/resource/languoid/id/swed1254)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Parallel dialectal-standard Swedish data](https://zenodo.org/record/4060296) ([Hämäläinen ea 2020](https://dl.acm.org/doi/10.1145/3423337.3429435), [Ivars & Södergård 2007](https://jysk.au.dk/fileadmin/www.jysk.au.dk/publikationer/centrets_publikationer/dialektologi.pdf#page=202)) | Finland Swedish (with locations) | 86.5k tokens | transcription, Swedish ortho | CC BY-NC-SA 4.0 |
| [American Nordic Speech Corpus (CANS)](https://tekstlab.uio.no/norskiamerika/korpus.html) (subset) ([Johannessen ea 2015](https://aclanthology.org/W15-1840/)) | locations (7 places in the US) | 46k tokens | Swedish ortho, [phono](https://tekstlab.uio.no/norskiamerika/CANS-f%C3%B6r-svensk.pdf) | CC BY-NC-SA 4.0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

## Anglo-Frisian

### Scots · sco · [scot1243](https://glottolog.org/resource/languoid/id/scot1243)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [POS-tagged Scots corpus](https://github.com/Hfkml/pos-tagged-scots-corpus) ([Lameris & Stymne 2021](https://aclanthology.org/2021.vardial-1.5/)) | POS (UPOS); overlaps with the *SCOTS* corpus | 1k tokens || partially ad hoc (SCOTS), partially with a standardized orthography (Mak Forrit) | ? |
| [Scottish Corpus of Texts & Speech (SCOTS)](https://scottishcorpus.ac.uk/) (subset) ([Anderson ea 2007](https://link.springer.com/chapter/10.1057/9780230223936_2)) | partially annotated in the *POS-tagged Scots corpus* | unknown (4.6M tokens total) | mix of ad-hoc spelling and English ortho | [custom](https://scottishcorpus.ac.uk/terms-and-conditions/) |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 35 MB | ? | CC BY-SA 3.0 |
| [Wikipedia](https://dumps.wikimedia.org/) ([sco](https://sco.wikipedia.org/) subset) | uncurated, see also [here](https://www.theguardian.com/uk-news/2020/aug/26/shock-an-aw-us-teenager-wrote-huge-slice-of-scots-wikipedia) and [here](https://slate.com/technology/2020/09/scots-wikipedia-language-american-teenager.html) | 39k articles | [Scots spelling recommendations](https://sco.wikipedia.org/wiki/Wikipedia:Spellin_an_grammar) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### English · eng · [stan1293](https://glottolog.org/resource/languoid/id/stan1293)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [TwitterAAE-UD](https://slanglab.cs.umass.edu/TwitterAAE/) ([Blodgett ea 2016](https://slanglab.cs.umass.edu/TwitterAAE/)) | dependencies (UD); AAVE | 250 tweets | ad-hoc spelling | |
| [Diachronic Electronic Corpus of Tyneside English (DECTE) (Corrigan ea 2012](https://research.ncl.ac.uk/decte/index.htm) | locations (19 places in NE England). Contains the Newcastle Electronic Corpus of Tyneside English ([NECTE](https://research.ncl.ac.uk/necte/)) and [NECTE2](https://research.ncl.ac.uk/decte/necte2.htm), and NECTE in turn contains the Tyneside Linguistic Survey ([TLS](https://research.ncl.ac.uk/decte/tls.htm)) and the Phonological Variation and Change in Contemporary Spoken English ([PVC](https://research.ncl.ac.uk/decte/pvc.htm)) corpus.| 72 hrs / 804k tokens | audio, English ortho, partially: [phono](https://research.ncl.ac.uk/decte/representation.htm) | [custom](https://research.ncl.ac.uk/decte/corpus.htm) |
| [Intonational Variation in English (IViE)](http://www.phon.ox.ac.uk/files/apps/IViE/) ([Nolan & Post 2013](https://research.ncl.ac.uk/decte/representation.htm)) | locations (British Isles: Belfast, Dublin, Newcastle, Leeds, Bradford, Liverpool, Cambridge, Cardiff, London) | 36 hrs | audio, English ortho | [custom](http://www.phon.ox.ac.uk/files/apps/IViE/download1.php#dis) |
| [Crowdsourced high-quality UK and Ireland English Dialect speech data set](https://openslr.org/83) ([Demirsahin ea 2020](https://aclanthology.org/2020.lrec-1.804/)) | locations (British Isles: Ireland, Midlands, Northern England, Scotland, Southern England, Wales) | 31 hrs | audio, English ortho | [CC BY-SA 4.0](https://www.openslr.org/resources/83/LICENSE) |
| [Helsinki Corpus of British English Dialects](https://varieng.helsinki.fi/CoRD/corpora/Dialects/) | locations (UK: Cambridgeshire, Devon, Essex/Lancashire, Isle of Ely, Somerset, Suffolk) | 1M tokens | audio, English ortho | |
| [Nationwide Speech Project (NSP)](https://u.osu.edu/nspcorpus/) ([Clopper & Pisoni 2006](https://www.sciencedirect.com/science/article/abs/pii/S0167639305002232)) | locations (USA: West, Midland, North, South, New England, Mid-Atlantic) | 60 × 1 hr | audio, partially: English ortho |
| [Corpus of Regional African American Language (CORAAL) (Kendall & Farrington 2021)](https://oraal.uoregon.edu/coraal) | 6 locations, AAVE | 135.6 hrs / 1.5M tokens | audio, English ortho | CC BY-NC-SA 4.0 |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### West(ern) Frisian · fry · [west2354](https://glottolog.org/resource/languoid/id/west2354)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [UD Frisian/Dutch Fame](https://github.com/UniversalDependencies/UD_Frisian_Dutch-Fame) ([Braggar & van der Goot 2021](https://aclanthology.org/2021.adaptnlp-1.6/), [Yılmaz ea 2016](https://aclanthology.org/L16-1739/)) | POS (UPOS), dependencies (UD), code-switching; code-mixed Frisian and Dutch. Annotated subset of *FAME.* | 400 sentences | Frisian​(/Dutch) ortho | [CC BY-SA 4.0](https://github.com/UniversalDependencies/UD_Frisian_Dutch-Fame/blob/master/LICENSE.txt) |
| [UD Frisian Frysk](https://github.com/UniversalDependencies/UD_Frisian-Frysk) ([Heeringa ea 2021](https://arxiv.org/abs/2107.07974)) | under development!; POS (UPOS), dependencies (UD), morpho (UD), lemmas | 2.9k sentences | Frisian ortho | [CC BY-SA 3.0](https://github.com/UniversalDependencies/UD_Frisian-Frysk/blob/master/LICENSE.txt) |
| [Common Voice](https://commonvoice.mozilla.org/en/datasets) (subset) ([Ardila ea 2020](https://aclanthology.org/2020.lrec-1.520/)) | | 150 hrs | audio, Frisian ortho | CC0 |
| [Frisian AudioMining Enterprise (FAME)](https://www.ru.nl/clst/tools-demos/datasets/) ([Yılmaz ea 2016](https://aclanthology.org/L16-1739/)) | partially: locations | 18.5 hrs | audio, Frisian ortho | |
| [Recordings of Dutch-Frisian council meetings](https://frisian.eu/dutchfrisiancouncilmeetings/) ([Bentum ea 2022](https://aclanthology.org/2022.lrec-1.107/)) || 26 hrs / 281k tokens | audio, Frisian ortho | |
| [Corpus Spoken Frisian / Korpus Sprutsen Frysk (KSF)](https://www1.fa.knaw.nl/ksf.html) | | 200 hrs (65 hrs thereof transcribed) | audio, partially: Frisian ortho | |
| [Boarnsterhim Corpus (BHC)](https://taalmaterialen.ivdnt.org/download/tstc-boarnsterhimcorpus1-0/) (subset) ([Sloos ea 2018](https://aclanthology.org/L18-1232/)) | under revision! | unknown (250 hrs total, with Dutch) | audio | |
| [Tatoeba](https://tatoeba.org/en/downloads) ([fry](https://tatoeba.org/en/sentences/show_all_in/fry/none) subset) | translations into other languages | 641 sentences | Frisian ortho | CC BY 2.0 FR |
| [Ubuntu via OPUS](https://opus.nlpl.eu/Ubuntu.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 22.4k tokens | Frisian ortho | |
| [KDE4 via OPUS](https://opus.nlpl.eu/KDE4-v2.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | ca. 300k tokens | Frisian ortho | |
| [GNOME via OPUS](https://opus.nlpl.eu/GNOME.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 55.7k tokens | Frisian ortho | |
| [Mozilla-I10n](https://github.com/mozilla-l10n/mt-training-data) | translations into other languages | ca. 400k tokens | Frisian ortho | Mozilla Public License 2.0 |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 72 MB | Frisian ortho | CC BY-SA 3.0 |
| [CC-100](https://data.statmt.org/cc-100/) (subset) ([Wenzek ea 2020](https://aclanthology.org/2020.lrec-1.494/)) | uncurated | 174 MB | Frisian ortho | |
| [OSCAR](https://oscar-project.github.io/documentation/versions/oscar-2301/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 9.9M tokens / 70.4 MB | Frisian ortho | [Metadata/annotations: CC0 1.0](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), [Common Crawl: custom](https://commoncrawl.org/terms-of-use/) |
| [Wikipedia](https://dumps.wikimedia.org/) ([fy](https://fy.wikipedia.org/wiki/) subset)| uncurated | 50k articles | Frisian ortho | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### North(ern) Frisian · frr · [north2626](https://glottolog.org/resource/languoid/id/nort2626)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Tatoeba](https://tatoeba.org/en/downloads) ([frr](https://tatoeba.org/en/sentences/show_all_in/frr/none) subset) | translations into other languages | 2.9k sentences | ? | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) ([frr](https://frr.wikipedia.org/wiki/) subset)| uncurated, partially [tagged with dialect information](https://frr.wikipedia.org/wiki/Kategorie:Spriakwiisen) | 17k articles | [different dialect-based (ad-hoc?) orthographies](https://frr.wikipedia.org/wiki/Wikipedia:Spr%C3%A4kekoordinasjoon) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Saterland Frisian/Saterfrisian · stq · [sate1242](https://glottolog.org/resource/languoid/id/sate1242)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Tatoeba](https://tatoeba.org/en/downloads) ([stq](https://tatoeba.org/en/sentences/show_all_in/stq/none) subset) | translations into other languages | 96 sentences | ? | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) ([stq](https://stq.wikipedia.org/) subset)| uncurated | 4k articles | [revised Kramer orthography for Saterfrisian](https://stq.wikipedia.org/wiki/Wikipedia:H%C3%A4lpe_bie_ju_seelter_Sproake) (unclear if example, recommendation or rule for this wiki) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

## Low German

### Low Saxon/Low German · nds · [lowg1239](https://glottolog.org/resource/languoid/id/lowg1239)

(The relationship between the ISO 639-3 code and the Glottocode is [complicated](https://github.com/glottolog/glottolog/issues/845).)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [UD Low Saxon LSDC](https://github.com/UniversalDependencies/UD_Low_Saxon-LSDC) ([Siewert ea 2021](https://aclanthology.org/2021.konvens-1.25/)) | POS (UPOS), dependencies (UD), morphological features (UD), glosses (Middle Low Saxon), lemmas, locations (18 dialect areas, see also *LSDC* note); overlaps with *LSDC* | 95 sentences | ad-hoc spelling, Nysassiske Sryvwyse | [CC BY-SA 4.0](https://github.com/UniversalDependencies/UD_Low_Saxon-LSDC/blob/master/LICENSE.txt) |
| [TaPaCo](https://zenodo.org/record/3707949) (subset) ([Scherrer 2020](https://aclanthology.org/2020.lrec-1.848/)) | paraphrases; annotated subset of *Tatoeba* | 1107 sentences | ? | CC BY 2.0 |
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | locations (15 dialect areas); overlaps with *UD Low Saxon LSDC*; also contains FRS, WEP, TWD, ACT content | 88.9k sentences (incl. FRS etc.) | ad-hoc spelling | [CC BY-NC-SA 4.0](https://github.com/Helsinki-NLP/LSDC/blob/main/LICENSE) |
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) ([Schröder 2011](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin), [Elmentaler ea 2015](https://www.degruyter.com/document/doi/10.1515/9783110363449-018/html)) (Low German subset) | varieties of Low Saxon (Nordhannoversch, Emsländisch Oldenburgisch), East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio | [HZSK-RES](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin#corpus-metadata) |
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | locations | 80 min / 10.7k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |
| [Tatoeba](https://tatoeba.org/en/downloads) ([nds](https://tatoeba.org/en/sentences/show_all_in/nds/none) subset) | translations into other languages | 18.1k sentences | ? | CC BY 2.0 FR |
| [Ubuntu via OPUS](https://opus.nlpl.eu/Ubuntu.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 35.3k tokens |  | ? |
| [KDE4 via OPUS](https://opus.nlpl.eu/KDE4-v2.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 1.1M tokens |  | ? |
| [GNOME via OPUS](https://opus.nlpl.eu/GNOME.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | ca. 700k tokens |  | ? |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 24 MB | ? | CC BY-SA 3.0 |
| [OSCAR](https://oscar-project.github.io/documentation/versions/oscar-2301/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 1.6M tokens / 10.7 MB | ? |[Metadata/annotations: CC0 1.0](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), [Common Crawl: custom](https://commoncrawl.org/terms-of-use/) |
| [Wikipedia](https://dumps.wikimedia.org/) ([nds](https://nds.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://nds.wikipedia.org/wiki/Kategorie:Artikels_na_Dialekt) | 84k articles | [Sass'sche Schrievwies](https://nds.wikipedia.org/wiki/Wikipedia:Sass) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |
| [Wikipedia](https://dumps.wikimedia.org/) ([nds-nl](https://nds-nl.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://nds-nl.wikipedia.org/wiki/Kategorie:Nedersaksies_artikel) | 8k articles | [Nysassiske Skryvwyse (preferred) and Algemene Nedersaksische Schriefwieze (older articles)](https://nds-nl.wikipedia.org/wiki/Wikipedia:Spelling) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### East Frisian Low Saxon · frs · [east2288](https://glottolog.org/resource/languoid/id/east2288)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) (East Frisian Low Saxon subset) | varieties of Low Saxon, East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio | [HZSK-RES](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin#corpus-metadata) |
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) (OFR subset) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | minor overlaps with *UD Low Saxon LSDC* | 240 sentences | ad-hoc spelling | [CC BY-NC-SA 4.0](https://github.com/Helsinki-NLP/LSDC/blob/main/LICENSE) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Gronings · gos · [gron1242](https://glottolog.org/resource/languoid/id/gron1242)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [TaPaCo](https://zenodo.org/record/3707949) (subset) [Scherrer 2020](https://aclanthology.org/2020.lrec-1.848/) | paraphrases; annotated subset of *Tatoeba* | 122 sentences | ? |
| [Tatoeba](https://tatoeba.org/en/downloads) ([gos](https://tatoeba.org/en/sentences/show_all_in/gos/none) subset) | translations into other languages | 5.7k sentences | ? | CC BY 2.0 FR |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Twents · twd · [twen1241](https://glottolog.org/resource/languoid/id/twen1241)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) (TWE subset) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | minor overlaps with *UD Low Saxon LSDC* | 668 sentences | ad-hoc spelling | [CC BY-NC-SA 4.0](https://github.com/Helsinki-NLP/LSDC/blob/main/LICENSE) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Achterhoeks · act · [acht1238](https://glottolog.org/resource/languoid/id/acht1238)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) (ACH subset) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | minor overlaps with *UD Low Saxon LSDC* | 988 sentences | ad-hoc spelling | [CC BY-NC-SA 4.0](https://github.com/Helsinki-NLP/LSDC/blob/main/LICENSE) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Westphalic/Westphalish/Westphalian · wep · [west2356](https://glottolog.org/resource/languoid/id/west2356)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | | 15 min / 2.4k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |
| [Low Saxon Dialect Classification (LSDC)](https://github.com/Helsinki-NLP/LSDC/) (OWL subset) ([Siewert ea 2020](https://aclanthology.org/2020.vardial-1.3/)) | minor overlaps with *UD Low Saxon LSDC* | 15k sentences | ad-hoc spelling | [CC BY-NC-SA 4.0](https://github.com/Helsinki-NLP/LSDC/blob/main/LICENSE) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

## Macro-Dutch

### Dutch · nld · [dutc1256](https://glottolog.org/resource/languoid/id/dutc1256)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Corpus of Southern Dutch Dialects (GCND)](https://www.gcnd.ugent.be/en/about-the-gcnd/) ([Breitbarth ea 2018](https://openjournals.ugent.be/kzm/article/id/71958/)) | under construction!; might also include West Flemish, Zeelandic, and/or Limburgs | | audio, [transcriptions](https://www.gcnd.ugent.be/wp-content/uploads/2022/11/2022_10_06_Transcriptieprotocol.pdf) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### West(ern) Flemish · vls · [vlaa1240](https://glottolog.org/resource/languoid/id/vlaa1240)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Stemmen uit het verleden (annotated subset)](https://dataverse.no/dataset.xhtml?persistentId=doi:10.18710/NSFN2B) ([Lybaert ea 2019](https://www.cambridge.org/core/journals/journal-of-germanic-linguistics/article/corpusbased-analysis-of-v2-variation-in-west-flemish-and-french-flemish-dialects/EAA18DFD4B507EECCAEF90395B60DD95), [Van Keymeulen ea 2019](https://biblio.ugent.be/publication/8629057)) | V2 variation, locations (25 places) | 1.4k sentences | phono | CC BY-NC 4.0 |
| [Wikipedia](https://dumps.wikimedia.org/) ([vls](https://vls.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://vls.wikipedia.org/wiki/Categorie:Wikipedia:Artikels_noar_dialect) | 8k articles | [Standoardvlams](https://vls.wikipedia.org/wiki/Wikipedia:Gebruuk_van_streektoaln) (orthography developped by vls.wikipedia.org editors) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Zeelandic/Zeeuws · zea · [zeeu1238](https://glottolog.org/resource/languoid/id/zeeu1238)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Wikipedia](https://dumps.wikimedia.org/) ([zea](https://zea.wikipedia.org/) subset)| uncurated | 6k articles | ? | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

## Middle German

### Upper Saxon · sxu · [uppe1400](https://glottolog.org/resource/languoid/id/uppe1400)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| SXUCorpus ([Herms ea 2016](https://aclanthology.org/L16-1736/)) (contact authors) | 8 locations | 500 min / 70 k tokens | German ortho |  |
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | | 12 min / 1.7k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Moselle Franconian · [luxe1241](https://glottolog.org/resource/languoid/id/luxe1241)

#### Luxembourgish · ltz · [luxe1243](https://glottolog.org/resource/languoid/id/luxe1243)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Banking Client Support (BCS) Dataset](https://github.com/Trustworthy-Software/BCS-dataset) ([Lothritz ea 2021](https://orbilu.uni.lu/handle/10993/47529)) | intent detection, slot filling, parallel with DEU, FRA, ENG | 1k sentences | Luxembourgish ortho | ? |
| [Luxembourgish translation of Winograd Natural Language Inference (L-WNLI)](https://github.com/Trustworthy-Software/LuxemBERT) ([Lothritz ea 2022](https://aclanthology.org/2022.lrec-1.543/)) | NLI, [parallel with other languages](https://cs.nyu.edu/~davise/papers/WinogradSchemas/WS.html) ([Levesque ea 2012](https://dl.acm.org/doi/10.5555/3031843.3031909)) | 767 samples | Luxembourgish ortho | ? |
| Luxembourgish POS and NER ([Lothritz ea 2022](https://aclanthology.org/2022.lrec-1.543/)) ([contact authors](https://github.com/Trustworthy-Software/LuxemBERT)) | POS tags (15 tags), NER (PER, ORG, LOC, GPE, MISC) | 5.5k sentences | Luxembourgish ortho | ? |
| Luxembourgish news classification ([Lothritz ea 2022](https://aclanthology.org/2022.lrec-1.543/)) ([contact authors](https://github.com/Trustworthy-Software/LuxemBERT)) | 8 classes | 10k articles | Luxembourgish ortho | ? |
| [LuxId](http://lrec2014.lrec-conf.org/en/shared-lrs/current-list-shared-lrs) ([Lavergne ea 2014](https://aclanthology.org/L14-1573/)) | code-switching (LTZ, DEU, FRA) | 924 sentences (most with LTZ content) | Luxembourgish​(/German/​French) ortho | CC BY-SA 3.0 |
| [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200) (subset) ([Goyal ea 2022](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00474/110993/The-Flores-101-Evaluation-Benchmark-for-Low), [NLLB Team 2022](https://arxiv.org/abs/2207.04672)) | parallel with ~200 languages | 2k sentences | Luxembourgish ortho | [CC BY-SA 4.0](https://huggingface.co/datasets/facebook/flores) |
| [Tatoeba](https://tatoeba.org/en/downloads) ([ltz](https://tatoeba.org/en/sentences/show_all_in/ltz/none) subset) | translations into other languages | 884 sentences | Luxembourgish ortho | CC BY 2.0 FR |
| [Ubuntu via OPUS](https://opus.nlpl.eu/Ubuntu.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 17k tokens | Luxembourgish ortho | ? |
| [KDE4 via OPUS](https://opus.nlpl.eu/KDE4-v2.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 28.8k tokens | Luxembourgish ortho | ? |
| [Mozilla-I10n](https://github.com/mozilla-l10n/mt-training-data) | translations into other languages | 6.9k tokens | Luxembourgish ortho | Mozilla Public License 2.0 |
| [QED via OPUS](https://opus.nlpl.eu/QED.php) ([Abdelali ea 2014](http://www.lrec-conf.org/proceedings/lrec2014/pdf/877_Paper.pdf), [Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 19.2k tokens | Luxembourgish ortho | ? |
| [TED2020 via OPUS](https://opus.nlpl.eu/TED2020.php) ([Reimers & Gurevych](https://aclanthology.org/2020.emnlp-main.365/), [Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 1.7k tokens | Luxembourgish ortho | [CC BY-NC-ND 4.0](https://www.ted.com/about/our-organization/our-policies-terms/ted-talks-usage-policy) |
| [Web to Corpus (W2C)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) (subset) ([Majliš 2011](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9), [Majliš & Žabokrtský 2012](https://aclanthology.org/L12-1110/)) | uncurated | 81 MB | ? | CC BY-SA 3.0 |
| [OSCAR](https://oscar-project.github.io/documentation/versions/oscar-2301/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 2.5M tokens / 18.4 MB | ? |[Metadata/annotations: CC0 1.0](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), [Common Crawl: custom](https://commoncrawl.org/terms-of-use/) |
| [Wikipedia](https://dumps.wikimedia.org/) ([lb](https://lb.wikipedia.org/) subset)| uncurated | 61k articles | Luxembourgish ortho | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

#### Transylvanian Saxon · [tran1294](https://glottolog.org/resource/languoid/id/tran1294)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Audioatlas siebenbürgisch-sächsischer Dialekte (ASD)](https://clarin.phonetik.uni-muenchen.de/BASRepository/index.php?target=Public/Corpora/ASD/ASD.1.php) ([University of Munich](http://www.asd.gwi.uni-muenchen.de/index.php)) | | 360 hrs / 450k tokens | audio, German ortho, partially phono | CLARIN RES |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Colognian · ksh · [kols1241](https://glottolog.org/resource/languoid/id/kols1241)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Tatoeba](https://tatoeba.org/en/downloads) ([ksh](https://tatoeba.org/en/sentences/show_all_in/ksh/none) subset) | translations into other languages | 82 sentences | ? | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) ([ksh](https://ksh.wikipedia.org/) subset)| uncurated, Colognian and other varieties of Ripuarian, partially [tagged with dialect and/or orthography information](https://ksh.wikipedia.org/wiki/Saachjrupp:Wikipedia:Atikkel_ier_Shprooche) | 3k articles | [ad-hoc spelling, some articles according to various Ripuarian orthographies](https://ksh.wikipedia.org/wiki/Wikipedia:Schrievwies) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Limburgish/Limburgan · lim · [lim1263](https://glottolog.org/resource/languoid/id/limb1263)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200) (subset) ([Goyal ea 2022](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00474/110993/The-Flores-101-Evaluation-Benchmark-for-Low), [NLLB Team 2022](https://arxiv.org/abs/2207.04672)) | parallel with ~200 languages; Maastrichtian Limburgs | 2k sentences |  | [CC BY-SA 4.0](https://huggingface.co/datasets/facebook/flores) |
| [Ubuntu via OPUS](https://opus.nlpl.eu/Ubuntu.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | 18.4k tokens |  | ? |
| [GNOME via OPUS](https://opus.nlpl.eu/GNOME.php) ([Tiedemann 2012](https://aclanthology.org/L12-1246/)) | translations into other languages | ca. 400k tokens |  | ? |
| [Wikipedia](https://dumps.wikimedia.org/) ([li](https://li.wikipedia.org/) subset)| uncurated, partially [tagged with dialect and/or orthography information](https://li.wikipedia.org/wiki/Categorie:Wikipedia:Artikele_nao_dialek) | 14k articles | [Veldeke-sjpelling, Algemein Gesjreve Limburgs](https://li.wikipedia.org/wiki/Wikipedia:Wie_sjrief_ich_Limburgs) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Rhine/Rhenish Franconian · [rhin1244](https://glottolog.org/resource/languoid/id/rhin1244)

Includes Palatin(at)e German · pfl · [pala1330](https://glottolog.org/resource/languoid/id/pala1330).

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | Hessian | 8 min / 1.4k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |
| [Wikipedia](https://dumps.wikimedia.org/) ([pfl](https://pfl.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://pfl.wikipedia.org/wiki/Sachgrubb:Adiggel_noch_em_Dialegd); contains articles in Palatine German, Lorraine Franconian, Hessian | 3k articles | [(implied) ad-hoc spelling](https://pfl.wikipedia.org/wiki/Wikipedia_Dischbediere:Schdammdisch) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Pennsylvania Dutch · pdc · [penn1240](https://glottolog.org/resource/languoid/id/penn1240)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Tatoeba](https://tatoeba.org/en/downloads) ([pdc](https://tatoeba.org/en/sentences/show_all_in/pdc/none) subset) | translations into other languages | 57 sentences | ? | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) ([pdc](https://pdc.wikipedia.org/) subset)| uncurated | 2k articles | ? | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Yiddish · yid · [west2361](https://glottolog.org/resource/languoid/id/west2361)/[east2295](https://glottolog.org/resource/languoid/id/east2295)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Penn Parsed Corpus of Historical Yiddish (Santorini 2021)](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish) | POS ([Penn-historical](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish/blob/main/doc/annotation-yiddish/annotation.html), phrase structure (Penn-historical) | 200k tokens | [partially YIVO transliteration, partially YIVO-inspired ad-hoc transliteration](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish/blob/main/doc/annotation-yiddish/transliteration.html) | [CC BY-NC-SA 4.0](https://github.com/beatrice57/penn-parsed-corpus-of-historical-yiddish/blob/main/LICENSE.rst) |
| [CABank Yiddish Corpus](https://ca.talkbank.org/access/Yiddish.html) ([Newman 2015](https://benjamins.com/catalog/silv.18.08kah)) | New York | 1 hr | audio, transcriptions (partially IPA, partially orthography-based (YIVO-transliteration-based?)) | [CC BY-NC-SA 3.0](https://talkbank.org/share/rules.html) |
| [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200) (subset) ([Goyal ea 2022](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00474/110993/The-Flores-101-Evaluation-Benchmark-for-Low), [NLLB Team 2022](https://arxiv.org/abs/2207.04672)) | parallel with ~200 languages; Eastern Yiddish (Hasidic) | 2k sentences |  | [CC BY-SA 4.0](https://huggingface.co/datasets/facebook/flores) |
| [OSCAR](https://oscar-project.github.io/documentation/versions/oscar-2301/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 14.3M tokens / 171.7 MB | ? |[Metadata/annotations: CC0 1.0](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), [Common Crawl: custom](https://commoncrawl.org/terms-of-use/) |
| [Wikipedia](https://dumps.wikimedia.org/) ([yi](https://yi.wikipedia.org/) subset)| uncurated | 15k articles | | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

## Upper German

### German · deu · [stan1295](https://glottolog.org/resource/languoid/id/stan1295)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Sprachvariation in Norddeutschland (SiN, Hamburg collection)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin) ([Schröder 2011](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin), [Elmentaler ea 2015](https://www.degruyter.com/document/doi/10.1515/9783110363449-018/html)) (German subset) | varieties of Low Saxon, East Frisian Low Saxon and (Northern) German | unknown (300 hrs total) | audio | [HZSK-RES](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:sin#corpus-metadata) |
| [Regional Variants of German 1 (RVG1)](https://www.bas.uni-muenchen.de/forschung/Bas/BasRVG1eng.html) (+[link2](https://clarin.phonetik.uni-muenchen.de/BASRepository/index.php?target=Public/Corpora/RVG1_CLARIN/RVG1_CLARIN.3.php)) ([Burger & Schiel 1998](https://www.phonetik.uni-muenchen.de/forschung/publikationen/Burger-98-RVG1.pdf)) | unclear whether all of the recordings are in regionally accented (Standard) German or some are in Low Saxon/Bavarian/Colognian/etc. instead | 500 × 1 min spontaneous speech | audio, phono (SAMPA), German ortho | CLARIN ACA |
| [Texas German Sample Corpus (TGSC) (Blevins 2022)](https://dataverse.tdl.org/dataset.xhtml?persistentId=doi:10.18738/T8/IOX9ZA) | | 13.5 hrs / 75k tokens | audio, German ortho | CC0 1.0 |
| [Wenkersätze](https://github.com/engsterhold/wenker-storage) (Wenker 1889–1923: Sprachatlas des Deutschen Reichs. Handdrawn by Emil Maurmann, Georg Wenker and Ferdinand Wrede. Published online as [Digitaler Wenker-Atlas](https://regionalsprache.de/home.aspx), [Schmidt ea 2020-](https://regionalsprache.de/)) | 40 German sentences, translated into various lects spoken in the German Reich at the turn of the century | 40 sentences × 2210 samples | various phonetic transcription styles and ad-hoc spellings | [CC BY-SA 4.0](https://apps.dsa.info/wenker/) | 

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Upper/High Franconian · [uppe1464](https://glottolog.org/resource/languoid/id/uppe1464)

Including East Franconian · vmf · [main1267](https://glottolog.org/resource/languoid/id/main1267).

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | South Franconian and East Franconian | South: 10 min / 1.6k tokens; East: between 13 and 26 min / between 1.9k and 2.3k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |

### Bavarian · bar · [bava1246](https://glottolog.org/resource/languoid/id/bava1246)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Kontatto](https://kontatti.projects.unibz.it/) ([Dal Negro & Ciccolone 2020](https://www.degruyter.com/document/doi/10.1515/soci-2020-0014/html)) | POS (unknown), lemmas (German) | 147k tokens | audio, phono | [custom](https://kontatti.projects.unibz.it/what-is-kontatti/conditions-of-use/) |
| [xSID/SID4LR](https://bitbucket.org/robvanderg/sid4lr/src/master/) ([van der Goot ea 2021](https://aclanthology.org/2021.naacl-main.197/); [Aepli ea 2023](https://aclanthology.org/2023.vardial-1.25/)) (de-st subset) | slot filling, intent detection, translations into 14 languages; South Tyrolean | 800 sentences | ad-hoc pronunciation spelling | [CC BY-SA 4.0](https://bitbucket.org/robvanderg/xsid/src/master/LICENSE) |
| [DIDI - The DiDi Corpus of South Tyrolean CMC 1.0.0 (Frey ea 2019)](https://clarin.eurac.edu/repository/xmlui/handle/20.500.12124/7) (subset) | South Tyrolean | unknown (600k tokens total) | ad-hoc pronunciation spelling | CLARIN ACA-BY-NC-NORED |
| [Kontatti](https://kontatti.projects.unibz.it/) ([Ghilardi 2019](https://hrcak.srce.hr/231238)) (subset) | South Tyrolean | unknown (6:48 hrs total) | audio, German ortho | [custom](https://kontatti.projects.unibz.it/what-is-kontatti/conditions-of-use/) |
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | | between 21 and 34 min / between 2.7k and 3.2k tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |
| [Tatoeba](https://tatoeba.org/en/downloads) ([bar](https://tatoeba.org/en/sentences/show_all_in/bar/none) subset) | translations into other languages | 226 sentences | ad-hoc pronunciation spelling | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) ([bar](https://bar.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://bar.wikipedia.org/wiki/Kategorie:Artikel_nach_Dialekt) | 27k articles | [ad-hoc pronunciation spelling with some optional conventions](https://bar.wikipedia.org/wiki/Wikipedia:Wia_schreib_i_a_guads_Boarisch%3F) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Cimbrian · cim · [cimb1238](https://glottolog.org/resource/languoid/id/cimb1238)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Kontatti](https://kontatti.projects.unibz.it/) ([Ghilardi 2019](https://hrcak.srce.hr/231238)) (subset) |  | unknown (6:48 hrs total) | audio, German ortho | [custom](https://kontatti.projects.unibz.it/what-is-kontatti/conditions-of-use/) |


[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Swabian · swg · [swab1242](https://glottolog.org/resource/languoid/id/swab1242) 

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Tatoeba](https://tatoeba.org/en/downloads) ([swg](https://tatoeba.org/en/sentences/show_all_in/swg/none) subset) | translations into other languages | 1.9k sentences | ad-hoc pronunciation spelling | CC BY 2.0 FR |
| [Wikipedia](https://dumps.wikimedia.org/) (subset of [als](https://als.wikipedia.org/) subset)| uncurated | [927 (of 27k) articles tagged as Swabian](https://als.wikipedia.org/wiki/Kategorie:Wikipedia:Dialekt) | [no defined standard, but a set of recommendations based on published works, the (Swiss German) Dieth orthography and the (Alsatian) Orthal orthography](https://als.wikipedia.org/wiki/Hilfe:Schrybig) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Central Alemannic (incl. Swiss German & Alsatian) · gsw · [swis1247](https://glottolog.org/resource/languoid/id/swis1247)


| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [Annotated Corpus for the Alsatian Dialects](https://zenodo.org/record/2536041#.YvIZrvFByKc) (Bernhard ea [2018](https://hal.science/hal-01704806), [2019](https://zenodo.org/record/2536041)) | POS (UPOS, mod. UPOS), lemmas, glosses (French); Alsatian; overlap with Wikipedia | 798 sentences | ad-hoc pronunciation spelling | CC BY-SA 4.0 |
| [BISAME GSW](https://www.ortolang.fr/market/corpora/bisame_gsw/v1) ([STIH 2020](https://www.ortolang.fr/market/corpora/bisame_gsw/v1), [Millour & Fort 2018](https://hal.science/hal-01995758)) | POS (mod. UPOS); Alsatian | 382 sentences | ad-hoc pronunciation spelling | CC BY-NC-SA 3.0 FR |
| [NOAH's corpus](https://github.com/noe-eva/NOAH-Corpus/) ([Hollenstein & Aepli 2015](https://www.zora.uzh.ch/id/eprint/174601/)) | POS ([mod.](https://github.com/noe-eva/NOAH-Corpus/blob/master/guidelines.md) [STTS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/#id-cfcbf0a7-0), partially also STTS and UPOS); overlap with UD Swiss German UZH and Wikipedia | 115k toks | (mostly?) ad-hoc pronunciation spelling | [annotations: CC BY 4.0](https://github.com/noe-eva/NOAH-Corpus/blob/master/LICENSE) | 
| [UD Swiss German UZH](https://github.com/UniversalDependencies/UD_Swiss_German-UZH) ([Aepli & Clematide 2018](https://ceur-ws.org/Vol-2226/paper1.pdf)) | POS (UPOS, [mod.](https://github.com/noe-eva/NOAH-Corpus/blob/master/guidelines.md) [STTS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/#id-cfcbf0a7-0)), dependencies (UD); overlap with NOAH's corpus and Wikipedia | 100 sentences | (mostly?) ad-hoc pronunciation spelling | [CC BY-SA 4.0](https://github.com/UniversalDependencies/UD_Swiss_German-UZH/blob/master/LICENSE.txt) |
| [WUS DIALOG GSW](https://whatsup.linguistik.uzh.ch/) ([Stark ea 2014-20](https://whatsup.linguistik.uzh.ch/), [Ueberwasser & Stark 2017](https://bop.unibe.ch/linguistik-online/article/view/3849/5834)) (subset) | POS ([mod.](https://whatsup.linguistik.uzh.ch/01_corpus/02_preprocessing/06_pos#swissgermandialect) [STTS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/#id-cfcbf0a7-0)), locations | 34.7k tokens | ad-hoc pronunciation spelling, [German ortho](https://whatsup.linguistik.uzh.ch/01_corpus/02_preprocessing/07_normalization) | CC BY-NC-ND |
| [SID4LR](https://bitbucket.org/robvanderg/sid4lr/src/master/) ([Aepli ea 2023](https://aclanthology.org/2023.vardial-1.25/)) (gsw subset) | slot filling, intent detection, translations into 14 languages. Bernese | 800 sentences | | |
| [SwissDial](https://mtc.ethz.ch/publications/open-source/swiss-dial.html) ([Dogan-Schönberger ea 2021](https://arxiv.org/pdf/2103.11401.pdf)) | topics (14 classes), translations (across dialects and into German), locations (Aargau, Bern, Basel, Graubünden, Luzern, St. Gallen, Wallis, Zürich); the Wallis data are presumably in Walser (wae) | 2.5-4.6 hrs × 7-8 dialects | audio, pronunciation spelling, German ortho | CC BY-NC 4.0 |
| [Zwirner-Korpus](https://dgd.ids-mannheim.de/) (subset of downloadable subcorpus) ([Zwirner & Bethge 1958](https://katalog.slub-dresden.de/id/0-1116234068), [IDS: Datenbank für gesprochenes Deutsch (DGD)](https://dgd.ids-mannheim.de/)) | | 10 min / 612 tokens | audio, German ortho | [custom terms](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_use) |
| [SpinningBytes Swiss German Corpus (SB-CH)](https://github.com/spinningbytes/SB-CH) (annotated subset) ([Grubenmann ea 2018](https://aclanthology.org/L18-1372/)) | sentiment; potential overlap with NOAH's corpus | 2.8k sentences | pronunciation spelling | [CC BY 4.0](https://spinningbytes.com/more/resources/) |
| [What's up, Switzerland?](https://whatsup.linguistik.uzh.ch/) (subset) ([Stark ea 2014-20](https://whatsup.linguistik.uzh.ch/), [Ueberwasser & Stark 2017](https://bop.unibe.ch/linguistik-online/article/view/3849/5834)) | locations | 507k messages / 3.6M tokens | pronunciation spelling | CC BY-NC-ND |
| Swatchgroup Geschäftsbericht (subset) via [PaCoCo](https://pub.cl.uzh.ch/wiki/public/pacoco/start) ([Graën ea 2019](https://doi.org/10.5167/uzh-175081)) | | 79.6k tokens | pronunciation spelling | [CC BY-SA](https://pub.cl.uzh.ch/corpora/PaCoCo/Swatchgroup/index.json) |
| [Schweizerdeutsches Mundartkorpus (CHMK)](https://chmk.ch/de/info_all) ([Weibel & Peter 2020](https://ceur-ws.org/Vol-2624/paper4.pdf)) | release for academic use planned | 25M tokens | | |
| [Text+Berg](https://textberg.ch/site/en/corpora/) via [PaCoCo](https://pub.cl.uzh.ch/wiki/public/pacoco/start) (subset) ([Bubenhofer ea 2015](https://textberg.ch/site/en/corpora/), [Graën ea 2019](https://doi.org/10.5167/uzh-175081)) | | 156 sentences / 3.1k tokens | | [CC BY-SA](https://pub.cl.uzh.ch/corpora/PaCoCo/Text_Berg/SAC/index.json) |
| [ArchiMob](https://spur.uzh.ch/en/departments/research/textgroup/ArchiMob.html) ([Scherrer ea 2019](https://bop.unibe.ch/linguistik-online/article/view/5947)) | | 70 hrs | audio, [transcription based on the Dieth orthography for Swiss German](https://drive.switch.ch/index.php/s/epEvTh5aY3nVakb), [German ortho](https://drive.switch.ch/index.php/s/7vej7OBN4O5nMt5) | CC BY-NC-SA 4.0 |
| [STT4SG-350](https://swissnlp.org/datasets/) ([Plüss ea 2023](https://arxiv.org/pdf/2305.18855.pdf)) | locations (7 regions) | 343 hrs | audio, German ortho | META-SHARE NonCommercial NoRedistribution |
| [SDS-200](https://swissnlp.org/datasets/) ([Plüss ea 2022](https://aclanthology.org/2022.lrec-1.347/)) | | 200 hrs | audio, German ortho | META-SHARE NonCommercial NoRedistribution |
| [Swiss Parliaments Corpus](https://www.cs.technik.fhnw.ch/i4ds-datasets) ([Plüss ea 2021a](https://ceur-ws.org/Vol-2957/paper3.pdf)) | | 293 hrs | audio, German ortho ||
| [All Swiss German Dialects Test Set](https://www.cs.technik.fhnw.ch/i4ds-datasets) ([Plüss ea 2021b](https://ceur-ws.org/Vol-2957/sg_paper1.pdf)) | locations (cantons, incl. Wallis) | 13 hrs / 5.8k utterances | audio, German ortho | MIT |
| [Gemeinderat Zürich Audio Corpus](https://www.cs.technik.fhnw.ch/i4ds-datasets) ([Plüss ea 2021b](https://ceur-ws.org/Vol-2957/sg_paper1.pdf)) | | 1208 hrs | audio | MIT |
| Ein geparstes und grammatisch annotiertes Korpus schweizerdeutscher Spontansprachdaten ([Schönenberger & Haeberli 2019](https://archive-ouverte.unige.ch/unige:121528)) (contact authors) | POS (mod. [Penn-historical](https://www.ling.upenn.edu/hist-corpora/annotation/index.html), phrase structure (Penn-historical). Location: Wil (SG) | 100k+ tokens | Dieth orthography | |
| [Swiss Crawl](https://icosys.ch/swisscrawl) ([Linder ea 2020](https://aclanthology.org/2020.lrec-1.329/)) | uncurated | 500k+ sentences | ? | CC BY-NC 4.0 |
| [SpinningBytes Swiss German Corpus (SB-CH)](https://github.com/spinningbytes/SB-CH) ([Grubenmann ea 2018](https://aclanthology.org/L18-1372/)) | uncurated; contains NOAH's corpus | 116k sentences | | [CC BY 4.0](https://spinningbytes.com/more/resources/) |
| [SwigSpot](https://github.com/derlin/SwigSpot_Schwyzertuutsch-Spotting) ([Linder 2018](https://github.com/derlin/SwigSpot_Schwyzertuutsch-Spotting/blob/master/report-online.pdf)) | uncurated | 8k sentences | ? | [Apache 2.0](https://github.com/derlin/SwigSpot_Schwyzertuutsch-Spotting/blob/master/LICENSE) | 
| [Tatoeba](https://tatoeba.org/en/downloads) ([gsw](https://tatoeba.org/en/sentences/show_all_in/gsw/none) subset) | translations into other languages | 474 sentences | ? | CC BY 2.0 FR |
| [OSCAR](https://oscar-project.github.io/documentation/versions/oscar-2301/) (subset) ([Abadji ea 2022](https://aclanthology.org/2022.lrec-1.463/)) | uncurated | 34k tokens / 233 KB | ? |[Metadata/annotations: CC0 1.0](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), [Common Crawl: custom](https://commoncrawl.org/terms-of-use/) |
| [Wikipedia](https://dumps.wikimedia.org/) (subset of [als](https://als.wikipedia.org/) subset)| uncurated, partially [tagged with dialect information](https://als.wikipedia.org/wiki/Kategorie:Wikipedia:Dialekt) | 27k total (including Swabian and Walser), thereof [2.3k (directly or indirectly) tagged as Alsatian, and 1.7k (directly or indirectly) tagged as Swiss German](https://als.wikipedia.org/wiki/Kategorie:Wikipedia:Dialekt) | [no defined standard, but a set of recommendations based on published works, the (Swiss German) Dieth orthography and the (Alsatian) Orthal orthography](https://als.wikipedia.org/wiki/Hilfe:Schrybig) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) | 

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)

### Walser · wae · [wals1238](https://glottolog.org/resource/languoid/id/wals1238)

| Corpus | Notes | Size | Representation | License |
|--------|-------|------|----------------|---------|
| [ArchiWals / CLiMAlp](https://climalp.org) ([Angster ea 2017](https://hdl.handle.net/2318/1670241), [Gaeta 2020](https://www.academia.edu/download/64894560/2020_Lecce_Paper.pdf)) | locations (Gressoney, Issime, Formazza, Rimella, Alagna) | 80k+ tokens | pronunciation spelling ||
| [Walliserdeutsch/RRO](https://zenodo.org/record/4580286) ([Garner 2014](https://zenodo.org/record/4580286), [Garner ea 2014](https://www.isca-speech.org/archive/interspeech_2014/garner14_interspeech.html)) | | 8.3 hrs | audio, non-standardized transcription | custom |
| [SwissDial](https://mtc.ethz.ch/publications/open-source/swiss-dial.html) (subset) ([Dogan-Schönberger ea 2021](https://arxiv.org/pdf/2103.11401.pdf)) | topics (14 classes), translations (into German and 7 Swiss German dialects) | 3.3 hrs | audio, pronunciation spelling, German ortho | CC BY-NC 4.0 |
| [All Swiss German Dialects Test Set](https://www.cs.technik.fhnw.ch/i4ds-datasets) ([Plüss ea 2021b](https://ceur-ws.org/Vol-2957/sg_paper1.pdf)) | locations (cantons, incl. Wallis) | unk | audio, German ortho | MIT |
| [Wikipedia](https://dumps.wikimedia.org/) (subset of [als](https://als.wikipedia.org/) subset)| uncurated | [35 (of 27k total) tagged as Wal(li)ser](https://als.wikipedia.org/wiki/Kategorie:Wikipedia:Dialekt) | [no defined standard, but a set of recommendations based on published works, the (Swiss German) Dieth orthography and the (Alsatian) Orthal orthography](https://als.wikipedia.org/wiki/Hilfe:Schrybig) | [text: GFDL, CC BY-SA 3.0; images: CC BY-SA 4.0](https://dumps.wikimedia.org/legal.html) |

[↑ top](#a-survey-of-corpora-for-germanic-low-resource-languages-and-dialects)
