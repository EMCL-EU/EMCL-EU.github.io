+++
title = "Modules"
template = "students.html"
+++

{{ menu (act="students") }} 

{% top_image (title="Modules", credit="UG, photographer: Peter Tahl") %}
	petertahl.jpg
{% end %}

<div class="container">

<div id="accordion">

All modules of the EMCL++ program are graded with ECTS. A student has to obtain at least 120 ECTS, 30 ECTS in each term, including internship and thesis. The program is divided into 8 modules: 


{% accordionItem(id="one", question="Start-up classes (no ECTS)", cardH ="foo", ext=true) %}
<ul>
<li> Statistics and methods (Start-up classes RUG, 0 ECTS) </li>
<li> Introduction to clinical linguistics (Start-up classes RUG, 0 ECTS)</li>
<li> Introduction to theoretical linguistics (Start-up classes RUG, 0 ECTS)</li>
<li> Ethics and resilience (Start-up classes RUG, 0 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="two", question="Language and Culture (9 ECTS)", cardH ="foo", ext=true) %}
<ul>
<li> Language and Culture (Dutch) (RUG, 1st term, 3 ECTS) </li>
<li> Language and Culture (Dutch) (UGENT, 2nd term, 3 ECTS)</li>
<li> Language and culture (Finnish) (UEF, 3rd term, 3 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="three", question="Methods (16 ECTS)", cardH ="foo", ext=true) %}
<ul>
	<li>Statistics and Research Methods in Psycholinguistics (UGENT, 2nd term, 9 ECTS)</li>
	<li>Speech technology for speech impairment research (UEF, 3rd term, 4 ECTS)</li>
	<li>Python programming for linguistic research (UEF, 3rd term, 3 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="four", question="Clinical Linguistics and Neurolinguistics (37 ECTS)", cardH ="foo", ext=true) %}
<ul>
	<li>Language and speech disorders in adults (RUG, 1st term, 5 ECTS)</li>
	<li>Language and speech disorders in children (RUG, 1st term, 5 ECTS)</li>
	<li>Language testing in awake brain surgery (RUG, 1st term, 6 ECTS)</li>
	<li>Bilingualism (UGent, 2nd term, 4 ECTS)</li>
	<li>Dyslexia (UGent, 2nd term, 4 ECTS)</li>
	<li>Advances in psycholinguistics (UGent, 2nd term, 3 ECTS)</li>
	<li>Computational models in psycholinguistics (UGent, 2nd term, 4 ECTS)</li>
	<li>Language and autism (UEF, 3rd term, 2 ECTS)</li>
	<li>Articulatory, acoustic and perceptual analysis of speech motor disorders (UEF, 3rd term, 4 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="five", question="Neurotechnology and IT for clinical linguistics (14 ECTS)", cardH ="foo", ext=true) %}
<ul>
	<li>Neuroimaging and Language (RUG, 1st term, 5 ECTS)</li>
	<li>Development of serious games, apps and virtual reality for language impaired populations (RUG, 1st term, 6 ECTS)</li>
	<li>Eye-tracking in language research (UGent, 2nd term, 3 ECTS)</li>
</ul>
{% end %}

{% accordionItem(id="six", question="Internship (10 ECTS)", cardH ="foo", ext=true) %}
The internship will take place in the 3rd term and will be conducted at one of the associated partner institutions. (10 ECTS)
{% end %}

{% accordionItem(id="seven", question="Thesis (34 ECTS)", cardH ="foo", ext=true) %}
The thesis will be written in the fourth term, under supervision of (at least) a teacher at one of the three partner universities. (30 ECTS) <br/>

Additionally, the course "Academic writing (Thesis preparation)" (4 ECTS) will be offered in the 3rd term at UEF.
{% end %}

{% accordionItem(id="eight", question="Research Extras (no ECTS)", cardH ="foo", ext=true) %}
Research Extras will be provided throughout the programme. This could be colloquia, reading circles, excursions and participation at the Science of Aphasia conference.
{% end %}

</div>
</div>
