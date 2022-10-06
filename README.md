# text_mining_vegan_recipe_data

Scraping at least 100 recipes from the web,provide their ingredient lists and cleaned the ingredient data for the further result calculation.
> Reference Webpage used https://rainbowplantlife.com/

Three main tasks performed: 
* Scraping data: scraped at least 100 recipes from the website
* Cleaning data: cleaned ingredient data for further calculation. This includes, but is not limited to, removing excess white spaces, correcting for a few edge cases, and correcting any remaining formatting issues
* Calculating result: captured the 10 most common ingredients used in these recipes

1. rawData.csv -> csv file generated which caputured the data got from webscrapping
  Data for the rawData and cleanData files is formatted with three columns: url, name, ingredient.
  Each ingredient is listed on a separate line.
  * url: contains the link where the recipe can be found
  * name: the name of the recipe
  * ingredient: the name of the ingredient
    
2. cleanData.csv -> csv file generated after some basic cleaning steps

3. results.csv -> csv file captured the count and proportion of the ingredients
Data for the calculation result contains three columns: word, count, proportion. 
The list of ingredients is sorted such that the most common ingredient is listed first and 10th most common is listed last.
  * ingredient: the ingredient name
  * count: the number of times the ingredient appears in the list
  * proportion: the proportion of recipes in which the ingredient appears
