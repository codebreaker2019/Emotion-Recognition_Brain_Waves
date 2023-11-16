# Emotion Recognition_Brain_Waves

In this research work, we propose a subject-dependent emotion recognition system from electroencephalogram (EEG) signals based on 1D- convolutional neural network (1D-CNN). To begin with, we decompose raw EEG signals into six sub-bands and extract the power spectrum feature by utilizing the fast Fourier transform technique. After that, we combined extracted power spectrum features with eye movement and removed differential entropy features. We do experiment with SJTU Emotion EEG Dataset SEED-V. 

This dataset is publicly available on their official website: https://bcmi.sjtu.edu.cn/home/seed/

Dataset: This dataset comprises 5 emotions including (Happiness, Sad, Disgust, Neutral, and Fear). 16 participants' EEG signals and Eye movement signals were recorded while they were watching movie clips. Each participant watched 45 trials from 3 sessions. 

Accuracy: We obtained 99.80% testing which surpasses prior research based on the SEED-V dataset. 
 
