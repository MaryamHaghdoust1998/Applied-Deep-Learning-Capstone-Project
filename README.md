# Applied-Deep-Learning-Capstone-Project
After filling in the missing codes, you should be able to load the pretrained model resnet18.
Setting the parameter pretrained to be true resnet18 returns a model that was pre-trained on the ImageNet database.
Since ImageNet contains 1000 classes the last layer of resnet18 "fc" has 1000 outputs.
But for this assignment you are classifying the Denomination of the Euro.
And there are seven different denomination of the European banknotes so you need to modify the last layer of the model that you loaded to have 7 outputs.

After setting up your model, you have to train your model on the training dataset of images of European Denomination.
You should be able to reach a validation accuracy of greater than 0.95 on your model and print out the validation accuracy. 
And plot a graph of Average Loss per Epoch vs Epoch and a graph of Accuracy vs Epoch.
Densenet121 is another pre-trained model for image classification. In this question you will repeat Question 3.1 and Question 3.2 using Densenet121 instead of resnet18.
You should load the pretrained model, modify the last layer of the model have 7 outputs and then train the model to achieve a validation accuracy of greater than 0.95.
