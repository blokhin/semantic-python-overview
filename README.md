# Semantic Python Overview

This repository aims to collect and curate a list of projects which are related both to python and semantic technologies (RDF, OWL, Reasoning, ...). It is inspired by collections like [awesome lists](https://github.com/sindresorhus/awesome#readme). The list might be incomplete and biased, due to the limited knowledge of its author(s).  Improvements are very welcome. Feel free to file an issue or a pull request. Every section is alphabetically sorted.


## Established Projects
- [FunOwl](https://github.com/hsolbrig/funowl) – functional OWL syntax for Python
  - features:
    - provide a pythonic API that follows the OWL functional model for constructing OWL
- [OntoPilot](https://github.com/stuckyb/ontopilot) – software for ontology development and deployment
  - docs: https://github.com/stuckyb/ontopilot/wiki
  - features:
    - support end users in ontology development, documentation and maintainance
    - convert spreadsheet data (one entity per row) to owl files
    - call a reasoner before triple-store insertion
- [ontospy](https://github.com/lambdamusic/Ontospy) – Python library and command-line interface for inspecting and visualizing RDF models
  - docs: http://lambdamusic.github.io/Ontospy/
  - features:
    - extract and print out any ontology-related information
    - convert different OWL syntax variants
    - generate html documentation for an ontology
- [owlready2](https://bitbucket.org/jibalamy/owlready2/src/master/README.rst) – ontology oriented programming in Python
  - docs: https://owlready2.readthedocs.io/en/latest/index.html
  - features:
    - parse owl files (RDF/XML or OWL/XML)
    - parse SWRL rules
    - call reasoner (via java)
- [rdflib](https://github.com/RDFLib/rdflib) – Python package for working with RDF
  - docs: https://rdflib.readthedocs.io/
  - graphical package overview: https://rdflib.dev/
  - features:
    - parsers and serializers for RDF/XML, NTriples, Turtle and more
    - a graph interface which can be backed by any one of a number of store implementations
    - store implementations for in-memory storage and persistent storage
    - a SPARQL 1.1 implementation – supporting SPARQL 1.1 Queries and Update statements

## Further Projects / Links
- [github-semantic-web-python](https://github.com/topics/semantic-web?l=python) – github project search with `topic=semantic-web` and `language=python`

- [semantic](https://github.com/crm416/semantic) – Python library for extracting semantic information from text, such as dates and numbers
- [Solving Einstein Puzzle](https://github.com/cknoll/demo-material/blob/master/expertise_system/einstein-zebra-puzzle-owlready-solution1.ipynb) – jupyter notebook demonstrating how to use owlready2 to solve a logic puzzle
- [W3C-Link-List1](https://www.w3.org/2001/sw/wiki/SemanticWebTools#Python_Developers) – link list "SemanticWebTools", section "Python_Developers" (wiki page)
  - might be outdated
- [W3C-Link-List2](https://www.w3.org/2001/sw/wiki/Python) – list of tools usable from, or with, Python (wiki page)
- [yamlpyowl](https://github.com/cknoll/yamlpyowl) – read an yaml-specified ontology into python by means of owlready2 (experimental)