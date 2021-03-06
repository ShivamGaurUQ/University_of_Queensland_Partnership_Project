- This tool was developed as a part of the University of Queensland Student-Staff partnership project.
- The tool helps the staff to analyse and visualise the student feedback data about engineering courses through topic modelling, text mining and opinion mining.
- The application was developed in Python.
- The application runs on Google Colab and can be accessed from the following link: https://colab.research.google.com/drive/126ykrAosZIhkzC9r5m-jkY9UevgjtP0I
- Execute all the steps from 1 to 5 before application starts.

# Dependencies

- Libraries/Packages used: Numpy, Pandas, NLTK, VaderSentiment, Gensim, Wordcloud, LatentDrichletAllocation, PylDavis, Ipywidgets, Matplotlib, Sklearn
- Python 3.6 or higher required.


# Demo

- The student feedback data from a prominent university in India was analysed with the help of the tool. The data is available on Kaggle and can be downloaded from the link https://www.kaggle.com/brarajit18/student-feedback-dataset/downloads/student-feedback-dataset.zip/1

- Download the data and run the application on Google Colab. Run all the cells from 1 to 5 in the colab notebook.
- Once application starts executing, import the feedback data. Note: the application only accepts .xls file (data in excel file format)

![](images/img1.png)

- The 'Data Settings' tab provides options to clean the data by removing NaN values and missing values in the rows for the 'Feature' (Column name) selected. Missing values can be specified in the 'Missing Value' text box.

![](images/img2.png)

- Data can be cleaned by clicking on 'Cleaned tab'. If cleaned, cleaned data will be used for analysis. To use original data for analysis purposes, click on 'Original' tab under the 'Data Settings'. To use a different column for data cleaning, choose the column from 'Feature' drop down box.

![](images/img4.png)

- Use Explore tab to view data/sort data/group data by 'Feature' selected.

![](images/img5.png)
![](images/img6.png)


- 'Visualize' feature distribution in the dataset through pie chart and bar graph.

![](images/img7.png)

- Use 'WordClouds' tab to generate uni-gram and bi-gram clouds for determining the most frequently occuring words in the text.

![](images/img8.png)
![](images/img9.png)

- 'Topic Modelling' helps to find out abstract topics in the text.

![](images/img10.png)

- Use 'Sentiment Analysis' to find out about the positive, neutral and negative feedbacks. 

![](images/img11.png)

- 'Text Summarization' provides a brief description of the feedback and highlights important words through POS tagging.

![](images/img12.png)
