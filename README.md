# Calorie Calculator API

A Python-based data analysis tool that interacts with the **USDA FoodData Central API** to fetch and process nutrition data (calories, protein, carbs, fat) for various food items.

This project demonstrates practical skills in:

- Python scripting
- Working with RESTful APIs (GET requests, parameters)
- Data extraction and transformation
- File handling (CSV)
- Preparing data for analysis using **pandas**

Perfect for data analysis, calorie tracking, and food research — built with real-world coding practices and clean, modular code.


---

## Features

- Search for any food item (e.g., pizza, banana, chicken breast)
- Retrieve nutritional values: calories, protein, carbs, fat
- Save results to CSV 
- Ready for data analysis or integration into bigger projects

---

## Requirements

Make sure you have the following libraries installed:

```bash
pip install requests pandas
 ```
---

## How to Use

1. Get a free API key from [USDA FoodData Central](https://fdc.nal.usda.gov/api-key-signup.html)

2. Add your API key to the script:

 Replace this line in the Python code:

   ```python
   API_KEY = "your_api_key_here"
 ```

---

## Example Output

```json
[
  {
    "description": "PIZZA",
    "brand": "The Kroger Co.",
    "calories": 238,
    "protein": 6.8,
    "carbs": 32.0,
    "fat": 2.38
  }
]
```

---

## Use Cases

- Nutrition analysis
- Calorie counting apps
- Food research and education
- Personal tracking or meal planning
