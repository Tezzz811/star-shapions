# star-shapions
EDA ON HOTEL BOOKING analysis

STAR SHAPIONS

SAYED FARUK
SHRADDHA GUJAR
ARUN PALLE
TEJAS PATIL
RISHAV KUMAR

Introduction -
We have got the hotel bookings dataset. Our motto is to perform Exploratory Data Analysis on the given hotel booking CSV data set & to get a comfortable conclusion about general fluctuation in hotel booking and how things ruling in hotel bookings are related with each other.


Dataset -
This data set contains booking information for a city hotel and resort hotel. It includes information such as type of the hotel, how many time it is cancelled, lead time, arrival date & month, stays in weekend nights, stays in week nights, children, adults, babies, country, market segment, distribution channel, is it repeated guest, previous cancellation, previous bookings, reserved room type, agent, company, customer type, required car parking & reservation status etc.


Understanding the whole dataset with help of column names. Given below is clearly mentioned.

hotel: Name of hotels

is_canceled : Indicating the booking was cancelled (1) or not cancelled (0)

lead_time : Number of days that elapsed between the entering data of booking

arrival_date_year : Year of arrival date

arrival_date_month : Month of arrival date

arrival_date_week_number : week number of year of arrival

arrival_date_day_of_month : Day of arrival date

stays_in_week_nights : The number of weekend nights ( Saturday and Sunday ) the guest stayed in hotel

stays_in_week_nights : Number of week days ( Monday to Friday )the guest stayed in hotel

adults: Number of adults stayed in hotel

children: Number of children stayed in hotel

babies: Number of babies stayed in hotel

meal: type of meal booked by customers

country: country of origin

market_segments : 'TA' means travel agent and 'TO' means team operators

distribution_channel : Booking distribution channel

is_repeated_guest : Repeated guest (1) or not repeated guest (0)

previous_cancellations : Number of booking that were cancelled by customers

previous_bookings_not_canceled : Number of bookings that were not cancelled by customers

reserved_room_type : Code is represented by room which is booked by customer

assigned_room_type : code is type of room assigned to the booking

booking_changes : Number of charges made to the booking

deposit_type : Indicates on the customer made a deposit to guarantee the booking

agent: ID for travel agency

company: Company ID entity that made booking or responsible for booking payment

days_in_waiting_list : Number of days from booking to confirmation booking

customer_type : booking assuming for four categories

adr : Average daily rate sum of all loading transactions dividing by total number of staying nights

required_car_parking_spaces : Car parking space required by customer

total_of_special_requests : Total special requests made by customer

reservation_status : Reservation status, assuming in three categories

reservation_status_date : Date of the last status was set








Data cleaning –

Removed duplicate rows
            All duplicate rows were dropped. 
Handled null values 
Null values are columns company & agent were replaced by 0
Null values in column country were replaced by ‘others.
Null values in column country were replaced by ‘0’ of the column.
Removing outliers





Questions performed in EDA - 
Which hotel is most preferred by customers?
Which month visitors visit highly?
Which type of room is highly booked and preferred by customers?
Which year got the best sale?
Which hotels are mostly cancelled by the customers?
Which type of customers are highly visited on both hotels?
What is the percentage of repeated guests?
What is the percentage distribution of deposit type?


Libraries and tools used in EDA -
Pandas
NumPy
Seaborn
Matplotlib

Graphs & plots been used -
Count plot
Pair plot
Heatmap
Histogram
Boxplot
Distort
Pie chart


Challenges faced – 
Huge amount of data was present in the dataset.
Dealt with some missing values.
Huge number of null values were present in the dataset.
Faced difficulties in understanding the data.



Final outcome (Result) -
 We learnt
Guests mostly preferred city hotels because city hotels have maximum bookings.
August is one of the months with a high number of visitors.
Code ‘A’ rooms are most preferred by customers because code ‘A’ rooms are highly booked by customers.
In 3 years of data, we got to know that sales of 2016 are higher than 2015 & 2017.
 City hotels are mostly cancelled by the customers after booking.
Transient types of customers are highly visited in both hotels.
3.2% of customers are repeat guests.
87.6% of data is distributed in deposit type.






Conclusion –

We used the dataset that contains data about hotel bookings (which was already given). We solved the challenges that we faced while performing the project. It took us a lot of time to get the solution of questions that we performed in our Collab notebook. After cleaning the data, we simply grabbed it. We had to understand the whole data first and then we performed the Exploratory Data Analysis to get the answer to our questions.
