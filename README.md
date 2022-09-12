# Multimodal_multioutput_classification
Multimodal Semantic Representation (MMSR) project

This is a multi-output classification problem, where a single model predicts 5 different labels (overall sentiment, humour, offensive, sarcastic and motivational) as output.

### Dataset
MEMOTION ANALYSIS dataset - link: https://www.kaggle.com/datasets/williamscott701/memotion-dataset-7k

Each meme has five labels: overall sentiment, humour, offensive, sarcastic and motivational

#### Project Structure

1) data - This folder contains the data for the train, validation and test subset
2) MMSR project - Multimodal multioutput classification.ipynb - Complete code for this project

This project analyses three different models: 

1) Text-only model - a distilBERT-based model which processes only the textual data
2) Image-only model - a Resnet-based model which processes only the visual data
3) Multimodal model - This model uses both textual and visual modalities
