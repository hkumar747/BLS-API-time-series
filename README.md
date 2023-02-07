# Unemployment Data from BLS

This script pulls in monthly, county-level unemployment data from the United States Bureau of Labor Statistics (BLS) API for unemployment, and does not run against limits. Combines results into a Pandas DataFrame.

It then downloads data from the US Census Bureau API for the counties (you will need a personal API Key). 

Future commits will change parameters: geography, time.
