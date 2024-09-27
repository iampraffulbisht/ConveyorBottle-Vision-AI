

---

# Glass Bottle Detection on Conveyor Belt Using YOLOv5

This project focuses on the development and optimization of a YOLOv5 model to detect glass bottles on a conveyor belt with high accuracy and efficiency. By leveraging custom-labeled data and OpenCV for real-time video processing, we achieved significant improvements in both accuracy and system throughput.

## Project Overview

The system identifies and tracks glass bottles moving on a conveyor belt, using deep learning techniques and real-time video processing. This setup is designed for industrial use cases where high-speed and precise detection is critical. The model was optimized to ensure consistent performance even on unseen data.

### Key Features:
- **YOLOv5 Custom Model**: Trained on a custom dataset of labeled glass bottle images.
- **High Detection Accuracy**: Achieved a 92% detection accuracy post-optimization.
- **Efficient Processing**: Enhanced system efficiency by 92%, capable of processing up to 500 bottles per hour.
- **Real-Time Video Streaming**: Utilized OpenCV to capture and process video streams in real-time.
- **Scalable Solution**: Works effectively in various lighting conditions and conveyor speeds.

## Results on Unseen Data

The model demonstrates consistent performance on unseen data. Below are examples of detections in real-time:
  
- ![Glass Bottle 1](https://github.com/user-attachments/assets/7ae5bc88-521b-4a9d-b61b-9e8b184ae98f)
- ![Glass Bottle 2](https://github.com/user-attachments/assets/d217e98d-2c60-4ecb-98bc-29873e3530a6)
- ![Glass Bottle 3](https://github.com/user-attachments/assets/7b16d381-b87a-4d46-8db4-0335c012aa4e)

## Model Training & Optimization

### Dataset:
- **Custom-Labeled Dataset**: The dataset consists of labeled images of glass bottles in different positions and orientations on the conveyor belt.
  
### Training:
- **Model**: YOLOv5
- **Accuracy**: Achieved a detection accuracy of 92% after several rounds of optimization.
  
### Optimization Techniques:
- **Model Hyperparameters**: Tuned hyperparameters for improved accuracy and reduced false positives.
- **Real-Time Processing**: Integrated OpenCV for capturing and processing video streams efficiently.

## System Performance

- **Processing Rate**: Capable of detecting and processing up to 500 bottles per hour.
- **Efficiency Gain**: The system efficiency was enhanced by 92%, making it suitable for high-speed industrial conveyor belt systems.
  
## Technologies Used:
- **YOLOv5**: For object detection.
- **Python & OpenCV**: For real-time video processing.
- **Custom Labeled Dataset**: Created using LabelImg for precise annotation.

## Future Improvements:
- **Further Optimization**: Additional work to fine-tune the detection algorithm for different types of bottles.
- **Deployment**: Plan to integrate the system into an industrial setup with enhanced hardware for faster processing.

