
0.7.0 (unreleased)
==================

* cap headers/sections to six levels for improved visualization
* fixed rest publishing for python 3.x (< 3.6)
* improve markup for:
  * body element lists
  * citations
  * definitions
  * footnotes
  * inline literals
  * literal block (code)
  * rubric
  * seealso
  * table
  * versionmodified
* re-work generated document references/targets (reference to section names)
* sanitize output to prevent Confluence errors for certain characters
* support indentations markup

0.6.0 (2017-04-23)
==================

* cleanup module's structure, versions and other minor files
* drop 'confluence' pypi package (embedded xml-rpc support added)
* improve hyperlink and cross-referencing arbitrary locations/documents support
* improve proxy support
* re-support python 3.x series
* support anonymous publishing
* support rest api

0.5.0 (2017-03-31)
==================

* header/footer support
* purging support
* use macros for admonitions
* (note) known issues with python 3.3, 3.4, 3.5 or 3.6 (see
   tonybaloney/sphinxcontrib-confluencebuilder#10)

0.4.0 (2017-02-21)
==================

* move from 'confluence' pypi package to 'confluence' pypi package (required for
   publishing). see: https://github.com/pycontribs/confluence

0.3.0 (2017-01-22)
==================

* adding travis ci, tox and initial unit testing
* module now depends on `future`
* providing initial support for python 3

0.2.0 (2016-07-13)
==================

* moved configuration to the sphinx config

0.1.1 (2016-07-12)
==================

* added table support
* fixed internal links

0.1.0 (2016-07-12)
==================

* added lists, bullets, formatted text
* added headings and titles

