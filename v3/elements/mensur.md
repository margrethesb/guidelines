---
layout: sidebar
sidebar: s1
version: "v3"
title: "mensur"

---

<div class="elementSpec">
   <h3 id="mensur">&lt;mensur&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">&lt;mensur&gt;</span> (mensuration) – Collects information about the metrical relationship between a note
            value and the next smaller value; that is, either triple or duple.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.mensural</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@altsym</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a way of pointing to a user-defined symbol. It must contain an ID of a
                  &lt;symbolDef&gt; element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.altsym">att.altsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@color</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to indicate visual appearance. Do not confuse this with the musical term
                  'color' as used in pre-CMN notation.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.COLOR">data.COLOR</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.color">att.color</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@copyof</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element of which the current element is a copy.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@corresp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                  fashion.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@dot</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Specifies whether a dot is to be added to the base symbol.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.BOOLEAN">data.BOOLEAN</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensur.log">att.mensur.log</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@facs</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Permits the current element to reference a facsimile surface or image zone which
                  corresponds to it.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.facsimile">att.facsimile</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontfam</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Contains the name of a font-family.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.FONTFAMILY">data.FONTFAMILY</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontname</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Holds the name of a font.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.FONTNAME">data.FONTNAME</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontsize</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                  relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                  size, e.g., "125%". 
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.FONTSIZE">data.FONTSIZE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontstyle</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the style of a font, i.e, italic, oblique, or normal.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.FONTSTYLE">data.FONTSTYLE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontweight</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to indicate bold type.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.FONTWEIGHT">data.FONTWEIGHT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@form</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates whether the base symbol is written vertically or horizontally.</span>
               Allowed values are:
               "
               <span style="font-weight: 500;">horizontal</span>" ,  "
               <span style="font-weight: 500;">vertical</span>" 
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensur.vis">att.mensur.vis</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@glyphname</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Glyph name.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.extsym">att.extsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@glyphnum</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B.
                  SMuFL version 1.18 uses the range U+E000 - U+ECBF.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">
                  a string matching the following regular expression: "(#x|U\+)[A-F0-9]+"
                  
               </span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.extsym">att.extsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@label</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@loc</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Holds the staff location of the feature.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.STAFFLOC">data.STAFFLOC</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.staffloc">att.staffloc</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@modusmaior</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the maxima-long relationship.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.MODUSMAIOR">data.MODUSMAIOR</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensural.shared">att.mensural.shared</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@modusminor</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the long-breve relationship.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.MODUSMINOR">data.MODUSMINOR</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensural.shared">att.mensural.shared</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@n</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a number-like designation for an element.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/token">token</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common">att.common</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@next</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@num</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Along with numbase, describes duration as a ratio. num is the first value in the
                  ratio, while numbase is the second.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">positiveInteger</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.duration.ratio">att.duration.ratio</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@numbase</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Along with num, describes duration as a ratio. num is the first value in the ratio,
                  while numbase is the second.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">positiveInteger</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.duration.ratio">att.duration.ratio</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@orient</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the rotation or reflection of the base symbol.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.ORIENTATION">data.ORIENTATION</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensur.vis">att.mensur.vis</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@prev</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@prolatio</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the semibreve-minim relationship.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.PROLATIO">data.PROLATIO</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensural.shared">att.mensural.shared</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@sameas</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                  copy of the current element.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@sign</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">The base symbol in the mensuration sign/time signature of mensural notation.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.MENSURATIONSIGN">data.MENSURATIONSIGN</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensur.log">att.mensur.log</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@size</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the relative size of a feature.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.SIZE">data.SIZE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.relativesize">att.relativesize</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@slash</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the number of slashes present.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.SLASH">data.SLASH</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.slashcount">att.slashcount</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@synch</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tempus</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the breve-semibreve relationship.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.TEMPUS">data.TEMPUS</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.mensural.shared">att.mensural.shared</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@when</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                  be the ID of a 
                  <a class="link_odd_elementSpec" href="/{{ v3}}/when">when</a> element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.alignment">att.alignment</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:base</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                  references into absolute URI references.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:id</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                  and other resources. Each id attribute within a document must have a unique
                  value.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">ID</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.id">att.id</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Member of</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ v3}}/model.eventLike.mensural">model.eventLike.mensural</a> 
               <a class="link_odd_classSpec" href="/{{ v3}}/model.staffDefPart.mensural">model.staffDefPart.mensural</a>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Contained by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild">
                     <span class="specChildModule">MEI.cmn</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/beam">beam</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/tuplet">tuplet</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/lem">lem</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/rdg">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/abbr">abbr</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/add">add</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/corr">corr</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/damage">damage</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/del">del</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/expan">expan</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/orig">orig</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/reg">reg</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/restore">restore</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/sic">sic</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/supplied">supplied</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/unclear">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.mensural</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/ligature">ligature</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/mensur">mensur</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/proport">proport</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.neumes</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/ineume">ineume</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/syllable">syllable</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/uneume">uneume</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/barLine">barLine</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/chord">chord</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/clef">clef</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/clefGrp">clefGrp</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/custos">custos</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/layer">layer</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/note">note</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/pad">pad</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/rest">rest</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/space">space</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/staffDef">staffDef</a>
                     </span>
                  </div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">May contain</span>
         </td>
         <td class="wovenodd-col2">
            <div class="specChild">
               <span class="specChildModule">Empty</span>
               <span class="specChildElements"></span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;classes&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.common">att.common</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.facsimile">att.facsimile</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.mensur.log">att.mensur.log</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.mensur.vis">att.mensur.vis</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.mensur.ges">att.mensur.ges</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.mensur.anl">att.mensur.anl</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.eventLike.mensural">model.eventLike.mensural</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.staffDefPart.mensural">model.staffDefPart.mensural</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:empty/&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Remarks</span>
         </td>
         <td class="wovenodd-col2">
            <p>The 
               <a class="link_odd_elementSpec" href="/{{ v3}}/mensur">mensur</a> element is provided for the encoding of mensural
               notation. The 
               <span class="att">slash</span> attribute indicates the number lines added to the
               mensuration sign. For example, one slash is added for what we now call 'alla breve'.
            </p>
         </td>
      </tr>
   </table>
</div>