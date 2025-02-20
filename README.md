# CURE

Week 1

# cd
'''
change directory
'''
# pwd
'''
print working directory
'''
# mkdir
'''
make new directory
'''
# rm
'''
remove file
'''
# cp
'''
copy file
scp - for copying between different computers
'''
# mv
'''
move file
'''
# touch
'''
create an empty file
'''
# vi
'''
to view and edit text files
'''
# Headnode
'''
Computers assigned to handle user accounts, logins, and job management
Limited capacilities; Don't run jobs in headnode
'''
# Compute Nodes
'''
Built for heavy computational jobs
Where simulations are performed
'''
# Scheduler (SLURM)
'''
Manages jobs that have been submitted based on priority and job specifications
'''
# sbatch
'''
to submit jobs
'''
# squeue
'''
to monitor jobs that are in queue
Use squeue --me to view the jobs that you submitted only
'''
# Molecular Dynamics (MD)
''' 
a computational technique that is used to simulate the movement of atoms and molecules in a system over time
'''
# AMBER
''' 
software that allows us to run MD simulations
'''
# pdb file
''' 
A coordinate file that describes the postion of atoms in a protein
'''
# Equilibirum Still-Shot Analysis vs. Dynamic Equilibrium Analysis
''' 
Equilibirum Still-Shot Analysis - Taking a snapshot of an ensemble of molecules at equilibrium to analyze the various configuration of molecules and making an average
;    Dynamic Equilibirum Analysis - Focusing on the changing configuration of a single molecule to create a "movie" and compare the fraction of time it spends in each configuration
'''
# tLEAP
''' 
program that take protein coordinate files (pdb files) and creates a topology file, an inital structure of how the atoms connect with each other 
'''
# cpptraj
''' 
a software tool used to analyze MD simulations, allowing us to assess structural changes and behaviors
'''
# Root-mean-square Deviation (RMSD) analysis
''' 
measures how much a molecule deviates over time compared to a reference structure, a "general analysis"
'''
# Root-mean-square fluctuation (RMSF) analysis
''' 
Asseses residue-level or atomic-level flexibility; Very useful when assesing the impact of a mutation on a certain residue
'''
# AlphaFold
''' 
an AI system that predicts the 3D structure of proteins from their amino acid sequence; Goes through many configurations and gives the structure with the highest probability
'''
