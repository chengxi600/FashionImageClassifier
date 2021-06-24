# FashionImageClassifier
Built a CNN model that classifies fashion images into 8 article types based on the dataset from https://www.kaggle.com/paramaggarwal/fashion-product-images-small. The written report detailing this project can be found in the 'paper' folder, or click [here](/paper/CS4100_Report.pdf).

# Brief Description of the experiments
1. Making a baseline model more complex by adding more layers systematically 
2. Kernel sizes tuning
3. Combating overfitting
4. Changing the width of the model 
9. Using colored input images instead of grayscale

# Brief Instructions
Please refer to the the appendix of the paper, or click [here](/paper/CS4100_Report.pdf).

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
![image](https://user-images.githubusercontent.com/57016570/123313094-23f1ec80-d4f7-11eb-8130-71c1050dda13.png)
