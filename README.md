# Gesture-Recognition_using-Transfer-Learning

As a data scientist at a home electronics company which manufactures state of the art **smart televisions.** We want to develop a cool feature in the smart-TV that can **recognise five different gestures** performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

- Thumbs up: Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds
- Stop: Pause the movie

Each video is a sequence of 30 frames (or images).

The generator is able to train with the model. Weights have been allocated to the correct list creation of img_idx, initialization of the batch, correctly looping over the data points in a batch, and cropping, resizing, and normalization of the images.

- img_idx is correctly arranged in the ascending order from 0-30
- The model is able to train without any errors. You get good accuracy with the least possible parameters. There is a weightage given to the structure of the model.

After doing all the experiments, we finalized **Model 11– Transfer learning with GRU and all training weights**, which performed well.

**Reason:**

- (Training Accuracy: 97%, Validation Accuracy: 90%)
- Learning rate gradually decreasing after some Epochs
- model_init_2022-05-1109_55_27.299738/model-00020-0.07672-0.97587-0.27440-0.90000.h5
