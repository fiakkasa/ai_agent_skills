---
name: Weather Forecast
description: Checks the weather for a location and provides a forecast for the number of specified days.
invokable: true
---

# Weather Forecast

This skill enables the ability to check the weather for a location and provide a forecast for the number of specified days.

## Process

1. Prompt the user for a location and number of days
2. Call tool #weather_forecast with the location and number of days as parameters
3. List the response as a table
4. Highlight today's conditions
5. Use emoji's to denote weather conditions next to the description
6. Provide a recommendation for 3 days after today
