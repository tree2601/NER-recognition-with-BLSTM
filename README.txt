CSCSI 544 HW4 Xiaoshu Luo 9541629716

The script is completed on Google Colab and the model is trained by GPU. 
In the zipped file, the report, ipynb file, python script, dev_1.out,dev_2.out, test_1.out and test_2.out are included.
There are two additional files called dev_prediction.txt and dev_prediction_2.txt which can be used to verify the results using perl command.

A py file named csci544_hw4_9541629716.py is provided to produce the dev_1.out and dev_2.out file with the command:

csci544_hw4_9541629716.py model_1_path model_2_path train_path dev_path glove_path

In the command, the five arguments refer to the path of model 1, model 2, train data, dev data, and glove data respectively. 
The command should generate dev.out and dev2.out in the same directory. 

Alternatively, an ipynb file named CSCI544_HW4_9541629716 .ipynb is also provided to give the same result. 
To reproduce the result, just simply run every code block consecutively. 

The following variables have been defined to find the corresponding files:
train_path
dev_path
test_path
glove_path

Also drive.mount is used to load files from google drive. The four variables should be adjusted to match the absolute path of the files, and the command drive.mount(path) is not needed if run locally.
 
Thank you!