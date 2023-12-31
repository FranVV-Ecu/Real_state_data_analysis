# Research of advertisements for apartments for sale
## Project description
We have data from the Yandex.Real Estate service - an archive of advertisements about apartments for sale in St. Petersburg and neighboring cities for several years. We need to learn how to determine the market value of real estate objects. The task is to set the parameters. This will allow you to build an automated system: it will track anomalies and fraudulent activity.

For each apartment for sale, two types of data are available. The first is entered by the user, the second is obtained automatically on the basis of map data. For example, distance to the center, airport, nearest park and water body.

## Data description
 - airports_nearest - distance to the nearest airport in meters (m),<br>
 - balcony - number of balconies, <br>
 - ceiling_height - ceiling height (m)<br>
 - cityCenters_nearest - distance to the city center <br>
 - days_exposition - how many days the ad was placed (from publication to removal)<br>
 - first_day_exposition - date of publication<br>
 - floor<br>
 - floors_total - total number of floors in the house<br>
 - is_apartment - apartment (Boolean type)<br>
 - kitchen_area - kitchen area in square meters (m²)<br>
 - last_price - price at the moment of withdrawal from publication<br>
 - living_area - living area in square meters (m²)<br>
 - locality_name - name of the locality<br>
 - open_plan - free layout (Boolean type)<br>
 - parks_around3000 - number of parks within 3 km radius<br>
 - parks_nearest - distance to the nearest park (m)<br>
 - ponds_around3000 - number of water bodies within 3 km radius<br>
 - ponds_nearest - distance to the nearest body of water (m)<br>
  - rooms - number of rooms<br>
  - studio - studio apartment (Boolean type)<br>
  - total_area - area of the apartment in square meters (m²)<br>
  - total_images - number of photos of the apartment in the ad<br><br>
    
    "Explanation: apartments are non-residential premises that do not belong to the housing stock, but have the necessary conditions for living."
