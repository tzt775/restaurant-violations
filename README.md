# Restaurant_Violations

Using two created measures of risk we can assess NYC's health inspection program for potential areas for improvement in restaurant evaluation.

***

1. RISKY BUSINESS:
A restaurant scoring below 14 points on an inital inspection would not require re-inspection for 11-13 months, whereas scoring 14+ on initial inspection but below 14 on the re-inspection is a 5-7 month inspection cycle, but scoring above 28 points on reinspection is a 3-5 month inspection cycle. From this, we can make the assumption if a restaurant averages more than 3 inspections per year in the data, it is likely repeatedly failing re-inspections, indicating a potentially deeper issue such as inconsistent standards or a lack of upkeep.

2. SECOND CHANCE:
1/3 of restaurants fail their initial inspection, and about 1/3 of those also fail their reopening/re-inspection.
By subsetting initial inspections we can look for patterns in failing restaurants. A text comparison for violation codes between the initial inspection and reinspection to see if anything changed in the grace period between inspections for restaurants that failed consecutively. And cluster analysis to see if there are any underlying similarities between restaurants that pass initial inspection vs restaurants that don't.


Sources:

"DOHMH New York City Restaurant Inspection Results", NYC OpenData, https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/data

How We Score And Grade, nyc.gov, https://www.nyc.gov/assets/doh/downloads/pdf/rii/how-we-score-grade.pdf
