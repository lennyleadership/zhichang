---
weight: 3
title: Commitment to Quality
authors: Lenny Lin
categories: Interview
tags: [Commitment to Quality, Attention to detail, Mistakes, Integrity, AECL Situations]
date: " "
description: 
draft: false
lastmod: "2022-07-27"
series: null
toc: true
---


EC2.1 Sometimes, if we rush, we can make mistakes or overlook a mistake.  Describe a time that you made a mistake and had to act to prevent further impact.  (Maximum 500 words.)
In your response:
1) Describe the situation and its complexity.  
2) Describe the mistake you made and how you noticed the error.
3) Describe the steps you took to mitigate further impact of the error.
4) Describe what the impact would have been if the error wasn't noticed.  
5) Discuss how often this mistake could happen.

Please provide the contact information for someone that can corroborate your response.

<!--more-->

---

Answer: We used to determine volatile organic compounds (VOCs) in groundwater samples at AECL.  A comprehensive method was developed for detecting quantitatively 32 compounds, including benzene, ethylbenzene, toluene, and xylene (BTEX).  We ran proficiency test (PT) tests with this method.

During our routine analysis, we ran samples for BTEX with a shortlisted method in which there were only BTEX to cut off the time to process data.  

Two VOCs mixes were purchased.  Styrene was added to a commercially available ATG-17, and the rest of the 32 compounds came from another mix called ATG-16.  Even though we used the customized ATG-17 for the routine analysis, we did not report styrene.  

I used to purchase standard mixes by myself during the method development and validation.  A technologist took over the responsibility after the analysis was put into production.  When I purchased the new standard mix, I forgot to mention we need the customized ATG-17, not the commercial ATG-17.

There was a time new standard mixes were purchased without noticing styrene was not in the mix.  Routine BTEX testing went well.  It was until we failed on styrene at a PT that we realized we purchased the wrong ATG-17.  We found out by overlaying the styrene peaks with previous ones, the peaks were significantly lower than those before.

If the error was not noticed, and we ran routine samples for styrene, it would be a severe problem.

I asked the technologist to reorder the customized ATG-17 right away.  In the meantime, I prepared technical specification documents for standards for procurement references.

This mistake happened occasionally.

Furthermore, I learned from this mistake and developed an R Shiny application at LifeLabs to visualize all historical data of samples, including calibrators, QCs, internal standards, and a critical parameter of GC-MS/MS.  It became an effective diagnostic tool for troubleshooting analysis and proactively maintaining instruments.

Contact: KF


---
[Revisited 2023.02.06]

Answer: We used to determine volatile organic compounds (VOCs) in groundwater samples at AECL.  A comprehensive method was developed for quantitatively detecting 32 compounds, including benzene, ethylbenzene, toluene, and xylene (BTEX).  

Two VOCs mixes were purchased, ATG-16 and ATG-17.  ATG-16 contained 32 compounds, ATG-17 was customized and it contained BTEX plus additional Styrene.  

During our routine analysis, we only received requests of BTEX analysis, therefore, we used the ATG-17 mix.  The method was also shortlisted to have BTEX only.  Styrene was not detected and reported.  

I used to purchase standard mixes by myself during the stage of method development and validation.  After we put the method into production, a technologist took over the responsibility of purchasing.  

There was a time when we were about to run PT, we needed to purchase ATG-16 and ATG-17.  When placing the order of the new standard mixes, I forgot to mention we need the customized ATG-17, not the commercial ATG-17.

We failed on styrene at that time. We found it out by overlaying the styrene peaks of the problematic batch with previous batches. The peaks were significantly lower than those before.

This purchasing problem was not caught up during the routine analysis until we ran PT.  

If testing request was BTEX plus styrene, we would encounter a severe problem.

I asked the technologist to reorder the customized ATG-17 right away.  In the meantime, I prepared technical specification documents for standards for procurement references.

This mistake happened occasionally.

Furthermore, I learned from this mistake and developed an R Shiny application at LifeLabs to visualize all historical data of samples, including calibrators, QCs, internal standards, and a critical parameter of GC-MS/MS.  It became an effective diagnostic tool for troubleshooting analysis and proactively maintaining instruments.


