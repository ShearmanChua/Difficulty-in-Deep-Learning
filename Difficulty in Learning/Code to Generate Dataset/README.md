# Instructions on How to Run the codes in 'Code to Generate Dataset' subfolder

The codes in this sub-folder are the codes that are used to generate the datasets for the various variation experiments conducted for the Final Year Project. All the files that
end with '.txt' are the files that contain the ticker symbols to be used to extract the various stock data from Yahoo finance. The 'data_generator - v6.ipynb', 
'data_generator - v7.ipynb' are the notebooks that are used to generate the training datasets for the Vartiation 6 and Vartiation 7 experiments respectively, and 
the 'data_generator - test - v6.ipynb', 'data_generator - test - v7.ipynb' are the notebooks that are used to generate the test datasets for the Vartiation 6 and 
Vartiation 7 experiments respectively. The 'data_generator.ipynb' and 'data_generator - test.ipynb' are used to generate the training and test datasets for the rest of the 
variation experiments from Variation 1 to 5.

## Requirements to run the codes in 'Code to Generate Dataset' subfolder

In order to run the codes in this sub-folder, you first have to ensure that you have Jupyter Notebook installed on your computer. Jupyter can be installed either as part of the 
Anaconda open-source Python ecosystem which can be downloaded from https://www.anaconda.com/products/individual or using the instructions on the Jupyter website 
https://jupyter.org/install

![Image of poster](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/jupyter.png)


Next, please ensure that you have the following Python libraries installed on your computer:

- pandas_datareader.data
- talib
- numpy
- pandas
- matplotlib
- requests
- lxml

The libraries can be installed by searching them from https://pypi.org/ and performing a pip install for the libraries.

Next, please ensure that you have setup ALL the subfolders contained within the 'data' subfolder so that there will be no errors when running the codes. 


## Running the codes

Now, with all the requirements fufiled in the above section, you can open each of the '.ipynb' python notebooks on the Jupyter environment and run every cell UNTIL THE END of
the notebooks in order to generate all the required datasets for the experiments conducted for the Final Year Project. You should run the notebooks in this order:

1. 'data_generator.ipynb'
2. 'data_generator - test.ipynb'
3. 'data_generator - v6.ipynb'
4. 'data_generator - test - v6.ipynb'
5. 'data_generator - v7.ipynb'
6. 'data_generator - test - v7.ipynb'

Once all the notebooks are run, you should be able to see the generated datasets in the 'data' subfolder and the subfolders contained within it  in CSV format. If there are
any errors encountered, it is most probably due to libraries not being installed or there is an error with the file paths, please check if the required libraries are installed
and the file paths in the cells are correct.


