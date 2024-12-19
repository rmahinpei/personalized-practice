# Leveraging Collaborative Filtering for Personalized Practice in Computer-Based Assessments

Computer-based homework and assessments have become increasingly prevalent in undergraduate STEM courses, offering automatic grading and instant feedback to accommodate large student populations. While randomization features are commonly used to combat collaborative cheating, less attention has been given to leveraging the existing data within online learning systems to personalize question selection based on individual student needs. This experience report explores the potential of collaborative filtering (CF)-based recommender systems to predict students' performance on new, unseen questions using their past scores, thereby offering a pathway to personalized question selection. 

We evaluated six CF models against a baseline model using Dietterich's 5x2 cross-validation method on two datasets from a computer systems course. The models were evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with statistical significance assessed through p-values from paired t-tests and effect sizes quantified by Cohen's d. Our findings indicate that all CF models significantly outperformed the baseline with large effect sizes, with the SVD++ model consistently delivering the most robust results. These results suggest that CF models can indeed predict student performance on unseen questions, enabling personalized question recommendations within online learning systems using existing data. Future research will evaluate the overall student experience with this personalization mechanism through a user study.

We provide public ccess to our [script](https://github.com/rmahinpei/personalized-practice/blob/main/cf_models_evaluation.ipynb) and [datasets]() to enable further exploration and extension of this work by others.
