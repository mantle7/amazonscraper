# amazonscraper

A web scraper is used to extract data from websites which can further be used to perform analysis.
This python script is ot be used specifically for extracting data from Amazon.in

PS: price of the products are in INR

Follow the steps to generate a dataset of your own:
1. Initialize search_term to whatever term you are using to scrape the data.
2. Initialize csv_file to the target csv file where you want to store the data. The csv file need not be created manaually, just a name for the file is sufficient
3. Go to https://httpbin.org/get, copy the contents of User-Agent to the variable 'user_agent' 
4. Run the script, and you get the dataset for your search term.
