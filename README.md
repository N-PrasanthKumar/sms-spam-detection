# SMS Spam Detection

This project uses a machine learning model to classify messages as spam or ham (non-spam) based on their text content. A Flask web application provides a user interface to input a message and see the classification result.

## Project Overview

The Spam vs. Ham Classification project applies Natural Language Processing (NLP) and supervised learning techniques to build a message classifier. The web app allows users to enter a message, which is then classified as either spam or ham by the trained model.

## Project Structure

- **templates/**: Contains HTML templates for the Flask web app.
  - `home.html`: Main page for message input.
  - `result.html`: Page to display classification results.
- **app.py**: Main script that runs the Flask web application.
- **requirements.txt**: Lists the dependencies for the project.
- **spam_detection.ipynb**: Jupyter Notebook containing data preprocessing, model training, and evaluation code.
- **spam_data/**: Folder containing the dataset files for the project.

## Getting Started

### Prerequisites

- **Python 3.x**: Ensure Python is installed on your system.

### Installation

1. Clone this repository to your local machine.
2. Install dependencies by running the following command:

   ```bash
   pip install -r requirements.txt

   
### result Pages
![spam image Page](image/spam image.png)


![ham image Page](image/ham image.png)
