# 🌿 **PlantWise**  
*Your Ayurvedic Health Companion for Disease Prediction and Natural Remedies*  

---

## 🌟 **Overview**  
**PlantWise** is a machine learning tool designed to predict diseases based on symptoms and offer **Ayurvedic remedies**. Its **user-friendly interface** makes it easy to input symptoms and receive predictions along with natural treatments.

---

## ✨ **Key Features**  

- **🔍 Disease Prediction:**  
   Utilizes a **RandomForestClassifier** to predict potential diseases from a list of user-provided symptoms.  
   
- **🌱 Ayurvedic Remedies:**  
   Suggests **effective**, natural remedies based on the predicted diseases using traditional Ayurvedic knowledge.

- **💻 User-Friendly Interface:**  
   Offers an **intuitive graphical interface** for symptom input and instant remedy suggestions.

---

## 🛠 **Project Components**  

### `main.py`
- **Loads and preprocesses** the dataset.
- Trains a machine learning model using **RandomForest**.
- **Predicts diseases** and provides corresponding Ayurvedic remedies.

### `gui.py`
- Built using **Tkinter** to create a simple yet effective GUI.
- Handles **user inputs**, processes symptom data, and displays **predictions and remedies**.

### `dataset.csv`
- A structured dataset containing **symptoms, diseases, and Ayurvedic remedies**.

---

## 🧑‍💻 **How to Use**  

1. **Enter symptoms** in the input field on the GUI.
2. Click the **"Submit"** button to get the **disease prediction**.
3. Receive **Ayurvedic remedies** for the predicted disease.

---

## 🚀 **Future Enhancements**  

- **Expand the dataset** to improve **prediction accuracy**.
- **Explore advanced machine learning models** for more precise predictions.
- **Incorporate user feedback** for continuous improvement of the tool.