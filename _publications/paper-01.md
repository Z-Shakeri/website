---
title: "International Electronic Health Record-Derived COVID-19 Clinical Course Profile: The 4CE Consortium"
cohort: Adult
author: 4CE Consortium
date:   2020-08-19 00:00:00 -0500
paper_url: https://doi.org/10.1038/s41746-020-00308-0
paper_type: journal
journal: npj Digital Medicine
releases:
    release-2020-04-11:
        order: 1
        name: April 11, 2020
        description: >-
            This initial release includes data from 21 institutions.
---

{% include_relative paper-01_4ce_consortium_overview.html %}


<h2>Abstract</h2>


<h3>Introduction</h3>

The Coronavirus Disease 2019 (COVID-19) epidemic has caused extreme strains on health systems, public health infrastructure, and economies of many countries. 
A growing literature has identified key laboratory and clinical markers of pulmonary, cardiac, immune, coagulation, hepatic, and renal dysfunction that are associated with adverse outcomes. 
Our goal is to consolidate and leverage the largely untapped resource of clinical data from electronic health records of hospital systems in affected countries with the aim to better-define markers of organ injury to improve outcomes.


<h3>Methods</h3>

A consortium of international hospital systems of different sizes utilizing Informatics for Integrating Biology and the Bedside (i2b2) and Observational Medical Outcomes Partnership (OMOP) platforms was convened to address the COVID-19 epidemic. 
Over a course of two weeks, the group initially focused on admission comorbidities and temporal changes in key laboratory test values during infection. 
After establishing a common data model, each site generated four data tables of aggregate data as comma-separated values files. 
These non-interlinked files encompassed, for COVID-19 patients, daily case counts; demographic breakdown; daily laboratory trajectories for 14 laboratory tests; and diagnoses by diagnosis codes.

<h3>Results</h3>

96 hospitals in the US, France, Italy, Germany, and Singapore contributed data to the consortium for a total of 27,927 COVID-19 cases and 187,802 performed laboratory values. Case counts and laboratory trajectories were concordant with existing literature. Laboratory test values at the time of viral diagnosis showed hospital-level differences that were equivalent to country-level variation across the consortium partners.

<h3>Conclusions</h3>

In under two weeks, we formed an international community of researchers to answer critical clinical and epidemiological questions around COVID-19. Harmonized data sets analyzed locally and shared as aggregate data has allowed for rapid analysis and visualization of regional differences and global commonalities. Despite the limitations of our datasets, we have established a framework to capture the trajectory of COVID-19 disease in various subsets of patients and in response to interventions.

<a href="{{ page.paper_url }}">Read on {{ page.journal }} &rarr;</a>
<br/><br/>
<a href="{{ "/data/index.html" | relative_url }}#publication_{{ page.slug }}">Explore the data &rarr;</a>
