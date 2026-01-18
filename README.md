# Smart Mobility Assignment: Traffic Optimization System 🚦

# About This Project
Welcome to my Smart Mobility submission!

This project explores how Artificial Intelligence can solve real-world traffic problems. I built a simulation that analyzes traffic patterns (like vehicle count and speed) to predict congestion levels in real-time.

The goal was to move away from manual guesswork and use a data-driven approach—specifically a **Random Forest Classifier**—to make accurate decisions about road conditions.

# What I Built
Instead of just a static report, I created a fully functional data pipeline:
* **Automated Data Loading:** I wrote the code to pull the dataset directly from this GitHub repository. You don't need to upload any CSV files manually to Google Colab—it just works.
* **Intelligent Filtering:** The system automatically cleans the data and focuses on a specific 7-day window (March 1st - March 7th) to simulate a weekly operation cycle.
* **AI Prediction:** The model learns from historical data to classify traffic as **Low**, **Medium**, or **High** congestion.

# Project Structure
Here is a quick guide to the files in this repo:
* `SAIA1123_Assignment.ipynb` : The main code. This is the Jupyter Notebook where the simulation runs.
* `smart_mobility_dataset.csv` : The raw data source used for training the model.
* `traffic_brain.pkl` : The saved AI model (so we don't have to retrain it every single time).
* `traffic_data_7days.pkl` : The processed week of data used for the simulation.

# How to Run the Code
I designed this to be as "plug-and-play" as possible for Google Colab:

1.  Open the `.ipynb` file.
2.  Click the **"Open in Colab"** button (or download and upload it manually).
3.  **Run All Cells.**

---
*Created by Afnan Isyraf bin Jusrry for SAIA1123.*
