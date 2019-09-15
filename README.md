# matplotlib-challenge
### Applying pandas and matplotlib to a pharmaceutical trial database

This project analyzes treatment data from an animal study of potential treatments for Squamous Cell Carcinoma.  250 mice were treated with a variety of drug regimes over 45 days.  Tumor size and metastatic site counts were the outcomes measured.  This analysis evaluates four treatments - Capomulin, Infubinol, Ketapril and Placebo - with regards to tumor size, metastic site count, and survival rates of the mice.  

### Included files
*[Jupyter Notebook with code, tables and figures](pymaceuticals/pymaceuticals_main.ipynb)
*Original Data CSV Files

 -[Clinical Trial](pymaceuticals/data/clinicaltrial_data.csv)
 
 -[Mouse-Drug](pymaceuticals/data/mouse_drug_data.csv)
 
*Figures
 -[Tumor Response to Treatment](pymaceuticals/figures/tumor_response.png)
 
 -[Metastatic Spread During Treatment](pymaceuticals/figures/metastatic_spread.png)
 
 -[Survival During Treatment](pymaceuticals/figures/survival.png)
 
 -[Tumor Change over 45 day Treatment](pymaceuticals/figures/percent_tumor_change.png)

## Observable Trends

Of the three treatments and control condition(Placebo), it is clear that Capomulin is the superior treatment.  It was the only treatment to demonstrate a decrease in tumor volume, with a 19.5% reduction in tumor size. Capomulin also had the smallest increase in metastatic sites, going from 0 to an average of 1 site over 45 days.  It also had the highest survival rate, with 84% of mice still alive at the end of the trial.  Mice on the other two treatments and the placebo fared equally worse than those on Capomulin.  The only exception is that mice on Infubinol seemed to have less metastatic spread than Ketapril or Placebo.  However, if you look at survival rates, Infubinol(9%) has a lower rate than Ketapril or Placebo (11%). Therefore, of the treatments, Capomulin seems the most promising.
