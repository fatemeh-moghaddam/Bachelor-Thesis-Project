# Prediction of FoG (Freezing of Gait) in parkinson patients
Thesis Project- Bachelor's of Biomedical Engineering
## Data
  Daphnet Freezing of Gait  dataset  [DG dataset](https://archive.ics.uci.edu/ml/datasets/Daphnet+Freezing+of+Gait#)
    This dataset contains the annotated readings of 3 acceleration sensors at the hip and leg of Parkinson's disease patients that experience freezing of gait (FoG) during walking tasks.
  - 10 patients, 7 male and 3 female
  - 8 hours and 20 minutes signals each
  - each person had 0-66 FoGs, average 23.7 per person
  - each FoG lasts between 5.4 - 40.5 seconds, average 7.3 seconds
 
## preprocessing
  - Windowing
  - Normalization
  - Pruning
  - Balancing
  - Clustering
  - Shuffling
  
## Network
  - 5 convolutional layers, max pooling, 1 fully connected layer
  - activation function: ReLU
  - learning rate: 0.001
  - optimizer: Adam
