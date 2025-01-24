# Email Fraud Detection Using Classification

Fraudulent emails are a common method used by fraudsters to deceive individuals into sharing sensitive personal information. These emails often disguise themselves as being from trustworthy sources, tricking recipients into providing critical data under false pretenses.

This project addresses **email fraud detection** as a **classification problem**, utilizing machine learning algorithms to classify emails as either **phished** or **ham** (legitimate). The objective is to develop a robust system with high accuracy while analyzing the impact of various features on classification results.

---

## Why Naive Bayes?

We selected the **Naive Bayes (NB)** classifier due to its simplicity, efficiency, and suitability for email filtering:

- **Simplicity & Speed:** NB is straightforward to implement and computationally efficient.
- **Small Data Friendly:** Performs well even with limited training data.
- **Scalable:** Scales linearly with the number of features and data points.
- **Versatile:** Handles both binary and multi-class classification tasks and works with continuous and discrete data.
- **Insensitive to Irrelevant Features:** Delivers strong performance even with some irrelevant features.
- **Quick Convergence:** Converges faster than discriminative models like Logistic Regression when assumptions hold.

---

## Project Workflow

1. **Download Dataset**: Collected publicly available datasets containing spam (phished) and ham emails.
2. **Preprocessing**:
   - Extracted the subject and body of each email.
   - Concatenated the subject and body as a single text feature for classification.
3. **Data Preparation**:
   - Converted the email data into structured dataframes.
   - Merged and shuffled the spam and ham dataframes.
   - Split the dataset into training (80%) and testing (20%) sets.
4. **Model Training**:
   - Trained a **Naive Bayes classifier** on the training dataset.
5. **Testing and Evaluation**:
   - Classified emails in the test dataset using the trained model.
   - Evaluated the model’s performance to ensure high accuracy.

---

## Key Features of the Dataset

- The dataset consists of **n phished emails** and **m ham emails**.
- Features were extracted to highlight distinctions between legitimate and fraudulent emails.


## Results and Insights

This project demonstrates the effectiveness of the **Naive Bayes classifier** in tackling email fraud detection. It highlights the algorithm's capability to handle classification tasks efficiently, even with small datasets, while providing reliable results.


