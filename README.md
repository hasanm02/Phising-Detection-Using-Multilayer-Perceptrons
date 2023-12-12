# Phising-Detection-Using-Multilayer-Perceptrons

This project aims to develop a phishing detection model using Multilayer Perceptrons (MLP). The model is trained on a dataset containing various website attributes and labels indicating whether a website is a phishing site or not. The project utilizes Python, along with libraries like NumPy, Pandas, and Scikit-learn, to preprocess data, train the model, and evaluate its performance.

### Dependencies 
* Python
* NumPy
* Pandas
* Scikit-Learn

### Dataset 
The dataset includes a mix of legitimate and phishing website instances, each characterized by unique features aimed at determining the legitimacy of a website. It includes a mix of legitimate and phishing website instances, each characterized by unique features aimed at determining the legitimacy of a website. The dataset comprises 27,998 legitimate website instances (labeled as 0) and 30,647 phishing website instances (labeled as 1), featuring a total of 111 distinct attributes.

### Features of the Project
1. Data Preprocessing: Loading the dataset, checking for null values, and understanding its structure.
2. Feature Selection: Separating website attributes as features and 'phishing' as the target variable.
3. Data Splitting: A 70/30 train/test split for model training and evaluation.
4. Model Training: Implementing and training the MLP model using Scikit-learn's MLPClassifier.
5. Model Evaluation: Assessing the model's accuracy on both training and test data.

### How to Run the Project
1. Install Libraries: Ensure all required Python libraries are installed.
2. Load the Dataset: Modify the dataset path according to your setup.
3. Run the Script: Execute the script to train and evaluate the model.

### Code Overview
* Data Loading: The dataset is loaded into a Pandas DataFrame for manipulation.
* Data Inspection: Initial exploration includes checking data types, shape, and null values.
* Features and Target Separation: Features are extracted from the target variable.
![Screenshot 2023-12-12 123507](https://github.com/hasanm02/Phising-Detection-Using-Multilayer-Perceptrons/assets/133940432/22e65dcc-c733-455f-a39c-e4ba0896894d)

* Dataset Splitting: The dataset is split into training and testing sets.
![Screenshot 2023-12-12 123639](https://github.com/hasanm02/Phising-Detection-Using-Multilayer-Perceptrons/assets/133940432/15dbbc14-de46-44b6-bbbf-093ae247d668)

* MLP Model: An MLP model with adjusted parameters (50, 100, 150 hidden layers; 500 iterations, alpha set to 0.01) is trained.
![Screenshot 2023-12-12 123525](https://github.com/hasanm02/Phising-Detection-Using-Multilayer-Perceptrons/assets/133940432/b3ffb337-027b-4127-b6d2-9875d5a45719)

* Prediction and Evaluation: Predictions are made on both training and test datasets, and accuracy is calculated.
![Screenshot 2023-12-12 123531](https://github.com/hasanm02/Phising-Detection-Using-Multilayer-Perceptrons/assets/133940432/beec7376-a864-4c44-a292-beed151a65ff)

### Results
The MLP model consistently demonstrates high accuracy, exceeding 85% in distinguishing between legitimate and phishing websites.

### Future Enhancements 
* Experimenting with different MLP configurations and hyperparameters.
* Incorporating additional features and advanced data preprocessing techniques.
* Comparing MLP with other machine learning algorithms for phishing detection.


