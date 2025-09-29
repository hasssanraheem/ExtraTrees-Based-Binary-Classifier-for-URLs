# ExtraTrees-Based-Binary-Classifier-for-URLs
Overview

This project implements a binary URL classification model using the ExtraTrees Classifier. It simplifies multi-category URL data into two primary classes (e.g., benign vs. suspicious) to support faster and more reliable analysis.

Dataset

The dataset is provided in ZIP format within this repository. It originally contains URLs from four distinct categories, which are transformed into two broader classes for binary classification. You can extract the ZIP file to access the raw data before running the scripts.

Methodology

Data Preprocessing – Extract the ZIP file, convert the original four-category dataset into two classes, extract URL features, and prepare data for training.

Model Training – Train an ExtraTrees Classifier to distinguish between benign and suspicious URLs.

Handling Overfitting – Initial training overfit on complex URLs and misclassified basic URLs (e.g., google.com).

Whitelist Implementation – A custom whitelist was added to automatically classify well-known/basic URLs as benign, improving prediction reliability.

Results

The model classifies URLs into two categories with high accuracy on most cases and improved performance on simple, well-known domains due to the whitelist mechanism.
