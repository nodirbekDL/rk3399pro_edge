# RK3399Pro Object Detection Project

### Short Description
A project leveraging the Rockchip RK3399Pro device for object detection, involving the conversion of trained PyTorch models to the RKNN format for efficient NPU inference on the RK3399Pro.

### Key Features/Technologies
- **Deep Learning Training**: Employed PyTorch with the YOLOv7 model for object detection training.
- **Model Conversion**: Converted PyTorch models to ONNX format, and subsequently from ONNX to RKNN using the RKNN tool 1.7.3, as there is no direct library for PT to RKNN conversion.
- **Edge Device Optimization**: Focused on running inferences on the RK3399Pro's NPU for efficient and real-time object detection.

### Detailed Explanation

#### Deep Learning Training
- **Model**: Utilized the YOLOv7 model for training object detection.
- **Framework**: PyTorch was the framework used for training due to its flexibility and support for state-of-the-art models.
- **Training Environment**: Training was conducted on a high-performance GPU system to expedite the process and achieve accurate results.

#### Model Conversion
- **ONNX Conversion**: The trained PyTorch model was first converted to ONNX format, providing a standardized intermediate representation.
- **RKNN Conversion**: Using RKNN tool 1.7.3, the ONNX model was further converted to RKNN format. This step was crucial for enabling the model to run on the RK3399Pro's NPU.

#### Edge Device Optimization
- **NPU Inference**: The RK3399Pro's NPU was leveraged to perform efficient and real-time object detection. The optimization ensured that the model could run smoothly on the edge device, providing quick and accurate detections.

### Challenges and Learnings
One significant challenge was the lack of comprehensive articles, documentation, and forums specifically for the RK3399Pro device. Most of the resources were in Chinese, requiring the use of translation tools and extra effort to implement the solutions effectively. This experience highlighted the importance of resourcefulness and adaptability in navigating non-English technical resources.

### Screenshots/Media
![RK3399Pro Object Detection Screenshot](link-to-screenshot)

### Link to Project/Repository
[GitHub Repository](https://github.com/username/rk3399pro-object-detection) | [Live Demo](https://username.github.io/rk3399pro-object-detection/)

### Usage

#### Basic Usage
Once the model is converted to RKNN format and deployed on the RK3399Pro, it can perform real-time object detection using the device's NPU. The setup involves configuring the RKNN model to run on the edge device and monitoring the detections through a connected interface.

#### Configuration
The project allows for customization of detection parameters to suit specific needs. Adjust detection thresholds, specify objects of interest, and configure notifications or alerts based on detection results.

#### Advanced Features
- **Real-time Monitoring**: Set up a monitoring system to visualize detections in real-time, providing immediate feedback on object presence.
- **Detailed Reports**: Generate reports on object detection performance over time to evaluate and improve model accuracy.

---

This summary provides an overview of the RK3399Pro Object Detection Project, including its key features, technologies, and usage instructions. Let me know if you need more detailed documentation or further assistance with this project!
