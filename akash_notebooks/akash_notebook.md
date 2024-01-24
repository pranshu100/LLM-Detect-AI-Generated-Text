## README.md

**Understanding and Classifying AI-Generated Text**

This repository explores an unsupervised approach to identifying AI-generated text in Kaggle essay datasets. Instead of traditional supervised classification methods, this approach focuses on dimensionality reduction and cluster analysis to separate human-written and AI-generated text.

### Key points:

* **observation:** Most Kaggle notebooks rely on supervised classifiers with TF-IDF vectors, often resulting in repetitive approaches.
* **Unsupervised solution:** This notebook attempts unsupervised classification through UMAP dimensionality reduction and cluster analysis.
* **Cluster identification:** Human-written essays tend to form a single, tightly-knit cluster, while AI-generated essays form multiple clusters due to their inherent variance.
* **Keyword analysis:** Identifying high usage of terms like "because" and "thing" as indicators of human authorship.
* **Probability estimation:** Utilizing cluster centroids and a logistic function to calculate the probability of a specific essay belonging to either cluster.

### Highlights:

* **Alternative to supervised methods:** Offers a fresh perspective on AI text classification.
* **Intriguing cluster behavior:** Demonstrates the distinct clustering patterns of human and AI-generated text.
* **Probabilistic labeling:** Provides a nuanced interpretation of essay origin beyond binary classification.

### Contributions:

* Explores a novel unsupervised approach to AI text classification.
* Offers insights into the clustering behavior of AI-generated text.
* Presents a method for estimating the probability of AI authorship.

### Further explorations:

* Can this approach be applied to different text types and datasets?
* Can other keywords or linguistic features be used for cluster identification?
* Can additional unsupervised learning techniques be incorporated for improved accuracy?

We encourage you to explore this code and contribute your own ideas to push the boundaries of AI text classification!

##### Note: Ahmet Erdem, a Kaggle Grandmaster, made a valuable contribution by highlighting the potential of "because" and "thing" as keywords for identifying human-written text

