# CO2_Emissions_Regression

This is a regression problem in order to predict the CO2 emissions from various cars in Canada. 
The dataset has been derived from https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles.

The initial dataset contains 7386 instances over 12 attributes. 
### Make
The make consists of car brands like Audi, Aston Martin, etc
### Model
* 4WD/4X4 = Four-wheel drive
* AWD = All-wheel drive
* FFV = Flexible-fuel vehicle
* SWB = Short wheelbase
* LWB = Long wheelbase
* EWB = Extended wheelbase
### Vehicle Class
This attribute describes the size of the car from compacts to trucks. 
### Engine Size
### Cylinders
### Transmission
* A = Automatic
* AM = Automated manual
* AS = Automatic with select shift
* AV = Continuously variable
* M = Manual
* 3 - 10 = Number of gears
### Fuel Type
* X = Regular gasoline
* Z = Premium gasoline
* D = Diesel
* E = Ethanol (E85)
* N = Natural gas
### Fuel Consumption
Over 4 separate attributes, we have Fuel Conumption City (L/100 km), Fuel Conumption Hwy (L/100 km), Fuel Conumption Comb (L/100 km) and Fuel Conumption Comb (mpg)
### CO2 Emissions(g/km)
This is our target, and the emissions of CO2 for the fuel consumption.

We are predicting CO2 Emissions(g/km).

This project has been split accordingly.
## Data exploration
* Summary stats
* Missing values
* Data types
* Visualisations

## Data preparation
* Dropping attributes
* Binarising
* Normalising

## Data analysis
* Training
* Testing
* SVR, KNNR, LR
* Predicting
