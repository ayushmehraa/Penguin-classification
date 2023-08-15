<div align="center">
    <h1 align="center">
        <img width="100" height="100" src="https://img.icons8.com/plasticine/100/pinguin.png" alt="pinguin"/>
        <br>Penguin Classification
    </h1>
</div>
<h3 align="center">
classify Penguin Species.
</h3>
<br>

# 🤖 Penguin Classification

This repository contains a machine learning project for classifying penguin species using their features. The project focuses on utilizing data, building a classification model, and deploying a Streamlit web application for easy interaction.

# ⚒️ Project Structure
The project is organized into the following structure:

```
.
├── artifacts/
│   ├── penguin_clean.csv
│   ├── penguin_clf.pkl
├── notebooks/
│   ├── penguin_model_building.ipynb
├── app.py
├── requirements.txt
└── README.md

```

- The artifacts/ folder contains subdirectories for data and trained model.

the dataset used for training and evaluation (penguin_cleaned.csv).
models -  the trained machine learning model (penguin_clf.pkl).
- The notebooks/ folder holds the Jupyter Notebook (penguin_model_building.ipynb) used for data preprocessing, model training, and evaluation.

- [app.py](https://ayushmehraa-penguins-classificatio-app-2mqfhf.streamlit.app/) is the main Streamlit application file that implements the penguin classification app.

- requirements.txt lists the required dependencies to run the project. Use the following command to install them:
```
pip install -r requirements.txt

```

# 🚀 Usage
1. Clone this repository to your local machine using:
```
git clone https://github.com/ayushmehraa/penguin-classification.git

```
2. Navigate to the project directory:
```
cd penguin-classification

```
3. Install the required dependencies:

```
pip install -r requirements.txt

```
4. Run the Streamlit app:
```
streamlit run app.py

```

5. Interact with the Streamlit app through your browser to classify penguin species using their features.

# 🤝 Contributors
Feel free to contribute to this project by creating pull requests, reporting issues, or suggesting improvements. Your contributions are greatly appreciated!

# 💳License
This project is licensed under the MIT License.
