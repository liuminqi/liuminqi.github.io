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

#### <b>Fieldwork (Lachirioag Zapotec)</b>
***

<strong>Verbal prefixes</strong>

My [MA thesis](https://www.proquest.com/pagepdf/2611991924?accountid=14512) provided a general description of the verbal morphology found in Lachirioag Zapotec, with a particular focus on the verbal TAM prefixes and the argument enclitics. Currently, I am continuing my investigation into the verbal prefixes with focus on two main questions:
<ol>
  <li>What conditions the allomorphy displayed by the irrealis and perfective prefixes?</li>
  <li>What is the semantic information conveyed by the TAM prefixes?</li>
</ol>

<strong>Acoustics of the fortis/lenis contrast (with Lily Xu)</strong>

Zapotec languages are described as having a fortis/lenis contrast for both obstruent and sonorant consonants. Despite the name, the two classes of consonants have been found to be primarily distinguished by duration in other Zapotec languages. Our <a href="/assets/pdf/ssila22_SCLZfortislenis.pdf" target="_new">preliminary results</a> support the previous findings, and additionally find voicing to be a significant acoustic correlate for obstruents. We are currently gathering more data, and hope that our results will provide us a better understanding of how the fortis/lenis contrast in Zapotec fits in the larger typology of laryngeal contrasts.

<br>
<hr width="50%" size="8" align="left">
Other linguists who work or have done work on Lachirioag Zapotec include: <br>
* Madeleine Booth (UCLA)<br>
* Michael Galant (UC Dominguez Hills)<br>
* [Harold Torrence](https://linguistics.ucla.edu/person/harold-torrence/) (UCLA)<br>
* [Pamela Munro](https://linguistics.ucla.edu/person/pamela-munro/) (UCLA)

There have also been community efforts to document and create language materials. A page with a collection of Zapotec resources is upcoming.

<br>
#### <b>Experimental</b>
***
<strong>Acquisition of non-local phonotactic dependencies</strong>

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
* [Megha Sundara](https://linguistics.ucla.edu/person/megha-sundara/)

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
