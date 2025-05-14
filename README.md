Hi!

This repository contains a (mostly) complete dataset of all pickup trucks produced and sold in the United States since roughly the year 2000. 

Trucks are shown by model, where each entry is specified by its Years Available, Engine, or Transmission specifications. Essentially, this data tracks all engine and transmission options for all truck models, and reports the years that each particular specification is/was offered.

The dataset was created manually, sourcing data primarily from Wikipedia vehicle pages. Edmunds was also used to confirm specific vehicle specifications when necessary. Cars.com was used to confirm US model years, as production years tend to vary by region.

Notes:
  - There may still be some errors, mistakes, misformatting, or missing vehicles here or there.
  - Since I created this in 2025, I chose to mark the end of all models using that year rather than "Present"
  - I tended to leave out Large Trucks with small engine options, such as the Silverado 1500 4.3L V6 which has plenty of solid V8 alternatives, or the Suzuki Equator 2.5L I4 which has the       larger 4.0L V6 option. 
  - I apologize to the true enthusiasts for this, but I opted to report only _automatic_ transmissions when pulling data for consistency. MANY of these trucks have _manual_ options as well.
  - Numerical features, including Displacement, Horsepower, and Torque, are stored as raw numerical values, but formatted to display their respective units. This was done for the sake of   
    data analysis.
