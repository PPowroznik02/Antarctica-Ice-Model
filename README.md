# Antarctica Ice Model
## Overview

This project includes a detailed report and an R script for creating a mathematical model to analyze changes in sea ice range on Antarctica between 1978 and 2009. Additionally, it features an animation that illustrates the modeled ice range in comparison with actual observational data.

## Project Components

### Mathematical Model:
- The project involves constructing a mathematical model to represent the variations in sea ice range over the specified period.
- The model is developed using statistical techniques and historical [data](/daily_ice_edge.csv) to provide accurate predictions and insights.
- Using the Spectrum function, the changes period was determined.
Then a function formula was determined, which best reflects the change in ice in time.
```math
f(t) = \sin \left( \frac{2\pi}{T}t \right) + \cos \left( \frac{2\pi}{T}t \right)
```

### R Script:
- An R script is provided to create and visualize the mathematical model.
- The script includes data processing, model fitting, and visualization steps to ensure a comprehensive analysis.
- Key functions and libraries used in the script include plotly for plotting, lm for linear modeling and fmsb.

### Report:
- The report documents the methodology, model development, and results.
- It includes detailed explanations of the modeling approach, assumptions made, and interpretation of the findings.

### Animation:
- An animation is created to compare the modeled ice range with the actual data.
- This visual representation helps in understanding the accuracy and trends of the model.
![Animation](wizualizacja_modelu_zasiegu_lodu.gif)
