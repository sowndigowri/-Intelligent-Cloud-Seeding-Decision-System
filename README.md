# -Intelligent-Cloud-Seeding-Decision-System
Intelligent Cloud Seeding Decision System using AI &amp; Reinforcement Learning A machine learning and deep learning project that predicts cloud types from images and decides whether cloud seeding is feasible based on weather conditions. Includes a Streamlit interface for real-time testing.
# Cloud Seeding Decision System

An AI-powered project that simulates intelligent cloud seeding decisions based on **cloud images** and **weather data**.

## Features
- **Cloud Classification:** CNN-based or brightness-based cloud type detection.
- **Rainfall Prediction:** Random Forest regression model to estimate rainfall based on weather parameters (humidity, pressure, temperature, wind speed).
- **Decision Logic:**  
  - 🌧️ **SEED NOW** – thick clouds and low rainfall  
  - ⏳ **WAIT** – medium clouds  
  - ☀️ **DO NOT SEED** – no clouds or high rainfall
- **Streamlit Interface:** Upload cloud images, adjust weather sliders, and view predictions in real-time.
- **Reinforcement Learning:** Q-learning simulation for decision-making in cloud seeding scenarios.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/username/CloudSeedingProject.git
cd CloudSeedingProject
pip install -r requirements.txt
streamlit run app.py
