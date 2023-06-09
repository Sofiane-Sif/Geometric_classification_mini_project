# Geometric classificication project
--- 
####  Project purpose :

#####  - Generate a synthetic dataset of shapes, such as rectangles, triangles, and ellipses, with random position, orientation, and color. The dataset should be sufficiently large and varied to allow for robust training and testing of the model.

##### - Train a classification model on the dataset and evaluate its performance on a held-out test set.

---
#### **Method** : 

Classification CNN implementing LeNet structure with pytorch

---
#### **To run the project** : 

1. Step 1 - Install all packages
```
$ pip install -r requirements.txt
```
2. Step 2 (OPTIONNAL) - If you wish, you can generate the dataset, running **generate_dataset.py** will create **_dataset_** folder with 3000 images for each shape (rectangles, ellipses and triangles).

3. Step 3 - Make predictions on new shape images (run **predict.py** will open a window showing a random shape image with the model's prediction). To make a new prediction, tab any keyboard key. To quit the prediction's window, tap 'q'. 

---
#### **Evaluation** : 

The _output_ folder contains the trained model (_model.pth_) and its performance (_plot.png_)


Here is the screenshot result of the prediction that you should have when you run **predict.py**. 


![Image](/output/Geometric_predict.png)



