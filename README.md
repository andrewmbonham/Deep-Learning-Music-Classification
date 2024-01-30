# Deep Learning Music Genre Classification

## Task
The task here is to analyze music audio files and predict
the genre using a convolutional neural network (CNN). 

## Description
The challenge was solved by using the librosa library to 
generate statistics for 1000 audio files which were then 
passed through a CNN which gradually learned to associate
music genres with certain statistics. 

## Installation
The following Python packages are required:
- numpy 
- pandas 
- matplotlib
- sklearn 
- tensorflow 
- glob 
- lobrosa

To install, run `pip install <package>`

## Usage
The original data can be found here: 

https://storage.googleapis.com/qwasar-public/track-ds/classically_punk_music_genres.tar.gz

This data was analyzed in the first section of the notebook, 
`Generate Features`, so the analysis can be used without the 
original data. Ensuring that the two CSV files, `myfeatures.csv` 
and `myfeatures_3_sec.csv` are included in the notebook directory, 
simply import the packages and execute all cells starting from the 
`Modeling the Data` section. Adjustments to NN parameters can be 
made but may affect model performance. 
