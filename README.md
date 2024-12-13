# Tabular Data Classification with Differentiable Decision Tree

In this notebook, we will conduct classification tasks using four distinct datasets: the Iris dataset, the Pima Indians Diabetes Database, the Breast Cancer Wisconsin (Diagnostic) dataset, and the Adult Dataset. Each dataset represents unique challenges in classification, and our goal is to apply deep learning-based methods to explore and solve these tasks.

- Iris Dataset: This classic dataset consists of measurements from three different Iris species. We'll classify samples into one of these three species based on four features: sepal length, sepal width, petal length, and petal width.

- Pima Indians Diabetes Database: This dataset contains diagnostic data collected from Pima Indian women, with the objective of predicting the onset of diabetes based on various health measurements, such as blood glucose level, body mass index, age, and more.

- Breast Cancer Wisconsin (Diagnostic) Dataset: Here, the task is to classify tumor samples as benign or malignant based on features computed from cell nuclei present in breast mass images. The dataset provides insights into texture, area, smoothness, and other characteristics critical for accurate diagnostics.

- Adult Dataset: This dataset, commonly used in income prediction tasks, includes features such as age, work class, education, occupation, and more. Our goal is to predict whether a person's income exceeds $50,000 per year, based on these socioeconomic factors.

For each dataset, we will use a primary classification method called the Differentiable Decision Tree. This deep learning technique combines the interpretability of traditional decision trees with the flexibility of gradient-based learning, making it well-suited for diverse data types and complex patterns.

In addition to preprocessing each dataset for model compatibility, we will try to use the data augmentation techniques of Mixup and also various regularization method such as and L2 normalization, to enhance model robustness and prevent overfitting. These augmentations aim to create more diverse training data representations, allowing the model to generalize better across unseen examples.

We will preprocess each dataset to ensure compatibility with the Differentiable Decision Tree model, explore underlying data distributions, and adjust hyperparameters to maximize performance. The evaluation process will involve accuracy, macro-F1 score, and a confusion matrix to thoroughly assess model performance across classes. Additionally, we will apply k-fold cross-validation to ensure the model generalizes well across different subsets of the data, promoting robust, reliable results.




