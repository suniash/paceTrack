
# PaceTrack: Vehicle Tracking and Speed Estimation with YOLOv8

PaceTrack repository demonstrates advanced vehicle tracking and speed estimation techniques leveraging the state-of-the-art YOLOv8 model. This repository is meticulously crafted to showcase the seamless integration of YOLOv8 into two comprehensive Jupyter Notebooks, offering an immersive exploration of vehicle tracking and speed estimation methodologies.

## Dataset

The video data used in these notebooks was obtained from Roboflow, a platform that simplifies dataset management, preprocessing, and augmentation. You can access the video data used in this project from [Roboflow](https://roboflow.com/).

## Supervision from Roboflow

[Supervision](https://supervision.roboflow.com/latest/) is a comprehensive library that provides various tools and utilities for computer vision tasks, including object detection, instance segmentation, and more. One of its notable features is polygon zone detection, which allows users to define custom regions of interest (ROIs) within images or video frames. The speed estimation notebook utilizes the polygon zone for speed calculations.

With Supervision's polygon zone detection functionality, users can:

### Define Custom ROIs

Users can specify polygonal regions within images or video frames by providing the coordinates of the vertices of the polygon. This enables selective processing and analysis of specific areas of interest within the visual data.

### Filter Detections

Once the polygon zones are defined, Supervision can filter out detections that fall outside these zones. This ensures that only relevant objects or events within the specified regions are considered for further analysis or annotation.

### Dynamic Configuration 

Supervision offers flexible configuration options for polygon zone detection, allowing users to adjust parameters such as polygon shape, size, and position dynamically based on their specific requirements.

### Integration with Object Detection and Tracking

Polygon zone detection seamlessly integrates with other functionalities of Supervision, such as object detection and tracking. This enables comprehensive analysis and annotation of visual data within specified polygonal regions.

Overall, Supervision's polygon zone detection feature provides users with a powerful tool for defining, filtering, and analyzing custom regions of interest within images and video frames, enhancing the flexibility and effectiveness of computer vision applications. 

![](/images/polygon_det.png)

## Project Structure

### Vehicle Speed Estimation with YOLov8.ipynb
 
This notebook demonstrates the application of YOLOv8 for estimating the speed of vehicles in videos. It utilizes YOLOv8's detection capabilities to detect vehicles and estimate their speeds based on their trajectories.

### Track and Count Vehicles with YOLOv8.ipynb

This notebook showcases vehicle tracking and counting using YOLOv8. It includes functionalities for vehicle detection, tracking, and counting, providing insights into vehicle movement and density in videos.

## Getting Started

To get started with this project, clone the repository to your local machine or directly to your preferred development environment: git clone https://github.com/suniash/paceTrack.git

- Run the Jupyter Notebook to train the model

## Results

### Vehicle Speed Estimation with YOLOv8

![](/images/speed_track.png)

### Track and Count Vehicles with YOLOv8

![](/images/result.png)

## Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
The YOLOv8 team for the powerful and efficient model. The creators of the datasets used in this project and Roboflow for providing supervision and platform for seamless integration of datasets in notebooks.

