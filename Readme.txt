Make sure you have the following installed on your machine:
Python (version 3.8)
OpenCV
Mediapipe
scikit-learn
Training the Model:

Run the collect_imgs.py script to gather data from the webcam.
Then, execute the create_dataset.py script to create the dataset.
After that, run the train_classifier.py script to train the model using the dataset.
Upon completion of these steps, the trained model will be saved in a file named model.p.
Testing the Model:

Run the inference_classifier.py script to test the trained model.
The program will load the trained model and use it to classify images captured by the webcam.
The results will be displayed on the screen in real-time.
Following these steps, anyone can easily open the project and execute the code to either train or test the model.