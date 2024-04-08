<!-- WELCOME  -->
## Welcome!

Welcome to the homepage for the University of Manchester's workshop: '_Introduction to Data Analysis in R and RStudio for Maternal and Fetal Health Research_'

This GitHub page contains all the documents you will need for the workshop. We will email all files to you directly, but this GitHub will serve as a one-stop-shop for future reference.

This workshop will take place on **Tuesday 9th April** at **St Mary's Hospital, 5th Floor Seminar Rooms A&B**, from **12:30 until 15:30**. To register for the workshop, please use the following [link](https://forms.office.com/e/gXJPqim4gh).

The workshop is intended to be hands-on and will cover all steps of a data analysis lifecycle in R, including importing, preparation, visualisation and analysis of healthcare data. A laptop will be required for you to take part. Please feel free to bring your lunch.



<!-- AIMS  -->
## Aims and objectives

The aim of this workshop is to give a foundational understanding of the statistics needed to conduct maternal and fetal health research, and how to programme these using R. It is aimed at those who have no prior programming experience or knowledge or R, and only limited knowledge of basic statistics.

Learning objectives include:
1. To understand how the R programming language works (understanding the ‘syntax’)
2. To be able to confidently work through a data analysis lifecycle using R: Preparing, summarising, visualising and analysing data
3. Running and interpreting basic hypothesis tests and regression-based models

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- IMPORTANT INFO  -->
## Important information

For the workshop, you will need:
* To have completed the pre-requisite activity, which includes downloading the data and installing the necessary software (see [here](https://github.com/UoM-R-Workshop/Pre_requisite)). This should take no longer than **1 hour**.
* A laptop (with sufficient charge)

If you have any questions about the workshop, or can no longer attend, please contact harriet.cant@manchester.ac.uk or victoria.palin@manchester.ac.uk

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- About R and RStudio -->
## About R and RStudio

R is a statistical computing software and a programming language commonly used for analysing data. It’s free to use and is open-source, meaning a large community of users can contribute to its maintenance. This has resulted in a software which is well equipped for analysing data, and a popularity within the academic community. RStudio is a separate software that works together with R. RStudio is what’s known as an 'Integrated Development Environment', which is basically a front-end application that makes R more user-friendly. You need to have R installed in order for RStudio to work, but you’ll likely only directly work with the RStudio application.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- COURSE MATERIAL  -->
## Course material and files

This course will consist of several modules. These include:
1. Loading and cleaning data
2. Summarising data
3. Visualising data
4. Hypothesis testing
5. Modelling

We will run the workshop in two halves, with a break between. Each part has two code files: one which contains all the code we will go through together, and another which contains the solutions to the activities.

All course files are contained on this GitHub page. They can be found in the following repositories:
* [Data](https://github.com/UoM-R-Workshop/Data)
  * [Data description](https://github.com/UoM-R-Workshop/Data/blob/main/Data%20description.pdf)
* [Pre-requisite activity](https://github.com/UoM-R-Workshop/Pre_requisite)
* Code files
  *[Course content: PART 1](https://github.com/UoM-R-Workshop/Code/blob/main/PART1_CourseContent.R)
  *[Course content: PART 2](https://github.com/UoM-R-Workshop/Code/blob/main/PART2_CourseContent.R)
  *[Activity solutions: PART 1](https://github.com/UoM-R-Workshop/Code/blob/main/PART1_Activities.R)
  *[Activity solutions: PART 2](https://github.com/UoM-R-Workshop/Code/blob/main/PART2_Activities.R)
* [Slides](https://github.com/UoM-R-Workshop/Slides/blob/main/WorkshopSlides.pdf)

The remaining course content will be uploaded in due course

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- DATA  -->
## Data 

We will be using data collected from an online study of 410 mother-infant pairs. This data was collected as part of a 2022 study by Sandoz et al., who aimed to better understand the link between maternal mental health and infant sleep:

> Sandoz V, Lacroix A, Stuijfzand S, Bickle Graz M, Horsch A. Maternal Mental Health Symptom Profiles and Infant Sleep: A Cross-Sectional Survey. Diagnostics. 2022; 12(7):1625.

The study can be read here: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9319039/ 

The data can be downloaded from the following page (here)[https://github.com/UoM-R-Workshop/Data/blob/main/data_input.csv]. To download the file, please visit the link and either (1) press the three dots at the top of the screen and click ‘Download’, or (2) press the save icon, or (3) Ctrl + shift + S.

The original file is available on Zenodo: https://zenodo.org/records/5070945#.Y8Oq4NJBwUE  (Dataset_maternal_mental_health_infant_sleep.csv). However, we recommend not using this file as there are some minor formatting errors, as well as variables which are not of interest for this workshop.

A description of the data can be found [here](https://github.com/UoM-R-Workshop/Data/blob/main/Data%20description.pdf).

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This course has been developed by Harriet Cant and Dr Vicki Palin. We would like to acknowledge Dr Hannah Lennon, whose teaching materials provided the basis of this workshop, and Chantelle Cornett, for her feedback on the course content and assistance in delivering the workshop on the day.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
