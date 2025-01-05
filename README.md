# Comparative Analysis of Vehicle Detection Using YOLOv8, RT-DETR, and DETR

## Overview
This project compares three object detection models—YOLOv8, RT-DETR, and DETR—on a traffic video dataset. We evaluate detection accuracy, vehicle counts, confidence scores, and class-wise distributions. The goal is to analyze the effectiveness of each model for real-time vehicle detection in traffic monitoring applications.

## Key Contributions
- Implementation and evaluation of YOLOv8, RT-DETR, and DETR for vehicle detection.
- Comparative analysis of detection performance.
- Visualizations of results including vehicle counts, confidence scores, and class-wise distributions.

## Results
- **Vehicle Count Per Frame**: RT-DETR detects more vehicles compared to YOLOv8 and DETR.
- **Confidence Scores**: RT-DETR exhibits higher confidence, especially for larger vehicles.
- **Class-wise Distribution**: RT-DETR shows strong performance in detecting cars, trucks, and buses.

## Conclusion
RT-DETR outperforms YOLOv8 and DETR in terms of accuracy, particularly for smaller objects, while YOLOv8 offers faster inference speeds.

## Future Work
- Optimize RT-DETR for real-time performance.
- Test models on larger datasets.
- Explore hybrid models combining YOLOv8's speed with RT-DETR's accuracy.
