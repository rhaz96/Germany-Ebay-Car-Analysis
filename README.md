# Examining Cars from eBay Kleinanzeigen

This project examines 50,000 used car/used car sales data points from the classifieds section of the German eBay website. The objective is to explore trends in advertising listings, as well as car variables like mileage and price.

![alt text](https://ebay-kleinanzeigen.de/static/img/common/logo/logo-ebay-kleinanzeigen-500x500.png)

### Prerequisites

The analysis is done with R and uses the following packages:

* *dplyr* - dataframe manipulation

* *kableExtra* - formatting tabular output

* *lubridate* - manipulating datetime objects

* *ggplot2* - graphics (well, just one graphic)

* *magrittr* - extends the features of *dplyr*

The data can be found in the *autos.csv* file and has been dirtied by Dataquest for data cleaning purposes.

### Data Dictionary

All of the variables are below:

 * ```dateCrawled``` - When this ad was first crawled. All field-values are taken from this date
 * ```name``` - Name of the car
 * ```seller``` - Whether the seller is private or a dealer
 * ```offerType``` - The type of listing,
 * ```price``` - The price on the ad to sell the car
 * ```abtest``` - Whether the listing is included in an A/B test
 * ```vehicleType``` - The vehicle Type
 * ```yearOfRegistration``` - The year in which which year the car was first registered
 * ```gearbox``` - The transmission type
 * ```powerPS``` - The power of the car in PS
 * ```model``` - The car model name
 * ```kilometer``` - How many kilometers the car has driven
 * ```monthOfRegistration``` - The month in which which year the car was first registered
 * ```fuelType``` - What type of fuel the car uses
 * ```brand``` - The brand of the car
 * ```notRepairedDamage``` - If the car has a damage which is not yet repaired
 * ```dateCreated``` - The date on which the eBay listing was created
 * ```nrOfPictures``` - The number of pictures in the ad
 * ```postalCode``` - The postal code for the location of the vehicle
 * ```lastSeenOnline``` - When the crawler saw this ad last online
