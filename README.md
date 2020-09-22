# TRAILS: genes & parents in substance use

Scripts accompanying the paper "Interplay between genetic risk and the parent environment in adolescence and substance use in young adulthood: a TRAILS study".

Analyses were conducted in MPLUS, data are available upon request from https://www.trails.nl/en/hoofdmenu/data/data-use

The script names for the exploratory factor analysis (EFA) follow the format efa_construct$ with construct being the latent variable that is modeled (either a predictor or outcome construct) and $ representing the modeling step. The script names for the structural equation models (SEM) follow the format outcome_parentingfactor_model step. Outcomes included a latent factor for smoking (fsmk), alcohol per week (alc), and cannabis initiation (can). Parenting factors included F1 parental involvement (f1inv), F2 parental substance use (f2sub), and F3 the parent-child relationship (f3rel). The modeling steps were ‘1main’ for the main effects of the PGS and the parenting factor, ‘2interactioneffects’ for the GxE between the PGS and the parenting factor, ‘3rgeeffects’ for the rGE effects, and ‘4full’ for the complete model including main, GxE, and rGE effects. 

The following abbreviations are used in the scripts to represent the variables: 

C1-C10 = Principal components for genetic ancestry

parknow = Parental knowledge

pardisc = Child disclosure

parcont = Parental control 

parsol = Parental solicitation

rel_rej = Parent-child relationship rejection

rel_warm = Parent-child relationship warmth

parsmk = Parental smoking

parcpd = Parental cigarettes per day 

paralc =	Parental alcohol use per week

paraddep = Parental addiction

parcan = Parental cannabis use

prssmcpd =	Smoking PGS (based on smoking initiation and cigarettes per day)

prsalc = Alcohol use PGS

prscan = Cannabis initiation PGS

eversmk =	Ever smoking

dailysmk =	Daily smoking

cpd = Cigarettes per day

ftnd	=	Nicotine dependence

alc =	Alcohol use per week

alcmonth =	Any alcohol use in past month (yes/ no)

audit = Alcohol Use Disorder Identification Test total score

can = Cannabis initiation

cupit1 =	Cannabis Use Disorder Identification Test subscale 1 (impaired control) score

cupit2 =	Cannabis Use Disorder Identification Test subscale 2 (cannabis problems) score
