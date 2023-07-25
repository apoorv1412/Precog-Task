# Precog-Task

This is the repo containing the data analysis and classification task for Precog. The task is to gain some insight from the dataset and then formulate a classification problem on the basis of it.

The dataset consists of indian court cases. The classification task decided is to classify the court cases based on their disposition. There were a number of labels denoting the disposition status. The task selected was to label the case as having reached a conclusion in the specific court (finalized) containing disposition status 'closed', 'decided', 'disposed', or as not finalized, containing the rest of the labels.

Due to the size of the dataset, the dataset used is for the 2015 cases. For the analysis, the data is analysed for the effect the gender of the judge, the state, and whether the case is deemed as a criminal case or not has on the case disposition. For classification, the methods used are logistic regression, KNN, Decision Trees and Random Forest

References 
The notebook has been constructed on kaggle with the court-cases dataset already uploaded. Chatgpt has been used sparingly for creating graphs and looking up basic syntax.

The report is the Precog Task.pdf file and the notebook is uploaded for the source code. The notebook can be imported on kaggle or google colab and can be executed. Standard pandas and sklearn libraries are used
