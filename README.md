<img width="1712" alt="Screen Shot 2021-05-03 at 2 00 22 PM" src="https://user-images.githubusercontent.com/80833988/116933790-e40a3980-ac18-11eb-83b2-513db6638647.png">


# Challenge 6
## Data visualization: creating interactive visualizations PyViz  and Mapbox API

> "For this assignment, I will create a Jupyter notebook that contains analysis of the housing rental market data for San Francisco 2010-2016. The analysis will be complete with professionally styled and formatted interactive visualizations.
"


!!! Important - go to HOW TO USE to make sure you can run Jupyter Lab file correctly



- [Introduction](#Introduction)
- [Why?](#why)
- [How to Install](#how-to-install)
- [How to use](#how-to-use)
- Technologies used
    - [Libraries](#Libraries)
    - [Interfaces](#Interfaces)



## Introduction

In this Challenge I created a Jupyter notebook with analysis of the housing rental market data for San Francisco. First, I gather data from CSV files for 2010-2016 real estate market, use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart. Second, style and format the overlay line plot to ensure a professionally styled visualization for each neighborhood of San Francisco and use interactive visualizations and widgets to answer challenge questions. 

I will demonstrate the ability to make an API call to Mapbox to create an interactive map to visualize data and better analize different areas as more attractive real estate investment. 

<img width="1038" alt="Screen Shot 2021-05-03 at 2 42 37 PM" src="https://user-images.githubusercontent.com/80833988/116937276-db683200-ac1d-11eb-8294-a047e4d98e23.png">

You can find my analysis, including the answers to the questions from the Challenge instructions. For each line of code there is comments, titles for plot, necessary professionally styled visualizations are included. 


## Why?

Proptech, the application of technology to real-estate markets, is an innovative domain in the fintech industry. 
My challenge is to use data visualization superpowers, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market 2010-2016 that are viable investment opportunities.



## How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Challenge_6.git
```

now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ san_francisco_housing.ipynb ] file to see the analysis report.



## How to use

In order to succesfully run the file you have to generate your own Mapbox API key and save it to .env file. Those files are hidden so Hold down the Command, Shift and Period keys (for Mac) to be sure you have it in the same folder as Jupyter Lab notebook

```
 cmd + shift + [.]
```
To generate Mapbox API key go to https://www.mapbox.com/ . You have to create your own account and request a new key. 



<img width="834" alt="Screen Shot 2021-05-03 at 2 30 18 PM" src="https://user-images.githubusercontent.com/80833988/116936209-5892a780-ac1c-11eb-906d-405f8dc2c3b1.png">



Save it in .env file, make sure to name the variable MAPBOX_API_ACCESS_TOKEN




<img width="709" alt="Screen Shot 2021-05-03 at 2 35 11 PM" src="https://user-images.githubusercontent.com/80833988/116936588-eb334680-ac1c-11eb-9da3-1a1972490693.png">

```

MAPBOX_API_ACCESS_TOKEN = '<your key>'


```

Those steps are nessesary to maintain a security of your information. 


## Technologies used

### Libraries


We are using Pandas- a software library written for the Python programming language for data manipulation and analysis.
The following libriries has to be imported:

```
import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv
```

In particular, Pandas offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

> " Written in: Python, Cython, C .  
Original author(s): Wes McKinney. . 
License: New BSD License
"




### Interfaces

* Jupyter Lab
* GitHub
* Mapbox - Maps and location for developers ( https://www.mapbox.com/ )



## Helps recruiters

* The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales, Siege.
* Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.
* AskBCS Learning Assistant channel was used to troubleshoot some of the accuring problems outside of the classroom

---

Feel free to contact me via channels

* Email:(nataliaburrey@gmail.com) 
* LinkedIn: (https://www.linkedin.com/in/natalia-burrey-181822175/)



---

* License

MIT
