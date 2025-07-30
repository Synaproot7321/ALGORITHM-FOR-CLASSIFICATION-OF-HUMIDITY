# 💧 ALGORITHM-FOR-CLASSIFICATION-OF-HUMIDITY

*NOTE: During my experience in the mining sector, I participated in the development of a visual inspection system using machine vision to estimate the mass humidity of mineral concentrate . Out of respect for confidentiality, no images or technical details of the actual system are included. The documentation presented here is a representative simulation developed by me for demonstration purposes.*

This project presents an AI-powered solution to estimate the **mass humidity of mineral concentrate** transported via conveyor belts. The algorithm utilizes visual data from a conventional camera to predict humidity levels without physical sensors or manual sampling. This approach is ideal for mining and processing plants seeking to optimize productivity, reduce costs, and minimize equipment wear.

---

## 🎯 Objective

The main objective of this algorithm is to offer a **non-invasive, automated, and cost-effective** method to estimate the humidity of mineral concentrate in real-time. Traditional methods rely heavily on moisture sensors or manual samples, which are often:
- Expensive to maintain,
- Subject to frequent calibration errors,
- Affected by environmental factors like dust and vibration.

This algorithm eliminates those dependencies by using only the **visual appearance of the concentrate** (e.g., color, texture, reflectivity) to estimate moisture levels, offering:
- Better process control,
- Continuous monitoring during transport,
- Reduced need for operator intervention.

---

## 🧠 Key Features

- 📷 **Camera-Only Monitoring**  
  The system works with a regular industrial camera placed strategically over the conveyor. It captures frames as the concentrate moves and feeds them to the model.

- 🧠 **Deep Learning Prediction**  
  A trained neural network model predicts moisture levels from visual characteristics extracted from each frame. The model was trained on labeled data of wet and dry concentrate samples under different conditions.

- ⚙️ **Real-Time or Offline Processing**  
  The algorithm can work in two modes:
  - **Real-Time**, processing frames from a live camera feed.
  - **Offline**, analyzing pre-recorded videos or image sequences.

- 🚫 **Sensor-Free Design**  
  Since the algorithm only relies on image data, it avoids the common issues of wear, damage, or calibration drift seen in contact-based sensors.

- 📈 **Scalable Solution**  
  The model can be deployed on multiple conveyors with minimal configuration changes, and easily re-trained with site-specific data for increased accuracy.

---

## 🛠️ Technologies Used

- **Python 3.x** 
- **OpenCV** 
- **NumPy** 
- **PyTorch** 
- **Pandas**
- **Matplotlib**

---


<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/e3602413-7e93-40ab-bcc2-42c2ec795a92" />
