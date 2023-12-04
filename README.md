[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060753&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/https://github.com/27410/group-assingment-team11.git/main)

# 27410 - Group assignment - Group 11 - Biosynthesis of isoamyl acetate by Saccharomyces cerevisiae

## Project summary
This project investigates the biosynthesis of isoamyl acetate using the yeast Saccharomyces cerevisiae, to optimize its enhanced production. Isoamyl Acetate, known as a banana flavor ester, is used in the food, beverage, pharmaceutical, and cosmetic industries. Our report begins with a literature review, outlining the chemical pathways of isoamyl acetate synthesis and its market potential. Product-relates issue is a low production rate that can be solved through metabolic engineering strategies. Therefore, we applied MEMOTE comparison for 7 potential S. cerevisiae models to identify the most suitable model for the project. We conducted yields and media optimization analysis, phenotypic phase plane analysis, FSEOF, and co-factor-swapping optimization analysis to highlight the main bottlenecks of the process and find feasible solutions for the product. The DFBA showed that cells respond to different applied environmental conditions and identified genetic modifications with higher isoamyl acetate production.

## Project overview
This projects is organized in a following way. [Report.ipynb](Report.ipynb) cointains core text description of the project covering introduction, problem definition, selection and assesment of excisting GSM, computer-aided cell factory engineering, discussion and conclusion parts with short statements, tables and figures. 
Main code with results is splited between 6 files related to different analyses.
1. _[02 Model and pathway](02_Model_and_pathway.ipynb)_ - MEMOTE comparison for 7 potential S. cerevisiae models.
2. _[03 Theoretical yields and media optimization](03_Theoretical_yields_and_media_optimization.ipynb)_ - Yields and media optimization analysis.
3. _[04 Phenotype phase plane](04_Phenotype_phase_plane.ipynb)_ - Phenotypic phase plane analysis on the baseline growth and progesterone production for identification cell response to changes in conditions.
4. _[05 Gene target analysis](05_Gene_target_analysis.ipynb)_ - FSEOF analysis of the model with identification of targets for doqnregulation and upregulation.
5. _[06 Co-factor swap](06_Co-factor_swap.ipynb)_ - Co-factor-swapping optimization analysis.
6. _[07 Dynamic FBA](07_Dynamic_FBA.ipynb)_ - Dynamic flux analysis to identify cell response to different environmental conditions or genetic modifications.

In the folder _[Files](Files)_ reaction with manually changed co-factors can be found. Folder _[Models](Models)_ contains yeast models we used for memote analysis. We put figures that are used in the _[Report.ipynb](Report.ipynb)_ to the folder _[Pictures](Pictures)_.
