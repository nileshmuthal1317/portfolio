
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



**Title: Import Export Data**
- **Technology Stack:** Python, pandas, wasabi, ThreadPoolExecutor, boto3
- **Problem Statement:** Develop an ETL (Extract, Transform, Load) pipeline to extract import-export data from the Trade Statistics portal of the Ministry of Commerce and Industry, Government of India. Create a large dataset spanning 16 years with monthly trade data at the country level, totaling over 100 GB. Utilize Python programming language and pandas library for data manipulation and preparation during the ETL process.
- **Steps Followed:**
  - Applied ETL techniques to extract data from the Trade Statistics portal.
  - Created a large import-export dataset from scratch, spanning 16 years and consisting of over 100 GB of monthly trade data at the country level.
  - Used Python programming language and pandas library for data manipulation, cleaning, and preparation.
  - Executed several steps during the ETL process, including data extraction, cleaning, transformation, and loading.
  - Implemented the ThreadPoolExecutor and multiprocessing library to parallelize data processing tasks, significantly reducing execution time.
  - The resulting dataset is valuable for analyzing trade patterns, identifying market opportunities, and monitoring trade policy changes.
  - Successful completion of the project demonstrates skills in data manipulation, ETL processes, and handling large volumes of data.

**Title: Real-Time Stock Market Data with Kafka**
- **Technology Stack:** Python, AWS, Apache Kafka, Glue, Athena, SQL
- **Problem Statement:** As a Data Engineer, develop a real-time stock market data system using Python and Apache Kafka. Implement data acquisition, processing, and analysis by leveraging AWS services like Glue and Athena. Enable real-time data computations and visualization using SQL queries and streaming frameworks. Ensure efficient and reliable data processing through performance optimization and error handling.
- **Project Overview:**
  - Developed a real-time stock market data system using Python and Apache Kafka.
  - Utilized AWS services like Glue and Athena for data acquisition, processing, and analysis.
  - Enabled real-time data computations and visualization through SQL queries and streaming frameworks.
  - Ensured efficient and reliable data processing by implementing performance optimization techniques and robust error handling.

**Title: MinDepExpScrapper**
- **Technology Stack:** Python, pandas, Camelot
- **Problem Statement:** Create a data extraction and preprocessing pipeline using Python and Camelot to extract expenditure data from Ministries and Departments in PDF format. Preprocess the data using pandas and store it in CSV format. Perform data transformation by reshaping and aggregating the data to create a comprehensive and structured database.
- **Steps Followed:**
  - Used Camelot and pandas to extract expenditure data from Ministries and Departments in PDF format.
  - Preprocessed the extracted data using pandas and stored it in CSV format.
  - Performed data transformation by using pandas' melt and pivot functions to reshape the data into long and wide formats.
  - Aggregated the data to create a comprehensive and structured database.


**Title: PMAY Data Scrapper**
- **Technology Stack:** Python, pandas, wasabi, ThreadPoolExecutor, selenium, boto3
- **Problem Statement:** As a Data Engineer for the PMAY Data Scrapper project, the goal was to automate the data acquisition and processing tasks for the Pradhan Mantri Awas Yojana (PMAY) using various Python libraries such as pandas, selenium, wasabi, ThreadPoolExecutor, and boto3. The responsibilities included automating the login process, extracting tokens, designing a logging mechanism, fetching data for specific cities, creating data frames, parallelizing data acquisition, converting data to CSV format, uploading files to S3, and following best practices for software development.
- **Steps Followed:**
  - Automated the login process and token extraction for accessing the PMAY data.
  - Designed and implemented a logging mechanism to track the data scraping process.
  - Developed data acquisition methods to fetch data for specific cities from the PMAY platform.
  - Utilized pandas library to create data frames for organizing and manipulating the acquired data.
  - Implemented ThreadPoolExecutor to parallelize data acquisition tasks, optimizing the data scraping process.
  - Converted the acquired data to CSV format for further analysis and storage.
  - Utilized boto3 library to upload the processed data files to the Wasabi storage platform.
  - Followed best practices for software development to ensure code quality and maintainability throughout the project.


