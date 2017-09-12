# Google_spreadsheet_slug_generator
A simple Google Sheets function to generate a "slug" out of a product name (e-commerce), so that it can safely be used within URLs. 
This function allows you to : 

* Lowercase everything
* Remove trailing and leading spaces
* Replace spaces by "-"
* Remove all accentuated characters and replace them by their non-accentuated equivalent


# To use

Insert in your spreadsheet, and replace "F3" by the cell you want to slugify
Do note : This function also replaces the "&" symbol by "und", as this was done for a German project. Feel free to replace it by "and" in the code. 

