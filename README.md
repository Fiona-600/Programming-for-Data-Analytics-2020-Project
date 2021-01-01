**Programming for Data Analysis 2020 Submission**

**GMIT Higher Diploma in Data Analytics**

**Submitted by Fiona Lee - 3 December 2021**

**Introduction**

This project creates and models a simulated data set related to the factors underlying the length of stay of dogs in animal shelters using the numpy.random package in Python. 

![alt text](https://i1.wp.com/puppytoob.com/wp-content/uploads/2017/07/Pet-Shelters.jpg?w=600&ssl=1)

*Source: https://i1.wp.com/puppytoob.com/wp-content/uploads/2017/07/Pet-Shelters.jpg?w=600&ssl=1*

**Qualities and attributes of the dataset**

The dataset contains 200 samples (rows), and 7 variables (columns) namely: Duration (Days), Age_Mths, Age_Yrs, Gender, Pedigree, Size and Risk. 

For each sample, the following features/variables were simulted i.e. 

  -	Duration (Days): Number of days a dog stays in the shelter from entry to adoption, foster or euthenasia  
  -	Age_Mths: Age in months rounded to nearest month
  -	Age_Yrs: Age in years rounded to nearest year
  -	Gender: Sex of the animal (male or female)
  -	Pedigree: Pedigree of the animal (purebred or crossbreed)
  - Size: Size of the animal (small, medium or large) 
  - Risk: The risk of long stay/euthenasia (low, medium, high and v-high)

**Simulated Animal Shelter Dataset**

The simulated ‘Animal Shelter Dataset’ is contained in the Final Project.ipynb file.

*Repository Link: https://github.com/Fiona-600/Programming-for-Data-Analytics-2020-Project/blob/main/Final%20Project.ipynb*


**Dataset Assumptions**

A summary of the assumptions behind the dataset simulation are detailed below:

**Age**

The age profile of dogs are split as follows: 

Puppy (<1 years) 36%; Adult (1-3 years) 29%; Adult (4-6 years) 19% Senior (7+) 16%

<6 mths 14%; 6-12 mths 22%; 1 year 12%; 2 years 11%; 3 years 6%; 4 years 8%; 5 years 7%; 6 years 4%; 7-9 years+ 13%; 10 yrs+ 3% (Extrapolated from US Study)

**Gender**

The split of male to female dogs was 57% male and 43% female.

**Pedigree**

The split of purebred to crossbred dogs was 21% purebred and 79% crossbred.

**Size**

The split of sizes were 22% small (<10kg); 60% medium (10-30kg) and 18% large (>30kg).

**Length of Stay (Duration (Days))**

Duration (Days) was simulated based on the 'Risk' variable. 

The average adoption time - 29 days

**Risk**

Risk was estimated for each sample based on the results of age, gender, pedigree and size.


**The Mean, Median, Standard Deviation, Min and Max Values for each variable are contained in the Final Project.ipynb file**

*Repository Link: https://github.com/Fiona-600/Programming-for-Data-Analytics-2020-Project/blob/main/Final%20Project.ipynb*



**Purpose of the project**

This project creates and models a simulated data set related to a chosen real-world phenomenon using the numpy.random package in python. This approach is taken rather than collecting the data.

The elements explored will be:

1.	Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four   different variables.
2.	Investigate the types of variables involved, their likely distributions, and their relationships with each other.
3.	Synthesise/simulate a data set as closely matching their properties as possible.
4.	Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell   within the notebook.

**Structure & Project Navigation**

The project will be stored in a GITHUB Repository at url: https://github.com/Fiona-600/Programming-for-Data-Analytics-2020-Project

1.	The GITHUB repository will contain:

    •	A ‘LICENSE’ file containing a copy of the MIT Licence

    •	A ‘gitignore’ file containing any files or file types which should be ignored by the github repository  

    •	A ‘README.md’ file which contains:

          •	Introduction to the dataset and its related assumptions
          •	How to run the python code
          •	References used in completing the project

    •	A python program file called ‘FinalProject.ipynb’ which will:

          •	The data set itself
          •	Online and other research into the data set variables
          •	Investigations into the relationship between data set variables

    

**Technology Used**

**Required Programs**

	•	Anaconda Navigator 3 - https://www.anaconda.com/
	•	Jupyter Notebook - https://jupyter.org/install  
	•	Python version 3.8.3 - downloaded via Anaconda Navigator 3 to Windows 10 OS
  •	Cmder Console Emulator - https://cmder.net/
	•	GitHub Repository Storage - https://github.com/
 	•	Firefox Internet Explorer - https://www.mozilla.org/en-US/firefox/new/


**Opening and running the code in the Jupyter Notebook**

  •	Clone or download the 'FinalProject.ipynb' file from Github onto your local drive
  •	Open the Jupyter Notebook file in your browser using CMDER
  •	Use Restart and run all re-run the entire code in the notebook
  •	Hold 'Shift' + 'Enter' to run/test code in individual code cells in a Jupyter Notebook with a .ipynb extension
  •	Check output against expected output

**Libraries and Modules**

    •	NumPy - ‘import numpy as np’

    •	Pandas – ‘import pandas as pd’
        
    •	Matplotlib - ‘import matplotlib.pyplot as plt’

    •	Seaborn - ‘import seaborn as sns’



**Author & Contributors**

Fiona Lee



**License**

This project is licensed under the MIT License - see the LICENSE.md file for details



**Acknowledgments**

Brian McGinley and Ian McLoughlin for all the helpful tips in completing these assignments



**References**

