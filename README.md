# Skyline

Our project is an airline reservation system, which provides a candid interface and an optimized system, 
enabling user to browse for flights and book flight tickets online. The datasets are obtained
from the source “openflights.org”, which provides real-time and accurate data. The data is divided
among two databases, one containing data of domestic flights and the other one containing data for
international flights. The flights operating within the United States are considered as domestic
flights. All other flights have been considered as international flights.
The search page shows the various flights for a one-way trip or a round trip. Search works on
the inputs given by the user namely Source and destinations, type of trip, number of passengers,
category of travel class, type of passengers, etc. The user can select the flight deciding upon the
hours of travel and fare displayed on the search page. After the booking is done, the user can check
for the booking history to see previous bookings for that account. The user can cancel the tickets.
The booking reference is provided for the user to identify the booking.
Finally search results are compared against the naïve approach of Airlines reservation
systems which has all its transactions load in a single database. The experiments and results showed
that Airlines with multiple databases has achieved better performance and scalability.

To run the project:

Use an IDE like Webstorm and start the server. Go to localhost:<your port number mentioned> in the browser to start the application.
