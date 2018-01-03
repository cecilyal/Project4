The purpose of this project was to get all the page text from Machine Learning Category in Wikipedia and as many pages in the Business Software category.
The text was then analyized through Latent semantic analysis in order to find the top related articles. 


This project looked at two categories within the Wikipedia API, Machine Learning and Business Software. 
The first category, Machine Learning contained many pages and also subcategories that also had pages. 

I used for loops and functions to go into all the subcategories to get all the Page IDs in order the pull then pull text from all the pages to analyze.
In order to be able to have the for loops and functions work, I created a url that accessed the API to get the page IDs for the subcategoreis.

I was then able to use a function that retrieved the text from all the articles based on the page IDs I had gotten previously. 
I used this same method for both Wikipedia Categories.
