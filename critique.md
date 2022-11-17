
# **Critique by Design**

## **Introduction**

For this project I was excited to critique and redesign a visualization of crime data because there is much to be gained and lost in a community if crime data is misrepresented. I thought it would be best to start close to home, so I decided to find crime statistics for Allegheny County. The county website had a dashboard that was easy to find, and before long I was able to find a lot of data visuals to work with.  I decided that the audience who would be presented with this information would be a resident of Pittsburgh, or perhaps someone considering moving to Pittsburgh, and so I would do my best to frame my critique on behalf of someone in either of those positions.
## **Materials to Critique**
![image](https://user-images.githubusercontent.com/117220516/202344280-3af389a1-e004-40e9-97b2-359cb2ce880c.png)
While there is a lot of visual information to be scrutinized here, I thought it would be best to focus on one specific element. The heat map titled “When do the offenses occur?” Immediately caught my eye. I like heat maps when they are used correctly, but their style can often conceal a lot of nuance in the data they are presenting. I immediately liked that they were using a color scale of white and gold. This allows them to use the same color text in each of the cells, in this case they are using black text, without sacrificing readability.

![image](https://user-images.githubusercontent.com/117220516/202344354-c92a179a-07a5-462c-a32c-aa7ada3fee03.png)

Upon closer examination I saw that the data was all listed as percentages, and the spread of percentages did not vary greatly. The lowest amount was 2% and the highest was 5%. With such a narrow spread, but so much variation of color, I began to feel like there was a lot of information that was not being represented adequately. Looking at the top row, which contained crimes reported in the morning, I saw that each day had percentages listed at 2% but the variation of color was significant. This felt very contradictory so I decided to pull out the individual numbers and see what kind of simple visualization I could sketch out….
## **Initial Wire Frame**
![pic3](https://github.com/duncbind/portfolio/blob/main/IMG_7926.JPEG?raw=true)

While not always appropriate as a final product, for an initial exercise I like to see what chronological data looks like in a line chart. In this case it became apparent that there were a few things that stood out, namely the spike in reported crimes on Saturday and Sunday Night, but it became harder to look at trends from other days in the week because there was so much overlap in the data. I decided to scrap the line chart in favor of a bar chart, and to try grouping bars by the sections of the day to make those trends a little easier to compare. 

![pic3](https://github.com/duncbind/portfolio/blob/main/IMG_7928.JPEG?raw=true)
## **Second Wire Frame**
![pic3](https://github.com/duncbind/portfolio/blob/main/IMG_7927.JPEG?raw=true)


I was much happier with the look of this chart. While certainly not complete, I felt like the data was already being presented more honestly. Eliminating the percentages in favor of the actual counts gave a much more accurate representation of the data. Trends are becoming more evident, such as the universal lull in criminal activity in the early mornings, and the spike on Saturday and Sunday evenings. I felt ready to show it to two individuals to see what they thought.

Here are their responses to the questionnaire I presented them with…


## Female, Early 30’s
- Can you tell me what you think this is?
>*Probably the number of reported crimes in Pittsburgh based on the time of week, and time of the day. These numbers are high, but they probably include stuff like petty theft. Maybe in a year? Hopefully not in a month.*

- Can you describe to me what this is telling you?
>*If I am getting this right, most crime happens at night on Saturday and Sunday and not a lot of crime happens in the morning. Afternoons and evenings are about the same, a little bit more in the evening. What I would be interested in is seeing if there is a seasonal effect. Is there more crime in the summer vs the winter? Do things spike up in the spring?*

- Is there anything you find surprising or confusing?
>*I would just say it would definitely help to have a label on the X axis to know what the count is. Just knowing if this is the number of reported cases per year, per month, what does 12k mean? What does 8k mean? Right now it just feels relative to the other bars.*

- Is there anything you would like to see added or removed for the sake of clarity?
>*I don't mind the numbers at the end. I know some people would say it could be cleaner, but I like it. There are always a couple dimensions going here, day of the week, time of day, counts, so three dimensions. I guess if you wanted to use another dimension you could use color, or use color to highlight a dimension that is already being displayed. You could use shapes, but that might make things a little bit “much.”*

- Who do you think is the intended audience for this?
>*Nerds! Just kidding. Probably the police departments, people managing or running the city? Citizens? The Media?*

- Is there anything you would change or do differently?
>*Yeah, I would add a label for the X axis, just saying what it is. Maybe add some color? Bringing some seasonality to it somehow? Maybe have a filter that shows the time of year or month?*

## Male, Late 20’s
- Can you tell me what you think this is?
>*This looks to be the crime rate in Pittsburgh. I see that it is broken down in times of day and days of the week. There seems to be a lot of crimes on Saturday and Sunday Night.*
- Can you describe to me what this is telling you?
>*I can see that there is a lot of crime that occurs on weekend nights. It looks like no one likes to commit crime in the morning. The evening and afternoon look about the same. It's crazy how little there is on Sunday Morning.*
- Is there anything you find surprising or confusing?
>*I don't really understand what is being considered a crime. Also, what time frame is this going off of? I don't really know enough to tell whether this is a year's worth, or even which year this might be.*
- Is there anything you would like to see added or removed for the sake of clarity?
>*I would just like to see more descriptions of what we are looking at. I like that it is asking a question and not telling what to think, but the answer is kind of obvious. A little color would be a nice way to make it more interesting.* 
- Who do you think is the intended audience for this?
>*People who live in Pittsburgh.*
- Is there anything you would change or do differently?
>*There is a lot of information, but just a little more context would be very helpful.*

## **Feedback Synthesis**
The two people I interviewed gave some really useful feedback. My tendency with data visualization is to be biased towards less is more, but sometimes less is just less. Omitting the timeframe that the crimes were reported in is incredibly misleading. If a resident of Pittsburgh thought that many crimes were reported in anything less than 12 years they would have a drastically different view on their city. They might vote differently, avoid certain parts of town, or perhaps move all together. Moving forward I would be less hesitant to provide additional information to inform the audience.

![pic3](https://github.com/duncbind/portfolio/blob/main/IMG_7929.JPEG?raw=true)


## **Final Product**

 I decided I had to make the title a little more specific about the data that seemed important for a resident, and provide additional information on the span of time that the data was collected, and a brief summation of trends that were present. I added the time frame the data was collected into the X axis to provide more clarity. The days marked on the Y axis felt very repetitive, so I removed them and color coded the bars. While the colors could be overwhelming, I wanted to include the specific numerical values on the Y axis as well, and having the abbreviated days would make it a little too busy. I also added the option to select specific days to view by clicking their portions of the legend.

<div class="flourish-embed flourish-chart" data-src="visualisation/11849289"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


[Back to portfolio](https://duncbind.github.io/portfolio/)
