# Project_AVS
 This repository contains our solution for the CVPR Event-based Image Deblurring Challenge. The goal of the challenge is to restore sharp intensity images from blurred frames using information provided by event cameras.

Event cameras asynchronously capture changes in brightness at each pixel with microsecond resolution, making them ideal for high-speed or low-light scenarios where traditional cameras produce motion blur. By combining blurred intensity images with high-temporal-resolution event streams, we aim to reconstruct sharp and temporally consistent images.

## Highlights

- Event-guided deblurring architecture  
- Fusion of event data and blurry RGB frames  
- Temporal alignment of events and frames  
- Trained and evaluated on the CVPR challenge dataset
