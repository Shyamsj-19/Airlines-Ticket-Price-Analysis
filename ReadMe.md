# Indian Airlines Ticket Price Analysis

## Objective

This project aims to employ advanced data analytics techniques to explore, analyze, and interpret relevant datasets, with the ultimate goal of providing actionable recommendations to stakeholders, including airlines, travel agencies, and consumers. Key objectives include:

1.Price Trend Identification:
Analyze historical ticket pricing data to identify trends and patterns in the fluctuation of airline ticket prices.
Determine the impact of various factors, such as seasonality, holidays, and demand, on ticket prices.

2.Competitive Pricing Analysis:
Compare and contrast ticket prices among different airlines operating in the Indian market.
Evaluate the competitive landscape to understand how pricing strategies vary across airlines.

3.Route-specific Analysis:
Focus on specific air routes to assess how pricing varies based on destination, distance, and popularity.
Identify routes with notable pricing dynamics and potential factors influencing these variations.

Check out the project [here](https://github.com/Shyamsj-19/Airlines-Ticket-Price-Analysis/blob/master/India%20Airlines%20Ticket%20Price%20Exploratory%20Analysis.ipynb)

## About the dataset

Data is gathered from the Kaggle and considered as secondary data.
The dataset includes details on the ticket booking alternatives available through the website "Easemytrip" for flights between India's top 6 metro areas. The cleaned dataset contains 11 characteristics and 300261 datapoints. Data was gathered in two stages: for business class tickets and for economy class tickets. The site provided a total of 300261 unique flight booking possibilities. 50 days of data were gathered, from February 11 to March 31 of 2022. 
Dataset Link: [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

The various features of the cleaned dataset are explained below:
1) Airline: The airline column contains the name of the airline firm. There are six different airlines, making it a category trait.
2) Flight: The flight code of the aircraft is stored in flight.
3) Source City: City where the flight departs from is a classification feature with 6 distinctive cities.
4) Departure Time: This is a categorical feature that was deduced from time periods being divided into bins. It has six different time labels and stores information about the departure time.
5) Stops: A category feature that holds the number of stops between the source and destination cities and has 3 different values.
6) Arrival Time: This derived categorical feature was developed by binning time intervals. It maintains information regarding the arrival time and has six different time labels.
7) Destination City: The location of the aircraft's landing. It is a classification feature with 6 distinctive cities.
8) Class: A permanent feature that shows the total number of hours needed to travel between cities.
9) Duration: A permanent feature that shows the total number of hours needed to travel between cities.
10)Days Left: The trip date is subtracted from the booking date to arrive at this derived feature.
11) Price: Information about the ticket price is stored in the target variable.

## Power BI Visualization Dashboard

Click on [Power BI Dashboard](https://github.com/Shyamsj-19/Airlines-Ticket-Price-Analysis/blob/master/Indian%20Airline%20Ticket%20Prices%20Dashboard.pdf) to view the dashboard

Using Power BI Dashboard one can quickly get to know ticket prices between different cities flying with different airlines in different classes along with flight duration

## Conclusion

1) 'Air Asia' offers the cheapest flight tickets while flying Economy class while 'Air India' is cheapest while flying Business class.
2) Booking tickets 3-7 weeks before travel will be cheaper than buying them within 3 weeks of travel as prices rise rapidly in 2-20 days period. Tickets can be cheap when bought just 1 day before however they might not be as cheap as when bought more than 3 weeks before
3) Ticket price grow linearly with duration of flight peaking when duration of flight reaches 20 hours. However due to some outliers they again fall for for flights with duration of more than 20 hours. Relation can be approximated by 2nd degree curve
4) Flight departing late at night and arriving early morning or late at night are cheapest.
5) Flight prices increase with increase in number of stops.
6) Delhi offers the cheapest flights while Hyderabad is most expensive city to fly to
