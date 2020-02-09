---
title: "Data607-MajorAssignment-Tidyverse"
author: "Vinayak Kamath"
date: "2/8/2020"
output: 
  html_document:
    df_print: paged
  pdf_document:
    extra_dependencies:
    - geometry
    - multicol
    - multirow
---

### An Example using TidyVerse packages - **ggplot2** and **dplyr**  and using tesla-stock-data-from-2010-to-2020 Data set from Kaggle  [*https://www.kaggle.com/timoboz/tesla-stock-data-from-2010-to-2020*]: ##  

*Pls load ggplot2 and dplyr package using install.packages("ggplot2") and install.packages("dplyr")*  

#### Package Selected : **ggplot2**  and **dplyr**

***Capability 1:  ggplot2 geom_line to show the stock price movement over the years for Tesla shares:*** 
  
***Capability 2: dplyr filter to show the days when the stock price for Tesla moved by over 15% (profit or loss) in one day ***  
  
***Capability 3: dplyr group by and summarise to show the yearly minimum and maximum stock price close and arranging it in descending order of movement in a year*** 
