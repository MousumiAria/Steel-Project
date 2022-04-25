<h2> <align="center">Machine learning project using steel processing data from ArcelorMittal</h1>
<p align="center"><img src="https://corporate-media.arcelormittal.com/cache/8/e/e/3/7/e/8ee37ed098f6e8fac8b901eb6c64aa54b4ad4e21.jpg" width="500" height="400"></p>


## Team name: STEELEARNING: 
<a href="https://github.com/Len-Fid">Lena-Fidrmuc, 
<a href="https://github.com/Moshood Owolabi">Moshood Owolabi,
<a href="https://https://github.com/MousumiAria"> Mousumi Sen</a>

## Host organization:
* <a href="https://github.com/becodeorg"><strong>BeCode</strong></a>(Ghent campus)
<img src="https://becode.org/app/uploads/2021/06/logo-becode.png" alt="Logo" width="200" height="200">
  
## Client organization:
* <a href="https://www.linkedin.com/company/arcelormittal-belgium/?originalSubdomain=be"><strong>ArcelorMittal</strong></a>
<img src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Arcelormittal-logo.svg" alt="Logo" width="200" height="200">


## The timeline of the project:
11 days - **11/04/2022 - 22/04/2022**

## Project Goal: 
*Predicting width constrictions during hot rolling using machine learning methods*

* Dealing with big data from given from the industry
* Analysing, cleaning and pre-processing all data files
* Visualizing data
* Modelling data using Supervised Machine Learning techniques
* Predicting width constriction

## Dataset details:
* Main_CoilFile.csv with attributs:
    (coil,	furnace Number,	analyse,	Hardness_1,	Hardness_2,	Width,	Temperature before finishing mill,	Temperature after finishing mill,	Thickness,	Thickness profile,	c,	mn,	si,	nb,	p,	s,	al,	ma,	b,	n,	ti,	cr,	va,	mo)

* More the 57,000 CSV files of each Coil-file and its measurements (length and width)

## Description:
ArcelorMittal is a project where we predicted width constrictions by given data from our Client.

The steps we have taken:
* Pre-processed and analysed all raw data.
* Visualised, recognised  and calculated the constriction for the each coil 
* Labeled all the coils that have the width constriction within (4-5mm) and merged it in Main_CoilFile.
* Constriction values is our dependant variable/target for the various machine learning models 
  
## Usage 
- We are using jupyter notebooks:
  * File cleaning
  * Functions for calculating the constriction
  * Random forest model 
  * Model comparison 

## Used Language and Libraries:
Python libraries:
* Numpy
* Pandas 
* Scikit-learn
* Matplotlib
* Glob
