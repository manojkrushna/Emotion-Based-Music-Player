# Emotion-Based-Music-Player
A ML based music player which plays songs according to user's mood. The model uses LBPH algorithm to recognize the facial emotions/expressions.



Step 1 : Create emotion folders inside data_set folder i.e. Anger, Happy, Neutral and Sad.

Step 2 : Put all photos in these folders according to their categories.

Step 3 : Run dataset.py and assign id to each emotions. Now all the photos will be saved in dataset folder.

Step 4 : Run trainer.py file. This will train the dataset and store it in trainer.yaml file inside trainer folder.

Step 5 : Run Recognition.py file to check if it is working correctly or open main.html file on any browser and do all operations.



Note : While putting images inside emotion folders make sure that all emotions are shown correctly with full face facing forward.
