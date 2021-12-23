# Deep_learning_homework

Analysis and conclusions

Model 0(first model) results
loss: 0.5670 - 
accuracy: 0.7271 -
recall: 0.7835 -

Layer 1 - 80
Layer 2 - 30
Ephocs 100

Model (Evaluation 2) results
loss: 0.5766 -
accuracy: 0.7290 -
recall_1: 0.7938 - 

Layer 1 - 1450
Layer 2 - 80
Ephocs 100

Model (evaluation 3) results 
loss: 0.5611 -
accuracy: 0.7145 - 
recall_2: 0.7320 - 

Layer 1 - 3
Layer 2 - 15
Layer 3 - 3
Ephocs 100

Summary 
Neither model was able to perform above 73% accuracy rate.  First and second evalution graphs seem to diverge with the traing error and the validation error, with the training error staying low and the validation error increasing on the loss graphs it seems to do this from over fitting data and learning way too much on the training examples.  Its pretty apparent from comparing the accuracy and the loss graphs. It can't seem to tell the difference from the training data and the actually new data.

The third evaluation seems to have a lower loss sensitivity as the first two. Seems for the loss graph that the gap will be minimal to the point of stability with its two final values. So the third evaluation has more promise for a good fit for the training and validation loss.



