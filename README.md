# README
## Repoducibility Report for "Inferring sources of substandard and falsified products in pharmaceutical supply chains"
This repository generates synthetic data file for the IISE submission "Inferring sources of substandard and falsified products in pharmaceutical supply chains."
Syntethic data and accompanying figures and tables mirror the content and principles contained in the paper but do not exactly replicate what is shown with deidentified data.

ReproducibilityReportPythonCode.py contains all necessary functions for generating figures and tables.
generateExampleInference() generates the inference example figure (Figure 2) located in Section 5 of the paper.
generateSyntheticData() creates a synthetic data set to mirror key qualities of the deidentified data, including figures and tables analagous to Figures 3 and 4 in Section 6, Figure 5 in Appendix D, and Tables 2 and 3 in Appendix D.
timingAnalysis() captures the MCMC computation time results shown in Table 1; this function may take upwards of an hour to run.