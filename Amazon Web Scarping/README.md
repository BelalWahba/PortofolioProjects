
# Amazon web scraping

In this Project i used selenium and beautifulsoup to Scrap data from amazon based on a search term 
then store the results in a local csv file

## What i did in this Project

- I used selenium and web driver to control the web browser
- I scraped the data using Beautifulsoup based on unique classes to fetch the needed fields
- Then I modified the main function to handle the missing data and attribute errors incase that there is a product without a price or ratings 

- I Then handled going to the next page by introducing &page query to the url 
- Then the different records will get saved in a local csv file with a header to showcase the data 
