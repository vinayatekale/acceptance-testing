The application displays the 5 day weather for a given location.

### Requirements

* Enter city name, get 5 day weather forecast
* Select day (by clicking), get 3 hourly forecast
* Select day again, hide 3 hourly forecast
* Daily forecast should summarise 3 hourly:
  * Most dominant condition
  * Current wind speed and direction
  * Aggregate rainfall
  * Minimum and maximum temperatures
* All values should be rounded down
* Rainfall rounded up (e.g. 0.5mm is 1mm)

We would like the application to be tested against the requirements above. Please rewrite the requirements into a more rigorous format, e.g. BDD feature files, and add any requirements that you think appropriate, such as edge cases or accessibility improvements.

Please write a set of automated tests against those requirements using any test framework of your choice.

The application is running in "test" mode, using a set of test data, matching that which comes from the public API at OpenWeatherMap (http://openweathermap.org/forecast5). There is test data for a number of locations, found in the folder ```src/data```.

You should find that every important part of the HTML produced has been marked with ```data-test``` attributes.

### What we are looking for

This exercise is to examine your technical knowledge, and testing skill. There are no tricks or hidden agendas. We are looking for a demonstration of your experience and skill using current testing technologies and methodologies. Please make sure your code is clear, demonstrates good practices and that the readme.md file explains how to run / build your solution. Also, detail anything further that you would like to achieve with more time. Your solution will form the basis for discussion in subsequent interviews.

### Checklist

Please ensure you have submitted the following:

* A repository containing the requirements and automated tests
* A readme.md explaining
  * How to run / build / test the code
  * Explanation of what could be done with more time
  * Project builds / runs / tests as per instruction

Good luck and thank you for your time - we look forward to seeing your creation.

