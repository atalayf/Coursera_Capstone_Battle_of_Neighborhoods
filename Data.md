# Data

Two cities will be analysed Manhattan, NY and Philadelphia, PA

For the list of Manhattan neighborhoods, we'll use the file https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/labs/newyork_data.json
For the list of Philadelphia neighborhoods, we'll use "https://github.com/azavea/geo-data/raw/master/Neighborhoods_Philadelphia/Neighborhoods_Philadelphia.zip" file which I found the link from the website
https://www.opendataphilly.org/dataset/philadelphia-neighborhoods/resource/06e8d380-821f-44ce-8718-a0f2f7902318?inner_span=True

To access Foursquare API we'll need neighborhood coordinates.

We have the coordinates of Manhattan neighborhoods in our source file for Manhattan.

We'll use geocoder to get the coordinates for Philadelphia neigborhoods.

We'll use top venues as a features for clustering. For that, we'll use Foursquare API to explore each neighborhood.
