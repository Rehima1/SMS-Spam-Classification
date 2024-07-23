# SMS-Spam-Classification


This project demonstrates the use of various machine learning models to classify text messages as either spam or ham (not spam). The models compared include Logistic Regression, Support Vector Classifier (SVC), Multinomial, Naive Bayes, Decision Tree Classifier, K-Nearest Neighbors (KNN), and Random Forest Classifier. The performance of these models is evaluated using accuracy as the metric.

## Project Structure

- [spam_ham_classification.ipynb](https://github.com/Rehima1/SMS-Spam-Classification/blob/main/spam_ham_classification.ipynb): The main jupyter notebook that includes the data processing, model training, evaluation, and visualization.
- `README.md`: Project documentation.

## Data

The dataset consists of sample text messages labeled as 'spam' or 'ham'. Here's a preview of the data:

| Spam or Ham | Text |
|-------------|------|
| ham         | Go until jurong point, crazy.. Available only ... |
| ham         | Ok lar... Joking wif u oni... |
| spam        | Free entry in 2 a wkly comp to win FA Cup fina... |
| ham         | U dun say so early hor... U c already then say... |
| ham         | Nah I don't think he goes to usf, he lives aro... |

<img width="500" alt="image" src="https://github.com/user-attachments/assets/74662192-35fc-46e2-9090-d5ceb55db77c">

## Exploratory Data Analysis (EDA)
During the EDA process, I examine the dataset to understand its structure, identify patterns, and uncover insights. Here are a few steps I performed:
Distribution of Spam vs. Ham Messages: I visualize the proportion of spam and ham messages.

![image](https://github.com/user-attachments/assets/8fb84656-276f-4a04-bea7-1d6e32609bdb)
![image](https://github.com/user-attachments/assets/56f92038-fcc8-4e1f-a0d3-189840c94450)
![image](https://github.com/user-attachments/assets/23cd8fd9-ed84-4360-9b24-084eb7d14de2)
![image](https://github.com/user-attachments/assets/a224cc50-dfb5-4994-9f6d-4e2ea8e0b73b)
![image](https://github.com/user-attachments/assets/0a61f9da-a3f4-43bc-aea7-f52a2d332162)
![image](https://github.com/user-attachments/assets/6fd3b3ed-46f3-40f6-b737-82a414707820)


## Models Compared

1. Logistic Regression
2. Support Vector Classifier (SVC)
3. Multinomial Naive Bayes
4. Decision Tree Classifier
5. K-Nearest Neighbors (KNN)
6. Random Forest Classifier

## Results

The accuracy of each models are compared and visualized using a bar plot. Below is the accuracy table:
<img width="800" alt="image" src="https://github.com/user-attachments/assets/455d259a-3bdb-4ad5-8a4d-e227c29e22ab">
![image](https://github.com/user-attachments/assets/8d51de0d-49c4-489a-8b4c-135b04b9ed9b)


