![Zomato](https://user-images.githubusercontent.com/88651007/147449497-8017fd17-e8eb-469f-952b-7ad7d435ec38.png)
<h1 align="center"> Zomato-Customer-Review-Sentiment-Analysis </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>
<h2> :floppy_disk: Project Files Description</h2>
<p>There are two sets of data.The first one provides the data on the 105 restaurants and the
other is about the 10,000 reviews for these 105 restaurants, approximately 100 reviews for each restaurants.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: k-means clustering</h2>
<p>K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.Typically, unsupervised algorithms make inferences from datasets using only input vectors without referring to known, or labelled, outcomes.</p>
<p>The objective of K-means is simple: group similar data points together and discover underlying patterns. To achieve this objective, K-means looks for a fixed number (k) of clusters in a dataset.</p>
<p>A cluster refers to a collection of data points aggregated together because of certain similarities.</p>
<p>The k-means algorithm searches for a pre-determined number of clusters within an unlabeled multidimensional dataset. It accomplishes this using a simple conception of what the optimal clustering looks like:</p>
<p><li>The "cluster center" is the arithmetic mean of all the points belonging to the cluster.</li></p>
<p><li>Each point is closer to its own cluster center than to other cluster centers.</li></p>
<p>Those two assumptions are the basis of the k-means model.</p>
<b><p>k-Means Algorithm: Expectation–Maximization</b></p>
<p>Expectation–maximization (E–M) is a powerful algorithm that comes up in a variety of contexts within data science. k-means is a particularly simple and easy-to-understand application of the algorithm.</p>
In short, the expectation–maximization approach here consists of the following procedure:
<li>Guess some cluster centers</li>
<li>Repeat until converged</li>
    <p>1. E-Step: assign points to the nearest cluster center</p>
    <p>2. M-Step: set the cluster centers to the mean</p>
    
<p>Here the "E-step" or "Expectation step" is so-named because it involves updating our expectation of which cluster each point belongs to.</p>
<p>The "M-step" or "Maximization step" is so-named because it involves maximizing some fitness function that defines the location of the cluster centers — in this case, that maximization is accomplished by taking a simple mean of the data in each cluster.</p>
<p>The literature about this algorithm is vast, but can be summarized as follows: under typical circumstances, each repetition of the E-step and M-step will always result in a better estimate of the cluster characteristics.</P>

<b><p>Principal Component Analysis</b></p>
<p>PCA is fundamentally a dimensionality reduction algorithm, but it can also be useful as a tool for visualization, for noise filtering, for feature extraction and engineering, and much more.</p>
<p>Principal component analysis is a fast and flexible unsupervised method for dimensionality reduction in data. Its behavior is easiest to visualize by looking at a two-dimensional dataset.</p>

<b><p>Learning the math behind PCA</b></p>
<b><p>Step 1 :</b> Take the whole dataset with dimension  d  (which corresponds to the  d  features)</p>
<p><b>Step 2 :</b> Compute the mean of every dimension of the whole dataset.</p>
<p><b>Step 3 :</b> Compute the covariance matrix of the whole dataset
  <b>Cov(X,Y)=1n−1∑i=1n(Xi−X¯)(Yi−Y¯)</b></p> 
<b><p>Step 4 :</b> Compute Eigenvectors and corresponding Eigenvalues for the covariance matrix A</p>
</p>Let <b>A</b> be a square matrix, <b>ν</b> a vector and <b>λ</b> a scalar that satisfies  <b>Aν=λν</b> , then <b>λ</b> is called eigenvalue associated with eigenvector ν of A.</p>
<b><p>Step 5 :</b> Sort the eigenvectors by decreasing eigenvalues and choose <b>k</b> eigenvectors with the largest eigenvalues to form a <b>d×k</b> dimensional matrix <b>W</b> .</p>
<b><p>Step 6 :</b> Transform the samples onto the new subspace</p>
<p>In the last step, we use the  d×k  dimensional matrix  W  that we just computed to transform our samples onto the new subspace via the equation  <b>y=W'×x</b>  where  W'  is the transpose of the matrix  W .</p>
<p>Given any high-dimensional dataset, we can start with PCA in order to visualize the relationship between points, to understand the main variance in the data, and to understand the intrinsic dimensionality.
Certainly PCA is not useful for every high-dimensional dataset, but it offers a straightforward and efficient path to gaining insight into high-dimensional data.
PCA's main weakness is that it tends to be highly affected by outliers in the data. For this reason, many robust variants of PCA have been developed, many of which act to iteratively discard data points that are poorly described by the initial components.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Sidhartha Patel | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/sidpatel96)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SIDPATEL-9496)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](	https://medium.com/@sidharthap1996)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1FzoVHxqus-tCxejkEy6VMEbcqzTVQuST/view?usp=sharing)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :books: References</h2>
<ul>
  <li><p>Dr. Michael J. Garbade, 'Understanding K-means Clustering in Machine Learning'. [Online].</p>
      <p>Available: https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1</p>
  </li>
  <li><p>Wikipedia.org, 'k-means clustering'. [Online].</p>
      <p>Available: https://en.wikipedia.org/wiki/K-means_clustering</p>
  </li>
  <li><p>Wikipedia.org, 'Elbow method (clustering)'. [Online].</p>
      <p>Available: https://en.wikipedia.org/wiki/Elbow_method_(clustering)</p>
  </li>
  <li><p>365datascience.com, 'How to Combine PCA and K-means Clustering in Python?'. [Online].</p>
      <p>Available: https://365datascience.com/tutorials/python-tutorials/pca-k-means/</p>
  </li>
  <li><p>SANCHITA MANGALE, 'Scree Plot'. [Online].</p>
      <p>Available: https://sanchitamangale12.medium.com/scree-plot-733ed72c8608</p>
  </li>
  <li><p>stackabuse.com, 'Simple NLP in Python with TextBlob: N-Grams Detection'. [Online].</p>
      <p>Available: https://stackabuse.com/simple-nlp-in-python-with-textblob-n-grams-detection/</p>
  </li>
  <li><p>geeksforgeeks.org, 'Using CountVectorizer to Extracting Features from Text'. [Online].</p>
      <p>Available: https://www.geeksforgeeks.org/using-countvectorizer-to-extracting-features-from-text/</p>
  </li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
