# Movie_Recommendation_System

<p><strong>Description:</strong> 
  
Machine Learning (ML) a subset of Artificial Intelligence (AI), enables systems to learn from data and make predictions. With the rapid growth of the entertainment industry, users often face difficulty in finding content aligned with their interests. <br>
To solve this, a movie recommendation system is designed using collaborative filtering, content-based filtering and hybrid methods. Collaborative filtering suggests movies based on similar user preferences, while content-based filtering uses metadata like genre, cast, and director to recommend related titles. <br>
Techniques such as text vectorization and cosine similarity are applied to assess the similarity between movies. Users input a favorite movie and the system generates personalized suggestions by comparing it with the dataset.
This solution offers a scalable and accurate way to enhance user experience through intelligent recommendations powered by ML.</p>

<hr>

<h2><strong> 1. Dataset Acquisition & Preprocessing </strong> </h2>
<p>
  This system utilizes publicly available datasets from <strong> Kaggle - TMDB (The Movie Database)</strong>:
</p>
<ul>
  <li><code>tmdb_5000_movies.csv</code></li>
  <li><code>tmdb_5000_credits.csv</code></li>
</ul>
<p>
  Real-world datasets often contain noisy or inconsistent data. A thorough preprocessing pipeline is implemented to handle:
</p>
<ul> 
  <li> Incorrect </li>
  <li>Missing values</li>
  <li>Data inconsistencies</li>
  <li>Duplicate data </li>
</ul>
<p>
  This ensures the data is clean, structured and ready for downstream machine learning tasks.
</p>

<hr>

<h2> <strong> 2. Backend Development – Data Processing & Recommendation Logic </strong> </h2>

<p>The backend is powered by <strong>Jupyter Notebook</strong> (also compatible with Google Colab). It performs:</p>
<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Feature Engineering (title, overview, cast, genres, keywords)</li>
  <li>Content-Based Filtering using <strong> Cosine Similarity </strong></li>
</ul>
<p>
  The processed data and trained recommendation logic are serialized for fast loading:
</p>
<ul>
  <li><code>movies.pkl</code></li>
  <li><code>movies_dict.pkl</code></li>
  <li><code>similarity.pkl</code></li>
</ul>

<hr>

<h2> <strong> 3. Frontend Development – Web Application Interface </strong> </h2>
<p>
  The frontend is developed using <strong>PyCharm</strong> and built on the <strong>Streamlit</strong> framework for a smooth and interactive UI.
</p>
<ul>
  <li>Loads pickled files for quick recommendations</li>
  <li>Integrates Kaggle API to dynamically fetch movie posters</li>
  <li>Search bar to input movie title and receive recommendations instantly</li>
</ul>
<p><em> Note: Kaggle API key is required for poster access </em></p>

<hr>

<h2><strong> 4. Recommendation Engine Highlights </strong> </h2>
<p>
  The engine analyzes multiple content attributes to generate accurate and relevant suggestions:
</p>
<ul>
  <li>User preferences</li>
  <li> Personalized recommendations </li>
  <li>Genres, cast and keywords</li>
</ul>
<p>
  This enhances movie discoverability and provides a personalized experience, bridging the gap between users and thousands of available titles.
</p>

<hr>

<h2> <strong> Outcome </strong></h2>
<p>
  The result is a highly engaging and responsive movie recommendation platform that blends data science and user-centered design to deliver precise and satisfying movie suggestions.
</p>

<hr>
