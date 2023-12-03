# Sign Language Detector

This project involves real-time hand gesture recognition using OpenCV and a pre-trained Keras model. The system detects hand gestures captured through a webcam and classifies them into predefined labels.

## Overview

The project uses the following components:

- [cv2](https://github.com/opencv/opencv) : OpenCV library for computer vision.
- [cvzone](https://github.com/cvzone/cvzone) : A library providing tools for computer vision applications.
- [Keras](https://github.com/keras-team/keras) : A high-level neural networks API.

## Setup

1. Install the required libraries:

   ```bash
   pip install opencv-python
   pip install numpy
   pip install keras
   pip install mediapipe
   ```

2. Download the pre-trained Keras model (`keras_model.h5`) and labels (`labels.txt`) from the `Model` directory.

3. Run the main script:

   ```bash
   python dataCollection.py
   python test.py
   ```

## Usage

1. Execute the script, and it will open a window displaying the webcam feed.

2. Make hand gestures within the camera frame, and the system will classify them based on the trained model.

3. The recognized gestures and their corresponding labels will be displayed on the screen.

## Customization

- **Adding New Gestures**: You can expand the dataset and train the model to recognize additional gestures. Update the `labels` list with the new gesture labels.

- **Adjusting Parameters**: Fine-tune parameters like `imgSize`, `offset`, and others in the script to optimize the performance based on your requirements.

## Examples

Here are some example gestures that the system can recognize:
<br>
<br>
Gesture A 
<br>
<br>
![Image_1699424094 89653](https://github.com/RAJA-2004/sign-language-detector/assets/113360474/b7f7401c-9919-424c-8022-d13e82724a3a)
<br>
<br>
Gesture C
<br>
<br>
![Image_1699425008 7019598](https://github.com/RAJA-2004/sign-language-detector/assets/113360474/feeaa704-54c1-4649-897c-793a1befb74a)
<br>
<br>
Gesture F
<br>
<br>
![Image_1699452636 749215](https://github.com/RAJA-2004/sign-language-detector/assets/113360474/d4ce3291-8107-4d48-8adc-5a0b5dcfa6c3)




## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and enhance the functionality!
