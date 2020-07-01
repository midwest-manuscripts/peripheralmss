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

# Structural Metadata Guidelines

Fill in fields for each page or item in the manuscript to be digitized.

## Counting Method

Indicates if the manuscript is paginated (each page is numbered) or
foliated (each leaf/folio is numbered)

## SERIAL\_NUM

Unique sequence number for the images. Images will be displayed in OPenn
in this order. The number itself does not display.

## DISPLAY PAGE

The label for this image. It will usually be a page number (e.g., 1) or
a folio number (e.g., 2r). For covers and flyleaves, identify the
location or number as relevant (e.g., Inside Front Cover, Flyleaf 1
recto). If pages are labeled using something other than Arabic numerals
(e.g., Roman numerals or letters) use whatever is on the page. A guide
for possible values are located on the other side of this page. Anything
to be photographed needs to have a value here. **Note:** Display pages
must be unique in a single manuscript. Front and back flyleaves should
be noted as such, and

## FILE\_NAME

If item has been digitized or a prescribed filename is desired, please
provide it here. Otherwise, FILE\_NAME may be left blank.

## TAGX

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

## VALUEX

\[required if corresponding **TAG** is one of TOC1, TOC2, TOC3, INC,
EXP, or DECO\]

Value for tag to the left: “Chapter 1”, “1 March 1834”, “Adam and Eve in
the Garden”, “Table of income”.

Values next to BLANK tags will be ignored.

## DISPLAY PAGE

Enter a **display page** value for each image. Typical values are
supplied in the subsections below.

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

## Text block (constituent leaves not including the flyleaves)

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

<!-- I'm uncertain what the progression from Arabic to Roman to Alpha is supposed to signify. irc -->

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

If you have any questions about how to describe something not covered in
these guidelines please contact Liz Hebbard (ehebbard@iu.edu).
