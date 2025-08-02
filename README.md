# 🎬 Movie Recommendation System — Collaborative & Content-Based Models

An end-to-end hybrid movie recommendation system utilizing Collaborative Filtering, Content-Based Filtering, and Matrix Factorization to predict user preferences and provide tailored movie suggestions.

## 🚀 Project Overview
- Built **User-Based and Item-Based Collaborative Filtering models** using cosine similarity and Pearson correlation.
- Developed **Content-Based Recommender** using TF-IDF vectors derived from movie metadata.
- Applied **Matrix Factorization (SVD)** for latent factor modeling to address sparsity.
- Combined Collaborative and Content-Based models to build a Hybrid Recommendation System.
- Evaluated model effectiveness with **Precision@K, Recall@K, RMSE**.
- Visualized recommendation results using similarity heatmaps and ranked lists.

## 🛠️ Tech Stack & Tools
- **Python (Pandas, NumPy, Scikit-learn, Surprise Library)**
- **Natural Language Processing (TF-IDF Vectorization)**
- **Matplotlib, Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development Environment)

## 📊 Key Components
| Component                              | Description                                                             |
|----------------------------------------|-------------------------------------------------------------------------|
| Collaborative Filtering (User & Item)  | Based on user-user and item-item similarity                             |
| Content-Based Filtering                | Movie metadata-based recommendations (genre, keywords)                  |
| Matrix Factorization (SVD)             | Decomposition of user-item utility matrix for latent factor modeling    |
| Evaluation Metrics                     | Precision@K, Recall@K, RMSE                                             |
| Hybrid Recommendation Engine           | Combines collaborative and content-based strategies                     |
| Business Use Cases                     | OTT platforms, E-commerce product suggestions, personalized newsletters |

## 📈 Results & Insights
- Achieved high Precision@K for top-5 movie recommendations.
- SVD improved recommendation accuracy on sparse datasets.
- Enhanced recommendation diversity and personalization by hybridizing approaches.
- Proposed deployment strategies for integrating the recommendation engine with OTT platforms to increase watch-time and user engagement.

## 🧑‍💼 Business Applications
- OTT Platform Content Recommendations
- Personalized User Experience for Streaming Services
- Movie Review Platforms with Tailored Suggestions
- Cross-Selling Related Content (TV shows, Web series, Documentaries)

## 👨‍💻 Contributors
- Manish Kumar Das (Project Lead)

## 🏁 How to Run Locally
1. Clone the repository.
2. Install required packages: `pip install -r requirements.txt`
3. Load datasets into the `/data` directory.
4. Execute Jupyter Notebooks to train and evaluate models.
5. Visualize recommendation outputs and ranked movie lists.
