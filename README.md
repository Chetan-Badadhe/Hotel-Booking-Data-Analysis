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

***Goals:***
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

**4] Which market segment has highest bookings.**

<img width="800" height="600" alt="newplot (2)" src="https://github.com/user-attachments/assets/7dc751df-04c7-4a35-a960-c7b7e96b3429" />.

The pie chart shows that most hotel bookings (59.1%) come from Online Travel Agents, followed by Offline TA/TO (15.9%) and Direct bookings (13.5%). Other channels like Groups, Corporate, Complementary, and Aviation contribute marginally, indicating heavy reliance on online platforms for guest reservations.

**5] Analysing avg price per night(ARD) of various room-types for all the market segment.**

<img width="821" height="515" alt="ard" src="https://github.com/user-attachments/assets/a946bff8-b1be-45d7-a659-61b08fa34dd9" />.

The bar chart displays average daily rates (ADR) across market segments and reserved room types. Online TA and Offline TA/TO segments show the highest ADRs, especially for room types L, H, and G. Complementary and Undefined segments have the lowest ADRs, indicating minimal or no revenue contribution.

**6] Analyze the Distribution of "Guest_Arrivle".**

<img width="575" height="446" alt="dis" src="https://github.com/user-attachments/assets/4398142d-5fcd-4013-bb78-a6010640a622" />.

The density plot shows the distribution of average daily rates (ADR) in hotel bookings. The distribution is right-skewed, with most values concentrated between 50 and 200. The peak density occurs around 150, indicating that this is the most common ADR value. Fewer bookings have ADRs above 250, with a gradual taper toward higher values. This suggests that mid-range pricing is most prevalent, while high-end rates are relatively rare.


**📊 Tools & Technologies Used:**
- Python for data handling and scripting.
- Pandas and NumPy for data cleaning and manipulation.
- Matplotlib and Seaborn for static visualizations.
- Plotly for interactive plots.
- Jupyter Notebook for coding and presenting analysis

Here’s a concise and insightful **Project Conclusion** for your *Hotel Booking Data Analysis* project:

---

**Conclusion:**

This project successfully analyzed hotel booking data to uncover actionable insights related to guest behavior, booking sources, pricing trends, and operational efficiency. The analysis revealed that:

* **Online Travel Agencies (OTAs)** are the primary source of bookings, suggesting that digital platforms significantly influence customer acquisition.
* **Portugal, UK, and France** are top countries of origin for guests, indicating regional market dominance.
* The **majority of guests receive their reserved room type**, reflecting well-managed room assignment systems.
* The **ADR (Average Daily Rate)** is highest for guests booking through corporate and OTA channels, which can guide targeted pricing strategies.
* Booking patterns and ADRs show notable **seasonality and distribution peaks**, useful for revenue forecasting and inventory planning.

Overall, the project provides hotels with a data-driven foundation to optimize **marketing, pricing, and operational strategies**, ultimately enhancing guest satisfaction and revenue performance.



























