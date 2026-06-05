# synent-task2-datavisualization-yourname

## Problem Statement

The Iris dataset contains measurements of three flower species. Just looking at the numbers does not make it easy to understand how the species differ from each other. The goal was to create visualizations that clearly show the patterns and differences across species.

## Dataset Details

- Dataset: Iris Dataset
- Source: Kaggle / sklearn built-in
- It has 150 rows with four numeric features: sepal length, sepal width, petal length, and petal width, along with the species label.
- Format: CSV

## Approach

I created three types of charts. First a bar chart showing the average value of each feature per species so you can compare them side by side. Then histograms for each numeric feature to see how the values are distributed. Finally scatter plots comparing petal length vs petal width with points colored by species to check if the classes are separable visually.

## Results

- Virginica has the largest petal dimensions on average and Setosa has the smallest
- Setosa is clearly separated from the other two species in the scatter plots
- Petal length and width turned out to be more useful for distinguishing species than sepal measurements
