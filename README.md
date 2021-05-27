# Small Case Studies

A list of small case studies to educate myself in **data science** (databases), **machine learning** and **deep learning**.

<br>

## Data Science

- ***VOICED Database***

  The [*VOICED (VOIce ICar fEDerico II) database*](https://physionet.org/physiobank/database/voiced/) is a database that includes 208 voice samples, from 150 pathological, and 58 healthy voices. In the notebooks the voice recordings in WFDB format (.dat) and in text format (.txt) are dowloaded together with the info text files (-info.txt) and the header files (.hea) to create a dataset saved in an excel file.

  - Download the dataset: [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/VOICED%20Database/getDatabase.ipynb)
  - Create the dataset: [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/VOICED%20Database/createDataset.ipynb), dataset is stored in  *dataset_InfoTxtFile.xlsx*

- ***The Chinook Database (SQL)*** 

  In this [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/The%20Chinook%20Database/SQL%20-%20The%20Chinook%20Database.ipynb) we play around with an example database using SQL and Python.
  

<br>

## Machine Learning

- ***Freesound General-Purpose Audio Tagging Challenge***
  
  In this [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/Freesound%20General-Purpose%20Audio%20Tagging%20Challenge/Freesound%20General-Purpose%20Audio%20Tagging%20Challenge%20-%20Random%20Forest%20and%20MFCC.ipynb), [Mel Frequency Ceptral Coefficient (MFCC)](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum) features from the audio signal are extracte, using [libROSA](https://librosa.github.io/librosa/), and a classification using Random Forest is performed. In this notebook only two labels are selected from the dataset: bark (dog) and meow (cat).

- ***PhysioNet 2016 Challenge.***

  Classification of Normal/Abnormal Hearth Sounds Recordings.
  
  Starting from a feature table, a machine learning algorithm is explored. The feature table comes from the [*Heart Sound Classification Matlab demo*](https://nl.mathworks.com/matlabcentral/fileexchange/65286-heart-sound-classifier), extracted from the *[PhysioNet/CinC Challenge 2016](https://physionet.org/challenge/2016/)* challenge dataset.
  
  - Logistic regression: [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/PhysioNet%202016%20Challenge/Machine_Learning_Logistic_regression.ipynb)
  - Random forest and comparison with logistic regression: [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/PhysioNet%202016%20Challenge/Machine_Learning_Random_forest.ipynb)

<br>

## Deep Learning

- ***MNIST***
  
  MNIST the "Hello World" of deep learning. In this [notebook](https://github.com/JrVerbiest/Data_Science_Machine_Learning_Case_Studies/blob/master/MNIST/MNIST.ipynb) grayscale images of handwritten digits (image size: 28 x 28 pixels) are classsified into 10 categories (0 through 9), in Keras using dense layers and 2D convnets.
  

<br>

## References

- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems, Aurélien Géron
- Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow, Sebastian Raschka and Vahid Mirjalili
- Deep Learning with Python, Francois Chollet

<br>

---

*Last update: 27 May 2021*