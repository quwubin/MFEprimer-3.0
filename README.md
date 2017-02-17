# MFEprimer-3.0: PCR Primer Quality Control

The name "MFEprimer" comes from the title of the first paper (2009, Bioinformatics): Multiple Factor Evaluation 
of the specificity of PCR primers. And both the version 1.0 and version 2.0 (2012, NAR) are only focused on primer
specificty, leaving dimers and hairpins for users. However, dimers and hairpins are very important factors 
affecting success of PCR. So, for version 3.0, we expand the functions of MFEprimer, and make it as a 
full-functional primer quality control (PrimerQC, maybe the new name) program. The features of version 3.0 including:

1. genomewide specificity check;
2. new and fast dimer check algorithm;
3. new and fast hairpin check algorithm;
4. primers compatible check for multiplex PCR;
5. thermodynamics based hybridization analysis;
6. core algorithm was rewritten with golang, which is fast and parallel.

