<!-- DOCUMENT HISTORY:
  this markdown file was generated with pandoc v. 2.8 on 20200624
  input source: docx, exported from these Google Docs:
  https://docs.google.com/document/d/1zeUkzmy-3kpK-egqko_IHWZJ992qEnMcgIdzF6Syz4M/edit?usp=sharing
  https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing

  markdown headings, lists, and other formatting conventions are supplied manually
  subsequently re-generated as GitHub-flavored Markdown, again with pandoc
  this fixes rendering of tables and other document formatting on GitHub
-->

# Metadata Guide
## The Peripheral Manuscripts Project

These guidelines derive originally from the Bibliotheca Philadelphiensis Project.
The original Bibliotheca Philadelphiensis documentation may be viewed [here](https://docs.google.com/document/d/1HzfYAgNuJaRKXcZ1rYE-0hS5_TxidWDNLN6X2cVFpAM/edit?usp=sharing) and [here](https://docs.google.com/document/d/1zeUkzmy-3kpK-egqko_IHWZJ992qEnMcgIdzF6Syz4M/edit?usp=sharing).

For instructions in style and usage see the [Style Guide](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/style-guide.md).

## Contents:

I. Project Taxonomy
- A. Locations & objects > Manuscripts in context
- B. Project Taxonomy > Classification > Collection
- C. Project Taxonomy > Classification > Object
  - i. Object > Feature > Identification
  - ii. Object > Feature > Analytic description
  - iii. Object > Feature > Agents
  - iv. Object > Feature > Contents
  - v. Object > Feature > Keywords
  - vi. Object > Association item
- D. Project Taxonomy > Event

II. Appendices
- A. Project Taxonomy
- B. Keywords
- C. Image Names
- D. OCHRE Predefinitions

## I. OCHRE Project Taxonomy

The fields given in the guide below correspond to the organization within the project database in OCHRE (Online Cultural and Historical Research Environment) and are reproduced in that schema for the ease of data mapping for this project between OCHRE and the project’s public-facing image and description repository. When possible, corresponding MARC fields are given for partners mapping to other environments in the appendix.

In general practice, the project team strives for efficient description by exploiting the hierarchical structure of item records within OCHRE, and the inheritance of descriptive metadata from parent items to child items within that structure. Codices are described as parent items with properties giving general comments about layout and decoration throughout the volume and a description field that provides a narrative list of contents. Subitems of a codex are its codicological units, and each subitem should contain the Feature>Identification and Feature>Analytic Description fields in which the subitem differs from the parent item, and at minimum, the following Feature>Contents properties: Language, Scribal title **or** Modern title **or** Supplied title, Incipit, Explicit, Folio range, Image Range start, and Image Range end. Subitems with multiple texts will have repeated instances of the Feature>Contents section, one for each content item. For in situ binding fragments, subitems are created for each fragment only in the case that they come from different original manuscripts. For materially distinct binding fragment from the same original source (for example, front and back pastedowns), these are described as one subitem with iterated Feature>Contents sections, and aggregated information under Feature>Analytic Description, for example:

  Page dimensions (in mm): 313 x 200 (front pastedown); 307 x 198 (back pastedown)

A complete project taxonomy is given in the appendix.

## A. Locations & Objects > Manuscripts in context

The following structure is flexible within OCHRE and its hierarchical structure. All items are organized by **Repository Country > Repository City**. For individual partners, institutional structure and item context is suggested by the number of levels between **Repository City** and a given item, and may include **Holding institution, Repository, and Collection**. These levels may vary depending on the institution or a given item at that institution.

### Repository Country

Country of the holding institution; United States for all partner institutions. Country appears at the highest level under *Locations & objects > Manuscripts in context.*

### Repository State, City

Municipality of the holding institution. **Repository State** appears at the second highest level under *Locations & objects > Manuscripts in context*, followed by **Repository City**.

### Holding Institution

Holding institution applies when the repository is part of a larger organization such as a university. Do not use abbreviations. For museums or private collectors that do not have a larger organization, skip to **Repository**.

### Repository

Repository name in full; do not use abbreviations. For private collectors, a personal name or an identifier for those collectors wishing to remain anonymous.

### Collection

Name of a named collection within the repository. Appears within OCHRE > Locations & Objects between a repository and the individual items within the identified collection.

## Location or object (default OCHRE fields)
### Name

Identify the institution in the name field and a one/two word descriptor of contents, eg.: SMC MS 2, Miscellany

### Description

One-paragraph abstract or summary summarizing the form and then content of the manuscript as a whole; for miscellanies, a narrative list of contents should be provided. Describes the salient features of a book’s textual, material and artistic contents, emphasizing the most important qualities that the reader will need to know about the manuscript. Qualitative judgments and subjective adjectives should be used sparingly. Important information to include, when known, are the date of the manuscript, its origin, if it is illuminated, and if it is complete or fragmentary. The note can also include the names of authors, scribes, artists, and named parties mentioned in documents, as well as notable features of decoration and musical notation where applicable and possible. 

## B. Project Taxonomy > Classification > Collection

This property, and only this property, is applied to collections created under *Concepts > Collections*. Those collections may represent collections of items within repositories (eg. the Knox College Moses donation) or to theoretical collections of related items (e.g. Otto Ege leaves and portfolios). Once collections are created within *Concepts*, they can then be linked within individual items in the field **Belongs to collection**.

## C. Project Taxonomy > Classification > Object

### Excluded from PMSS

**Description:** Boolean field, default to “TRUE” as this field is only added to items that fit the chronological scope of the project, but are excluded for other reasons, eg. item condition prevents transport for digitization, or text is recorded in non-Latin alphabet.

### Candidate for MSI

**Description:** Boolean field, default to “TRUE” as this field is only added to items that exhibit features suggesting that it would be an apt candidate for multispectral imaging at a later time, eg. damaged and discolored paint or ink, unusual ink or paint colors, offsets, evidence of erasures, etc.

### Has child items

**Description:** Boolean field, default to “TRUE” as this field is only added to items that have complex hierarchical descriptions within OCHRE, such as host volumes with binding fragments, or fascicular and composite codices. This field is currently used to flag items for review by the project team as they develop a model from crosswalking data from OCHRE into the project repository.

### Physical type

**Description:** Picklist of item types: codex, document, fragment, roll, host volume, or booklet (for a codicological unit within a larger codex). For fragments, an additional classification must be added according to the following picklists of terms adopted from Fragmentarium:

#### Fragment type > In situ
- Pastedown
- Flyleaf
- Cover
- Wrapper
- Guard
- Spine lining
- Insert
- Offset

#### Fragment type > Detached
- Leaf (trimmed)
- Leaf (untrimmed)
- Bifolium (trimmed)
- Bifolium (untrimmed)
- Quire
- Cutting
- Strip

### Content Type

Picklist of general content categories (Service or liturgical book; Devotional book; Bible; Treatise; Document; Narrative, epic, and lyric texts; Other) each with additional classification. See complete Project Taxonomy for classification choices.

## i. Object > Feature > Identification

### Tombstone title

Title representing the manuscript volume as a whole in the format: Author name, Title(s) of work(s) (or book of Bible) [Fragment]; if an author is known or identified, include the author name; if the volume includes one or multiple works, give the title(s), with multiple titles separated by commas. For manuscripts of multiple works, give titles of two best-known texts. For a bible fragment, give the book as title. For a miscellany or collection of smaller works, enter a supplied title such as “Recipe book.” If a fragment, indicate this at the end of the entry with “[Fragment].” For documents, give document genre (quittance, letter, etc.) and name of issuing party or addressee, when possible.

### Descriptive date

Part of a century, a century, or a range of years larger than a century, or single approximate year for a manuscript described as “Circa” with a single year; if the item has parts with disparate creation dates, multiple dates may be described narratively together here (e.g., “12th century and 15th century”). Complete descriptions will include both a **Descriptive date** and an **Origin** in Events. For documents with a specific date, the date should be recorded day-month-year, eg. "20 May 1499."

### Place of Origin

Place where a manuscript was copied or a suggestion, possibly very broad, of where it might have been copied; often in dealer and library description headings; include cardinal specifications (for example, Northern France); may be followed by a question mark for conjectural locations. Multiple locations may be entered for codices containing multiple manuscripts with different origins bound together.

This should be a modern geographical location whenever possible (Flanders being a rare exception). The smallest component of the location should be listed first, followed by larger locations, usually simply City, Country, e.g., “Oxford, England,” but this could be more specific, such as “Monastery of Reichenau, Lake Constance, Germany,” or could include a region either after a city or as a more specific element before a country. If country is not known, then a region with an accepted or commonly used geographical designation may be given. Cardinal specifications (for example, Northern France) may be included. Conjectural locations may be followed by a question mark, but only one question mark should be used in an origin series, at the most specific level:
- Paris, France
- Oxford?, England
- Florence?, Tuscany, Italy
- Lyon or Rouen?, France
- Northwestern France

The final element of an origin will likely be one of the European geographic keywords:
- Austria
- Belgium
- England
- Flanders
- France
- Germany
- Greece
- Italy
- Netherlands
- Poland
- Portugal
- Romania
- Russia
- Spain
- Switzerland
- Wales

Multiple locations may be entered for codices containing multiple manuscripts with different origins bound together.

If a manuscript's location of origin cannot be determined within Europe (as is the case for some Greek manuscripts, for example), enter Undetermined.

### Belongs to Collection

Use this field to identify multiple items related through shared provenance. These might be collections within institutional repositories (eg. the Moses donation at Knox College) or collections that have been dispersed across many repositories (eg. Otto Ege leaves and portfolios). Collections linked in this field must first be entered in *Concepts > Collections*. For the theoretical reconstruction of an individual item dispersed across multiple repositories, use **Associated item** instead.

### Call Number

Format varies by library. Use only current call number or other item ID number provided by holding institution. Former shelfmarks or additional internal identification numbers should be entered as **Alternate ID**(s).

### Digitization ID

Number assigned by project digitization team. Format consists of a three-letter institutional abbreviation, followed by a three-number item identifier, then a three-number sub-item identifier, eg.: smc_004_001.

### Record URL

URL format varies; for records in a partner institution online catalog.

### Alternate ID (must be paired with Alternate ID Type; repeatable, and record must repeat Feature > Identification > Alternate ID structure)

Internal control number supplied by holding institution, such as: accession number, former shelfmark; or other identifier, such as a Gwara handlist number for leaves of books broken by Otto Ege.

### Alternate ID Type (Required for items with alternate IDs)

Accession numbers, former shelfmarks, other holding institution identifiers or former identifiers to be supplied by the holding institution; other types to be supplied by the PIs.

### Title (only for "Host volume" items)

Title of the imprint as given in the imprint itself. Additional information about titles, when possible, go into the **Description**, including short titles and ISTC numbers from the Incunabula Short Title Catalogue (ISTC), or other reference works for early print volumes.

### Author (only for "Host volume" items)

Name of author of host volume.

### Publisher (only for "Host volume" items)

Name of publisher recorded in imprint. Field may be deleted if the publisher is unknown.

### Place of publication (only for "Host volume" items)

Place of publication for an imprint; in this project, imprints appear only as host volumes containing binding fragments. Any correction to erroneous information should be provided in square brackets.

### Date (only for "Host volume" items)

Publication year for a host volume (imprint) containing manuscript material.

## ii. Object > Feature > Analytic description

### Support Material

Material on which the manuscript is written: from the picklist, *parchment, paper*, or *mixed* if both parchment and paper. Any other material, identify by name.

### Foliation/Pagination

How the leaves or pages of the manuscript are numbered (in foliation, each leaf is numbered once; in pagination, both the recto and verso of each leaf are numbered), and where the numbers appear on the leaves, such as *upper right recto* or *lower outer corners*, or *Modern foliation in pencil, upper right recto*.

### Extent (required for all items except cuttings)

Formula showing the numbers of flyleaves and leaves, in the format [modern front flyleaves in roman numerals]+[medieval front flyleaves in arabic numerals] + [textblock leaves in arabic numerals]+[medieval back flyleaves in arabic numerals]+[back flyleaves in roman numerals]: 

ii+113+iii > for a volume wiht only modern endleaves

ii+1+116+1+ii > for a volume with single medieval endleaves and pairs of modern endleaves to either side of the text block

Single detached leaves receive the value “1”; a bifolium, “2”. Do not include spaces. Information about the flyleaf material can be entered into the **Description**. No **Extent** is entered for cuttings. For rolls, enter the number of parchment pieces comprising the roll.

### Collation

Information about the structure of a codex including numbers of gatherings and numbers of leaves per gathering, presented as a formula. Gatherings are enumerated with Arabic numerals following Q for “quire.” After the quire number, parentheses enclose a numeral indicating the number of conjoint leaves originally constituting that quire. Any leaves added or removed from that original structure, including where they were added or whence they were removed, are indicated after a colon.

Example collation: Q1 (8), Q2 (8: +1 after 4), Q3 (8: -3, -7)

In the above example, quire 2 has a single leaf tipped in after the fourth original leaf; quire 3 was originally a quaternion from which the third and seventh leaves were excised or lost.

If the collation cannot be determined, enter “Structure uncertain” or e.g. “binding too tight to collate.”

### Layout

Information about how a page is ruled (including single or double bounding lines) and ruling method (drypoint, lead, ink) and any visible prickings also goes here. A written area that is delineated by four intersecting lines that run from edge to edge is **frame-ruled**. A written area that is delineated by a floating box is **box-ruled**. For a codex or miscellany, the parent item layout property should describe general features of the volume as a whole.

**Examples:**
- Ruled in brown ink for two columns of ten lines
- Two columns of ten lines. Double outer bounding lines. Frame-ruled in red. Ruled in lead
- One column with five lines of text with music

### Number of columns

Record the number of columns. This property may be repeated for codicological units within a codex when these differ among parts of the manuscript.

### Number of lines

Record the number of lines if the entire written area is present. Do not record for trimmed leaves or binding fragments, as the number of extant visible lines will be recorded under **Layout** instead. This property may be repreated for codicological units within a codex when these differ among parts of the manuscript.

### Colophon

Statement at the end of some manuscripts recording the date, place, scribe, and/or reason for production of the manuscript. Potential source of Date and Place of origin information, when present. Transcribe the colophon and provide a leaf citation. Any other information about a colophon should be included in the **Description**.

### Script

Information about the type of lettering used in the manuscript (for example, Caroline minuscule, Gothic). Information about hands (a hand is an individual scribe’s interpretation of a script) and scribes may also be entered in notes fields. Multiple hands may write in the same script. Choose appropriate terms from the following picklists. When unable to determine an appropriate precise classification, use the general categories.

**Pre-Caroline**
- Uncial
- Half-uncial
- -Insular minuscule

**Caroline minuscule**

**Romanesque**

**Beneventan**

**Gothic**
- Anglicana
- Bastarda
- Cursiva
- Praecissa
- Quadrata (application of feet and biting of curves; includes scripts sometimes categorized separately as Quadrata and Semi-Quadrata)
- Rotunda (round Italian textualis, not Brownian rotunda, which is English with rounded-off minims)
- Textualis (everything below semi-quadrata)

**Humanistic**
- Humanistic cursive
- Humanistic minuscule
- Mercantesca

**Documentary** (Document hands that do not fit in other categories above)

### Decoration

Summary of information about formal visual elements of the item, including illuminations, diagrams, decorated initials, colored headings and chapter and paragraph marks; also includes informal visual elements added later to the manuscript, such as drawings, sketches, and manicules. General, rather than page-level list of visual elements. Might include leaf citations for miniatures in an illuminated codex. When identifying an initial in this field, place it between quotation marks. Additional detailed descriptions of decoration should be recorded in the **Description**.

**Examples:**
- Three-line pen-flourished initials, alternating red and blue
- A four-line initial “A” includes penwork that extends down the left margin
- Half-page illuminated miniatures at the opening of the Hours of the Virgin, the Hours of the Cross, and the Office of the Dead
- Two full page miniatures. Extensive decorative borders and one-line illuminated initials throughout. rubrics in red

### Musical notation

For manuscripts containing musical notation, describe at minimum the number of staff lines and their color, and notation style. Notation is classified in the broadest terms: square notation describes any notation with square noteheads on a staff, and “neumatic,” any neumes that do not have square noteheads. For these latter, specify heightened or unheightened when possible. Additional optional details may include the presence of barlines, clef lines, accidentals, and custos. Number of staves per page, or the general arrangement of text and music, is recorded in **Layout**. When possible, chants should be identified by Cantus ID numbers, and those numbers should be listed in the **Cantus ID** field (Feature>Contents).

### Binding

Information about the cover (such as type of leather or fabric), its ornamentation (such as gilt or blind, tooled or stamped), fastenings (such as clasps or ties) and other hardware (bosses, cornerpieces, chain remnants), and damage or repairs to the cover. Preferred terminology comes from the [Ligatus Language of Bindings (LoB) Thesaurus](https://www.ligatus.org.uk/lob). 

### Watermarks

For manuscripts written on paper, descriptions of the watermarks in the manuscript, possibly with citations to reference sources such as Briquet and Piccard.

### Catchwords

Information about the number and location of catchwords. If catchwords are present, record where they are found, and the orientation on the page (vertical or horizontal), e.g.: On versos, bottom right corner. If they are not consistent (for instance, where the pages are cropped and some are missing), indicate that as well.

### Signatures

Information about the numbers or letters used to ensure correct order of gatherings in the binding process, often found on the first recto or last verso of a gathering. If they are using a system in which quires are marked progressively, rather than using catchwords, you can explain that here. Describe location on the page and within the volume as for catchwords.

### *NB: for the measurement fields below, measurements were taken on site visits and, whenever possible, confirmed by a second set of measurements taken by the PI on site during capture.*

### Bound dimensions (in mm)

Maximum height, width, and depth of bound volume in millimeters, in the following format: 290 x 220 x 30

### Page dimensions (in mm)

Maximum height and width of manuscript leaves in millimeters, in the following format: 280 x 210

If originally separate manuscripts of different dimensions have been bound together in a volume, repeat the field for the different page sizes.

For *in situ* binding fragments from the same original item being described together, give page dimensions for each, separated by a comma, eg. 120 x 50 (front flyleaf), 110 x 70 (back flyleaf).

For bifolia, give the dimensions of a single leaf (height and width), as in a codex. 

For cuttings and binding fragments, give the longest height and width dimensions.

For folded documents with a single block of writing (e.g., personal letters), give the dimensions of the fully unfolded sheet when such measurements are possible. If the sheet has been folded folio, with writing disposed into two or more pages, treat the document as a bifolium as above. In either case, clarify the measurement in the **Description**.

### Written area (in mm)

Height and width of the written space in millimeters. If pages are ruled and writing is confined to the ruled space, measure that. Otherwise measure height from the top of minims on the first line to the bottom of minims on the last line. Repeat as necessary if a codex consists of booklets of markedly different layouts. Width may be omitted for unruled verse or where the right edge of writing is ragged. For text disposed in two columns, include a measurement of column width as well, eg. 80 x 60, column width 25mm 

### Line height (required; fragments only)

The height in millimeters of a single line of writing. For an average, measure the height of ten lines, baseline to baseline, and divide by ten. Supply this data point for all fragments, except those with full page music.

### Notes
### Provenance details

Additional information beyond former owner names, including family ownership, former libraries or geographical locations, marks of provenance such as bookplates, and sale information. In this field the whole known history of the manuscript should be given. Provenance is concerned with the individuals or institutions that may have owned or handled a book up to and including the present time, and should be written out chronologically. Record provenance agents separately in *Persons & organizations*, in authorized form and linked to relevant authority files.

### Bibliography

Relevant citations to other bibliographic resources, such as essays or articles about a manuscript. Citations are supplied in Chicago Style, imported from Zotero.

## iii. Object > Feature > Agents

For all agents identified within or associated with project items, agent records are created in *Persons & organizations*. For each agent record, link the VIAF ID associated with that name using the OCHRE thesaurus tools. If a VIAF ID is lacking, use LC NAF or ULAN authorities when relevant and possible, and create thesaurus links accordingly. If there is not an Authority Name, 
- Give the name of the agent in Latin letters in authority form (Lastname, Firstname) for modern names and medieval names with surnames. For medieval names with patronyms or toponyms, give names as “Firstname Patronym/Toponym” without commas. 
- Modernize given names, but keep particles and toponyms as recorded, modernizing toponyms only for persisting place names
- Add an alias to the agent record with the name as it is recorded in each item where it figures

Agents in the following categories can be linked from *Persons & organizations* within item records: Author, translator, artist, chancellor or secretary, notary, scribe, signatory, addressee. For a miscellany, Feature>Agents>Author should be repeated to include all authors whose works are represented in the volume.

Agents related to item provenance (donor, conservator or restorer, bookbinder, former owner, fragmentator, librarian, seller, describer) can be linked from *Persons & organizations* within Events.

## iv. Object > Feature > Contents

### Language

Language or languages in which the manuscript is written, available as a picklist within OCHRE. If there are notes about the use of languages (e.g., “Latin with Greek glosses”) include all the language names in repeated **Language** fields, and add the additional information in the **description**. 

The following languages are currently in the OCHRE picklist. The corresponding ISO 639-2 Codes follow each value in square brackets. These codes are linked as aliases in our picklist, and viewable on export.
- Latin [lat]
- Greek [grc]
- Anglo-Norman [xno]
- Arabic [ara]
- Armenian [arm]
- Catalan [cat]
- Dutch [dum]
- English after approx 1500 [eng]
- English, Middle, to approx 1500 [enm]
- French, Middle, approx. 1400-1600 [frm]
- French, Old, before approx. 1400 [fro]
- German, after approx. 1500 [ger]
- German, Middle High, approx. 1050-1500 [gmh]
- German, Old High, approx. 750-1050 [goh]
- Hebrew [heb]
- Italian [ita]
- Low German [nds]
- Spanish: Castilian [spa]

### Scribal title

Title as given by scribe or contemporary hand at the beginning of a text item. Do not record rubrics appearing in liturgical books.

### Protocol

Formulaic language in papal documents ending with “salutem et apostolicam benedictionem,” after which is found the incipit. For other kinds of documents, include similar opening formulae, even when these are less standardized in contracts and other notarial records.

### Incipit and explicit

Incipit and explicit should be recorded for the following types of material:
- Works imperfect at beginning or end. Incipit is the initial words of the work as transmitted, following double forward slashes (//).
- All fragments. Incipit is the initial words of the fragment. When possible we supply within square brackets [ ] the missing portions of broken Latin words.
- Unidentified works, works without a standard modern edition, and eccentric copies of known works. Incipit is the initial words of the work, following the title or rubric (if any)
- Papal letters. Incipit is the first words after the initial protocol. Explicit is not recorded.
- Other kinds of documents. Record incipit. If the document is complete, explicit is unnecessary.

Record a single complete clause of prose or two lines of verse when possible. Do not provide incipit or explicit for Bibles transmitted intact.

Transcription follows the the following policies:
- Abbreviations are silently expanded.
- We preserve the distinction between **u** and **v** and between **i** and **j** in the sources. For example, long **i** is transcribed as **j** where the scribe has used this form in final position, e.g., in roman numeral *xiij*.
- Words inserted by the scribe are recorded within double slashes, e.g. \\habet//.
- Letters supplied where the writing is illegible or uncertain due to damage are enclosed in < >.
- Use ( ) around words or letters deleted by the scribe.
- Punctuation is represented by modern equivalents, determined by context.

### Modern title

For works with a standard modern edition, give the standard title of the work. Psalms are identified according to the Greek/Vulgate numbering.

### Supplied title

For works with no standard modern edition, and lacking a scribal title in the copy, give a brief indication of the nature of the work if possible.

### Cantus IDs

For notated manuscripts, when possible, identified chants are listed in order of appearance by Cantus ID numbers, as established by the [Cantus Index](https://cantusindex.org/)

### Folio range

For each work within a manuscript, record the range of leaves that transmit the text, eg. 1r-4v or [1]r-v. Only provide a unit abbreviation if the item is paginated, eg. pp. 3-7. Do not record for documents.

### Image range and end

For each content item, list the beginning and end images of that item. For host volumes of *in situ* fragments, the range should cover all item images; the *in situ* fragment images will be repeated separately in the fragment subitem(s).

### Author

This author field is only for codicological units containing works by multiple authors, and it is used in order to associated specific works with specific authors under repeated Feature>Contents sections. All authors should still be identified under Feature>Agents.

## v. Object > Feature > Keywords

### Keywords (repeatable)

Keywords are organized into six groups: Book Type, Century, Culture, Descriptive term, Geography, and Subject. Each group appears as a picklist in OCHRE, and each group can be repeated as many times as necessary. Some keywords may repeat metadata supplied in other forms in the fields described above. All relevant keywords should still be added to each record, to help users to search the digital item repository. A list of keywords is given in the appendix.

## vi. Object > Associated item

### Associated item (repeatable)

This field allows for the identification of related items across collections, for example, leaves from the same original manuscript, now dispersed. Repeatable as needed.

## C. Project taxonomy > Event

### Origin

Flexible date recording that may comprise a single date or date range, the latter represented using start and end years. For **Descriptive dates**, regularize the start and end years according to the table below:

| **Descriptive date**            | **Start year** | **End year** |
| :------------------------------ | :--------------| :----------- |
| 14th century                    | 1300           | 1399         |
| Early 14th century              | 1300           | 1315         |
| First quarter 14th century      | 1300           | 1325         |
| Fourth quarter 14th century     | 1375           | 1399         |
| Mid-14th century                | 1340           | 1360         |
| 14th century after 1320         | 1320           | 1399         |
| Late 14th century               | 1385           | 1399         |
| Late 14th or early 15th century | 1385           | 1415         |
| Mid-14th to early 15th century  | 1340           | 1415         |
| 14th or 15th century            | 1300           | 1499         |
| Circa 1325                      | 1310           | 1340         |

### Additional Events

Additional events can be added to any item in order to record conservation interventions and provenance details. Record private and institutional owners and any provenance agents separately in *Persons & organizations*, in authorized form and linked to relevant authority files. Link relevant agents to events whenever possible. For a complete list of **Events**, see the Project Taxonomy in the appendix.

Events also record internal progress of item description, indicating when initial, second, and third rounds of description and review have been begun and completed, and by whom. 

## III. Appendices

### A. Project Taxonomy

Classification
- Collection
- Object
  - Excluded from PMSS
  - Candidate for MSI
  - Has child items
  - Physical type
      - Codex
      - Document
      - Fragment
        - Fragment type
          - In situ
            - Classification:
              - Pastedown
              - Flyleaf
              - Cover
              - Wrapper
              - Guard
              - Spine Lining
              - Insert
              - Stacked boards
              - Offset
          - Detached
            - Classification:
              - Leaf (trimmed)
              - Leaf (untrimmed)
              - Bifolium (trimmed)
              - Bifolium (untrimmed)
              - Quire
              - Cutting
              - Strip
      - Roll
      - Host volume
      - Booklet
  - Content Type
    - Service or liturgical book
      - Classification:
        - Antiphonal
        - Breviary
        - Collectar
        - Gospel lectionary
        - Gradual
        - Kyriale
        - Missal
        - Processional
        - Psalter
    - Devotional Book
      - Classification:
        - Book of Hours
        - Psalter
        - Prayer book
    - Bible
    - Sermons
    - Treatise
      - Classification:
        - Legal
        - Theological
        - Scientific
    - Document
      - Classification
        - Land deed
        - Letter
        - Papal bull
        - Will or testament
    - Narative, epic, and lyric texts
    - Other
  - Feature
    - Identification:
      - Tombstone title
      - Descriptive date
      - Place of origin
      - Belongs to collection
      - Call number
      - Digitization ID
      - Alternate ID
      - Alternate ID type
      - Holding Institution
      - Record URL
      - Title
      - Author
      - Publisher
      - Place of publication
      - Date
    - Analytic description
      - Support material:
        - Parchment
        - Paper (material)
        - Mixed
      - Foliation-pagination
      - Extent
      - Collation
      - Layout
      - Number of columns
      - Number of lines
      - Script:
        - Pre-caroline
          - Script type:
            - Uncial
            - Half-uncial
            - Insular minuscule
        - Caroline minuscule
        - Romanesque
        - Beneventan
        - Gothic
          - Script type:
            - Anglicana
            - Bastarda
            - Cursiva
            - Praecissa
            - Quadrata
            - Rotunda
            - Textualis
        - Humanistic
          - Script type:
            - Humanistic cursive
            - Humanistic minuscule
            - Mercantesca
        - Documentary
        - Early Modern Cursive
      - Decoration
      - Musical notation
      - Binding
      - Watermarks
      - Catchwords
      - Signatures
      - Bound dimensions (in mm)
      - Page dimensions (in mm)
      - Written area (in mm)
      - Line height (in mm)
    - Agents
      - Author
      - Translator
      - Artist
      - Scribe
      - Donor
      - Conservator or restorer
      - Bookbinder
      - Former owner
      - Fragmentator
      - Librarian
      - Seller
      - Describer
      - Addressee
      - Chancellor or secretary
      - Signatory
      - Notary
    - Contents
      - Language:
        - Dutch, Middle, ca. 1050-1350 [dum]
        - English after approx. 1500 [eng]
        - English, Middle, to approx. 1500 [enm]
        - English, Old, ca. 450-1100 [ang]
        - Flemish
        - French, after approx. 1600 [fre]
        - French, Middle, approx. 1400-1600 [frm]
        - French, Old, before approx. 1400 [fro]
        - Gaelic [gla]
        - German, after approx. 1500 [ger]
        - German, Middle High, approx. 1050-1500 [gmh]
        - German, Old High, approc. 750-1050 [goh]
        - Italian [ita]
        - Latin [lat]
        - Portuguese [por]
        - Spanish: Castilian [spa]
      - Scribal title
      - Modern title
      - Protocol
      - Incipit
      - Explicit
      - Colophon
      - Cantus IDs
      - Folio range
      - Image range start
      - Image range end
      - Author
      - Scribe
      - Translator
    - Keywords [see table below for all keywords in the following categories]
      - Book type
      - Century
      - Culture
      - Descriptive term
      - Geography
      - Subject
  - Associated Item
Event
- Acquired
- Conserved
- Digitized
- Finalized
- Gifted
- Listed for sale
- Origin
- Owned by
- Donated by
- Rebound
- Restored
- Sold
- Initial pass: started
- Initial pass: completed
- Second pass: started
- Second pass: completed
- Third pass: started
- Third pass: completed
- Reopened for Discussion

### B. Keywords

| **Book type**           | **Century**  | **Culture**     |
| :---------------------- | :----------- | :-------------- |
| Accounts                | 9th century  | Arabic          |
| Antiphonal              | 10th century | Carolingian     |
| Armorial                | 11th century | Christian       |
| Bible                   | 12th century | Flemish         |
| Biography               | 13th century | Greek antiquity |
| Book of Hours           | 14th century | Humanistic      |
| Breviary                | 15th century | Islamic         |
| Chronicle               | 16th century | Jewish          |
| Collectar               | 17th century | Jesuit          |
| Collection of letters   | 18th century | Monastic        |
| Collection of sermons   | 19th century | Ottonian        |
| Commentary              | 20th century | Papal           |
| Dictionary              |              | Roman antiquity |
| Document                |              |                 |
| Dogale                  |              |                 |
| Friendship Book         |              |                 |
| Genealogy               |              |                 |
| Glossary                |              |                 |
| Gospel lectionary       |              |                 |
| Gospels                 |              |                 |
| Gradual                 |              |                 |
| Haggadah                |              |                 |
| Halakhah                |              |                 |
| Homiliary               |              |                 |
| Horologion              |              |                 |
| Hymnal                  |              |                 |
| Lectionary              |              |                 |
| Letter                  |              |                 |
| Mass book               |              |                 |
| Miscellany              |              |                 |
| Missal                  |              |                 |
| Passional               |              |                 |
| Pontifical              |              |                 |
| Portolan chart          |              |                 |
| Prayer book             |              |                 |
| Private devotional text |              |                 |
| Processional            |              |                 |
| Protective scroll       |              |                 |
| Psalter                 |              |                 |
| Psalter-Hours           |              |                 |
| Qur'an / Koran          |              |                 |
| Recipe book             |              |                 |
| Saint's life            |              |                 |
| Scribal manual          |              |                 |
| Scroll                  |              |                 |
| Song book               |              |                 |
| Sequentiary             |              |                 |
| Torah                   |              |                 |
| Treatise                |              |                 |

| **Descriptive term**   | **Geography**  | **Subject**       |
| :--------------------- | :--------------| :---------------- |
| Accordion book         | Austria        | Alchemy           |
| Album                  | Belgium        | Allegory          |
| Annotated              | Czech Republic | Astrology         |
| Binding                | England        | Astronomy         |
| Binding fragment       | Flanders       | Biblical          |
| Border                 | France         | Cartography       |
| Cadelle                | Germany        | Church Fathers    |
| Chart                  | Greece         | Cosmology         |
| Charter                | Italy          | Devotion          |
| Colophon               | Mexico         | Financial records |
| Damage                 | Netherlands    | Fortune-telling   |
| Decorated initial      | Poland         | Friendship        |
| Diagrams               | Portugal       | Games             |
| Drawing                | Romania        | Geography         |
| Forgery                | Spain          | Geomancy          |
| Fragment               | Switzerland    | Grammar           |
| Gloss                  | Wales          | History           |
| Grisaille              |                | Legal             |
| Grotesques             |                | Literature-poetry |
| Headpiece              |                | Literature-prose  |
| Heraldry               |                | Liturgy           |
| Historiated initial    |                | Logic             |
| Illumination           |                | Magic             |
| Illustration           |                | Maritime          |
| Inhabited initial      |                | Mathematics       |
| Manicules              |                | Mineralogy        |
| Marginalia             |                | Philosophy        |
| Medallion              |                | Responsa          |
| Micrography            |                | Science           |
| Miniature              |                | Science-medicine  |
| Missing leaves         |                | Scripture         |
| Movable device         |                | Theology          |
| Musical notation       |                |                   |
| Notable binding        |                |                   |
| Original binding       |                |                   |
| Ornament               |                |                   |
| Painting               |                |                   |
| Palimpsest             |                |                   |
| Paper                  |                |                   |
| Pen-flourished initial |                |                   |
| Penwork initial        |                |                   |
| Puzzle initial         |                |                   |
| Rinceau                |                |                   |
| Scrapbook              |                |                   |
| Scroll                 |                |                   |
| Scroll-work initial    |                |                   |
| Seals                  |                |                   |
| Tables                 |                |                   |
| Watermark              |                |                   |
| White-vine lettering   |                |                   |
| Woodcuts               |                |                   |

### C. Image Names               
    
Anything to be photographed needs a name-value. Values must not repeat within a single manuscript. The value will usually be a page number (e.g., 1) or a folio number (e.g., 2r). See **Foliation/Pagination.**

For covers and flyleaves, identify the location or number as relevant (e.g., Inside Front Cover, Flyleaf 1 recto). If pages are labeled using something other than Arabic numerals (e.g., Roman numerals or letters) use whatever is on the page. Front and back flyleaves should be noted as such.

The subsections below supply additional instructions for data entry in this column.

**External Structure**
- Spine
- Fore edge
- Top edge
- Bottom edge

**Covers and Flyleaves**

Front matter:
- Front cover
- Inside front cover
- [Flyleaf 1 recto]
- [Flyleaf 1 verso]

Back matter:
- [Flyleaf 1 recto]
- [Flyleaf 1 verso]
- Inside back cover
- Back cover

When flyleaves are numbered, identify the leaf as a flyleaf and add the folio number after, separated by a colon:
- [Flyleaf 1 recto: fol.239]

**Text block (constituent leaves not including the flyleaves)**

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

If pages are labeled using something other than Arabic numerals (e.g., Roman numerals or letters) use whatever is on the page. If leaves are foliated in Arabic numerals, use [these template values.](https://github.com/midwest-manuscripts/peripheralmss/blob/master/documentation/folio-values.csv)

Leaves attached but not foliated/paginated:
- [1r]
- [1v]
- [2r]
- [2v]

Leaves foliated/paginated but detached:
- 1r (unattached)
- 1v (unattached)

Foliation skips a folio (i.e., 7, unnumbered, 8, not 7, unnumbered, 9):
- Unnumbered recto
- Unnumbered verso

(When more than one in a row, add 'i' etc. after 'Unnumbered')

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

### D. OCHRE Predefinitions

Within OCHRE (Online Cultural and Historical Research Environment), each physical item type has its own Predefinition consisting of the fields that are generally expected to apply to that item type. Additional potentially relevant fields are included in **bold**, but must be manually added to pertinent item records. A list of physical item types and corresponding Predefinition fields is supplied below. The entry <unassigned> represents a picklist within OCHRE among which the cataloger must make a selection for that item type in that field.

All predefinitions additionally include notes for item provenance and for discussion internal to the project team.

### Codex

Classification > Object
- **Excluded from PMSS**
- Physical Type: Codex
- Content Type: <unassigned>
  - [subtypes added as appropriate]
- Feature > Identification
  - Tombstone title
  - Descriptive date
  - Place of origin
  - **Belongs to collection**
  - Call number
  - Digitization ID
  - Alternate ID [repeatable]
  - Alternate ID type [repeatable]
- Feature > Analytic description
  - Support material
  - Foliation-Pagination
  - Extent
  - Collation
  - Layout
  - Number of columns
  - Number of lines
  - Colophon
  - Script: <unassigned> [subtype added where appropriate]
  - Decoration
  - Musical notation
  - Binding
  - **Watermarks**
  - Catchwords
  - Signatures
  - Bound dimensions (in mm)
  - Page dimensions (in mm)
  - Written area (in mm)
- Feature > Agents
  - [subtypes added as appropriate]
- Feature > Contents
  - Language: <unassigned>
  - Scribal title
  - Incipit
  - Explicit
  - Cantus IDs
  - Modern title
  - Folio range
  - Image range start
  - Image range end
- Feature > Keywords
  - [keywords in various categories added as appropriate]
- Associated Item [repeatable]

### Document

Classification: Object
- **Excluded from PMSS**
- Physical Type: Document
- Content Type: Document
  - Classification: <unassigned>
- Feature > Identification
  - Tombstone title
  - Descriptive date
  - Place of origin
  - **Belongs to collection**
  - Call number
  - Digitization ID
  - Alternate ID [repeatable]
  - Alternate ID type [repeatable]
- Feature > Analytic description
  - Support material
  - Extent
  - Layout
  - Script: <unassigned> [subtype added where appropriate]
  - Decoration
  - Page dimensions (in mm)
  - Written area (in mm)
- Feature > Agents
  - [subtypes added as appropriate]
- Feature > Contents
  - Language: <unassigned>
  - Protocol
  - Incipit
  - Explicit
  - Folio range
  - Image range start
  - Image range end
- Feature > Keywords
  - [keywords in various categories added as appropriate]
- Associated Item [repeatable]

### Fragment (detached) - may include Host Volume record (see below)
Classification: Object
- **Excluded from PMSS**
- Physical Type: Fragment
  - Fragment type: Detached
    - Classification: <unassigned>
  - Content Type: <unassigned>
  - Feature > Identification
    - Tombstone title
    - Descriptive date
    - Place of origin
    - **Belongs to collection**
    - Call number
    - Digitization ID
    - Alternate ID [repeatable]
    - Alternate ID type [repeatable]
  - Feature > Analytic description
    - Support material
    - Foliation-Pagination
    - Extent
    - Layout
    - Number of columns
    - Number of lines
    - Script: <unassigned> [subtype added where appropriate]
    - Decoration
    - Musical notation
    - **Catchwords**
    - **Signatures**
    - Page dimensions (in mm)
    - Written area (in mm)
    - Line height (in mm)
  - Feature > Agents
    - [subtypes added as appropriate]
  - Feature > Contents
    - Language: <unassigned>
    - **Scribal title**
    - Incipit
    - Explicit
    - Cantus IDs
    - Modern title
    - Folio range
    - Image range start
    - Image range end
  - Feature > Keywords
    - [keywords in various categories added as appropriate]
  - Associated Item [repeatable]
 
  ### Fragment (in situ) - must include Host Volume record (see below)

  Classification: Object
  - Physical Type: Fragment
    - Fragment type: In situ
      - Classification: <unassigned>
  - Content Type: <unassigned>
  - Feature > Identification
    - Tombstone title
    - Descriptive date
    - Place of origin
    - Call number
    - Digitization ID
    - Alternate ID [repeatable]
    - Alternate ID type [repeatable]
  - Feature > Analytic description
    - Support material
    - Foliation-Pagination
    - Layout
    - Script: <unassigned> [subtype added where appropriate]
    - Decoration
    - Musical notation
    - **Catchwords**
    - **Signatures**
    - Page dimensions (in mm)
    - Written area (in mm)
    - Line height (in mm)
  - Feature > Agents
    - [subtypes added as appropriate]
  - Feature > Contents
    - Language: <unassigned>
    - **Scribal title**
    - Incipit
    - Explicit
    - Cantus IDs
    - Modern title
    - Image range start
    - Image range end
  - Feature > Keywords
    - [keywords in various categries added as appropriate]
  - Associated Item [repeatable]
 
### Host Volume (for imprints; for manuscript host volumes, use Codex predefinition)

Classification: Object
- Physical Type: Host volume
- Feature > Identification
  - Tombstone title
  - Title
  - Author
  - Publisher
  - Place of publication
  - Date
  - Call number
  - Digitization ID
  - Alternate ID [repeatable]
  - Alternate ID type [repeatable]
- Feature > Agents
  - [subtypes added as appropriate]
- Feature > Contents
  - Image range start
  - Image range end
- Feature > Keywords
  - [keywords in various categories added as appropriate]
- Associated Item [repeatable]

