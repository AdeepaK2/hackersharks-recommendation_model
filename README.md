# Personalized Travel Destination Recommendation System for Sri Lanka

This project showcases a recommendation model developed to provide personalized travel suggestions for destinations in Sri Lanka. The model recommends the top 5 travel destinations based on user preferences, such as interests in nature, culture, and adventure activities. Built using a straightforward, efficient approach, the system offers tailored recommendations while minimizing complexity.

## 1. Data Analysis Approach

### Exploratory Data Analysis (EDA)
Our initial focus during the EDA phase was to:
- Identify and address missing values.
- Explore unique values within the visitor preferences and destination datasets.

We reviewed the dataset's structure to ensure alignment with the recommendation engine's requirements, though we did not conduct extensive data visualizations.

## 2. Key Insights Derived from Analysis

### Key Findings
- Preferences such as "adventure," "beach," and "cultural activities" had a notable impact on the recommendations.
- The majority of destinations aligned well with visitor interests, ensuring frequent matches with user preferences.

### Actionable Insights
- The model effectively recommended destinations tailored to user preferences, providing personalized travel options.
- The simplicity of the model allowed for efficient processing and quick recommendations.

## 3. Data Preprocessing Methods

### Missing Value Treatment
- We addressed missing values by either filling them with default values or dropping incomplete rows from the dataset.

### Normalization/Scaling
- As most features were categorical (e.g., user preferences), extensive normalization was not required.
- We applied **Min-Max scaling** to numerical features, such as ratings, to ensure they remained within a uniform range.

## 4. Recommendation Algorithm

We implemented a similarity-based recommendation algorithm that measures how closely user preferences align with the features of travel destinations. Based on user-item interactions from the dataset, the algorithm generates the top 5 destinations that best match user preferences.

## 5. Evaluation Metrics

### Selected Metrics
- **Precision**: Assessed how many of the recommended destinations were relevant to user preferences.
- **Recall**: Measured the model's ability to capture a wide variety of relevant destinations.

### Rationale for Metric Selection
- **Precision**: Ensured that the recommendations closely aligned with the user's interests.
- **Recall**: Guaranteed that the recommendations covered a diverse range of destinations matching the user’s preferences.

## 6. Model Limitations

- The model was built strictly using the provided datasets, with no external data enrichment (e.g., demographic or seasonal data).
- The preprocessing was minimal, relying primarily on preference matching rather than advanced transformations or feature engineering.

## Conclusion

This recommendation system provides personalized travel destination suggestions in Sri Lanka by matching user preferences with places in the dataset. The simplicity of the model enabled efficient processing, and the system met the requirements of the datathon competition by delivering accurate and relevant travel recommendations.