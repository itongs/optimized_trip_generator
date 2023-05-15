# optimized_trip_generator

*Last Updated:* 2023_05_15
*Update By:* itongs

Side-project to see if conventional ML approaches can create a better form of itinerary generator than chat gpt, especially accounting for ratings and better timings, as well as specific locations to try.

*Basic idea of this project:* use google APIs to build an interactive trip optimizing serive that can come up with day trips, date plans, and the like, with the core process built around an optimization process.

*Key Ingredients as intended at present:*
- Ingress module from the google maps api to find locations within a given area
- Ingress module from google reviews api to get ratings and descriptions of businesses in a certain area
- ML approach to match to people's preferences
- optimization module to iterate the best possible itinerary 
- some way of making results visible and interactive in a web app/bucket

More details to follow as more is developed.