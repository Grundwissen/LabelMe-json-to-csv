# LabelMe-json-to-csv
When labeling Images with LabelMe you will get a .json file for each Image. 
This code extract important information from the .json file and puts them into one .csv file.


In my opinion most of the time when you working with neural networks it is easier to have the labels 
in one big csv file.
But, as mentioned above, the LabelMe program will create for every label a .json file. For me it is more
complicated to work with all the .json files instead of one big .csv file with only the information that I need.

This jupyther notebook will do this task. 

The output, e.g. the columns in the csv file will contain the name of the image, the label and the key points.

Peace
