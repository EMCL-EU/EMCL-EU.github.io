+++
title = "FAQs"
template = "page.html"
+++


{{ menu (act="faq") }} 

{% top_image (title="FAQs", credit="UG, photographer: Peter Tahl") %}
	petertahl.jpg
{% end %}


<div class="container">

# Application/admission

<div id="accordion">
  
{% accordionItem(id="one", question="I cannot find EMCL in 'Studielink'!", cardH ="studielink", ext=true) %}
The name of the EMCL programme in "Studielink" is "Research Master Clinical Linguistics".
{% end %}

{% accordionItem(id="two", question="Should I upload my reference letters in progress?", cardH ="reference letter", ext=false) %}
There is a confusing message in the application system. The instructions in Progress ask you to upload the reference letters. However, on our website we mention that your referees need to send their letters to the emailaddress: <A HREF="mailto:emcl@rug.nl">emcl@rug.nl</A>. <br><br>

This is what needs to be done: ask your referees to send their letters to <A HREF="mailto:emcl@rug.nl">emcl@rug.nl</A>. As soon as we received them, we will notify the admissions office to tick the necessary box in Progress
{% end %}

{% accordionItem(id="three", question="When will I receive the payment link for the application fee?", cardH ="paymentLink", ext=false) %}
You will receive the link for payment from our admissions office after you submitted your package in the progress portal.
{% end %}

{% accordionItem(id="four", question="I have not received my diploma yet/I will finish my BA  in 2024. Is that a problem?", cardH ="noDiploma", ext=false) %}
Not a problem at all. You need to send us (so upload it in the progress portal) a transcript of records plus a statement of your university that you will finish your studies before the 1st of September 2024.
{% end %}

</div>
<br>

# Programme

<div id="accordion_prog">

{% accordionItem(id="start", question="When does the EMCL programme start?", cardH ="start date", ext=true) %}
The programme starts on September 1, 2024.
{% end %}
</div>

</div>


