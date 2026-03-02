Lab: The Broad Street Outbreak Simulation
Practice Module

1. Clinical Context
It is September 1854. You have been recruited as a data assistant for Dr. John Snow. London is facing a catastrophic cholera outbreak, and the prevailing "Miasma Theory" (bad air) is failing to stop the deaths. Your mission is to use the provided clinical records to identify spatial and demographic trends that point toward a waterborne source.

2. The Data Dictionary
This repository contains a synthetic version of the Broad Street records: cholera_deaths.csv.

Column	Description
Death_ID	Unique identifier for each victim (integer).
Street	The recorded address of the victim at the time of death.
Age	Age of the deceased (years).
Gender	M (Male) or F (Female).
3. GitHub "Lab Protocol"
To complete this lab, you must demonstrate mastery of the Fork-Branch-PR workflow. This mimics the peer-review process used in professional bioinformatics pipelines.

Step 1: Initialize

Fork this repository to your personal account.

Clone your fork to your local machine.

Step 2: Branching

Create a new branch for your analysis: git checkout -b analysis-updates. Do not work on the main branch.

Step 3: Analysis

Open analysis_template.ipynb in Jupyter.

Complete the "TODO" sections (Data Inspection, Outlier Check, and Demographic Statistics).

Step 4: Submission

Commit your changes with a professional message.

Push your branch to your GitHub fork.

Open a Pull Request (PR) from your fork back to this original repository.