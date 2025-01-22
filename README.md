E-commerce Product Categorization
Introduction
E-commerce is the process of buying and selling products online, and its growth has led to the need for efficient systems to categorize vast product offerings. Product categorization plays a crucial role in improving the user experience by helping customers quickly find what they are looking for. This project aims to automate the product categorization task, which is traditionally laborious and time-consuming, using text classification techniques. The goal is to classify product descriptions into predefined categories such as Electronics, Household, Books, and Clothing & Accessories.

Problem Statement
The task involves categorizing e-commerce product descriptions into specific categories based on the text content. This automated classification system enhances search engine results and improves customer experience by streamlining navigation through the product catalog.

Dataset
The dataset is scraped from an Indian e-commerce platform and contains product descriptions for four main categories:

Electronics
Household
Books
Clothing & Accessories
You can access the dataset here:

Original Source
Kaggle Dataset
The dataset is in CSV format with two columns:

Target Class Name (Category)
Product Description
Text Classification Approach
Text classification is a common Natural Language Processing (NLP) task where we assign a document or statement to a predefined category. For this project, the task is to classify product descriptions into one of four categories. We apply a series of text normalization processes, including:

Converting text to lowercase
Removing stop words, punctuations, and non-alphabetic characters
Correcting spelling errors
Stemming and Lemmatization
Substituting contractions
Key Features
Data Preprocessing: Includes text normalization steps like removing unnecessary characters and correcting text.
Text Classification: The product descriptions are classified into categories using machine learning models, improving the efficiency of e-commerce platforms.
Exploratory Data Analysis: Includes visualizations like class frequencies, word count, and average word length.
Installation
Clone the repository and install the dependencies using the following command:

git clone https://github.com/yourusername/ecommerce-product-categorization.git
cd ecommerce-product-categorization
pip install -r requirements.txt
Usage
To preprocess and classify the product descriptions, run the following:

python preprocess_data.py
python classify_product.py
