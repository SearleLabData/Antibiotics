Description of data files for the manuscript “Antimicrobial agents can alter life history, density, and species interactions of aquatic crustaceans” by Kacie L. Jonasen, David D. Prather, Brittany N. Heil, Abigail M. Merrick, and Catherine L. Searle



For the “Population_experiment.csv”

week = sampling week

rep = an unique identifier for each replicate

treat.ID = an indicator of the combined antibiotic + pathogen treatment. A = tetracycline present, no pathogen, B = tetracycline present, pathogen present, M = no tetracycline, pathogen present, N = no tetracycline, no pathogen (control) 

anti.treat = an indicator of the antibiotic treatment where “tetra” = tetracycline present and “none” = clean water

para.treat = an indicator of the pathogen treatment with “exposed” = pathogen exposed and “unexposed” = no pathogen present 

*ad.fem = uninfected adult female

*juv.fem = uninfected juvenile female

*ad.male = uninfected adult male

*juv.male = uninfected juvenile male

*eph.fem = uninfected adult female carrying an ephippia

*ad.fem.inf = infected adult female

*juv.fem.inf = infected juvenile female

*ad.male.inf = infected adult male

*juv.male.inf = infected juvenile male

*eph.fem.inf = infected adult female carrying an ephippia

tot.num = the total number of individuals found in the subsample

num.inf = the number of infected individuals found in the subsample

prop.inf = the proportion of individuals infected in the subsample

*Values in columns with an asterisk are the number of individuals in each category found in the 200mL subsample of the population on a given sampling day. 


For the “Life_history_experiment.csv”

Treat = indicator of the treatment where “Control’ = clean water, “LowT” = low tetracycline, “MedT” = medium tetracycline, “HiT” = high tetracycline, “LowS” = low sulfadimethoxine, “MedS” = medium sulfadimethoxine, and “HiS” = high sulfadimethoxine

Rep = replicate indicator within each treatment

Columns 3-17 = the date of data collection

first_baby_date = the calendar date when we first observed an offspring for an individual

first_baby_day = the day of the experiment when we first observed an offspring for an individual

death_date = the calendar date when we first observed the animal was dead

death_day = the day of the experiment when we first observed the animal was dead

censored = an indicator if the animal died during the experiment (1) or survived the whole experiment (0) 


For “Feeding_trial_experiment.csv”

treat = an indicator of the treatment where “control” = clean water, “tetra” = tetracycline, and “sulfa” = sulfadimethoxine

rep = an indicator of the replicate within each treatment

begin.cell = the number of algal cells at the beginning of the experiment

rfu = raw fluorescence units, measured at the end of the experiment with a fluorometer

length = body length of the individual

cells.left = the estimated number of cells left in each replicate at the end of the experiment, based on the standard curves 

cels.eaten = the estimated number of cells eaten by each individual
