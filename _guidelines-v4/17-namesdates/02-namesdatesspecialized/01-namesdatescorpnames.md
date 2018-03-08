---
sectionid: namesdatesCorpNames
title: "Corporate Names"
version: "v3"
---



{% include desc elem="corpname" %}




Corporate names are non-personal names which refer to structured bodies of one or
more
persons that act as a single entity. Typical examples include associations, businesses,
projects or institutions (e.g.,. 'the Royal College of Music' or 'the BBC'), but also
racial
or ethnic groupings or political factions where these are regarded as forming a single
agency. Organization names typically include some type of indicator or pattern or
words that
help identify them as non-personal names.

The {% include link elem="corpname" %} element is frequently used within the {% include link id="header" %} of an MEI document. It is typically found in the {% include link elem="respstmt" %} element:

{% include plainExample.html example="examples/namesdates/namesdates-sample279.xml" valid="true" version=page.version %}
It may also be used wherever it is necessary to mark a corporate name, for example
when a
corporation is responsible for a certain event in the history of a musical work:

{% include plainExample.html example="examples/namesdates/namesdates-sample280.xml" valid="true" version=page.version %}
When it is necessary to provide structure for a name, the separate parts of the name
may be
encoded in {% include link elem="corpname" %} sub-elements, for example:

{% include plainExample.html example="examples/namesdates/namesdates-sample281.xml" valid="true" version=page.version %}
Standard designations for corporate bodies can be taken from a controlled vocabulary,
such
as the Gemeinsame Normdatei (GND). If a controlled value is used, the list from which
it is
taken should be recorded. In this case, the following attributes are particularly
relevant:

<table class="table table-striped">
   <thead>
      <tr>
         <th>Value</th>
         <th>Description</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td><span class="att">authority</span></td>
         <td> - to record the list from which a controlled value is taken,</td>
      </tr>
      <tr>
         <td><span class="att">authURI</span> (authority URI)
         </td>
         <td> - to record the web-accessible location of the controlled vocabulary from which the
            value is taken,
         </td>
      </tr>
      <tr>
         <td><span class="att">dbkey</span> (database key)
         </td>
         <td> - to record a value which serves as a primary key in an external database.</td>
      </tr>
   </tbody>
</table>