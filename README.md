# Longitudinal Dynamics of Viral Exposure & Epigenetic Drift

[![R](https://img.shields.io/badge/Language-R-blue.svg)](https://www.r-project.org/)
[![Cohort](https://img.shields.io/badge/Cohort-Milieu--Int%C3%A9rieur-green.svg)](https://www.milieuinterieur.fr/en/)

This repository contains the data processing workflows, statistical models, and visualization code for my poster exploring **"Longitudinal Dynamics of Viral Exposure and Epigenetic Drift in the Milieu Intérieur Cohort"**.
**[Download / View Full Poster PDF](https://github.com/user-attachments/files/31151039/ISI_2026_MI_Viruses.pdf)**


## Overview
Persistent viral exposures (e.g., CMV, SARS-CoV-2) are recognized drivers of chronic inflammation and immune exhaustion, yet their life-course influence on the methylome remains poorly understood. Using high-throughput multiplex serology (*Luminex INTELLIFLEX®*) and DNA methylation profiling across a 10-year follow-up of the *Milieu Intérieur* cohort ($n = 1,000$), this study investigates age-dependent windows of viral-driven epigenetic maturation and biological age acceleration (DNAm PhenoAge).  


## 10-Year Biological Ageing in the (very) healthy *Milieu Intérieur* cohort.

<img width="3200" height="1000" alt="Fig000x_PhenoAge_Transition_HighRes" src="https://github.com/user-attachments/assets/68c2ed8f-358c-4e11-9604-f74f6cdee5b8" />  

These individuals look about 10 years younger biologically (DNAm PhenoAge) than their chronological age. After 10 years, they still look about 10 years younger than their new chronological age. This is a really important caveat, as the effect we are investigating here is extremely small. What does "age acceleration" look like in a population that are not really ageing? Later, we explore infections in a nationally representative cohort.  


## Important Note: Inverse Life-Course Rate of Epigenetic Acceleration in a Healthy Cohort

<img width="6400" height="4000" alt="Fig0001_PhenoAgeResidual_Vs_Age" src="https://github.com/user-attachments/assets/bc1fc7b5-e6fd-472a-81c7-8281e7791210" />  

Despite biological impairment accumulating exponentially in late life, younger individuals in this healthy cohort display a significantly higher propensity for accelerated epigenetic drift over 10 years. Because the Milieu Intérieur cohort strictly screens for overall good health at enrolment, older participants *might* represent a resilient "healthy survivor" subset, whereas younger adults retain broader variance and capacity for early biological ageing. In other words, if you are disease free and morbidity free at 55, it appears more likely that you stay this healthy compared to a "healthy" 25 year old. There could be other explanations too, such as cohort effects relating to age-related dropout.  
  
To account for this, we actually normalise our "Ageing Residual" to what is expected relative to age-mates, using linear regression.  

<img width="6400" height="4000" alt="Fig0001_PhenoAgeExpectedResidual" src="https://github.com/user-attachments/assets/4d66106d-6ef0-4568-a6fd-9984bf09fc10" />  


## Increases in PhenoAge after 10 years is most strongly associated with cell composition in healthy adults.  

<img width="7200" height="3600" alt="Fig0003_Cells_CellsRatios" src="https://github.com/user-attachments/assets/0fcabb8b-dd78-4b60-864b-16f62144d126" />    


<img width="3200" height="3600" alt="Fig0003_Cells_CellsVSExpectedResidual_Models" src="https://github.com/user-attachments/assets/ee48439e-24af-44f7-93ff-b18547eebcd9" />


## Increases in PhenoAge after 10 years is not strongly associated with evidence of prior infection in healthy adults.  

<img width="7200" height="2800" alt="Fig0002_AgeingFastSlow_Vs_Viruses" src="https://github.com/user-attachments/assets/094162e5-5dfa-4a4b-9739-aeb5d19cacc8" />

While we do not see any strong signals, it is worth nothing that this is very possibly a sensitivity issue - our antibody readout is really one single snapshot into the viral exposure of each individual before and after 10 years. More regular, real-time documentation of exposure and responses is much more likely to reflect the exposome dynamics of an individual. Additionally, as noted in our animated figure, these individuals are quite healthy; we may be more likely to see a signal in a more representative ageing population.  

## Teaser: in our upcoming study, we investigate the association between frailty and becoming infected, symptomology, and the subsequent association between infections and progression of frailty.

<img width="4455" height="1651" alt="Frailty_VC_CMV" src="https://github.com/user-attachments/assets/b9f53030-1f9e-46c4-ae0a-cb4c1aa6978b" />



