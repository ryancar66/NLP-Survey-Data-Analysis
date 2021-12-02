# NLP-Survey-Data-Analysis
A company had just finished conducting a survey to 16,000 of their employees. They did not have the resources within their team to perform advanced analytics to uncover the insights in their data. They asked my consulting firm for help in this data science project. The resulting knowledge from this nlp analysis was then presented in a meeting to C-suite executives at the firm. <br> <br>
This repository will include two Jupyter Notebook which I've recreated and condensed from some of the script used in the analysis of the client's data. The purpose of this notebook is to provide the viewer an example of the kind of work I've done in a client setting, it is not meant for another git user to run this code. This repository does not include many other analysesused in this engagement, it is just a glimpse into the python code used for a NLP analysis. Please refer to the **NLP-Article** repository for more context around Natural Language Processing and how to use the spaCy library. <br>
### 1. nlp_analysis.ipynb
This notebook will show the python Class created in order to take in the raw survey response data, prepare it for natural language processing, and then perform multiple different analyses. The code is robust in that it is able to evaluate by each of the dimensions that were part of the survey response (age, tenure, job function, gender, etc.). This notebook is intended to show my python capabilites and the different ways you can visualize and extract insights from response data. The notebook contains more commentary on the steps and results. <br>
### 2. topic_modeling_framework.ipynb
This workbook shows the code for a custom solution that the client wanted. This retail company had values which were promoted by their C-level executives to all employees. They had to do with the workplace, personal development, teamwork, management, leadership, etc. The client wanted some sort of way to evalaute the responses by their list of values and asked for us to come up with something. Our idea was to develop a Topic Tagging Model that would scan through each response and if it included a word that fell into one of their cateogires then it would be tagged with that company value. I then sat down with members of the company to discuss which words they felt related to a value. The resulting product was an easily configurable excel file (incase the compnay ever wanted to make adjustments to the dictionary) that would be loaded into a python script and output a structred excel file. This excel file was then loaded into Qlik where they could visually see the quantiative results from response data. The notebook provides more commmentary as you follow along. 
