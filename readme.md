The dataset of the road segmentation of 32 images. Defined 6 classes for cars, road, markings, signs, nature, background.
The segmentation is done with U-net.
"code" contains code of the model with training and displaying the results.
"images" contains original images
"masks" contains marked up masks
"predict" contains the result of the model predictions

To use the model on your computer create a python file, paste the code, download dataset, enter the path to the dataset folder,
train the model. After that you can comment the training part, uncomment the displaying part (originally comented in the "code" file)
and load the saved state of the model in order to see the results, choosing any image of the dataset via LoadData class variable and using show function.
