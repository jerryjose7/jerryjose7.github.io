---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Journal Publications (preprint)

1.	Part 1: Multifractal analysis of wind turbine power and the associated biases, 
Jose, J., Gires, A., Roustan, Y., Schnorenberger, E., Tchiguirinskaia, I., and Schertzer, D.: 
Nonlin. Processes Geophys. Discuss. [preprint], https://doi.org/10.5194/npg-2024-5, in review, 2024.

2.	Part 2: Joint multifractal analysis of available wind power and rain intensity from an operational wind farm; Jose, J., Gires, A., Schnorenberger, E., Roustan, Y., Schertzer, D., and Tchiguirinskaia, I.:
Nonlin. Processes Geophys. Discuss. [preprint], https://doi.org/10.5194/npg-2024-6, in review, 2024.

Journal Publications (published)

3.	CAIPEEX: Indian Cloud Seeding Scientific Experiment (2023); Thara V Prabhakaran, Mercy Varghese, Mahen Konwar, Jerry Jose….Bulletin of the American Meteorological Society 104, 11

4.	Impact of monsoon on below cloud base aerosol hygroscopicity over a rain shadow region of India (2023
M Varghese, N Malap, M Konwar, S Bera, J Jose, SP Bankar, ... Atmospheric Research 285, 106630

5.	Combined high-resolution rainfall and wind data collected for 3 months on a wind farm 110 km southeast of Paris (France) (2022) A Gires, J Jose, I Tchiguirinskaia, D Schertzer, Earth System Science Data 14 (8), 3807-3819

6.	Scale invariant relationship between rainfall kinetic energy and intensity in Paris region: An evaluation using universal multifractal framework (2022), J Jose, A Gires, I Tchiguirinskaia, Y Roustan, D Schertzer, Journal of Hydrology 609, 127715

7.	Vertical profile of aerosol characteristics including activation over a rain shadow region in India (2022); M Varghese, J Jose, AS Anu, M Konwar, P Murugavel, N Kalarikkal, ...Atmospheric Environment 262, 118653

8.	Cloud and aerosol characteristics during dry and wet days of southwest monsoon over the rain shadow region of Western Ghats, India (2022);M Varghese, J Jose, AS Anu, P Murugavel, EA Resmi, S Bera, S Thomas, ...Meteorology and Atmospheric Physics 133 (4), 1299-1316


Conference Publications

1.	Joint multifratcal analysis of available wind power and rain intensity from an operational wind farm
J Jose, A Gires, E Schnorenberger, I Tchiguirinskaia, D Schertzer
EGU23

2.	Multi-scale comparison of rainfall measurement with the help of a disdrometer and a mini vertically pointing Doppler radar
MS Silva, RVC Monteiro, J Jose, A Gires, I Tchiguirinskaia, D Schertzer
EGU23

3.	Combined multifractal analysis of wind power production and atmospheric fields using simultaneous measurement of high-resolution data
J Jose, A Gires, E Schnorenberger, I Tchiguirinskaia, D Schertzer
EGU General Assembly Conference Abstracts, EGU22-6858

4.	Influence of lower threshold on empirical data in estimation of multifractal parameters (using atmospheric extinction coefficient as the field of study)
J Jose, A Gires, I Tchiguirinskaia, D Schertzer
AGU Fall Meeting Abstracts 2021, NG45C-0591

5.	Application of universal multifractal framework in estimating a new scale invariant power law relation between kinetic energy and intensity of rainfall
J Jose, A Gires, D Schertzer, Y Roustan, A Ruas, I Tchiguirinskaia
NSCCT20-International joint meeting on recent advances in nonlinear science

6.	Multifractal analysis of extinction coefficient and its consequences in characterizing atmospheric visibility
J Jose, A Gires, I Tchiguirinskaia, D Schertzer
EGU General Assembly Conference Abstracts, EGU21-11242

7.	Variability in Rainfall and Kinetic Energy across scales of measurement: evaluation using disdrometers in Paris region
J Jose, A Gires, D Schertzer, Y Roustan, A Ruas, I Tchiguirinskaia
EGU General Assembly Confer Abstract 994, 7765

8.	Variation of Aerosol Chemistry with Strengthening of South West Monsoon Using Individual Particle Analysis: A Case Study with Airborne Samples.
J Jose, M Varghese, S Thomas, N Kalarikkal, T Prabhakaran
Geophysical Research Abstracts 21


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
