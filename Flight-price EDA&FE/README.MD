### FEATURES
The various features of the cleaned dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.
3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.
4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.
8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
11) Price: Target variable stores information of the ticket price.


#### The bar plot reveals how individual airlines contribute to the overall price distribution.
#### Highest Median Price: 
#### Jet Airways Business has a median price ($\sim 55,000$) significantly higher than the overall dataset maximum 75th percentile ($12,373$). 
#### This category contains the most expensive tickets, driving the overall 'Max' price of $79,512$.
#### Mid-Range Carriers (Median $\sim 10,000$ to $12,000$):
#### Air India, Jet Airways (Economy/General), Multiple carriers, Vistara, Vistara Premium economy, and Multiple carriers Premium economy all fall into this tier. Their median prices are close to the overall 75th percentile ($12,373$), indicating they represent the more expensive $25\%$ of typical bookings.
#### Budget Carriers (Median $\sim 5,000$ to $7,000$):
#### IndiGo, Spicejet, GoAir, Air Asia, and Trujet cluster in the most affordable tier. Their median prices are close to the overall 25th percentile ($5,277$), suggesting they represent the bulk of budget-friendly bookings.
#### Skewness: 
#### The presence of the Jet Airways Business category (with a median of $\sim 55,000$) significantly pulls the overall Mean price ($9,087$) higher than the overall Median price ($8,372$).
