# Difficulty of Learning for Deep Learning Models Experiments

This folder contains the experiments artifacts that were used to conduct the Final Year Project (Fintech related machine learning : experimental investigation on the effects of data variance towards difficulty of learning for deep learning models), the results that are obtained from the experiments, as well as the datasets that were used. 

There are multiple sub-folders contained within this folder itself. The sub-folders that contains the codes and experiments artifacts used to conduct the Final Year Project are stored in the folders titled:

- New variation 1 Experiments
- New variation 2 Experiments
- New variation 3 Experiments
- New variation 4 Experiments
- New variation 5 Experiments
- New variation 6 Experiments

The following sub-folders contains the results obtained from the various experiments carried out throughout the project:

- FYP Final Report Supplementary Results (supplementary results not included in FYP Report)
- New variation experiments results - combined (combined results and graph plots of all experiments conducted)
- Results for New variation 3 Experiments (Results for the variation 3 Experiments as it could not be included in 'New variation 3 Experiments' folder due to file path length)

The sub-folder that contains the codes used to generate the various datasets required for the various experiments for the Final Year Project:

- Code to Generate Dataset



# Instructions on How to Run the codes in 'New variation x Experiments' subfolders

The instructions to run the codes for the variation experiments for Variation 1 to 6 contained in the folders titled:

- New variation 1 Experiments
- New variation 2 Experiments
- New variation 3 Experiments
- New variation 4 Experiments
- New variation 5 Experiments
- New variation 6 Experiments

are given below.

## Requirements to run the codes in 'New variation x Experiments' subfolders

In order to run the codes in this sub-folder, you first have to ensure that you have Jupyter Notebook installed on your computer. Jupyter can be installed either as part of the 
Anaconda open-source Python ecosystem which can be downloaded from https://www.anaconda.com/products/individual or using the instructions on the Jupyter website 
https://jupyter.org/install

![Image of jupyter](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/jupyter.png)


Next, please ensure that you have the following Python libraries INSTALLED on your computer:

- pandas_datareader.data
- talib
- numpy
- pandas
- matplotlib
- requests
- lxml
- scikit-learn
- numpy
- tensorflow
- Pillow
- tensorflow_addons
- opencv-python

The libraries can be installed by searching them from https://pypi.org/ and performing a pip install for the libraries.


In order to ensure that the python notebooks can be run effectively and efficiently, please run the notebooks on a Desktop or Laptop that has a GPU compatible with Tensorflow.
This will allow the python notebooks to be able to run faster and train the models faster. Alternatively, you can download the entire 'New variation x Experiments' sub-folders into your Google Drive, including the 'data' sub-folder contained within each 'New variation x Experiments' folder. Then, run the python notebooks on Google Colab with the runtime type changed to 'GPU' for the hardware accelerator. 
NOTE: If you were to run the notebooks in the Google Colab environment, be sure to create a new cell to mount your Google Drive to be able to access the datasets in the 'data' sub-folder and be sure to change the file paths to read or write any files as and when required.


## Running the codes

Now, with all the requirements fufiled in the above section, you can open each of the '.ipynb' python notebooks on the Jupyter environment and run every cell UNTIL THE END of the notebooks in order to train the models and generate the results and graphs for each of the following Variation Experiment. There is no particular order to run the 'New variation x Experiments' sub-folders or the python notebooks in them. However, please ensure that the required datasets that should be in the 'data' sub-folder contained within each 'New variation x Experiments' folder are present and that the file paths for any I/O of the notebooks are set properly to prevent any file paths error.

Once all the notebooks are run, you should be able to see the generated results for each of the experiments in CSV format. If there are any errors encountered, it is most probably due to libraries not being installed or there is an error with the file paths, please check if the required libraries are installed and the file paths in the cells are correct.



