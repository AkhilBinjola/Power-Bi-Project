# Airline Operations Dashboard (Power BI)

An interactive Power BI report that tracks bookings, passengers and routes across airlines, with per-airline access control.

## Business questions

- How do bookings break down by status, and how many tickets are confirmed?
- How many passengers does each airline carry?
- Which airline–destination combinations have the most traffic?
- How many passengers fly on each flight, and which flights are the "best" performers?

## What was built

**1. Data preparation in Power Query**
- Cleaned the flight, passenger and ticket tables.
- Created conditional columns to categorise booking status.
- Set up one-to-many relationships between the tables so filters flow correctly through the model.

**2. DAX measures**
- Confirmed tickets
- Passengers per flight
- A "Best" flights filter measure

**3. Report design**
- Visuals for booking status, passengers by airline, and airline–destination views.
- Slicers for interactive filtering.
- Bookmarks for navigation between views.
- Separate report pages for each airline.

**4. Publishing and security**
- Published to Power BI Service.
- Row-Level Security (RLS) so each airline sees only its own data.
- Scheduled data refresh.

## Skills shown

Power Query, data modelling, DAX, dashboard design, Row-Level Security, Power BI Service.

## Author

Akhil Binjola · [LinkedIn](https://linkedin.com/in/akhilbinjola) · [GitHub](https://github.com/AkhilBinjola)
