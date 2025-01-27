# MiniProject
Movie Data Visualizations
This project provides interactive visualizations of movie ratings data, including the distribution of ratings by genres and years, popular genres by user demographics, and correlations between genres, user activity, and ratings. The app is built using Streamlit and Seaborn for visualization.

Prerequisites
Before running this app, make sure you have the following dependencies installed:

Python 3.7+ (preferably Python 3.8+)
Streamlit
Seaborn
Matplotlib
Numpy
You can install the required libraries using the following command:

bash
Copy
Edit
pip install streamlit seaborn matplotlib numpy
Additionally, you’ll need the MovieLens dataset files for ratings, movies, and users. The dataset can be downloaded from here.

Dataset Files
ratings.dat: Contains user ratings for movies.
movies.dat: Contains movie details including movie IDs, titles, and genres.
users.dat: Contains user details, including user IDs, ages, and gender.
Place these files in the MiniProject-NexGen/ folder or specify the correct path to them in the script.

Project Structure
The project contains the following files:

Copy
Edit
Movie-Data-Visualizations/
├── app.py
├── MiniProject-NexGen/
│   ├── ratings.dat
│   ├── movies.dat
│   └── users.dat
└── README.md
app.py: The main Python script that runs the Streamlit app.
MiniProject-NexGen/: Directory containing the dataset files.
README.md: This file.
How to Run the App
Clone or Download the Repository:

Clone or download this repository to your local machine.
Install Dependencies:

Ensure that all the required libraries (Streamlit, Seaborn, Matplotlib, NumPy) are installed.
Place the Dataset Files:

Ensure the ratings.dat, movies.dat, and users.dat files are in the MiniProject-NexGen/ directory (or update the paths in the code accordingly).
Run the Streamlit App:

Open a terminal or command prompt in the project directory and run the following command:

bash
Copy
Edit
streamlit run app.py
View the App:

The app will open in your default web browser. You can interact with the app and explore the visualizations.
Features
The app offers the following visualizations:

1. Distribution of Ratings by Genres and Years
Displays a bar chart of average ratings by genre.
Shows a line plot of average ratings by year.
2. Popular Genres by User Demographics
Displays bar charts of popular genres for different age groups.
3. Heatmaps Showing Correlation Between Genres, User Activity, and Ratings
Displays a heatmap showing the correlation between user activity, total ratings, and average ratings for different genres.
Customization
You can modify the following in the app:

Dataset Paths: Update the paths to the dataset files if they are not located in the default directory.
Visualizations: Add more visualizations or modify the existing ones to explore the data further.
License
This project is licensed under the MIT License - see the LICENSE file for details.
