# Ebola-outbreak
Data Visualisation of Ebola Outbreak

•	Dataset:Ebola dataset is downloaded from ebola.data.org

1.It’s a monthly statistics uploaded by WHO starting from june to december in the year 2015.
 
•	Technolgies used:

1.R programming language is used to visualize the data set . Following packages are used for the same googleVis , shiny.

Steps to run  visualization in your local

1.	Install R

2.	Place all the files in the folder(UI.r,server.r,all the data files in your folder)

3.	Set the work dir to folder where all the above files are placed

Setwd(“path”)

4.	Open console and run the following lines to import the packages

Install.packages(“googleVis”) 

Install.packages(“shiny”)

require(shiny)

require(googleVis)

runApp()

