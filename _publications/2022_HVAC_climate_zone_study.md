---
layout: archive
title: "On Energy-efficient HVAC Operation with Model Predictive Control: A Multiple Climate Zone Study"
permalink: /_publications/2022_HVAC_climate_zone_study
author_profile: true
---

Naren Srivaths Raman, **Bo Chen**, and Prabir Barooah<br><span style="font-size:12pt"> *Applied Energy, Volume 324, 2022, 119752, ISSN 0306-2619.*</span><br>

[Paper](https://www.sciencedirect.com/science/article/pii/S0306261922010376)

<img 
src="/images/HVAC_climate_zone_study_results.png" 
width=1000 
style="float: right; margin-left: 10px; margin-right: 10px;">

**Abstract:** This paper aims to quantify the performance of Model Predictive Control (MPC) for a typical commercial building heating, ventilation and air conditioning (HVAC) system across a wide range of climate and weather conditions. The motivation of the study comes from the fact that although there is a large body of work on MPC for HVAC systems, there is a lack of studies that examine the range of possible performance of MPC, in terms of both energy savings and maintaining indoor climate (temperature and humidity) as a function of outdoor weather. A challenge in conducting such a study is developing an MPC controller that can be used in a wide range of weather. The root cause of this challenge is the need for a tractable cooling and dehumidification coil model that can be used by the MPC controller, since the coil may operate in quite distinct modes depending on weather. We present such an MPC controller, and then leverage it to conduct an extensive simulation campaign for fourteen climate zones in the United States and four weather conditions (winter, spring, summer, and fall) in each climate zone. The performance of the proposed controller is compared with not only a rule-based baseline controller but also with a simpler MPC controller that ignores humidity and latent heat considerations. There are several results the arise from this comparative study. One such result is that energy savings from MPC over baseline can vary dramatically based on climate and season. Another is that the effect of ignoring humidity in the MPC formulation can lead to poor indoor humidity control more in milder weather rather than in hot weather. The results from this study can help practitioners and researchers assess costs and benefits of proposed MPC formulations for HVAC control.