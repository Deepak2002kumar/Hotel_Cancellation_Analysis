
# Hotel_Reservation_Cancellation_Analysis

## Contents

- Hotel_bookings 2.csv : Raw Data Set in CSV format.
        [Download](https://github.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/blob/main/hotel_bookings%202.csv)

- Hotel_Cancellation_Analysis.ipynp : Jupyter notebook to understand code. [Download](https://github.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/blob/main/Hotel_Cancellation_Analysis.ipynb)
- Report_H_C_Analysis.pdf:  Report in PDF Format [Download](https://github.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/blob/main/Report_H_C_Analysis.pdf)

## Business Problem

In recent years, City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result, including fewer revenues and less than ideal hotel room use. Consequently, lowering cancellation rates is both hotels' primary goal in order to increase their efficiency in generating revenue, and for us to offer thorough business advice to address this problem.

The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this report


## Assumptions

- No unusual occurrences between 2015 and 2017 will have a substantial impact on the data used.
-  The information is still current and can be used to analyze a hotel's possible plans in an efficient manner.
-  There are no unanticipated negatives to the hotel employing any advised technique. 
-  The hotels are not currently using any of the suggested solutions.
-  The biggest factor affecting the effectiveness of earning income is booking cancellations.
-  Cancellations result in vacant rooms for the booked length of time.
-  Clients make hotel reservations the same year they make cancellations.

## Research Question
-  What are the variables that affect hotel reservation cancellations?
-  How can we make hotel reservations cancellations better?
-  How will hotels be assisted in making pricing and promotional decisions?

## Hypothesis
-  More cancellations occur when prices are higher.
-  When there is a longer waiting list, customers tend to cancel more frequently. 
-  The majority of clients are coming from offline travel agents to make their reservations.

## Analysis and Findings

### Bar Plot of Cancelled Vs Not Cancelled Reservations

![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_1.jpg)

The accompanying bar graph shows the percentage of reservations that are cancelled and those that are not. It is obvious that there are still a significant number of reservations that have not been cancelled. There are still 37% of clients who cancelled their reservation, which has a significant impact on the hotels' earnings.

### Bar Plot of Reservation Status in Different Hotels

![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_3.png)

In Comaprison to Resort hotels, City Hotels have more bookings. It's Possible that Resort hotels are more expensive than those in cities. 

### Average Daily Rate (ADR) in City Vs Resort Hotels
![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_2.png)


The line graph above shows that, on certain days, the average daily rate for a city hotel
is less than that of a resort hotel, and on other days, it is even less. It goes without saying that weekends and holidays may see a rise in resort hotel rates.

### Reservation Status on Month basis 

![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_4.png)

We have developed the grouped bar graph to analyze the months with the highest and lowest reservation levels according to reservation status. As can be seen, both the number of confirmed reservations and the number of canceled reservations are largest in the month of August. whereas January is the month with the most canceled reservations.

### Average Daily Rate (ADR) by Month 

![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_6.png)

This bar graph demonstrates that cancellations are most common when prices are greatest and are least common when they are lowest. Therefore, the cost of the accommodation is solely responsible for the cancellation.

Now, let's see which country has the highest reservation cancelled. The top country is Portugal with the highest number of cancellations

![E-R.png](https://raw.githubusercontent.com/Deepak2002kumar/Hotel_Reservation_Cancellation_Analysis/main/Report_Image_7.png)


Let's check the area from where guests are visiting the hotels and making reservations. Is it coming from Direct or Groups, Online or Offline Travel Agents? 

#### market_segment
        Online TA        46.969560
        Groups           27.398532
        Offline TA/TO    18.746603
        Direct            4.348614
        Corporate         2.215075
        Complementary     0.203841
        Aviation          0.117775




Around 46% of the clients come from online travel agencies, whereas 27% come from groups. Only 4% of clients book hotels directly by visiting them and making reservations.

## Suggestions 

- Cancellation rates rise as the price does. In order to prevent cancellations of reservations, hotels could work on their pricing strategies and try to lower the rates for specific hotels based on locations. They can also provide some discounts to the consumers.
- As the ratio of the cancellation and not cancellation of the resort hotel is higher in the resort hotel than the city hotels. So the hotels should provide a reasonable discount on the room prices on weekends or on holidays.
- In the month of January, hotels can start campaigns or marketing with a reasonable amount to increase their revenue as the cancellation is the highest in this month.
-  They can also increase the quality of their hotels and their services mainly in Portugal to reduce the cancellation rate.




