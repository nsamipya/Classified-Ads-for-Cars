# Classified-Ads-for-Cars

Context
Over the course of a year, the data was scraped from a variety of websites in the Czech Republic and Germany.

Content
The scrapers were tuned slowly over the course of the year and some of the sources were completely unstructured, so as a result the data is dirty, there are missing values and some values are very obviously wrong (e.g. phone numbers scraped as mileage etc.)

There are roughly 3,5 Million rows and the following columns:

maker - normalized all lowercase
model - normalized all lowercase
mileage - in KM
manufacture_year
engine_displacement - in ccm
engine_power - in kW
body_type - almost never present, but I scraped only personal cars, no motorcycles or utility vehicles
color_slug - also almost never present
stk_year - year of the last emission control
transmission - automatic or manual
door_count
seat_count
fuel_type - gasoline, diesel, cng, lpg, electric
date_created - when the ad was scraped
datelastseen - when the ad was last seen. Our policy was to remove all ads older than 60 days
price_eur - list price converted to EUR

Inspiration
Which factors determine the price of a car?
With what accuracy can the price be predicted?
Can a model trained on all cars be used to accurately predict prices of models with only a few samples?
