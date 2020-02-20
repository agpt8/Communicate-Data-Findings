# Communicate Data Findings

Data visualization is an important skill that is used in many parts of the data analysis process.

_Exploratory_ data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed.

_Explanatory_ data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

## Project Details

1. Dataset: [Ford GoBike](https://www.lyft.com/bikes/bay-wheels/system-data)
   The original link provided in the project (https://www.fordgobike.com/system-data) points to the above link. The data files have not been included due to their size and volume, but can be obtained from the here [Ford GoBike](https://www.lyft.com/bikes/bay-wheels/system-data) and has to be kept in the `./data/raw/` folder. You need to download files ranging from 01/2018 - 04/2019. There will be more files but those have a little different structure and data in them, so they won't be needed. You do not need to unzip any file. The script present in `exploration.ipynb` will do it for you.
2. Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored.
3. Document the story: organized findings convey a story to present to an audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.

## Project Findings

A large number of people can benefit from this program:

- Environmentally friendly, budget friendly, and lifestyle friendly.
- Subscribers (i.e. daily commuters) benefit from a health commuting choice
- Customers (i.e. tourists, students, etc.) have a sustainable, yet flexible option for touring the city.
- Affordable and convenient transportation for the people of all socioeconomic classes
- Renting a bike from the Ford GoBike System is a fantastic (healthy and environmentally friendly) way of moving around in the city, both for enjoyment and work.

There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occasional riders who use the system mainly on weekends to explore the Bay Area. The usage has been seen increasing in 2019. The service usage spikes during the summers and into the autumn season.

## Key Insights

- This data covers three areas: San Francisco, East Bay and San José
- The highest count of trips can be found in San Francisco, followed by East Bay and San José
- The average trips is ~700 seconds long, the most trips were around ~500 seconds long
- San Francisco has the longest trips with ~717 seconds, followed by East Bay with ~631 seconds and San José with ~627seconds
- There are a lot more subscribers than customer using this service
- People use the bikes more/in higher counts during the week than during the weekend
- On the other hand the trips on the weekend are longer, ~1100 seconds than during the week which is about ~780 seconds
- Also people start their trips later during the weekends than during the week (~1400hrs instead of ~13:20 during the week)
- Overall San Francisco has the longest average trips, followed by East Bay and San José
- Users starting in the morning and in the evening have shorter trips than people who start between 11 and 15
- In San Jose the trips start on average the latest, followed by East Bay and San Francisco
- There is an increasing trend of usage
- People start their trips most frequently at 800 and 1700hrs
- the most popular trip so far is between stations 15_0 San Francisco Ferry Building (Harry Bridges Plaza) and 6_0 The Embarcadero at Sansome St

## Files

- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis.

- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration.

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

  To view the slide deck, use the following command:

  `jupyter nbconvert slide_deck.ipynb --to slides --post serve --template output_toggle`

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).

## Sources referred

- https://stackoverflow.com/questions/3451111/unzipping-files-in-python/3451150
- https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude/43211266#43211266
- https://datatofish.com/k-means-clustering-python/
- https://codeyarns.com/2015/06/29/how-to-hide-axis-of-plot-in-matplotlib/
- https://stackoverflow.com/questions/43855474/changing-sort-in-value-counts
- https://stackoverflow.com/questions/4700614/how-to-put-the-legend-out-of-the-plot
- https://stackoverflow.com/questions/35143672/seaborn-conditional-colors-based-on-value
- Udacity Course Material
- Library documentations
