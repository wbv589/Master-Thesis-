# Master-Thesis 

Overleaf document: https://www.overleaf.com/project/62fc9604f7d78fc59aa156d3

This repository provides code for the master thesis: "Children, Wages and Sickness Absence" by Natasha Drud Bendsen and Anna Herzberg

The code is found in the folder named "main" and is structured in the following way:


Chosen Variables List:        List of chosen variables from Statistics of Denmark

Programs:
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


Event_study1.do               Use the main sample to estimate the main 10 year event study
                              


