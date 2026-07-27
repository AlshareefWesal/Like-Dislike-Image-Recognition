# Like-Dislike-Image-Recognition
Image recognition model using Teachable Machine to classify Like and Dislike hand gestures.
# Like-Dislike Image Recognition

Like-Dislike Image Recognition is a simple image classification project
developed using Google Teachable Machine. The model recognizes hand
gestures and classifies them into two categories: Like and Dislike.
After training, the model was exported in TensorFlow (Keras) format and
tested using a Python script.

------------------------------------------------------------------------

### Project Contents

`test.py`\
Loads the trained model, reads an input image, and predicts its class.

`keras_model.h5`\
The trained Keras model exported from Teachable Machine.

`labels.txt`\
Contains the class labels used by the model.

`README.md`\
Project documentation.

------------------------------------------------------------------------

### Required Libraries

``` bash
pip install tensorflow==2.12.1
pip install opencv-python
pip install pillow
pip install numpy
```

------------------------------------------------------------------------

### Running the Project

1.  Place the image to be tested inside the project folder.
2.  Update the image path in `test.py` if necessary.
3.  Open the terminal.
4.  Run:

``` bash
python test.py
```

------------------------------------------------------------------------

### Sample Output

``` text
Class: Dislike
Confidence Score: 0.98718387
```

------------------------------------------------------------------------

### Project Workflow

-   Create a new image classification project in Google Teachable
    Machine.
-   Create two classes: Like and Dislike.
-   Collect and upload training images.
-   Train the model.
-   Export the model as TensorFlow (Keras).
-   Load the model using Python.
-   Test the model with an input image.
-   Display the predicted class and confidence score.

------------------------------------------------------------------------

### Development Tools

-   Google Teachable Machine
-   Python
-   TensorFlow (Keras)
-   NumPy
-   Pillow
-   OpenCV
