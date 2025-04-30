Hey there!
This is my college team project where we tried implementing weapon detection and facial recognition system using YOLOv8.

Our intention is to identify the people holding the weapons in public areas. 

As the dedicated dataset to do the same is not available, we captured our face images and trained a CNN - based InceptionV3 model . (face_recognition_dataset.zip has the faces and face_recognition_with_bounding_boxes.ipynb has the code)

For weapon detection, a weapon dataset from roboflow website has been taken and trained on our YOLOv8s model in Google Colab.  (code can be found in weapon_detection.ipynb)

For the integration, we saved both the models and used them to detect the person holding the weapon in the image.  (code can be found in combine.ipynb and combined_final.ipynb)
