Wikidata reconciliation interface for OpenRefine [![Build Status](https://travis-ci.org/wetneb/openrefine-wikidata.svg?branch=master)](https://travis-ci.org/wetneb/openrefine-wikidata)
================================================

An instance of this endpoint can be found at:
https://tools.wmflabs.org/openrefine-wikidata/en/api

This is a new reconciliation interface, with the following features:
* Matching columns with Wikidata properties, to improve the fuzzy
  matching score ;
* Optimized for speed with redis caching at various places, API calls
  kept to the minimum ;
* Autocomplete for properties and items ;
* Support for SPARQL-like property paths such as "P17/P297" (which fetches the ISO code of the country of an item) ;
* Language selection (use /$lng/api as endpoint, where $lng is your
  language code).

TODO:
* Better scoring.

MIT license.

