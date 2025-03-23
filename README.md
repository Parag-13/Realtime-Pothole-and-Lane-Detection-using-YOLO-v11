# Realtime-Pothole-and-Lane-Detection-using-YOLO-v11
This project uses the YOLO v11 model for real-time pothole and lane detection, enhancing road safety with advanced computer vision and federated learning. It enables real-time monitoring and can integrate with autonomous vehicles or driver assistance systems to prevent accidents and improve traffic efficiency.


=> WORK DONE: Pothole Detection


-> Preprocessing:

1. Auto-Orient: Applied

2. Resize: Stretch to 640x640


-> Augmentations:

1. Outputs per training example: 3

2. Flip: Horizontal, Vertical

3. Crop: 0% Minimum Zoom, 20% Maximum Zoom

4. Rotation: Between -15° and +15°


=> WORK DONE: Lane Detection


-> Preprocessing:

1. Auto-Orient: Applied

2. Resize: Stretch to 640x640

3. Auto-Adjust Contrast: Using Adaptive Equalization

4. Greyscale: Applied


-> Augmentations:

1. Outputs per training example: 3

2. Flip: Horizontal, Vertical

3. Crop: 0% Minimum Zoom, 20%

4. Grayscale: Apply to 15% of images

5. Saturation: Between -25% and +25%

6. Blur: Up to 2.5px

7. Noise: Up to 0.1% of pixels
