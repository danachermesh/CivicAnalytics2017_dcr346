## Problem set #1
### Problem Category (3) Identifying at-risk populations
# How does certificate of occupancy issuance correlates with building violation complaints?

#### _Backround_
A Certificate of Occupancy (CO) states a building’s legal use and/or type of permitted occupancy. New buildings must have a CO, and existing buildings must have a current or amended CO when there is a change in use, egress or type of occupancy.  (from [nyc.gov](https://www1.nyc.gov/site/buildings/homeowner/certificate-of-occupancy.page))


#### _Research Objectives_
My motivation for this HW assignment was to analyze the impact of the number of residential certificates of occupancy issuance on the number of building violation complaints, if any, and by this to identify areas that should get more attention regarding building codes and building use validation.

I pre assumed that an area with a very low number of certificates of occupancy issued over a year (meaning, an area that is less developing / renewing) will also have a relatively large number of building violation (illegal conversion) complaints. 
I also guessed there will be anomalies, so as highly renewing areas with large number of CO's and a large number of building violation complaints.


#### _Data Inventory_
The **building violation complaints data** is taken from 311 open data; The certificate of occupancy issuance data is taken from DOB open data. All data in this research rely on data from year 2016 and were cleaned to focus only in residential information. Any personal information was excluded from the datasets pre-importing. 

The 311 complaints data were filtered to include **Building/Use complaint type** only, and then filtered again by descriptor to include **illegal conversion** of non residential buildings/units to residential without obtaining approval from the New York City Department of Buildings (excluding illegal vehicle storage, for example). 

For more information regarding illegal conversion: [nyc.gov](https://www1.nyc.gov/site/buildings/renter/illegal-conversions-vacates.page)

The **DOB Certificate of Occupancy data** were cleaned from any unuseful / private data. Both **temporary** and **final** certificate types were included. 

_____

For the full analysis and code please see the [Ipyhton Notebook attached](https://github.com/danachermesh/CivicAnalytics2017_dcr346/blob/master/Problem%20set%20-1/dcr346_CAproblemset1.ipynb).
_____

### Conclusion and optional future research 
The analysis turned to be insufficient to provide a predictive model for the chosen question.

An optional interesting factor to be included in future relevant research could be, in my opinion, averaged income of every zip code, excluding very high income areas from the analysis. The assumption behind this approace is that very wealthy people, in their home in which they live, do not usually add residential units and/or converting non-residential area to residential. Moreover, they do not complaint about these kind of data around their homes.

By this, I imagine, we might find a stronger, more reliable correlation between the two sets of data.
