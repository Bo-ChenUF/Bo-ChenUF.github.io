---
layout: archive
title: "The Bounded Gaussian Mechanism for Differential Privacy"
permalink: /_publications/2022_The_Bounded_Gaussian_Mechanism_for_Differential_Privacy
author_profile: true
---

**Bo Chen**, and Matthew Hale<br><span style="font-size:12pt">Accepted by *Journal of Privacy and Confidentiality.*</span><br>

[Paper](https://arxiv.org/pdf/2211.17230.pdf)

<img 
src="/images/bounds_compare.png" 
width=600 
style="float: right; margin-left: 10px; margin-right: 10px;">

**Abstract:** The Gaussian mechanism is one differential privacy mechanism commonly used to protect numerical data. However, it may be ill-suited to some applications because it has unbounded support and thus can produce invalid numerical answers to queries, such as negative ages or human heights in the tens of meters. One can project such private values onto valid ranges of data, though such projections lead to the accumulation of private query responses at the boundaries of such ranges, thereby harming accuracy. Motivated by the need for both privacy and accuracy over bounded domains, we present a bounded Gaussian mechanism for differential privacy, which has support only on a given region. We present both univariate and multivariate versions of this mechanism and illustrate a significant reduction in variance relative to comparable existing work.

