This assignment was locked Mar 16 at 11:59pm.
1. Do a 2 page [word doc]  writeup of your project in technical detail

2. Create a dynamic visualization of your confusion matrix based on a changing of distribution 
https://towardsdatascience.com/data-visualization-with-python-holoviz-plotting-4848e905f2c0 (Links to an external site.)

Change data distribution
Upsample, downsample on a given feature
Which feature? perhaps use Ginis core, feature importance, shap
e g Gender –retail purchase, neighborhood- real estate purchase
Compute Muller loop :  pick. Your best model [MLP]
Change distribution --> run muller --> XGB is not the best for change 1
Change your data distribution with a slider
To see if your metrics (eg, r2, or, f1) will change if you change the data distribution?
Choose 3-4 (1 person each in team) algo, compute the model as you change the data distribution and plot the confusion matrix/other metrics and a visualization of the metrics / graphs
here are additional tips:
data distribution and smote for upsampling or downsampling:
find the feature importance
upsample one of the imp features
plot the resulting distribution for the key features above
try again but downsample one of the features
plot
training: [for each round of upsampling (or downsampling)]
train in a muller loop -- regression or classification
store the f1 score for the top algorithms
eg, xgboost, mlp, rf, svm
Change the data distribution
re-train
print confusion matrix, plot specificity vs sensitivity
repeat for each feature (1-3)
Now use the software I pointed you to to visualize the results instead of plotting
be able to call function that downsamples when you move slider left,
call upsampling function when you slide right
retrain
redisplay results f1, confusion, plot spec vs sensi
repeat for other four algos (each person one algo)
