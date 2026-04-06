# Plant 🌱 Disease 🐛 Detection 🔎
## Author
**Sneha Shaw**  
B.Tech CSE – 3rd Year



## Project Description
Plant Disease Detection is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.



## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- Streamlit


## Development Environment
The project was implemented and tested using:
- Visual Studio Code
- Python
- Streamlit


## Project Structure 📂

The project comprises essential components:

- `main_app.py`: Streamlit web application for plant disease prediction.
- `plant_disease_model.h5`: Pre-trained model weights.
- `requirements.txt`: List of necessary Python packages.


## Features

- Upload plant leaf images
- Detect plant diseases using a CNN model
- Simple and interactive web interface
- Real-time prediction using Streamlit



## Installation 🚀

To run the project locally, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/snehashaw0330-arch/Plant-Disease-Detection.git
```

2. Navigate to the project directory:

```bash
cd Plant-Disease-Detection
```

3. **Install the required packages:**

```bash
pip install -r requirements.txt
```

4. **Run the Streamlit web application:**

```bash
streamlit run main_app.py
```



## Usage 🌿

Once the application is running, open your web browser and navigate to [http://localhost:8501](http://localhost:8501). Upload an image of a plant leaf, and the system will analyze the image
and predict whether the plant is healthy or affected by a disease.


## Model Information 🧠

This project uses a pre-trained Convolutional Neural Network (CNN) model
for plant disease classification.

The trained model is stored in the file `plant_disease_model.h5`.
The model analyzes uploaded plant leaf images and predicts the
corresponding plant disease class.



## Web Application 🌐

The web application (`main_app.py`) is built using Streamlit and allows users
to upload plant leaf images. The system processes the image using the trained
CNN model and provides real-time predictions about plant diseases.


## Requirements 🛠️

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0


## Future Improvements

- Support more plant disease categories
- Improve model accuracy with a larger dataset
- Add real-time camera detection
- Deploy the application on a cloud platform
