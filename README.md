## K-Drama Recommendation System

**Overview**

The K-Drama Recommendation System is a project that provides personalized recommendations for Korean dramas (K-Dramas) based on various user-specified criteria such as rating, genre, cast, and other features. The project leverages data preprocessing techniques and similarity calculations to offer accurate and relevant recommendations.

**Features**

Customizable Recommendations: Users can specify the features they are interested in (e.g., Rating, Genre, Cast) to get tailored recommendations.

Data Preprocessing: Handles conversion of string-based columns to vector format for better similarity calculations.
Similarity Calculations: Uses cosine similarity for numeric variables and Jaccard similarity for categorical variables to compute the overall similarity score.

Cast Filtering: Ensures that recommended K-Dramas share at least one of the main cast members with the input K-Drama.
Technologies Used

Python: The primary programming language used for developing the recommendation system.

pandas: For data manipulation and preprocessing.

scikit-learn: For standardization and similarity calculations.

Jupyter Notebook: For developing and running the project interactively.

**Project Structure**

kdrama_recommendation_system.ipynb: Jupyter Notebook containing the project code and explanations.
kdrama.csv: Dataset containing information about various K-Dramas.

**Example**

<img width="790" alt="Screenshot 2024-07-24 at 2 43 45 PM" src="https://github.com/user-attachments/assets/28086521-e41e-4bb4-b773-8936d0f1fa4d">
