# Task 3

**To create a neural network using least numbers of parameters and get a highest accuracy model.**

- Process

  - Download the dataset from the link https://drive.google.com/drive/folders/1AlztDRzHhuavHPb77o9ZDHGIp6za77AR
  - Create all the pre-processing steps similar to the one from the above notebooks.
  - Create a Neural network model using Keras and train the model on the training
dataset
  - Test the model on the test dataset
  - Push the code on Github, showing the model architecture, number of parameters
and test accuracy on the Readme.md file.

Modules/Libraries used:

        1. OS
        2. Numpy
        3. Pandas
        4. Tensorflow
        5. Keras
        
## Input

### Here we have csv files of train_data and test_data of both dog and cat combined as shown below.



      


![Screenshot 2022-03-30 115150](https://user-images.githubusercontent.com/81549221/160765293-4f25fcd7-c336-4506-b197-8f780be34f3f.png)      ![Screenshot 2022-03-30 115223](https://user-images.githubusercontent.com/81549221/160765327-b6e3f85f-e93a-4e43-bad5-ad6b1d292885.png)

### We have folder of both test_data and train_data of containing 2000 and 8000 images respectively as shown below.


![Screenshot 2022-03-30 115831](https://user-images.githubusercontent.com/81549221/160765831-b6ed10ad-960d-4cfd-8da3-00dd435f92cf.png)

![Screenshot 2022-03-30 115900](https://user-images.githubusercontent.com/81549221/160765840-bef037be-f3a3-46bb-9f97-2749319c361f.png)


 ### Now using the os library and the csv file we will get the names of image from csv file and print the path of image as shown:
 
 ![Screenshot 2022-03-30 120143](https://user-images.githubusercontent.com/81549221/160766438-10de0bc1-9437-44da-833f-779617d7045c.png)



 ### After creating all preprocessing steps we will continue to train neural network using kears model and train it on train_data set.
 
 
 ![Screenshot 2022-03-30 122059](https://user-images.githubusercontent.com/81549221/160769355-91fda62b-791e-4815-b9d2-40bae6fdf522.png)


## Output:
**We trained the model on trained dataset and now we test it on test data and here are the result we get:**



 ![Screenshot 2022-03-30 122302](https://user-images.githubusercontent.com/81549221/160769709-294a7b3b-b781-4abd-8ad7-1cce436912ba.png)


**And eventually we will save the model for future use.**
