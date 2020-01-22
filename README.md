# Simulating-Self-Driving-Cabs
# Breif introduction to what this project tries to do

The Smart cab's job is to pick up the passenger at one location and drop them off in another location saving time by taking the shortest route while taking care of passenger’s safety and traffic rules.

There are different aspects that need to be considered here while modeling and Reinforcement Learning solution to this problem: rewards, states, and actions.

Users can book a cab by sending a free text SMS containing source, destination and time of travel. So text mining techniques are used to fetch pickup location, drop location and time of travel from text.

OpenAI Gym’s Taxi v3 environment, Text mining and Q-Learning algorithm were used.

# Details about this project

BACKGROUND 

Cab booking system is the process where renting a cab is automated through an app throughout a city. Using this app,people can book a cab from one location to another location.

Being a cab booking app company, exploiting theunderstanding ofcab supply and demand could increase the efficiency of their service and enhance user experience by minimizing waiting time.

Objective of this project is to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city.

PROCESS FLOW

You will be provided with hourly renting data span of two years. Data is randomly divided into Train and  testset.
You must predict the total count of cabs booked in each hour covered by the test set, using the information available prior to the booking period.
You need to append the train_label dataset to train.csv as ‘Total_booking’ column.


