# Sentiment Analysis with RNN

This project is a sentiment analysis application that classifies movie reviews as positive or negative. It uses a pre-trained Recurrent Neural Network (RNN) model trained on the IMDB movie reviews dataset.

## Features
- Classifies user-inputted movie reviews as either **Positive** or **Negative**.
- Provides a prediction score for the sentiment.
- Built using TensorFlow and Streamlit for an interactive web interface.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python (3.7 or higher)
- pip (Python package installer)

### Install Dependencies
```bash
pip install tensorflow streamlit
```

Ensure you have the `RNN_IMDB_sentiment_model.h5` file in the project directory.

---

## Usage

### Running the Application
1. Navigate to the project directory.
2. Start the Streamlit app:
   ```bash
   streamlit run SentimentAnalysis_App.py
   ```
3. Enter a movie review in the text box and click **Classify** to view the sentiment.

### Example
Input:
```
The movie was absolutely wonderful with stunning visuals and a compelling story.
```
Output:
```
Sentiment: Positive
Prediction Score: 0.89
```

---

## Files
- **RNN_SentimentAnalysis.ipynb**: Notebook used for training and evaluating the RNN model.
- **SentimentAnalysis_App.py**: Streamlit app for user interaction.
- **RNN_IMDB_sentiment_model.h5**: Pre-trained model file.

---

## Technologies Used
- **Python**: Programming language
- **TensorFlow**: Deep learning framework
- **Streamlit**: Web application framework for machine learning models

---

## Acknowledgments
- IMDB dataset provided by TensorFlow.
- Inspiration and guidance from online resources and community forums.

Feel free to contribute or raise issues in the repository!

