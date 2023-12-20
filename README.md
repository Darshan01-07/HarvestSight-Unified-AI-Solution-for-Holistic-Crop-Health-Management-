# HarvestSight: Unified AI Solution for Holistic Crop Health Management

## Overview

HarvestSight is an AI-powered system designed to offer personalized recommendations for farmers in crop selection, fertilization, and disease detection. Leveraging machine learning and deep learning techniques, it analyzes soil composition, nutrient levels, weather patterns, and crop health images.

## Objectives

- **Soil Classification:** Detect different soil classes through classification.
- **Environmental Integration:** Incorporate nitrogen, phosphorus, pH, humidity, and rainfall data.
- **Crop Recommendations:** Provide tailored suggestions based on soil characteristics.
- **Fertiliser Recommendation** Provide tailored fertiliser suggestions based on soil characteristics and Crop.

## Methodology

HarvestSight utilizes multimodal machine learning by combining data from various sources, including soil classifications, nutrient levels, and environmental conditions. This comprehensive data fusion enables the development of strong predictive models considering multiple variables for precise crop recommendations.

## Implementation Details

- **Data Collection and Preprocessing:** Gathered soil nutrient and environmental data from 22 distinct crop classes.
- **Dataset Split:** Divided soil composition and weather pattern data into training and testing subsets.
- **Model Training:** Implemented Random Forest, Logistic Regression, Decision Tree, and Naive Bayes models for crop recommendation.
- **Soil Classification:** Trained a deep learning model on soil image data for classifying soil types.
- **Crop Recommendation** Trained a Machine Learning Model to recommend Crop based on Soil Type and Chemical and Enviromental Factors

## Results

The system achieved:
- 87.5% accuracy  with VGG16 and 62.5% with the CNN model for soil classification
- 90% accuracy with Decision Tree and 99% accuracy with Random Forest for  Crop Recommendation Based on Chemicals and Environmental Factors.

## Conclusion

HarvestSight showcases the potential of AI-powered solutions in precision agriculture, aiding sustainable and efficient crop management practices. Its ability to offer personalized insights based on soil conditions and crop requirements can significantly enhance yields and reduce environmental impact.

## Future Scope

- Expand system capabilities to include more crops.
- Integrate real-time sensor data.
- Develop mobile applications for farmers.

## How to Use

Include instructions on how to:
- Set up the environment.
- Run the code or use the system.
- Any prerequisites or dependencies needed.

## Contributors

- Mention contributors and their contributions.

## License

Specify the project's license.
