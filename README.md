# Ebola-outbreak
Data Visualisation of Ebola Outbreak
•	Dataset:
Ebola dataset is downloaded from ebola.data.org
1.	It’s a monthly statistics updated every month by WHO in the year 2015 from june- december. We got different sheets of data for every month.
 
•	Technolgies used:
1.	We used R programming language to visualize 1st data set . Following packages are used for the same
googleVis , shiny.

Steps to run  visualization in your local
1.	Install R
2.	Place all the files in the folder(UI.r,server.r,all the data files in your folder)
3.	Set the work dir to folder where all the above files are placed
4.	Open console and run the following lines to import the packages

#This will install the required packages in your local
Setwd(“path”)# example path will be some thing like c:/bigdataproj)
Install.packages(“googleVis”) 
Install.packages(“shiny”)
require(shiny)
require(googleVis)
runApp()

