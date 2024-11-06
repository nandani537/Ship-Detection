# Ship Detection in Satellite Imagery

This project focuses on detecting ships in satellite images using machine/deep learning techniques. The dataset used is sourced from Kaggle: [Ships in Satellite Imagery](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery).

## 🚀 Project Overview

This project demonstrates the complete process of detecting ships within satellite images. The workflow includes data preprocessing, model training, evaluation, and deployment.

## 📂 Project Structure


## 📊 Dataset

- **Source**: [Ships in Satellite Imagery on Kaggle](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery)
- **Description**: The dataset consists of satellite images labeled for the presence or absence of ships.
- **Format**: `.jpg` images with corresponding labels in JSON format.
- **Contents**:
  - `images/`: Folder containing satellite images.
  - `shipsnet.json`: JSON file containing image labels and bounding box information.

## 📝 Steps

1. **Data Preprocessing**:
   - Load images and labels from the dataset.
   - Resize and normalize images to make them suitable for model input.
   - Split data into training, validation, and testing sets.

2. **Model Training**:
   - Use a Convolutional Neural Network (CNN) to classify images.
   - Train the model on preprocessed images.
   - Save the trained model for later use.

3. **Evaluation**:
   - Evaluate model performance using metrics such as accuracy, precision, and recall.
   - Visualize results with confusion matrices and example predictions.

4. **Deployment**:
   - Prepare code for deploying the model to make predictions on new satellite images.
   - Utilize a web framework like Flask for serving the model as an API (optional).

## 🔧 Technologies Used

- **Python**: Core programming language for the project.
- **CNN**:Deep learning algorithm for image data used for training the model.
- **Jupyter Notebook**: For data exploration and model training.

## 🚀 Usage

To run the model and view predictions:

1. **Open `ship_detection.ipynb`**.
2. Run each cell to preprocess the data, train the model, and visualize the predictions.

## 🔗 Hosting on GitHub

The project files, including the notebook and data file, are hosted on GitHub. For large files (like datasets), **Git LFS** is used to manage file size limitations.

## 🖥️ Installation and Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/nandani537/Ship-Detection.git

2. **Navigate to the project folder**:

   ```bash
  cd Ship-Detection

3. **Install the required packages**:

   ```bash
  pip install -r requirements.txt

4. **Run the Jupyter Notebook**:

   ```bash
  jupyter notebook ship_detection.ipynb
