

# Disease Prediction Model for Tomato Plant
A Convolutional Neural Network based image classification model to disease in tomato plant leaves.

 - Model is developed over AlexNet architecture. Refer: [ImageNet classification with deep convolutional neural networks | Proceedings of the 25th International Conference on Neural Information Processing Systems - Volume 1 (acm.org)](https://dl.acm.org/doi/10.5555/2999134.2999257)
 - This model is trained on tomato disease images taken from PlantVillage dataset.
 
 

## Files

 - *plant_disease.ipynb* contains the code to develop and train the model.
 - *model* folder contains the saved model.
## Run Locally
 - Install git, anaconda or miniconda.
 - Run `git clone https://github.com/sudoshivam/plant-disease-DL.git` in cmd or terminal to clone the project or you can simply download the folder and unzip it.
 - create an anaconda environment with python3.6. Refer [this link](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands)  for tutorial.
 - Activate conda anvironment and run the commands given in *dependencies.txt* file to install required libraries.
 - Open new anaconda prompt in project folder and run following command `flask run`
 - Now the app should be running in anaconda prompt. Open the given url in a web browser to use the app.
 
## Demo
Choose an image file and click on Upload or paste link to an image in the URL box and click on Proceed.
![home](https://raw.githubusercontent.com/sudoshivam/plant-disease-DL/main/static/images/1.png)
---------------------------------
Model will predict the disease in leaf. It also shows which disease has highest probability.
![result](https://raw.githubusercontent.com/sudoshivam/plant-disease-DL/main/static/images/2.png)
