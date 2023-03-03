***Mars EDA***
<br>
**Project Description**<br>
<br>
*Part 1: Scrape HTML Titles and Preview Text from Mars News*<br>
After identifying HTML elements on a webpage, I identified their id and class attributes, and extracted article titles and previews via both automated browsing with Splinter and HTML parsing with Beautiful Soup. Finally, I stored the scraped information in a Python data structure—specifically, a list of dictionaries.<br>
<br>
*Part 2: Scrape and Analyze Mars Weather Data*<br>
I extracted an HTML table into a Pandas DataFrame by first using Splinter and Beautiful Soup to scrape the data. Data analysis answers the following questions:
> How many months exist on Mars?<br>
> How many Martian days' worth of data are there?<br>
> Which month, on average, has the lowest temperature? The highest?<br>
> Which month, on average, has the lowest atmospheric pressure? The highest?<br>
> How many terrestrial days exist in a Martian year?<br>
> The DataFrame was exported into a CSV file.<br>
<br>
*Analysis*<br>
> On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!<br>
> Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.<br>
> The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.<br>
<br>
*To Use*<br>
Open .ipynb files using Jupyter Notebook.<br>
<br>
*Credits*<br>
Grepper Chrome Extension<br>
AskBCS Support<br>