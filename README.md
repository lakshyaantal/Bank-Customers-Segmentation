# Bank-Customers-Segmentation
I’m thrilled to share my recent hands-on project focused on unsupervised learning using clustering algorithms. We worked on a real-world bank marketing dataset and applied rigorous steps to derive meaningful customer segments. Here's a quick breakdown:

🔍 Project Workflow:

📥 Data Loading & Cleaning

Loaded a financial dataset with features like min_payment_amt, probability_of_full_payment, and more.

Addressed missing values, duplicates, and outliers using IQR technique.

📊 Exploratory Data Analysis

Used seaborn and matplotlib to visualize distributions, boxplots, and pairwise relationships.

Correlation heatmaps were used to detect multicollinearity.

⚖️ Feature Scaling

Applied MinMaxScaler to normalize variables for better distance-based clustering.

🌿 Hierarchical Clustering

Visualized dendrograms to determine optimal clusters (tried 2 to 9).

Chose 3 clusters using Ward’s linkage and Silhouette Scores.

📈 Cluster Evaluation

Cluster profiling revealed:

Cluster 0: Likely responsible financial behavior (high probability of full payment).

Cluster 1: Moderate behavior.

Cluster 2: High-risk customers (low payment probability, low min payments).

💡 Key Insights:

The clustering approach helped isolate customer segments that can be targeted differently for marketing strategies, risk profiling, or credit policy refinement.

Silhouette scores validated our choice of 3 clusters for best cohesion and separation.

📌 Conclusion: This project was a great dive into unsupervised learning and real-world clustering. It emphasized the value of data preparation, visual EDA, and business-contextual interpretation of technical outcomes.

🔧 Tools Used: Python, Pandas, Seaborn, Scikit-learn, Hierarchical Clustering, Dendrograms, Silhouette Score
