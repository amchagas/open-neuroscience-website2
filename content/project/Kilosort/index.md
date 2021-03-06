---
title: 'Kilosort'
date: 2021-03-21
authors: ['admin']
layout: post
categories: ['Software','Data Analysis','Animal electrophysiology','Computational Neuroscience','worldwideseries']
tags: ['Software','Data Analysis','Animal electrophysiology','Computational Neuroscience','worldwideseries']
---

## World Wide Series Seminar  

{{< youtube FlRql3g41iE >}}

Kilosort is a software package for identifying neurons and their spikes in extracellular electrophysiology, a process known as "spike sorting". Kilosort has been primarily developed and tested on the Neuropixels 1.0 probes, but is now used on data acquired with a wide variety of ephys methods, from Utah arrays to tetrodes and to the latest Neuropixels 2.0 probes.  

Spike sorting consists of several largely-independent steps: data preprocessing, drift correction, spike clustering, template matching, and results postprocessing. There have been several versions of Kilosort, improving on various aspects of these steps, and we are currently on version v3. In many cases, and especially for Neuropixels probes, the automated output of Kilosort3 requires minimal manual curation. The main change from v2.5 is a completely new and much more sophisticated clustering algorithm. To learn about Kilosort2.5, the primary reference is the Neuropixels 2.0 paper. Kilosort2.5 improves on Kilosort2 primarily in the type of drift correction we use. Where Kilosort2 modified templates as a function of time/drift (a drift tracking approach), Kilosort2.5 corrects the raw data directly via a sub-pixel registration process (a drift correction approach). 

All versions of Kilosort so far have been developed and released in Matlab. However, we are advancing towards Python releases of the codebase, including of older version like Kilosort 2 and 2.5 (available here: https://github.com/MouseLand/pykilosort/tree/master/pykilosort ).
## Project Author(s)
Marius Pachitariu
## Project Links
https://github.com/MouseLand/Kilosort
## Project Video
{{< youtube clq50N7V_wA >}}

***
This post was automatically generated by
Marius Pachitariu
***
