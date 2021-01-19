# eBay_Car_Sales_data_exploring

The aim of this project is to clean the data and analyze the included used car listings. We'll work with a dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website. You can find the original data set here [here](https://www.kaggle.com/orgesleka/used-cars-database)
<br>
The data dictionary provided with data as follows:
- 'dateCrawled' - When this ad was first crawled. All field-values are taken from this date
- 'name' - Name of the car.
- 'seller' - Whether the seller is private or a dealer.
- 'offerType' - The type of listing
- 'price' - The price on the ad to sell the car.
- 'abtest' - Whether the listing is included in an A/B test.
- 'vehicleType' - The vehicle Type.
- 'yearOfRegistration' - The year in which the car was first registered.
- 'gearbox' - The transmission type.
- 'powerPS' - The power of the car in PS.
- 'model' - The car model name.
- 'kilometer' - How many kilometers the car has driven.
- 'monthOfRegistration' - The month in which the car was first registered.
- 'fuelType' - What type of fuel the car uses.
- 'brand' - The brand of the car.
- 'notRepairedDamage' - If the car has a damage which is not yet repaired.
- 'dateCreated' - The date on which the eBay listing was created.
- 'nrOfPictures' - The number of pictures in the ad.
- 'postalCode' - The postal code for the location of the vehicle.
- 'lastSeenOnline' - When the crawler saw this ad last online.

### Findings
- And as a result, Ebay Car Sales site experienced the most number of visitors on 2016-04-06 which is same as the date the most listing created and most crawled. -> I guess 2016-04-06 offered some special oppotunities between customers and seller on Ebay  
- Based on registration year data, we achieve that number of cars registerd the first 50 years before 2018 accounts for nearly 99,6%
- From 2008 to 2018 saw a vast majority of buyers earning for cars which is around 75,8% over the total one
- As we can see, the **average difference** between these **brand's prices** is around \$1000 and **'audi'** is the **most expensive** brand in this industry while the mean value of **maximum traveling distance (odometer_km)** of 'audi' and 'opel' are nearly **the same**
