# Linked Art Modelling

[![DOI](https://zenodo.org/badge/563828272.svg)](https://zenodo.org/badge/latestdoi/563828272)

[Linked Art](https://linked.art) is an RDF application profile of CIDOC-CRM that uses JSON-LD and the
Getty Vocabularies (such as AAT - the Arts and Architecture Thesaurus) to describe object-based cultural heritage (see [Newbury 2018](https://cidoc.mini.icom.museum/wp-content/uploads/sites/6/2021/03/CIDOC2018_paper_153.pdf) and [Delmas-Glass & Sanderson 2020](https://doi.org/10.1017/alj.2019.32)).

This repository contains some Linked Art models or templates for my own purposes, especially those that I would like to publish in the context of my PhD Thesis (_Linked Open Usable Data in the Humanities: Perspectives on Semantics and Interoperability_), most probably at `https://data.julsraemy.ch/` (TBD).

The following top-level [Linked Art API entities](https://linked.art/api/1.0/endpoint/) - with _examples_ - have been serialised in JSON-LD (and some models are also represented as graphs in SVG):

- [Textual Works](/text) for encoding the chapters, sections and subsections of the thesis.
  - _PhD Thesis_
  - _Introduction_ (example of a chapter which is part of the PhD Thesis)
- [Digital Objects](/digital) for encoding the notebook entries available on my [PhD Website](https://phd.julsraemy.ch)
  - _Actor-Network Theory_
- [Concepts](/concept) for encoding terms that are not available via the Getty Vocabularies
  - _Linked Open Usable Data_
- [Person](/person) for encoding myself and others individuals involved in the PhD thesis
  - _Julien Antoine Raemy_
- [Group](/group) for encoding the organizations and 
  - _University of Basel_