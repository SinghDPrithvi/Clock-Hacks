# Clock-Hacks 

This project was inspired by the millions of struggling high school who have too much work to complete and just can't get themselves concentrated enough or focused to do the work
With this AI that we have developed as the core of predictor as to when someone is distracted, neutral or concentrated. With this, we can help people the 336 million people with ADHD and other mental health issues 
or simply the general public to help themselves focus more. Though this project isn't exactly solving these Issues it is a big step towards diagnosing it. Our AI uses a machine learning algorithm to look at 
EEG signals figure out whether someone is in a mental state of distracted, neutral or whether they are concentrated. The EEG signals were converted into a CSV file that we read and preprocessed to get ready for training. 
[
https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-mental-state/data](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-mental-state/data)

J. J. Bird, L. J. Manso, E. P. Ribiero, A. Ekart, and D. R. Faria, “A study on mental state classification using eeg-based brain-machine interface,” in 9th International Conference on Intelligent Systems, IEEE, 2018.

The data was collected from four people (2 males, and 2 females) for 60 seconds per state - relaxed( we describe it as distracted due to its similarity), concentrating, and neutral. They used a Muse EEG headband which recorded the TP9, AF7, AF8 and TP10 EEG placements via dry electrodes.

The AF7 and AF8 are responsible for reading EEG signals between the pre-frontal cortex (Fp), and frontal lobe (F). The prefrontal cortex is responsible for executive functions, personality, working memory, attention, motor planning, and social cognition, and damage to this region can cause problems in decision-making, social interactions, and emotional regulation. The TP9 and TP10 are found between the Temporal Lobe and the Parietal lobe. The Temporoparietal Junction (TPJ) is responsible for multisensory integration, spatial attention, theory of mind, social cognition, memory retrieval, and language processing. It is located between the Temporal Lobe and the Parietal Lobe. Using all this data the paper referenced above made a dataset for people to use to determine whether a person is concentrated, relaxed or neutral. Using this dataset we preprocessed the data split it into training and testing then trained on an ML algorithm(Random_Foreset) That would become a classifier that got a 97 percent accuracy  on detecting where someone is concentrated, relaxed or neutral from the test data. 
