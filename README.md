# 🐧 Penguin Species Prediction – Streamlit Machine Learning App

This project is an interactive **Streamlit web application** that predicts the **species of a penguin** using a machine-learning model trained on the **Palmer Penguins dataset**.

The app allows users to:
- Explore the dataset  
- Visualize penguin measurements  
- Adjust input features using sidebar controls  
- Generate species predictions with probability scores  

---

## 🚀 Features

### ✅ **1. Load and Explore Data**
- Automatically loads the cleaned penguins dataset from GitHub.
- Shows raw data, feature matrix (X), and target vector (y).

### 🖼️ **2. Data Visualization**
- Interactive scatter plot of **bill length vs body mass**, colored by species.

### 🎛️ **3. User Input Controls**
Users can adjust penguin characteristics:
- Island  
- Sex  
- Bill length  
- Bill depth  
- Flipper length  
- Body mass  

These inputs are used to generate predictions.

### 🧹 **4. Data Preparation**
- Handles categorical encoding using `pd.get_dummies()`.
- Maps species to numerical labels for model training.

### 🤖 **5. Machine Learning Model**
A **RandomForestClassifier** is trained directly inside the app using:
- Encoded feature matrix (X)
- Encoded target labels (y)

### 📊 **6. Prediction Output**
The app displays:
- Prediction probabilities for each species (Adelie, Chinstrap, Gentoo)
- Highlighted predicted species

---

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://jose-ml-app.streamlit.app/)

## GitHub Codespaces

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/streamlit/app-starter-kit?quickstart=1)
