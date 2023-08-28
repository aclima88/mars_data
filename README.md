# mars_data Part 1: Mars News

1. Started by importing the necessary modules.

2. Used automated browsing to visit the mars news website.

3. Created a Beautiful Soup object and used it to extract all of the text elements from the content_title and article_teaser_body classes of the website.

![part_1_extract_all_elems](https://github.com/aclima88/mars_data/assets/133547307/e87790e9-b531-45ed-9e3a-bd700838a7f1)

4. Create an empty list to store the dictionaries that I created to hold the title and preview pairs of information for each individual news article in the website. 
    a. Looped the website and collected the title and preview info for each news article.
    b. Stored it into individual dictionaries.
    c. Appended the dictionaries into the empty list created at the start.
    
![part_1_titles_previews_list](https://github.com/aclima88/mars_data/assets/133547307/c2ff5fc6-f075-47ec-898a-38842796a8d3)
    
# mars_data Part 2: Mars Weather Analysys

1. Started by importing the necessary modules.

2. Used automated browsing to visit the mars news website.

3. Created a Beautiful Soup object and use it to scrape the data in the HTML table and saved it into a pandas DataFrame called mars_weather_data.

![part_2_mars_weather_df](https://github.com/aclima88/mars_data/assets/133547307/060dbd87-8cfd-4d46-9f5a-1a1bf6e6cb3f)

4. Prepared the data for analysis.
    a. Used the info() method to get information about the dataframe.
    b. Changed the dtype for each column to the appropriate dtype.
    
![part_2_examine_df_data_type_1](https://github.com/aclima88/mars_data/assets/133547307/2f818f98-5b1a-4c2b-91d2-e0848a01f920)

![part_2_examine_df_data_type_2](https://github.com/aclima88/mars_data/assets/133547307/281232e5-ec43-4206-acbe-e81678aabb0c)

5.Analyzed the data.
    a. Used the data to find out how many months exist in Mars.
    
<img width="370" alt="total_numbers_of_months_in_mars" src="https://github.com/aclima88/mars_data/assets/133547307/e3f16539-0a66-4cd2-bce6-72fe3590751a">
    
    b. Used the data to find out how many Martian days worth of data we had in the data set.

<img width="361" alt="martian_days_worth_of_data" src="https://github.com/aclima88/mars_data/assets/133547307/2abf048b-e7f3-47ae-9d68-24eb134785c8">

    c. Used the data to find out the average low temperature per month, in Mars.
    
<img width="317" alt="avg_min_temp_per_month1" src="https://github.com/aclima88/mars_data/assets/133547307/4d3fbdb4-2e9a-4d98-b96b-9d38c77849f7">

    d. Plotted the average minimum temperature per month into a bar chart.
    
![avg_temp_per_month](https://github.com/aclima88/mars_data/assets/133547307/f7f73ed9-bbb0-4e96-aa05-6c518b5f6ef0)

    e. Recreated the bar chart in descending order to understand which months are coldest and which are hottest on average.
    
![coldest_hottest_month](https://github.com/aclima88/mars_data/assets/133547307/d9be2527-7ad2-49cf-8e88-652ad8ed8da1)

    f. Used the data to find the average pressure per month.
    
<img width="243" alt="ave_pressure_per_month1" src="https://github.com/aclima88/mars_data/assets/133547307/23c2a97b-ccce-48bc-84e6-683096efb180">

    g. Created a bar chart to plot the average pressure per month for the planet.
    
![avg_pres_per_month](https://github.com/aclima88/mars_data/assets/133547307/0ab218cb-aea6-44d1-95a1-dcd47f373c7d)

    h. Used the data to plot the number of terrestrial days by temperature into a line chart.
    
<img width="558" alt="number_of_terrestrial_days" src="https://github.com/aclima88/mars_data/assets/133547307/8d9659c7-c919-419b-bd71-bfb6752d7af4">

6. Saved the mars_weather_data DataFrame as a CSV file and used code to automatically close the browser.

**Notes**
Bryant Griessel and I worked together on this module challange.
I also used chatGPT and Google bard to help me clean up my code and problem solve syntax issues.



