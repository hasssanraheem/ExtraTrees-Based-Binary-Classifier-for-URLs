# ExtraTrees-Based-Binary-Classifier-for-URLs
Overview

This project implements a binary URL classification model using the ExtraTrees Classifier. It takes URLs from multiple categories and converts them into two primary classes (e.g., benign vs. suspicious) for simplified analysis.

Dataset

The dataset used in this project is included in the repository. It contains URLs originally belonging to four different categories, which are transformed into two broader classes for binary classification.

Methodology

Data Preprocessing – Convert the original four-category dataset into two classes, extract URL features, and prepare data for training.

Model Training – Train an ExtraTrees Classifier to distinguish between benign and suspicious URLs.

Handling Overfitting – Initial training resulted in overfitting on complex URLs and poor predictions for basic URLs (e.g., google.com).

Whitelist Implementation – A custom whitelist was added to automatically classify well-known/basic URLs as benign, improving prediction reliability.

Results

The model classifies URLs into two categories with high accuracy on most cases and improved performance on simple, well-known domains due to the whitelist mechanism.
