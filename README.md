# CSC4850 Machine Learning Final Project

## Models Used

1. Decision Tree
2. Random Forest
3. Perceptron
4. Naive Bayes
5. Logistic Regression
6. Linear Regression
7. SVM - Linear Kernel
8. SVM - RBF kernel
9. Gradient Boosting
10. Multi-layer Perceptron (MLP)

## Decision Tree

<img width="1076" alt="Screenshot 2023-04-23 at 7 05 21 PM" src="https://user-images.githubusercontent.com/101344801/234142493-f9efddcc-9288-4468-84e2-3a8b775f6cd2.png">

<img width="1016" alt="Screenshot 2023-04-23 at 7 12 30 PM" src="https://user-images.githubusercontent.com/101344801/234142636-8171590e-c14e-460c-8405-638f5ddeaa81.png">


## Random Forest

<img width="976" alt="Screenshot 2023-04-23 at 8 42 34 PM" src="https://user-images.githubusercontent.com/101344801/234142785-0c7c0244-de12-47b5-959a-69cf0f42e11b.png">

<img width="1020" alt="Screenshot 2023-04-23 at 8 43 57 PM" src="https://user-images.githubusercontent.com/101344801/234142801-17c3604d-11b2-472b-99cd-3ef6d93afdb5.png">


## Perceptron

<img width="974" alt="Screenshot 2023-04-23 at 8 51 18 PM" src="https://user-images.githubusercontent.com/101344801/234142877-37208316-ba24-4152-a572-927744384b59.png">

<img width="1020" alt="Screenshot 2023-04-23 at 8 44 09 PM" src="https://user-images.githubusercontent.com/101344801/234143167-9e45a74b-34a0-4bfa-aee4-cb9deffa6b12.png">


## Naive Bayes

<img width="974" alt="Screenshot 2023-04-23 at 8 51 24 PM" src="https://user-images.githubusercontent.com/101344801/234142909-40530343-f360-4721-a4f0-c950b0579159.png">

<img width="1020" alt="Screenshot 2023-04-23 at 8 44 16 PM" src="https://user-images.githubusercontent.com/101344801/234143195-2830fef6-262a-4cbb-b81b-e0fa962add72.png">


## Logistic Regression

<img width="974" alt="Screenshot 2023-04-23 at 8 51 28 PM" src="https://user-images.githubusercontent.com/101344801/234142947-2f467fd2-5181-4549-bc4a-33778fa33716.png">

<img width="1020" alt="Screenshot 2023-04-23 at 8 44 20 PM" src="https://user-images.githubusercontent.com/101344801/234143224-206a4046-aaf1-43d5-b569-36b6709bd36c.png">


## Linear Regression

<img width="847" alt="Screenshot 2023-04-23 at 8 51 42 PM" src="https://user-images.githubusercontent.com/101344801/234142989-4a084490-54fe-43bf-8957-d746c11ce889.png">

<img width="1036" alt="Screenshot 2023-04-23 at 8 44 29 PM" src="https://user-images.githubusercontent.com/101344801/234143257-96adc120-e2b0-4611-893b-abd50140c082.png">


## SVM - Linear Kernel

<img width="975" alt="Screenshot 2023-04-23 at 8 51 58 PM" src="https://user-images.githubusercontent.com/101344801/234143017-3ac98bcd-8de3-48ca-ab33-17953b3486fc.png">

<img width="1002" alt="Screenshot 2023-04-23 at 8 44 42 PM" src="https://user-images.githubusercontent.com/101344801/234143283-d4bb84af-7226-4f55-b411-e723e036ae97.png">


## SVM - RBF kernel

<img width="975" alt="Screenshot 2023-04-23 at 8 52 01 PM" src="https://user-images.githubusercontent.com/101344801/234143045-5a74027f-5590-4f7c-bcff-cb47e33eca7d.png">

<img width="1011" alt="Screenshot 2023-04-23 at 8 44 52 PM" src="https://user-images.githubusercontent.com/101344801/234143313-13276fb2-0d09-476a-a938-28c802dae39f.png">


## Gradient Boosting


<img width="975" alt="Screenshot 2023-04-23 at 8 52 05 PM" src="https://user-images.githubusercontent.com/101344801/234143065-96cdc2fd-2001-4b1f-a89c-f6552f2ec25c.png">

<img width="1028" alt="Screenshot 2023-04-23 at 8 45 03 PM" src="https://user-images.githubusercontent.com/101344801/234143332-a0fbf51f-c62e-4f73-aed8-d65b47d1c7e8.png">


## Multi-layer Perceptron (MLP)

<img width="975" alt="Screenshot 2023-04-23 at 8 52 08 PM" src="https://user-images.githubusercontent.com/101344801/234143116-97351ee5-3191-4ba4-916b-27d23da5effd.png">

<img width="1028" alt="Screenshot 2023-04-23 at 8 45 17 PM" src="https://user-images.githubusercontent.com/101344801/234143352-8f7d13d3-a36f-4689-b676-afc552b81e38.png">

## Best fold per Split

|Model              |50/50|70/30|80/20|Best split|
|:------------------|:----|:----|:----|:---------|
|Decision Tree      | 1   | 2   | 7   | 50/50    |
|Random Forest      | 3   | 2   | 1   | 50/50    |
|Perceptron         | 3   | 1   | 6   | 50/50    |
|Naive Bayes        | 3   | 2   | 6   | 50/50    |
|Logistic Regression| 1   | 2   | 7   | 50/50    |
|Linear Regression  | 3   | 2   | 6   | 50/50    |
|SVM- Linear Kernel | 0   | 2   | 6   | 70/30    |
|SVM- RBF Kernel    | 8   | 2   | 1   | 50/50    |
|Gadient Boosting   | 3   | 2   | 6   | 80/20    |
|MLP                | 3   | 2   | 6   | 80/20    |

The most common fold for splits 50/50, 70/30, 80/20 were 3,2,6 respectively. These folds were the most frequent by a landslide in their splits. Our hypothesis for this is since our k-fold cross validation had the shuffle parameter set to true, the data was randomly shuffled and split into fold which could have led to certain folds having a more representative sample of the overall data than others. This difference in representativeness is magnified when you have three splits since different splits will produce different distributions of data for the folds to generate from. Combining this with our aforementioned imbalance class leads to the possible explanation that certain folds may just be performing better due to better distributions of the target. 

## Best Model Selection

### Naive Bayes vs. Logistic Regression

<img width="614" alt="Screenshot 2023-04-23 at 8 57 26 PM" src="https://user-images.githubusercontent.com/101344801/234143389-67f0258b-e476-412a-a22f-d7f13162d3d7.png">

<img width="614" alt="Screenshot 2023-04-23 at 8 58 09 PM" src="https://user-images.githubusercontent.com/101344801/234143415-831fe5a4-ced5-4daf-abbc-1b39fb63a424.png">


To determine the best model we looked at the confusion matrix ratios, f1-scores, and learning curves. We were looking for the model with the most correctly classified dropouts with the least incorrectly classified ones, with a good f1-score, and the best learning curve. It was between Naive Bayes 50/50 split fold 3 and Logistic Regression 50/50 split fold 3. The logistic regression has the better ratio and f1-score, but Naive Bayes appears to have the best learning curve. After graphing these two learning curves side by side, it was easy to see that logistic regression is the better model.
