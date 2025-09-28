# DOPE


[Back to Main Page](../../../README.md)

# Deep Object Pose Estimation using DOPE and Synthetic Data

This project implements the [DOPE (Deep Object Pose Estimation)](https://arxiv.org/abs/1809.10790) pipeline using **only synthetic data** generated from BlenderProc. The trained model is capable of real-time 6-DoF object pose estimation on standard YCB objects using a single RGB image—without the need for depth or real-world labeled data.


## 🎥 Demo Video
Watch the demo in action here:  
🔗 [Demo Video on Google Drive](https://drive.google.com/file/d/1Q-ruStOp8VjEdj_t6izvuaJ1Bl4fbzQc/view)
https://github.com/user-attachments/assets/735b7227-9c3b-416b-b3b8-5634fb23791b

## 📊 Presentation Slides
View the project presentation here:  
🔗 [Final Presentation PDF](https://drive.google.com/your-presentation-url)

---

## 🚀 Features

- DOPE network trained entirely on synthetic images
- Two YCB objects supported: Cracker Box and Large Marker
- Real-time inference (~15–20 FPS) with webcam
- Full support for multi-object detection
- Evaluation scripts with ADD / ADD-S metrics and graph generation

---

## 🛠 Dependencies

- Python ≥ 3.8
- PyTorch ≥ 1.10
- OpenCV
- tensorboardX
- BlenderProc
- NVISII (for evaluation) – [Install Guide](https://nvisii.com/)

---

## 🤝 Acknowledgments

- DOPE: [Tremblay et al.](https://arxiv.org/abs/1809.10790)
- BlenderProc: [Denninger et al.](https://arxiv.org/abs/1911.01911)
- YCB Dataset
- PyTorch, OpenCV, and the open-source community

---

