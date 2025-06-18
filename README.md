# 🌟 Let It Glow – Skin Type Classification Web App

**Let It Glow** is a web application that uses deep learning to classify skin types from uploaded images. The application is designed to be user-friendly and can predict whether a person's skin is **dry**, **oily**, **normal**, or **combination** based on facial image input.

## 🚀 Features

- Upload an image to detect skin type
- Deep learning model based on **MobileNetV2**
- Lightweight and fast
- Clean and simple HTML/CSS interface
- Runs locally using Flask

## 💄 Product Recommendation

Based on the detected skin type, the app suggests basic skincare product types (e.g., cleanser, moisturizer) tailored for:

- Dry Skin → Hydrating and rich moisturizers
- Oily Skin → Lightweight and non-comedogenic products
- Normal Skin → Balanced formulas
- Combination Skin → Zone-specific care recommendations

## 🧠 Model

- Architecture: MobileNetV2
- Format: Keras `.h5` model file
- Input: Facial image
- Output: One of four skin types

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **TensorFlow / Keras**
- **HTML / CSS / Jinja2**

## Sample Usage

Upload a clear image of your face and click “Predict”. The model will classify your skin as:
- **Dry**
- **Oily**
- **Normal**
- **Combination**

## Images from the Website
<img width="1440" alt="Screenshot 2025-06-18 at 19 36 33" src="https://github.com/user-attachments/assets/de7fe837-4752-420f-9d2b-254476ba54d4" />
<img width="1440" alt="Screenshot 2025-06-18 at 19 38 44" src="https://github.com/user-attachments/assets/4d56869f-79e3-478a-bf20-5e989b18fc4a" />


## Future Improvements

- **Enhance dataset for better generalization**
- **Add a confidence score display**
- **Deploy online (e.g., using Streamlit, Heroku)**
