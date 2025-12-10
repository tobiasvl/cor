# COR

This is a mirror of the corpora published at
[Det Centrale Ordregister](https://ordregister.dk/) (COR), a register of the
lemmas and lexemes of the Danish vocabulary developed to support language
technology projects.

COR is created and published by [Dansk Sprognævn](https://dsn.dk/forskning/sprogteknologi-og-fagsprog/cor/)
under the CC0 license (public domain).

Please go to COR's website to read the [COR-README](https://ordregister.dk/doc/COR-README.html)
and [COR manual](https://ordregister.dk/doc/COR.html) (in Danish). You can also
search directly in COR on the website or access it through a webservice, and
they also have other resources that are not in the public domain, such as
COR.SEM.EXT (a supplementary resource for COR.SEM).

## COR 1 (base resource)

COR 1 is the basic resource in COR. The register is based on
[Retskrivningsordbogen](https://ro.dsn.dk/) (the official Danish dictionary)
and contains information on word classes, inflections and lexemes for all
lemmas in the dictionary.

The supplemental file `bix2bform_UTF8_01.tsv` contains morphological data
about COR 1.x.

## COR.EXT

COR.EXT 1.0 contains over 25 000 lemmas from [Den Danske Ordbog](https://ordnet.dk)
(The Danish Dictionary) that are not found in COR 1.0. COR.EXT 1.0 contains
parts of speech and most inflections.

## COR.SOEGEHJAELP

COR.SOEGEHJAELP 1.0 is a list with a number of spelling errors and alternative
spellings (both official and unofficial), as well as an indication of the
correct form.

The list draws on information used in the search algorithm on [Den Danske Ordbog's website](https://ordnet.dk)
to help the user find the desired entry.

## COR.SEM

See also the [COR.SEM website](https://corsem.dsl.dk/).

COR.SEM 1.0 is a lexical semantic resource that is linked to either the basic
resource COR or COR.EXT. The COR.SEM resource describes the common language
meanings of 34 000 Danish lemmas, expressed using formalized values. The
resource is based on a number of information from other dictionaries:
[DanNet](https://wordnet.dk/dannet/page/frontpage), [Den Danske Ordbog](https://ordnet.dk),
the [Danish FrameNet lexicon](https://korpus.dsl.dk/resources/details/framenet.html#english),
[The Danish Sentiment lexicon](https://github.com/dsldk/danish-sentiment-lexicon)
and [Den Danske Begrebsordbog](https://ordnet.dk/ddb).
