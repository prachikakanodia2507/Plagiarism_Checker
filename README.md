# Plagiarism_Checker
 PS-1 Internship Project
 
# Objective: 
The objective is to achieve is to design a system which when provided any doc or pdf file, check for Plagiarism in the content and revert for the same, along with the sources, from where the content has been copied.

# Tech Stack:
Python

Data Science 

Machine Learning

# Libraries Used:
difflib (SequenceMatcher)

re

nltk (N-gram Language Model)

plotely.graph_objects

scipy.ndimage (gaussian_filter)

docx2txt & doc2txt

textract & pypdf2

random

Copyleaks API

# How to Use?
To run the project to check between two files, upload the file paths of first file in file1path and sencond file in file2path with their file extensions. Three sample files have been added with the project to test the project (DesignAnalysisAlgorithm.docx, N-gramModel.txt, PlagiarismDetectionSystem.pdf) 

To check a file for plagirarism against online sources, register on https://api.copyleaks.com to get the API key.
Fill the key and email accordingly in the place marked as:

EMAIL_ADRESS = ''

KEY = ''

You will receive the report on Copyleaks dashboard https://api.copyleaks.com/account/login?returnUrl=%2Fdashboard%2F:product in .json file.

# Future Scope:
This project can be further enhanced with its own system so that the use of external API is reduced. It can also be expanded to check plagiarism in code files rather than just pdfs and docx files. 

HAPPY LEARNING!! ✌😇
