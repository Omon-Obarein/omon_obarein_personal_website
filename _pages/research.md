---
title: "Research"
layout: archive
permalink: /research/
author_profile: true
---
## Key Projects and Roles

---

**Count-Down to 2030 – Geospatial Modelling of Maternal Health Outcomes Across Sub-Saharan Africa (Lead Modeller)**  
This project supports the global Countdown to 2030 initiative, which tracks progress toward maternal and child health targets. I led spatial statistical modelling to understand the distribution of antenatal care visits and malaria prevalence among pregnant women across Sub-Saharan Africa. The outputs provide critical evidence to guide interventions and policies to improve maternal health outcomes.  

![Maternal Health Outcomes Map](/images/pred_maps.png)

---

**Geospatial Modelling of Vaccine Coverage in Nigeria (Lead Modeller)**  
This project explored inequalities in immunisation coverage by applying Bayesian and machine learning approaches. By comparing estimates from different modelling frameworks, we were able to highlight areas with low vaccination uptake in Nigeria and Ethiopia. The results provide valuable evidence for improving vaccine equity and ensuring no child is left behind.  

![Vaccine Coverage Map](/images/Vaccine.png)

---

**Estimation of Populations Targeted for Vaccination in Cameroon (Lead Modeller)**  
Accurate population estimates are essential for planning vaccination campaigns. In this project, I led efforts to combine microcensus data with geospatial information to estimate the number of children eligible for vaccination. These high-resolution estimates are designed to support national immunisation programmes and improve vaccine delivery strategies.
Project partners include [GAVI](https://www.gavi.org/), [Bluesquare](https://www.bluesquarehub.com/) and Expanded Program on Immunisation (EPI) in Cameroon

![Cameroon Vaccination Target Map](/images/Cameroon.png)

---

**Adjusting for Census Undercount in Jamaica (Lead Modeller)**  
Censuses often undercount certain groups, leading to gaps in official statistics. I developed a statistical model to adjust Jamaica’s census results by accounting for undercounts, improving national population estimates. This work ensures better planning for healthcare, education, and resource allocation.  
*Output year: 2025*  

![Jamaica Census Adjustment Map](/images/jamaica_census.png)

---

**Gridded Population Modelling for DRC Vaccination Campaigns (Co-lead Modeller)**  
In the Democratic Republic of Congo, accurate and up-to-date population data is critical for planning vaccination campaigns. I co-led this project, which integrated multiple data sources and applied spatial modelling to produce gridded population estimates. These outputs directly supported the government and partners in delivering vaccines to hard-to-reach communities.  
*Output year: 2024*  

![DRC Population Modelling Map](/images/drc_population.png)

---

**Top-down Population Modelling Using Bayesian Methods (Lead Modeller)**  
This project advanced methods for census disaggregation by applying Bayesian machine learning approaches. The goal was to generate fine-scale population distribution maps from national census totals. The outputs demonstrated improved accuracy and reliability, contributing to more effective use of census data for policy and research.  
*Output year: 2023*  

![Top-down Population Modelling Map](/images/topdown_population.png)

---

**Population Estimates for Cameroon Using Hierarchical Geostatistical Models (Co-lead)**  
In collaboration with national and international partners, this project developed subnational population estimates for Cameroon using hierarchical Bayesian geostatistical models. The work provided more granular and reliable estimates than official figures alone, strengthening evidence for public health planning and resource allocation.  
*Output year: 2022*  

![Cameroon Population Estimates Map](/images/cam.png)

---


{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}