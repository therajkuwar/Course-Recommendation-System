# Course-Recommendation-System

This project is a course recommendation system that helps users find courses similar to a given course title. By utilizing natural language processing (NLP) techniques, it analyzes the course titles, cleans the text, and generates recommendations based on the similarity between course titles using cosine similarity. The system is built using Python and leverages libraries such as Pandas, Scikit-learn, and CountVectorizer for text processing and similarity calculations.

Features
Input Course Search: Users can input a course title, and the system will recommend similar courses.
Text Cleaning and Preprocessing: Handles stop words, punctuation, and tokenization to prepare text data.
Count Vectorization: Converts course titles into vectors based on word frequency.
Cosine Similarity Calculation: Measures the similarity between course titles to suggest relevant courses.
Top N Recommendations: Displays the most similar courses based on the input course title.
Dataset
The dataset used in this project consists of Udemy course data. Each course contains information such as:

Course Title
Course Category
Subcategory
Price
Rating
Number of Reviews
The course title is the primary attribute used to recommend similar courses.


Technologies Used
Programming Language: Python 3
Libraries:
Pandas: For data loading and manipulation
Scikit-learn: For CountVectorizer and cosine similarity calculation
Numpy: For handling numerical operations
Flask (Optional): To create a web interface for the recommendation system
How the Recommendation System Works
Data Cleaning: The course titles are cleaned by removing stopwords, punctuation, and unnecessary characters to focus only on the relevant keywords.
Vectorization: Using CountVectorizer, course titles are transformed into word frequency vectors.
Cosine Similarity: The cosine similarity is calculated between the input course title vector and all other course title vectors in the dataset.
Recommendations: Courses with the highest cosine similarity scores are selected and displayed as recommendations.
