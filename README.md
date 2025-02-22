# Tire Classification Web Application

This is a simple web application built using Flask and TensorFlow. It classifies images of tires to determine their condition: whether they are flat, okay, or undetectable. The project uses a pre-trained deep learning model to predict tire conditions.

## Features

- Image upload for tire classification.
- Previews of uploaded images.
- Background changes based on the tire condition:
  - **Flat Tire**: `wracked-car.webp`
  - **Okay Tire**: `bolid.webp`
  - **Unidentified Tire**: `road.webp`

## Requirements

- Python 3.x
- TensorFlow
- Flask
- PIL (Python Imaging Library)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/MykhailoIvchenko/detect-flat-tire.git
cd tire-classification
```

### 2. Create a Virtual Environment
```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment
#### On macOS/Linux:
```bash
source venv/bin/activate
```
#### On Windows:
```bash
.\venv\Scripts\activate
```

### 4. Install the Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the Flask Application
```bash
flask run
```
The application will be accessible at http://127.0.0.1:5000/.

## How to Use the Application

1. **Open the homepage**: [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

2. **Upload an image** of a tire by clicking the button with plus symbol.

3. **Click the Check button** to submit the image for classification.

4. Based on the classification result, the background of the page will change, and a message with the classification result will be displayed:

   - **Flat Tire**: The background will change to `wracked-car.webp`.
   - **Okay Tire**: The background will change to `bolid.webp`.
   - **Unidentified Tire**: The background will remain as `road.webp`.

## Images set link
https://www.kaggle.com/datasets/rhammell/full-vs-flat-tire-images

## Colab link
https://colab.research.google.com/drive/1UYK66KQfMHA1I3cucpOc54sUkF4jpF6B?usp=sharing