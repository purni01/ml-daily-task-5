# ml-daily-task-5

# Task 5 – Decision Trees & Random Forests

## 📌 Objective


Tools & Libraries

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (sklearn)



 What I Did

1. Loaded and explored the dataset to understand the structure and features.
2. Trained a Decision Tree Classifier on the data and made predictions.
3. Visualized the decision tree using `plot_tree()` from sklearn.
4. Controlled overfitting by setting `max_depth` and trained a pruned decision tree.
5. Trained a Random Forest Classifier and compared its accuracy with the decision tree.
6. Used feature importance to find which columns influenced the predictions most.
7. Evaluated model performance using 5-fold cross-validation for better reliability.


 Results

 Model                    | Accuracy        
--------------------------|-----------------
 Decision Tree (default)  | ~93%            
 Pruned Decision Tree     | ~85%            
 Random Forest            | ~97-98%         
 Cross-Validation Score   | ~96% average    


