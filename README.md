<div align="center"> <div>&nbsp;</div> <img src="docs/alphafold3_title.png" width="300"/> </div>
Introduction
AlphaFold3 is already available as a pre-installed module on the MSU High Performance Computing Cluster (HPCC).
The model can be accessed directly through the HPCC module system without requiring local installation.
Structure Prediction
To predict the structures of eight proteins organized in the input directory folder, batch inference was performed.
All protein input files were prepared prior to submission.
Job Submission on HPCC
A SLURM job script named:
af3_protein.sb
was submitted to HPCC to run AlphaFold3 on the eight protein inputs.# af3_CHE882_project
