---
sectionid: headerFileDescription
title: "File Description"
version: "v3"
---



The structure of the bibliographic description of a machine-readable or digital musical
text
resembles that of a book, an article, or other kinds of textual objects. The file
description
element of the MEI header has therefore been closely modelled on existing standards
in library
cataloging; it should thus provide enough information to allow users to give standard
bibliographic references to the electronic text, and to allow catalogers to catalog
it.
Bibliographic citations occurring elsewhere in the header, and in the text itself,
are derived
from the same model.

The bibliographic description of an electronic musical text should be supplied by
the
mandatory [fileDesc](/{{ page.version }}/elements/fileDesc.html){:.link_odd_elementSpec} element:



{% include specDesc.html version=page.version key="fileDesc" atts="" %}



The [fileDesc](/{{ page.version }}/elements/fileDesc.html){:.link_odd_elementSpec} element contains two mandatory and six optional elements,
each of which is described in more detail below. These elements are listed below in
the order
in which they must occur within the [fileDesc](/{{ page.version }}/elements/fileDesc.html){:.link_odd_elementSpec} element.



{% include specDesc.html version=page.version key="titleStmt" atts="" %}
{% include specDesc.html version=page.version key="editionStmt" atts="" %}
{% include specDesc.html version=page.version key="extent" atts="" %}
{% include specDesc.html version=page.version key="pubStmt" atts="" %}
{% include specDesc.html version=page.version key="seriesStmt" atts="" %}
{% include specDesc.html version=page.version key="notesStmt" atts="" %}
{% include specDesc.html version=page.version key="sourceDesc" atts="" %}



A complete file description will resemble the following example:

{% include plainExample.html example="./v3/examples/header/header-sample019.xml" valid="false" %}







