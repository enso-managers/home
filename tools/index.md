---
layout: default
title: Tools
---

# Tools

The following tools use code and ontology of the <a href="https://gfse.org">GfSE</a> Initiative <a href="https://specif.de">SpecIF</a>
to which enso managers GmbH has contributed substantially.
The tools are open-source and free to use, however a donation is very welcome to support further development of methods and standards 
in the area of Systems Engineering and Enterprise Architecture.

<ul>
<li><a href="#specif-editor">SpecIF Model-Integrator and Editor</a></li>
<li><a href="#sheet2reqif">Sheet → ReqIF</a></li>
<li><a href="#bpmn2word">BPMN → Word® and ePub</a></li>
<li><a href="#open-source">Donation to Open Source Software</a></li>
</ul>


<h2 id="specif-editor">SpecIF Model-Integrator und Editor</h2>

<p><a href="https://specif.de">SpecIF</a> is the 'Specification Integration Facility'. It combines partial specifications from different tools in a semantic net for</p>
<ul>
<li>searching, navigating and auditing partial results in a common context as well as</li>
<li>exchanging model information between organizations and tools.</li>
</ul>
<p>Use the tool <a href="https://specif.de/apps/edit.html" target="_blank">SpecIF Model-Integrator und Editor</a>. For instructions, please refer to the <a href="https://specif.de/Manuals/01_Quick-Start-Guide_EN.html" target="_blank">Quick Start Guide</a>.</p>
<p>A <a href="https://specif.de/apps-alpha/edit.html" target="_blank">newer version</a> is currently under test and not yet released. 
New features include the import of UML Class Diagrams as well as SysML Block Definition Diagrams and Internal Block Diagrams plus an
export using RDF triples to populate a knowledge graph.</p>


<h2 id="sheet2reqif">Sheet → ReqIF</h2>

<p>Transform a workbook with one or more spreadsheets (Excel® *.xlsx, LibreOffice *.ods as well as *.csv) to the Requirements Interchange Format (ReqIF). The property names are expected in the first line (column head) and an entity (<span class="text-bg-light"><em>SPEC-OBJECT</em></span> in ReqIF terms) with its property values per following line.</p>
<p>The property names are semantically interpreted and mapped using the <a href="https://specif.de/apps/edit.html#import=https://specif.de/v1.1/Ontology.specif" target="_blank">SpecIF Ontology</a>. For example, a property name <span class="text-bg-light"><em>Title</em></span> is first normalized to <span class="text-bg-light"><em>dcterms:title</em></span> and then mapped to <span class="text-bg-light"><em>ReqIF.Name</em></span> as suggested by the 
<a href="https://www.ps-ent-2023.de/fileadmin/prod-download/prostep-ivip_ImplementationGuide_ReqIF_V1-8.pdf" target="_blank">Prostep iViP ReqIF Implementation Guideline</a>. 'Ontology-based' means that the interpretation and translation of terms is entirely defined by the underlying ontology. Please share your <a href="https://github.com/enso-managers/SpecIF-Tools/discussions/1" target="_blank">ideas and comments</a>.</p>
<p>Use the tool <a href="https://tools.enso-managers.de/sheet2reqif.html" target="_blank">Sheet → ReqIF</a>. For instructions, please refer to the <a href="./intro-sheet2reqif.html" target="_blank">Introduction to Sheet → ReqIF</a>.</p>


<h2 id="bpmn2word">BPMN → Word® and ePub</h2>

.. coming soon.


<h2 id="open-source">Donation to Open Source Software</h2>

<div style="float: left; margin: 6px 9px 0 0;" > <iframe src="https://github.com/sponsors/enso-managers/button" title = "Sponsor enso-managers" height = "32" width = "114" style = "border: 0; border-radius: 6px;" > </iframe></div >
<div style="padding-top:0.5em"><p>Is any of these tools of value to you, would you like to make a donation?</p><p>You support further development of transformations and model integration to improve collaboration over the product lifecycle, see <a href="https://cascade.gfse.org" target="_blank">Project CASCaDE</a>.</p></div>

