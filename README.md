# Principles of Data Analytics

## *Weekly Tasks*

![alt text](iris.png)

## Overview 🌱

This repository contains ten weekly task submissions completed as part of the assessment requirements for the *Principles of Data Analytics* module at Atlantic Technological University – Galway.

The purpose of this repository was to document my introductory journey into data analytics, undertaken as a novice learner. Over a series of ten weekly tasks, I engaged with foundational concepts in data analysis using Python and Jupyter Notebooks, with the well-known Iris dataset serving as the central focus of exploration. This allowed me to gain practical experience in applying data analytic processes on real-world data. 

Each task introduced a core element of the data analytics pipeline:

  1. **Sourcing the Dataset:** I began by importing the Iris dataset, gaining familiarity with accessing and loading structured data using sklearn.

  2. **Exploring the Data Structure:** I examined the dataset’s features, data types, and general format, developing an understanding of how datasets are organized.

  3. **Summarizing the Data:** Descriptive statistics were computed to observe central tendencies and spread, enhancing my grasp of numerical summaries.

  4. **Visualizing Features – Histograms:** I used matplotlib to create histograms, learning how to assess distributions of individual features.

  5. **Investigating Relationships – Scatterplots:** Scatterplots allowed me to begin examining pairwise relationships between features.

  6. **Analyzing Relationships – Regression Line:** I incorporated a regression line into the scatterplot from task 5 to understand linear trends and strengthen visual interpretation, using numpy.polyfit. 

  7. **Class Distributions – Boxplots:** Boxplots of petal lengths by species were created to investigate intra-class variability and inter-class distinctions.

  8. **Computing Correlations – Heatmap:** I calculated the correlation coefficients between the features and visualized them using a heatmap, using matplotlib, to identify strong or weak feature relationships.

  9. **Fitting a Simple Linear Regression:** I used SciPy to fit a simple linear regression between two features from Task 5 and calculated the coefficient of determination (R²) to assess the model's explanatory power. The scatterplot from Task 6 was re-created and annotated with the R² value using Matplotlib, enhancing the interpretation of the relationship.

  10. **Creating a Pair Plot:** Finally, a comprehensive pair plot using seaborn enabled simultaneous visualization of all feature relationships and class distinctions.

I utilized essential Python libraries such as NumPy, SciPy, pandas, matplotlib, seaborn, and scikit-learn. These tools supported data manipulation, statistical computation and visualization, allowing me to form a practical foundation for future work in data science and analytics.

author: Niamh Hogan

## About this repository 🌺

This repository is comprised of the following files and folders:  

  - A **.gitignore** file which contains all the files/folders to be ignored by Git in this repository.
  - An **iris.png** file containing an image of the different types of iris species & the location of sepal & petal measurements taken from: [Giri, 2022](https://machinelearning4ya.blogspot.com/2022/04/iris-flowers-classification-using.html).
  - A **README** file that contains an overview of the repository & explanation of the tasks within the Jupyter Notebook, a list of dependecies & their versions, technologies utilized, How to: Setup environment, Download repository & Run the code and a short explanation on where to find the references.
  - A **requirements.txt** file containing all the Python packages that the code depends on & their versions.  
  - A Jupyter Notebook, titled **tasks.pynb** that contains all ten tasks previously discussed in the overview.

## Dependencies 🌺  
**See tasks.ipynb for further information on the following libraries** 

* python==3.12.1  
* numpy==2.2.0  
* scipy==1.14.1  
* matplotlib.pyplot==3.9.3  
* seaborn==0.13.2  
* pandas==2.2.3  
* scikit-learn==1.6.0  

## Technologies 🌺 

- Python
- Anaconda
- Git
- GitHub
- Codespaces
- Jupyter Notebooks
- Visual Studio Code

## How to Setup Environment 🌺  

For downloading and running the repository locally download the following:  

**Git**  

Download the latest version of Git at:  
https://git-scm.com/downloads

**GitHub**  

Create a free GitHub account at:  
https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

**Anaconda**  

I recommend using Anaconda as it comes bundled with Python, Jupyter Notebooks & the Python libraries used in this repository.  
Install Anaconda using the following steps:  

1. Download Anaconda for free from:  
https://www.anaconda.com/download
2. Open the downloaded file & press next, next
3. When the advanced options appear check the following boxes:  
  - Add to PATH environment variable  
  - Make this version your default Python  

**Visual Studio Code**

Download Visual Studio Code at:  
https://code.visualstudio.com/Download  
  - Install Python & Jupyter extensions in VS Code 


## How to Download Repository 🌺  

You can clone this repository to VS Code using the following steps:

1. Copy the repositories URL from GitHub:  
https://github.com/NibnabCodes/principles_of_data_analytics
2. Create a folder in VS Code of where you want to store the cloned repository
3. Open new terminal in VS Code & input following:  
  - git clone PASTED.URL - To clone repository  
  - git config pull.rebase false - Set pull mode to merge  
  - git pull - To pull the content of the repository  

The repository should now be accessible in VS Code & ready to execute.


## How to Run the Code 🌺  

  1. Open repository folder in VS Code  
  2. Open .ipynb file  
  3. In the top right-hand corner click "select kernel"  
  4. select Python environment  
  5. To execute the cells to run the code within the notebook, select "Run All" or run the cells one by one by clicking "▶️ Execute cell" on the top left-hand corner of the cell


## References 🌺  

Please see tasks.ipynb for references used.