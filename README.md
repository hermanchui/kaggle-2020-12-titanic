# Kaggle Getting Started Challenge at https://www.kaggle.com/c/titanic
# 
# Files:
#   notebooka96140491d.ipynb = my solution using TensorFlow
#   train.csv = provided training dataset, labelled
#   test.csv = provided test dataset, no labels
#   gender_submission = provided sample submission
#   my_submission.csv = output from my notebook solution
# 
# Model:
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense (Dense)                (None, 32)                320       
_________________________________________________________________
dense_1 (Dense)              (None, 16)                528       
_________________________________________________________________
dense_2 (Dense)              (None, 16)                272       
_________________________________________________________________
dense_3 (Dense)              (None, 16)                272       
_________________________________________________________________
dense_4 (Dense)              (None, 1)                 17        
=================================================================
Total params: 1,409
Trainable params: 1,409
Non-trainable params: 0
_________________________________________________________________
