---
title: "pre- and post-tsunami aceh through satellite imagery"
layout: post
date: 2016-01-23 22:10
tag: [geology, landsat]
image: ../assets/images/projects/thumbnail/aceh.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
jemoji: '<img class="emoji" title=":satellite:" alt=":satellite:" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4e1.png" height="20" width="20" align="absmiddle">'
category: geo
author: tiffanycitra
externalLink: false
---

This is my final project for one of the best classes I have taken at Brown so far — *Global Environmental Remote Sensing (Spring 2015)*.

---

![Preprocessed Images](../assets/images/projects/aceh/preprocessed.png)
*Preprocessed images displayed in natural color (321)*

Using Landsat 5 TM imagery, I attempted to explore the relationship between land cover changes and socioeconomic growth in pre- and post-tsunami Aceh, Indonesia. To do so, I compared land cover in December 2004 (pre-tsunami), January 2005 (right after tsunami), and February 2010 (post-tsunami).

I used ENVI to do the necessary preprocessing (dark pixel subtraction and reflectance calibration), select the region of interest (Banda Aceh and Aceh Besar), and finally perform spectral mixture analysis  — with four end members: urban, sediment, vegetation, and shades — to quantify land cover changes.

![Processed Images](../assets/images/projects/aceh/processed.jpg)
 *Stacked end member map in (red) 2004, (cyan) 2010: (top-left) sediment, (top-right) shades, (bottom-left) urban, (bottom-right) vegetation*

---

<p align="center"><img class="aceh" title="Land Cover Changes" src="../assets/images/projects/aceh/land-cover.png" width="50%"><br>
<i>Land cover changes</i></p>

We can see from the table above that the percentage of urban and sediment areas increase quite significantly, whereas vegetation and shade areas decrease.

My findings suggest that remote sensing can be used to correlate land cover changes with socioeconomic growth in Aceh, Indonesia. The results obtained in this project display relatively similar trends as the growing economic sectors and population growth in the region, as well as a previous study that maps the land use changes within the same time period (Achmad, 2013).

**Reference:**

Achmad, A. (2013). Land use changes in the urban growth process after a tsunami using RS and GIS: A case of Banda Aceh, Indonesia. CSIS (Center for Strategic and International Studies) Days 2014, Tokyo, Japan.
