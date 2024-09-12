# mars_weather-challenge

This repository contains four files and a folder tiltes "Outputs".

Upon running the first file, part_1_mars_new, the script will scrape the Mars news site, https://static.bc-edx.com/data/web/mars_news/index.html. The script will scrape the site for all text elements and store them in dictionaries inside of a Python list. It will then generate and print a list of all of the titles and previews of each article on the website. 

Running the second file, part_2_mars_weather, will swrape the Mars Temperature Data Site, https://static.bc-edx.com/data/web/mars_facts/temperature.html. The script will pull the data table from the webiste and populate a Pandas dataframe with the data sorted into the relevent columns from the table. The script will then convert the data to the appropriate data types for calculations and plotting. 5 questions will be answered by the script:

        1. How many months exist on Mars?
        2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
        4. Which months have the lowest and the highest atmospheric pressure on Mars?
        5. About how many terrestrial (Earth) days exist in a Martian year?

The script will also make 5 plots to visually assist in answering the posed questions.
    
    Plot 1: Shows the average minimum temperature for each month.
    Plot 2: Sorts the above plot from lowest to highest temperature.
    Plot 3: Shows the average atmospheric pressure for each month.
    Plot 4: Sorts the above plot from lowest to highest atmospheric pressure.
    Plot 5: Shows a visual representation of the number of Earch days in a Martian year.