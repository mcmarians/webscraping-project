# Scraping Immobiliare.it site and Hash Functions
The project consists in two parts: scaping a website and cluster its informations in different ways and use hash functions to find duplicates in a big set of passwords. 

![](immobiliare.jpg)

#### Scaping a web site

The scraping part of the project was based on this [link](https://www.immobiliare.it/vendita-case/roma/?criterio=rilevanza&pag=1) in the Immobiliare.it site.

This data will be the corpus for our analysis.

## Script descriptions

1. __`FinalProject.ipynb`__: 
	> This script provides the code of our analisys. It is possible that some plots are not clearly viewed, so to visualize them correctly the notebook is also shown [here](https://nbviewer.org/github/mcmarians/webscraping-project/blob/main/FinalProject.ipynb).
	
2. __`data.csv`__: 
	> This file contains all the informations of the annoucements taken from Immobiliare.it.
	
3. Files containing all the functions of the different parts of the homework:
	1. __`first_part_functions.py`__: 
		> This file contains all the functions used during the part 1 of the HW.
	2. __`scraping.py`__: 
		> This file contains all the functions used for the scaping part.
	3. __`Hash_functions.py`__: 
		> This file contains all the functions used in the 2nd part of the HW.
	
4. __`KMeans.py`__ and __`KMeans_map_reduce.py`__: 
	> These files contain the Classes of the KMeans algorithm implemented with and without map-reduce.
  
