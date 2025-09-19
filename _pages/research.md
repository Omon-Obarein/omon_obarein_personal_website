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

![Maternal Health Outcomes Map](image_path/countdown2030.png)

```{r echo = FALSE, fig.align = "left", out.width = "100%", fig.cap ="**Fig. 1 The Delaunay Triangulation of a Sample Mesh used for the INLA-SPDE implementation. The red points are the centroids of the spatial units**."}
knitr::include_graphics("images/pred_maps.tif")
```


{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}