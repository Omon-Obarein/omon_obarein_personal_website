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

**Gridded Population Modelling for DRC Vaccination Campaigns (Co-lead Modeller)**  
In the Democratic Republic of Congo, accurate and up-to-date population data is critical for planning vaccination campaigns. I co-led this project, which integrated multiple data sources and applied spatial modelling to produce gridded population estimates. These outputs directly supported the government and partners in delivering vaccines to hard-to-reach communities.
This work was part of the GRID3 – Phase 2 Scaling project, with funding from the Gates Foundation (INV-044979). Project partners included [GRID3 Inc](https://grid3.org/), [CIESIN](https://ciesin.climate.columbia.edu/) within the Columbia Climate School at Columbia University, and [WorldPop](https://www.worldpop.org/) at the University of Southampton.

![DRC Population Modelling Map](/images/DRC_Pop_map.png)

---


{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}