# Saturdays AI Madrid (fall 2019) sessions by Miguel Blanco Marcos
Here I will record the projects created in relation to the autumn 2019 edition of the Saturdays AI Madrid initiative, in the Deep Learning path. I will generally clean up my code and include small improvements or extensions during the week following the session.

## Session 1: Video Frame Classifier (2019/09/14)
The objective of this session was to train a Neural Network to identify to which of two videos does a frame belong.

For this, any two videos from youtube were downloaded, and a number of frames extracted form them (around 500 form each). Then, they were resized to the same format, divided between train and test set, and stored in an array for inputing to a NN created using Keras.

This project was designed to run in Google Colab.
