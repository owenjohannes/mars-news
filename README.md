# mars-news

This repository contains code and files for scraping titles and previewing text from Mars news articles as well as scraping and analysing Mars weather data.        
The analysis is performed using splinter, BeautifulSoup, Matplolib and Pandas.

## Part 1
### Scrape Titles and Preview Text from Mars News
1. Imports the necessary libraries, Splinter and BeautifulSoup.      
2. Initializes a Splinter browser using the Chrome browser.       
3. Visits the Mars news website specified by the url variable.       
4. Creates a Beautiful Soup object by parsing the HTML of the visited page.       
5. Finds all the text elements containing news articles on the page.        
6. Creates an empty list to store dictionaries.       
7. Iterates through each text element and extracts the title and preview text.       
8. Stores the title and preview text as key-value pairs in a dictionary.      
9. Appends the dictionary to the list.       
10. Prints the list to confirm the success of the extraction process.       
11. Quits the browser.

## Part 2
### Scrape and Analyse Mars Weather Data
1. Imports the necessary libraries: Splinter, BeautifulSoup, Matplotlib, and Pandas.      
2. Initializes a Splinter browser using the Chrome browser.       
3. Visits the Mars facts website specified by the url variable.      
4. Creates a Beautiful Soup object by parsing the HTML of the visited page.       
5. Extracts all rows of data from the table.      
6. Creates an empty list to store the rows of data.      
7. Loops through the scraped data to create a list of rows.
Extracts the header fields from the table.
Creates a Pandas DataFrame using the list of rows and the list of column names.
Confirms the DataFrame was created successfully and displays the first few rows.
Examines the data type of each column in the DataFrame.
Changes the data types of specific columns for data analysis purposes.
Confirms the type changes were successful by examining the data types again.
Performs various data analysis tasks, including counting the number of months on Mars, determining the amount of Martian days' worth of data, calculating the average low temperature by month, and calculating the average pressure by Martian month.
Generates visualizations based on the analysis, including bar plots for average temperature by month and average pressure by month, as well as a line plot for minimum temperature by the number of terrestrial days.
Writes the data to a CSV file named mars_temperature_data.csv.
Quits the browser.
