# Food Data Processing Code

This is a JavaScript code that processes food data from a JSON file (`food.json`) and provides various functionalities to list and sort the food items based on different criteria.

## How to Use

1. Clone the repository or download the `food.json` files to your local machine.

2. Ensure that you have the `food.json` file in the same directory as your JavaScript code.

3. Open the JavaScript code file (assuming it's named `foodApp.js`) in a text editor or IDE.

4. Run the code using a JavaScript runtime or environment that supports the `console.log` function.

5. The code will list all the food items and perform various operations like sorting by protein content, carb content, listing food items in specific categories, and filtering food items by calorie content.

## Functions

The code provides the following functions:

1. `listAllFoodItems(data)`: Lists all the food items.

2. `listFoodItemsByCategory(data, category)`: Lists all the food items in a specific category.

3. `listAllFoodItemsByCalorie(data, above)`: Lists all the food items with calorie above or below a given threshold (100).

4. `listAllFoodItemsByProtien(data)`: Lists all the food items sorted by the highest protein content to the lowest.

5. `listAllFoodItemsByCab(data)`: Lists all the food items sorted by the lowest carb content to the highest.

## Example Output

The code, when executed, will display the following output (assuming `foodData` contains the JSON data from `food.json`):

```
All Food Items:
[ 'Apple', 'Banana', 'Chicken Breast', ... ]

Vegetables:
[ 'Carrot', 'Broccoli', 'Spinach', ... ]

Fruits:
[ 'Apple', 'Banana', 'Orange', ... ]

Proteins:
[ 'Chicken Breast', 'Salmon', 'Tofu', ... ]

Nuts:
[ 'Almonds', 'Walnuts', 'Peanuts', ... ]

Grains:
[ 'Rice', 'Quinoa', 'Oats', ... ]

Dairy:
[ 'Milk', 'Cheese', 'Yogurt', ... ]

Food Items with Calorie Above 100:
[ 'Peanuts', 'Cheese', 'Salmon', ... ]

Food Items with Calorie Below 100:
[ 'Apple', 'Banana', 'Carrot', ... ]

Food Items Sorted by Highest Protein Content:
[ 'Salmon', 'Chicken Breast', 'Tofu', ... ]

Food Items Sorted by Lowest Carb Content:
[ 'Salmon', 'Chicken Breast', 'Tofu', ... ]
```

## Note

Make sure to have the `food.json` file in the same directory as the JavaScript code. The code reads data from this JSON file for processing.

Happy food data processing!
