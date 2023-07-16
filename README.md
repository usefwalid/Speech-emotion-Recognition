# Speech-emotion-Recognition
1. Dataset
 CREMA (Crowd-sourced Emotional Multimodal Actors Dataset) is a dataset of 7,442 original clips from 91 actors. 7442 samples may be considered a relatively moderate-sized dataset for speech emotion recognition. These clips were from 48 male and 43 female actors between the ages of 20 and 74 coming from a variety of races and ethnicities (African America, Asian, Caucasian, Hispanic, and Unspecified). Actors spoke from a selection of 12 sentences. The sentences were presented using one of six different emotions (Anger, Disgust, Fear, Happy, Neutral, and Sad). The dataset is available on Kaggle.
 
 Speech emotion recognition typically requires a substantial amount of labeled data for training accurate models. Deep learning models, such as those based on convolutional neural networks (CNNs) or recurrent neural networks (RNNs), often benefit from large amounts of data to generalize well and capture complex patterns in speech signals.
 
 While 7,442 samples can provide a good starting point for training a speech emotion recognition model, having access to a larger dataset is generally desirable. More data can help improve the model's performance, reduce overfitting, and enhance its ability to generalize to unseen data.
 
 It's worth noting that the quality and diversity of the data also play a crucial role. If the 7,442 samples are diverse, covering a wide range of speakers, languages, emotions, and recording conditions, they can be more valuable than a larger dataset with limited variability.

2. Data Splitting
For the data splitting, we will use the following ratios:
Training Set: 70%
Testing Set: 30%
Validation Set: 5% of the Training Set
While the validation set is not used for training the model, it is used for tuning the hyperparameters of the model, such as the learning rate. The validation set is also used for evaluating the model during training to determine when to stop training and prevent overfitting.

3.Accuracy on test data:41%
