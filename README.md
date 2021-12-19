# Gmaps API

This repository is for a project called python-api-challenge.

I started by creating a Python script to visualise the weather of 500+ cities across the world of varying distance from the equator.
I have created a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

I ran linear regression on each relationship below;

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

My final notebook includes:

- Randomly selected unique (non-repeat) cities based on latitude and longitude.
- Weather check on each of the cities using a series of successive API calls.
- A print log of each city as it's being processed with the city number and city name.
- A CSV of all retrieved data and a PNG image for each scatter plot.
