# 🛡️ Real-Time Smart Surveillance System

A comprehensive real-time surveillance system with capabilities such as face recognition, face registration, motion detection (both full-frame and specific regions), and theft alarm activation.
 
---


## 📚 Table of Contents

- [🔍 Overview](#-overview)
- [✨ Features](#-features)
- [⚙️ Installation](#-installation)
- [🚀 Usage](#-usage)
- [🛠️ Configuration](#-configuration)
- [🤝 Contributions](#-contributions)
- [📬 Contact](#-contact)




---

## 🔍 Overview

This Real-Time Smart Surveillance System is built to address modern security needs using advanced computer vision techniques. It provides intelligent detection and monitoring capabilities, allowing organizations and individuals to track activities in real-time with precision and reliability.

---

## ✨ Features

- **👁️ Face Recognition**  
  Automatically identify and verify individuals using facial recognition.

- **🧑‍💻 Person Face Registration**  
  Register new faces dynamically to update the face recognition database.

- **🎯 Motion Detection**  
  Detect motion in the full frame or user-defined regions of interest.

- **🚨 Theft Alarm Trigger**  
  Instantly trigger alerts when unauthorized access or suspicious activity is detected.

---

## ⚙️ Installation

Follow these steps to get started:

### 1. Clone the Repository

```bash
git clone https://github.com/adeshjais/Real-Time_Surveillance-System
cd Real-Time_Surveillance-System
```

### 2. Set Up the Virtual Environment

Make sure Python 3.8 or higher is installed on your system. Then, set up a virtual environment:

```bash
# Create a virtual environment
python -m venv venv

# Activate the environment

source venv/bin/activate   # On macOS/Linux:
venv\Scripts\activate      # On Windows:
```

### 3. Install Dependencies

With the virtual environment activated, install the required dependencies:

```bash
pip install -r requirements.txt
```
---

## 🚀 Usage

Each module can be run independently based on your requirements:

### 👁️ Face Recognition

  Run the following command to start face recognition:
```bash
python face_recognition.py
  ```
### 🧑‍💻 Person Face Registration

   Run the following command to register a new face:
```bash
python face_register.py
```

  Follow the on-screen instructions to capture and register new faces.

### 🎯 Motion Detection

1. **Run the motion detection module**:
    ```bash
    python motion_detection.py
    ```

2. **Specify detection areas**: Configure the module to detect motion in full frame or specific regions as needed.

### 🚨 Theft Alarm Trigger

1. **Run the theft alarm module**:
    ```bash
    python theft_alarm.py
    ```

2. **Set up alert mechanisms**: Configure the system to trigger alarms through various means (e.g., sound, email, SMS).

---

## 🛠️ Configuration

Adjust configuration settings in the provided configuration files:

- ```config.json```:
  Set parameters such as camera source, detection thresholds, and alarm settings.
- **Environment variables**: Use environment variables for sensitive information like API keys and access tokens.

---

## 🤝 Contributions

We welcome contributions to improve and expand the Real-Time Smart Surveillance System!

To contribute:

1. **Fork** the repository  
2. **Create a new branch**  
    ```bash
    git checkout -b feature-branch
    ```
3. **Make your changes**  
4. **Commit** your updates  
    ```bash
    git commit -am "Add a new feature"
    ```
5. **Push** to your branch  
    ```bash
    git push origin feature-branch
    ```
6. **Create a Pull Request**  
    - Go to the original repository on GitHub
    - Click on **Pull Requests** → **New Pull Request**

Please ensure your changes are well-documented and tested before submitting a PR. Thanks for helping us grow!

---

## 📬 Contact

For issues, suggestions, or collaboration:

- **GitHub**: [@adeshjais](https://github.com/adeshjais)
- **Email**: adeshjaiswal23@gmail.com
