<!-- DOCUMENT HISTORY:
  this markdown file was generated with pandoc v. 2.8 on 20200624
  input source: docx, exported from these Google Docs:
  https://docs.google.com/document/d/1zeUkzmy-3kpK-egqko_IHWZJ992qEnMcgIdzF6Syz4M/edit?usp=sharing
  https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing

  markdown headings, lists, and other formatting conventions are supplied manually
  subsequently re-generated as GitHub-flavored Markdown, again with pandoc
  this fixes rendering of tables and other document formatting on GitHub
-->

These guidelines derive originally from the Bibliotheca Philadelphiensis Project.
The original Bibliotheca Philadelphiensis documentation may be viewed [here](https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing) and [here](https://docs.google.com/document/d/1zeUkzmy-3kpK-egqko_IHWZJ992qEnMcgIdzF6Syz4M/edit?usp=sharing).

For general instructions in style and usage see the [Style Guide](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/style-guide.md).

# Item
## Identifiers

### Repository Country

Optional

**MARC Location**: Possibly 852 subfield e

**Description**: Country of the holding library; United States for all partner institutions.

### Repository City

Required

**MARC Location**: 852 subfield e

**Description**: Municipality of the holding library; consistent for all manuscripts from a single institution.

**Instructions**:Name of the city *only*, do not include the name of the state

### Holding Institution

Optional

**MARC Location**: 852 subfield a

**Description**: Organization name if library is part of a larger organization such as a university.

**Instructions**: Name of the institution above the **Repository**. The **Repository** will be the name of the library, so the **Holding Institution** will usually be the name of a university. Full name, do not use abbreviations.

### Repository Name

Required

**MARC Location**: 852 subfield b

**Description**: Library name.

**Instructions**: Full name, do not use abbreviations.

### Source Collection

Optional

**MARC Location**: Possibly 500, possibly 710

**Description**: Name of a named collection within the library.

### Call Number/ID

Required

**MARC Location**: 099, 852 subfield j

**Description**: Format varies by library; not included in dealer descriptions; possibly in headings in library description.

**Instructions**: Use what is provided by the institution.

### Record URL

Optional

**Description**: URL format varies by library; for records in an online catalog, possibly available when viewing record online.

### Alternate ID

Optional

**MARC Location**: 001 in Penn records

**Description**: Internal control number such as Penn’s BibID or URN such as DOI, PURL, or ARK; to be supplied by holding library.

### Alternate ID Type

Required for manuscripts with alternate IDs

**Description**: Possibilities include DOI, PURL, ARK, BibID; to be supplied by holding library.

### Manuscript Name

Required

**MARC Location**: 245

**Description**: Title in English representing the manuscript volume as a whole; if the whole volume consists of one or two works, the single title or two titles separated by a semicolon; if a collection of smaller works, a supplied title such as Recipe book; probably in the headings of dealer or library descriptions.

## Agents

### Author Name

Optional, Repeatable

**MARC Location**: Possibly 100, possibly 110

**Description**: When a manuscript contains a work or works with personal or corporate authors, use the LC or VIAF authority heading or record an unauthorized name in authority form; unlikely to appear in this form in dealer or narrative library descriptions, probably needs to be supplied from LC/OCLC.

If there is not an Authority Name, give the name of the author in Latin letters in authority form (Last Name, First Name)

### Author URI

Optional, Repeatable

**Description**: For authors in the LC NAF, give the URI from <http://id.loc.gov/authorities/names.html>; for creators in VIAF give the permalink from <http://viaf.org/>; unlikely to appear in dealer or narrative library descriptions, probably needs to be supplied. If you have verified that the author name does not have an authorized form in LC NAF or VIAF, enter N/A.

### Translator Name

Optional, Repeatable

**MARC Location**: Possibly 245, possibly 500, possibly 700

**Description**: When a manuscript contains the name of a translator, or when the translator of a text has been identified independently, use the LC or VIAF authority heading or record an unauthorized name in authority form; unlikely to appear in this form in dealer or narrative library descriptions, probably needs to be supplied from LC/OCLC.

**Instructions**: Same rules as **Author** fields above

### Translator URI

Optional, Repeatable

**Description**: For translators in the LC NAF, give the URI from <http://id.loc.gov/authorities/names.html>; for translators in VIAF give the permalink from <http://viaf.org/>; unlikely to appear in dealer or narrative library descriptions, probably needs to be supplied. If you have verified that the translator name does not have an authorized form in LC NAF or VIAF, enter N/A.

### Artist Name

Optional, Repeatable

**MARC Location**: Possibly 500, possibly 700

**Description**: When a manuscript contains the name of an illuminator or illustrator, or when the work of an artist in a manuscript has been identified independently, use the \*\*ULAN\*\*, LC, or VIAF authority heading or record an unauthorized name in authority form; unlikely to appear in this form in dealer or narrative library descriptions, probably needs to be supplied from LC/OCLC.

### Artist URI

Optional, Repeatable

**Description**: For artists in ULAN, give the ID from <http://www.getty.edu/research/tools/vocabularies/ulan/>; for artists in LC NAF, give the URI from <http://id.loc.gov/authorities/names.html>; for artists in VIAF give the permalink from <http://viaf.org/>; unlikely to appear in dealer or narrative library descriptions, probably needs to be supplied. If you have verified that the artist name does not have an authorized form in ULAN, LC NAF, or VIAF, enter N/A.

### Former Owner Name

Optional, Repeatable

**MARC Location**: Possibly 500, possibly 561, possibly 700

**Description**: When a manuscript contains the name of a former owner, or when a former owner of a manuscript has been identified independently, use the LC or VIAF authority heading or record an unauthorized name in authority form; unlikely to appear in this form in dealer or narrative library descriptions, probably needs to be supplied from LC/OCLC.

### Former Owner URI

Optional, Repeatable

**Description**: For former owners in the LC NAF, give the URI from <http://id.loc.gov/authorities/names.html>; for former owners in VIAF give the permalink from <http://viaf.org/>; unlikely to appear in dealer or narrative library descriptions, probably needs to be supplied. If you have verified that the former owner name does not have an authorized form in LC NAF or VIAF, enter N/A.

## History

### Provenance

Optional

**MARC Location**: 541, 561

**Description**: Additional information beyond former owner names, including family ownership, former libraries or geographical locations, marks of provenance such as bookplates, and sale information.

**Instructions**: In this field the whole known history of the manuscript should be given. Provenance is concerned with the individuals or institutions that may have owned or handled a book up to and including the present time, and should be written out chronologically.  Record **Former Owner Names** separately, in authorized form.

### Date (single)

Optional, but one type of numerical date metadata must be supplied; Repeatable

**MARC Location**: Fixed field 008/07-10, possibly 245 subfield f, possibly 260 subfield c

**Description**: Year for a dated manuscript, or of a section of a manuscript consisting of originally separate manuscripts copied at different times, which each section provided its own Date (single) or Date (range); probably in the headings of a dealer or library description, otherwise in notes; if the single date is given as a narrative phrase (see Date (narrative) below), supply a year here; enter as the year only without additional words.

### Date (range) start

Optional, but required if a Date (narrative) entry is present, and one type of numerical date metadata must be supplied; Repeatable

**MARC Location**: Fixed field 008/07-10, possibly 245 subfield f, possibly 260 subfield c

**Description**: Beginning year for a manuscript completed over an extended period of time or the earliest year of a section of a manuscript consisting of originally separate manuscripts copied at different times, with each section provided its own Date (single) or Date (range); probably in the headings of a dealer or library description, otherwise in notes; if the range is given as a narrative phrase (see Date (narrative) below), supply a starting year here; enter as the year only without additional words.

### Date (range) end

Optional, but required if a Date (narrative) entry is present, and one type of numerical date metadata must be supplied; Repeatable

**MARC Location**: Fixed field 008/11-14, possibly 245 subfield f, possibly 260 subfield c

**Description**: Ending year for a manuscript completed over an extended period of time or the latest year of a section of a manuscript consisting of originally separate manuscripts copied at different times, with each section provided its own **Date (single)** or **Date (range)**; probably in the headings of a dealer or library description, otherwise in notes; if the range is given as a narrative phrase (see **Date (narrative)** below), supply an ending year here; enter as the year only without additional words.

### Date (narrative)

Optional, NOT Repeatable

**MARC Location**: 500 notes

**Description**: Phrase from a dealer or library description suggesting an exact date, part of a century, a century, or a range of years larger than a century, or single approximate year for a manuscript described as “Circa” with a single year; multiple dates in the previous fields may be described narratively together here (e.g., “12th century and 15th century”). Complete descriptions will include both a Date (narrative) and a Date (range) or a Date (single). Enter the phrase as given in this row and supply start and end dates in the appropriate rows, as in the following examples:

| **Date (narrative)**            | **Supply Date (range) start** | **Supply Date (range) end** |
| :------------------------------ | :---------------------------- | :-------------------------- |
| 14th century                    | 1300                          | 1399                        |
| Early 14th century              | 1300                          | 1315                        |
| First quarter 14th century      | 1300                          | 1325                        |
| Fourth quarter 14th century     | 1375                          | 1399                        |
| Mid-14th century                | 1340                          | 1360                        |
| 14th century after 1320         | 1320                          | 1399                        |
| Late 14th century               | 1385                          | 1399                        |
| Late 14th or early 15th century | 1385                          | 1415                        |
| Mid-14th to early 15th century  | 1340                          | 1415                        |
| 14th or 15th century            | 1300                          | 1499                        |

### Place of Origin

Required, Repeatable

**MARC Location**: 260 subfield a, possibly additional details in 500 notes

**Description**: Place where a manuscript was copied or a suggestion, possibly very broad, of where it might have been copied; often in dealer and library description headings; include cardinal specifications (for example, Northern France); may be followed by a question mark for conjectural locations. Multiple locations may be entered for codices containing multiple manuscripts with different origins bound together.

**Instructions**: This should be a modern geographical location whenever possible (Flanders being a rare exception). The smallest component of the location should be listed first, followed by larger locations, usually simply City, Country, e.g., “Oxford, England,” but this could be more specific, such as “Monastery of Reichenau, Lake Constance, Germany,” or could include a region either after a city or as a more specific element before a country. If country is not known, then a region with an accepted or commonly used geographical designation may be given. Cardinal specifications (for example, Northern France) may be included. Conjectural locations may be followed by a question mark, but only one question mark should be used in an origin series, at the most specific level:

  - Paris, France
  - Oxford?, England
  - Florence?, Tuscany, Italy
  - Tuscany?, Italy
  - Northwestern France

The final element of an origin preferably will be an entry from the European geographic keywords:

  - Austria
  - England
  - Flanders
  - France
  - Germany
  - Greece
  - Italy
  - Netherlands
  - Romania
  - Russia
  - Spain

Multiple locations may be entered in multiple columns for codices containing multiple manuscripts with different origins bound together.

If a manuscript’s location of origin cannot be determined within Europe (as is the case for some Greek manuscripts, for example), enter Undetermined.

### Origin Details

Optional

**MARC Location**: 500 notes

**Description**: Additional details about where the manuscript was created.

## Contents

### Title

In Latin transcribed and/or supplied title in square brackets.

### Incipit and explicit

Incipit and explicit should be recorded for the following types of material:

- All leaves. Incipit is the initial words of the leaf.
- Works imperfect at beginning or end. Incipit is the initial words of the work as transmitted.
- Unidentified works, works without a standard modern edition, and eccentric copies of known works. Incipit is the initial words of the work, following the title or rubric (if any)
- Papal letters. Incipit is the first words after the initial protocol.

Do not provide incipit or explicit for Books of Hours, Bibles, or other standard works transmitted intact in codex form.

In general, transcription follows the policies set out in
M. B. Parkes, *English Cursive Book Hands, 1250–1500* (Oxford: Oxford University Press, 1969), pp. xxviii--xxx ("A note on the transcriptions").
We depart from Parkes's practice in the following details:

- Words inserted by the scribe are recorded within double slashes, e.g. `\\habet//`.
- Long *i* is transcribed as *j* where the scribe has used this form in final position, e.g., in roman numeral *xiij*.

### Language

Required, Repeatable

**MARC Location**: Fixed field 008/35-37, 041, 546

**Description**: Language or languages in which the manuscript is written.

**Instructions**: Name of the language or languages represented in the manuscript. Include names only, one name per column. If there are notes about the use of languages (e.g., “Latin with Greek glosses”) include all the language names in the **Language** field, and add the additional information as a **Note**. Use the following Language codes (from the ISO 639-2) - full names are provided for reference, do not include them in the field:

  - lat \[Latin\]
  - grc \[Greek\]
  - xno \[Anglo-Norman\]
  - arm \[Armenian\]
  - chu \[Church Slavonic\]
  - dum \[Dutch\]
  - eng \[English after approx 1500\]
  - enm \[English, Middle, to approx 1500\]
  - frm \[French, Middle, approx. 1400-1600\]
  - fro \[French, Old, before approx. 1400\]
  - ger \[German, after approx. 1500\]
  - gmh \[German, Middle High, approx. 1050-1500\]
  - goh \[German, Old High, approx. 750-1050\]
  - heb \[Hebrew\]
  - nds \[Low German\]
  - ita \[Italian\]
  - cat \[Catalan\]
  - spa \[Spanish\]

### Description

Optional

**MARC Location**: 520

**Description**: Abstract or summary of no more than a couple of sentences summarizing the content of the manuscript as a whole.

**Instructions**: Each **Description** should, in a **maximum of 250 words,** introduce or summarize the salient features of a book’s textual, material and artistic contents, emphasizing the most important qualities that the reader will need to know about the manuscript – what makes it special or important? Qualitative judgments and subjective adjectives should be used sparingly. Important information to include, when known, are the date of the manuscript, its origin, if it is illuminated, if it is complete or fragmentary, and the names of authors, scribes, and artists where applicable.

Subjective adjectives and qualitative judgments (famous, well-known, great, elegant, clear) should be used sparingly.

## Analytic description

### Foliation/Pagination

Optional

**MARC Location**: 500 notes

**Description**: How the leaves or pages of the manuscript are numbered (in foliation, each leaf is numbered once; in pagination, both the recto and verso side of each leaf are numbered), and where the numbers appear on the leaves, such as *upper right recto* or *lower outer corners*, or *Modern foliation in pencil, upper right recto*

### Flyleaves & Leaves

Required for codices; this field is not used for leaves.

**Description**: Formula showing the numbers of flyleaves and leaves, in the format \[front flyleaves\]+\[leaves\]+\[back flyleaves\], for example ii+113+iii

**Instructions**: No spaces. Make note of the flyleaf material using the **Note** field.

### Layout

Optional

**MARC Location**: 500 notes

**Description**: The easiest layout details to capture are number of columns and number of lines per page, if those are generally consistent throughout the manuscript or in sections of the manuscript. Information about how a page is ruled and by what means (drypoint, lead, ink) also goes here.

**Instructions**: A written area that is delineated by four intersecting lines that run from edge to edge is **frame-ruled**. A written area that is delineated by a floating box is **box-ruled**.

### Colophon

Optional

**MARC Location**: 500 notes

**Description**: Statement at the end of some manuscripts recording the date, place, scribe, and/or reason for production of the manuscript. Potential source of Date and Place of origin information, when present.

**Instructions**: Transcription of the colophon, if present. Any other information about a colophon should be a **Note**.

### Collation

Optional

**MARC Location**: 500 notes

**Description**: Information about the structure of the volume in terms of numbers of gatherings and numbers of leaves per gathering, often presented as a formula.

**Instructions**: We will express collation by formula.
Gatherings are enumerated with Arabic numerals.
After the numeral representing each gathering, type two carets `^^` then the number of conjoint leaves originally constituting that quire. 
Any unpaired leaves or postproduction losses are recorded in parentheses afterwards, following the conventions laid down in N.R. Ker, *Catalogue of manuscripts containing Anglo-Saxon*, p. xxii.
David Gura's collation of St. Mary's College MS 2 is represented by the following formula in our notation:

```
1^^6 (+1 leaf after 5) 2^^10 (wants 9, 10) 3^^6 (+1 leaf after 4) 4^^12 (+1 after 7; wants 9, 10, 11, 12)
```

If the collation cannot be determined, enter ‘Structure Uncertain.’

If you can determine part of the collation, but not the entire thing, you can also describe the collation as best you can and this will be passed to the TEI.

### Script

Optional, Repeatable

**MARC Location**: 500 notes

**Description**: Information about the type of lettering used in the manuscript (for example, Caroline minuscule, Gothic). Information about hands (a hand is an individual version of a script written by a single scribe) and scribes may also be entered here. Multiple hands may write in the same script.

**Instructions**: Information about the type of lettering used in the manuscript, preferring the terms listed below if applicable.

  - Square Capitals
  - Rustic Capitals
  - Uncial
  - Half-Uncial
  - Caroline Minuscule
  - Protogothic
  - Gothic–textualis quadrata (consistent application of feet and biting of curves)
  - Gothic–textualis semi-quadrata (inconsistent application of feet and biting of curves)
  - Gothic–textualis (everything below semi-quadrata; for Gothic with single-compartment *a*, sometimes called semitextualis, add a note: “Gothic–textualis; single-compartment *a*”)
  - Gothic–rotunda (round Italian textualis, not Brownian rotunda, which is English with rounded-off minims)
  - Gothic–anglicana
  - Gothic–cursiva
  - Littera bononiensis
  - Secretary
  - Bâtarde
  - Mercantesca
  - Hybrida
  - Humanistic
  - Humanistic Cursive
  - Humanistic semi-cursive
  - Greek Minuscule

If the scribe is identifiable, include the scribe’s name, preceded by “Scribe:” For example, “Scribe: Thomas Hoccleve”.

### Decoration

Optional

**MARC Location**: Fixed field 008/18-21, 500 notes

**Description**: Summary of information about formal visual elements of the manuscript (including illuminations, diagrams, decorated initials, colored headings and paragraph marks) and informal visual elements added later to the manuscript (including drawings, sketches, and manicules).  Not a page-level list of visual elements.

### Musical notation

Optional

**MARC Location**: ???

**Description**: (to be supplied)
<!-- This field is our addition, not yet in the Google Sheet template -->

**Instructions**: If notation is present, describe it here.

### Binding

Optional

**MARC Location**: 500 notes

**Description**: Information about the cover (such as type of leather or fabric), its ornamentation (such as gilt or blind, tooled or stamped), fastenings (such as clasps or ties), and damage or repairs to the cover.

### Watermarks

Optional, Repeatable

**MARC Location**: 500 notes

**Description**: For manuscripts written on paper, descriptions of the watermarks in the manuscript, possibly with citations to reference sources such as Briquet and Piccard.

### Catchwords

Optional

**MARC Location**: 500 notes, often with collation notes

**Description**: Information about the number and location of catchwords.

**Instructions**: If catchwords are present, where are they found, and what is the orientation on the page (at the bottom, along the side margin, etc.), e.g.: On versos, bottom right corner. If they are not consistent (for instance, where the pages are cropped and some are missing), indicate that as well.

### Signatures

Optional

**MARC Location**: 500 notes, often with collation notes

**Description**: Information about the numbers or letters used to ensure correct order of gatherings in the binding process, often found on the first recto or last verso of a gathering.

**Instructions**: If they are using a system in which quires are marked progressively, rather than using catchwords, you can explain that here. Same rules apply as for catchwords.

### Support material

Required

**MARC Location**: 300 subfield b

**Description**: Material on which the manuscript is written: *parchment*, *paper*, or *mixed* if both parchment and paper. Any other material, identify by name.

### Page dimensions

Optional, Repeatable

**MARC Location**: 300 subfield c

**Description**: Maximum height and width of manuscript leaves in millimeters, in the following form: 280 x 210 mm (no period after mm).
If originally separate manuscripts of markedly different dimensions have been bound together in a volume, repeat for the different page sizes. 

For bifolia, give the dimensions of a single leaf (height and width), just as in a codex.

For cuttings and binding fragments, give the longest height and width dimensions.

For folded documents with a single block of writing (e.g., personal letters), give the dimensions of the full unfolded sheet.
If the sheet has been folded folio, with writing disposed into two or more pages, treat the document as a bifolium (see above).
In either case, explain the measurement in a comment or in the field "Short Description."

### Written area

Optional, Repeatable

**MARC Location**: ???

**Description**: Height and width of the written space in millimeters.
If pages are ruled and writing is confined to the ruled space, measure that.
Otherwise measure height from the top of minims on the first line to the bottom of minims on the last line.
Repeat as necessary if a codex consists of booklets of markedly different layouts.
Width may be omitted for unruled verse or where the right edge of writing is ragged.

### Line height

Optional

**MARC Location**: ???

**Description**: The height in millimeters of a line of writing. 
Measure the height of ten lines, baseline to baseline, and divide by ten.
Supply this data point for fragments. 
For codices report **written area** instead.

### Bound dimensions

Optional

**MARC Location**: Possibly 300 subfield c

**Description**: Maximum height, width, and depth of bound volume in millimeters, in the following form: 290 x 220 x 30 mm (no period after mm).

### Notes

Optional, Repeatable

**MARC Location**: 500

**Description**: Possible entry for notes not explicitly covered by the spreadsheet, such as condition notes.

**Instructions**: Additional information about the manuscript that does not fit into other fields can be added as a note. Acknowledgements of e.g., cataloging work should not be included in Notes. Each note should be placed in a different cell.

## Bibliography

### Related resource

Optional, Repeatable

**MARC Location**: Possibly 773 subfield t, 856 subfield z

**Description**: Related resources may include the name of a larger collection to which this manuscript belongs; a digital facsimile of the manuscript; or a finding aid or catalog record for the manuscript.
Also includes citations to other bibliographic resources, such as essays or articles about a manuscript.
Citations are supplied in Chicago Style, imported from Zotero.

### Related resource URL

Optional, Repeatable

**MARC Location**: 856 subfield u

**Description**: URL for the related resource given in the previous row.

## Subjects and keywords

### Subject: names

Optional, Repeatable

**MARC Location**: 600

**Description**: When a manuscript has an individual or group as its subject, use the LCNAF or VIAF authority heading or record an unauthorized name in authority form; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied from LC/OCLC.

### Subject: names URI

Optional, Repeatable

**Description**: For subjects in the LCNAF, give the URI from <http://id.loc.gov/authorities/names.html>; for creators in VIAF give the permalink from <http://viaf.org/>; unlikely to appear in dealer or narrative library descriptions, may be supplied.

### Subject: topical

Optional, Repeatable

**MARC Location**: 650

**Description**: Topical subject as found in LCSH; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied from LC/OCLC.

### Subject: topical URI

Optional, Repeatable

**Description**: For subjects in LCSH, give the URI from <http://id.loc.gov/authorities/subjects.html>; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied.

### Subject: geographic

Optional, Repeatable

**MARC Location**: 651

**Description**: Geographic subject as found in LCSH; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied from LC/OCLC.

### Subject: geographic URI

Optional, Repeatable

**Description**: For subjects in LCSH, give the URI from <http://id.loc.gov/authorities/subjects.html>; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied.

### Subject: genre/form

Optional, Repeatable

**MARC Location**: 655

**Description**: Genre/form term as found in LCSH or Getty Art & Architecture Thesaurus <http://www.getty.edu/research/tools/vocabularies/aat/>; unlikely to appear in this form in dealer or narrative library descriptions, may be supplied.

### Subject: genre/form URI

Optional, Repeatable

**Description**: For genre/form terms in LCSH, give the URI from <http://id.loc.gov/authorities/subjects.html> or <http://id.loc.gov/authorities/genreForms.html>; for genre/form terms in AAT, give the URI in the form <http://vocab.getty.edu/aat/> {AAT ID\#} (more information available at <http://vocab.getty.edu/>); unlikely to appear in this form in dealer or narrative library descriptions, may be supplied.

### Keywords

Required, Repeatable

**MARC Location**: ???

**Instructions**: Keywords are listed [here](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/keywords.md).  There are seven groups: Book Type, Century, Culture, Descriptive term, Geography, Subject, and Other.

Add one keyword per column. You should be able to add at least one from Book Type, Century, Culture, and Geography. Add Descriptive Terms, Subjects, and Others as relevant. Copy and paste terms to avoid misspellings.

Keywords are to help users find the books. So consider what terms a user might select to try to find this book or a book like it, in addition to considering which terms apply to this book.

# Appendices

## Image names
<!-- PMSS is not supplying this -->

Anything to be photographed needs a name-value. Values must must not repeat within a single manuscript.
The value will usually be a page number (e.g., 1) or a folio number (e.g., 2r). See [Foliation/Pagination].

For covers and flyleaves, identify the location or number as relevant (e.g., Inside Front Cover, Flyleaf 1 recto). If pages are labeled using something other than Arabic numerals (e.g., Roman numerals or letters) use whatever is on the page. Front and back flyleaves should be noted as such.

The subsections below supply additional instructions for data entry in this column.

### External Structure

  - Spine
  - Fore edge
  - Top edge
  - Bottom edge

### Covers and Flyleaves

Front matter:

  - Front cover
  - Inside front cover
  - \[Flyleaf 1 recto\]
  - \[Flyleaf 1 verso\]

Back matter:

  - \[Flyleaf 1 recto\]
  - \[Flyleaf 1 verso\]
  - Inside back cover
  - Back cover

When flyleaves are numbered, identify the leaf as a flyleaf and add the folio number after, separated by a semicolon:

  - \[Flyleaf 1 recto; fol. 239\]

### Text block (constituent leaves not including the flyleaves)

Leaves foliated or paginated and attached:

  - 1r
  - 1v
  - IIIr
  - IIIv
  - IVr
  - IVv
  - Ar
  - Av
  - Br
  - Bv

If pages are labeled using something other than Arabic numerals (e.g., Roman numerals or letters) use whatever is on the page. If leaves are foliated in Arabic numerals, use [these template values](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/folio-values.csv).

Leaves attached but not foliated/paginated:

  - \[1r\]
  - \[1v\]
  - \[2r\]
  - \[2v\]

Leaves foliated/paginated but detached:

  - 1r (unattached)
  - 1v (unattached)

Foliation skips a folio (i.e., 7, unnumbered, 8, not 7, unnumbered, 9):

  - Unnumbered recto
  - Unnumbered verso

(When more than one in a row, add ‘i’ etc. after ‘Unnumbered’)

Stubs included in foliation:

  - 15r (Stub)
  - 15v (Stub)

Stubs not included in foliation:

  - Stub recto
  - Stub verso

(When more than one in a row, add ‘i’ etc. after ‘Stub’)

Foldouts, unfoliated/unpaginated:

  - Foldout recto (folded)
  - Foldout verso (folded)
  - Foldout recto (unfolded)
  - Foldout verso (unfolded)

(When more than one in a row, add ‘i’ etc. after ‘Foldout’)

Foldouts, foliated/paginated:

  - 1r (Foldout, folded)
  - 1v (Foldout, folded)
  - 1r (Foldout, unfolded)
  - 1v (Foldout, unfolded)

Insert, not included in foliation/pagination, attached:

  - Insert recto
  - Insert verso

(When more than one in a row, add ‘i’ etc. after ‘Insert’)

Insert, not included in foliation/pagination, not attached:

  - Loose leaf recto
  - Loose leaf verso

(When more than one in a row, add ‘i’ etc. after ‘Loose leaf’)

Fragments or cuttings:

  - Loose leaf recto
  - Loose leaf verso

Multiple fragments or cuttings:

  - Loose leaf 1 recto
  - Loose leaf 1 verso
  - Loose leaf 2 recto
  - Loose leaf 2 verso

Fragments or cuttings when you can’t determine recto and verso:

  - Loose leaf Side 1
  - Loose leaf Side 2

Multiple fragments or cuttings without identifiable recto/verso:

  - Loose leaf 1 Side 1
  - Loose leaf 1 Side 2
  - Loose leaf 2 Side 1
  - Loose leaf 2 Side 2

## Special instructions for Books of Hours

Examples of section descriptions (for descriptions and page-level metadata):

### TOC elements

  - Calendar
  - Calendar, in French
      - i.e. only include the language if it is not Latin
      - in general any vernacular prayers or rubrics should be pointed out
  - Gospel Lessons
  - Passion according to John
  - Hours of the Virgin, Use of Rome
  - Hours of the Virgin, Use of Rome, intercalated with the Hours of the Cross and Hours of the Holy Spirit
      - We have decided **not** to list the individual hours within the office. Even if they begin with miniatures
  - Penitential Psalms, Litany, and Prayers
  - Prayer, Obsecro te
  - Prayer, O intemerata
  - Prayer, Salva sancta facies
  - Prayers, beginning with Salva sancta facies
  - Office of the Dead
  - Suffrages
      - individual suffrages **not** listed as TOC element

### DECO elements

  - Inhabited initial Q, a monk
      - inhabited = figures that are decorative only, with no precise subject, i.e. a saint
  - Historiated initial D, Annunciation
      - historiated = identifiable figure, i.e. Saint Peter, or a scene, i.e. Martyrdom of Saint Paul
  - Small miniature, Annunciation
  - Large miniature, Annunciation
  - Full-page miniature, Annunciation
      - the distinction is that a full-page miniature has no lines of text on the page

Sometimes miniatures are divided into subsections, for example a full-page miniature that depicts four different stages of a character’s story within the same frame. In this case identify the size of the miniature, then each section individually separated by semicolons. Each group of sections (e.g., top row, bottom row) should be preceded by a directional cue describing which direction the images are to be read.  The following example is from a Hebrew manuscript, so images are to be read upper to lower, right to left:

  - Full-page miniature, upper right to left, Moses with Jethro’s flock (Exodus 3:1); Moses and the Burning Bush (Exodus 3:5); lower right to left, Moses answers the Lord, holding up his rod – a shepherd’s staff (Exodus 4:2); his rod turns into a serpent (Exodus 4:4); Moses holds the serpent (Exodus 4:4)

Names of standard iconographies:

  - Annunciation
  - Visitation
  - Nativity
  - Annunciation to the Shepherds
  - Adoration of the Magi
  - Presentation in the Temple
  - Flight into Egypt
  - Massacre of the Innocents
  - Coronation of the Virgin
  - Agony in the Garden
  - Crucifixion
  - Pentecost
  - Saint John the Baptist
  - Saint Catherine
      - we have decided to include Saint before proper names of saints
