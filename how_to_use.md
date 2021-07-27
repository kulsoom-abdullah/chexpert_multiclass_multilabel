READ ME on how to run the notebooks (give a disclaimer of no requirements.txt or just not mention it. 

`EDA.ipynb` - Exploratory Data Analysis and feature cleaning. It writes a train and test pickle file that is used in the modeling notebook.

`modeling-metadata.ipynb` - This is the modeling notebook. It loads the pickle files created in the EDA notebook to use for training and validation. The ending cell has the inference function. 

Arguements at the beginning of the modeling notebook:

`DEBUG = False # reduce train size for testing purposes when this is set to True`
`NEPTUNE_TRACK = True #If true, start a neptune session` to keep track of metrics

To learn more about neptune, visit https://neptune.ai/

