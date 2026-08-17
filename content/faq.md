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

{% accordionItem(id="four", question="I have not received my diploma yet/I will finish my BA in 2027. Is that a problem?", cardH ="noDiploma", ext=false) %}
Not a problem at all. You need to send us (so upload it in the application portal) a transcript of records plus a statement of your university that you will finish your studies before the 1st of September 2027.
{% end %}

{% accordionItem(id="five", question="What are the requirements for the motivation letter?", cardH ="motivationLetter", ext=false)%}
The motivation letter should be 1-2 pages. Not longer than 2 pages in any case.
{% end %}

{% accordionItem(id="english", question="Are alternatives accepted for the English Proficiency Test, such as MOI, Duolingo, Tesol, Pearson?", cardH ="englishCert", ext=false) %}
No, you still need to send in the results of one of the English Proficiency Tests - Academic version - as mentioned on our website, not older than 2 years.
{% end %}

{% accordionItem(id="referee", question="Why has my referee not received the link, to answer the reference questions, straight after I submitted my application?", cardH ="refereeLink", ext=false)%}
We first need to check if your application package is complete and if you are eligible for our programme. Once that is completed, your referees will be contacted.
{% end %}

</div>
<br>

# Programme

<div id="accordion_prog">

{% accordionItem(id="start", question="When does the EMCL programme start?", cardH ="start date", ext=true) %}
The programme starts on September 1, 2027.
{% end %}

{% accordionItem(id="startPlace", question="Which semester is offered by which partner/where?", cardH ="where", ext=true) %}
Starting with the cohort 2025-2027, the first semester will be spent at UEF (Finland), the second semester at UGENT (Belgium) and the third semester at RUG (the Netherlands). The location of the final semester depends on the internship and thesis and could be at either of the partner's institutions or at a different location (external partner).
{% end %}

</div>

</div>


