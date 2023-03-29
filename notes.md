# Personal notes

## Inspiration: While listening to my dishwasher loudly work its way through another daily load of dishes, I had two thoughts:
1. I should really replace that dishwasher - it's loud, and likely very inefficient given its age
2. I really don't want to *pay* for a new dishwasher. I wonder how long it would take for a newer, more efficient dishwsher to "earn back" its cost through reduced energy and water usage, as well as fewer loads (larger capacity)

So I thought, "this should be a software project!"

## Initial idea:
Quickly create a cost/benefit analysis of a dishwasher, wash, dryer, or other home appliance purchase. Consider the price of the new appliance, energy efficiency, energy savings (specific to geographic region), time to make up the expense, and consumer reviews/ratings

## What is my minimum viable product?
A web app that compares the energy and water cost of running two difference appliances
The app would provide: data about the machines (energy efficieny, price, water usage, capacity, size [needs to be comparable], a selection of machines to compare to the user's machine, a legend or guide for the information being provided,
The user would provide: location data (for localizing costs), their current machine's model

## Where to start?

Probably start by using an API. Home Depot has a strong API I can use to pull information about price, energy usage, and customer rating
Energy data at state level here: [eia API](https://www.eia.gov/opendata/)
More precise utility rate data: [NREL Utitlity Rates API](https://developer.nrel.gov/docs/electricity/utility-rates-v3/)

Start learning here? [https://realpython.com/python-api/](https://realpython.com/python-api/)
