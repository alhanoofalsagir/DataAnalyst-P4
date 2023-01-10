<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h3 align="center"><a href = "https://www.udacity.com/course/data-analyst-nanodegree--nd002"> Udacity Data Analyst Nanodegree </a></h3>
<h4 align="center">Project IV:Wrangle and Analyze Data</h4>

## Table of Contents
- [Project Overview](#project_overview)
- [Installation](#installation)
- [Project Details](#details)
- [Key Points](#key)
- [Code Functionality](#function)

## Project Overview <a name="project_overview"></a>
Real-world data rarely comes clean. Using Python and its libraries, the project gathers data from a variety of sources and in a variety of formats, assesses its quality and tidiness, then provides a cleaned version. This process is known as data wrangling. These wrangling efforts are documents in a Jupyter Notebook and a separate write-up.

The dataset which will be wrangled is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## Software Needed <a name="installation"></a>
The entirety of this project can be completed inside the Udacity classroom on the Project Workspace: Complete and Submit Project page using the Jupyter Notebook provided there. (Note: This Project Workspace may not be available in all versions of this project, in which case you should follow the directions below.)

If you want to work outside of the Udacity classroom, the following software requirements apply:

- You need to be able to work in a Jupyter Notebook on your computer. Please revisit our Jupyter Notebook and Anaconda tutorials earlier in the Nanodegree program for installation instructions.
- The following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.
   - pandas
   - NumPy
   - requests
   - tweepy
   - json
- You need to be able to create written documents that contain images and you need to be able to export these documents as PDF files. This task can be done in a Jupyter Notebook, but you might prefer to use a word processor like [Google Docs](https://www.google.com/docs/about/), which is free, or Microsoft Word.
- A text editor, like [Sublime](https://www.sublimetext.com/), which is free, will be useful but is not required.

## Project Details <a name="details"></a>
The tasks in this project are as follows:

- Data wrangling, which consists of:
  - Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
  - Assessing data
  - Cleaning data
- Storing, analyzing, and visualizing your wrangled data
- Reporting on
  - Data wrangling efforts
  - Data analyses and visualization

## Key Points <a name="key"></a>
Key points to keep in mind when data wrangling for this project:

- The project only need original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.
- Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
- Cleaning includes merging individual pieces of data according to the rules of tidy data.
- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.
- The project does not require gathering tweets beyond August 1st, 2017.

## Code Functionality : <a name="function"></a>
- All project code is contained in a Jupyter Notebook named [wrangle_act.ipynb](https://github.com/alhanoofalsagir/DataAnalyst-P4/blob/main/wrangle_act.ipynb) and runs without errors.
- The Jupyter Notebook has an intuitive, easy-to-follow logical structure. The code uses comments effectively and is interspersed with Jupyter Notebook Markdown cells. The steps of the data wrangling process (i.e. gather, assess, and clean) are clearly identified with comments or Markdown cells, as well.
