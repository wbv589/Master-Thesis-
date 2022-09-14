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
                              sickness earnings merged.dta
                          
                              Merging sickness earnings employees data and saving final file as;
                              sickness earnings employees merged.dta                   
                              
EVENT STUDY:                              
2a event study.do             Use the main sample to estimate the main 10 year event study                              
                              
                              


