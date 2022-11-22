# The Github History of The Scala Language
A little project of data analysis on the real world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). 
We will find out who has had the most influence on its development and who are the experts.

## About the data
The dataset we will use, which has been previously mined and extracted from GitHub, is comprised of three files:

- pulls_2011-2013.csv contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.
- pulls_2014-2018.csv contains identical information, and spans from 2014 up to 2018.
- pull_files.csv contains the files that were modified by each pull request.

## Questions to answer
In this project we will answer the questions below:
- [x] Is development going steadily, or is there a drop? Has the project been abandoned altogether?
- [x] Is there camaraderie in the project?
- [x] What files were changed in the last ten pull requests?
- [x] Who made the most pull requests to a given file?
- [x] Who made the last ten pull requests on a given file?
- [x] Who was most involved in the project in recent times?
- [x] Which of our two developers of interest have the most experience with the code in a given file?

## Techniques
In this project, I used the following techniques to do the analysis:
- [x] Data manipulation with Pandas
- [x] Joining data with Pandas
- [x] Data visualisation with Matplotlib and Plotly
