# Realtime-Pothole-and-Lane-Detection-using-YOLO-v11
This project uses the YOLO v11 model for real-time pothole and lane detection, enhancing road safety with advanced computer vision and federated learning. It enables real-time monitoring and can integrate with autonomous vehicles or driver assistance systems to prevent accidents and improve traffic efficiency.


WORK DONE: Pothole Detection


Preprocessing:

Auto-Orient: Applied

Resize: Stretch to 640x640


Augmentations:

Outputs per training example: 3

Flip: Horizontal, Vertical

Crop: 0% Minimum Zoom, 20% Maximum Zoom

Rotation: Between -15° and +15°


WORK DONE: Lane Detection


Preprocessing:

Auto-Orient: Applied

Resize: Stretch to 640x640

Auto-Adjust Contrast: Using Adaptive Equalization

Greyscale: Applied


Augmentations:

Outputs per training example: 3

Flip: Horizontal, Vertical

Crop: 0% Minimum Zoom, 20%

Grayscale: Apply to 15% of images

Saturation: Between -25% and +25%

Blur: Up to 2.5px

Noise: Up to 0.1% of pixels
