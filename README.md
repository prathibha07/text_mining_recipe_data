# text_mining_recipe_data

Scraping at least 100 recipes from the web,provide their ingredient lists and cleaned the ingredient data for the further calculation.
Used -- https://rainbowplantlife.com/ as reference webpage

Three main tasks performed: 
* scraping data: scraped at least 100 recipes from the website
* cleaning data: cleaned ingredient data for further calculation. This includes, but is not limited to, removing excess white spaces, correcting for a few edge cases, and correcting any remaining formatting issues
* calculating: what are the 10 most common ingredients used in these recipes

1. rawData.csv -> data captured from webscrapping
  Data for the rawData and cleanData files is formatted with three columns: url, name, ingredient.
  Each ingredient is listed on a separate line.
   * url: contains the link where the recipe can be found
   * name: the name of the recipe
   * ingredient: the name of the ingredient
    
2. cleanData.csv -> after some basic cleaning steps

3. results.csv -> captures count and proportion of the ingredients
Data for the calculation result contains three columns: word, count, proportion. 
The list of ingredients is sorted such that the most common ingredient is listed first and 10th most common is listed last.
  * ingredient: the ingredient name
  * count: the number of times the ingredient appears in the list
  * proportion: the proportion of recipes in which the ingredient appears
