# Baywheels_SF
Resources:

    - PostgreSQL
    - pgAdmin 4
    - Excel
    - PowerPoint

## Overview

Analysis of Baywheels SF bikeshare data

- Use postgreSQL on pgAdmin4 to analyze Lyft bikeshare data and create visualizations in excel.
- Make suggestions on Distribution, Maintenance, and Model options based on results.
- Communicate 5-8 minute powerpoint presentation of insights.

## Analysis

#### Goals:

![Screen Shot 2022-05-05 at 11 01 12 AM](https://user-images.githubusercontent.com/100544761/166965001-88bfbcac-390c-4ece-8ca6-fcfbdbf7b444.png)

- Clearly defined goals will help guide our analysis

#### Summary Statistics:

![Screen Shot 2022-05-05 at 11 01 35 AM](https://user-images.githubusercontent.com/100544761/166965109-990c90ab-9851-436f-a686-1c2fa7d2ed52.png)

    - Explore data and get a feel for key statistics

#### Distribution:

.![Screen Shot 2022-05-05 at 11 01 55 AM](https://user-images.githubusercontent.com/100544761/166965247-1776fef4-62c4-4934-bbd7-22f14f684f60.png)

- The criteria above display the accumulation/depletion rates per station per E.O.D.  Therefore, it's important to redistribute bicycles around the city to ensure that each station is adequately, but not overly, supplied with bicycles for users.  Also, peering into the timestamp aggregation, we can clearly see which hours see peak activity which indicates effective and ineffective times of the day to perform the distributions.

![Screen Shot 2022-05-05 at 11 13 14 AM](https://user-images.githubusercontent.com/100544761/166966810-5833c77f-f49a-4f2a-b33d-4f56fb7b5eb5.png)

#### Maintenance

![Screen Shot 2022-05-05 at 11 14 27 AM](https://user-images.githubusercontent.com/100544761/166967079-2e543566-5bd9-45f8-a953-40ac7dc2850f.png)

- Best time of year to perform maintenance is Dec-Feb.  We also see how to monitor the usage per bike_id which in turn indicates more grandularly scheduled tune-ups.

#### Bicycle Models

![Screen Shot 2022-05-05 at 11 19 35 AM](https://user-images.githubusercontent.com/100544761/166967954-f449b632-10c6-41a6-8bcb-3aa64026bc82.png)

- Based on user type and trip duration, I suggest at least 4 ride models to offer to our customers for maximum experience.  Subscribers generally take shorter rides (likely because they're local, commuting, or familiar with the system) and could benefit from our road bike or scooter options.  Customers (singular trips) take longer rides as they are likely visitors touring the city or exploring at their leisure which would make the comforts of touring bikes or electric bikes more fitting.

## Conclusion

Using SQL to analyze rideshare data, we've become well acquainted with the lay of the land in terms of operations and have drawn several actionable insights that will help us provide an ever increasing statisfaction for our users interacting with our products and services.  These queries can be actively recycled and refactored to keep offering Baywheels SF a clear and valuable vision for it's future.
