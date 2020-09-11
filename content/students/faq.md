+++
title = "FAQs"
template = "students.html"
+++


{{ menu (act="students") }} 

{% top_image (title="FAQ's") %}
	petertahl.jpg
{% end %}


<div class="container">

<div id="accordion">
  
{% accordionItem(id="one", question="First Question", cardH ="foo", ext=true) %}
Bla bla bla - good question. This one is easy to answer, just read the guidelines...
{% end %}

{% accordionItem(id="two", question="Second Question", cardH ="bar") %}
Bla bla bla - good question- I don't have the answer right now, please check back.
{% end %}

{% accordionItem(id="three", question="Third Question", cardH ="bla") %}
Bla bla bla - good question- I don't have the answer right now, please check back.
We'll answer all questions as soon as possible...
{% end %}

</div>







</div>

{% credit() %}
Photo: &copy; UG, photographer: Peter Tahl.
{% end %}

