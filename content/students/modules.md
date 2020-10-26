+++
title = "Modules"
template = "students.html"
+++

{{ menu (act="students") }} 

{% top_image (title="Modules") %}
	petertahl.jpg
{% end %}

<div class="container">

<div id="accordion">

EMCL++ consists of 8 modules:

{% accordionItem(id="one", question="Start-up classes", cardH ="foo", ext=true) %}
<ul>
<li> Statistics and methods (Start-up classes RUG, 0 ECTS) </li>
<li> Introduction to clinical linguistics (Start-up classes RUG, 0 ECTS)</li>
<li> Introduction to theoretical linguistics (Start-up classes RUG, 0 ECTS)</li>
<li> Ethics and resilience (Start-up classes RUG, 0 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="two", question="Language and Culture", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="three", question="Methods", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="four", question="Clinical Linguistics and Neurolinguistics", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="five", question="Neurotechnology and IT for clinical linguistics", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="six", question="Internship", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="seven", question="Thesis", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="eight", question="Research Extra’s", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

</div>
</div>

{% credit() %}
Photo: &copy; UG, photographer: Peter Tahl.
{% end %}