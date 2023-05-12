Taxi Trip Fare Predictions ML Project
This project aims to predict the fare of taxi trips using machine learning techniques. By analyzing various factors such as distance traveled, time of day, and other relevant features, we can build a predictive model that estimates the fare for a given taxi trip.

Dataset
The project utilizes a dataset containing historical taxi trip information. The dataset includes features such as pickup and drop-off locations, trip distances, time of day, and the actual fare amount. The dataset is used for both training and evaluating the machine learning model.

STEPS:
STEPS:
1. Import Libraries
2. Read Data
3. Getting Dataframe Information
4. To find numeric and non numerical cols
5. Filling Missing Values
6. Using cat cols feature encoding
7. Feature reduction on corr
8. Finding X and Y Column
9. Model Building



Data description:
Trip_distance: The elapsed trip distance in miles reported by the taximeter.
Rate_code: The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride
Storeandfwd_flag: This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip
Payment_type: A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip
Fare_amount: The time-and-distance fare calculated by the meter
Extra: Miscellaneous extras and surcharges.
Mta_tax: $0.50 MTA tax that is automatically triggered based on the metered rate in use.
Tip_amount: Tip amount credited to the driver for credit card transactions.
Tolls_amount: Total amount of all tolls paid in the trip.
Imp_surcharge: $0.30 extra charges added automatically to all rides
Total_amount: The total amount charged to passengers. Does not include cash tips
Pickuplocationid: TLC Taxi Zone in which the taximeter was engaged
Dropofflocationid: TLC Taxi Zone in which the taximeter was disengaged
Year: The year in which the taxi trip was taken.
Month: The month on which the taxi trip was taken.
Day: The day on which the taxi trip was taken.
Day_of_week: The day of the week on which the taxi trip was taken
Hour_of_day: Used to determine the hour of the day in 24 hours format
Trip_duration: The total duration of the trip in seconds
calculated_total_amount: The total amount the customer has to pay for the taxi.












