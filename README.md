# poly-drd-effects-est-CIs
Script to:  
1 Import 'untruncated' estimated lambdas  
2 Calculate CIs using Daidoji & Iwasaki’s (2012) method (Wald-type)  
3 Calculate CIs using Sangnawakij’s (2021) method (novel)  
4 Generate interaction plots to illustrate both CI methods and export a csv of the data  

File key:  
yrage.df.csv = number of observations for each cell in a year x age group table  
yrage.eff.csv = table of untransformed effects from the model.  The R script fixes the column names and retains year(x), age group(group), and lambda(predicted)  
yrage_eff_inc_cis = table of transformed effects generated by the script.  Provides year, age, num observations, lamda hat, ci_low and ci_high from both methods, and the differences between the calculated CIs (method 1 - method 2)  
interaction_plots.docx = TL;DR output showing effects + CIs for both methods
