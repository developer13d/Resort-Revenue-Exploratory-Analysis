# Resort-Revenue-Exploratory-Analysis

RESTORTSREVENUE ANALYSIS EDA

Exploratory Data Analysis for Hotels reveue and finding insights for improvement in earnings.


Hotel Business Problems

1.	In recent years, City Hotel and Resort Hotel have higher cancellation rates.
2.	Each Hotel facing issues and resulting in less revenues.
3.	Uses of rooms are less than ideal.
4.	Hotels trying to lowering their booking cancellation rates.
5.	Hotels Asked us to find out business suggestions to solve these problems.
6.	Analysis of hotel booking cancellation and to find other factors affecting revenues.
7.	This report shows yearly revenue generation and factors have no bearings on the business.

Assumptions Made

No outliers between 2015 and 2017 will have substantial impact the data used.
The information is still current and can be used to analyse a hotels possible plans in efficient manner.
The hotels are not using any of the solution suggested below.
The biggest factor affecting the earning revenue is booking cancellations.
Cancellations results in vacant rooms for the books period.
Clients make hotel reservations the same year they make cancellations.

Questions for Research

What are the variables affecting hotel reservation cancellation?
How can we make hotel reservation cancellation rate decrease?
How will hotels be assisted in booking pricing and promotional decisions?

Hypothesis

Marketing strategies need to be efficient and effective according current trends.
Customers cancel booking more frequently when waiting list is long.
Offline booking through travel agents for reservations.
Data Analysis
Found out how much the reservations are cancelled and not cancelled through percentage and counts.
 

 <img width="650" height="504" alt="Image" src="https://github.com/user-attachments/assets/ca8c4ba8-bcdc-41e7-8b30-85cd8b388888" />

Depending on the hotel type, analysing the maximum ratio of cancellation and not cancellation.
According the calculation below visualization of bar graph, the price of ‘Resort hotel is high’ and the ratio of cancel and non_cancelled is in comparison of ‘City Hotel’.


 <img width="847" height="439" alt="Image" src="https://github.com/user-attachments/assets/5c8a424a-31a7-4671-abb6-229bc81c1c76" />

In Resort hotel ADR can be the reason for cancellation but in City Hotel, maintenance and other facilities can be the reason of cancellation.
Now finding the percent value of cancellation.
Resort Hotel 
0    0.722366
1    0.277634

City Hotel
0    0.582738
1    0.417262
 
There are still 37% client who cancelled reservation that have significant impact on hotels earnings.
------------------------------------------------------------------------------------------------------------------------------------

<img width="1018" height="423" alt="Image" src="https://github.com/user-attachments/assets/598ce6c6-dcd1-478a-a334-0a9431977ca1" />


Instead of looking at each individual booking—which can vary a lot—grouping all bookings by date and taking the average. This smooths out the noise from unusually high or low rates on a given day and helps reveal useful patterns, like:
Which days tend to be more expensive (e.g. weekends vs weekdays)?
Are there seasonal spikes in prices (e.g. holidays, festivals)?
Is the hotel's pricing increasing or decreasing over time?
-The line graph shows that on certain days the average daily rate of city hotel is less than that of resort hotel and on other days, it is even less. It goes without saying that the weekend and holidays may see rise in resort hotel.
 

-------------------------------------------------------------------------------------------------------


Below Graph clearly shows the cancellation rates in are higher in the month of January for and low in the month of August. Vice versa the reservations are low in january and high in August.

 <img width="940" height="471" alt="Image" src="https://github.com/user-attachments/assets/f0b64258-827b-4036-89d8-79a624c7e856" />


We have created the grouped bar graph to analyse the month with the highest and lowest reservation levels according to the reservation status. As we can see the confirmed reservation and the number of cancelled reservation are largest in the month of August. Whereas January is the month has large number of cancelled reservation.


------------------------------------------------------------------------------------------------------------


Below CHART is plotting sum of ADR per month for cancelled bookings

If ADR is low in the month of August in comparison to high reservation in the same month.


<img width="940" height="549" alt="Image" src="https://github.com/user-attachments/assets/afc8142d-82be-4621-86bd-0da648a4586f" />

 

This bar graph shows that the cancelations are most common when prices are greatest and are least common when they are lowest. Therefore, the cost of the accommodation is solely responsible for the cancellation.
 

Top 10 countries shows the reservation cancellation and Portugal is the highest reservation cancellation among all top 10 countries.
For this country, a suggestion can be-

<img width="850" height="797" alt="Image" src="https://github.com/user-attachments/assets/51d00e5d-72d6-46ca-bd14-dcf7d41af6a5" />

Our previous hypothesis was that the hotels getting more reservation through offline TA.
We have found Booking values according to market segment below. Checking the area from where guest are visiting hotels and making reservation Online, offline, direct coming or travel agent. About 46% of client come from online TA, whereas 27 % coming from group. Only 4% come for offline by vising them.



market_segment
Online TA        56402
Offline TA/TO    24159
Groups           19806
Direct           12448
Corporate         5111
Complementary      734
Aviation           237

Booking value via Market segment	market_segment
Online TA        0.474377
Offline TA/TO    0.203193
Groups           0.166581
Direct           0.104696
Corporate        0.042987
Complementary    0.006173
Aviation         0.001993

Booking percent via Market segment	market_segment
Online TA        0.469696
Groups           0.273985
Offline TA/TO    0.187466
Direct           0.043486
Corporate        0.022151
Complementary    0.002038
Aviation         0.001178

Cancelled percent via market segment

As per above shown analysis our previous hypothesis goes wrong as in more booking coming from online TA.
Also the cancelled rates are more in online booking than offline booking as shown in data figure above.
Reason for cancellation can be the false presentation of hotel services and views which leads to cancel the reservation.

AVERAGE DAILY RATE 2016 TO 2017

<img width="964" height="444" alt="Image" src="https://github.com/user-attachments/assets/893f89e5-6182-43bf-bee3-4167d77effbb" />

 

ADR of Cancelled reservations are high and ADR of non-cancelled reservations are low.
The spikes visible in the graph are for weekends and end of the month when the charges go down or up.
When ADR is high reservation got cancelled then when it is not cancelled. Above analysis shows the higher prices leads to higher cancellations. 

SUGGESTIONS

Cancellation rate is high as the prices does. In order to minimize the cancellation hotels can make strategies to lower the rates of specific hotel depending on the location. They can also provide some discount to the consumers.

As the ration of cancellation and not cancellation of the resort hotel than the city hotel. So the hotel should provide reasonable discount for rooms on weekends and holidays.

In the month of January hotels can start campaign or marketing with reasonable amount to increase their revenue as the cancellation is the highest in this month.
Hotels can offer a quality service and maintain hotels, mainly in Portugal to reduce the cancellation rate.
Increase the quality service, Reservation price must be affordable, Advertisement campaign should run. Promotional discounts and offers 




