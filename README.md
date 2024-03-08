# Restaurant_Violations

Using two created measures of risk we can assess NYC's health inspection program for potential areas for improvement in restaurant evaluation.

1. GRADED:
There are multiple circumstances when a restaurant may be scored but ungraded after a health inspection in New York City - 
if they recieved a score above 13 (the threshold for an A grade) on their initial inspection, monitoring inspections on restaurants that failed re-inspection, new restaurants not open to public, restaurants wanting to reopen after closing, and investigations of complaints. Subsetting initial inspections we can look for patterns in failing restaurants.

2. RISKY BUSINESS:
A restaurant scoring below 14 points on an inital inspection would not require re-inspection for 11-13 months, whereas scoring 14+ on initial inspection but below 14 on the re-inspection is a 5-7 month inspection cycle, but scoring above 28 points on reinspection is a 3-5 month inspection cycle. From this, we can make the assumption if a restaurant averages more than 3 inspections per year in the data, it is likely repeatedly failing re-inspections, indicating a potentially deeper issue such as inconsistent standards or a lack of upkeep.


Sources:

"DOHMH New York City Restaurant Inspection Results", NYC OpenData, https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/data

How We Score And Grade, nyc.gov, https://www.nyc.gov/assets/doh/downloads/pdf/rii/how-we-score-grade.pdf
