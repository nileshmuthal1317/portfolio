
# Data Science Portfolio 

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Machine Learning Projects

**Title: BoomBikes shared bikes**
- **Problem Statement:** Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.
- **Steps Followed:**
  - Read and understood the data for finding out missing values.
  - Converted the datatype of dteday column to datetime.
  - Encoding the Labels & Visualization.
  - Visualizing the Relationship among variables.
  - Dealing With Categorical Variables.
  - Splits the Data into Training and Testing Sets.
  - Rescaling the Features.
  - Built a linear model.
  - Residual Analysis of the train data.
  - Making Predictions.
  - Model Evaluation.
  - Gained an accuracy level of 80%.
- **GitHub Link:** [GitHub Repository](https://github.com/saurabhharak/BoomBike.git)

**Title: House prices prediction (Ridge and Lasso Regression)**
- **Problem Statement:** Build a regularized regression model to understand the most important variables to predict the house prices in Australia.
- **Steps Followed:**
  - Data Understanding and Exploration.
  - Outlier Treatment.
  - Checking the Correlation between the variables.
  - Data Cleaning.
  - Null value treatment.
  - Dummy Variable.
  - Data Preparation for model building.
  - Model Building and Evaluation (Ridge and Lasso Regression).
  - Export Data into Excel sheet.
- **GitHub Link:** [GitHub Repository](https://github.com/saurabhharak/House-Price-Prediction)

**Title: Telecom Churn (Linear Regression)**
- **Problem Statement:** Built a ML model to predict churn for a leading telecom operator in South-East Asia.
- **Steps Followed:**
  - Loading Modules & Libraries.
  - Loading dataset.
  - Data Preparation.
  - Filter high-value customers.
  - EDA- Pre-process data (convert columns to appropriate formats, handle missing values, etc.).
  - Stats for potential Categorical datatype columns.
  - Conduct appropriate exploratory analysis to extract useful insights (whether directly useful for business or for eventual modelling/feature engineering).
  - Replacing NAN values.
  - PCA: Principal Component Analysis.
  - Linear Regression Accuracy: 0.88.
  
**Title: Melanoma Detection (CNN)**
- **Problem Statement:** Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- **Steps Followed:**
  - Implementing a multiclass classification model on Skin cancer dataset using a custom model in Tensorflow.
  - Load the data.
  - EDA.
  - Up sampling function for imbalanced data.
  - Down sampling function for imbalanced data.
  - Get the class indices.
  - Create the model.
  - Define the model architecture.
  - Compile the model.
  - Train the model.
  - Test model.
  - RocAuc Score.
  - Performance curves.
  - Confusion Matrix.
- **GitHub Link:** [GitHub Repository](https://github.com/saurabhharak/Melanoma-Detection)

**Title: Drone Detection Model**
- **Technology Stack:** CNN (YOLOv3), Python, OpenCV, NumPy
- **Problem Statement:** Develop a dynamic Drone Detection Model for defense applications, utilizing machine learning techniques and PTZ Camera & sensors. The objective is to detect drones and integrate the system with jammers or other hard kill systems. The model should be cost-effective and enhance the performance of jammer systems.
- **Steps Followed:**
  - Conducted exhaustive research on Drone Detection and Neutralization in the Defense sector.
  - Collected drone image data from different aggregators through web scraping.
  - Formulated detailed datasets for recordkeeping.
  - Designed and developed a Drone Detection System using YOLOv3 (CNN) in Python with OpenCV and NumPy.
  - Integrated PTZ Camera & sensors into the detection system.
  - Minimized the cost of the PTZ system by one third compared to other solutions.
  - Implemented the Drone Detection System, coupled with jammers or other hard kill systems.
  - Evaluated the performance of the Drone Detection System and found a 35% enhancement in jammer system performance.

**Title: Gesture recognition**
- **Problem Statement:** Build a 3D Conv model that will be able to predict the 5 gestures correctly.
- **Steps Followed:**
  - Loading Modules & Libraries.
  - Generator.
  - Generator Validation.
  - Model Building.
  - Base Model.
  - Model Callbacks Setup.
  - Test Batch Size & Frames.
  - Hyperparameters tuning.
  - Trying different models.
  - Max. Training Accuracy 1.0.
  - Max. Validation Accuracy 0.875.

**Title: Automatic Ticket Classification (NLP)**
- **Problem Statement:** Create a model that can automatically classify customer complaints based on the products and services that the ticket mentions.
- **Steps Followed:**
  - Text in Description is pre-processed by removing unwanted characters and words. Some descriptions are given in other languages which are translated to English internally.
  - Stop words are removed, and all the words are lemmatized.
  - With this pre-processed description, the words in the corpus are tokenized, and embeddings were created with word2vec. Embedding was also generated with glove.
  - Different NLP algorithms were tried out - RNN, LSTM, GRU, Traditional ML algorithms such as Random Forest and SVM.
  - Model can classify the IT tickets with 91.24% accuracy.

**Title: Bank Note Authentication Using Random Forest Algorithm**
   - **Project Description:** The aim of this project is to determine the authenticity of bank notes. Using certain features such as variance, skewness, curtsies, and entropy, all of the features are fed into the Random Forest algorithm, and the model determines whether the note is authenticated or not. This algorithm has a 90% accuracy rate.
   - **Front End:** Python, Flask
   - **Backend:** Python, Flask, Pickle, pandas, numpy, sklearn
   - **Key Role:**
     - UI Design.
     - Data Cleaning Features Selection.
     - Model Creation and Deployment.
   - **Live project link:** [GitHub Repository](https://github.com/saurabhharak/Random-Forest-Algorithm)

**Title: Chances of Surviving The Titanic, which sank in the Atlantic Ocean**
   - **Project Description:** To determine the likelihood of survival, I developed a logistic regression algorithm that takes into account age, gender, passenger status, and other variables. I used various graphs to explain findings to help people understand why the columns are important. I pick a column and train the model based on its output or significance. The model's accuracy is 77 percent.
   - **Front End:** Python
   - **Backend:** Python, pandas, numpy, seaborn, math, matplotlib, sklearn
   - **Key Role:**
     - Data Cleaning Features Selection.
     - Model Creation and Deployment.
   - **Live project link:** [GitHub Repository](https://github.com/saurabhharak/Logistic-Regression-)

## Full Stack Developer Projects

**Title: ERP System**
   - **Project Description:** This is the ERP application that assists vegetable companies of all types in more ways than one. For busy vegetable dealers, this application provides accounting, staff management, transportation information, costs, import-export details, mobile message billing, and several other features.
   - **Front End:** Kivy
   - **Backend:** Python
   - **Key Role:**
     - UI Design.
     - Client Communication for specification.
     - Core functionality development.
     - Deployment
   - **Live project link:** [GitHub Repository](https://github.com/saurabhharak/)


**Title: Breath Analyser Web Applications**
- **Technology Stack:** Python, Django, HTML, CSS, Ajax, Heroku
- **Problem Statement:** Create a web application for Breath Analyzer to track user information and results, allowing CRUD operations and providing a user-friendly interface. The application should be designed to manage user interactions efficiently and use AJAX for seamless data updates without reloading the entire page. The application will use Django Web Framework and MySQL database for data storage.
- **Steps Followed:**
  - Participated in the Software Development Life Cycle (SDLC), including requirements gathering, analysis, detailed design, development, system testing, and user acceptance testing.
  - Developed Create, Read, Update, and Delete (CRUD) methods in Active Record.
  - Designed the front-end and back-end modules using Python with Django Web Framework.
  - Created user interactive web pages using HTML, JavaScript, and CSS for a better appearance and user experience.
  - Implemented AJAX to update small portions of web pages through server requests without full page reloads.
  - Managed code versioning using GitHub and handled deployment to staging and production servers.
  - Utilized MySQL database for handling simple queries.
  - Deployed the web application using Heroku.

