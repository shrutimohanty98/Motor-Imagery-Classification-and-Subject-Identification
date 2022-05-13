# Motor Imagery Classification and Subject Identification

This project focuses on learning the representations for
the Electroencephalogram (EEG) signals that are responsible
for motor imagery. This can be utilized in multiple
prediction tasks. The first task explored in this project is
motor imagery classification. Various neural network architectures
are implemented and tuned for this purpose -
CNN, LSTM, and GRUs. The insights from motor imagery
task classification are leveraged to identify the subject given
the EEG data, which is our second task. A combination of
CNN-LSTM architecture is used to learn the EEG distribution
by training on the entire dataset. Using the tuned
model, we perform the task of transfer learning to predict
subject identities given their EEG representations. We have
discussed the results from training on every subject, and the
entire dataset, and have compared the various architectures
implemented. Analysis has been performed on the data after
certain pre-processing deduced from the effect of time
period on accuracy. We achieve an accuracy of 73% for
motor imagery classification, and 85% for subject identification.

This is a part of Winter 2022 Course - Neural Networks and Deep Learning (ECE 247)
