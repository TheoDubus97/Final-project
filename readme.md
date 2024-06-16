# 294A Final Project: Solar Installations in California
**Theo Dubus**

*This is a Jupyter notebook containing my final project for UC Santa Cruz Econ 294A Python Lab Spring 2024.*

Residential solar power is a rapidly-growing market in California. As the increasing
effects of climate change reveal weaknesses in existing electrical infrastructure and the
importance of decarbonization, many customers are choosing to invest in solar energy generation
systems for clean, reliable electrical service. I will explore demographic factors that may
influence the decision of a household or business whether to adopt solar power at the county
level across California.

#### DATA AND METHODS

I use data derived from multiple sources, including the US Census Bureau
American Community Survey (ACS), the California Association of Realtors (CAR), and the
California Public Utilities Commission (CPUC). The data will contain the following variables:
- County – The index column of this dataset is a list of all 58 counties in California.
- Installations Per Capita – Number of solar installations in each county divided by the
population of that county for a given time period. This variable is derived from a CPUC
database of all residential/commercial/industrial solar installations in California since the
1990s.
- Median Age of Homeowner.
- Education – This is a percentage of the population in each county with some college or
more.
- Race – these are multiple variables for different racial groups as a percentage of
population.
- Median Income
- Percent of home owners/renters.
- Median Home Value from the California Association of Realtors (CAR).
- Median Home Time on the Sales Market, also from the CAR.

I chose these variables to measure factors that would impact the long-term financial decision of a
home or commercial property owner to install solar panels. I am focusing specifically on
property owner attributes and omitting generalized demographics (like median age for a whole
county) to omit renters and children, who do not have decision-making power over property
changes to a home/business.

I use OLS to conduct a cross-sectional analysis of all California counties using data
from 2019. My goal will be to determine which of these factors has the greatest effect on
residential solar adoption in each county.