**Client:** The New York City Taxi and Limousine Commission (TLC), created in 1971, 
is the agency responsible for licensing and regulating New York City's Medallion (Yellow) taxi cabs, 
for-hire vehicles (community-based liveries, black cars and luxury limousines), 
commuter vans, and paratransit vehicles.
        
Over 200,000 TLC licensees complete approximately 1,000,000 trips each day.

**Data Collection**

The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by 
technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

 Source:                    https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
                    
**About Data**

TLC Trip Record Data used contains:

1. **Yellow Taxi Trip Records** (PARQUET) of March 2025 - (4145257, 20)
   
   Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
   
2. **Green Taxi Trip Records** (PARQUET) of March 2025 - (51539, 21)

   Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf

3. **High Volume For-Hire Vehicle Trip Records** (PARQUET) of March 2025 - (20536879, 25)

   Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_hvfhs.pdf

4. **Taxi Zone Lookup Table** (CSV) - (265, 4)

   Columns: LocationID, Borough, Zone, service_zone

Yellow and green taxi trip records include fields capturing pickup and drop-off dates/times, pickup and drop-off locations,
trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Yellow taxis are the only vehicles permitted to respond to a street hail in all five boroughs without a pre-booked ride.

Green taxis may respond to street hails, but only in the areas indicated in green on the map. 
(i.e. above W 110 St/E 96th St in Manhattan and in the boroughs).

New York City is made up of **5 boroughs**, which are like big districts or zones:

Manhattan - Financial, business, tourism hub

Brooklyn - Densely populated, arts & culture

Queens - Diverse, home to JFK & LGA airports

Bronx - Residential, Yankee Stadium

Staten Island - More suburban, ferry access to NYC
