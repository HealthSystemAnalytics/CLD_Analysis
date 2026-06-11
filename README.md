# CLD Structural Analysis

This repository contains the R script, Vensim CLD file, and CSV outputs used for the supplementary structural analysis of the causal loop diagram reported in the manuscript:

//Conceptualizing Hospital Readmission Dynamics in the Danish Healthcare System: An Evidence-Informed Qualitative System Dynamics Study//

The analysis reconstructs the CLD as a signed directed graph, enumerates and classifies feedback loops, summarizes variable participation in feedback loops, and assesses first-arrival path-based qualitative influences on **30-Day Readmission Rate**.

To reproduce the outputs, run the script from the repository root:

source("QualitativeCLDAnalysis.R")

The analysis requires the R package: igraph

The script does not perform calibrated simulation, inverse-based Levins community-effect analysis, or impose diagonal self-effects/self-damping assumptions.
