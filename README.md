# Tlingit Roots

This is a collection of documented roots and other parts of speech in the
Tlingit language, meant for reference and linguistic research. The structure of
the file is very simple so that it can be easily parsed by text processing
tools. The contents are mostly derived from Leer’s stem and verb documentation,
with additions from various sources like Edwards 2009, later Leer materials,
and other researchers inclduing my own fieldwork.

* Naish & Story 1963: http://www.uaf.edu/anla/item.xml?id=TL959NS1963g
* Leer 1973: http://www.uaf.edu/anla/item.xml?id=TL962L1973g
* Leer 1975: http://www.uaf.edu/anla/item.xml?id=TL962L1975i
* Leer 1976: http://www.uaf.edu/anla/item.xml?id=TL962L1975n
* Leer 1978: http://www.uaf.edu/anla/item.xml?id=TL962L1975m
* Leer 1978: http://www.uaf.edu/anla/item.xml?id=TL962L1978c
* Leer 1978: http://www.uaf.edu/anla/item.xml?id=TL962L1978g
* Leer 1978: http://www.uaf.edu/anla/item.xml?id=TL962L1978i
* Leer 1978: http://www.uaf.edu/anla/item.xml?id=TL962L2000
* Leer 2001: http://www.uaf.edu/anla/item.xml?id=TL962L2001
* Edwards 2009: http://www.uaf.edu/anla/item.xml?id=TL005E2009

This collection is meant to be exhaustive for verb roots, but not for nouns.
Verbal derivation is relatively limited but nominal derivation through
compounding and other morphology makes the noun inventory practically infinite.
Most if not all monomorphemic nouns and borrowings are represented, but only
a selection of interesting compounds and other nouns are included.

The coverage of other parts of speech aims to be exhaustive but this is not
achieved at present. Particular attention has been paid to interjections,
directionals, underived adjectives, and underived adverbs. Other parts of
speech that need more representation are postpositions and postpositional
phrases, determiners, demonstratives, pronouns, and verb morphemes.

Names are included mostly to illustrate otherwise rare lexical items. The
vast majority of included names are ethnonyms, clan names, and place names.
Personal names are generally limited to legendary and mythical figures, to
avoid issues with clan ownership.

## File structure

The structure of the roots list is very simple. The file is composed of many
entries, with each entry on a separate line. (Unix line endings are used, so
that [newlines](https://en.wikipedia.org/wiki/Newline) are represented by
U+000A Line Feed.) Each entry line is divided into three columns, and these
columns are separated by tabs ([U+0009 Character
Tabulation](http://en.wikipedia.org/wiki/Horizontal_tabulation)).

* `column1 → column2 → column3`

The first column, `column1` above, is the entry datum. This is a single word
without any spaces, possibly preceded by a `√` root sign ([U+221A Square
Root](https://codepoints.net/U+221A?lang=en)) if the entry is a verb root. The
second column, `column2` above, contains a part of speech label. The part of
speech labels are listed exhaustively in a subsection below. The third column,
`column3` above, is the definition and other assorted information about the
datum.

* `√taxʼ → root → bite, chew`
* `lʼaak → noun → dress`
* `tléil → pcl → not, negative`
* `tléikʼ → interj → no`

### Parts of speech

* `root` – a verb root
* `noun` – a noun or noun-like word
* `adj` – an adjective that modifies a noun
* `adv` – an adverb that modifies a verb
* `pron` – a pronoun, including pronominal prefixes of the verb
* `det` – a determiner
* `pcl` – a grammatical particle
* `dirn` – a directional word
* `ppn` – a postposition or a postpositional phrase
* `aux` – an auxiliary verb
* `affix` – an affix not identifiable as a separate word
* `interj` – an interjection or exclamation
* `name` – a proper name of a place, person, etc.

## Representation of roots

Tlingit roots form two classes: variable and invariable. These two classes and
their various subclasses are represented in the roots list with particular
orthographic conventions. These conventions differ slightly from the
orthography used for the rest of the language.

Variable roots have multiple surface forms that depend on phonological and
inflectional context. The variation in surface forms is mostly tone and length.
Variable roots do not have an underlying specification of either tone or
length, so their representations are not pronounceable forms. In contrast,
invariable roots have one surface form regardless of context. The
representations of invariable roots are therefore pronounceable.

The following list illustrates the representation of invariable roots. Note the
use of a grave accent to indicate low tone where it might be ambiguous. This is
omitted where there is a high tone vowel in a neighbouring syllable.

* `√tsàa` [tsʰàː] CV̀V̀
* `√dzée` [tsíː] CV́V́
* `√.àas` [ʔàːs] CV̀V̀C
* `√ÿáash` [ɰáːʃ] CV́V́C
* `√hélʼk` [héɬʼk] CV́CC
* `√náalx̱` [náːɬχ] CV́V́CC
* `√háachʼi` [háːtʃʼì] CV́V́CV̀
* `√haakʼú` [hàːkʼʷú] CV̀V̀CV́
* `√ÿaax̱áḵw` [ɰàːχáqʷ] CV̀V̀CV́C
* `√tlʼéekʼát` [tɬʼíːkʼát] CV́V́CV́C

The following list illustrates the representation of variable roots. Note the
lack of tone on the vowels.

* `√tla` /tɬʰa/ CV
* `√tlaʰ` /tɬʰa/ CVʰ
* `√tan` /tʰan/ CVC
* `√taʼw` /tʰaw/ CVʼC

The CVʰ roots differ from CV roots in appearing in suffixed forms with low tone
where high tone would otherwise be expected. The CVʼC roots differ from CVC
roots in having high tone where low tone would otherwise be expected.
The representations are due to Tongass Tlingit where CVʰ roots had breathy
vowels instead of plain vowels, and CVʼC roots had glottalized vowels instead
of plain vowels.

## Dialects and representation

Tlingit dialect variation is primarily phonological, so that different dialects
have distinct pronunciations of the same word. There are a few regular
historical phonological processes that capture much of Tlingit’s dialect
differentiation, particularly rounding spread and uvular lowering.

### Rounding spread

Rounding spread (or labial spread) is the spread of labial features from one
segment to other adjacent segments. This can be progressive (perseveratory) or
retrogressive (anticipatory), or both. The following is an example of
progressive rounding spread, with the initial labialized velar stop `gw`
spreading to the following `i` so that it becomes `u`.

* `gwít` /kʷít/ ‘dime’ → `gút` /kʷút/ ‘dime’

The next example shows retrogressive rounding, with the final `w` spreading to
the preceding `ei` so that it becomes `oo`.

* `lʼeiwú` /ɬʼèːwú/ ‘wood’ → `lʼoowú` /ɬʼùːwú/ ‘wood’

### Uvular lowering

Uvular lowering is the lowering of the high front vowel `i` ~ `ee` to the
mid front vowel `e` ~ `ei` when adjacent to a uvular segment. The uvulars are
uniformly represented in the orthography with an underscore diacritic
([U+0331 Macron Below](https://en.wikipedia.org/wiki/Macron_below)), so these
are e.g. `x̱`, `ḵʼ`, `g̱w`. Uvular lowering can be progressive or retrogressive
or both. The example below shows progressive uvular lowering, with the uvular
`g̱` causing the following `ee` to lower to `ei`.

* `g̱eeÿ` /qìːɰ/ ‘bay’ → `g̱eiÿ` /qèːɰ/ ‘bay’

The following illustrates retrogressive uvular lowering, with the final uvular
stop `ḵ` causing the preceding high front vowel `ee` to be lowered to the mid
front `ei`.

* `eeḵ` /ʔìːq/ ‘copper’ → `eiḵ` /ʔèːq/ ‘copper’

### Representation of dialect variation as etymology

The two processes of rounding spread and uvular lowering are the most important
causes of dialect variation in the Tlingit lexicon, though there are others
such as final vowel lowering. As such, much of the dialect variation is
phonologically predictable.

To represent dialect variation, I include multiple entries for each lexical
item that is affected by variation. Since the phonological processes that cause
these changes are well documented, the variation is indicated as forward and
backward etymologies using the > and < arrows respectively.

* `gwít → noun → dime (< CJ bit < Eng. bit ‘1/8 Spanish dollar’; > gút)`
* `gút → noun → dime (< gwít ‘dime’)`
* `lʼeiwú → noun → wood (> lʼoowú ‘wood’)`
* `lʼoowú → noun → wood (< lʼeiwú ‘wood’)`
* `g̱eeÿ → noun → bay (> g̱eiÿ ‘bay’)`
* `g̱eiÿ → noun → bay (< g̱eeÿ ‘bay’)`
* `eeḵ → noun → copper (> eiḵ ‘copper’, iḵnáachʼ ‘brass’, iḵÿéisʼ ‘iron’)`
* `eiḵ → noun → copper (< eeḵ ‘copper’)`
