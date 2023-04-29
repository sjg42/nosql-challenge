# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. In this challenge,
I pretend to be contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists
and food critics decide where to focus future articles.

### Part 1: Database and Jupyter Notebook Set Up

The first challenge was to import the provided "establishments.json" into Mongo Compass and set up a Mongo Client using the PyMongo Library.



### Part 2:

Next, I used the Mongo Client in python to make several updates to the establishments collection including:

. Adding a new restaurant to the collection

. Updating a field for a single document

. Updating the datatype of two fields for the entire collection



### Part 3:

I performed analysis for the magazine using Mongo Client functions like .find(), .count_documents, .sort(), .limit() and .aggregation().


## References


UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks 
to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567,
pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
