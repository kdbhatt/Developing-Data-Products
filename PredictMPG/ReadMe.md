---
title: "ReadMe"
author: "Krishan Bhatt"
date: "September 06, 2016"
output: html_document
---
# Shiny app Predict Mileage Per Gallon

For a direct access to this Shiny application, click [here](https://kbhatt.shinyapps.io/PredictMPG/)

This README file is the supporting documentation accompagning this Shiny application. It includes three parts: 

1. Instructions given for this project
2. Description of this Shiny application
3. Directives on how to visualize this Shiny application

### 1. Instructions given for this project

1. Write a shiny application with associated supporting documentation. The documentation should be thought of as whatever a user will need to get started using your application. 
2. Deploy the application on Rstudio's shiny server.
3. Share the application link by pasting it into the text box below. 
4. Share your server.R and ui.R code on github. 

The application must include the following:

1. Some form of input (widget: textbox, radio button, checkbox, ...).
2. Some operation on the ui input in sever.R.
3. Some reactive output displayed as a result of server calculations.
4. You must also include enough documentation so that a novice user could use your application.
5. The documentation should be at the Shiny website itself. Do not post to an external link.

The Shiny application in question is entirely up to you. However, if you're having trouble coming up with ideas, you could start from the simple prediction algorithm done in class and build a new algorithm on one of the R datasets packages. Please make the package simple for the end user, so that they don't need a lot of your prerequisite knowledge to evaluate your application. You should emphasize a simple project given the short time frame.  

### 2. Description of this Shiny application

This Shiny application "PredictMPG"" get user input values for Hourse power, number of cylenders and weight. Then it simulates among Mile Per Galen VS Hourse Power, number of cylender and weight. 


This Shiny application displays a series of graphs illustrating various comparision between MPG, Number of cylender, Hourse Power and Weight based on the input provided by the user.


### 3. Directives on how to visualize this Shiny application

Option 1: Direct link: click [here](https://kbhatt.shinyapps.io/PredictMPG/)

Option 2: Download the `server.R` and `ui.R` files from [here](https://github.com/kdbhatt/Developing-Data-Products/tree/master/PredictMPG) and place them in a directory named 'PredictMPG'. Open an R session and set the working directory to the folder that contains the directory 'PredictMPG'. Then run the following commands:

use setwd to make the current folder as a working folder.

```
setwd("C:/Krishna/MyProject/DataScience/9_Developing_Data_Products/Developing-Data-Products")
library(shiny)
runApp('PredictMPG')
```

