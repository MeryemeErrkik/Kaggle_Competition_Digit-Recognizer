# Kaggle_Competition_Digit-Recognizer
CNN model (score= 0.99285)

# Data set
The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
 https://www.kaggle.com/c/digit-recognizer/data
 
 # Model architecture
 Input -> [[Conv2D->relu]*2 -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Output
 
 Optimizer: Nadam
 
 loss function: categorical_crossentropy
 
 # Model evaluation
 After 30 epochs we achieved 99.45% of accuracy
 
