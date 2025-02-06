# Project Portfolio for R. Scott Navert
This is a Website for my Data Science and Research Portfolio. Please share!

My name is Scott Navert. I have over 9+ years of experience working in Data and Analytics, including data visualization, advanced modeling in Python and Excel, ETL, and SQL. I've built this website as a comprehensive portfolio of my work and interests, for friend, coworkers, and any other interested individuals. 

Please find here some of my historical projects and any new or interesting things I am currently working on in my spare time. I've also included samples and certificates of my work, including SFDC Adminsitrator Certification, Tableau Desktop Certification (Udemy), Python Certification (Udemy), and other examples of my abilites in data analysis and SQL. 

##  Skills Expertise & Certification

As a demonstration of my ability in SQL, I've attached a few SQL tests and my current HackerRank profile.

SQL TEST #1: Education Software Company [(link)](https://docs.google.com/document/d/1kPCdby7zHIdXxrcoJCSNkj3z8DWOGgeJvpjt7pHoq5o/edit?tab=t.0)
SQL Test #2: Hospitality & Travel [(link)](https://docs.google.com/document/d/1nEt7up1HWvwAYmUtHboizvhUy2he2VvZRGoNXk-zEtw/edit?tab=t.0)

HackerRank Portfolio: [(link)](https://www.hackerrank.com/profile/scottnavert)

Salesforce Administrator Certification: Udemy // SDFC Certified
Tableau Desktop Certification: Udemy
Python Certification: Udemy

## The Snowfall Scraper
In late 2017, I was working on managing a portfolio of winter homes in Utah and Colorado. I wanted to leverage the website OnTheSnow to best identify market trends for our short term ski markets. My hypothesis was: If we can identify heavy snowfall periods, would that inform our rates and revenue strategy for any drive-to customers in these ski markets? Could we make more money with just a little bit more information?

By using this scraper, I was able to identify short and long term pricing strategy based on the snowfall in 2 ways:

Short Term: This was the easiest, as by tracking snowfall ahead of weekend skiing, we could accurately map new customers booking homes for the weekend across our ski markets in Utah, Colorado, and California. This assisted in flexing our pricing to optimize based on current and projected snowfall

Long Term: This was a little more nuanced, but by following trends from year to year (2017-2019 when I was managing these markets), we were able to track how much snowpack was necessary for skiiers to take weekend trips AND how much snowfall bumped up demand. By matching lead to times from year to year, our pricing became more dynamic than our competitors, leading to higher yield for Vacasa's owners. 

You can find the code [here](https://github.com/TheScottN/snowfall).

## Business Case Study Examples

##  Fun Projects
### NFL Power Rankings & Why I Hate The Curse Wheel
Like many American Football fans, I believe in superstition. Whether it is to wear a favorite jersey, sit in a lucky chair, or adhere to any assortment of minor karmic influences, I hope that my contributions to the cosmic justice will appease the Football Gods. However, what if I told you that 

Brandon Perna, of the Youtube Channel [ThatsGoodSports](https://www.youtube.com/channel/UCew5br5cO1ZKO7Z_F1WA8Bg), exemplifies this superstition. Mr. Perna makes a weekly Power Ranking of the Top 10 teams in the NFL, and then randomly chooses a team to "curse" that week from his spinning wheel of foretelling doom. During his weekly videos I bate my breath that my football team somehow avoids this internet voodoo (although lately the Cowboys haven't been good enough to crack the Top 10.). But while Mr. Perna keeps a public record of his rankings in video form, I haven't found a great resource of tracking or deriving insights from his rankings. 

The idea was to determine: How effective is Brandon's Curse Wheel, and can we determine any meaningful insights from his near pansophical foretelling of a team's doom?

To determine this, I created a record of each team's ranking per week starting from 2022 when the first ranking came out. Then, coupling with a Pandas formatted schedule, I could match each team's regular season performance with their ranking. Finally, by adding in the "cursed" team per week, I could mark each instance of a curse and how it affected the outcome of a team, game, or season. By using Python for statistical analysis and formatting, SQL for database storage and report writing, and Tableau to visualize the insights, I could better provide insights for myself and fans of ThatsGoodSports alike to see how effective the Curse Wheel was. 

Here's what we found:

You can find the code and additional materials [here](https://github.com/TheScottN/tgs_curse_wheel)

### Identifying Luck in Mario Party: A 25 Year Journey
