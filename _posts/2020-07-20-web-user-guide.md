---
layout: post
author: Jeff Naemura
tags: [
    "user guide", "procedures", "documentation", "manual", "IFU", "DFU", "static site generator", "hugo", "photoshop", "illustrator", "atom"
]
---

[Web-based User Guide Sample](https://naem-j.github.io/web-doc-sample/)

## Summary

This sample of a web document was converted from a printed user guide I authored. The original document was intended to be provided as a printed book with hardware and satisfy EU and IEC instructions for use and FDA directions for use definitions.

The document is provided in its original PDF form on the company website for "labeling," but it has since been updated. The web sample coincides with the last PDF revision I authored.

## Responsibilities

The product was acquired by my company, but documentation for it was written and organized by a quality engineer that had since left the company. One of my first responsibilities was to coordinate with an R&D engineer for the acquired company and completely rewrite the document.

Ultimately, I was responsible for writing most of the content (with very little content reused from the original document), reorganizing the topics to better match FDA guidelines, and assimilating the document to the company branding. I also drew vector-based illustrations of hardware in isometric and orthographic projections based on CAD drawings.

The original PDF was reviewed informally with SMEs and other writers and formally through PTC Windchill (CCMS). Reviews were performed primarily with PDF comments and changes were justified in the CMS with company-defined "redlines."

For the web-based version, I parsed the content from a binary file (Adobe InDesign) into modular topics (markdown files). I utilized a free Hugo theme to create the layout and published it to GitHub. Content was created with markdown, HTML, and CSS. Styles were predominately provided by the theme creator, but slightly manipulated using TOML and CSS.

## Target Audience

* Ophthalmic surgeons and their medical staff
* IT departments
* Responsible organizations (owners of the equipment)

## Tools

* Atom
* Adobe Illustrator
* Adobe Photoshop
* Git
* GitHub
* Hugo

NOTE: For the original PDF, I also used Adobe InDesign, Microsoft SharePoint, and PTC Windchill.
