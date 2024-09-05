Lyrics-Generator-Model-Using-Recurrent-Neural-Networks


Project Overview
This project utilizes Long Short-Term Memory (LSTM) neural networks to create song lyrics that emulate the style and structure of existing music. By training on a dataset of lyrics, the model learns to generate coherent and contextually relevant text from a given seed. Techniques like tokenization and one-hot encoding, along with the Adam optimizer, are employed to produce high-quality lyrical content. This project demonstrates AI's creative potential in the music industry, showcasing how machine learning can enhance artistic expression.

Project Structure
Lyric-Gen_RNN.ipynb: The main Jupyter Notebook covering all stages from data exploration and preprocessing to model training and lyric generation.
README.md: This file, providing a comprehensive overview of the project.
output: Contains a graph depicting "Training Loss over Epochs" for the RNN-based lyrics generator. The x-axis represents epochs (0 to 4), while the y-axis shows training loss, which decreases from around 1.84 to 1.75

Features
Exploratory Data Analysis (EDA):
Summary statistics including the distribution of characters, words, and sentences.
Visualizations such as histograms and word clouds for data insights.
Data Preprocessing:
Text cleaning: Removing special characters and converting text to lowercase.
Corpus creation: Building a vocabulary from the lyrics.
Feature and target generation for model training.
Model Training:
LSTM-based neural network trained on character sequences.
Hyperparameter tuning and performance monitoring through loss visualization.
Lyrics Generation:
Creates new song lyrics based on a user-provided seed phrase.
Predicts one character at a time, allowing for flexible and creative outputs.

Dataset
The training dataset, sourced from Kaggle and named AZLyrics, is a comprehensive collection of song lyrics provided in a single CSV file, azlyrics_lyrics_w.csv. This dataset facilitated a streamlined development process while offering a diverse range of text data for effective model training.

Prerequisites
Python 3.x
Jupyter Notebook
Libraries:
TensorFlow
Keras
Pandas
NumPy
Matplotlib
Seaborn
NLTK
WordCloud
Pillow

Cloning the Repository
To clone the repository and navigate to its directory, use the following commands:

```bash
git clone https://github.com/varsha-sherla/Lyrics-Generator-Model-Using-Recurrent-Neural-Networks.git
cd Lyrics-Generator-Model-Using-Recurrent-Neural-Networks
```
