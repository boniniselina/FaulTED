# FaulTED

<img width="500" height="143" alt="logo" src="https://github.com/user-attachments/assets/a0dbcb5f-1bc0-41cb-bcd2-3725f317fff8" />


FaulTED is a new MATLAB-based toolkit for Probabilistic Fault Displacement Hazard Analysis (PFDHA), integrating multiple published models, magnitude-frequency distributions, fault scaling relationships and surface rupture probability functions referring to different fault kinematics styles (i.e., normal, reverse, strike-slip faults), which are available in scientific literature. The toolkit features two main modules: 
(i) a site-specific hazard curve calculator, and 
(ii) a fault-specific hazard map generator for user-defined return periods. 

Both modules account for on fault and distributed off-fault ruptures, explicitly incorporating the floating rupture approach commonly adopted in probabilistic seismic hazard analysis. 
This toolkit was developed in the framework of Dr. Selina Bonini's PhD project (University of Bologna, co-founded by Italferr S.p.A., and in collaboration with Autorité de Sûreté Nucléaire et de Radioprotection - ASNR, Istituto di Geofisica e Vulcanologia - INGV, and Università degli Studi "G. D'Annunzio" Chieti e Pescara). 

The code is written in MATLAB (v.R2024a).
This repository contains two .zip folders (referring to the specific tool), each of them including three main directories: 
    (i) Input, where input files can be placed; 
    (ii) Output, where the code stores the modeling results in a dedicated folder created for each run; and 
    (iii) Sources, which contains all the source codes used by the main script to perform the calculations. The main script is located outside these directories along with a “Read me” in .pptx format. 

The source code is described in  a manuscript in preparation for submission to the journal Earthquake Spectra: 
Bonini, S., O. Scotti, A. Valentini, F. Visini, B. Pace, G. Tartaglia, G. Viola, G. Vignaroli. FaulTED: a probabilistic fault displacement hazard code exploring floating ruptures scenarios and epistemic uncertainties.
