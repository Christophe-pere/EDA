# EDA
This notebook is made to permit users to explore quickly their data. The goal is to automatize this part of the lifecycle to provide insights and intuitions about the data. So the notebook uses pandas-profiling, and dataprep.eda to facilitate the exploration. Next, the different parts explore the feature importance and feature extraction with different methods and algorithms.
This notebook has been presented in a medium post [What is EDA? Yes, another post on EDA](#https://medium.com/@pere.christophe1/what-is-eda-yes-another-post-on-eda-d8b5c06269a9) and submitted to [Towards Data Science](#https://towardsdatascience.com/).
 

## Content
- Sand box to load and clean data
- EDA
	- pandas-profiling
	- Dataprep EDA
	- Sweetviz to analyze data
	- Target identification
- Feature selection
	- Removing features with low variance
	- Univariate Selection
	- Recursive Feature Elimination (RFE)
	- SelectFromModel
- Feature Extraction
	- Principal Component Analysis (PCA)
	- Independent Component Analysis (ICA)
	- Linear Discriminant Analysis (LDA)
	- Locally Linear Embedding (LLE)
	- t-distributed Stochastic Neighbor Embedding (t-SNE)
- Feature Importance
	- Tree method
	- Permutation Method
