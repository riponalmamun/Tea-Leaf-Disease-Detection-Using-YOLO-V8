# Tea Leaf Disease Detection Using YOLOv8, YOLOv5, and Faster R-CNN
<img width="1280" height="854" alt="image" src="https://github.com/user-attachments/assets/36d3b658-e70e-42c3-a94f-0a56c828bb8a" />


*A system for detecting diseases in tea leaves using state-of-the-art deep learning models.*

---

## Overview
This project detects **diseases in tea leaves** using deep learning models **YOLOv8, YOLOv5, and Faster R-CNN**. It can detect diseases from live images and provide **treatment suggestions**, helping tea farmers maintain healthy crops.

The dataset contains images of tea leaves labeled with **10 classes**, collected from the **Bangladesh Tea Research Institute (BTRI), Sylhet**.

---

## Dataset
The dataset contains the following classes:

1. **Algal_Leaf_Rust**  
2. **Bug_Eaten**  
3. **Final Labelling RIPON**  
4. **Healthy_Leaf**  
5. **Labelled Dataset RIPON**  
6. **Leaf_BlightBrown_BLight_No_Ring_3**  
7. **Leaf_Spot_Diesase_Ring_Present**  
8. **Nutrient_Deficiency**  
9. **Red_Spider_Mite**  
10. **Tea_Mosqueto_Bug_Infected**  

> All images were collected from **BTRI, Sylhet**, and properly annotated for training and evaluation.

---

## Features
- **Disease Detection**: Detects tea leaf diseases with deep learning.  
- **Live Detection**: Real-time detection using your device camera.  
- **Treatment Suggestions**: Provides actionable recommendations for detected diseases.  
- **Model Comparison**: YOLOv8, YOLOv5, and Faster R-CNN are compared for performance.

---

## Technologies Used
- **YOLOv8 & YOLOv5**: Real-time object detection and classification.  
- **Faster R-CNN**: Region-based object detection model.  
- **Python**: Model training and application development.  
- **TensorFlow / PyTorch**: Deep learning frameworks.  
- **OpenCV**: Image processing and handling live inputs.  
- **Android Studio**: Mobile application for detection and suggestions.

---

## Installation & Running the App
1. Clone the repository:
```bash
git clone https://github.com/yourusername/tea-leaf-disease-detection.git
cd tea-leaf-disease-detection
```

2. Open the Android app project in Android Studio.

3. Build and run the app on your device or emulator.

4. Allow camera access to detect diseases in real-time.

Usage

Live Detection: Open the app, point the camera at a tea leaf, and get disease detection and treatment suggestions instantly.

Model Evaluation: Run testing scripts to evaluate model performance:
```bash
python test_yolov8.py
python test_yolov5.py
python test_faster_rcnn.py
```

## Contributing

Contributions are welcome!  

- Open issues for bugs or suggestions.  
- Submit pull requests to improve detection or add new disease categories.  

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## Acknowledgements

- Bangladesh Tea Research Institute (BTRI) for dataset support.  
- Developers of YOLOv8, YOLOv5, and Faster R-CNN.  
- TensorFlow / PyTorch communities.  
- OpenCV contributors.  

Happy Tea Farming! 🍃  

---

If you want, I can **also make a final version with a clean table for classes** and badges for Python, PyTorch, and Android Studio — this will make your GitHub README **look very professional**.  

Do you want me to do that?


---

## Sample Class Images

Here are some examples from the dataset for each tea leaf class:

| Class Name | Sample Image |
|------------|--------------|
| Algal_Leaf_Rust | ![img_7498](https://github.com/user-attachments/assets/edbf2af9-6d28-4e62-8844-fcbd4a3fab7d) |
| Bug_Eaten | ![img_9062](https://github.com/user-attachments/assets/dd86e415-e0a8-431e-b427-728be6e1baa7) |
| Final Labelling RIPON | ![Final Labelling RIPON](https://github.com/user-attachments/assets/3bceecbb-022f-46ab-8181-610d5d21c689) |
| Healthy_Leaf | ![img_3](https://github.com/user-attachments/assets/32110469-8b2a-4e53-bf66-466b37730818) |
| Labelled Dataset RIPON | ![Labelled Dataset RIPON](https://github.com/user-attachments/assets/c24d895d-c01f-4060-b911-f3b8d574d6d8) |
| Leaf_BlightBrown_BLight_No_Ring_3 | ![img_1378](https://github.com/user-attachments/assets/6a222952-f2c5-4390-93e8-6785c03d3ed4) |
| Leaf_Spot_Diesase_Ring_Present | ![img_6306](https://github.com/user-attachments/assets/2f048700-5841-4ff0-bb36-720a4fe1d34c) |
| Nutrient_Deficiency | ![img_9950](https://github.com/user-attachments/assets/67725afb-0a53-43db-ba56-761b9dd79ab9) |
| Red_Spider_Mite | ![img_4394](https://github.com/user-attachments/assets/a7a99ee1-f910-43d0-baab-d5a4618bcf47) |
| Tea_Mosqueto_Bug_Infected | ![img_10529](https://github.com/user-attachments/assets/f5d05714-79cb-4e71-877a-aff318736c6d) |

> These images provide a quick visual understanding of the dataset used for training the models.


