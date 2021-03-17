# Deep-Learning-analysis-on-Chicago-crime-data
Feed Forward Neural Network to predict, but not be limited to, the primary crime type by month, time of the day, neighborhoods, the correlations between primary crime type and the socioeconomic indicators, and the probability of being arrested in a certain neighborhood. 

X variables and their descriptions (Chicago Crime Dataset):
Block - The partially redacted address where the incident occurred, placing it on the same block as the actual address
Date - Date when the incident occurred
Description - The secondary description of the IUCR code, a subcategory of the primary description 
Location Description - Description of the location where the incident occurred.
Domestic - Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
Beat - Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. Three to five beats make up a police sector, and three sectors make up a police district.
District - Indicates the police district where the incident occurred. See the districts at https://data.cityofchicago.org/d/fthy-xz3r.
Ward- The ward (City Council district) where the incident occurred. See the wards at https://data.cityofchicago.org/d/sp34-6z76.
Community Area - Indicates the community area where the incident occurred. Chicago has 77 community areas. See the community areas at https://data.cityofchicago.org/d/cauq-8yn6.
Year - Year the incident occurred.
Latitude - The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
Longitude - The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
Location - The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.
X variables and their descriptions (Chicago Socioeconomic Dataset):
Community Area Number (For joining purpose)
Community Area Name: The area names are related to the community area numbers.
Percent of Housing Crowded: Percent occupied housing units with more than one person per room.
Percent Households Below Poverty: Percent of households living below the federal poverty level.
Percent Aged 16+ Unemployed: Percent of persons over the age of 16 years that are unemployed.
Percent Aged 25+ Without High School Diploma: Percent of persons over the age of 25 years without a high school education.
Percent Aged Under 18 or Over 64: Percent of the population under 18 or over 64 years of age (i.e., dependency).

Business Relevance:
Support the allocation of city resources, including focused funding, and targeted law enforcement.
Serve as a guide for local community and visitors
Which areas to visit or avoid visiting
Where to purchase or rent a home
Where to open a business
