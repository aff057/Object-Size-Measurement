
# Object Size Measurement

This project demonstrates how to measure the size of objects using Python. It includes functionalities for both live measurement (using a webcam) and image size measurement (using pre-captured images).

## Prerequisites

- Python 3.x
- OpenCV
- NumPy

You can install the necessary libraries using pip:

```bash
pip install opencv-python numpy
```

## Usage

### Live Measurement

To measure the size of objects in real-time using a webcam, run the following command:

```bash
python file.py --mode video --width 0.955
```

The script will open the webcam feed and display the measured size of the objects in the frame.

### Image Size Measurement

To measure the size of objects in pre-captured images, run the following command:

```bash
python file.py --image images/example_01.png  --width 0.955
```

Replace `path/to/image.jpg` with the path to your image file. The script will display the measured size of the objects in the image.

## Project Structure

- `live_measurement.py`: Script for live object size measurement using a webcam.
- `image_measurement.py`: Script for measuring object size in pre-captured images.
- `README.md`: This readme file.



## Acknowledgments

- OpenCV for image processing functionalities.
- NumPy for numerical operations.

