# E-Commerce Product Recommendation Engine

## Project Overview

The E-Commerce Product Recommendation Engine is a beginner-friendly recommendation system built using Python and Streamlit. The project generates personalized product recommendations based on user interactions such as views, cart actions, and purchases.

This project demonstrates how recommendation systems work in e-commerce platforms using simple scoring logic and DSA concepts.

---

## Features

* Personalized product recommendations
* Product search functionality
* Category-based recommendation logic
* User interaction analysis
* Recommendation scoring system
* Streamlit dashboard interface
* Top-N recommendation generation
* Dataset visualization

---

## Problem Statement

E-commerce platforms contain thousands of products, making product discovery difficult for users. Recommendation systems help users find relevant products based on previous interactions and preferences.

This project solves that problem by creating a recommendation engine that suggests products using interaction history and category similarity.

---

## Technologies Used

* Python
* Streamlit
* Pandas

---

## DSA Concepts Used

* Dictionary (HashMap)
* Heap / Priority Queue
* Lists and Arrays
* Sorting
* Searching
* Recommendation Scoring Logic

---

## Project Structure

E-Commerce-Product-Recommendation-Engine/

├── data/

│   ├── products.csv

│   └── interactions.csv

├── images/

├── outputs/

├── README.md

├── requirements.txt

└── main.py

---

## Dataset Description

### Products Dataset

Contains:

* Product ID
* Product Name
* Category
* Brand
* Price
* Rating

### Interactions Dataset

Contains:

* User ID
* Product ID
* User Activity (view/cart/purchase)

---

## How Recommendation Works

1. Load product and interaction datasets
2. Read user interaction history
3. Assign activity scores
4. Find products from similar categories
5. Calculate recommendation scores
6. Rank products using heap logic
7. Display Top-N recommendations

---

## Installation

Install required libraries:

pip install -r requirements.txt

Run the application:

streamlit run main.py

---

## Sample User Input

User ID:

U101

Top Recommendations:

5

---

## Sample Output

Recommended Products:

* Laptop Stand
* USB-C Hub
* Webcam HD

---

## Future Improvements

* Advanced recommendation algorithms
* Similar product recommendation engine
* Analytics dashboard
* Machine Learning ranking models
* Better UI design

---

## Learning Outcomes

* Building recommendation systems
* Working with datasets
* Applying DSA concepts in projects
* Streamlit dashboard development
* Product ranking and scoring logic

---

## Author

Sharvari Patangrai – E-Commerce Product Recommendation Engine
