# GSoC 2022 Progress Report
This is the official repository for my GSoC 2022 project with ML4SCI.
Titled: **Vision Transformers for End-to-End Particle Reconstruction for the CMS Experiment**
This project aims to add Vision Transformer and related models to the already present CMS E2E
pipeline for more accurate analysis and classification.</br>
<ins>This is repository is still under-development and may contain some unnecessary files</ins>.</br>
Note:Till completion this report will act as **progress report** for the project and will be converted
to a detailed documentation once the development phase is over
***
### Problem Statement
If the reader has idea of what he/she is dealing with I would advise to proceed further.

In this project we are working with multi-detector images corresponding to true maps of low-level
energy deposits in the detector for various type of particle collision events in CMS(CERN).
In laymans term we are using the data generator by the detectors in the CMS experiment to 
learn more about the particles and analyse them. The used in our case are Monte-Carlo simulated 
data. We are using the follwing data and contructing images(jet image) out of them and using
Machine Learning to analyse(in our case Classify) them. Differnt types of detectors or sensors
produce different types of data or in our case jet images.
These are some jet images for the Quarks and Gluons







