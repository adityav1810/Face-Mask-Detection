# Face Mask Detection using MobileNetV2

1.Setup enviorment using pip install -r requirments.txt

2. Train Model using python3 mask-detector-model.py

3. To apply this model on an Image, python3 mask-detector-image.py -i [path of image]

4. To apply this model on an Video, python3 mask-detector-video.py -v [path of Video]

#### COMMENTS:


Model needs to be generalized for real life scenarios as it fails to detect masks when more number of faces are present in the image

Due to Hardware limitiations this model was trained only for 30 epochs.
