# Python-CL-Sep-2018-Mon
My Python data analysis project for Code Louisville

Start up:
1. Clone and download files from GitHub
2. Open Duos_beta.ipynb in jupyter notebooks through Anocanda.
3. Run all of the cells

This project was inspired by my love of competitive gaming and drive to keep improving my skill.

I am pulling my friends player data for Fortnite so I can see if he has been playing better week to week. I also want to look day to day within those weeks to see if he played better on a specific day.

My hypothesis is that he plays better on the weekend and that he continues to get better week to week.

Under each section is a description of what the code is doing.

I started by requesting an API key to the TRN Fortnite match tracker.
then I used their url and the key to pull my friends match data. This tracker only pulls a snapshot of the last 50 matches he has played so I pulled the data multiple times over the last few weeks.
Each time I would merge the new data with the data I already had and clear all duplicates.
Then I grouped the matches by the day they were played.
At this point I pulled all my import statements to the top so that I didn't input the same thing twice and that someone looking and see everything I imported easily.
So I ended up with 4 weeks of data.
I put the data in a table to see if it looked correct then queried to get the total number of kills and matches for each day so that I could find the average kills per match on each day.
Then I plotted the kills per match or KPM for each day by week. So week one he played 4 days Thursday through Sunday. The data from the API put Sunday at the end of the week. This actually helped me because games are played more on the weekend so it makes sense to group the whole weekend together.
The line graph made it easy to see multiple weeks and to compare the same day of the week from each week.

In conclusion I found that he does seem to play better on the weekend but it looks like he does worse week to week though the last week seems to be average.
I also found something not in my hypothesis! He plays the most on the weekends which I assumed but I noticed he never plays on Wednesdays. (Maybe he works longer hours on Wednesdays? I'll have to ask.)
