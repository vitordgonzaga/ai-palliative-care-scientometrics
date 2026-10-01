# Artificial intelligence in palliative care: materials of a scientometric mapping (2018-2025)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23046536.svg)](https://doi.org/10.5281/zenodo.23046536)

Supplementary materials of the scientometric mapping of research on artificial
intelligence (AI) in palliative care indexed in the Web of Science Core Collection.
This repository holds the search documentation, the list of included records, the
analysis outputs and the figures of the article, so that the selection and the
analyses can be inspected and repeated.

Version history: see CHANGELOG.md.

## How to cite

> [author names, title, journal, year, DOI - to be completed on acceptance]

## Contents

| Folder | Contents |
| --- | --- |
| `01_search/` | Database, access route, search date, full search string, filters and the number of records at each stage of selection |
| `02_selection/` | The 166 included records with journal, year, DOI, Web of Science document type, citation count and classification; the 30 records that are not original empirical research or in which AI or palliative care is only tangential; and the full document inventory as a spreadsheet |
| `03_bibliometrix_outputs/` | Tables and plots exported from Bibliometrix 4.3.0 / Biblioshiny (main information, annual production, country production, sources, authors, affiliations, most globally and locally cited documents, thematic map, trend topics, metadata completeness) |
| `04_figures/` | Figures of the article and of the supplementary material, as published |
| `05_vosviewer/` | Map and network files of the three VOSviewer networks (see the file in that folder) |

## Methods, in short

- Database: Web of Science Core Collection, searched on 6 April 2025 through an
  institutional portal, with no edition-specific limiter.
- Filters: publication years 2016-2025, document type "Article", language English.
- Selection: 391 records retrieved, 109 removed by the filters, 282 screened on
  title, author keywords and abstract by two authors together with inclusion decided
  by consensus, 116 excluded, 166 included (published 2018-2025). Full texts were not
  consulted at the screening stage. Mendeley Desktop 1.19.5 identified no duplicates.
- The document type was used as an operational criterion and not as a synonym of
  original empirical research. A post hoc reading of titles and abstracts identified
  25 records that are not original empirical research and five in which AI or
  palliative care is only a tangential element. All 30 were kept, to preserve the
  corpus as retrieved and indexed; they are listed in `02_selection/`.
- Software: Microsoft Excel 2021, Bibliometrix 4.3.0 (Biblioshiny), VOSviewer 1.6.20.
- Analysis parameters were the defaults of each program; the values are stated in
  `05_vosviewer/` and in the Methods section of the article.
- Local citations were computed by matching DOIs in the cited references of the corpus.

## What is not included

The raw Web of Science export is not redistributed here, because the records are
licensed content of the database provider. The search string, the search date and the
DOIs of every included record are given, which is enough to retrieve the same set, and
the export can be requested from the corresponding author.

## Licence

Materials produced by the authors (record lists, figures, derived tables) are released
under CC BY 4.0. Files exported from third-party software keep the terms of their
source data.

## Note for peer review

If the article is submitted to a journal with double-blind review, share an anonymous
copy of this repository during review, or state in the article that the link will be
made available on acceptance: the repository owner and commit history identify the authors.
