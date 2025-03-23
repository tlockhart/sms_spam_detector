# SMS Spam Text Classification: Branched Neural Network

## Summary

This repository hosts a Jupyter Notebook showcasing a neural network model designed to classify SMS messages as spam or ham. The model is designed with a branched neural network structure and includes a Gradio user interface for easy interaction.

Key features include:
1. **SMS Message Input**: The Gradio UI provides an input box where users can submit an SMS message.
2. **Classification Output**: The UI displays whether the SMS message is classified as "spam" or "ham" in an output box.
3. **Neural Network Model**: A branched neural network trained to accurately predict the classification of SMS text messages.

---

## Branched Neural Network Diagram
![Screenshot1](./Branched_Neural_Network_Diagram.png)

---

## Setup

The Jupyter Notebook for this project is named `sms_text_classification.ipynb`. Ensure you have the required dependencies installed before proceeding.

### Requirements

1. Python v3.10 or later
2. Jupyter Notebook
3. Visual Studio Code or any other preferred IDE

---

## Installation Steps

1. **Create a new Conda environment for the project in the Terminal:**

   ```bash
   conda create -n llm python=3.10 anaconda -y
   conda activate llm
   pip install keras==3.8.0 keras-preprocessing==1.1.2 keras-tuner==1.4.7 Tf-keras==2.16.0
   pip install transformers sentence-transformers gradio
   ```
2. Open Visual Studio Code
3. Open the `gradio_sms_text_classification.ipynb` jupyter notebook.
4. Select Run All
5. Select Python 3.10.4.1 and llm, if prompted for kernel 
6. Click the public gradio link to open your webbrowser
7. Enter the sample SMS text info
8. Click submit
