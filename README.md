# AN2DL-FinalProject
This project was realized for the final examination of Artificial Neural Networks and Deep Learning at POLIMI.
The evaluation was divided in two parts: the first one about classification with CNN; the second one about time series regression with LSTM.

## Part 1 - CNN Classification
This part consisted in correctly classifying leaves photos. It was given a training dataset, different from the one used for the final evaluation.

The training set was then split locally for training and validation of the models before submitting them to the online evaluation platform.

The model achieved a final accuracy around 97%, scoring in the top 20 of all projects.

## Part 2 - LSTM Regression
This part consisted in produce forecasting of a time series. It was given a training dataset, different from the one used for the final evaluation, but no knowledge about the attributes in the set was given.

The training set was split similarly for the previous part.

The model achieved a final accuracy around 95%, scoring in the top 30 of all projects.

## Custom framework
To better design and train models, it has been developed also a framework, based on Python and Tensorflow, able to read networks design (written in configuration files .yaml) and to train a queue of models.
It was also implemented a function to send notification over telegram about the progress of trainings and validations.

## Evaluation
After completing both parts the complete project was graded 10/10.5.
