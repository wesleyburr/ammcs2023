# ammcs2023

Talk for AMMCS 2023 at WLU: Open Source Workflows for Mass Spectrometry Analysis

**Session [SS-MAAC]** Modelling and Analysis in Analytic Chemistry 

Open Source Workflows for Mass Spectrometry Analysis
D. Patel1 , R. Dargan1 , S. Forbes1,2 and W.S. Burr3

1 Department of Chemistry, Biochemistry and Physics, UQTR, Canada darshil.patel, rushali.dargan@uqtr.ca
2 Department of Chemistry and Biochemistry, University of Windsor, Canada shari.forbes@windsor.ca
3 Department of Mathematics, Trent University, Canada, wesleyburr@trentu.ca

## Abstract

It is very common for workflows connected to mass spectrometry to be entirely contained to closed-source
software provided by instrumentation manufacturers, e.g., LECO instruments are designed to work with the ChromaTOF [1] mass spectrometry data system, and the StatCompare suite of statistical tools. These tools have many
advantages: they are professionally designed, with modern graphical interfaces; they are tested and known to
process the data types produced by the instrument; and they are standard. They also have disadvantages: the algorithms are not publicly exposed; the process is limited to the implementation; and occasionally new instruments
are released which are not supported by the current version of the software suites.
In this talk we will discuss the development of two open source tools: the subMaldi package [4] for single
dimension mass spectrometry data; and gcgcWork [2, 3] for the reproduction of a somewhat standard GCxGC
workflow and pipeline, similar to key components provided by ChromaTOF. Both are created for the R programming environment, and available on GitHub. We will discuss the issues with implementation, especially with
respect to data size and format, and lay out the challenges ahead for producing higher quality, user-friendly software for common chemical analyses. In both cases, the packages were developed to aid in the analysis of forensic
science data sets: subMaldi for dried bloodstain chemical analysis; and gcgcWork for VOC analysis from human
body decomposition.


## References
* LECO, (2023) An Introduction to LECO’s Comprehensive Two-Dimensional Gas Chromatography (GCxGC) with ChromaTOF
Software. Available from: https://bit.ly/chromaTOF
* R. Dargan, (2022) Comparing the Decomposition Odour Between Cadavers and Human Remains being used as Cadaver Detection
Dog Training Aids (PhD thesis, UQTR, Quebec, Canada).
* D. Patel, (2023) Identifying the transition from ante-mortem odour to post-mortem odour (PhD thesis, UQTR, Quebec, Canada).
* Yeh, K., Castel, S., Stock, N. L., Stotesbury, T., & Burr, W. (2021). subMALDI: an open framework R package for processing
irregularly-spaced mass spectrometry data. Journal of Open Source Software, 6(65), 2694.


