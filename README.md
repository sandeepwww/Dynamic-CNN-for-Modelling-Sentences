# Dynamic-CNN-for-Modelling-Sentences
An implementation of the CNN model described in "A Convolutional Neural Network for Modelling Sentences". Kalchbrenner et al. 2014. <u><a href='http://phd.nal.co/DCNN'>Here</a></u> is the original code in <b>MATLAB</b>.<br><br>
I referred to <a href='https://github.com/FredericGodin/DynamicCNN'>https://github.com/FredericGodin/DynamicCNN</a> for implementation hints. The model I implemented however, is very specific to the experiments described in the paper.<br>

### Binary Classification
Due to unavailability of a high-end GPU, <b>one epoch of training took ~4 hours</b> and this achieved an accuracy of <b>~78%</b> on the test set of Stanford Sentiment Treebank. The authors reported an accuracy of <b>86.8 %</b> by a well-trained model in the paper.
