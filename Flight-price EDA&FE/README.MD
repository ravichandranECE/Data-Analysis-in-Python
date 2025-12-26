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
Highest Median Price: 
1) Jet Airways Business has a median price ($\sim 55,000$) significantly higher than the overall dataset maximum 75th percentile ($12,373$). 
2) This category contains the most expensive tickets, driving the overall 'Max' price of $79,512$.
Mid-Range Carriers (Median $\sim 10,000$ to $12,000$):
Air India, Jet Airways (Economy/General), Multiple carriers, Vistara, Vistara Premium economy, and Multiple carriers Premium economy all fall into this tier. Their median prices are close to the overall 75th percentile ($12,373$), indicating they represent the more expensive $25\%$ of typical bookings.
Budget Carriers (Median $\sim 5,000$ to $7,000$):
IndiGo, Spicejet, GoAir, Air Asia, and Trujet cluster in the most affordable tier. Their median prices are close to the overall 25th percentile ($5,277$), suggesting they represent the bulk of budget-friendly bookings.
Skewness: 
The presence of the Jet Airways Business category (with a median of $\sim 55,000$) significantly pulls the overall Mean price ($9,087$) higher than the overall Median price ($8,372$).



##### SUMMARY
📍 Destination City Distribution
The visualizations show the distribution of flights based on their Destination city:
Dominant Destination: Cochin is the most frequent destination, accounting for 42.5% of all flights, with an approximate count of 4,500.
Next Largest Destinations: Bangalore is the second largest destination at 26.9% (approx. 2,900 flights), followed by Delhi at 11.8%.
Remaining Destinations: New Delhi (8.7%), Hyderabad (6.5%), and Kolkata (3.6%) make up the rest of the destinations.


✈️ Source City Distribution
The visualizations show the distribution of flights based on their Source city:
Dominant Source: Delhi is the most frequent source city, accounting for 42.5% of all flights in the dataset, with an approximate count of 4,500.
Next Largest Sources: Kolkata is the second largest source at 26.9% (approx. 2,900 flights), followed by Bangalore at 20.6% (approx. 2,200 flights).
Least Frequent Sources: Flights originating from Mumbai (6.5%) and Chennai (3.6%) are significantly less frequent.


🛑 Total Stops Distribution
The visualizations show the distribution of flights based on the number of total_stops:
Most Common: Flights with 1 stop are the most common, accounting for 52.7% of the dataset, with a count of approximately 5,600.
Second Most Common: Flights with 0 stops (non-stop) are the next most common at 32.7% (approx. 3,500 flights).
Less Common: Flights with 2 stops make up 14.2% (approx. 1,500 flights).
Rarest: Flights with 3 stops and 4 stops are extremely rare, making up less than 0.5% combined (not visibly present in the bar chart).



Jet Airways (Standard/Economy) had the highest total accumulated price (over $40$ million), suggesting it has the highest volume of bookings in the dataset.
Median Price (Second Plot): Jet Airways Business has the highest typical (median) price per ticket ($\sim 55,000$).

Dominant Airline: Jet Airways has the highest total accumulated price by a significant margin, with a value exceeding $4 \times 10^7$ (40 million).
Second Highest: Air India has the second-highest total price, followed closely by Multiple carriers, both falling in the range of approximately $1.5 \times 10^7$ to $2 \times 10^7$ (15-20 million).
Other Major Carriers: IndiGo also shows a substantial total price, close to $1 \times 10^7$ (10 million).
Smaller Totals: Airlines like Spicejet, Vistara, GoAir, and Air Asia have comparatively smaller total prices, all below $1 \times 10^7$.
Negligible Totals: Specialized or smaller categories like Vistara Premium economy, Jet Airways Business, Multiple carriers Premium economy, and Trujet show very low total accumulated prices, barely visible on the scale.
The plot suggests that Jet Airways is either the most frequently booked airline or has the highest fares, leading to the largest overall sum in the dataset.
