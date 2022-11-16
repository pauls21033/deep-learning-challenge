# deep-learning-challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

*EIN and NAME—Identification columns

*APPLICATION_TYPE—Alphabet Soup application type

*AFFILIATION—Affiliated sector of industry

*CLASSIFICATION—Government organization classification

*USE_CASE—Use case for funding

*ORGANIZATION—Organization type

*STATUS—Active status

*INCOME_AMT—Income classification

*SPECIAL_CONSIDERATIONS—Special considerations for application

*ASK_AMT—Funding amount requested

*IS_SUCCESSFUL—Was the money used effective

Resuts:
## Attempt 1
Layers: 2 "relu"
Attempt one: Model: "sequential"
_____
Layer (type) Output Shape Param
=================================================================

dense (Dense) (None, 9) 477
dense_1 (Dense) (None, 18) 180
dense_2 (Dense) (None, 1) 19
=================================================================

Total params: 676
Trainable params: 676
Non-trainable params: 0
268/268 - 0s - loss: 0.5413 - accuracy: 0.7378 - 464ms/epoch - 2ms/step¶
Loss: 0.5412667989730835, Accuracy: 0.7378425598144531

![1ch5](https://user-images.githubusercontent.com/107385310/202059150-b473d8e7-9ee4-46bd-8db5-9a0ed8ffea16.png)


## ATTEMPT 2

# Layers: 3 "relu"
Model: "sequential_1"
Layer (type) Output Shape Param # 
dense_3 (Dense) (None, 9) 477

dense_4 (Dense) (None, 18) 180

dense_5 (Dense) (None, 25) 475

dense_6 (Dense) (None, 1) 26

================================================================= #Total params: 1,158 #Trainable params: 1,158 Non-trainable params: 0

268/268 - 1s - loss: 0.5442 - accuracy: 0.7366 - 1s/epoch - 4ms/step Loss: 0.5441606044769287, Accuracy: 0.7365597486495972


![2ch5](https://user-images.githubusercontent.com/107385310/202059190-8948f86a-a513-44bf-b675-960a56440f63.png)


## Attempt 3

Layers: 4 "Tanh"
Model: "sequential_6"
Layer (type) Output Shape Param # 
dense_24 (Dense) (None, 5) 265

dense_25 (Dense) (None, 10) 60

dense_26 (Dense) (None, 15) 165

dense_27 (Dense) (None, 20) 320

dense_28 (Dense) (None, 1) 21

================================================================= Total params: 831 Trainable params: 831 Non-trainable params: 0

268/268 - 0s - loss: 0.5438 - accuracy: 0.7390 - 281ms/epoch - 1ms/step Loss: 0.5438346266746521, Accuracy: 0.7390087246894836

![3ch5](https://user-images.githubusercontent.com/107385310/202059230-653a63d8-4250-45e4-b92c-37e57a6a1892.png)
