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

#### <b>First language (L1) Acquisition</b>
***
<strong>(Featural) Relativized Minimality and Intervention Effects in Child Languages</strong>


<strong>Acquisition of passives in Mandarin</strong>
Cross-linguistically, children’s acquisition of passive sentences is delayed, with long passives – those in which the agent is expressed (e.g., 'The mouse is chased by the cat') – even more difficult for children to understand and/or produce than short passives (e.g., 'The mouse is chased'). We aim to determine what causes these difficulties by examining the effects of grammar (the Intervention Hypothesis, Friedmann et al., 2009) and language input in children’s passive acquisition in Mandarin, a language in which this construction is understudied and the sparse existing literature shows conflicting results on this topic. Our project contains a corpus study (<a href="/assets/pdf/Liu_BUCLD46_poster.pdf" target="_new">preliminary results</a>) and three behavioral experiments. The corpus study is the first large-scale investigation on child Mandarin passives, investigating CHILDES (MacWhinney 2000) corpora from 1,182 children and their caretakers. The three experiments will investigate 3- to 6-year-olds’ comprehension of Mandarin long and short passives and test the predictions of the Intervention Hypothesis with respect to the role of morpho-syntactic and semantic features, which remains to be done in any language. 


Collaborator(s):
* [Nina Hyams](https://linguistics.ucla.edu/person/nina-hyams/) <br>
* [Victoria Mateu](https://www.victoriamateu.com)<br>


<strong>Acquisition of (psudo-)sluicing in Mandarin</strong>
Sluicing refers to an elliptical structure in which only a wh-phrase is overt in a CP, as in "Someone left. I don’t know who". In Mandarin, sluice-like strings (‘S-strings’) with argument wh-remnants require the presence of "shi", a form that is ambiguous between a copula and a focus marker. My [MA thesis](https://www.proquest.com/docview/2330601872/F87CEFA1CCBA4A89PQ/2?accountid=14512)  proposes a hybrid analysis of Mandarin S-strings as having two possible derivations, a sluice and a pseudo-sluice, unless one of the structures is independently forced. When "shi" is a copula, the S-string has a pseudo-sluice analysis, [pro be wh-phrase], involving neither movement nor ellipsis. When "shi" is a focus marker, the S-string is derived by focus movement followed by TP-ellipsis yielding a sluice analysis. Results from a comprehension experiment with 59 Mandarin-speaking children show that 3-4-year-olds have only a pseudo-sluice/copula analysis of S-strings. They acquire the sluice/focus movement derivation at approximately age 5 at which point they show the “subject advantage” typically associated with A’-movement structures in young children.

<!-- <ol>
  <li>What conditions the allomorphy displayed by the irrealis and perfective prefixes?</li>
  <li>What is the semantic information conveyed by the TAM prefixes?</li>
</ol> -->



<br>
#### <b>Syntax</b>
***
<!-- <strong>Acquisition of non-local phonotactic dependencies</strong>

Sundara et al.'s (2022) meta-analysis on phonotactic acquisition found that infants display sensitivity to vowel harmony before any other local or non-local phonotactic dependency. This is despite the fact that non-local dependencies are reportedly more difficult to learn than local dependencies. We are currently planning a series of experiments to investigate two main questions:
<ol>
  <li>Is the early sensitivity that infants display for vowel harmony due to its perceptual saliency?</li>
  <li>Does experience with vowel harmony aid infants in the learning more arbitrary non-local dependencies?</li>
</ol>

Collaborator(s):
* [Megha Sundara](https://linguistics.ucla.edu/person/megha-sundara/)

<strong>Non-concatenative morphological priming across Semitic languages</strong>

We are using Bayesian meta-analysis to investigate morphological priming effects in Arabic, Hebrew, and Maltese. Semitic languages are well-known for their extensive non-concatenative morphology; most Semitic words (e.g., <i>inkataba</i> 'he subscribed' in Arabic) can be decomposed into a consonantal root carrying the main lexical semantics (e.g., k-t-b is a triconsonantal root associated with the concept of writing) and a template associated with morphosyntactic information (e.g., inCaCaCa is a template for 3.SG intransitive past tense verbs). We are using the aggregate data points to look at the status of non-concatenative morphology in the adult grammar. [You can find a list of papers to be included in the meta-analysis here.](https://docs.google.com/spreadsheets/d/1N3mGwNddj4hi0lgn-QGvubxZmvcLL9nPDyjDE1GbOxw/edit?usp=sharing)

Collaborator(s):
* [Lily Xu](https://sites.google.com/view/lilyxxu/)<br>
* Huilei Wang<br>
* [Megha Sundara](https://linguistics.ucla.edu/person/megha-sundara/) -->

<br>
#### <b>Fieldwork</b>
***
<strong>Lachirioag Zapotec</strong>


<strong>Tonggu Gan Chinese</strong>

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
