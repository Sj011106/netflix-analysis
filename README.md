📊 Netflix Data Analysis
<div align="justify"> This project analyzes a Netflix dataset containing movie details and applies **Exploratory Data Analysis (EDA)**, **Regression Modeling**, and a **Recommendation System** to understand what influences movie ratings and how to suggest similar content. </div>
📂 Dataset
<div align="justify"> The dataset includes the following features: - **Release_Date** – Date when the movie was released - **Title** – Name of the movie - **Overview** – Short description of the movie - **Popularity** – Popularity score - **Vote_Count** – Number of audience votes - **Vote_Average** – Average rating given by viewers - **Original_Language** – Language of release - **Genre** – Movie genres - **Poster_URL** – Movie poster link </div>
🔍 Exploratory Data Analysis (EDA)
<div align="justify"> - Distribution of movies across years and genres - Identification of most popular genres - Trends in popularity scores over time - Relationship between vote count and ratings

📈 Visualizations were created to highlight patterns in release trends and genre distributions.

</div>
📈 Regression Analysis
<div align="justify"> A **Linear Regression model** was developed to predict a movie’s **average rating (Vote_Average)** based on: - Popularity - Vote Count - Genre - Release Year
Key Results

Popularity and vote count are strong predictors of higher ratings.

Genre has an impact but is less influential compared to popularity.

Recent movies generally attract higher popularity scores.

</div>
🎬 Recommendation System
<div align="justify"> A **content-based recommendation system** was built using **TuriCreate**, with the following approaches: - **From Overview** → Text similarity of movie descriptions - **From Genres** → Categorical similarity - **Combined Approach** → Merging overview + genre features

Recommendations were further aligned with regression insights to better reflect viewer preferences.

</div>
🛠️ Tools & Libraries
<div align="justify"> - **Python 3** - **Pandas, NumPy** → Data cleaning & analysis - **Matplotlib, Seaborn** → Data visualization - **Scikit-learn** → Regression modeling - **TuriCreate** → Recommendation system </div>
