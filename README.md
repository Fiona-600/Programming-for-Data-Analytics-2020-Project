**Programming for Data Analytis 2020 Submission**

**GMIT Higher Diploma in Data Analytics**

**Submitted by Fiona Lee - 3 December 2021**

**Introduction**

This project creates and models a simulated data set related to the factors underlying the length of stay of dogs in animal shelters using the numpy.random package in Python. 

![alt text](https://i1.wp.com/puppytoob.com/wp-content/uploads/2017/07/Pet-Shelters.jpg?w=600&ssl=1)

*Source: https://i1.wp.com/puppytoob.com/wp-content/uploads/2017/07/Pet-Shelters.jpg?w=600&ssl=1*


**Preliminary Findings & Interpretation of the Data Set**

**Qualities and attributes of the dataset**

The dataset contains 200 animals (rows), and 5 variables (columns) named; Duration (Days), Age_Yrs), Gender, Pedigree and Size, and species  

For each sample, five features/variables were measured i.e. 

  -	Duration (Days): Number of days a dog stays in the shelter from entry to adoption, foster or euthenasia
  -	Age_Yrs: Age in years rounded to nearest year
  -	Gender: Sex of the amimal (male or female)
  -	Pedigree: Pedigree of the amimal (purebred or crossbreed)
  - Size: Size of the amimal (small, medium or large) 

**Detailed Analysis - Initial Findings**

The detailed results of the initial analysis on ‘Animal Shelter Data Set’ are contained in the Final Project.ipynb file.

*Repository Link: https://github.com/Fiona-600/Programming-for-Data-Analytics-2020-Project/blob/main/Final%20Project.ipynb*

A summary of the initial analysis is detailed below:

Age:

The age profile of dogs in the dataset are broken down as follows: 

UK: Puppy (0-1 years) 36%; Adult (1-3 years) 29%; Adult (4-6 years) 19% Senior (7+) 16%

UK: <6 mths 14%; 6-12 mths 22%; 1 year 12%; 2 years 11%; 3 years 6%; 4 years 8%; 5 years 7%; 6 years 4%; 7-9 years+ 13%; 10 yrs+ 3% (Extrapolated from US Study)

Gender:
Research Assumptions:
UK: The split of male to female dogs based on 2,806 dogs in the 'Dogs Trust dataset' was 57% male and 43% female.

UK Dogs Trust study: https://www.tandfonline.com/doi/full/10.1080/10888700903369255
US: The split of male to female dogs based on 36,000 dogs in the 'Austin animal shelter dataset' was 54% male and 46% female.

US Study: https://data.world/rdowns26/austin-animal-shelter/workspace/file?filename=Austin_Animal_Center_Intakes.csv
Close to equal numbers of male and female dogs were surrendered.

US Study 2008-2011: https://www.companionanimalpsychology.com/2013/03/what-influences-dogs-length-of-stay-at.html
Pedigree:
Research Assumptions:
UK: The split of pedigree / crossbreed dogs based on 2,806 dogs in the 'Dogs Trust dataset' was 21% pedigree and 79% crossbreed dogs.

UK Dogs Trust study: https://www.tandfonline.com/doi/full/10.1080/10888700903369255
US: The split of pedigree / crossbreed dogs based on 36,000 dogs in the 'Austin animal shelter dataset' was 7% pedigree and 93% crossbreed dogs.

US Study: https://data.world/rdowns26/austin-animal-shelter/workspace/file?filename=Austin_Animal_Center_Intakes.csv
Size:
Research Assumptions:
UK: The split of pedigree / crossbreed dogs based on 2,806 dogs in the 'Dogs Trust dataset' was 22% small (<10kg), 60% medium (10-30kg) and 18% large (>30kg).

UK Dogs Trust study: https://www.tandfonline.com/doi/full/10.1080/10888700903369255
US: The split of pedigree / crossbreed dogs based on 36,000 dogs in the 'Austin animal shelter dataset' was 30% small (<10kg), 29% medium (10-30kg) and 40% large (>30kg).

US Study: https://data.world/rdowns26/austin-animal-shelter/workspace/file?filename=Austin_Animal_Center_Intakes.csv

XS dogs are adopted soonest, followed by the small dogs. XL dogs (e.g. St Bernards) were quite unique and likely were adopted out because of this. Length of stay increased with age and was highest for medium-sized dogs.

US Study: https://faunalytics.org/effects-of-phenotypic-characteristics-on-the-length-of-stay-of-dogs-at-two-no-kill-animal-shelters-2/

US Study 2008-2011: https://www.companionanimalpsychology.com/2013/03/what-influences-dogs-length-of-stay-at.html
Length of Stay (Duration (Days)):
Research Assumptions:
UK average adoption time - 29 days

UK: Puppies < 6 months - 20 days; 6-12 months - 28 days; Adult dogs (1-6 years) - 32 days; Seniors 7+ years - 72 days (Extrapolated split by age based on US Stats)

UK Study 2001-2004: https://www.researchgate.net/publication/244642863_Factors_affecting_time_to_adoption_of_dogs_re-homed_by_a_charity_in_the_UK

UK Study: https://veterinaryrecord.bmj.com/content/161/9/283.2
US average adoption time - 35 days

US Puppies < 6 months - 23 days; 6-12 months - 33 days; Adult dogs (1-6 years) - 42 days; Seniors 7+ years - 89 days

US Study 2008-2011: https://www.companionanimalpsychology.com/2013/03/what-influences-dogs-length-of-stay-at.html US Study (Senior Dogs): https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5867524/



*Table 5 - Mean, Median, Standard Deviation, Min and Max Values by Species*

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Fig%204%20Dataset%20Information%20by%20variable.PNG?raw=true)

**Conclusions**

  *Sepal Length:*

  ‘Iris_Setosa’ is the most consistent variety of Iris in terms of sepal length measurements in the sample.  The standard deviation of 0.35 is a calculation of the variation or spread of measurements recorded between the min value of 4.3 and max value of 5.8 across the sample versus the average measurement of 5.01.

   ‘Iris Virginica’ is the least consistent with a standard deviation of 0.64, mean of 6.59 and samples ranging from 4.9 to 7.9.

  *Sepal Width:*

   ‘Iris_Versicolor’ is the most consistent in terms of sepal width as it has the lowest standard deviation of 0.31 versus the average value of 2.77 and samples ranging from 2.0 to 3.4.

   ‘Iris Setosa’ is the least consistent with a standard deviation of 0.38, mean of 3.42 and samples ranging from 2.3 to 4.4.

  *Petal Length:*

  ‘Iris_Setosa’ is by far the most consistent in terms of petal length as it has the lowest standard deviation of 0.17 versus the average value of 1.46 and samples ranging from 1.0 to 1.9.

  ‘Iris Virginica’ is the least consistent with a standard deviation of 0.55, mean of 5.55 and samples ranging from 4.5 to 6.9.

  *Petal Width:*

  ‘Iris_Setosa’ is again by far the most consistent in terms of petal width as it has the lowest standard deviation of 0.11 versus the average value of 0.24 and samples ranging from 0.1 to 0.6.

  ‘Iris Virginica’ is the least consistent with a standard deviation of 0.27, mean of 2.03 and samples ranging from 1.4 to 2.5.

  Overall, ‘Iris Setosa is the most consistent across the sample measured and Iris Virginica’ was the least consistent.

**Purpose of the project**

To research the iris flower data set and to prepare a presentation to investigate the data set with a view to explaining it to your colleagues in a few weeks’ time.

The presentation will include:

1.	An explanation of what investigating a data set entails
2.	How python can be used to investigate the data set
3.	The required code for the analysis using python
4.	The resulting output of the code


**Structure & Project Navigation**

The project will be stored in a GITHUB Repository at url: https://github.com/Fiona-600/Project-2020.git

1.	The GITHUB repository will contain:

    •	Png files called ‘Fig 1 iris variants.png’ and ‘fig 3 iris petals and sepals.png’ which contains images of the variants of iris identified in the study i.e. Iris setosa, Iris    virginica and Iris versicolor and an indication of the location of the flower's petals and sepals.

    •	Png files called Fig 2 Iris Data Set - First 10 Results.PNG and Fig 4 Dataset Information by variable.png which are samples from the Iris_Dataset_Summary.txt file       

    •	A text file called ‘irisdataset.txt’ containing a download the data set
     
    •	A text file called ‘irisdataset.csv’ containing a download the data set

    •	A ‘LICENSE’ file containing a copy of the MIT Licence

    •	A ‘README.md’ file which contains:

          •	The data set itself
          •	Online and other research into the data set
          •	Investigations into the data set
          •	How to run the python code
          •	What that code does.
          •	All references used in completing the project

    •	A python program file called ‘analysis.py’ which will:

          1.  Output a summary of each variable to 'Iris_Dataset_Summary.txt
          2.  Save a histogram of each variable to png. ﬁles (Appendices 1-8)
          3.  Output a scatter plot of each pair of variables (Appendices 9-11)



**Investigation Approach using Python**

*Step 1 - Analyse the following aspects of the data set using Python program file ‘analysis.py’:*

    1.  Summarise each variable outputted to a text file Iris_Dataset_Summary.txt
    2.  Present histograms of each variables - Appendices 1-8
    3.  Present Scatter plots of each pair of variables - Appendices 9-11)

*Step 2 - Save all files to GitHub*

*Step 3 - Write a summary of all findings and conclusions in README.md*




**Findings and Conclusions**

Based the histograms below, we can conclude the following based on range spread of measurements and range of frequency of measurements: 

**Sepal Length**

  Iris Setosa has the highest concentration of samples in one 'bin' and has a shorter range of measurements.  
  Iris Versiculor has a wider range of measurements but is reasonably consistent frequency across the 'bins'. 
  Iris Virginica has the widest range spread and variety of measurement frequency


**Fig 5. Histogram - Sepal Length**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%201%20-%20Sepal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set.png?raw=true)
**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%201%20-%20Sepal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set.png



**Fig 6. Histogram - Sepal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%202%20-%20Sepal%20Length%20Occurances%20in%20the%20Iris%20Data%20Set%20by%20Species.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%202%20-%20Sepal%20Length%20Occurances%20in%20the%20Iris%20Data%20Set%20by%20Species.png


**Sepal Width**

  All three varieties have a large range of measurements and a marked concentration in one 'bin'


**Fig 7. Histogram - Sepal Width**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%203%20-%20Sepal%20Width%20%20Occurences%20in%20the%20Iris%20Data%20Set.png?raw=true)
**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%203%20-%20Sepal%20Width%20%20Occurences%20in%20the%20Iris%20Data%20Set.png


**Fig 8. Histogram - Sepal Width by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%204%20-%20Sepal%20Width%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%204%20-%20Sepal%20Width%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png


**Petal Length**

  Iris Setosa has the highest concentration of samples in one 'bin' and has a shorter range of measurements.  
  Iris Versiculor has a wider range of measurements and is reasonably consistent frequency across the 'bins'. 
  Iris Virginica has the widest range spread and is reasonably consistent frequency across the 'bins'.


**Fig 9. Histogram - Petal Length**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%205%20-%20Petal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set.png?raw=true)
**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%205%20-%20Petal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set.png



**Fig 10. Histogram - Petal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%206%20-%20Petal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%206%20-%20Petal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png


**Petal Width**

  Iris Setosa has the highest concentration of samples in one 'bin' and has a shorter range of measurements.  
  Iris Versiculor has a wider range of measurements and is reasonably consistent frequency across the 'bins'. 
  Iris Virginica has the widest range spread and is reasonably consistent frequency across the 'bins'.



**Fig 11. Histogram - Petal Width**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%207%20-%20Petal%20Width%20Occurences%20in%20the%20Iris%20Data%20Set.png?raw=true)
**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%207%20-%20Petal%20Width%20Occurences%20in%20the%20Iris%20Data%20Set.png



**Fig 12. Histogram - Petal Width by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%208%20-%20Petal%20Width%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%207%20-%20Petal%20Length%20Occurences%20in%20the%20Iris%20Data%20Set%20by%20Species.png





**Scatter Plot Conclusions**

  •	Positive correlation between Petal Width and Petal Length

  •	Positive correlation between Petal Length and Sepal Length

  •	Positive correlation between Petal Width and Sepal Length


**Fig 13. Scatter Plot - Petal Width vs Petal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209%20-%20Sample%20Scatterplot%20Petal%20Width%20vs%20Petal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209%20-%20Sample%20Scatterplot%20Petal%20Width%20vs%20Petal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png



**Fig 13a. Scatter Plot - Petal Length vs Sepal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209a%20-%20Scatterplot%20Petal%20Length%20%20vs%20Sepal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209a%20-%20Scatterplot%20Petal%20Length%20%20vs%20Sepal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png



**Fig 13b. Scatter Plot - Petal Width vs Sepal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209b%20-%20Scatterplot%20Petal%20Width%20%20vs%20Sepal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%209b%20-%20Scatterplot%20Petal%20Width%20%20vs%20Sepal%20Length%20by%20Species%20-%20Without%20%20Regression%20Lines.png



**Fig 14. Sample Scatter Plot with Regression Lines- Petal Width vs Petal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010%20-%20Sample%20Scatterplot%20Petal%20Width%20vs%20Petal%20Length%20by%20Speciesv-%20with%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010%20-%20Sample%20Scatterplot%20Petal%20Width%20vs%20Petal%20Length%20by%20Speciesv-%20with%20Regression%20Lines.png


**Fig 14a. Sample Scatter Plot with Regression Lines- Petal Length vs Sepal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010a%20-%20Scatterplot%20Petal%20Length%20vs%20Sepal%20%20Length%20by%20Species-%20with%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010a%20-%20Scatterplot%20Petal%20Length%20vs%20Sepal%20%20Length%20by%20Species-%20with%20Regression%20Lines.png

**Fig 14b. Sample Scatter Plot with Regression Lines- Petal Width vs Sepal Length by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010b%20-%20Scatterplot%20Sepall%20Length%20vs%20Petal%20Width%20by%20Species-%20with%20Regression%20Lines.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2010b%20-%20Scatterplot%20Sepall%20Length%20vs%20Petal%20Width%20by%20Species-%20with%20Regression%20Lines.png



**Fig 15. Scatter Plot Grid - Comparison of All Variables by Species**

![alt text](https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2011%20-%20Scatter%20Plot%20Grid%20-%20Compare%20All%20Variables.png?raw=true)

**Repository Link**: https://github.com/Fiona-600/Project-2020/blob/master/Appendix%2011%20-%20Scatter%20Plot%20Grid%20-%20Compare%20All%20Variables.png





**Technology Used**

**Required Programs**

	•	Anaconda Navigator 3
	•	Visual Studio Code
	•	Python version 3.7.4
  •	Cmder 
	•	GitHub
 	•	MS Office 
	•	Firefox Internet Explorer

**Procedure for downloading required programs**

    •	Python version 3.7.4 was downloaded via Anaconda Navigator 3 to Windows 10 OS (https://www.anaconda.com/).
    •	Microsoft Visual Studio Code was downloaded (https://code.visualstudio.com/).
    •	Microsoft Visual Studio Code was configurated with GitHub (https://github.com/).
    •	The Iris dataset was imported to Python as a CSV file 


**Libraries and Modules**

    •	NumPy - ‘import numpy as np’

    •	Pandas – ‘import pandas as pd’
        
    •	Matplotlib - ‘import matplotlib.pyplot as plt’

    •	Seaborn - ‘import seaborn as sns’, 'sms.set'



**Author & Contributors**

Fiona Lee



**License**

This project is licensed under the MIT License - see the LICENSE.md file for details



**Acknowledgments**

Brian McGinley and Ian McLoughlin for all the helpful tips in completing these assignments



**References**

