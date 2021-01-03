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

1.	The GITHUB repository contains:

    •	A ‘gitignore’ file containing any files or file types which should be ignored by the github repository  
    
    •	Austin-Dataset.csv - Study of 27,000 dogs in Austin, Texas

    •	Dogs-Trust.csv - Study of 2,806 dogs by Dogs Trust in the UK

    •	A python program file called ‘FinalProject.ipynb’ which contains:

          •	The simulated data set
          •	Online and other research into the data set variables
          •	Investigations into the relationship between data set variables   
    
    •	A ‘LICENSE’ file containing a copy of the MIT Licence

    •	A ‘README.md’ file which contains:

          •	Introduction to the dataset and its related assumptions
          •	How to run the python code
          •	References used in completing the project


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
	•	Use 'Restart and Run All' in the 'Kernel' tab in Jupyter Notebook re-run the entire code
	•	Hold 'Shift' + 'Enter' to run/test code in individual code cells in a Jupyter Notebook

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

Brian McGinley and Ian McLoughlin for all the helpful tips in completing this assignment



**References**

Irish Study: https://www.thejournal.ie/dogs-abandoned-5194543-Sep2020/

UK Study: https://veterinaryrecord.bmj.com/content/161/9/283.2

UK Dogs Trust study:https://www.tandfonline.com/doi/full/10.1080/10888700903369255

UK Study: https://www.tandfonline.com/doi/abs/10.1080/10888700903369255?journalCode=haaw20

US Study: https://www.aspca.org/animal-homelessness/shelter-intake-and-surrender/pet-statistics

US Study: https://www.petfinder.com/pet-adoption/dog-adoption/pets-relinquished-shelters/

US Study: https://pubmed.ncbi.nlm.nih.gov/32575574/#&gid=article-figures&pid=figure-2-uid-1

US Study: https://news.orvis.com/dogs/when-is-it-time-to-surrender-your-dog

US Study: https://faunalytics.org/understanding-the-factors-that-lead-to-successful-dog-adoptions/

US Study: https://pubmed.ncbi.nlm.nih.gov/29557174/

US Study: https://apnews.com/article/218042cf3f684525874f48ae990ed49b

US Study: https://www.hillspet.com/dog-care/new-pet-parent/common-reasons-adopted-dogs-are-returned-to-shelters

US Study: https://www.companionanimalpsychology.com/2013/03/what-influences-dogs-length-of-stay-at.html

US Re-homing stats:https://data.world/rdowns26/austin-animal-shelter/workspace/file?filename=Project+Report.pdf

US Older dog study:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5867524/

US Study: https://data.world/rdowns26/austin-animal-shelter/workspace/file?filename=Austin_Animal_Center_Intakes.csv

https://thispointer.com/pandas-skip-rows-while-reading-csv-file-to-a-dataframe-using-read_csv-in-python/

https://stackoverflow.com/questions/32249960/in-python-pandas-start-row-index-from-1-instead-of-zero-without-creating-additi

https://www.geeksforgeeks.org/python-pandas-dataframe-drop_duplicates/

https://stackoverflow.com/questions/23377108/pandas-percentage-of-total-with-groupby

https://stackoverflow.com/questions/30009948/how-to-reorder-indexed-rows-based-on-a-list-in-pandas-data-frame/3001000

https://stackoverflow.com/questions/39482722/how-to-print-dataframe-on-single-line