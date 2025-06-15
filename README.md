# IPL Data Analysis – Player Valuation and Clustering


![image](https://github.com/user-attachments/assets/990684c0-1a42-42a5-9ba8-2e6bdf05967a)


This project explores IPL (Indian Premier League) player performance using data analysis and machine learning techniques to identify and cluster valuable and unvaluable players. By analyzing historical performance statistics, we extract meaningful insights and apply clustering algorithms to group players based on their impact and value to a team.



📌 Objective
1.The main goals of this project are:

2.To clean and preprocess IPL player data.

3.To compute key performance indicators for players (batsmen and bowlers).

4.To evaluate player value using metrics such as runs, strike rate, wickets, economy, consistency, etc.

6.To apply KMeans clustering to group players into valuable and unvaluable clusters.

7.To visualize and interpret the results to assist in data-driven decision-making for team building.




🧰 Tech Stack
Python

Pandas – for data manipulation

Matplotlib / Seaborn – for data visualization

Scikit-learn – for clustering and machine learning

Jupyter Notebook – for development and demonstration




📊 Dataset
The dataset used is a cleaned and preprocessed version of IPL data, which includes:

Match statistics

Player performance

Batting and bowling metrics

Team and season information

(Data can be sourced from Kaggle IPL Datasets or official IPL stats)




🔍 Methodology
1.Data Cleaning – Handle nulls, duplicates, and inconsistent entries.

2.Feature Engineering – Calculate custom metrics like average, strike rate, economy, contribution score, etc.

3.Normalization – Scale features for fair clustering.

4.Clustering with KMeans – Find optimal clusters using Elbow Method and visualize clusters.

5.Visualization – Use scatter plots, heatmaps, and bar graphs to interpret results.



🚀 How to Run
1.Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/ipl-player-valuation.git
cd ipl-player-valuation

2.Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt

3.Open the Jupyter Notebook:
bash
Copy
Edit
jupyter notebook
Run the ipl_player_clustering.ipynb file step-by-step.



🤝 Contributing
Pull requests are welcome! If you want to improve the model or add more insights (like auction price comparison or role-based clustering), feel free to fork and suggest changes.


