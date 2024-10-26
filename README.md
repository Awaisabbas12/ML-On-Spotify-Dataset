<h1>Objective</h1>
    <p>The goal is to predict whether a song will be popular based on audio features such as danceability, energy, and loudness using classification techniques.</p>

<h1>Exploratory Data Analysis (EDA)</h>

    <p>![image](https://github.com/user-attachments/assets/a1c89947-b03c-4aeb-9891-33ed3b46fc73)</p>
    
   <p> ![image](https://github.com/user-attachments/assets/2ba1a175-b818-4b13-a0da-0c8c2dad8b1f)</p>
   
    ![image](https://github.com/user-attachments/assets/0f519719-c0d7-4246-ae79-4e22a80aa502)</p>



<h1>Modeling</h1>
    <p>Based on popularity, I used classification techniques to predict song popularity. I tried several machine learning models, including Logistic Regression, Random Forest, Decision Tree, SVM, and Gradient Boosting. Among these models, Random Forest achieved the highest accuracy at 99% for the Spotify dataset.</p>

<h1>Model Evaluation</h1>
    <p>The target classes were imbalanced, which can lead to bias in machine learning models—a common issue known as class imbalance. To address this, I used resampling techniques. After applying resampling, I evaluated the models using metrics such as the confusion matrix and classification report. The Random Forest model continued to perform best after balancing the classes.</p>
