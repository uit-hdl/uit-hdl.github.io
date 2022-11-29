---
title: Software
---

# Software

This page contains links to the source code for our publications. Note that code without a public repository is generally not maintained anymore. We will however help with any questions and issues as best as we can.
Contact: larsab@cs.uit.no

## Open source projects

We have developed the META-pipe pipeline for marine metagenomics data analysis. We plan to open source most of these repositories. Version 2.0 consists of several backend systems, servers, and services:
1. [Marine Metageonomics Portal](https://mmp.sfb.uit.no/). Marine reference databases and more.
2. [Galaxy pipeline](https://galaxy-uit.bioinfo.no/) provided as part of the [](https://nels.bioinfo.no/)NeLS infrastructure. It is intended for Norwegian users so a a FEIDE account is needed for login.
3. [Spark based execution manager](https://gitlab.com/uit-sfb/newpan-tools) and [Go components](https://gitlab.com/uit-sfb/newpango). Closed source.
4. [META-pipe job manager](https://gitlab.com/uit-sfb/jobmanager).
5. [META-pipe authentication service](https://gitlab.com/uit-sfb/AuthService2) that is integrated with Elixir AAI.
6. [META-pipe web application](https://gitlab.com/uit-sfb/newpan-frontend).
7. [Object storage server](https://gitlab.com/uit-sfb/newpango). Closed source.
8. [Tool to setup META-pipe backend on the OpenStack](https://gitlab.com/uit-sfb/METApipe-cPouta-cloud-setup) [cPouta cloud](http://pouta.csc.fi).			
9. [Tool to setup META-pipe backend on OCCI enabled endpoints](https://github.com/cduongt/mmg-cluster-setup-CESNET).			
10. [Scripts to setup META-pipe backend on AWS EMR](https://gitlab.com/uit-sfb/metapipe-on-aws).
11. [META-pipe deployment scripts](https://gitlab.com/uit-sfb/metapipe-deploy). These will not be open sourced.
12. [Marine Metagenomics Portal code](https://gitlab.com/uit-sfb/MarineMetagenomicPortal).
13. [Marine reference databases web app](https://gitlab.com/uit-sfb/mar-frontend). Closed source.
14. [Galaxy-Pulsar integration on the Stallo Supercomputer](https://gitlab.com/uit-sfb/METApipe-cPouta-cloud-setup). This is specific to the Stallo machine and will not be open sourced.
15. [Auto scaling framework, simulator and runtime](https://github.com/TTeige/uit-go).

Source code for META-pipe 1.0 is in the following repositories. Note that these are not maintained anymore:

16. [META-pipe 1.0](https://github.com/emrobe/META-pipe). Implemented for execution on HPC clusters.
17. [Patches for META-pipe specific metarep (1.4.0)](https://github.com/elixir-marine/metarep) sequence retrieval modifications.

These repositories are from research projects that use data, infrastructure, or problems from the META-pipe project:

18. [GeStore](https://github.com/EdvardPedersen/GeStore). This is a system for enabling transparent incremental updates for metagenomic pipelines.
19. [nrsoot](https://github.com/uit-no/nsroot). Minimalist process isolation tool implemented with Linux namespaces.
20. [COMBUST I/O](https://github.com/jarlebass/combustio). Abstractions facilitating parallel execution of programs implementing common I/O patterns in a pipelined fashion as workflows in Spark.
21. [Mario](https://www.cs.uit.no/hdl/code/mario/mario.zip) is a system for interactive data analysis built on top of the HBase storage system.
22. [Benchmark](https://www.cs.uit.no/hdl/code/mario/hbase-evaluation.zip) used to evaluate the performance of Hbase using data and access pattern found in typical biological data processing tools. 

We have developed a system for data management and standardized preprocessing of the data in the NOWAC study:

23. [nowaclite](https://ice-git.cs.uit.no/nowac/nowac): R based data management for biinformatics data.
24. [NOWAC R package](https://ice-git.cs.uit.no/nowac/nowac): has information about the available datasets and analyses you can run on them. (closed source)
25. [Pippeline](https://ice-git.cs.uit.no/nowac/pippeline): standardized  and interactive pipeline for NOWAC data preprocessing.
26. [nowaclean](https://github.com/3inar/nowaclean). R package implementing the methods of the standard operating procedure for 
27. [geneset](https://github.com/3inar/geneset). R package of data sets and functions that facilitate gene set analysis.
28. [seq](https://github.com/fjukstad/seq). A collection of Docker containers with different	bioinformatics tools, such as GATK, bwa, and Picard, installed.
29. [GeneNet VT](https://github.com/kolibrid/GeneNet-VR). Interactive visualization of large-scale biological networks using a standalone VR headset.

We have developed systems for data management, analysis and exploration in the NOWAC project. But these can also be used for other datasets:

30. [NOWAC R package](https://github.com/uit-bdps/nowaclite) for managing and documenting omics data.
31. [Kvik](https://github.com/fjukstad/kvik). A framework for developing interactive data exploration applications in genomics and systems biology.
32. [walrus](https://github.com/fjukstad/walrus). A system for running data analysis pipelines using Docker containers.
33. [Freia](https://github.com/Knudah/Freia). Biological Path Visualization using Unity3D to visualize gene expression data integrated with pathway images.
34. [KEGGviewer](https://github.com/Knudah/Keggviewer). Simple Python Flask web viewer for KEGG images.


In addition, we have developed many different data analyses that are specific for the NOWAC data:

35. [MIxT](https://github.com/fjukstad/mixt). Matched Interaction Across Tissues (MIxT) is a web application for exploring and comparing transcriptional profiles from two or more matched tissues across individuals. [Online](http://mixt-blood-tumor.bci.mcgill.ca)					
36. [Smoking variables](https://github.com/uit-bdps/smoking-variables). Estimate smoking status and other smoking-related variables the NOWAC-cohort.

The air:bit project repositories are:

37. [Luft](https://github.com/fjukstad/luft). Web application for visualizing air quality in Tromsø with	data from The Norwegian Institute for Air Research (NILU) and Kongsbakken VGS. [Online](http://luft.cs.uit.no). 
38. [air:bit backend platform](https://github.com/ninaangelvik/luft). The backend is deployed on Google Cloud Platform.
39. [Air quality sensor and web server](https://github.com/ninaangelvik/luftprosjekttromso). An Arduino-based portable air quality sensor kit and a Ruby on Rails web application deployed on Heroku.
					
Source code for our research projects (random order):			
<!-- Morten -->
40. [Histology learning tool](https://github.com/Gronnesby/Histology) for use in a browser with a Python backend .
<!-- Einar -->
41. [validator](https://github.com/3inar/validator). an R package for running repeated k-fold cross-validation.
42. [So you want to use R on stallo](https://github.com/3inar/stallo_r). A brief guide to launching long-running embararssingly parallel R jobs on the UiT supercomputer Stallo.
43. [Supporting data and code](https://github.com/3inar/crime_rates) to "Empirical bayes shrinkage estimation of crime rate statistics".
44. [krongen](https://github.com/3inar/krongen). Creates kronecker graphs that simulate networks with power law edge distributions.
<!-- Nikita -->
44.  [HoVer-net pipeline](https://github.com/SFI-Visual-Intelligence/hovernet-pipeline). Modified version of [HoVer-Net](https://github.com/vqdang/hover_net).
45.  [HoVer-buid](https://github.com/uit-hdl/hover_build). Setup HoVer-Net environment.
46.  [HoVer-serving](https://github.com/uit-hdl/hover_serving). for inference only code for HoVer-Net we use in [Histology viewer](https://github.com/uit-hdl/histology).
47.  [HEImmune](https://github.com/uit-hdl/HEImmune). Simple rule-based classification of cells in H&E images.
48.  [ROI TILs quantification project](https://github.com/uit-hdl/roi-quant). Region of interest detection in whole-slide images.
<!-- Rafael -->
45. [Fit Futures social network](https://github.com/uit-hdl/mimisbrunnr). Fit Futures social network analysis code and results.
<!-- Other projects -->
45. [Heart sound classification](https://github.com/uit-hdl/heart-sound-classification). Algorithm for predicting valvular heart disease from heart sounds in an unselected cohort.
47. [rhd-codes](https://github.com/uit-hdl/rhd-codes) Automatic transcription of numeric codes from Norwegian population census 
48. [Handwritten digit recognition](https://github.com/TTeige/rhd) and [a solution implemented in Keras](https://github.com/johanravn/handwritten-number-classification).
49. [UiT Github course guide and template](https://github.com/uit-no/github-course-guide). The unofficial guide for using GitHub for UiT courses.
<!-- Theses -->
46. [rhd-linking](https://github.com/uit-hdl/rhd-linking) Record linkage of Norwegian historical census data using machine learning.
47. [Ship-detection](https://github.com/matill/Ship-detection) ShipPointYOLO: Ship Detection and Description based on Point Coordinates in SAR Images
49. [norpd_prescription_analyses](https://github.com/uit-hdl/norpd_prescription_analyses) Spark and Jupyter notebooks to analyse data from the Norwegian Prescription Database 
50. [Replication code](https://github.com/mikevoets/jama16-retina-replication)for [Replication study: Development and validation of deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs](https://arxiv.org/abs/1803.04337).
51. [DICOM anonymizer](https://github.com/mikevoets/dicom_anonymizer).
52. [Mr. Clean](https://github.com/UniversityofTromso/mrclean) is a tool for combining different visualization tools, interaction devices, and display middleware for visual comparisons on high-resolution displays.
53. [M.O.R.T.A.L.](http://sourceforge.net/projects/mortal/) is a  programming language for domain  specific high performance computing.
54. [Spell expression data processing pipeline](http://gtrac-spell-tools.princeton.edu/trac/wiki). This a data cleaning pipeline for microarray data.
55. [Troilkatt](https://github.com/larsab/troilkatt) is a system for scalable batch processing of biological data built on the hadoop stack.
56. [BSV system](http://www.cs.uit.no/~larsab/bsv/) for scalable visualizations on multi-core and multi-display platforms. 
<!-- Note! New projects are added to the top of the list. -->
