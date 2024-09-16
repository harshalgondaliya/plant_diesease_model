# 🌿 Plant Disease Detection 🐛🔍

Plant Disease Detection is a machine learning project aimed at identifying and classifying diseases in plants using Convolutional Neural Networks (CNN). By providing farmers and agricultural experts with quick and accurate plant health diagnostics, the project aims to facilitate timely interventions, reducing the risk of crop loss and improving agricultural productivity.

## 📊 Dataset

The dataset used for this project contains images of healthy and diseased plant leaves and can be found [here](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).

## 📂 Project Structure

The project contains the following files and directories:

- `PDD.ipynb`: Jupyter Notebook for training the plant disease detection model.
- `main.py`: A Streamlit web app for making predictions on plant diseases.
- `Model.h5`: Pre-trained model weights used for prediction.
- `need.txt`: A file that lists the Python dependencies required to run the project.

## 🚀 Installation

To run the project on your local machine, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/harshalgondaliya/plant_diesease_model
    ```

2. Navigate to the project directory:

    ```bash
    cd Plant-Disease-Detection
    ```

3. **Install the required packages**:

    Install all necessary libraries listed in the `need.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:

    Start the web application by running the following command:

    ```bash
    streamlit run main.py
    ```

## 🌿 Usage

After running the Streamlit app, open your web browser and navigate to [http://localhost:8501](http://localhost:8501).

1. Upload an image of a plant leaf.
2. The model will analyze the image and provide predictions on whether the plant is healthy or diseased.
3. If diseased, the application will classify the type of disease.

## 🧠 Model Training

The model is trained using a Convolutional Neural Network (CNN) architecture on the plant disease dataset. The training process is documented in the `PDD.ipynb` notebook. After training, the model's weights are saved to `Model.h5`.

## 🌐 Web Application

The web application allows users to upload plant leaf images and receive real-time predictions on the health of the plant. The app is built using Streamlit, a lightweight Python web framework.

## 🛠️ Requirements

The project requires the following dependencies:

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0

You can install them by running:

```bash
pip install -r need.txt

