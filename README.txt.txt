In source codes folder:-
1-Feature_extraction.py - it contains the feature extraction code for the dataset.
2-running file.ipynb - it extract the features of urls in the test_final.txt and train_final.txt
3-trainer.py - it contains the models that we applied 
4-main.py - it contains the code to run the model and to predict output file.
5-gui.ipynb - it contains the code for the GUI 


6-train_final.txt - file which contains the train urls.
7-test_final.txt - file which conatins the test urls.
8-test_features_imp.csv - it is the test dataset for our model
9-train_festures_imp.csv - it is the train dataset for our model
10-test_target.csv - it the target file with which we calculated the accuracy
11-test_predicted_target_grad.csv - this is the output file that we got after applying model on the test dataset
12-accuracy.txt - it contains the code to calculate the accuracy
13- gui_testing_url.txt - it conatins the url to test in GUI.

steps to run the codes
a>open ipython notebook
b>open running file.ipynb and run it(it will generate the whole csv files having features using feature extraction) 
c>open main.ipynb and run it (this will create the test_predicted_target_grad.csv file it is the output file)
d> to calculate the accuracy just run the accuracy.txt code in R
e> for showing thr GUI just run the gui.ipynb file .it will give you the interface to know whether the website is benign or malicious
