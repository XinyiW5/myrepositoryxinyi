# DATA1030: Hands-on data science
## Fall 2023 semester project: Music and Mental Health

    This project focus on the correlations between music taste and self-reported mental health issues. The dataset have 736 points and 31 features, and it is IID and balanced. The data were collected both online and in person through Google Forms and posters, with no restrictions on the participant age and locations. The dataset has missing values in 8 features, including all categorical, ordinal and numerical features. The missing values are dealt with before I train the models. Besides, the age group for the dataset is around twenties, which means the final results may only useful when applying to people at twenties.
    
    The problem is a classification problem with target variable of "Anxiety" level, which is an ordinal feature ranking from '0' to '10', while '0' means 'you barely experience anxiety' and '10' means 'you frequently experience anxiety'.
    
    Five models are used and tuned in the project, they are Logistic Regression, Random Forest, SVC, kNN and XGB models. "Accuracy" is the evaluation metrics. With relatively low validation and test scores for all the five models, kNN model is the best predictive model. 
    
    Finally, with feature importance computation, I concluded that other mental health problems such as "Depression" are related to "Anxiety" a lot. So, the next step to outlook is to look at the relations between music types and other music types. Also, it's better to add more age groups to the dataset so that the results can generalize better. Finally, it can make sure the result accuracy to teach participants how to measure their mental health level next time before asking them to fill our the surveys.


