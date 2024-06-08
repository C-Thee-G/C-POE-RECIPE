# C-POE-RECIPE
C# POE (RECIPE FILTERS)

# DM ME ON WHATSAPP(063 104 9072) IF YOU NEED THE SOURCE CODE:R300

# SCREENSHOTS
![HOMEPAGE](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/dc3e02c4-8322-4da8-9d07-101447f3ea17)
![RECIPE DETAILS FRAGMENT](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/0f4b631a-d8dd-4b6a-a4a0-4cd9c3fea745)
![HH](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/c2d59882-c4da-44a5-8470-fb1e8c40fd9e)
![FILTER FRAGMENT](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/b4aa37eb-849b-444f-ad40-76ceb01b82b6)
![FOOD GROUP](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/aa10671f-f681-434c-a021-aef322ddc5b7)
![CALORIES](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/0097d2c2-8a59-43a4-9596-9b759150055f)
![GG](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/224a3349-ed18-4cf3-af61-3784e2da98b3)
![HD](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/8df8cfbf-b14b-4f54-9ddc-de429b2d9fa2)
![RECIPE DE](https://github.com/C-Thee-G/C-POE-RECIPE/assets/107345987/ca75d0cb-b589-4c80-8c3a-d72c0c948691)

## Project Overview

RecipeeManager3 is a WPF-based application designed to help users manage their recipes efficiently. The application allows users to add, view, search, and delete recipes. Each recipe contains details such as ingredients, steps, food groups, and calorie information.

## Features

1. **Add Recipes**: Users can add multiple recipes with detailed information, including ingredients, quantities, units of measurement, food groups, calories, and preparation steps.
2. **View Recipes**: Users can view the list of recipes and see detailed information about each recipe.
3. **Delete Recipes**: Users can delete a selected recipe from the list.
4. **Search Recipes**: Users can filter recipes based on ingredient names, food groups, and maximum calories.

## Dependencies

- .NET Framework 4.7.2 or later
- Visual Studio 2019 or later

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RecipeeManager3.git
   ```
2. Open the solution file (`RecipeeManager3.sln`) in Visual Studio.
3. Build the solution to restore the necessary packages.

## Usage

### Running the Application

1. Press `F5` in Visual Studio to run the application.
2. The main window will appear with an empty recipe list.

### Adding Recipes

1. Enter the number of recipes to add in the `recipeCountTextBox`.
2. Click the `Add Recipes` button.
3. Follow the prompts to enter the details for each recipe and its ingredients.

### Viewing Recipes

1. Select a recipe from the `recipeListBox`.
2. The details of the selected recipe, including name, ingredients, steps, food group, and calories, will be displayed.

### Deleting Recipes

1. Select a recipe from the `recipeListBox`.
2. Click the `Delete` button to remove the recipe.

### Searching Recipes

1. Enter the ingredient name filter in the `ingredientFilterTextBox`.
2. Select the food group filter from the `foodGroupFilterComboBox`.
3. Enter the maximum calories in the `caloriesFilterTextBox`.
4. Click the `Search` button to filter the recipes.

## Classes and Methods

### MainWindow.xaml.cs

- `MainWindow()`: Initializes the component and the recipes list.
- `AddRecipesButton_Click(object sender, RoutedEventArgs e)`: Handles adding recipes based on user input.
- `CalculateTotalCalories(List<Ingredient> ingredients)`: Calculates the total calories of a list of ingredients.
- `GenerateRecipeId()`: Generates a random recipe ID.
- `RecipeListBox_SelectionChanged(object sender, SelectionChangedEventArgs e)`: Displays the details of the selected recipe.
- `ClearRecipeDetails()`: Clears the displayed recipe details.
- `DeleteButton_Click(object sender, RoutedEventArgs e)`: Deletes the selected recipe.
- `SearchButton_Click(object sender, RoutedEventArgs e)`: Filters the recipes based on the specified criteria.

### Recipe Class

- `Id`: Unique identifier for the recipe.
- `Name`: Name of the recipe.
- `Ingredients`: List of ingredients.
- `Steps`: List of preparation steps.
- `MatchesFilters(string ingredientNameFilter, string foodGroupFilter, double maxCaloriesFilter)`: Checks if the recipe matches the specified filters.
- `CalculateTotalCalories()`: Calculates the total calories of the recipe.
- `GetFoodGroupString()`: Returns the string representation of the food group.

### Ingredient Class

- `Name`: Name of the ingredient.
- `Quantity`: Quantity of the ingredient.
- `UnitMeasurement`: Unit of measurement for the ingredient.
- `FoodGroup`: Food group of the ingredient.
- `Calories`: Calorie content of the ingredient.

## Enum
### FoodGroup
- `FruitAndVegetables`
- `StarchyFood`
- `Dairy`
- `Protein`
- `Fat`

## Contributing
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push the branch and create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries or issues, please contact 0631049072 ON Whatsapp.
