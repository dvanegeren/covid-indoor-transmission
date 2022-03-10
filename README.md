# Simulations of within-classroom COVID-19 transmission

Code for reproducing all analyses except the CFD simulations (Fig. 7) in "No magic bullet: limiting in-school transmission in the face of variable SARS-CoV-2 viral loads".

The code is broken into multiple iPython notebooks:

+ plot_room_simulations.ipynb has the majority of the results from the ODE model describing viral accumulation in classrooms and the effect of different interventions on airborne viral concentrations. Figs. 1-6 and S1 can be reproduced using this code.
+ fraction_inhaled_virions.ipynb executes the calculations used to estimate the fraction of inhaled virions using the published data on respiratory droplet size from [Xie et al](https://pubmed.ncbi.nlm.nih.gov/19812073/) and fluid dynamics simulations in the nasopharynx from [Basu (2021)](https://www.nature.com/articles/s41598-021-85765-7). These data are provided here in droplet_sizes.csv, which should be placed in the same directory as this script to facilitate data loading.
+ num_infected_individuals_poisson.ipynb contains the code for assessing the effect of changing class sizes on COVID-19 transmission (Fig. 8).

Questions? Contact Debra at debra.vanegeren@gmail.com.
