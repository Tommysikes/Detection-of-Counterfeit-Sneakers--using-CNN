# Detection of Counterfeit Sneakers using CNN

Welcome to the Detection of Counterfeit Sneakers repository, where we present an image classifier model based on Convolutional Neural Networks (CNN) to discern between authentic and counterfeit sneaker products.

## Overview

This project aims to tackle the challenge of identifying counterfeit sneakers using computer vision techniques. The CNN-based image classifier is trained on a dataset of sneaker images scraped from Reddit. The repository also includes a text-based model leveraging Sentence Transformers (Sbert) to provide a secondary opinion by analyzing metadata associated with the products.

## Dataset and Training

1. **Image Data Collection**: The dataset includes images collected through the Reddit_Scrape.ipynb script. Images were categorized into two classes: authentic and counterfeit.
2. **CNN Model Training**: The Convolutional Neural Network (CNN) model is trained on these labeled images to learn and differentiate between authentic and counterfeit sneakers.
3. **Text Model Training**: The Sentence Transformers (Sbert) model processes metadata related to the products to provide additional insights and opinions.

## Usage

1. Install the required libraries using `pip install numpy pandas matplotlib sklearn keras requests sentence-transformers`.
2. Execute the Reddit_Scrape.ipynb notebook to scrape sneaker images from Reddit.
3. Run the CNN and Sbert model training scripts to generate the image and text classifiers.
4. Provide sneaker images or metadata to the models for detection and analysis.

## Libraries Used

- `numpy`, `pandas`, `matplotlib`: For data manipulation and visualization.
- `sklearn`: For machine learning and model evaluation.
- `keras`: For building and training the CNN model.
- `requests`: For making HTTP requests to retrieve Reddit images.
- `sentence-transformers`: For training the Sbert text model.

## Contribution

Contributions to this repository are encouraged! Feel free to enhance the models, add new features, or improve existing ones by submitting pull requests.

## Disclaimer

While the models provide insights into the authenticity of sneakers, it's important to remember that their accuracy may vary. Always exercise caution and expert judgment in real-world scenarios.

Explore the world of counterfeit sneaker detection through image and text analysis using CNN and Sbert models!
