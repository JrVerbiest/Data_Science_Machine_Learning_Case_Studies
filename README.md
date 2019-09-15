# Small Case Studies

A list of small case studies to educate myself in **data science** (databases), **machine learning** and **deep learning**.

<br>

## Data Science

- ***VOICED Database***

  The [*VOICED (VOIce ICar fEDerico II) database*](https://physionet.org/physiobank/database/voiced/) is a database that includes 208 voice samples, from 150 pathological, and 58 healthy voices. In the notebooks the voice recordings in WFDB format (.dat) and in text format (.txt) are dowloaded together with the info text files (-info.txt) and the header files (.hea) to create a dataset saved in an excel file.

  - Download the dataset: [notebook]()
  - Create the dataset: [notebook](), dataset is stored in  *dataset_InfoTxtFile.xlsx*

- ***The Chinook Database (SQL)*** 

  In this [notebook]() we play around with an example database using SQL and Python.
  

<br>

## Machine Learning

- ***Freesound General-Purpose Audio Tagging Challenge***
  
  In this [notebook](), [Mel Frequency Ceptral Coefficient (MFCC)](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum) features from the audio signal are extracte, using [libROSA](https://librosa.github.io/librosa/), and a classification using Random Forest is performed. In this notebook only two labels are selected from the dataset: bark (dog) and meow (cat).

- ***PhysioNet 2016 Challenge.***

  Classification of Normal/Abnormal Hearth Sounds Recordings.
  
  Starting from a feature table, a machine learning algorithm is explored. The feature table comes from the [*Heart Sound Classification Matlab demo*](https://nl.mathworks.com/matlabcentral/fileexchange/65286-heart-sound-classifier), extracted from the *[PhysioNet/CinC Challenge 2016](https://physionet.org/challenge/2016/)* challenge dataset.
  
  - Logistic regression: [notebook]()
  - Random forest and comparison with logistic regression: [notebook]()

<br>

## Deep Learning

- ***MNIST***
  
  MNIST the "Hello World" of deep learning. In this [notebook]() grayscale images of handwritten digits (image size: 28 x 28 pixels) are classsified into 10 categories (0 through 9), in Keras using dense layers and 2D convnets. 
  


<br>

---

*Last update: 15 September 2019*