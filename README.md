**Hotel Booking Data Analysis using Python.**

***Project Overview:***
To analyze hotel booking data to uncover insights into customer behavior, booking trends, cancellation patterns, and operational efficiency using data visualization and statistical tools.

***Problem Statement:***
Discovered key trends such as higher cancellation rates among city hotel bookings, seasonal peaks in reservations, and the impact of lead time, deposit type, and distribution channel on cancellations. Identified customer segments with higher booking reliability and revenue contribution.

***Dataset Information:***
- The dataset includes booking information for two types of hotels:
1.  City Hotel
2.  Resort Hotel
- This dataset contains a mix of categorical, numerical, and date-related features relevant to hotel bookings.

***Goal:***
1. Where do the maximum Guest come from which country.
2. Creating Graph as country wise data.
3. Pivot table for differnce between assigned and reserved room types.
4. Which market segment has highest bookings.
5. Analysing avg price per night(ARD) of various room-types for all the market segment.
6. Analyze the Distribution of "Guest_Arrivle".

**1] Where do the maximum Guest come from which country.**
<img width="751" height="465" alt="guest coming from" src="https://github.com/user-attachments/assets/b3b9ffa5-239a-45ed-99cb-0f49e70cc461" />.

📊 **Conclusion from the Chart: Top 5 Countries by Number of Guests**
1. Portugal (PRT) leads significantly in the number of hotel guests, indicating a strong domestic travel trend or hotel popularity among locals.
2. United Kingdom (GBR) and France (FRA) follow as top foreign contributors to hotel bookings.
3. Spain (ESP) and Germany (DEU) are also notable source countries, though with lower guest numbers compared to the top three.
4. The large gap between Portugal and other countries suggests domestic tourism plays a dominant role in hotel occupancy.
5. The hotels analyzed may be located in Portugal, as domestic guests often outnumber international ones in such datasets.

**2] Creating Graph as country wise data.**

<img width="700" height="360" alt="newplot (1)" src="https://github.com/user-attachments/assets/d83bbdce-d3df-4f67-b7fb-0ddf526f10de" />.

The choropleth map visualizes the number of hotel guests by their home country. **Portugal** (PRT) is the most prominent source, with over **17,000 guests**, highlighted in bright yellow. Other European nations such as the **UK, France, Spain, and Germany** also contribute significantly, shown in lighter shades. In contrast, countries from Africa, Asia, and South America appear in darker colors, indicating fewer guests. The visualization reveals a clear concentration of hotel guests from **Europe**, especially **Western Europe**.

**3] Pivot table for differnce between assigned and reserved room types.**

<img width="466" height="306" alt="pivot" src="https://github.com/user-attachments/assets/dbafe8de-2cf2-415b-9674-04709ecdf358" />

The pivot table shows that most guests were assigned the same room type they reserved. Minor mismatches occurred, mainly for room types A, D, and H. Room type H had notable cross-assignments, while types B, C, and F showed high accuracy in assignment, indicating effective room allocation overall.













