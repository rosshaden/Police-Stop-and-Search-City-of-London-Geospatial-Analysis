![header](./images/header.png)

Source: BBC 

# Metropolitan Police Stop and Search Analysis (June 2017 - July 2020)

#### Project Status: In progress

Stop and search is a divisive topic. Some view it as a necessary evil to help curb violent crime, while others see it as an inherently predatory and even racist practice. Seeking a deeper understanding of the topic, we acquired datasets spanning from mid 2017 to mid 2020, and began to answer the most consequential questions. While statistics in and of themselves cannot provide absolute answers for how we ought to administer a just society, a firm understanding of the data surrounding a subject is an essential prerequisite for reasoned discussion. This analysis aspires to aid that understanding.

The data was acquired from the official UK Police repository: https://data.police.uk/data

## Results 

### 1. How much more frequently are males searched compared to females?

<p align="center">
  <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/gender.png"  width='500'/>
</p>

<p align="center">
<img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/gender_ethnicity.png"  width='500'/> 
</p>

### 2. Which age group is searched most often?
  
  <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/age_range.png" width='500'/>
  </p>

  <p align="center">
    <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/age_range_ethnicity.png" width='500'>
  </p>


### 3. What is the ethnicity of citizens who are searched the most?

 <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/self_defined_ethnicity.png" width='500'/>
  </p>

### 4. What is the ethnicity of officers who search the most? 


 <p align="center">
    <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/officer_defined_ethnicity.png" width='500' />
  </p>
  
   <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/officer_defined_ethnicity_ethnicity.png" width='500' />
  </p>

### 5. Which piece of legislation do officers most commonly invoke to justify a search? 

 <p align="center">
    <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/legislation.png" width='500'/>
  </p>
  
   <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/legislation_ethnicity.png" width='500'/> 
  </p>

### 6. What do officers most commonly claim they are looking for to justify a search? 

 <p align="center">
    <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/object_of_search.png" width='500'/>
  </p>
  
   <p align="center">
    <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/object_of_search_ethnicity.png" width='500'/>
  </p> 

### 7. What is the most common outcome of a search?

 <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/outcome.png" width='500'/>
  </p>
  
   <p align="center">
   <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/outcome_ethnicity.png"width='500'/> 
  </p> 

### 8. At which part of the day are most searches perfomed? 

 <p align="center">
   
  <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/part_of_day.png" width='500'/>
  </p>
  
   <p align="center">
     <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/part_of_day_ethnicity.png" width='500'/> 
  </p> 

### 9. How does the number of searches vary by London borough? 

 <p align="center">
 <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/borough.png" width='500'/>
  </p>
  
   <p align="center">
       <img src="https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/figures/geospatial.png" width='600'/>  
  </p> 

## Getting Started
1. Clone and `cd` into this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/))
2. Execute `pip install -r requirements.txt`
4. [Install JupyterLab](https://jupyter.org/install)
5. Download the CSV files from https://data.police.uk/data/
6. Store the CSV files in a folder named `raw_data` in the root of the repo
7. Execute `jupyter lab`

## Deliverables
* [Analysis Notebook](https://github.com/rosshaden/Metropolitan-Police-Stop-and-Search-Analysis/blob/master/analysis.ipynb)
* Visualisation Dashboard (TBC)

## Awknowledgements
* [Police Data UK](https://data.police.uk/data/)

## Contact
* My email address is <b>hello@rosshaden.com</b>
* Feel free to contact me with any questions or if you are interested in contributing!
