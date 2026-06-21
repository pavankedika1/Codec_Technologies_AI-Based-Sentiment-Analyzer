# AI-Based Sentiment Analyzer
## Overview
AI-Based Sentiment Analyzer is a Natural Language Processing (NLP) project that analyzes user reviews, social media posts,
and customer feedback to determine sentiment. The application uses a Transformer-based model from Hugging Face to classify text as Positive, 
Negative, or Neutral and provides confidence scores along with visualized sentiment reports.

## Features
* Real-time sentiment analysis
* Positive, Negative, and Neutral classification
* Confidence score prediction
* Interactive web interface using Flask
* Sentiment visualization using Matplotlib
* Transformer-based NLP model
* User-friendly dashboard

## Technologies Used
* Python
* Flask
* Hugging Face Transformers
* PyTorch
* Matplotlib
* HTML/CSS

## Installation
### Clone the Repository
```bash
git clone https://github.com/your-username/AI-Based-Sentiment-Analyzer.git
cd AI-Based-Sentiment-Analyzer
```
### Install Dependencies
```bash
pip install flask transformers torch matplotlib
```
## Run the Application
```bash
python app.py
```
Open your browser and visit:
```text
http://127.0.0.1:5000
```
## Example Input
```text
This product is amazing and works perfectly.
```
## Example Output
```text
Sentiment: Positive
Confidence: 98.5%
```

## How It Works
1. User enters a review or social media text.
2. Flask receives the input.
3. Hugging Face Transformer model analyzes the sentiment.
4. The model predicts Positive, Negative, or Neutral sentiment.
5. Confidence score is displayed.
6. A sentiment chart is generated and shown to the user.

## Learning Outcomes
* Natural Language Processing (NLP)
* Transformer Models
* Sentiment Analysis
* Flask Web Development
* Data Visualization
* AI Application Deployment

## Future Enhancements
* MongoDB Integration
* User Authentication
* Sentiment History Tracking
* PDF Report Generation
* Advanced Dashboard Analytics
* Social Media API Integration

## Author
Pavan Kedika
B.Tech - Artificial Intelligence & Machine Learning

This project is developed for educational and learning purposes.
