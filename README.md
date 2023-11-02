# Final-Project-Tableau

## Project/Goals
Primarily, the goal was to use Tableau to inspect, filter, display, and analyze the data from a dataset. As well, formulating questions along the way is a good practice.

## Process
1) Obtain and load data into Tableau, then use the interface to explore the data.
2) Visualize the story you want to tell, then design figures and graphs to help you do that.
3) Put together related visuals onto dashboards, and combine them into a coherent story.

## Results
I went with Option 2 using the FAA Wildlife Strike Database. The data was cleaned and through inspection I noted that some fields were going to be less useful (number of strikes/incident, number of engines, aircraft type) and most useful (the generated variable that counts the number of strikes). Cleaning mostly consisted of finding outliers in the dataset, one in particular, which dwarfed all the others in cost.

The 'results' of this exploratory analysis must be taken with extreme caution, as there are really no inferences that can be made about wildlife collisions at airports in the US without data that quantifies the overall flights. As well, because the data are voluntarily submitted (see Challenges below), the data is likely highly skewed toward events that might not be easily to escape reporting (high-profile or events with many witnesses). However, with those cautions, some trends within the data can be spoken about.

After analyzing the dataset, it was clear that the number of (reported) strikes are increasing over time. Birds are the wildlife group with by far the most strikes, and the most costly strikes. Seasonality and time of day follow the pattern of bird activity: Summer is the season when most strikes occur, and most strikes happen during the day. However, when looking at specific species different patterns emerge ie. Deer are most often struck in the months of September and October. Mammals and Bats are also more likely to be struck at night than during the day. The most costly strikes in the database were caused by birds, but by birds within the Goose family in particular.

## Challenges 
This data has a lot of information, but much of it lacks context. The strikes were probably not evenly represented, as strikes with no damage I'm sure are underreported (this is voluntary reporting). As well, it seems as though most airports are either not taking place or their data is not included in this public dataset. Also, there is no data on the number of flights each day without strikes, relative air traffic based on time of day, season, etc. so there is no way to know whether strikes were more common using any of this data because there were in effect no control population. The one thing you could sort of measure was the amount of damage... but because of the difficulty expressed earlier, even those conclusions would be pretty dubious. 

## Future Goals
I would try to find some sort of data on the number of flights on each day, to have a reference to compare this data to.
