# Road Traffic Monitoring System

## Overview

This project addresses the imperative challenge of automating the intricate task of vehicle counting and tracking within traffic surveillance videos. Leveraging the powerful OpenCV library, our proposed solution intricately integrates background subtraction, morphological operations, and a sophisticated correlation-based tracking algorithm. The system achieves high accuracy for both in-traffic and out-traffic scenarios, 
specifically in videos of the widely used mp4 format. The comprehensive methodology encompasses contour analysis, a pivotal component for robust vehicle identification. Furthermore, the project features dedicated code for both in-traffic and out-traffic scenarios, providing adaptability to diverse traffic situations. This system's effectiveness is underscored by its capacity to seamlessly automate the vehicle counting process, 
offering not only precision but also valuable insights for sophisticated traffic management and surveillance applications.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Install the required Python packages using the following commands:
```bash
pip install -r requirements.txt
```
## Usage
-Open in_traffic.ipynb and run the cells to monitor incoming traffic.

-Open out_traffic.ipynb and run the cells to monitor outgoing traffic.

-Make sure to have the highway.mp4 video file in the same directory as the notebooks or update the file path in the cap = cv2.VideoCapture('highway.mp4') line, that is available under Data/ directory.

## Notes
-Press 'q' to exit the video stream.

-The system counts and displays the number of cars either coming in (IN) or moving out (OUT).

-Adjustments to the code may be needed based on specific video file characteristics.

## Results

Gives the count of vehicles that are incoming and outgoing from the video file.

## License
This project is licensed under the MIT License.

