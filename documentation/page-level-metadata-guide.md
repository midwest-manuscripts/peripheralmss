<!-- DOCUMENT HISTORY:
  this markdown file was generated with pandoc v. 2.8 on 20200624
  input source: docx, exported from this GoogleDoc:
  https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing

  markdown headings, lists, and other formatting conventions are supplied manually
  subsequently re-generated as GitHub-flavored Markdown, again with pandoc
  this fixes rendering of tables and other document formatting on GitHub
-->

*These guidelines are based on the work of the Bibliotheca
Philadelphiensis Project. The original Bibliotheca Philadelphiensis
documentation may be viewed
[here](https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing)*

# Guidelines for Page-Level Metadata

This document provides guidelines for entry of **page**-level metadata
fields (sheet 2 of the template spreadsheet). For guidance on entry of
administrative information and **collection**- and **item**-level
metadata fields (sheet 1 of the template spreadsheet) see the [Item-Level Metadata
Guidelines](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/item-level-metadata-guide.md).

The first field to be completed on this sheet is the **Counting method** (**cell B1**).
In this field indicate whether the manuscript is paginated (each page is numbered) or
foliated (each leaf/folio is numbered).

Instructions for the remaining fields are organized by column in the sections below.
Complete one row for each image captured.
At the end of this document we supply special instructions for Books of Hours.

If you have any questions about how to describe something not covered in
these guidelines please contact Liz Hebbard (ehebbard@iu.edu).

## column A: SERIAL\_NUM

Unique sequence number for the images. Images will be displayed in this
order. The number itself does not display.

## column B: DISPLAY PAGE

The label for this image. Anything to be photographed needs to have a
value here. Values must must not repeat within a single manuscript.

The value will usually be a page number (e.g., 1) or a folio number
(e.g., 2r). For covers and flyleaves, identify the location or number as
relevant (e.g., Inside Front Cover, Flyleaf 1 recto). If pages are
labeled using something other than Arabic numerals (e.g., Roman numerals
or letters) use whatever is on the page. Front and back flyleaves should
be noted as such.

Further instructions follow in the subsections below.

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

When flyleaves are numbered, identify the leaf as a flyleaf and add the
folio number after, separated by a semicolon:

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

If pages are labeled using something other than Arabic numerals (e.g.,
Roman numerals or letters) use whatever is on the page. If leaves are
foliated in Arabic numerals, use [these template
values](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/folio-values.csv).

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

## column C: FILE\_NAME

If item has been digitized or a prescribed filename is desired, please
provide it here. Otherwise, FILE\_NAME may be left blank.

## column D: TAGX

Type for an extra label of this image:

  - TOC1, TOC2, TOC3 — table of contents entry (Value required)
  - INC — Incipit for the text in corresponding TOCX (Value required)
  - EXP — Explicit for the text in the corresponding TOCX (Value
    required)
  - DECO — Any decoration: illustration, illumination, table, or figure.
    Includes bookplates (bookplate information should also be provided
    in the Provenance field if relevant) (Value required)
  - BLANK — page or folio side is blank (Value not required; values
    ignored)

Further instructions follow in the subsections below. For **Books of
Hours** see the special instructions at the end of this file.

### TOC

In Latin transcribed and/or supplied title in square brackets.

### INC and EXP

Include only for works where they are especially helpful or meaningful.
Do not provide these for Books of Hours, Bibles, or other standard
texts.

On the spreadsheet, INC and EXP for a text belong in the same row as the
TOC for the text. The folio number of the location of the incipit and
explicit go inside the field, after the text, in square brackets, and
following the formatting for folio numbering described earlier in this
document:

| **DISPLAY PAGE** | **FILE\_NAME** | **TAG1** | **VALUE1** | **TAG2** | **VALUE2**               | **TAG3** | **VALUE3**              |
| :--------------- | :------------- | :------- | :--------- | :------- | :----------------------- | :------- | :---------------------- |
| 5v               | 1234-9473.tif  | TOC1     | Title      | INC      | Here begins. \[fol. 5v\] | EXP      | Here ends. \[fol. 31r\] |

In those instances when there is more than one TOC on the same page, the
INC and EXP come after the corresponding TOC. It is fine if some TOCs
lack INC or EXP:

> TOC1 INC TOC2 INC EXP TOC3 EXP \[etc.\]

### DECO

Brief description of the decoration or illustration. If there is a type
of decoration include the type, followed by a comma, followed by a
description: Diagram, furnace. Anything that can be described well in
the manuscript-level **Decoration** field does not belong in the
page-level **DECO** field, e.g., “Alternating red and blue initials
throughout.”

## column E: VALUEX

\[required if corresponding **TAG** is one of TOC1, TOC2, TOC3, INC,
EXP, or DECO\]

Value for tag to the left: “Chapter 1”, “1 March 1834”, “Adam and Eve in
the Garden”, “Table of income”.

Values next to BLANK tags will be ignored.

# Special instructions for Books of Hours

Examples of section descriptions (for descriptions and page-level
metadata):

## TOC elements:

  - Calendar
  - Calendar, in French
      - i.e. only include the language if it is not Latin
      - in general any vernacular prayers or rubrics should be pointed
        out
  - Gospel Lessons
  - Passion according to John
  - Hours of the Virgin, Use of Rome
  - Hours of the Virgin, Use of Rome, intercalated with the Hours of the
    Cross and Hours of the Holy Spirit
      - We have decided **not** to list the individual hours within the
        office. Even if they begin with miniatures
  - Penitential Psalms, Litany, and Prayers
  - Prayer, Obsecro te
  - Prayer, O intemerata
  - Prayer, Salva sancta facies
  - Prayers, beginning with Salva sancta facies
  - Office of the Dead
  - Suffrages
      - individual suffrages **not** listed as TOC element

## DECO elements:

  - Inhabited initial Q, a monk
      - inhabited = figures that are decorative only, with no precise
        subject, i.e. a saint
  - Historiated initial D, Annunciation
      - historiated = identifiable figure, i.e. Saint Peter, or a scene,
        i.e. Martyrdom of Saint Paul
  - Small miniature, Annunciation
  - Large miniature, Annunciation
  - Full-page miniature, Annunciation
      - the distinction is that a full-page miniature has no lines of
        text on the page

Sometimes miniatures are divided into subsections, for example a
full-page miniature that depicts four different stages of a character’s
story within the same frame. In this case identify the size of the
miniature, then each section individually separated by semicolons. Each
group of sections (e.g., top row, bottom row) should be preceded by a
directional cue describing which direction the images are to be read.
The following example is from a Hebrew manuscript, so images are to be
read upper to lower, right to left:

  - Full-page miniature, upper right to left, Moses with Jethro’s flock
    (Exodus 3:1); Moses and the Burning Bush (Exodus 3:5); lower right
    to left, Moses answers the Lord, holding up his rod – a shepherd’s
    staff (Exodus 4:2); his rod turns into a serpent (Exodus 4:4); Moses
    holds the serpent (Exodus 4:4)

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
