# Hotel Booking and Cancelation Analysis

The Hotel Booking Cancellation Analysis project aims to analyze the patterns and factors contributing to hotel booking cancellations. With the increasing popularity of online hotel booking platforms, understanding the reasons behind cancellations can provide valuable insights to hotel managers and help optimize revenue management strategies.

This project leverages the power of Python and various libraries to perform comprehensive analysis on a dataset containing hotel booking information.
The key Python libraries used in this project include:

Pandas: Pandas is a powerful data manipulation library that provides high-performance data structures and tools for data analysis. It allows for efficient handling, cleaning, and preprocessing of the hotel booking dataset.

Matplotlib: Matplotlib is a widely used plotting library that enables the creation of various types of visualizations. It allows for the generation of insightful graphs, charts, and plots to visualize trends and patterns in hotel booking cancellations.

Seaborn: Seaborn is a data visualization library built on top of Matplotlib. It provides a high-level interface for creating aesthetically pleasing statistical graphics. Seaborn enhances the visual appeal and readability of the generated plots.

## Hypothesis

1. More cancellations occur when prices are higher.
2. When there is a longer waiting list, customers tend to cancel more frequently.
3. The majority of clients are coming from ofﬂine travel agents to make their reservations.



## Analysis and Findings

![Alt text](Visualisation%20Images/Reservation%20Status%20Count.png)

The accompanying bar graph shows the percentage of reservations that are canceled and those that are not. It is obvious that there are still a signiﬁcant number of reservations that have not been canceled. There are still 37% of clients who canceledtheir reservation, which has a signiﬁcant impact on the hotels' earnings.



![Alt text](Visualisation%20Images/Reservation%20status%20in%20different%20hotel.png)

In comparison to resort hotels. city hotels have more bookings, It‘s possible that resort hotels are more expensive than those in cities.


![Alt text](Visualisation%20Images/Average%20Daily%20Rate%20in%20City%20and%20Resort%20Hotel.png)

The line graph above shows that, on certain days, the average daily rate for a city hotel is less than that of a resort hotel. and on other days, it is even less. It goes without saying that weekends and holidays may see a rise in resort hotel rates.


![Alt text](Visualisation%20Images/Reservation%20Status%20per%20month.png)

We have developed the grouped bar graph to analyze the months with the highest and lowest reservation levels according to reservation status. As can be seen. both the number of conﬁrmed reservations and the number of canceled reservations are largest in the month of August. whereas January is the month with the most canceled reservations.


![Alt text](Visualisation%20Images/ADR%20per%20month.png)

This bar graph demonstrates that cancellations are most common when prices are greatest and are least common when they are lowest. Therefore. the cost of the accommodation is solely responsible for the cancellation.

Now, let's see which country has the highest reservation canceled, The top country is Portugal with the highest number of cancellations.

![Alt text](Visualisation%20Images/Top%2010%20Countries%20with%20Reservation%20canceled.png)

Let's check the area from where guests are visiting the hotels and making reservations. Is it coming from Direct or Groups, Online or Ofﬂine Travel Agents? Around 46% of the clients come from online travel agencies, whereas 27% come from groups. Only 4% of clients book hotels directly by visiting them and making reservations.

![Alt text](Visualisation%20Images/Average%20Daily%20Rate.png)

As seen in the graph, reservations are canceled when the average daily rate is higher than when it is not canceled. It clearly proves all the above analysis, that the higher price leads to higher cancellation.

## Conclusion

1. Cancellations occur more when prices are higher.
2. The majority of clients are coming from online travel agents to make their reservations so your hypothesis was wrong

