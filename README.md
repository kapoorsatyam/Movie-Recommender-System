# 🎥 Movie Recommender System

**Discover Your Next Favorite Film!**  
Our NLP-powered **Movie Recommendation Web App** offers tailored suggestions based on cast, genres, and production companies. With a seamless Streamlit interface, you can:  
- Get personalized movie recommendations.  
- Explore detailed movie descriptions and cast information.  
- Browse a complete list of all available movies.

---

## 🏆 Features

- **Tailored Recommendations:** Find movies similar to your favorites based on tags, genres, and production companies.
- **Detailed Movie Insights:** View descriptions, cast details, and more.
- **All Movies Page:** Browse through the entire movie collection with user-friendly navigation.
- **Interactive Interface:** Built with Streamlit for an engaging and intuitive user experience.

---

## 🚀 Technologies Used

- **Python**  
- **Natural Language Processing (NLP)**  
- **Pandas and NumPy** for data manipulation.  
- **NLTK** for stemming and text preprocessing.  
- **Scikit-learn** for cosine similarity and feature extraction.  
- **Streamlit** for creating an interactive web app.  

---

## 🛠 How It Works

1. **Data Processing:**  
   - Combines movie features like overview, genres, cast, keywords, and director into a single textual representation (`tags`).  
   - Applies stemming and vectorization to generate a **bag-of-words model**.  

2. **Similarity Calculation:**  
   - Utilizes **cosine similarity** to measure how closely related movies are.  

3. **Interactive Web App:**  
   - Users can search for a movie, get recommendations, and explore additional details.  

---

## 📸 Sample Application Screenshots

### **Movie Recommendations**  
Discover movies similar to your favorites with a single click!  
![Recommended Movies](https://github.com/kapoorsatyam/Movie-Recommender-System/blob/main/Assets/RecommendedMovies.png)

---

### **Detailed Movie Description**  
Dive deeper into the details of a selected movie, including its plot and cast.  
![Movie Description](https://github.com/kapoorsatyam/Movie-Recommender-System/blob/main/Assets/movieDescription.png)  
![Movie Cast](https://github.com/kapoorsatyam/Movie-Recommender-System/blob/main/Assets/Cast.png)

---

### **All Movies Page**  
Easily browse through a complete list of movies with intuitive navigation.  
![All Movies Page](https://github.com/kapoorsatyam/Movie-Recommender-System/blob/main/Assets/allMovies.png)

---

## 🌟 Future Enhancements

###  **Content Filtering**
Add additional filters like:
- Release Year
- Language
- Runtime

### **Enhanced UI/UX**
Make the interface more engaging by introducing:
- Smooth animations
- Improved visual aesthetics
- Dark mode
