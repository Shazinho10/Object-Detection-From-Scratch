# Object-Detection-From-Scratch
Object detector made from scratch with CNN and sliding window algirithm with Haarcascade

The file named as "image_augmentation.ipynb" is the one which takes the images from different directories belonging to diferent classes. After that image
augmentation is applied using ImageDataGenerator from Keras.

when the images are augmented, then there is 'training.ipynb' file with which I have trained the model using CNN.

Once the model was ready, then in 'sliding_detection.ipynb', I applied haar cascade classifier which uses the sliding window algirithm to detect faces. After detecting the faces,
I fed those croped images to the CNN classifier with which I got the label.
