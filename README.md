# FashionImageClassifier
Built a CNN model that classifies fashion images into 8 article types based on the dataset from https://www.kaggle.com/paramaggarwal/fashion-product-images-small. The written report detailing this project can be found in the 'paper' folder, or click [here](/paper/CS4100_Report.pdf).

# Brief Description of the experiments
1. Making a baseline model more complex by adding more layers systematically 
2. Kernel sizes tuning
3. Combating overfitting
4. Changing the width of the model 
9. Using colored input images instead of grayscale

# Brief Instructions
Download all the files inside the "files"
folder. There should be 4 zips. Download the notebook "FashionCNN_final.ipynb" in the "notebook" folder to run the final model
for our project. For a more detailed walkthrough of our project
including all experiment and data preprocessing, download the
notebook "FashionCNN_detailed.ipynb". Instructions to run the
detailed version will be found in the detailed notebook.

### Running FashionCNN_final.ipynb
After unzipping the zip files in the "files" folder, there were be four
folders. "assets" will contain assets of the final model. "variables"
will contain variables of the final model. "model_histories" will
contain the model histories of all our experiments and models.
"saved_files" will contain all our preprocessed data. There are
instructions in the detailed notebook on how to reproduce all the
data, but due to the run time, we will be loading all our variables
and data in this notebook.
Please change the paths to each folder in the notebook to wherever you placed these folders. If you are running the notebook
on Google Colab, you can upload the zips to your Drive and unzip these folders in the Colab. Make sure to run the appropriate
shell commands given in the notebook if you want to mount your
Drive. Before running the code, make sure you have the following
libraries: Numpy, Pandas, Seaborn, Matplotlib, scikit-learn, TensorFlow Follow the instructions given in the notebook and you
should be able to reproduce our model, the evaluation results,
and the confusion matrix

# Structure of the final model
Type: sequential
<br>
![image](https://user-images.githubusercontent.com/57016570/123312099-e345a380-d4f5-11eb-80ef-07174ab5af2c.png)
<br>
Total params: 2,895,768
<br>
Trainable params: 2,895,768
<br>
Non-trainable params: 0

# Scoring of the final model
Testing Accuracy: 0.923
<br>
Confusion Matrix:
<br>
![image](https://user-images.githubusercontent.com/57016570/123311868-a11c6200-d4f5-11eb-811c-3361bdb500ac.png)
<br>
Performance Table:
<br>
![image](https://user-images.githubusercontent.com/57016570/123313094-23f1ec80-d4f7-11eb-8130-71c1050dda13.png)
