# Face Mask Detection using MobileNetV2

1.Setup enviorment using pip install -r requirments.txt

2. Train Model using python3 mask-detector-model.py

3. To apply this model on an Image, python3 mask-detector-image.py -i [path of image]

4. To apply this model on an Vide, python3 mask-detector-video.py -v [path of Video]

#### COMMENTS:

We have an accuracy of ~99% which is quite good. The model is able to detect if a person is wearing a face mask or not when the image has less number of people.
This model could further be improved by retraining it on a much wider dataset and with more epochs.
Due to Hardware limitiations this model was trained only for 30 epochs.
