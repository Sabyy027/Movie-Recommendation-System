🎥 Movie Recommendation System 
This project is a Movie Recommendation System that recommends movies based on a selected title. It uses cosine similarity to identify similar movies and features an interactive UI built with Streamlit. The dataset is preprocessed with pandas, and CountVectorizer is used for vectorization. 

Features 
- Content-Based Recommendations: Suggests movies based on overviews and genres using cosine similarity. 
- Dataset Processing: Preprocessed a dataset of 10,000 movies with attributes like title, overview, and genre. 
- Movie Posters: Fetches dynamic posters using the TMDb API. 
- Interactive UI: User-friendly interface to select a movie and view recommendations. 
- Efficient Data Management: Uses Pickle to store preprocessed data and similarity matrices. 

Skills Learned
- Data Preprocessing: Cleaned data, handled null values, and combined features using pandas. 
- Machine Learning: Used CountVectorizer for text vectorization and cosine similarity for recommendations. 
- Streamlit Development: Built an interactive web application. 
- API Integration: Worked with the TMDb API to enhance the UI with movie posters. 
- Data Serialization: Leveraged Pickle to store large datasets and models. 

Tech Stack
- Python: Core programming language. 
- Pandas: For data manipulation. 
- Scikit-learn: For vectorization and similarity computation. 
- Streamlit: To create an engaging front-end. 
- TMDb API: To fetch movie metadata and posters. 
- Pickle: For efficient data storage. 

How It Works 
1. Dataset Preparation: Combined overviews and genres into a "tags" column and vectorized using CountVectorizer. 
2. Similarity Computation: Calculated cosine similarity between movies. 
3. Recommendations: Generated top 5 similar movies for a selected title. 
4. User Interaction: Streamlit app displays recommendations with posters in a clean layout.🎥 Movie Recommendation System This project is a Movie Recommendation System that recommends movies based on a selected title. It uses cosine similarity to identify similar movies and features an interactive UI built with Streamlit. The dataset is preprocessed with pandas, and CountVectorizer is used for vectorization. Features - Content-Based Recommendations: Suggests movies based on overviews and genres using cosine similarity. - Dataset Processing: Preprocessed a dataset of 10,000 movies with attributes like title, overview, and genre. - Movie Posters: Fetches dynamic posters using the TMDb API. - Interactive UI: User-friendly interface to select a movie and view recommendations. - Efficient Data Management: Uses Pickle to store preprocessed data and similarity matrices. Skills Learned - Data Preprocessing: Cleaned data, handled null values, and combined features using pandas. - Machine Learning: Used CountVectorizer for text vectorization and cosine similarity for recommendations. - Streamlit Development: Built an interactive web application. - API Integration: Worked with the TMDb API to enhance the UI with movie posters. - Data Serialization: Leveraged Pickle to store large datasets and models. Tech Stack - Python: Core programming language. - Pandas: For data manipulation. - Scikit-learn: For vectorization and similarity computation. - Streamlit: To create an engaging front-end. - TMDb API: To fetch movie metadata and posters. - Pickle: For efficient data storage. How It Works 1. Dataset Preparation: Combined overviews and genres into a "tags" column and vectorized using CountVectorizer. 2. Similarity Computation: Calculated cosine similarity between movies. 3. Recommendations: Generated top 5 similar movies for a selected title. 4. User Interaction: Streamlit app displays recommendations with posters in a clean layout.
Skills: Data Analysis · Machine Learning · streamlit · Python (Programming Language) · Data Visualization
