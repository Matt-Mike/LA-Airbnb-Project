# LA-Airbnb-Project

## Project Summary<br/>
Dashboard analyzing the Airbnb property market in Los Angeles.<br/>

I've always had an interest in renting out an Airbnb. Being from Los Angeles, I was curious as to how the Airbnb market is performing there.<br/>
<br/>

**Skills Used:**<br/>
- **SQL** to analyze and format table data
- **Power BI** for visualization
<br/>

**Desired Insights:**<br/>
- How has the market been trending yearly?
- What are the most popular months?
- What is the average price per night?
- How many listings are there in LA?
- Where are the most popular listings located?
- What is the most popular listing type?
<br/>

## Preparing the Project Data<br/>

**The Dataset:**
Found on http://insideairbnb.com/ <br/>

![Inside Airbnb Website](https://user-images.githubusercontent.com/111325425/201702397-c75930ca-a228-40b0-999e-30f2fd76522c.PNG)<br/>
<br/>

**Importing the Dataset to PostgrSQL:**<br/>

First I created the following tables:<br/>

![Create table - listings](https://user-images.githubusercontent.com/111325425/201702771-f4cb0970-1698-4017-b5ae-f6d66d5ac6d2.PNG)

![Create table - neighbourhoods](https://user-images.githubusercontent.com/111325425/201702798-d1f6bf20-2459-4c2a-a287-256659eb4fee.PNG)

![Create table - reviews](https://user-images.githubusercontent.com/111325425/201702820-f81c9b62-32be-4fad-8735-af41edfd0708.PNG)<br/>
<br/>

**I then imported the files and queried the following table:**<br/>

![MAIN QUERY](https://user-images.githubusercontent.com/111325425/201703151-ac8408ae-60c7-4809-a766-157337b2d1dc.PNG)<br/>
<br/>

## Creating the Visualization<br/>

No pictures here, but this was my ideation process for creating the dashboard:<br/>
- My goal was to create a one-sheet dashboard that tells the entire story
- I wanted to create a few simple insights that would answer my questions
- I wanted to make the dashboard interactive in order to drill into specific areas, months, years, etc.

In the end I was able to accomplish this, and felt pretty good about the results.<br/>

## Key Takeaways from the Data<br/>

This info is also on the dashboard itself, but I'll repeat it here:<br/>
- **Now is still a good time to rent out an Aibnb.**
  - 2019 was the peak year but listings have been steady since then.
  - Summer months are the most popular for LA, but business appears to be consistent year-round.
- **Most popular areas are by the beach or downtown.**
  - Venice is the most popular location.
  - 3 of the top 5 locations are beachside areas.
  - 4 of the top 15 are Hollywood cities.
- **Rent out the entire property if possbile.**
  - The large majority of listings are for the entire property.

Of course, properties in LA are expensive, but if you are able to purchase one as an investment, the conclusions drawn here provide valuable insights!
