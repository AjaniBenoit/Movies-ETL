# Movies ETL

## Overview of Project 

The ETL process was used to extract and transform movie data from Wikipedia data and Kaggle data and load it into a database in preparation for the Amazing Prime Hackathon.  

## Results. 

### Extracting 

#### Wikipedia Movies JSON file 

Data frame contains 193 columns

![fig1.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig1.png)

#### KAGGLE Movies 

Data frame contains 25 columns 

![fig2.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig2.png)

#### KAGGLE Rating 

Data frame contains 26,024,289 rows and 4 columns 

![fig3.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig3.png)

### Transforming 

#### Wikipedia Movie JSON file 

Data fram cleaned and transformed. Data frame now contains 22 columsns 

![fig4.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig4.png)

![fig5.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig5%20.png)

#### Merged Data Frame 

Merged Wikipedia, KAGGLE Movies and KAGGLE Rating data frame. New data frame contains 31 columns 

![fig7.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig7.png)

### Loading 

#### Exporting to Database 

![fig8.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/fig8.png)

#### Verifying Tables Created in pgAdmin

##### Movie table 

Table contains 6,052 rows.

![Fig9.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/Fig9.png)

###### Rating table 

Table contains 2,048,578 rows. Rating table should contain 26,024,289 rows. The table was not correctly created. 

![Fig10.png](https://github.com/AjaniBenoit/Movies-ETL/blob/main/Fig10.png)
