<!-- DOCUMENT HISTORY:
  this markdown file was generated with pandoc v. 2.8 on 20200624
  input source: docx, exported from this GoogleDoc:
  https://docs.google.com/document/d/1zeUkzmy-3kpK-egqko_IHWZJ992qEnMcgIdzF6Syz4M/edit?usp=sharing

  markdown headings, lists, and other formatting conventions are supplied manually
-->

# FINAL DRAFT---BiblioPhilly Spreadsheet Metadata Guidelines---FINAL DRAFT

**Revised 24 April 2017**

For each row in the project spreadsheet for a single manuscript, the
notes below suggest how that information might appear in a dealer
description or library narrative description of a manuscript. For
metadata included in MARC records, there are notes about possible
relevant MARC fields and subfields. Begin the notes in each cell with a
capital letter.

**In cases where you have multiple items but a field is not
Repeatable**, put all items in the single field and separate the items
with a semi-colon.

## Administrative Contact
(Required)

**Description:** Name of the BiblioPhilly liaison at a partner
institution; consistent for all manuscripts from a single institution.

## Administrative Contact Email
(Required)

**Description:** Email address of the BiblioPhilly liaison at a partner
institution; consistent for all manuscripts from a single institution.

## Metadata Creator
(Required)

**Description:** Name of the person entering information into the
spreadsheet for a particular manuscript.

## Metadata Creator Email
(Required)

**Description:** Email address of the person entering information into
the spreadsheet for a particular manuscript.

## Repository Country
(Optional)

**MARC Location:** Possibly 852 subfield e

**Description:** Country of the holding library; United States for all
BiblioPhilly partner institutions.

## Repository City
(Required)

**MARC Location:** 852 subfield e

**Description:** Municipality of the holding library; consistent for all
manuscripts from a single institution.

## Holding Institution
(Optional)

**MARC Location:** 852 subfield a

**Description:** Organization name if library is part of a larger
organization such as a university.

## Repository Name
(Required)

**MARC Location:** 852 subfield b

**Description:** Library name.

## Source Collection
(Optional)

**MARC Location:** Possibly 500, possibly 710

**Description:** Name of a named collection within the library.

Note: For FLP, the correct format of the Source Collection is John
Frederick Lewis Collection of European Manuscripts

## Call Number/ID
(Required)

**MARC Location:** 099, 852 subfield j

**Description:** Format varies by library; not included in dealer
descriptions; possibly in headings in library description.

## Record URL
(Optional)

**Description:** URL format varies by library; for records in an online
catalog, possibly available when viewing record online.

## Alternate ID
(Optional)

**MARC Location:** 001 in Penn records

**Description:** Internal control number such as Penn's BibID or URN
such as DOI, PURL, or ARK; to be supplied by holding library.

## Alternate ID Type (Required for Manuscripts with Alternate IDs)

**Description:** Possibilities include DOI, PURL, ARK, BibID; to be
supplied by holding library.

## Manuscript Name
(Required)

**MARC Location:** 245

**Description:** Title representing the manuscript volume as a whole; if
the whole volume consists of one or two works, the single title or two
titles separated by a semicolon; if a collection of smaller works, a
supplied title such as Recipe book; probably in the headings of dealer
or library descriptions.

## Author Name
(Optional, Repeatable)

**MARC Location:** Possibly 100, possibly 110

**Description:** When a manuscript contains a work or works with
personal or corporate authors, use the LC or VIAF authority heading or
record an unauthorized name in authority form; unlikely to appear in
this form in dealer or narrative library descriptions, probably needs to
be supplied from LC/OCLC.

## Author URI
(Optional, Repeatable)

**Description:** For authors in the LC NAF, give the URI from
[[http://id.loc.gov/authorities/names.html]{.underline}](http://id.loc.gov/authorities/names.html);
for creators in VIAF give the permalink from
[[http://viaf.org/]{.underline}](http://viaf.org/); unlikely to appear
in dealer or narrative library descriptions, probably needs to be
supplied. If you have verified that the author name does not have an
authorized form in LC NAF or VIAF, enter N/A.

## Translator Name
(Optional, Repeatable)

**MARC Location:** Possibly 245, possibly 500, possibly 700

**Description:** When a manuscript contains the name of a translator, or
when the translator of a text has been identified independently, use the
LC or VIAF authority heading or record an unauthorized name in authority
form; unlikely to appear in this form in dealer or narrative library
descriptions, probably needs to be supplied from LC/OCLC.

## Translator URI
(Optional, Repeatable)

**Description:** For translators in the LC NAF, give the URI from
[[http://id.loc.gov/authorities/names.html]{.underline}](http://id.loc.gov/authorities/names.html);
for translators in VIAF give the permalink from
[[http://viaf.org/]{.underline}](http://viaf.org/); unlikely to appear
in dealer or narrative library descriptions, probably needs to be
supplied. If you have verified that the translator name does not have an
authorized form in LC NAF or VIAF, enter N/A.

## Artist Name
(Optional, Repeatable)

**MARC Location:** Possibly 500, possibly 700

**Description:** When a manuscript contains the name of an illuminator
or illustrator, or when the work of an artist in a manuscript has been
identified independently, use the \*\*ULAN\*\*, LC, or VIAF authority
heading or record an unauthorized name in authority form; unlikely to
appear in this form in dealer or narrative library descriptions,
probably needs to be supplied from LC/OCLC.

## Artist URI
(Optional, Repeatable)

**Description:** For artists in ULAN, give the ID from
[[http://www.getty.edu/research/tools/vocabularies/ulan/]{.underline}](http://www.getty.edu/research/tools/vocabularies/ulan/);
for artists in LC NAF, give the URI from
[[http://id.loc.gov/authorities/names.html]{.underline}](http://id.loc.gov/authorities/names.html);
for artists in VIAF give the permalink from
[[http://viaf.org/]{.underline}](http://viaf.org/); unlikely to appear
in dealer or narrative library descriptions, probably needs to be
supplied. If you have verified that the artist name does not have an
authorized form in ULAN, LC NAF, or VIAF, enter N/A.

## Former Owner Name
(Optional, Repeatable)

**MARC Location:** Possibly 500, possibly 561, possibly 700

**Description:** When a manuscript contains the name of a former owner,
or when a former owner of a manuscript has been identified
independently, use the LC or VIAF authority heading or record an
unauthorized name in authority form; unlikely to appear in this form in
dealer or narrative library descriptions, probably needs to be supplied
from LC/OCLC.

## Former Owner URI
(Optional, Repeatable)

**Description:** For former owners in the LC NAF, give the URI from
[[http://id.loc.gov/authorities/names.html]{.underline}](http://id.loc.gov/authorities/names.html);
for former owners in VIAF give the permalink from
[[http://viaf.org/]{.underline}](http://viaf.org/); unlikely to appear
in dealer or narrative library descriptions, probably needs to be
supplied. If you have verified that the former owner name does not have
an authorized form in LC NAF or VIAF, enter N/A.

## Provenance
(Optional)

**MARC Location:** 541, 561

**Description:** Additional information beyond former owner names,
including family ownership, former libraries or geographical locations,
marks of provenance such as bookplates, and sale information.

## Date (single) 
(Optional, but one type of numerical date metadata must
be supplied; Repeatable)

**MARC Location:** Fixed field 008/07-10, possibly 245 subfield f,
possibly 260 subfield c

**Description:** Year for a dated manuscript, or of a section of a
manuscript consisting of originally separate manuscripts copied at
different times, which each section provided its own Date (single) or
Date (range); probably in the headings of a dealer or library
description, otherwise in notes; if the single date is given as a
narrative phrase (see Date (narrative) below), supply a year here; enter
as the year only without additional words.

## Date (range) start
(Optional, but required if a Date (narrative) entry
is present, and one type of numerical date metadata must be supplied;
Repeatable)

**MARC Location:** Fixed field 008/07-10, possibly 245 subfield f,
possibly 260 subfield c

**Description:** Beginning year for a manuscript completed over an
extended period of time or the earliest year of a section of a
manuscript consisting of originally separate manuscripts copied at
different times, with each section provided its own Date (single) or
Date (range); probably in the headings of a dealer or library
description, otherwise in notes; if the range is given as a narrative
phrase (see Date (narrative) below), supply a starting year here; enter
as the year only without additional words.

## Date (range) end 
(Optional, but required if a Date (narrative) entry
is present, and one type of numerical date metadata must be supplied;
Repeatable)

**MARC Location:** Fixed field 008/11-14, possibly 245 subfield f,
possibly 260 subfield c

**Description:** Ending year for a manuscript completed over an extended
period of time or the latest year of a section of a manuscript
consisting of originally separate manuscripts copied at different times,
with each section provided its own Date (single) or Date (range);
probably in the headings of a dealer or library description, otherwise
in notes; if the range is given as a narrative phrase (see Date
(narrative) below), supply an ending year here; enter as the year only
without additional words.

## Date (narrative)
(Optional, NOT Repeatable)

**MARC Location:** 500 notes

**Description:** Phrase from a dealer or library description suggesting
an exact date, part of a century, a century, or a range of years larger
than a century, or single approximate year for a manuscript described as
"Circa" with a single year; multiple dates in the previous fields may be
described narratively together here (e.g., "12th century and 15th
century"). Complete descriptions will include both a Date (narrative)
and a Date (range) or a Date (single). Enter the phrase as given in this
row and supply start and end dates in the appropriate rows, as in the
following examples:

  **Date (narrative)**              **Supply Date (range) start**   **Supply Date (range) end**
  --------------------------------- ------------------------------- -----------------------------
  14th century                      1300                            1399
  Early 14th century                1300                            1315
  First quarter 14th century        1300                            1325
  Fourth quarter 14th century       1375                            1399
  Mid-14th century                  1340                            1360
  14th century after 1320           1320                            1399
  Late 14th century                 1385                            1399
  Late 14th or early 15th century   1385                            1415
  Mid-14th to early 15th century    1340                            1415
  14th or 15th century              1300                            1499

## Place of Origin
(Required, Repeatable)

**MARC Location:** 260 subfield a, possibly additional details in 500
notes

**Description:** Place where a manuscript was copied or a suggestion,
possibly very broad, of where it might have been copied; often in dealer
and library description headings; include cardinal specifications (for
example, Northern France); may be followed by a question mark for
conjectural locations. Multiple locations may be entered for codices
containing multiple manuscripts with different origins bound together.

## Origin Details
(Optional)

**MARC Location:** 500 notes

**Description:** Additional details about where the manuscript was
created.

## Description
(Optional)

**MARC Location:** 520

**Description:** Abstract or summary of no more than a couple of
sentences summarizing the content of the manuscript as a whole.

## Language
(Required, Repeatable)

**MARC Location:** Fixed field 008/35-37, 041, 546

**Description:** Language or languages in which the manuscript is
written.

## Foliation/Pagination
(Optional)

**MARC Location:** 500 notes

**Description:** How the leaves or pages of the manuscript are numbered
(in foliation, each leaf is numbered once; in pagination, both the recto
and verso side of each leaf are numbered), and where the numbers appear
on the leaves, such as *upper right recto* or *lower outer corners*.

## Flyleaves & Leaves
(Optional)

**Description:** Formula showing the numbers of flyleaves and leaves, in
the format \[front flyleaves\]+\[leaves\]+\[back flyleaves\], for
example ii+113+iii

## Layout
(Optional)

**MARC Location:** 500 notes

**Description:** The easiest layout details to capture are number of
columns and number of lines per page, if those are generally consistent
throughout the manuscript or in sections of the manuscript. Information
about how a page is ruled and by what means (drypoint, lead, ink) also
goes here.

## Colophon
(Optional)

**MARC Location:** 500 notes

**Description:** Statement at the end of some manuscripts recording the
date, place, scribe, and/or reason for production of the manuscript.
Potential source of Date and Place of origin information for the
spreadsheet, when present.

## Collation
(Optional)

**MARC Location:** 500 notes

**Description:** Information about the structure of the volume in terms
of numbers of gatherings and numbers of leaves per gathering, often
presented as a formula.

## Script
(Optional, Repeatable)

**MARC Location:** 500 notes

**Description:** Information about the type of lettering used in the
manuscript (for example, Caroline minuscule, Gothic). Information about
hands (a hand is an individual version of a script written by a single
scribe) and scribes may also be entered here. Multiple hands may write
in the same script.

## Decoration
(Optional)

**MARC Location:** Fixed field 008/18-21, 500 notes

**Description:** Summary of information about formal visual elements of
the manuscript (including illuminations, diagrams, decorated initials,
colored headings and paragraph marks) and informal visual elements added
later to the manuscript (including drawings, sketches, and manicules).
Not a page-level list of visual elements.

## Binding
(Optional)

**MARC Location:** 500 notes

**Description:** Information about the cover (such as type of leather or
fabric), its ornamentation (such as gilt or blind, tooled or stamped),
fastenings (such as clasps or ties), and damage or repairs to the cover.

## Watermarks
(Optional, Repeatable)

**MARC Location:** 500 notes

**Description:** For manuscripts written on paper, descriptions of the
watermarks in the manuscript, possibly with citations to reference
sources such as Briquet and Piccard.

## Catchwords
(Optional)

**MARC Location:** 500 notes, often with collation notes

**Description:** Information about the number and location of
catchwords.

## Signatures
(Optional)

**MARC Location:** 500 notes, often with collation notes

**Description:** Information about the numbers or letters used to ensure
correct order of gatherings in the binding process, often found on the
first recto or last verso of a gathering.

## Notes
(Optional, Repeatable)

**MARC Location:** 500

**Description:** Possible entry for notes not explicitly covered by the
spreadsheet, such as condition notes. Each note should be placed in a
different cell.

## Support material
(Required)

**MARC Location:** 300 subfield b

**Description:** Material on which the manuscript is written:
*parchment*, *paper*, or *mixed* if both parchment and paper. Any other
material, identify by name.

## Page dimensions
(Optional, Repeatable)

**MARC Location:** 300 subfield c

**Description:** Maximum height and width of manuscript pages in
millimeters, in the following form: 280 x 210 mm (no period after mm).
If originally separate manuscripts of markedly different dimensions have
been bound together in a volume, repeat for the different page sizes. If
dimensions are provided in a manuscript description with no comment,
assume they are page dimensions.

## Bound dimensions
(Optional)

**MARC Location:** Possibly 300 subfield c

**Description:** Maximum height and width of bound volume in
millimeters, in the following form: 290 x 220 mm (no period after mm).

## Related resource
(Optional, Repeatable)

**MARC Location:** Possibly 773 subfield t, 856 subfield z

**Description:** Related resources may include the name of a larger
collection to which this manuscript belongs; a digital facsimile of the
manuscript; or a finding aid or catalog record for the manuscript. Also
includes citations to other bibliographic resources, such as essays or
articles about a manuscript. For citations, use the **modified Chicago
Style for notes** (with Last Name, First Name for first author; hyphens
instead of en-dashes for page ranges; p. and pp. for page numbers), as
in the following examples:

> De Ricci, Seymour, with the assistance of W. J. Wilson, *Census of
> Medieval and Renaissance Manuscripts in the United States and Canada*,
> vol. 2 (New York: H. W. Wilson, 1935-40), p. 2040, no. 91.
>
> Free Library of Philadelphia, *A Descriptive Catalogue of the John
> Frederick Lewis Collection of European Manuscripts in the Free Library
> of Philadelphia*, compiled by Edwin Wolf, 2nd, with an introduction by
> Dr. A.S.W. Rosenbach (Philadelphia: The Library, 1937), p. 142, no.
> 127.

\[note that the Wolf catalogue of the Lewis Collection is added here and
NOT in the Alternate ID field because its catalog numbers simply repeat
the Lewis shelfmark numbers\]

> Branner, Robert, *Manuscript Painting in Paris During the Reign of
> Saint Louis: A Study of Styles* (Berkeley: University of California
> Press, 1977), p. 82.
>
> Branner, Robert, \"The Johannes Grusch Atelier and the Continental
> Origins of the William of Devon Painter,\" *Art Bulletin* 54, no. 1
> (1972): p. 30 (article pp. 24-30).
>
> Peterson, Elizabeth Anne, "The Textual Basis for Visual Errors in
> French Gothic Psalter Illustration," in *The Early Medieval Bible: Its
> Production, Decoration and Use*, ed. Richard Gameson (Cambridge:
> Cambridge University Press, 1994), pp. 182-83 (article pp. 177-204).

\[note that the page or page range where a manuscript is mentioned is
given first, then the full range of the article or chapter is given
within brackets. Hyphens (not en dashes) should be used to indicate page
ranges.\]

## Related resource URL
(Optional, Repeatable)

**MARC Location:** 856 subfield u

**Description:** URL for the related resource given in the previous row.

## Subject: names
(Optional, Repeatable)

**MARC Location:** 600

**Description:** When a manuscript has an individual or group as its
subject, use the LCNAF or VIAF authority heading or record an
unauthorized name in authority form; unlikely to appear in this form in
dealer or narrative library descriptions, may be supplied from LC/OCLC.

## Subject: names URI
(Optional, Repeatable)

**Description:** For subjects in the LCNAF, give the URI from
[[http://id.loc.gov/authorities/names.html]{.underline}](http://id.loc.gov/authorities/names.html);
for creators in VIAF give the permalink from
[[http://viaf.org/]{.underline}](http://viaf.org/); unlikely to appear
in dealer or narrative library descriptions, may be supplied.

## Subject: topical
(Optional, Repeatable)

**MARC Location:** 650

**Description:** Topical subject as found in LCSH; unlikely to appear in
this form in dealer or narrative library descriptions, may be supplied
from LC/OCLC.

## Subject: topical URI
(Optional, Repeatable)

**Description:** For subjects in LCSH, give the URI from
[[http://id.loc.gov/authorities/subjects.html]{.underline}](http://id.loc.gov/authorities/subjects.html);
unlikely to appear in this form in dealer or narrative library
descriptions, may be supplied.

## Subject: geographic
(Optional, Repeatable)

**MARC Location:** 651

**Description:** Geographic subject as found in LCSH; unlikely to appear
in this form in dealer or narrative library descriptions, may be
supplied from LC/OCLC.

## Subject: geographic URI
(Optional, Repeatable)

**Description:** For subjects in LCSH, give the URI from
[[http://id.loc.gov/authorities/subjects.html]{.underline}](http://id.loc.gov/authorities/subjects.html);
unlikely to appear in this form in dealer or narrative library
descriptions, may be supplied.

## Subject: genre/form
(Optional, Repeatable)

**MARC Location:** 655

**Description:** Genre/form term as found in LCSH or Getty Art &
Architecture Thesaurus
([[http://www.getty.edu/research/tools/vocabularies/aat/]{.underline}](http://www.getty.edu/research/tools/vocabularies/aat/));
unlikely to appear in this form in dealer or narrative library
descriptions, may be supplied.

## Subject: genre/form URI
(Optional, Repeatable)

**Description:** For genre/form terms in LCSH, give the URI from
[[http://id.loc.gov/authorities/subjects.html]{.underline}](http://id.loc.gov/authorities/subjects.html)
or
[[http://id.loc.gov/authorities/genreForms.html]{.underline}](http://id.loc.gov/authorities/genreForms.html);
for genre/form terms in AAT, give the URI in the form
[http://vocab.getty.edu/aat/](http://vocab.getty.edu/aat/) \{AAT ID\#} 
(more information available at
[http://vocab.getty.edu/](http://vocab.getty.edu/)); unlikely to appear in this form in dealer or
narrative library descriptions, may be supplied.
