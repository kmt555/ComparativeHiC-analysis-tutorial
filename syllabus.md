
# Comparative Hi-C data analysis, a tutorial

# Instructors names and contact information

Katarzyna M. Tyc<sup>* </sup> (katarzyna [dot] tyc [at] vcuhealth [dot] org)

Mikhail G. Dozmorov<sup>* </sup> (mikhail [dot] dozmorov [at] vcuhealth [dot] org)

<sup>* </sup> Department of Biostatistics, Virginia Commonwealth University, Richmond, Virginia

# Workshop Description

This is an introductory workshop to comparative Hi-C data analysis. The format of the class consists of an introductory lecture followed by hands-on practical examples. We will outline steps necessary for raw FASTQ data processing in order to obtain Hi-C contact matrices. The principles of joint normalization will be discussed, along with statistical tests applied to detect statistically significant differences in chromatin interaction frequencies between two or more Hi-C datasets. Participants will learn how to change between various Hi-C data formats. As part of the lab session, participants will perform Hi-C data normalization and generate a list of regions with significanlty different interaction frequencies. We will conclude with examples on how to visualize and interpret the results.

## Pre-requisites

* A computer with internet access 
* 20 GB of hard drive space
* Basic knowledge of command line tools
* RStudio and basic knowledge of R syntax
* Installed relevant R packages, as listed below

Expected background knowledge:

* Familiarity with NGS technologies and FASTQ format

Relevant background reading for the workshop:  

* "R Tutorial: Detection of Differentially Interacting Chromatin Regions From Multiple Hi‐C Datasets" John C. Stansfield, Duc Tran, Tin Nguyen, Mikhail G. Dozmorov. Current Protocols in Bioinformatics, 2019, https://currentprotocols.onlinelibrary.wiley.com/doi/full/10.1002/cpbi.76

## Workshop Participation

Participants are expected to actively participate in the workshop and run the example codes on their computers.

## _R_ / _Bioconductor_ packages used

Hi-C comparative analysis:

* HiCcompare

* multiHiCcompare 

* diffHic

* FIND

__Please make sure you have these packages installed prior to the beginning of the workshop.__

## Time outline

The workshop will run for 2 hours:

| Activity                     | Time |
|------------------------------|------|
| Introduction                 | 30m  |
| Data collection              | 15m  |
| Data normalization and comparative analysis  | 45m  |
| Data visualization and interpretation        | 30m  |

# Workshop goals and objectives

The overall goal of this workshop is to familiarize the participants with the processing of Hi-C data, and show how to integrate multiple Hi-C datasets into a single analysis workflow. The goal is to outline the inherent properties of Hi-C data and how these are exploited to allow for multi-Hi-C data comparisons. We will show how to retrieve Hi-C data from public repositories and switch between different Hi-C formats. The participants will perform normalization of the data, detect regions with differential interaction frequencies and visualize the results. By the end of the tutorial, participants will have enough background information to perform basic analysis of their own Hi-C data.

## Learning goals

* Define Hi-C data properties and different sources of bias in Hi-C data

* Identify tools for Hi-C data processing from raw FASTQ data to contact matrix

* Describe different formats for Hi-C contact matrices

  - .hic format http://aidenlab.org/data.html [developed in Aiden lab]

  - .cool format ftp://cooler.csail.mit.edu/coolers [developed in Mirny lab]

  - plain text, sparse upper-triangular matrix format

* Construct a pipeline for comparative analysis across multiple Hi-C data

## Learning objectives

At the conclusion of this workshop, participants will be able to:

* Retrieve Hi-C data from public repositories, e.g., Gene Expression Omnibus (GEO) 

* Apply methods for normalization of multiple Hi-C contact matrices 

* Apply methods for detection of chromatin regions with differential interaction frequencies

* Overlay the results with topologically associating domains

* Visualize and interpret the results

* Design a custom pipeline for the analysis of novel Hi-C data
