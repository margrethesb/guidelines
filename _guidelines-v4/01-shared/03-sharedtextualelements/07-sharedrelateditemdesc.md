---
sectionid: sharedRelatedItemDesc
title: "Related Items"
version: "v3"
---

In some situations it is necessary to provide references from one bibliographic item
to
another. For these situations, MEI offers the {% include link elem="relateditem" %} element. A
{% include link elem="relateditem" %} may be used inside of {% include link elem="bibl" %}, and
may either point to a different entity using its **@target** attribute, or may hold
the related item as child. 

{% include plainExample.html example="examples/shared/shared-sample013.xml" valid="true" version=page.version %}
 In this example, the nested {% include link elem="relateditem" %} / {% include link elem="bibl" %}
provides information about the ‘container’ where the outer {% include link elem="bibl" %} may be found. The kind of relation is expressed using the
**@rel** attribute. It describes the relationship of the child {% include link elem="bibl" %} to the {% include link elem="relateditem" %}'s parent {% include link elem="bibl" %}. 



{% include desc atts="relateditem/rel" %}




 In these relations, the subject is always the relatedItem, and the object is always
the
parent of the relatedItem. Thus, a value of **@rel**="preceding" indicates that the
resource described within the relatedItem (or referenced by its **@target** attribute)
precedes the {% include link elem="bibl" %} containing the {% include link elem="relateditem" %}.
Following MODS, both values of "preceding" and "succeeding" indicate a temporal order.


 It is important not to confuse {% include link elem="relateditem" %} with the concepts of {% include link id="frbr" %}; see {% include link id="headerrelateditemvsfrbr" %}. 
