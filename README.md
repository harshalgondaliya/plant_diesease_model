# Plant 🌱 Disease 🐛 Detection 🔎

Plant Disease Detection is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.


## Datasets 🔗

(https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

## Project Structure 📂

The project comprises essential components:

- `PDS.ipynb`: Jupyter Notebook with the code for model training.
- `main.py`: Streamlit web application for plant disease prediction.
- `Model.h5`: Pre-trained model weights.
- `need.txt`: List of necessary Python packages.

## Installation 🚀

To run the project locally, follow these steps:

1. **Clone the repository:**

```bash
github clone https://github.com/harshalgondaliya/plant_diesease_model
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

Once the application is running, open your web browser and navigate to [http://localhost:8501](http://localhost:8501). Upload an image of a plant leaf, and the system will predict if it is affected by any disease.

## Model Training 🧠

The model was trained using the `PDS.ipynb` notebook. It employs a Convolutional Neural Network architecture to classify plant images into different disease categories. The trained model weights are saved in `Model.h5`.

## Web Application 🌐

The web application (`main.py`) empowers users to interact with the trained model. Upload plant images, and the application provides real-time predictions regarding the health of the plant.

## Requirements 🛠️

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0
