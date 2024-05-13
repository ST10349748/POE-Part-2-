# POE-Part-2-
The Recipe class details a recipe with attributes like Name, Ingredients, and Steps, while the Ingredient class consists of an ingredient with Name, Quantity, Unit, Calories, and FoodGroup.
Recipe App 1
This C# application allows users to manage recipes, including entering recipe details, displaying recipes, scaling recipes, resetting quantities, and clearing all data.

Usage
Enter Recipe Details: Choose option 1 from the menu to enter the details of a new recipe. You will be prompted to provide the recipe name, list of ingredients (name, quantity, unit, calories, and food group), and steps to prepare the recipe.

Display Recipes: Option 2 allows you to view a list of available recipes sorted by name. Enter the name of the recipe to display its details, including ingredients, their quantities, calories, and preparation steps.

Scale Recipe: Select option 3 to scale a recipe by a factor of 0.5, 2, or 3. Enter the name of the recipe you want to scale and the scaling factor.

Reset Quantities: Option 4 resets the quantities of all ingredients in a recipe to zero. Enter the name of the recipe to reset its quantities.

Clear All Data: Choose option 5 to clear all recipe data from the application.

Exit: Select option 6 to exit the recipe app.

Additional Information
The application warns users if a recipe exceeds 300 calories.
All data is managed using the RecipeManager class, which handles recipe entry, display, scaling, quantity reset, and data clearing.
The Ingredient class represents individual ingredients with properties such as name, quantity, unit, calories, and food group.
Recipes are represented by the Recipe class, containing properties for the recipe name, ingredients, and preparation steps.
