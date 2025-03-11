# Google Play Store App Review Analysis: Unlocking App Success
![Relationship-between-app-rating-and-the-number-of-installs](https://github.com/user-attachments/assets/94694f50-6e4e-454d-9c38-b98ff8c1f47f)

## Overview

This project is an Exploratory Data Analysis (EDA) of Google Play Store app data and user reviews. The goal is to identify key factors that contribute to app success, providing data-driven recommendations for app developers.  This was an individual capstone project for Module 2.

## Project Objectives

*   Uncover relationships between app characteristics (category, size, price, etc.) and user ratings/installs.
*   Analyze user sentiment expressed in app reviews.
*   Identify the most influential factors driving app success.
*   Provide actionable recommendations for improving app performance on the Google Play Store.

## Data Source

*   **Google Play Store Apps Dataset:** Contains information about app name, category, rating, installs, size, price, content rating, genres, last update date, current version, and Android version.
*   **Google Play Store Reviews Dataset:** Contains user reviews for each app, including sentiment polarity, sentiment subjectivity, and review translation.

Both datasets were provided to me  from almabetter, and accessed via Google Drive links for the purpose of this project.

## Data Preparation

The following data preparation steps were performed:

*   **Data Extraction:** Data was extracted from Google Drive using specific URLs. Error handling was implemented to address potential data corruption or URL issues.
*   **Data Cleaning:**
    *   Handling missing values (using imputation methods like median or mode).
    *   Correcting data types.
    *   Removing duplicates.
*   **Data Wrangling:**  Transforming data into a usable format for analysis. This included:
    *   Converting data types (e.g., converting install counts to numerical values).
    *   Creating new features (e.g., calculating the length of app descriptions).
    *   Handling string conversion exceptions to avoid errors during processing.

## Key Findings

The analysis revealed the following key findings:

*   **Category Distribution:** The "Family" category has the highest number of apps, followed by "Game" and "Tools". "Beauty" apps are the least common.
*   **Rating vs. Installs:** A strong correlation between rating and installs was **not** found.  While higher-rated apps *can* have more installs, this is not always the case. A few highly-rated apps tend to have the most installs.
*   **App Size Distribution:** Most apps have a relatively small size (under 20 MB).
*   **Free vs. Paid Apps:** The majority of apps are free, indicating the dominance of the freemium model.
*   **Average Rating by Category:** The "ART\_AND\_DESIGN", "BEAUTY", and "BOOKS\_AND\_REFERENCE" categories tend to have higher average ratings.
*   **App Price Distribution:**  Most paid apps are priced below $10.
*   **Sentiment Polarity by Category:** "COMICS" and "EVENTS" apps tend to have more positive user sentiment compared to "FAMILY" and "GAME" apps.

## Recommendations

Based on the analysis, the following recommendations are provided for app developers:

*   **Prioritize App Quality and User Reviews:** Focus on delivering a high-quality user experience and actively solicit and respond to user feedback. Positive reviews are directly correlated to increased installs.
*   **Select Appropriate App Categories and Target Audience:** Conduct thorough market research to identify the most appropriate app categories and target audience for your app.
*   **Optimize App Size:** Keep your app size as small as possible to avoid issues with downloads, especially for users with limited storage or slow internet connections.
*   **Consider a Freemium Model:**  Offer a free version of your app to attract a wider user base. Monetize through in-app purchases or subscriptions.

## Technologies Used

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn

## How to Run the Project

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Ansh1kaDixit/CapstoneModule2/
    cd CapstoneModule2
    ```

2.  **Install the required libraries:**

    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3.  **Open and run the Jupyter Notebook:**

    ```bash
    jupyter notebook CapstoneModule2.ipynb
    ```

## Contact

Anshika Dixit

anshikad86@gmail.com
