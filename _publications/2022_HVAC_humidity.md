---
layout: archive
title: "Model Predictive Control for Energy-efficient HVAC Operation with Humidity and Latent Heat Considerations"
permalink: /_publications/2022_HVAC_humidity
author_profile: true
---

Naren Srivaths Raman, Karthikeya Devaprasad, **Bo Chen**, Herbert A. Ingley, and Prabir Barooah<br><span style="font-size:12pt"> *Applied Energy, Volume 279, 2020, 115765, ISSN 0306-2619.*</span><br>


[Paper](https://www.sciencedirect.com/science/article/pii/S0306261920312502)

<img 
src="/images/HVAC_humidity_energy_consumption.png" 
width=600 
style="float: right; margin-left: 10px; margin-right: 10px;">

**Abstract:** Even though energy-efficient climate control of commercial buildings using model predictive control (MPC) has been widely investigated, most MPC formulations ignore humidity and latent heat. The inclusion of moisture makes the problem considerably more challenging, primarily since a cooling and dehumidifying coil model which accounts for both sensible and latent heat transfers is needed. In this work, we propose an MPC controller in which humidity and latent heat are incorporated in a principled manner. We construct low order data-driven models of a cooling and dehumidifying coil that can be used in the MPC formulation. The resulting controller’s performance is tested in simulation using a plant that differs significantly from the model used by the optimizer. Additionally, the performance of the proposed controller is compared with that of a naive MPC controller which does not explicitly consider humidity, and also to that of a conventional rule-based controller. Simulations show that the proposed MPC controller outperforms the other two in terms of energy use and thermal comfort. It is also observed that the naive MPC formulation which does not consider humidity leads to poor humidity control under certain conditions. Such violations in humidity can adversely affect occupant comfort and health.