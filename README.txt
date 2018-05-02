Omnet adversarial anomaly detection
Prameesha Weerasinghe, p.weerasinghe'at'student.unimelb.edu.au

The datasets were generated using Omnet++, a network simulation tool. It can be used for testing adversarial anomaly detection applications (integrity attacks).

Data Type:  Multivariate
Task:  Classification 
Attribute Type: Real
Area: CS / Engineering
Format Type: Matrix
Does your data set contain missing values?: No

Number of Attributes (fields within each record): 111

The data is collected from a simulation where there are multiple adversaries and civilians communicating in a region with multiple passive listeners.
Data about each transmission source is collected from 3 of the listeners. The objective is to classify if a transmission source is an adversary or a civilian based on the data.
The problem also has an adversarial flavor where the adversaries deliberately attemt to mislead the classifier by changing their communication behavior.

There are several data files that contain clean data from 2 classes

Contains data from the normal class for training
normal_training.mat - 337 instances
Contains data from the anomaly class for training
anomaly_training.mat - 18 instances

Test data and test labels
test_data
test_labels

other datasets contain instances where anomalies have been distorted to resemble normal data points. The distortion severity defines the sevirity of the attack.
dist_anomaly_training_0.3.mat
dist_anomaly_training_0.4.mat
dist_anomaly_training_0.5.mat
dist_test_data.mat
dist_test_labels.mat

All attributes have been normalized.
1 - carrierFrequency
2 - bandwidth
3 - bitrate
~4 - duration
~5 - messageLength
~6 - inter arrival time

The last 3 features were averaged over 5 minute intervals and appended to the feature vector which resulted in 111 features.
