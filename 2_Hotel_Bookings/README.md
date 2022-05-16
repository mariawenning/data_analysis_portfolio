In this mini-project I analysed the data of Hotel bookings with Pandas. 

**1. Goals of the project:**
 - Exploratory Data Analysis 
 - Calculate the Customer Churn Rate

**2. Functions used:**

read_csv, dtype, info, rename, groupby, agg, query, sort_values, idxmax, idxmin, value_counts

**3. Data description:**

The following variables are available:

 - Hotel - type of hotel (City Hotel or Resort Hotel)  
 - Is canceled - reservation was cancelled (1) or not cancelled (0); non-cancelled is considered successful
 - Lead time - number of days between reservation date and arrival date  
 - Arrival full date - full date of arrival
 - Arrival date year - arrival year  
 - Arrival date month - month of arrival  
 - Arrival date week number - number of arrival week
 - Arrival date day of month - day of arrival
 - Stays in weekend nights - number of weekends (Saturday or Sunday) that the guest has booked for the stay at the hotel
 - Stays in week nights - number of days (Monday through Friday) that the guest booked to stay at the hotel
 - Stays total nights - total number of nights booked (sum of the previous two columns)
 - Adults - number of adults
 - Children = number of children
 - Babies - number of infants 
 - Meal - the chosen type of food
 - Country - country of client's origin
 - Reserved room type - Reserved room type
 - Assigned room type - type of room received (can differ from booked room)
 - Customer type - booking type
 - Reservation status - last booking status: Canceled - was canceled by client; Check-Out - client checked-in, but has already left the hotel; No-Show - client didn't check-in and informed hotel administration about the reason
 - Reservation status date - status update date
