![Static Badge](https://img.shields.io/badge/Topic-Data_Science_and_Machine_Learning-purple) ![Static Badge](https://img.shields.io/badge/Project_Status-Complete-brightgreen) 

## Movie Recommendation System

### Overview

This project explores and implements three primary recommendation techniques for movies: 
Popularity-Based Filtering, Collaborative Filtering, and Content-Based Filtering. 
Each approach offers distinct advantages and caters to different user preferences.

**Popularity-Based Filtering**

* **Description:** Recommends movies based on overall popularity, considering metrics like vote count and average rating.
* **Methodology:** Calculates a weighted average of user ratings and applies a threshold to vote count for consistency.
* **Dependencies:** pandas

**Collaborative Filtering**

* **Description:** Recommends movies based on user behavior and similarities with other users.
* **Methodology:** Employs the Surprise library and scikit-learn's SVD algorithm for model training and evaluation using RMSE and MSE metrics.
* **Dependencies:** scikit-surprise

**Content-Based Filtering**

* **Description:** Recommends movies based on the content of the movie (e.g., genre, plot).
* **Methodology:** Creates a similarity matrix using movie descriptions and the sklearn library's TfidfVectorizer and linear_kernel.
* **Dependencies:** scikit-learn

### Usage

1. **Clone the Repository:** 

```bash
git clone https://github.com/davedepo/app19-ds-movie-rec-sys.git
```

2. **Install Dependencies:**

   - To set up your environment for the movie recommendation system, follow these steps:

        1. **Python Version:** Make sure you have Python 3.12 installed on your system.
  
        2. **Choose a Jupyter Environment:**
    
           - **JupyterLab:** If you prefer using JupyterLab, install it using `pip install jupyterlab`.

           - **Anaconda Jupyter Notebook:** If you're using Anaconda, launch Jupyter Notebook using `jupyter notebook`.

           - **Google Colab:** Alternatively, you can use Google Colab directly in your browser.
        
        3. **Data Science & ML Libraries:**

           - Install the necessary libraries using the following command:
            ```bash
            pip install pandas scikit-surprise scikit-learn
            ```
       Now you're all set to run the recommendation system! Feel free to explore the different methods and enjoy personalized movie recommendations. 🎬🍿


3. **Run Notebooks:** Execute the provided Jupyter Notebooks to explore each recommendation technique.

   - Popularity-Based-Filtering.ipynb
   - Collaborative-Based-Filtering.ipynb
   - Content-Based-Filtering.ipynb

_**Note:** This project utilizes Jupyter Notebooks for interactive development and analysis._

### Additional Considerations

* **Data:** The project assumes access to a movie dataset containing relevant information (e.g., movie titles, genres, user ratings).
* **Evaluation:** To assess the performance of different recommendation techniques, consider using metrics like precision, recall, and F1-score.
* **Hybrid Approaches:** Explore combining multiple recommendation techniques for enhanced results.

By understanding the core concepts and implementation details, you can leverage this project as a foundation for building more sophisticated recommendation systems.

### Authors and Acknowledgment

- **Udemy**: For providing a platform to learn.
- **Ardit Sulce** (https://github.com/arditsulceteaching) : Created a code-along learning module for building this app.
- **Python Developers & Community**: Provided extensive documentation and examples to support this learning.
- **OpenAI, Copilot and Gemini**: For providing support, assistance, and encouragement in this learning journey.
- **PyCharm Team:** Making it easy to learn with all embedded features for beginners.
