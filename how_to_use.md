READ ME on how to run the notebooks (give a disclaimer of no requirements.txt or just not mention it. 

EDA notebook - that it saves pickles of train and test

Then the modeling notebook loads Load pickle files to use for training. the ending cell has the inference function. 

about Neptune https://neptune.ai/ I used this to keep track of each run of training I did.

Arguements at the beginning of the modeling notebook:

`DEBUG = False # reduce train size for testing purposes when this is set to True`
`NEPTUNE_TRACK = True #If true, start a neptune session`

