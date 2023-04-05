# Chinese-handwriting-recognition
Download Chinese dataset and refer to https://github.com/AI-FREE-Team/Traditional-Chinese-Handwriting-Dataset.
Data Preparation: Use move_file.py to classify many handwriting words to separate "file". (Optional)
Step 1: Download the Chinese handwriting file.
Step 2: Set up traing and validation datasets. (80% of total files is for training, and 20% of ones is for validation.)
Step 3: Data augmentation.
Step 4: Build the model.
Step 5: Train the model.
Step 6: Training 50 epochs, the accuracy is almost 96%. (Optional, if your dataset is too large, please skip.)
Step 7: Pick up the file for testing, and check the accuracy. If not good, please revise the model and re-train it.
Step 8: Save the model. (.h5)
