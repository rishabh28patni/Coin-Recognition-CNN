# Coin-Recognition-CNN
Using a CNN, I will attempt to develop a model capable of predicting what currency and denomination an inputted coin's photo is. 

## List of Supported Currencies:
Australian dollar	Hungarian Forint	Pakistan Rupee
Brazilian Real	Indian Rupee	Philipine peso
British pound	Indonesian Rupiah	Polish Zloty
Canadian dollar	Israeli New Shekel	Russian Ruble
Chilean peso	Japanese Yen	Singapore Dollar
Chinese Yuan Renminbi	Korean Won	South African Rand
Czech Koruna	Malaysian Ringgit	Swedish Krona
Danish Krone	Mexican peso	Swiss Franc
Euro	New Zealand dollar	Tawian Dollar
Hong Kong dollar	Norwegian Krone	Thai Baht
Turkish Lira	US Dollar	

## Data Source
The data I used was a set of 8000 labelled images available on Kaggle:
https://www.kaggle.com/wanderdust/coin-images
The set was predivided into a training, validation and test set with 80%-10%-10% distribution in each respective set of data.


## Steps
Uploading the data:
A step by step series of examples that tell you how to get a development env running


## Final CNN Used
Architecture used is:



## Results
A final accuracy of 78% on the testing data and 77% on the validation set was obtained through running the CNN above. Adding more parameters, increasing the size of the dataset used, and further tuning could improve accuracy of the model. Another issue that could potentially be resolved is that some images have both the front and the back of the coin, some images had only one side. Finding a consistency on the type of images used could improve accuracy.

## Tools Used
Language: Python
Frameworks/Libraries: Tensorflow, Keras, Matplotlib, Numpy

## Authors
Rishabh Patni

## Acknowledgments
Wanderlust for dataset and function for mapping function (integery to currency):
https://github.com/wanderdust/coin-cnn

Amyoshino for first CNN architecture to test:
https://github.com/amyoshino/Identifying-Brazilian-Coins-with-CNN
