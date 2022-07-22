---
layout: page
title: Research
ord: 20
permalink: /research/
description:
nav: true
display_categories: # [work, fun]
horizontal: false
---

#### <b>First Language Acquisition</b>
***
<strong>(Featural) Relativized Minimality and Intervention Effects in Child Mandarin</strong>

Collaborator(s):
* [Nina Hyams](https://linguistics.ucla.edu/person/nina-hyams/) <br>
* [Victoria Mateu](https://www.victoriamateu.com)<br>

<strong>Acquisition of passives in Mandarin</strong>\\
Cross-linguistically, children’s acquisition of passive sentences is delayed, with long passives – those in which the agent is expressed (e.g., 'The mouse is chased by the cat') – even more difficult for children to understand and/or produce than short passives (e.g., 'The mouse is chased'). We aim to determine what causes these difficulties by examining the effects of grammar (the Intervention Hypothesis, Friedmann et al., 2009) and language input in children’s passive acquisition in Mandarin, a language in which this construction is understudied and the sparse existing literature shows conflicting results on this topic. Our project contains a <a href="/assets/pdf/Liu_BUCLD46_LongPass.pdf" target="_new">corpus study </a> and three behavioral experiments. The corpus study is the first large-scale investigation on child Mandarin passives, investigating CHILDES (MacWhinney 2000) corpora from 1,182 children and their caretakers. The three experiments will investigate 3- to 6-year-olds’ comprehension of Mandarin long and short passives and test the predictions of the Intervention Hypothesis with respect to the role of morpho-syntactic and semantic features, which remains to be done in any language. 



Project outputs:
* 

<strong>Acquisition of (psudo-)sluicing in Mandarin</strong>\\
Sluicing refers to an elliptical structure in which only a wh-phrase is overt in a CP, as in "Someone left. I don’t know who". In Mandarin, sluice-like strings (‘S-strings’) with argument wh-remnants require the presence of "shi", a form that is ambiguous between a copula and a focus marker. My [MA thesis](https://www.proquest.com/docview/2330601872/F87CEFA1CCBA4A89PQ/2?accountid=14512)  proposes a hybrid analysis of Mandarin S-strings as having two possible derivations, a sluice and a pseudo-sluice, unless one of the structures is independently forced. When "shi" is a copula, the S-string has a pseudo-sluice analysis, [pro be wh-phrase], involving neither movement nor ellipsis. When "shi" is a focus marker, the S-string is derived by focus movement followed by TP-ellipsis yielding a sluice analysis. Results from a comprehension experiment with 59 Mandarin-speaking children show that 3-4-year-olds have only a pseudo-sluice/copula analysis of S-strings. They acquire the sluice/focus movement derivation at approximately age 5 at which point they show the “subject advantage” typically associated with A’-movement structures in young children.

Project outputs:
* 

<!-- <ol>
  <li>What conditions the allomorphy displayed by the irrealis and perfective prefixes?</li>
  <li>What is the semantic information conveyed by the TAM prefixes?</li>
</ol> -->



<br>
#### <b>Theoretical Syntax</b>
***
<strong>Mandarin passives</strong>\\


Project outputs:
* 

<strong>Mandarin (psudo-)sluicing</strong>\\


Project outputs:
* 





<br>
#### <b>Fieldwork</b>
***
<strong>San Cristóbal Lachirioag Zapotec (Jan--July 2020)</strong>\\
I conducted fieldwork on a Zapotec language spoken in San Cristóbal Lachirioag, Oaxaca, Mexico in the  Field Methods class at UCLA Linguistics. Weekly elicitation sessions have
<!-- * Speaker: Julio Dominguez -->
* Collaborators: Prof. [Harold Torrence](https://linguistics.ucla.edu/person/harold-torrence/) (adviser), Prof. [Pam Munro](https://linguistics.ucla.edu/person/pamela-munro/), Maddy Booth, [Hironori Katsuda](https://hironori1123.github.io/Homepage/), Christine Prechtel, [Iza Sola-Llonch](https://soy.elsolallon.ch), Andy Xu, and [Z.L. Zhou](https://zlzhou.me).


Project outputs:
* __Liu, Minqi__. 2021. _Adverbial Clitics in San Cristóbal Lachirioag Zapotec_. Poster presented at the 2021 Annual Meeting of Society for the Study of the Indigenous Languages of the Americas (SSILA 2021), Online. [<a href="/assets/pdf/Liu_SSILA2021_AdvClitics.pdf" target="_new">Presentation slides</a>]
* __Liu, Minqi__. 2020. _Dependent and independent pronouns in San Cristóbal Lachirioag Zapotec_. UCLA Manuscript [<a href="/assets/pdf/Liu_SCLZ_pronoun.pdf" target="_new">PDF</a>]


<strong>Tonggu Gan Chinese (Summer 2016)</strong>\\
I participated in a dialect documentation project by Peking University on a Gan dialect spoken in Tonggu, Jiangxi, China. I worked closely with a local speaker for 56 hours on elicitation and collaborated with my cohorts on a 150-page comprehensive description of the Gan variety in Tonggu, including its phonetics and phonological systems, as well as a general introduction to its lexicon and characteristic syntax structures. We also recorded, annotated, and digitized five long narrative stories by local  speakers. 
<!-- * Speaker: Xinxing Shuai -->
* Collaborators: Prof. Mengbing Xiang (adviser), Yun Feng, Zhijia Ni, and Zhihao Wang.

<!-- <br>
#### <b>Phonological Adaptation in Code-switch</b>
*** -->

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
