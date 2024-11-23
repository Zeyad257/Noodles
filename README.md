# Noodles: AI-Powered Food Recognition and Nutritional Tracking
Noodles is a machine learning-driven application designed to automate meal recognition and nutritional tracking. It enables users to identify food items from images, estimate their caloric content, and access comprehensive nutritional details using the USDA Food and Nutrient Database. The project aims to simplify dietary tracking and promote healthier eating habits through real-time, accurate food detection and calorie estimation.

Key Features:
Food Detection and Classification: Utilizes advanced machine learning models to identify food items and classify them into specific categories.
Calorie and Nutrient Estimation: Provides accurate caloric values and a breakdown of macronutrients (proteins, fats, carbohydrates) and micronutrients.
Seamless Integration with USDA Database: Fetches reliable and comprehensive nutritional data for a wide variety of food items.
User-Friendly Interface: Allows users to upload meal images and instantly receive food predictions, nutrient estimations, and related recipes.
Real-Time Analysis: Offers instant feedback, making it easier to log meals and monitor dietary intake.

Technical Overview:
The project integrates three machine learning models:

1- Food Detection (nateraw/food): Identifies food items within images.
2- Food Classification (kaludi/food-category-classification-v2.0): Classifies detected items into predefined categories.
3- Custom Fruits and Vegetables Model: Specifically developed to enhance the detection accuracy of fruits and vegetables.

Potential Future Enhancements:
- Improved Portion Estimation: Advanced image processing techniques for better accuracy.
- Complex Meal Decomposition: Enhanced handling of mixed dishes.
- Personalized User Features: Tailored meal plans and dietary preferences integration.
