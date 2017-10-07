---
layout: sidebar
sidebar: s1
version: "v3"
title: "data.MEASUREMENTREL"

---

<div class="macroSpec">
   <h3 id="data.MEASUREMENTREL">data.MEASUREMENTREL</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">data.MEASUREMENTREL</span> Measurement expressed in real-world (e.g., centimeters, millimeters, inches, points,
            picas, or pixels) or virtual units (vu). 'vu' is the default value. Unlike
            data.MEASUREMENTABS, in which only positive values are allowed, both positive and
            negative
            values are permitted.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Used by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.distances">att.distances</a> (@dynam.dist), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.lyricstyle">att.lyricstyle</a> (@lyric.align), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.spacing">att.spacing</a> (@spacing.staff), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.staffDef.vis">att.staffDef.vis</a> (@spacing), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset.ho">att.visualoffset.ho</a> (@ho), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset.vo">att.visualoffset.vo</a> (@vo), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset2.ho">att.visualoffset2.ho</a> (@startho), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset2.vo">att.visualoffset2.vo</a> (@startvo)
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
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:data 
                        <span class="attribute">type=</span>
                        <span class="attributevalue">"token"</span>&gt;
                     </span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:param 
                           <span class="attribute">name=</span>
                           <span class="attributevalue">"pattern"</span>&gt;
                        </span>
                        <div class="indent4">(\+|-)?\d+(\.\d+)?(cm|mm|in|pt|pc|px|vu)?</div>
                        <span data-indentation="3" class="element">&lt;/rng:param&gt;</span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:data&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>