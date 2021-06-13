# Movie-Recommendation-System-Movielens-dataset
# Problem Statement <br>
Given a set of users with their previous ratings for a set of movies, we predict the rating user would give to movies which they have not rated.<br>
# Technologies Used:
•	Visual Studio Code<br>
•	MongoDB compass<br>
•	Spyder-IDE<br>
<b> Backend Technologies:</b><br>
•	Python Version (2,7,2.8)<br>
•	Anaconda (Spyder Ide)<br>
•	pytorch<br>
<b>Requirements</b>:<br>
•	OPERATING SYSTEM: windows 10<br>
•	PROCESSOR INTEL: CORE i3<br>
•	DISK STORAGE :3Gb<br>
# Movie Lens Dataset
1 million ratings from 6040 users to 3706 movies.<br>
Each rating is an integer that varies on a scale from 1 to 5.<br>
movie.csv that contains movie information.<br>
movieId	title	genres<br>
rating.csv that contains ratings of movies by users<br>
userId		movieId		Rating	  timestamp<br>
User.csv that contains user information<br>
userId	      Gender	 Age	 Occupation 	ZipCode<br

DATASET:https://grouplens.org/datasets/movielens/<br>
                                                     
# Deep Autoencoders for Collaborative Filtering
                                                    
The traditional CF methods are usually in a linear manner and they cannot fully explore the potential information that is contained in the interaction matrices.
CF-based recommender systems, a big challenge is the sparsity problem and it is common that more than 90% of values are missing in some datasets
We use deep autoencoder for collabrative filtering to overcome this use.<br>
An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. The aim of an autoencoder is to learn a representation (encoding) for a set of data, typically for dimensionality reduction, by training the network to ignore signal “noise”.
collaborative approach recommendations are made based on items consumed by users  and preferences are similar to that of the referred user.<br>

# Hybrid Model

We  stack the individual models Content based Filtering model and Single value decomposition model discussed above.<br>
#                 Hybrid =Content Based Filtering + SVD 
<b>ALGORITHM:</b><br>
Run Content based filtering and determine the movies which we want to recommend to the user.<br>
Filter and sort the recommendations of CF using SVD predicted ratings.<br>

# Pytorch Tensor

PyTorch supports dynamic computation graphs that allow you to change how the network behaves on the fly, unlike static graphs that are used in frameworks such as Tensorflow.<br>
<br><b>Pytorch=Numpy, with strong GPU acceleration</b><br><br>
PyTorch is a Python-based scientific computing package that uses the power of graphics processing units. It is also one of the preferred deep learning research platforms built to provide maximum flexibility and speed.<br><br>
It is known for providing two of the most high-level features; namely, tensor computations with strong GPU acceleration support and building deep neural networks <br>




                                                    
                                                    

