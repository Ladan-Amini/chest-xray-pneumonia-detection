# Chest X-Ray Pneumonia Classification

## Project Overview
This educational project uses a pretrained deep learning model to classify chest X-ray images into two categories: NORMAL and PNEUMONIA.

The project demonstrates a basic medical AI workflow using Python, Hugging Face Transformers, and Gradio.

## Model
- Model: dima806/chest_xray_pneumonia_detection
- Task: Image classification
- Output classes: NORMAL and PNEUMONIA

## Dataset
The project uses the Hugging Face dataset:
Hassaan90/chest-xray-pneumonia

A small, balanced sample of images is used for exploratory evaluation.

## Features
- Upload chest X-ray images for classification
- Display model prediction scores
- Evaluate predictions on a small sample
- Calculate accuracy, precision, recall, and F1-score
- Generate a confusion matrix
- Export evaluation results to CSV

## Technologies
- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Gradio
- Pandas
- Matplotlib
- Scikit-learn
- Pillow

## Project Files
- `Medical_AI_Project.ipynb`: Main project notebook
- `chest_xray_evaluation.csv`: Evaluation results
- `README.md`: Project documentation
- `requirements.txt`: Python dependencies

## Important Limitations
This project is for educational purposes only and is not intended for clinical use.

The evaluation uses a small sample and does not establish clinical accuracy or generalizability. Model prediction scores should not be interpreted as calibrated probabilities or as a measure of disease severity.

This project is not a substitute for professional medical assessment.

## How to Run
1. Open `Medical_AI_Project.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Upload one or more chest X-ray images in the Gradio interface.
4. Review the predictions and exploratory evaluation results.

## Author
Ladan Amini
