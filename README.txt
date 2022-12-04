# Master-Thesis 

Overleaf document: https://www.overleaf.com/project/62fc9604f7d78fc59aa156d3

This repository provides code for the master thesis: "Children, Wages and Sickness Absence" by Natasha Drud Bendsen and Anna Herzberg

The code is found in the folder named "main" and is structured in the following way:


VARIABLES:
Chosen Variables List:        List of chosen variables from Statistics of Denmark


PROGRAMS DATA GENERATION:
0a data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Children00, Children11, Children22
                              
0b data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Parents00, Parents00aa, Parents11, Parents22, Adults00, 
                              Adults11, Adults22, Adults33
              
                              Saving final file as;
                              Adults.csv
                              
0c data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Sickness00
                              
                              Saving final file as;
                              Sickness.csv                          

0d data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Employees00
                                
                              Saving final file as;
                              Employees.csv                        

0e data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Robustness
                                
                              Saving final file as;
                              Robustness.csv 

0f data generation.sas        Process the raw data and saves the main sample in dataset; 
                              Grandparents00
                                
                              Saving final file as;
                              Grandparents.csv 


PROGRAMS CLEANING DATA:
1a earnings cleaning.do       Cleaning earnings (adults) data set;

                              Saving final file as;
                              1a earnings.dta   


1b sickness cleaning.do       Cleaning sickness absence data set;

                              Saving final file as;
                              1b sickness.dta      


1c employees cleaning.do      Cleaning epmloyees data set;

                              Saving final file as;
                              1c employees.dta  

MERGING DATA:  
1d merge data.do              Merging earnings and sickness data;
                              1d sickness earnings merged.dta
                          
                              Merging sickness earnings employees data and saving final file as;
                              1d sickness earnings employees merged.dta                   

1e the populationg.do         Restrictions and choiches regarding the population;

                              Saving final file as;
                              1e the population.dta 

EVENT STUDY:                              
2a event study.do             Use the main sample to estimate the main event study; 
                              2a event study baseline.dta
                          

OAXACA-BLINDER METHOD:      
3a Oaxaca-Blinder.do          Estimation;
                              3a Oaxaca-Blinder.dta

3b Oaxaca-Blinder.do          Extrapolation of gaps
                              3b Oaxaca-Blinder gaps basic.dta

3c Oaxaca-Blinder.do          Decomposition graphs.         



HETROGENOUS EFFECT ANALYSIS:
4a grandparents cleaning.do   Cleaning grandparents data set;
                              4a grandparetns.dta

4b merge grandparents.do      Merging earnings, sickness, employees and grandparetns data; 
                              4b sickness earnings employees grandparetns merged.dta                 

4c event study.do             Heterogenous event study; 
                              4c event study heterogenous effects.dta
                              
4d event study category.do    The heterogenous event-study divided into category; 
                              4d event study heterogenous effects category.dta
     
     
     
