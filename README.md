# Iris Flower Classification 🌸

This is a simple ML project I made as part of my CodeAlpha internship task. 
The goal was to predict the species of an iris flower based on its measurements 
(sepal length, sepal width, petal length, petal width).

## What I did
- Loaded the Iris dataset using pandas
- Checked the data (no missing values, 50 samples of each species)
- Made a pairplot with seaborn to see how the species are separated
- Split the data into training (80%) and testing (20%) sets
- Trained a Logistic Regression model
- Tested it on data it hadn't seen before

## Libraries used
- pandas
- seaborn
- scikit-learn

## Result
Got 100% accuracy on the test set. All 3 species (setosa, versicolor, virginica) 
were classified correctly with no mistakes. This dataset is pretty small and the 
petal measurements especially make it easy to separate the classes, which is why 
the accuracy is this high.

## Files
 `Iris_Flower_Classification.ipynb` - the notebook with all the code

---
Made for CodeAlpha Data Science Internship
