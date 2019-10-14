# XTernDataScienceSolution
Drawing conclusions based on given dataset
# Assumptions
- 1.0 = 1 mile in the coordinate system
- The bus and charge or refill on gas while charging scooters
- Scooters are used less at night
- The mega bus can charge 100 scooters at the same time

# Explanation
  The total time to charge all scooters was calculated to be 64271 hours charging one at a time without factoring in time for the bus transportation time. With the mega bus the time it would take to charge all scooters would be 642.71 hours. 
  
  The total time to charge all scooters using the mega bus is enormous so the best course of action seems to be to keep the charging process ongoing. If the charging process is continuous, charged scooters will continuously be released so there are always available scooters. This solution is better than one that includes trying to charge all the scooters then releasing them all back at once. The recently listed solution would involve taking away the scooters for etremelely long periods of time which would not fix the issue. 
  
  Upon looking at the dispersion of scooters they are all located in 19 groups where they are tightly packed together. The fastest method would then seem to be to target groups at time. The bus should go to one group that way it must only go the distance to the grouping and can pick many up in that area without having to drive again to pick more up. The bus will pick up as many of the lowest charged scooters as possible and travel to another grouping. Once the scooters in the bus are charged the bus will drop the scooters off at the new location, pick up the most uncharged scooters from that area, and then repeat the process. Ideally the bus will travel to a far location as the time to travel from opposing ends of the entire area is much less than what it takes to charge a scooter. This method will ensure that charged scooters are evenly dispersed among the groupings. The bus will be able to stop to charge or get gas while time is being taken to charge. The process will take place during the night to make sure scooters are not completely gone for the users while they are being charged. 

## Data and graphs can be found in the DataExplained.ipynb file
